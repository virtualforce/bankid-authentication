



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-3c1694fab1568340f2e75b26efa1f55d97c5153364a7357e9e1104c718ff1a2f.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-3e95d73eb454e0099947df00d91ab0dbfc6b10be69dd5daf5de7aeb676580d20.css" media="all" rel="stylesheet" />
    
    
    
    

    <link as="script" href="https://assets-cdn.github.com/assets/frameworks-f8175c23360b42a4eb18b2319fefeae252cfeea482fb804356f4136a52bfddb3.js" rel="preload" />
    
    <link as="script" href="https://assets-cdn.github.com/assets/github-1502104f450cb05859f99b57e29782e071e3fb240e237adb8cbf17ebbdb271c7.js" rel="preload" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>bankid-authentication/README.md at 5b6fa35ea429faea475ec390ad585dae48eac64f · virtualforce/bankid-authentication</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="https://avatars2.githubusercontent.com/u/18654062?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="virtualforce/bankid-authentication" name="twitter:title" /><meta content="bankid-authentication - This repository contains sample code for node.js based Relaying Party (RP) for European bankid systems" name="twitter:description" />
      <meta content="https://avatars2.githubusercontent.com/u/18654062?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="virtualforce/bankid-authentication" property="og:title" /><meta content="https://github.com/virtualforce/bankid-authentication" property="og:url" /><meta content="bankid-authentication - This repository contains sample code for node.js based Relaying Party (RP) for European bankid systems" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/NDYyOTM3NDozZmI0MWE3NTUxYzBmNjBlY2IzNDJkMjNmODkxMTg3YjpjZWEzYjU2NjQzMjJjODg1NTE5MTFlZjc2MWE1YTczNGE1MmI0ODAzOGU5ZWUzMTBkNmMyOWVmZGRjYjBlYWQ5--5bd019623ec6601cb100c59db5c5ca1156c3343b">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="CAA6A3B4:7A00:9ED146:5735870E" name="octolytics-dimension-request_id" /><meta content="4629374" name="octolytics-actor-id" /><meta content="JavedZahoor" name="octolytics-actor-login" /><meta content="2e819c89421f75553e4b3100fd998f5e5452c8a9284fb5ca8b13709adf600c69" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="JavedZahoor">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="ZGZhMzI3M2QxZWI3NWE4OGQzZmM4NTc1ZjA1NmJjMTYzY2MwM2M0Y2E1MzI1ODAwZjAyNzczMTFlOTA0NTRkOXx7InJlbW90ZV9hZGRyZXNzIjoiMjAyLjE2Ni4xNjMuMTgwIiwicmVxdWVzdF9pZCI6IkNBQTZBM0I0OjdBMDA6OUVEMTQ2OjU3MzU4NzBFIiwidGltZXN0YW1wIjoxNDYzMTI1Nzc0fQ==">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="13451b369e3ff14b65cecc498cfcea9aa2d66066" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="22dd3b7ce1aea89995da9e98ee8a9677">
    

      
  <meta name="description" content="bankid-authentication - This repository contains sample code for node.js based Relaying Party (RP) for European bankid systems">
  <meta name="go-import" content="github.com/virtualforce/bankid-authentication git https://github.com/virtualforce/bankid-authentication.git">

  <meta content="18654062" name="octolytics-dimension-user_id" /><meta content="virtualforce" name="octolytics-dimension-user_login" /><meta content="57950703" name="octolytics-dimension-repository_id" /><meta content="virtualforce/bankid-authentication" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="57950703" name="octolytics-dimension-repository_network_root_id" /><meta content="virtualforce/bankid-authentication" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/virtualforce/bankid-authentication/commits/5b6fa35ea429faea475ec390ad585dae48eac64f.atom" rel="alternate" title="Recent Commits to bankid-authentication:5b6fa35ea429faea475ec390ad585dae48eac64f" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/virtualforce/bankid-authentication/blob/5b6fa35ea429faea475ec390ad585dae48eac64f/README.md" data-pjax-transient>
  </head>


  <body class="logged-in   env-production windows vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/orgs/virtualforce/dashboard" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59 0.4 0.07 0.55-0.17 0.55-0.38 0-0.19-0.01-0.82-0.01-1.49-2.01 0.37-2.53-0.49-2.69-0.94-0.09-0.23-0.48-0.94-0.82-1.13-0.28-0.15-0.68-0.52-0.01-0.53 0.63-0.01 1.08 0.58 1.23 0.82 0.72 1.21 1.87 0.87 2.33 0.66 0.07-0.52 0.28-0.87 0.51-1.07-1.78-0.2-3.64-0.89-3.64-3.95 0-0.87 0.31-1.59 0.82-2.15-0.08-0.2-0.36-1.02 0.08-2.12 0 0 0.67-0.21 2.2 0.82 0.64-0.18 1.32-0.27 2-0.27 0.68 0 1.36 0.09 2 0.27 1.53-1.04 2.2-0.82 2.2-0.82 0.44 1.1 0.16 1.92 0.08 2.12 0.51 0.56 0.82 1.27 0.82 2.15 0 3.07-1.87 3.75-3.65 3.95 0.29 0.25 0.54 0.73 0.54 1.48 0 1.07-0.01 1.93-0.01 2.2 0 0.21 0.15 0.46 0.55 0.38C13.71 14.53 16 11.53 16 8 16 3.58 12.42 0 8 0z"></path></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/virtualforce/bankid-authentication/search" class="js-site-search-form" data-scoped-search-url="/virtualforce/bankid-authentication/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
      <div class="header-search-scope">This repository</div>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        tabindex="1"
        autocapitalize="off">
    </label>
</form></div>


      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
    
    <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-channel="notification-changed-v2:4629374" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status "></span>
        <svg aria-hidden="true" class="octicon octicon-bell" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 12v1H0v-1l0.73-0.58c0.77-0.77 0.81-2.55 1.19-4.42 0.77-3.77 4.08-5 4.08-5 0-0.55 0.45-1 1-1s1 0.45 1 1c0 0 3.39 1.23 4.16 5 0.38 1.88 0.42 3.66 1.19 4.42l0.66 0.58z m-7 4c1.11 0 2-0.89 2-2H5c0 1.11 0.89 2 2 2z"></path></svg>
