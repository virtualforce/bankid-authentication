# Integrating LiveChat API - The good, the bad and the ugly
Faisal Mumtaz, Software Engineer, Virtual Force Pvt. Ltd.

We recently worked on an application that had chat as a major component. We chose to work with Meteor JS for the application but decided that for release 1, we will integrate Livechat on one end. The application required an operator module that was somewhat available through Livechat so we decided to use it for release 1 and then implement our own Operator module in Release 2. Here are some of my ramblings about the good, the bad and the ugly things that happened to us because of that decision:

## The Good
We evaluated a number of ticketing system and operator chat solutions but found that Livechat was the best in terms of availability of a chat API. We compared [zendesk](http://www.zendesk.com), [freshdesk](http://www.freshdesk.com) etc. and found good API documentation as well but couldn not find APIs for chat. For that reason we chose Livechat API.

After some research we started playing with it and were easily able to create a sample app that would work with Livechat. That was really good. We have a pre-built Operator module, a ticketing system and our chat worked.

## The Bad (items that were difficult but we figured out a workaround)
Livechat had a really good API but there were limitations. 

### Problem 1
LiveChat is based around visitor ID instead of a recurring chat ID. Every chat started with the same visitor ID, opens in the same window on the agent side and has it's history maintained by livechat (which the agent can view by scrolling up in that window). To have different conversations or chats started by the same visitor, you need to have different visitor IDs. We ended up having to use visitor IDs as our task IDs. This chat has it's separate chat history maintained at live chat and can be assigned to different agents depending on the topic of the chat.

### Problem 2
When a ticket is created, it only saves chat transcript for that particular session at the time of creation. Any chat history from the previous or any subsequent sessions, has to be manually copied over to the ticket. There is no API to update the ticket so it has to be done manually.

### Problem 3
There is no webhook for ticket update; be it a new message in the ticket or it's status getting updated. So we have to manually poll the ticket info API and get any new messages sent by the agent (e.g. to implement push notifications).

### Problem 4
In order to receive new messages from a chat, we have to poll the an API for chat. If the polling stops for ~15 seconds at least (e.g. due to network failure), livechat closes the chat session and then there is no way for the agent to respond to the visitor other than through a ticket. In this case, the visitor must start a new chat session to continue chatting with the agent. Since, there is no API to update a ticket, the visitor cannot respond to an agent through a ticket either (other than by replying to the automatically generated email from a ticket update).

### Problem 5
Messages don't have unique IDs on livechat and are prone to duplication if the message list is not handled carefully on the client side considering the poll based nature of chat API.

## The Ugly (items that became ugly for us)
* The online and offline mode

## Conclusion
Well this was just to share our particular experience with the Livechat API and in no way meant to shade it. If anyone else found a way to resolve these issues, we would love to hear about it. 
### References

 * [markdown editor](https://jbt.github.io/markdown-editor/)
 * [Live Chat API](https://developers.livechatinc.com/rest-api/)