</a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"></path></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>

  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="virtualforce">This organization</span>
  </div>
  <a class="dropdown-item" href="/orgs/virtualforce/invitations/new" data-ga-click="Header, invite someone">
    Invite someone
  </a>
  <a class="dropdown-item" href="/orgs/virtualforce/new-team" data-ga-click="Header, create new team">
    New team
  </a>
  <a class="dropdown-item" href="/organizations/virtualforce/repositories/new" data-ga-click="Header, create new organization repository, icon:repo">
    New repository
  </a>


  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="virtualforce/bankid-authentication">This repository</span>
  </div>
    <a class="dropdown-item" href="/virtualforce/bankid-authentication/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>
    <a class="dropdown-item" href="/virtualforce/bankid-authentication/settings/collaboration" data-ga-click="Header, create new collaborator">
      New collaborator
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/JavedZahoor"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@JavedZahoor" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/4629374?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">JavedZahoor</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/JavedZahoor" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
          <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
            Explore
          </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>


          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="13451b369e3ff14b65cecc498cfcea9aa2d66066" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="kuiLdT0dqwTc7jvXgpAz6BgI5WWz8BYJ9ALgFZF1H5NVIIHlth4urG2cU4DvddQyeFjzhfFv/3/Faov53909SA==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="13451b369e3ff14b65cecc498cfcea9aa2d66066" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="j+oaVDcrMV7GegNZFqCi2PRzGujhzunKvE7g7uqp1AomZwAYT4FkBhEGRB+vnJw+x/ZD+Jojvde8BwYbTXI4qw==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="57950703" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/virtualforce/bankid-authentication/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
              Unwatch
            </span>
          </a>
          <a class="social-count js-social-count" href="/virtualforce/bankid-authentication/watchers">
            3
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6c4.94 0 7.94-6 7.94-6S13 2 8.06 2z m-0.06 10c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4z m2-4c0 1.11-0.89 2-2 2s-2-0.89-2-2 0.89-2 2-2 2 0.89 2 2z"></path></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8 2.81v10.38c0 0.67-0.81 1-1.28 0.53L3 10H1c-0.55 0-1-0.45-1-1V7c0-0.55 0.45-1 1-1h2l3.72-3.72c0.47-0.47 1.28-0.14 1.28 0.53z m7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06 1.97 1.97-1.97 1.97 1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06-1.97-1.97 1.97-1.97z"></path></svg>
                      Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/virtualforce/bankid-authentication/unstar" class="starred" data-form-nonce="13451b369e3ff14b65cecc498cfcea9aa2d66066" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="yo08HOO5Sn6ArWrlANTjvqHr7G6PnD3mro12Xj43hzZebyYhPcqBVvpJgoWU4lrbqqSptanyQWLHbv4RwPtlJg==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar virtualforce/bankid-authentication"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-0.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14l4.33-2.33 4.33 2.33L10.4 9.26 14 6z"></path></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/virtualforce/bankid-authentication/stargazers">
          1
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/virtualforce/bankid-authentication/star" class="unstarred" data-form-nonce="13451b369e3ff14b65cecc498cfcea9aa2d66066" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Mj42KKw1/9lgyDWpqnbD54YALeqaCWcUC8qHBL6uX9EDXsrelAdSItlfQvMy8iSRJS4X8fLgpG3BmgHLe8bGGg==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star virtualforce/bankid-authentication"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-0.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14l4.33-2.33 4.33 2.33L10.4 9.26 14 6z"></path></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/virtualforce/bankid-authentication/stargazers">
          1
        </a>
</form>  </div>

  </li>

  <li>
          <a href="#fork-destination-box" class="btn btn-sm btn-with-count"
              title="Fork your own copy of virtualforce/bankid-authentication to your account"
              aria-label="Fork your own copy of virtualforce/bankid-authentication to your account"
              rel="facebox"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1c-1.11 0-2 0.89-2 2 0 0.73 0.41 1.38 1 1.72v1.28L5 8 3 6v-1.28c0.59-0.34 1-0.98 1-1.72 0-1.11-0.89-2-2-2S0 1.89 0 3c0 0.73 0.41 1.38 1 1.72v1.78l3 3v1.78c-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72V9.5l3-3V4.72c0.59-0.34 1-0.98 1-1.72 0-1.11-0.89-2-2-2zM2 4.2c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z m3 10c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z m3-10c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z"></path></svg>
            Fork
          </a>

          <div id="fork-destination-box" style="display: none;">
            <h2 class="facebox-header" data-facebox-id="facebox-header">Where should we fork this repository?</h2>
            <include-fragment src=""
                class="js-fork-select-fragment fork-select-fragment"
                data-url="/virtualforce/bankid-authentication/fork?fragment=1">
              <img alt="Loading" height="64" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" width="64" />
            </include-fragment>
          </div>

    <a href="/virtualforce/bankid-authentication/network" class="social-count">
      0
    </a>
  </li>
</ul>

    <h1 class="entry-title public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M4 9h-1v-1h1v1z m0-3h-1v1h1v-1z m0-2h-1v1h1v-1z m0-2h-1v1h1v-1z m8-1v12c0 0.55-0.45 1-1 1H6v2l-1.5-1.5-1.5 1.5V14H1c-0.55 0-1-0.45-1-1V1C0 0.45 0.45 0 1 0h10c0.55 0 1 0.45 1 1z m-1 10H1v2h2v-1h3v1h5V11z m0-10H2v9h9V1z"></path></svg>
  <span class="author" itemprop="author"><a href="/virtualforce" class="url fn" rel="author">virtualforce</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/virtualforce/bankid-authentication" data-pjax="#js-repo-pjax-container">bankid-authentication</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/virtualforce/bankid-authentication" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /virtualforce/bankid-authentication" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M9.5 3l-1.5 1.5 3.5 3.5L8 11.5l1.5 1.5 4.5-5L9.5 3zM4.5 3L0 8l4.5 5 1.5-1.5L2.5 8l3.5-3.5L4.5 3z"></path></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/virtualforce/bankid-authentication/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /virtualforce/bankid-authentication/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7S10.14 13.7 7 13.7 1.3 11.14 1.3 8s2.56-5.7 5.7-5.7m0-1.3C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7S10.86 1 7 1z m1 3H6v5h2V4z m0 6H6v2h2V10z"></path></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/virtualforce/bankid-authentication/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /virtualforce/bankid-authentication/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 11.28c0-1.73 0-6.28 0-6.28-0.03-0.78-0.34-1.47-0.94-2.06s-1.28-0.91-2.06-0.94c0 0-1.02 0-1 0V0L4 3l3 3V4h1c0.27 0.02 0.48 0.11 0.69 0.31s0.3 0.42 0.31 0.69v6.28c-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72z m-1 2.92c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2zM4 3c0-1.11-0.89-2-2-2S0 1.89 0 3c0 0.73 0.41 1.38 1 1.72 0 1.55 0 5.56 0 6.56-0.59 0.34-1 0.98-1 1.72 0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.73-0.41-1.38-1-1.72V4.72c0.59-0.34 1-0.98 1-1.72z m-0.8 10c0 0.66-0.55 1.2-1.2 1.2s-1.2-0.55-1.2-1.2 0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2z m-1.2-8.8c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z"></path></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/virtualforce/bankid-authentication/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /virtualforce/bankid-authentication/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M2 5h4v1H2v-1z m0 3h4v-1H2v1z m0 2h4v-1H2v1z m11-5H9v1h4v-1z m0 2H9v1h4v-1z m0 2H9v1h4v-1z m2-6v9c0 0.55-0.45 1-1 1H8.5l-1 1-1-1H1c-0.55 0-1-0.45-1-1V3c0-0.55 0.45-1 1-1h5.5l1 1 1-1h5.5c0.55 0 1 0.45 1 1z m-8 0.5l-0.5-0.5H1v9h6V3.5z m7-0.5H8.5l-0.5 0.5v8.5h6V3z"></path></svg>
      Wiki
</a>

  <a href="/virtualforce/bankid-authentication/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /virtualforce/bankid-authentication/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0V10h3.6L4.5 8.2l0.9 5.4L9 8.5l1.6 1.5H14V8H11.5z"></path></svg>
    Pulse
</a>
  <a href="/virtualforce/bankid-authentication/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /virtualforce/bankid-authentication/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M16 14v1H0V0h1v14h15z m-11-1H3V8h2v5z m4 0H7V3h2v10z m4 0H11V6h2v7z"></path></svg>
    Graphs
</a>
    <a href="/virtualforce/bankid-authentication/settings" class="js-selected-navigation-item reponav-item" data-selected-links="repo_settings repo_branch_settings hooks /virtualforce/bankid-authentication/settings">
      <svg aria-hidden="true" class="octicon octicon-gear" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 8.77V7.17l-1.94-0.64-0.45-1.09 0.88-1.84-1.13-1.13-1.81 0.91-1.09-0.45-0.69-1.92H6.17l-0.63 1.94-1.11 0.45-1.84-0.88-1.13 1.13 0.91 1.81-0.45 1.09L0 7.23v1.59l1.94 0.64 0.45 1.09-0.88 1.84 1.13 1.13 1.81-0.91 1.09 0.45 0.69 1.92h1.59l0.63-1.94 1.11-0.45 1.84 0.88 1.13-1.13-0.92-1.81 0.47-1.09 1.92-0.69zM7 11c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3z"></path></svg>
      Settings
</a>
</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/virtualforce/bankid-authentication/blob/5b6fa35ea429faea475ec390ad585dae48eac64f/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:c82fb519bf6d365cc1024ea631da21f7 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title=""
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Tree:</i>
    <span class="js-select-button css-truncate-target">5b6fa35ea4</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/virtualforce/bankid-authentication/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5L4 13 0 9l1.5-1.5 2.5 2.5 6.5-6.5 1.5 1.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="master">
                master
              </span>
            </a>
        </div>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/virtualforce/bankid-authentication/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" data-form-nonce="13451b369e3ff14b65cecc498cfcea9aa2d66066" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="TLaUbqwEyV2zS8ugdiPZGmJDtdcW0hs08IPY9xdxCeo6vM6bKUULihCyirTJ1pgIiREZPzSu+Nte/KWlavWlDA==" /></div>
          <svg aria-hidden="true" class="octicon octicon-git-branch select-menu-item-icon" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M10 5c0-1.11-0.89-2-2-2s-2 0.89-2 2c0 0.73 0.41 1.38 1 1.72v0.3c-0.02 0.52-0.23 0.98-0.63 1.38s-0.86 0.61-1.38 0.63c-0.83 0.02-1.48 0.16-2 0.45V4.72c0.59-0.34 1-0.98 1-1.72 0-1.11-0.89-2-2-2S0 1.89 0 3c0 0.73 0.41 1.38 1 1.72v6.56C0.41 11.63 0 12.27 0 13c0 1.11 0.89 2 2 2s2-0.89 2-2c0-0.53-0.2-1-0.53-1.36 0.09-0.06 0.48-0.41 0.59-0.47 0.25-0.11 0.56-0.17 0.94-0.17 1.05-0.05 1.95-0.45 2.75-1.25s1.2-1.98 1.25-3.02h-0.02c0.61-0.36 1.02-1 1.02-1.73zM2 1.8c0.66 0 1.2 0.55 1.2 1.2s-0.55 1.2-1.2 1.2-1.2-0.55-1.2-1.2 0.55-1.2 1.2-1.2z m0 12.41c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z m6-8c-0.66 0-1.2-0.55-1.2-1.2s0.55-1.2 1.2-1.2 1.2 0.55 1.2 1.2-0.55 1.2-1.2 1.2z"></path></svg>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘5b6fa35’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="5b6fa35ea429faea475ec390ad585dae48eac64f">
            <input type="hidden" name="path" id="path" value="README.md">
</form>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/virtualforce/bankid-authentication/find/5b6fa35ea429faea475ec390ad585dae48eac64f"
          class="js-pjax-capture-input btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/virtualforce/bankid-authentication/tree/5b6fa35ea429faea475ec390ad585dae48eac64f"><span>bankid-authentication</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>

<include-fragment class="commit-tease" src="/virtualforce/bankid-authentication/contributors/5b6fa35ea429faea475ec390ad585dae48eac64f/README.md">
  <div>
    Fetching contributors&hellip;
  </div>

  <div class="commit-tease-contributors">
    <img alt="" class="loader-loading left" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" />
    <span class="loader-error">Cannot retrieve contributors at this time</span>
  </div>
</include-fragment>
<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/virtualforce/bankid-authentication/raw/5b6fa35ea429faea475ec390ad585dae48eac64f/README.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/virtualforce/bankid-authentication/blame/5b6fa35ea429faea475ec390ad585dae48eac64f/README.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/virtualforce/bankid-authentication/commits/5b6fa35ea429faea475ec390ad585dae48eac64f/README.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           aria-label="You must be on a branch to open this file in GitHub Desktop">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15 2H1c-0.55 0-1 0.45-1 1v9c0 0.55 0.45 1 1 1h5.34c-0.25 0.61-0.86 1.39-2.34 2h8c-1.48-0.61-2.09-1.39-2.34-2h5.34c0.55 0 1-0.45 1-1V3c0-0.55-0.45-1-1-1z m0 9H1V3h14v8z"></path></svg>
        </a>

        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be on a branch to make or propose changes to this file">
          <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M0 12v3h3l8-8-3-3L0 12z m3 2H1V12h1v1h1v1z m10.3-9.3l-1.3 1.3-3-3 1.3-1.3c0.39-0.39 1.02-0.39 1.41 0l1.59 1.59c0.39 0.39 0.39 1.02 0 1.41z"></path></svg>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be on a branch to make or propose changes to this file">
          <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M10 2H8c0-0.55-0.45-1-1-1H4c-0.55 0-1 0.45-1 1H1c-0.55 0-1 0.45-1 1v1c0 0.55 0.45 1 1 1v9c0 0.55 0.45 1 1 1h7c0.55 0 1-0.45 1-1V5c0.55 0 1-0.45 1-1v-1c0-0.55-0.45-1-1-1z m-1 12H2V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9z m1-10H1v-1h9v1z"></path></svg>
        </button>
  </div>

  <div class="file-info">
      435 lines (337 sloc)
      <span class="file-info-divider"></span>
    28.4 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-implementing-two-factor-authentication-using-bankid" class="anchor" href="#implementing-two-factor-authentication-using-bankid" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Implementing Two Factor Authentication using BankID</h1>

<p>Umer Asif, Assistant Software Engineer, Virtual Force Pvt. Ltd.</p>

<h2><a id="user-content-what-is-bankid-system" class="anchor" href="#what-is-bankid-system" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>What is BankID System</h2>

<p>The BankID system is a leading electronic identification solution in Nordic/Scandinavian countries for two factor authentication. The mechanism allows companies, banks and government agencies to authenticate and conclude agreements with individuals over the internet.</p>

<p>It has been developed and implemented by a large number of banks. The system contains and protects a user’s sensitive information such as contact details, email address, phone number, bank account number.</p>

<p>The BankID system is a two-step verification mechanism. The user can install the BankID app on either his mobile phone or personal computer. This application will provide the user with a “personal number” for any website/client that implements BankID system in order to verify his identity. It will give information about the user’s first name, last name, complete name and the personal number.</p>

<p>For development, the BankID system offers a testing service which can be accessed <a href="https://demo.bankid.com/">here</a></p>

<p>Throughout this document, the term BankID will be used in three contexts:</p>

<ul>
<li>BankID system: this refers to the system or the mechanism of BankID.</li>
<li>BankID app: this refers to the mobile/desktop application of the BankID system.</li>
<li>BankID personal number: This refers to the ‘personal number’ or ID generated by BankID system.</li>
</ul>

<h2><a id="user-content-obtaining-a-new-personal-code--bankid-personal-number" class="anchor" href="#obtaining-a-new-personal-code--bankid-personal-number" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Obtaining a New Personal Code &amp; BankID Personal Number</h2>

<p>In order to generate a new personal code and BankID personal number, follow these steps:</p>

<ul>
<li>Log on to <a href="https://demo.bankid.com">https://demo.bankid.com</a> </li>
<li>As demonstrated in Figure 1, click on the “Generate Code” tab on the red highlighted section of the page</li>
</ul>

<p><a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure1.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure1.png" alt="Figure 1" title="Figure 1" style="max-width:100%;"></a></p>

<ul>
<li>A new page will open as shown in Figure 1.2. Continue by providing the credentials: organisation name, project name, your first name, last name and a valid email.</li>
<li><p>Click “Order code”. 
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure1.2.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure1.2.png" alt="Figure 1.2" title="Figure 1.2" style="max-width:100%;"></a></p></li>
<li><p>The BankID system will send you a code on your given email. Check your email and copy the string after  “är:” Go back to the page demo page (Figure 1). Paste the copied string in the text field of the highlighted section and click “Log In.”
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure1a.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure1a.png" alt="Figure 1a" title="Figure 1a" style="max-width:100%;"></a></p></li>
<li><p>A new page will open (Figure 1.3). Click on “Issue” tab. 
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure1.3.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure1.3.png" alt="Figure 1.3" title="Figure 1.3" style="max-width:100%;"></a></p></li>
<li><p>A new page will open (Figure 1.4), asking you to enter your desired BankID personal number. The personal number you select must comply with the Luhn algorithm in order to be accepted. You could use <a href="http://planetcalc.com/2464/">http://planetcalc.com/2464/</a> to generate a unique personal number that complies with Luhn algorithm. </p></li>
<li><p>Type in your BankID personal number in the text field under “Issue Mobile BankID” if you want to install the system and verify it using mobile. Or if you wish to use the BankID for a desktop application, then type in your BankID personal number in the text field under “Issue BankID on file”. Click “Issue”. Since using mobile BankID is more common, we would select that in our example.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure1.4.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure1.4.png" alt="Figure 1.4" title="Figure 1.4" style="max-width:100%;"></a></p></li>
<li><p>Once you click “Issue”, the system will assess your personal number against Luhn algorithm. If it is acceptable, a pop-up screen will open with an activation code. (Figure 1.5)
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure1.5.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure1.5.png" alt="Figure 1.5" title="Figure 1.5" style="max-width:100%;"></a></p></li>
</ul>

<h2><a id="user-content-setting-up-the-mobile-app" class="anchor" href="#setting-up-the-mobile-app" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Setting Up the Mobile App</h2>

<p>Before we continue, it is important to first install the BankID app on your Android phone. Follow these steps:</p>

<ul>
<li><p>Log on to <a href="https://www.bankid.com/bankid-i-dina-tjanster/rp-info">https://www.bankid.com/bankid-i-dina-tjanster/rp-info</a> and download the android app from the page shown in Figure 2.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure2.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure2.png" alt="Figure 2" title="Figure 2" style="max-width:100%;"></a></p></li>
<li><p>Once you have downloaded and installed this .apk, activate it using the personal number and activation code on your mobile.</p></li>
</ul>

<p><a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure2.1.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure2.1.png" alt="Figure 2.1" title="Figure 2.1" style="max-width:100%;"></a></p>

<ul>
<li><p>On subsequent login attempts, a screen will appear on your phone, with a tab to enter a new Mobile Bank ID.</p></li>
<li><p>The app will ask you to enter your BankID personal number and your activation code.</p></li>
<li><p>Now it will ask you to create a security code/password.</p></li>
<li><p>Once you have entered your password and it is accepted, the BankID system is ready for you to use.</p></li>
<li><p>You can check whether your BankID system is working properly. Log on to <a href="http://demo.bankid.com">http://demo.bankid.com</a> and click on “Log in with a Test BankID” and enter your BankID personal number on the “BankID on any Device” section. If you keep your Mobile BankID app running on your mobile/desktop, this will initiate a prompt in your app to enter the security code/password for authentication.</p></li>
</ul>

<p><a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure2.2.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure2.2.png" alt="Figure 2.2" title="Figure 2.2" style="max-width:100%;"></a></p>

<ul>
<li>Enter the password and click “Identify”. You should be allowed into the system now. This means a testing BankID has been issued successfully and you can use it to implement and test BankID based authentication on your application. </li>
</ul>

<h2><a id="user-content-setting-up-the-client-certificate" class="anchor" href="#setting-up-the-client-certificate" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Setting Up the Client Certificate</h2>

<p>This section will outline steps for Relaying Party (Your Application).</p>

<ul>
<li><p>You need to first download the certificate so that you can access the SOAP service of the BankID system. Log on to <a href="https://www.bankid.com/bankid-i-dina-tjanster/rp-info">https://www.bankid.com/bankid-i-dina-tjanster/rp-info</a> and download the certificate in the marked section shown in Figure 3.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure3.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure3.png" alt="Figure 3" title="Figure 3" style="max-width:100%;"></a></p></li>
<li><p>Now log on to <a href="https://appapi.test.bankid.com/rp/v4?wsdl">https://appapi.test.bankid.com/rp/v4?wsdl</a> to access the web service. This service requires the above mentioned certificate. </p></li>
<li>The password for this certificate is “qwerty123”.</li>
</ul>

<h2><a id="user-content-using-soap-client-ui" class="anchor" href="#using-soap-client-ui" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Using SOAP Client UI</h2>

<p>In order to check which methods are available in the web service, we can use a soap client:  </p>

<ul>
<li>Download the latest version of SoapUI from <a href="https://www.soapui.org/">https://www.soapui.org/</a>. </li>
<li><p>Once the download and installation is complete, a new screen will open as shown in Figure 4.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.png" alt="Figure 4" title="Figure 4" style="max-width:100%;"></a></p></li>
<li><p>Now you need to configure the certificate so that it can be used to access the service methods. For that: - Click on File&gt;Preference, or click on the preference button. </p>

<ul>
<li>On the left panel, click on SSL Settings. </li>
<li>In the KeyStore, provide the link to certificate you downloaded.</li>
<li>In keyStore Password enter “qwerty123”.</li>
<li>Click OK.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4a.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4a.png" alt="Figure 4a" title="Figure 4a" style="max-width:100%;"></a></li>
</ul></li>
<li><p>Now click on “SOAP”. On the next window, provide the project name, it’s SOAP address i.e. <a href="https://appapi.test.bankid.com/rp/v4?wsdl">https://appapi.test.bankid.com/rp/v4?wsdl</a>. Click OK.</p></li>
<li>After loading you will see the above screen with a project folder as shown in Figure 4.1. To know more about what a WSDL is, see <a href="http://www.w3schools.com/wsdl">http://www.w3schools.com/wsdl</a>.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.1.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.1.png" alt="Figure 4.1" title="Figure 4.1" style="max-width:100%;"></a></li>
</ul>

<h3><a id="user-content-sending-request-to-the-server" class="anchor" href="#sending-request-to-the-server" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Sending Request to the Server</h3>

<p>In order to login using the BankID system, you need the first two methods under “RpServiceSoapBinding”: Authenticate and Collect; as shown in Figure 4.1. You can use these methods to get user information:</p>

<ul>
<li>Click on the + icon preceding Authenticate. </li>
<li>Double click  “Request 1.” </li>
<li><p>You’ll pass an XML request template that the server expects, as shown in Figure 4.2.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.2.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.2.png" alt="Figure 4.2" title="Figure 4.2" style="max-width:100%;"></a></p></li>
<li><p>The first box is where you will type in your BankID personal number.</p></li>
<li>The second box is where you can enter User info. In this example, I have entered only the IP address of my localhost. This is a recommended field, so that the RP (Relaying Part, the app that is using BankID to login) knows where the request originated.</li>
<li>The third box contains the conditions which are given in following table. You can use these conditions according to your requirements. In the aforementioned example, I have used two conditions. </li>
</ul>

<table><thead>
<tr>
<th>Type of condition</th>
<th>Values</th>
<th>Default</th>
</tr>
</thead><tbody>
<tr>
<td>CardReader</td>
<td>"class1" - (default). The transaction must be performed using a card reader where the PIN-code is entered on the computers keyboard, or a card reader of higher class.<br>*  "class2" - The transaction must be performed using a card reader where the PIN-code is entered on the reader, or a reader of higher class.<br>*  &lt;no value&gt; - defaults to "class1".<br>*  This condition should be combined with a CertificatePolicies for a smart card to avoid undefined behavior.<br></td>
<td>No special type of card reader required.</td>
</tr>
<tr>
<td>CertificatePolicies</td>
<td>The oid in certificatePolicies in the user certificate. One wildcard ”<em>” is allowed from position 5 and forward ie. 1.2.752.78.</em><br>The values for production BankIDs are:<br>"1.2.752.78.1.1" - BankID on file<br>"1.2.752.78.1.2" - BankID on smart card<br>"1.2.752.78.1.5" - Mobile BankID<br>"1.2.752.71.1.3" - Nordea e-id on file and on smart card.<br>The values for test BankIDs are:<br>"1.2.3.4.5" - BankID on file<br>"1.2.3.4.10" - BankID on smart card<br>"1.2.3.4.25" - Mobile BankID<br>"1.2.752.71.1.3" - Nordea e-id on file and on smart card.<br>“1.2.752.60.1.6” - Test BankID for some BankID Banks<br></td>
<td>If no certificatePolicies is set the following are default in the production system:<br>1.2.752.78.1.1, 1.2.752.78.1.2, 1.2.752.78.1.5, 1.2.752.71.1.3<br>The following are default in the test system:<br>1.2.3.4.5, 1.2.3.4.10, 1.2.3.4.25, 1.2.752.60.1.6, 1.2.752.71.1.3<br>If one certificatePolicy is set all the default policies are dismissed.</td>
</tr>
<tr>
<td>IssuerCn</td>
<td>The CN (common name) of the issuer. Wildcards are not allowed. Nordea values for production: <br> "Nordea CA for Smartcard users 12" - E-id on smart card issued by Nordea CA. "Nordea CA for Softcert users 13" - E-id on file issued by Nordea CA</td>
<td></td>
</tr>
<tr>
<td>Example Nordea values for test: "Nordea Test CA for Smartcard users 12" - E-id on smart card issued by Nordea CA. "Nordea Test CA for Softcert users 13" - E-id on file issued by Nordea CA</td>
<td>If issuer is not defined all relevant BankID and Nordea issuers are allowed.</td>
<td></td>
</tr>
<tr>
<td>AutoStartTokenRequired</td>
<td>If set to Yes, the client must have been started using the autoStartToken. To be used if it is important that the BankID App is on the same device as the RP service.</td>
<td></td>
</tr>
<tr>
<td>If omitted, the client does not need to be started using the autoStartToken. It does not work to set it to No.</td>
<td>If omitted, the client does not need to be started using the autoStartToken.</td>
<td></td>
</tr>
<tr>
<td>AllowFingerprint</td>
<td>Users of iOS devices may use Touch ID for authentication. No other devices are supported at this point. The functionality is not supported for signing.</td>
<td></td>
</tr>
</tbody></table>

<p>If set to yes, the users are allowed to use Touch ID.
If set to no, the users are not allowed to use Touch ID. | yes for authentication.
Not supported for signing.</p>

<h3><a id="user-content-response-from-the-server" class="anchor" href="#response-from-the-server" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Response from the Server</h3>

<p>When you request the server with your XML, it will give you an initial response. If there is an error in parameters, it will give “INVALID_PARAMETERS” error as shown in Figure 4.3</p>

<p><a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.3.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.3.png" alt="Figure 4.3" title="Figure 4.3" style="max-width:100%;"></a></p>

<p>If all the parameters are correct, then you will receive a response from the server with two values:</p>

<ul>
<li><strong>orderRef</strong>: it is an important value for Mobile BankID. Subsequent calls to the server must contain this orderRef for the server to consider it a valid/authentic request.</li>
<li><strong>autoStartToken</strong>: it is used if you wish to use a locally installed application.</li>
</ul>

<p>If the all the parameters are correct, it service will give a response like shown in Figure 4.4.</p>

<p><a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.4.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.4.png" alt="Figure 4.4" title="Figure 4.4" style="max-width:100%;"></a></p>

<p>Now click on the Collect method and double click on Request 1 of Collect as shown in Figure 4.1 and Figure 4.5. Copy the orderRef string and paste it in the collect method’s orderRef tag.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.1.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.1.png" alt="Figure 4.1" title="Figure 4.1" style="max-width:100%;"></a></p>

<p><a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.5.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.5.png" alt="Figure 4.5" title="Figure 4.5" style="max-width:100%;"></a></p>

<p>At this point you need to open BankID app in your mobile and type your password in it. If the password is correct and there is no disruption in the communication, (e.g. internet disconnection) you’ll see a response from the BankID server containing the data as shown in Figure 4.6.
<a href="https://github.com/virtualforce/bankid-authentication/blob/master/images/Figure4.6.png" target="_blank"><img src="https://github.com/virtualforce/bankid-authentication/raw/master/images/Figure4.6.png" alt="Figure 4.6" title="Figure 4.6" style="max-width:100%;"></a></p>

<p>As you can see in Figure 4.6, the response has many fields. The first one is progressStatus which tells you about the status of the request. The messages and their reasons are explained in the following table:</p>

<table><thead>
<tr>
<th>Status</th>
<th>Reason</th>
<th>Action by RP</th>
</tr>
</thead><tbody>
<tr>
<td>OUTSTANDING_TRANSACTION</td>
<td>The order is being processed. The client has not yet received the order. The status will later change to NO_CLIENT, STARTED or USER_SIGN.</td>
<td>If RP tried to start the client automatically, the RP should inform the user that the app is starting. Message RFA13 should be used.<br>If RP did not try to start the client automatically, the RP should inform the user that he needs to start the app. Message RFA1 should be used.</td>
</tr>
<tr>
<td>NO_CLIENT</td>
<td>The order is being processed. The client has not yet received the order.<br>If the user did not provide her ID number the error START_FAILED will be returned in this situation.</td>
<td>If RP tried to start the client automatically: This status indicates that the start failed or the users BankID was not available in the started client. RP should inform the user. Message RFA1 should be used.<br>If RP did not try to start the client automatically: This status indicates that the user not yet has started his client. RP should inform the user. Message RFA1 should be used.</td>
</tr>
<tr>
<td>STARTED</td>
<td>A client has been started with the autostarttoken but a usable ID has not yet been found in the started client. When the client starts there may be a short delay until all IDs are registered. The user may not have any usable IDs at all, or has not yet inserted their smart card.</td>
<td>If RP does not require the autoStartToken to be used and the user provided her ID number the RP should inform the user of possible solutions. Message RFA14 should be used.<br>If RP require the autostarttoken to be used or the user did not provide his ID number the RP should inform the user of possible solutions. Message RFA15 should be used. Note: STARTED is not an error, RP should keep on polling using collect.</td>
</tr>
<tr>
<td>USER_SIGN</td>
<td>The client has received the order.</td>
<td>The RP should inform the user. Message RFA9 should be used.</td>
</tr>
<tr>
<td>USER_REQ</td>
<td>Not used</td>
<td>-</td>
</tr>
<tr>
<td>COMPLETE</td>
<td>COMPLETE <br> The user has provided the security code and completed the order. Collect response includes the signature, user information and the ocsp response.</td>
<td>RP should control the user information returned in userInfo and continue their process.</td>
</tr>
</tbody></table>

<p>In the <em>userInfo</em> tag, you will get the user information. From here you can extract the user information and use it for login purposes. </p>

<h1><a id="user-content-nodejs-implementation" class="anchor" href="#nodejs-implementation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>Node.js Implementation</h1>

<p>In general the BankID based authentication should be implemented at the server side (though it really depends upon your project needs). In this example, I have implemented it using Node.js. </p>

<p>I have made a node.js project and made a module for the users. Here I have model, controller and route files. In my controller I have made a new method called signinWithBankId and in this method I have defined my code as shown in Figure 5.</p>

<p>I am making a variable myXMLText in which I have defined all the XML. This is my controller file. The following code fragment shows how my code is laid out. I am also getting the personal number in the req variable which I stored in personalNumber:</p>

<p>And here's some code! <img class="emoji" title=":+1:" alt=":+1:" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f44d.png" height="20" width="20" align="absmiddle"></p>

<div class="highlight highlight-source-js"><pre><span class="pl-c">/**</span>
<span class="pl-c"> * Module dependencies.</span>
<span class="pl-c"> */</span>
<span class="pl-k">var</span> nodemailer <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>nodemailer<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> crypto <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>crypto<span class="pl-pds">'</span></span>);
<span class="pl-k">var</span> path <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>path<span class="pl-pds">'</span></span>),
    errorHandler <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-smi">path</span>.<span class="pl-en">resolve</span>(<span class="pl-s"><span class="pl-pds">'</span>./modules/core/server/controllers/errors.server.controller<span class="pl-pds">'</span></span>)),
    mongoose <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>mongoose<span class="pl-pds">'</span></span>),
    passport <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>passport<span class="pl-pds">'</span></span>),
    https <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">"</span>https<span class="pl-pds">"</span></span>),
    request <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>request<span class="pl-pds">'</span></span>),
    fs <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>fs<span class="pl-pds">'</span></span>),
    User <span class="pl-k">=</span> <span class="pl-smi">mongoose</span>.<span class="pl-en">model</span>(<span class="pl-s"><span class="pl-pds">'</span>User<span class="pl-pds">'</span></span>),
    parseString <span class="pl-k">=</span> <span class="pl-c1">require</span>(<span class="pl-s"><span class="pl-pds">'</span>xml2js<span class="pl-pds">'</span></span>).<span class="pl-smi">parseString</span>;

<span class="pl-c1">exports</span>.<span class="pl-en">signinWithBankId</span> <span class="pl-k">=</span> <span class="pl-k">function</span>(<span class="pl-smi">req</span>, <span class="pl-smi">res</span>, <span class="pl-smi">next</span>) {

    <span class="pl-k">var</span> personalNumber <span class="pl-k">=</span><span class="pl-smi">req</span>.<span class="pl-c1">body</span>.<span class="pl-smi">bankId</span>;

    <span class="pl-c">//The initial call to the bankId server with personal number to get orderRef</span>
    <span class="pl-k">var</span> myXMLText <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;?xml version="1.0" encoding="utf-8"?&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:typ="http://bankid.com/RpService/v4.0.0/types/"&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;soapenv:Header/&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;soapenv:Body&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;typ:AuthenticateRequest&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--Optional:--&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;personalNumber&gt;<span class="pl-pds">'</span></span><span class="pl-k">+</span>personalNumber<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">'</span>&lt;/personalNumber&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--0 to 20 repetitions:--&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;endUserInfo&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;type&gt;IP_ADDR&lt;/type&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;value&gt;192.168.0.1&lt;/value&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>         <span class="pl-c">//Optional Parameters</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/endUserInfo&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--Optional:--&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;requirementAlternatives&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--0 to 7 repetitions:--&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;requirement&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--1 to 10 repetitions:--&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;condition&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--&lt;key&gt;?&lt;/key&gt; --&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--1 to 20 repetitions:--&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;!--&lt;value&gt;?&lt;/value&gt; --&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;key&gt;CertificatePolicies&lt;/key&gt;     &lt;!--The certificate policy must be --&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;value&gt;1.2.3.4.*&lt;/value&gt;   &lt;!--1.2.752.1.5 (Mobile BankID) --&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-c">//Currently set to test BankID -- Change in Production</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/condition&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/requirement&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;requirement&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;condition&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;key&gt;AllowFingerprint&lt;/key&gt;    &lt;!--// TouchID --&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;value&gt;no&lt;/value&gt;          &lt;!--is not allowed --&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/condition&gt;  <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/requirement&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/requirementAlternatives&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/typ:AuthenticateRequest&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/soapenv:Body&gt; <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
        <span class="pl-s"><span class="pl-pds">'</span>&lt;/soapenv:Envelope&gt;<span class="pl-pds">'</span></span>;
</pre></div>

<p><strong>Figure 5</strong></p>

<p>Next I will explain the node.js based client side.</p>

<p>Section A shows I am making the initial request to the BankID server. Here I am also passing the certificate in the agentOptions. At the end I have a callback function which will execute when this request is successful.</p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> resJson <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>;
    <span class="pl-k">var</span> autoStartToken <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>;
    <span class="pl-k">var</span> orderRef <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>;
    <span class="pl-k">var</span> faultString <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>;
    <span class="pl-k">var</span> intervalid;

    <span class="pl-en">request</span>({
        url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>https://appapi.test.bankid.com/rp/v4<span class="pl-pds">"</span></span>,
        host<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>appapi.test.bankid.com<span class="pl-pds">"</span></span>,
        rejectUnauthorized<span class="pl-k">:</span> <span class="pl-c1">false</span>,
        requestCert<span class="pl-k">:</span> <span class="pl-c1">true</span>,
        method<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>POST<span class="pl-pds">"</span></span>,
        headers<span class="pl-k">:</span> {
            <span class="pl-s"><span class="pl-pds">"</span>content-type<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>application/xml<span class="pl-pds">"</span></span>,  <span class="pl-c">// &lt;--Very important!!!</span>
            <span class="pl-c">//'Accept-Encoding': "gzip,deflate",</span>
            <span class="pl-s"><span class="pl-pds">'</span>Content-Length<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-smi">Buffer</span>.<span class="pl-en">byteLength</span>(myXMLText),
            <span class="pl-c">//'User-Agent': 'Apache-HttpClient/4.1.1 (java 1.5)',</span>
            <span class="pl-s"><span class="pl-pds">'</span>Connection<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Keep-Alive<span class="pl-pds">"</span></span>
        },

        body<span class="pl-k">:</span> myXMLText,

        agentOptions<span class="pl-k">:</span> {
            pfx<span class="pl-k">:</span> <span class="pl-smi">fs</span>.<span class="pl-en">readFileSync</span>(<span class="pl-s"><span class="pl-pds">'</span>cert/FPTestcert2_20150818_102329.pfx<span class="pl-pds">'</span></span>),
            passphrase<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>qwerty123<span class="pl-pds">'</span></span>,
        },


    }, <span class="pl-k">function</span>(<span class="pl-smi">error</span>, <span class="pl-smi">response</span>, <span class="pl-smi">body</span>) {
</pre></div>

<p><strong>Section A</strong></p>

<p><strong>Section B</strong> shows I am extracting the information from the XML response. Here I am parsing the response of the server. If the server responded with a fault or error, this will extract that too and log the fault string. You can pass this fault string to the client.
If the server has responded with Completed, then moving forward we need to extract the orderRef and now make a call to the Collect method. </p>

<div class="highlight highlight-source-js"><pre><span class="pl-c">//extracting orderRef from the bankId server response XML</span>
        <span class="pl-en">parseString</span>(body, <span class="pl-k">function</span>(<span class="pl-smi">err</span>, <span class="pl-smi">result</span>) {
            resJson <span class="pl-k">=</span> <span class="pl-c1">JSON</span>.<span class="pl-en">stringify</span>(result);

            <span class="pl-k">var</span> tempStr <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>JSON.parse(resJson)<span class="pl-pds">"</span></span>;
            <span class="pl-k">var</span> indeces <span class="pl-k">=</span> <span class="pl-c1">Array</span>(<span class="pl-s"><span class="pl-pds">'</span>soap:Envelope<span class="pl-pds">'</span></span>,<span class="pl-s"><span class="pl-pds">'</span>soap:Body<span class="pl-pds">'</span></span>,<span class="pl-c1">0</span>,<span class="pl-s"><span class="pl-pds">'</span>ns2:AuthResponse<span class="pl-pds">'</span></span>,<span class="pl-c1">0</span>);

            <span class="pl-k">for</span> (<span class="pl-k">var</span> i<span class="pl-k">=</span><span class="pl-c1">0</span>;i<span class="pl-k">&lt;</span><span class="pl-smi">indeces</span>.<span class="pl-c1">length</span>; i<span class="pl-k">++</span>)
                <span class="pl-k">if</span>(<span class="pl-c1">eval</span>(tempStr<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">"</span>['<span class="pl-pds">"</span></span><span class="pl-k">+</span>indeces[i]<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">"</span>']<span class="pl-pds">"</span></span>))
                    tempStr <span class="pl-k">+=</span> <span class="pl-s"><span class="pl-pds">"</span>['<span class="pl-pds">"</span></span><span class="pl-k">+</span>indeces[i]<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">"</span>']<span class="pl-pds">"</span></span>;
                <span class="pl-k">else</span>
                {
                    tempStr <span class="pl-k">+=</span> <span class="pl-s"><span class="pl-pds">"</span>['soap:Fault'][0]<span class="pl-pds">"</span></span>;
                    faultString <span class="pl-k">=</span> <span class="pl-c1">eval</span>(tempStr).<span class="pl-smi">faultstring</span>[<span class="pl-c1">0</span>];
                    <span class="pl-k">break</span>;
                }

            <span class="pl-k">if</span>(faultString <span class="pl-k">!==</span><span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>){
                <span class="pl-en">console</span>.<span class="pl-c1">log</span>(faultString); <span class="pl-c">//Report the user (client) about the fault</span>
            }
</pre></div>

<p><strong>Section B</strong></p>

<div class="highlight highlight-source-js"><pre><span class="pl-k">else</span>
            {
            <span class="pl-k">var</span> theValue <span class="pl-k">=</span> <span class="pl-c1">eval</span>(tempStr);
            autoStartToken <span class="pl-k">=</span> <span class="pl-smi">theValue</span>.<span class="pl-smi">autoStartToken</span>;
            orderRef <span class="pl-k">=</span> <span class="pl-smi">theValue</span>.<span class="pl-smi">orderRef</span>;
            <span class="pl-c">//Ping the BankId server every 3 seconds, with orderRef to get the User Data</span>
            intervalid <span class="pl-k">=</span> <span class="pl-c1">setInterval</span>(<span class="pl-k">function</span>() {
                <span class="pl-k">var</span> myXMLTextOrderRef <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;?xml version="1.0" encoding="utf-8"?&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
                    <span class="pl-s"><span class="pl-pds">'</span>&lt;soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:typ="http://bankid.com/RpService/v4.0.0/types/"&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
                    <span class="pl-s"><span class="pl-pds">'</span>&lt;soapenv:Header/&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
                    <span class="pl-s"><span class="pl-pds">'</span>&lt;soapenv:Body&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
                    <span class="pl-s"><span class="pl-pds">'</span>&lt;typ:orderRef&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span> orderRef[<span class="pl-c1">0</span>] <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;/typ:orderRef&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
                    <span class="pl-s"><span class="pl-pds">'</span>&lt;/soapenv:Body&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
                    <span class="pl-s"><span class="pl-pds">'</span>&lt;/soapenv:Envelope&gt;<span class="pl-pds">'</span></span>;
</pre></div>

<p><strong>Section C</strong></p>

<p>After extracting the orderRef, we make another XML and will be requesting the server again, this time with orderRef and calling the Collect method. I have also attached a timer with this piece of code to poll the server every 3 seconds (not the most sophisticated way, but works for me). I have done this because there can be delays related to user’s typing speed or error, issues with the personal number or the internet etc. This request also contains the certificate. </p>

<div class="highlight highlight-source-js"><pre><span class="pl-en">request</span>({
                    url<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>https://appapi.test.bankid.com/rp/v4<span class="pl-pds">"</span></span>,
                    host<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>appapi.test.bankid.com<span class="pl-pds">"</span></span>,
                    rejectUnauthorized<span class="pl-k">:</span> <span class="pl-c1">false</span>,
                    requestCert<span class="pl-k">:</span> <span class="pl-c1">true</span>,
                    method<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>POST<span class="pl-pds">"</span></span>,
                    headers<span class="pl-k">:</span> {
                        <span class="pl-s"><span class="pl-pds">"</span>content-type<span class="pl-pds">"</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>application/xml<span class="pl-pds">"</span></span>,  <span class="pl-c">// &lt;--Very important!!!</span>
                        <span class="pl-c">//'Accept-Encoding': "gzip,deflate",</span>
                        <span class="pl-s"><span class="pl-pds">'</span>Content-Length<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-smi">Buffer</span>.<span class="pl-en">byteLength</span>(myXMLTextOrderRef),
                        <span class="pl-c">//'User-Agent': 'Apache-HttpClient/4.1.1 (java 1.5)',</span>
                        <span class="pl-s"><span class="pl-pds">'</span>Connection<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">"</span>Keep-Alive<span class="pl-pds">"</span></span>
                    },
                    body<span class="pl-k">:</span> myXMLTextOrderRef,
                    agentOptions<span class="pl-k">:</span> {
                        pfx<span class="pl-k">:</span> <span class="pl-smi">fs</span>.<span class="pl-en">readFileSync</span>(<span class="pl-s"><span class="pl-pds">'</span>cert/FPTestcert2_20150818_102329.pfx<span class="pl-pds">'</span></span>),
                        passphrase<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>qwerty123<span class="pl-pds">'</span></span>,
                    },
</pre></div>

<p><strong>Section D</strong></p>

<div class="highlight highlight-source-js"><pre>}, <span class="pl-k">function</span>(<span class="pl-smi">error</span>, <span class="pl-smi">response</span>, <span class="pl-smi">body</span>) {
                    <span class="pl-k">if</span> (<span class="pl-k">!</span>error) {
                        <span class="pl-en">parseString</span>(body, <span class="pl-k">function</span>(<span class="pl-smi">err</span>, <span class="pl-smi">result</span>) {
                            <span class="pl-k">var</span> resp <span class="pl-k">=</span> <span class="pl-c1">JSON</span>.<span class="pl-en">stringify</span>(result);
                            <span class="pl-k">var</span> tempStrnew <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>JSON.parse(resp)<span class="pl-pds">"</span></span>;
                            <span class="pl-k">var</span> indecesNew <span class="pl-k">=</span> <span class="pl-c1">Array</span>(<span class="pl-s"><span class="pl-pds">'</span>soap:Envelope<span class="pl-pds">'</span></span>,<span class="pl-s"><span class="pl-pds">'</span>soap:Body<span class="pl-pds">'</span></span>,<span class="pl-c1">0</span>,<span class="pl-s"><span class="pl-pds">'</span>ns2:CollectResponse<span class="pl-pds">'</span></span>,<span class="pl-c1">0</span>);
                            <span class="pl-k">var</span> statusCod <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>;
                            <span class="pl-k">var</span> faultStringRes <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>;

                            <span class="pl-k">for</span> (<span class="pl-k">var</span> i<span class="pl-k">=</span><span class="pl-c1">0</span>;i<span class="pl-k">&lt;</span><span class="pl-smi">indecesNew</span>.<span class="pl-c1">length</span>; i<span class="pl-k">++</span>)
                                <span class="pl-k">if</span>(<span class="pl-c1">eval</span>(tempStrnew<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">"</span>['<span class="pl-pds">"</span></span><span class="pl-k">+</span>indecesNew[i]<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">"</span>']<span class="pl-pds">"</span></span>))
                                    tempStrnew <span class="pl-k">+=</span> <span class="pl-s"><span class="pl-pds">"</span>['<span class="pl-pds">"</span></span><span class="pl-k">+</span>indecesNew[i]<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">"</span>']<span class="pl-pds">"</span></span>;
                                <span class="pl-k">else</span>
                                {
                                    tempStrnew <span class="pl-k">+=</span> <span class="pl-s"><span class="pl-pds">"</span>['soap:Fault'][0]<span class="pl-pds">"</span></span>;
                                    faultStringRes <span class="pl-k">=</span> <span class="pl-c1">eval</span>(tempStrnew).<span class="pl-smi">faultstring</span>[<span class="pl-c1">0</span>];
                                    <span class="pl-k">break</span>;
                                }
                            <span class="pl-k">if</span>(faultStringRes <span class="pl-k">!==</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>)
                            {
                                <span class="pl-en">console</span>.<span class="pl-c1">log</span>(faultStringRes); <span class="pl-c">//Inform the client about this fault too!</span>
                                <span class="pl-c1">clearInterval</span>(intervalid);
                                <span class="pl-k">return</span>;
                            }

                            statusCod <span class="pl-k">=</span> <span class="pl-c1">eval</span>(tempStrnew).<span class="pl-smi">progressStatus</span>[<span class="pl-c1">0</span>];

                            <span class="pl-k">if</span> (statusCod <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">"</span>OUTSTANDING_TRANSACTION<span class="pl-pds">"</span></span>) {
                                <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">"</span>Outstanding Transaction<span class="pl-pds">"</span></span>);

                            }
                            <span class="pl-k">if</span> (statusCod <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">"</span>NO_CLIENT<span class="pl-pds">"</span></span>) {
                                <span class="pl-en">console</span>.<span class="pl-c1">log</span>(<span class="pl-s"><span class="pl-pds">"</span>No Client<span class="pl-pds">"</span></span>);
                                <span class="pl-c1">clearInterval</span>(intervalid);
                            }
                            <span class="pl-k">if</span> (statusCod <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">"</span>COMPLETE<span class="pl-pds">"</span></span>) {
                                <span class="pl-en">console</span>.<span class="pl-c1">log</span>(body);
                                <span class="pl-k">var</span> providerUserProfile <span class="pl-k">=</span> 
                                {
                                firstName<span class="pl-k">:</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-smi">givenName</span>[<span class="pl-c1">0</span>],
                                lastName<span class="pl-k">:</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-smi">surname</span>[<span class="pl-c1">0</span>],
                                displayName<span class="pl-k">:</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-c1">name</span>[<span class="pl-c1">0</span>],
                                email<span class="pl-k">:</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-smi">emails</span> <span class="pl-k">?</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-smi">emails</span>[<span class="pl-c1">0</span>].<span class="pl-c1">value</span> <span class="pl-k">:</span> <span class="pl-c1">undefined</span>,
                                username<span class="pl-k">:</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-smi">personalNumber</span>[<span class="pl-c1">0</span>],
                                password<span class="pl-k">:</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-smi">surname</span>[<span class="pl-c1">0</span>]<span class="pl-k">+</span><span class="pl-s"><span class="pl-pds">"</span>123!@#<span class="pl-pds">"</span></span>,
                                <span class="pl-c">//profileImageURL: (profile.id) ? '//graph.facebook.com/' + profile.id + '/picture?type=large' : undefined,</span>
                                provider<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>local<span class="pl-pds">'</span></span>,
                                providerIdentifierField<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>username<span class="pl-pds">'</span></span>,
                                providerData<span class="pl-k">:</span> {username<span class="pl-k">:</span> <span class="pl-c1">eval</span>(tempStrnew)[<span class="pl-s"><span class="pl-pds">'</span>userInfo<span class="pl-pds">'</span></span>][<span class="pl-c1">0</span>].<span class="pl-smi">personalNumber</span>[<span class="pl-c1">0</span>]},
                                userRole<span class="pl-k">:</span> [<span class="pl-s"><span class="pl-pds">'</span>patient<span class="pl-pds">'</span></span>],
                                };

                                <span class="pl-smi">User</span>.<span class="pl-en">findOne</span>({<span class="pl-s"><span class="pl-pds">"</span>username<span class="pl-pds">"</span></span><span class="pl-k">:</span><span class="pl-smi">providerUserProfile</span>.<span class="pl-smi">username</span>}, <span class="pl-k">function</span> (<span class="pl-smi">err</span>, <span class="pl-smi">person</span>) {
                                    <span class="pl-k">if</span> (<span class="pl-k">!</span>person)
                                    {
                                        <span class="pl-smi">providerUserProfile</span>.<span class="pl-smi">isNewUser</span> <span class="pl-k">=</span> <span class="pl-c1">true</span>;
                                        <span class="pl-smi">res</span>.<span class="pl-en">json</span>(providerUserProfile);  
                                    }
                                    <span class="pl-k">else</span>
                                    {
                                        <span class="pl-smi">providerUserProfile</span>.<span class="pl-smi">isNewUser</span> <span class="pl-k">=</span> <span class="pl-c1">false</span>;
                                        <span class="pl-smi">res</span>.<span class="pl-en">json</span>(providerUserProfile);  
                                    }
                                });
                                <span class="pl-c1">clearInterval</span>(intervalid);
                                <span class="pl-k">return</span>;
                            }
                        });
                        }
                    });
                }, <span class="pl-c1">3000</span>);
            }
        });
    });
};
</pre></div>

<p><strong>Section E</strong></p>

<p>In the callback of the function request, I again parse it to see what the response is. After parsing we will get one of two things. Either:
Status code of the request: if the response shows status in progress, we can check for different statuses and add commands accordingly. 
Fault string: contains the fault string you can inform the client about the fault. </p>

<p>If however, the progress status was complete, then we can extract the user data from the response, and use that data to login/signup the system. In the given example, after extracting the data from the response, I search in my ‘User’ model to find if there is an existing User of the same username (in this case I am treating the username as the personal number which will be unique).
If such a person is found then it not a new user and it will return that user. If the user does not exist, then we can redirect to the signup function.</p>

<h3><a id="user-content-references" class="anchor" href="#references" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a>References</h3>

<ul>
<li><a href="https://www.bankid.com/assets/bankid/rp/bankid-relying-party-guidelines-v2.10.pdf">BankID Relying Party Guidelines v2.10</a> for technical details</li>
<li><a href="https://github.com/markdown-it/markdown-it">markdown-it</a> for Markdown parsing</li>
<li><a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#html">markdown cheat sheet</a> for Markdown learning</li>
</ul>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="hidden">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59 0.4 0.07 0.55-0.17 0.55-0.38 0-0.19-0.01-0.82-0.01-1.49-2.01 0.37-2.53-0.49-2.69-0.94-0.09-0.23-0.48-0.94-0.82-1.13-0.28-0.15-0.68-0.52-0.01-0.53 0.63-0.01 1.08 0.58 1.23 0.82 0.72 1.21 1.87 0.87 2.33 0.66 0.07-0.52 0.28-0.87 0.51-1.07-1.78-0.2-3.64-0.89-3.64-3.95 0-0.87 0.31-1.59 0.82-2.15-0.08-0.2-0.36-1.02 0.08-2.12 0 0 0.67-0.21 2.2 0.82 0.64-0.18 1.32-0.27 2-0.27 0.68 0 1.36 0.09 2 0.27 1.53-1.04 2.2-0.82 2.2-0.82 0.44 1.1 0.16 1.92 0.08 2.12 0.51 0.56 0.82 1.27 0.82 2.15 0 3.07-1.87 3.75-3.65 3.95 0.29 0.25 0.54 0.73 0.54 1.48 0 1.07-0.01 1.93-0.01 2.2 0 0.21 0.15 0.46 0.55 0.38C13.71 14.53 16 11.53 16 8 16 3.58 12.42 0 8 0z"></path></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.09597s from github-fe116-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15.72 12.5l-6.85-11.98C8.69 0.21 8.36 0.02 8 0.02s-0.69 0.19-0.87 0.5l-6.85 11.98c-0.18 0.31-0.18 0.69 0 1C0.47 13.81 0.8 14 1.15 14h13.7c0.36 0 0.69-0.19 0.86-0.5S15.89 12.81 15.72 12.5zM9 12H7V10h2V12zM9 9H7V5h2V9z"></path></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      
      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-f8175c23360b42a4eb18b2319fefeae252cfeea482fb804356f4136a52bfddb3.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-1502104f450cb05859f99b57e29782e071e3fb240e237adb8cbf17ebbdb271c7.js"></script>
      
      
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15.72 12.5l-6.85-11.98C8.69 0.21 8.36 0.02 8 0.02s-0.69 0.19-0.87 0.5l-6.85 11.98c-0.18 0.31-0.18 0.69 0 1C0.47 13.81 0.8 14 1.15 14h13.7c0.36 0 0.69-0.19 0.86-0.5S15.89 12.81 15.72 12.5zM9 12H7V10h2V12zM9 9H7V5h2V9z"></path></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48-3.75-3.75-3.75 3.75-1.48-1.48 3.75-3.75L0.77 4.25l1.48-1.48 3.75 3.75 3.75-3.75 1.48 1.48-3.75 3.75z"></path></svg>
    </button>
  </div>
</div>

  </body>
</html>

