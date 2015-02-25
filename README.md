


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>Java-AWS-S3Sample/README.md at master · KarthikChandy/Java-AWS-S3Sample</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="KarthikChandy/Java-AWS-S3Sample" name="twitter:title" /><meta content="Java-AWS-S3Sample - This sample Java script performs simple S3 operations. " name="twitter:description" /><meta content="https://avatars2.githubusercontent.com/u/5674976?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars2.githubusercontent.com/u/5674976?v=3&amp;s=400" property="og:image" /><meta content="KarthikChandy/Java-AWS-S3Sample" property="og:title" /><meta content="https://github.com/KarthikChandy/Java-AWS-S3Sample" property="og:url" /><meta content="Java-AWS-S3Sample - This sample Java script performs simple S3 operations. " property="og:description" />
      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="36F0C769:11B4:476F3C8:54ED57E6" name="octolytics-dimension-request_id" /><meta content="5674976" name="octolytics-actor-id" /><meta content="KarthikChandy" name="octolytics-actor-login" /><meta content="10ba97f6c84a4c1425d7a33756c8aab0d7770ba0a5b357471ef5a244a7502be1" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="nm5s4MSu1uaN+qVi2ITdKBXHxZPQlL13Mw+vyDXcn639uxsNsU6kaLGKRtFYqTrvPMzXDzAUOIR08/WPz90rfg==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-84e4144e3c0347e1187b021a88b6bcbad5186ac898c63e26b13332c7c53504a6.css" media="all" rel="stylesheet" />
    <link href="https://assets-cdn.github.com/assets/github2-f7073494168d35df2845fccdae3f73cb69dc51cf65c42dccd9cefb67ee814256.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="945278cda3a45c59c8dbdf70297f2687">

      
  <meta name="description" content="Java-AWS-S3Sample - This sample Java script performs simple S3 operations. ">
  <meta name="go-import" content="github.com/KarthikChandy/Java-AWS-S3Sample git https://github.com/KarthikChandy/Java-AWS-S3Sample.git">

  <meta content="5674976" name="octolytics-dimension-user_id" /><meta content="KarthikChandy" name="octolytics-dimension-user_login" /><meta content="31295685" name="octolytics-dimension-repository_id" /><meta content="KarthikChandy/Java-AWS-S3Sample" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="31295685" name="octolytics-dimension-repository_network_root_id" /><meta content="KarthikChandy/Java-AWS-S3Sample" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/KarthikChandy/Java-AWS-S3Sample/commits/master.atom" rel="alternate" title="Recent Commits to Java-AWS-S3Sample:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production macintosh vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/KarthikChandy/Java-AWS-S3Sample/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/KarthikChandy/Java-AWS-S3Sample/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/KarthikChandy" data-ga-click="Header, go to profile, text:username">
      <img alt="Karthik Chandy" class="avatar" data-user="5674976" height="20" src="https://avatars0.githubusercontent.com/u/5674976?v=3&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">KarthikChandy</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new" data-ga-click="Header, create new repository, icon:repo"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new" data-ga-click="Header, create new organization, icon:organization"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="KarthikChandy/Java-AWS-S3Sample">This repository</span>
    </li>
      <li>
        <a href="/KarthikChandy/Java-AWS-S3Sample/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
      <li>
        <a href="/KarthikChandy/Java-AWS-S3Sample/settings/collaboration" data-ga-click="Header, create new collaborator, icon:person"><span class="octicon octicon-person"></span> New collaborator</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="N3nAGriseZPg7K2n20gJokUsnU6wFldmLS9t+IYu+RX7VRgyxunRdn4dkmr14DJmuMqyNo21poMpvhNcpDC2Lw==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>


    
  </div>
</div>

      

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="6isfk1MomW7zAR/3veZS3j/YUnxRcOmR4PdW8mlzBBKZKNGKVPTF1Rg/To411ucBOEPdYi/cslkObu6/9ufx4g==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="31295685" />

      <div class="select-menu js-menu-container js-select-menu">
        <a class="social-count js-social-count" href="/KarthikChandy/Java-AWS-S3Sample/watchers">
          1
        </a>
        <a href="/KarthikChandy/Java-AWS-S3Sample/subscription"
          class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Unwatch
          </span>
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
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

    <form accept-charset="UTF-8" action="/KarthikChandy/Java-AWS-S3Sample/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="kRKE/gVC37CK/uQc+0+tzQ3nTUePn5xUUt9HhQWsZAKhBVDi0MCQDthL19anfNkbU5PJR7jwuvSepHlTGiSCjw==" /></div>
      <button
        class="minibutton with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar KarthikChandy/Java-AWS-S3Sample">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/KarthikChandy/Java-AWS-S3Sample/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/KarthikChandy/Java-AWS-S3Sample/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="8bKBJ23IznJFdPUNPfM0bMec7O8cpDXkzChxJ17pIWNZqy9+PSfNUjAjDTO6h4s95O7Q11rV1WULUO0tDKJOLw==" /></div>
      <button
        class="minibutton with-count js-toggler-target"
        aria-label="Star this repository" title="Star KarthikChandy/Java-AWS-S3Sample">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/KarthikChandy/Java-AWS-S3Sample/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <a href="/KarthikChandy/Java-AWS-S3Sample/fork" class="minibutton with-count js-toggler-target tooltipped-n" title="Fork your own copy of KarthikChandy/Java-AWS-S3Sample to your account" aria-label="Fork your own copy of KarthikChandy/Java-AWS-S3Sample to your account" rel="facebox nofollow">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/KarthikChandy/Java-AWS-S3Sample/network" class="social-count">0</a>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/KarthikChandy" class="url fn" itemprop="url" rel="author"><span itemprop="title">KarthikChandy</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/KarthikChandy/Java-AWS-S3Sample" class="js-current-repository" data-pjax="#js-repo-pjax-container">Java-AWS-S3Sample</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/KarthikChandy/Java-AWS-S3Sample/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/KarthikChandy/Java-AWS-S3Sample" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /KarthikChandy/Java-AWS-S3Sample">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/KarthikChandy/Java-AWS-S3Sample/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /KarthikChandy/Java-AWS-S3Sample/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
      <a href="/KarthikChandy/Java-AWS-S3Sample/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /KarthikChandy/Java-AWS-S3Sample/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>


      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/KarthikChandy/Java-AWS-S3Sample/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /KarthikChandy/Java-AWS-S3Sample/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/KarthikChandy/Java-AWS-S3Sample/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /KarthikChandy/Java-AWS-S3Sample/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/KarthikChandy/Java-AWS-S3Sample/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /KarthikChandy/Java-AWS-S3Sample/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Settings">
        <a href="/KarthikChandy/Java-AWS-S3Sample/settings" aria-label="Settings" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_settings /KarthikChandy/Java-AWS-S3Sample/settings">
          <span class="octicon octicon-tools"></span> <span class="full-word">Settings</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
    </ul>
</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/KarthikChandy/Java-AWS-S3Sample.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:KarthikChandy/Java-AWS-S3Sample.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/KarthikChandy/Java-AWS-S3Sample" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>

  <a href="http://mac.github.com" data-url="github-mac://openRepo/https://github.com/KarthikChandy/Java-AWS-S3Sample" class="minibutton sidebar-button js-conduit-rewrite-url" title="Save KarthikChandy/Java-AWS-S3Sample to your computer and use it in GitHub Desktop." aria-label="Save KarthikChandy/Java-AWS-S3Sample to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/KarthikChandy/Java-AWS-S3Sample/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download the contents of KarthikChandy/Java-AWS-S3Sample as a zip file"
                   title="Download the contents of KarthikChandy/Java-AWS-S3Sample as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/KarthikChandy/Java-AWS-S3Sample/blob/8466179296bc70e4712110e5e3fcdfba28ce982b/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:d44d1e1dc197690d64fea25a528a638e -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/KarthikChandy/Java-AWS-S3Sample/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <form accept-charset="UTF-8" action="/KarthikChandy/Java-AWS-S3Sample/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="PT0INcASwusTcB8Fm/vqaxI4aIUqfmFQ2fYRjKQRudS1CnwzR2ZhHXscnFgH/Xcz1dC0XPSk+G3faAPRpZELgQ==" /></div>
            <span class="octicon octicon-git-branch select-menu-item-icon"></span>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘master’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
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

  <div class="button-group right">
    <a href="/KarthikChandy/Java-AWS-S3Sample/find/master"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/KarthikChandy/Java-AWS-S3Sample" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">Java-AWS-S3Sample</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="Karthik Chandy" class="avatar" data-user="5674976" height="24" src="https://avatars2.githubusercontent.com/u/5674976?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/KarthikChandy" rel="author">KarthikChandy</a></span>
        <time datetime="2015-02-25T04:21:10Z" is="relative-time">Feb 25, 2015</time>
        <div class="commit-title">
            <a href="/KarthikChandy/Java-AWS-S3Sample/commit/8466179296bc70e4712110e5e3fcdfba28ce982b" class="message" data-pjax="true" title="Update README.md">Update README.md</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="Karthik Chandy" data-user="5674976" height="24" src="https://avatars2.githubusercontent.com/u/5674976?v=3&amp;s=48" width="24" />
            <a href="/KarthikChandy">KarthikChandy</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-info">
        44 lines (28 sloc)
        <span class="file-info-divider"></span>
      2.715 kb
    </div>
    <div class="file-actions">
      <div class="button-group">
        <a href="/KarthikChandy/Java-AWS-S3Sample/raw/master/README.md" class="minibutton " id="raw-url">Raw</a>
          <a href="/KarthikChandy/Java-AWS-S3Sample/blame/master/README.md" class="minibutton js-update-url-with-hash">Blame</a>
        <a href="/KarthikChandy/Java-AWS-S3Sample/commits/master/README.md" class="minibutton " rel="nofollow">History</a>
      </div><!-- /.button-group -->

        <a class="octicon-button tooltipped tooltipped-nw js-conduit-openfile-check"
           href="http://mac.github.com"
           data-url="github-mac://openRepo/https://github.com/KarthikChandy/Java-AWS-S3Sample?branch=master&amp;filepath=README.md"
           aria-label="Open this file in GitHub for Mac"
           data-failed-title="Your version of GitHub for Mac is too old to open this file. Try checking for updates.">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <a class="octicon-button js-update-url-with-hash"
               href="/KarthikChandy/Java-AWS-S3Sample/edit/master/README.md"
               aria-label="Edit this file"
               data-method="post" rel="nofollow" data-hotkey="e"><span class="octicon octicon-pencil"></span></a>

          <a class="octicon-button danger"
             href="/KarthikChandy/Java-AWS-S3Sample/delete/master/README.md"
             aria-label="Delete this file"
             data-method="post" data-test-id="delete-blob-file" rel="nofollow">
        <span class="octicon octicon-trashcan"></span>
      </a>
    </div><!-- /.actions -->
  </div>
  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a id="user-content-java-basics---aws---s3sample-operations" class="anchor" href="#java-basics---aws---s3sample-operations" aria-hidden="true"><span class="octicon octicon-link"></span></a>Java Basics - AWS - S3Sample Operations</h1>

<p>This script is based on the AWS Toolkit for S3. It is available here <a href="https://github.com/aws/aws-sdk-java/tree/master/src/samples/AmazonS3">https://github.com/aws/aws-sdk-java/tree/master/src/samples/AmazonS3</a>.<br>
By using this script you agree to requirements laid out by Apache and AWS.</p>

<h2>
<a id="user-content-prerequisites" class="anchor" href="#prerequisites" aria-hidden="true"><span class="octicon octicon-link"></span></a>Prerequisites</h2>

<ol class="task-list">
<li><p>Create an <strong>AWS</strong> account. Learn more about AWS here <a href="http://aws.amazon.com/getting-started/">http://aws.amazon.com/getting-started/</a></p></li>
<li><p>Create an <strong>IAM</strong> user with the required permissions to perform related operations. Learn more here --&gt; <a href="http://docs.aws.amazon.com/IAM/latest/UserGuide/GSGHowToCreateAdminsGroup.html">http://docs.aws.amazon.com/IAM/latest/UserGuide/GSGHowToCreateAdminsGroup.html</a>  </p></li>
<li>
<p>Create an <strong>Access Key</strong> and <strong>Secret Key</strong> for your user. Learn more here <a href="http://docs.aws.amazon.com/IAM/latest/UserGuide/ManagingCredentials.html#Using_CreateAccessKey">http://docs.aws.amazon.com/IAM/latest/UserGuide/ManagingCredentials.html#Using_CreateAccessKey</a><br>
Fill in your AWS access credentials in the provided credentials file template, and be sure to move the file to the default location (~/.aws/credentials) where the sample code will load the credentials from.  </p>

<p><strong>WANRNING:</strong> To avoid accidental leakage of your credentials, DO NOT keep the credentials file in your source directory. <a href="http://aws.amazon.com/security-credentials">http://aws.amazon.com/security-credentials</a></p>
</li>
<li><p>Download and install <strong>JDK-EE</strong> and <strong>JEE</strong> from <a href="http://www.oracle.com/technetwork/java/javaee/downloads/index.html">http://www.oracle.com/technetwork/java/javaee/downloads/index.html</a></p></li>
<li><p>Install <strong>Eclipse IDE for Java EE Developers</strong> from <a href="http://www.eclipse.org/downloads/">http://www.eclipse.org/downloads/</a></p></li>
<li><p><strong>Optionally</strong> you can install <strong>EGit</strong> from <a href="http://download.eclipse.org/egit/updates/">http://download.eclipse.org/egit/updates/</a> to download code stored on Git.</p></li>
<li><p>Open <strong>Eclipse</strong> and first update your IDE. <strong>Help</strong> &gt; <strong>Check for Updates</strong>   </p></li>
<li><p>Create a new project in Eclipse by selecting <strong>File</strong> &gt; <strong>New</strong> &gt; <strong>Java Project</strong> &gt; Give the project a name <strong>S3Sample</strong> &gt; Click <strong>Next</strong> &gt; <strong>Libraries</strong> &gt; <strong>Add Library...</strong> &gt; <strong>AWS SDK for Java</strong> &gt; Click <strong>Next</strong> &gt; Click <strong>Finish</strong> &gt; Click <strong>Finish</strong>.</p></li>
<li><p>Right Click the newly created project and choose <strong>Import</strong> &gt; Under <strong>Git</strong> choose <strong>Projects from Git</strong> &gt; Select <strong>Clone URL</strong> &gt; paste Git URL <a href="https://github.com/KarthikChandy/Java-AWS-S3Sample">https://github.com/KarthikChandy/Java-AWS-S3Sample</a> in the URL text box &gt; Click <strong>Next</strong> &gt; Make sure all files are selected &gt; Click <strong>Next</strong> &gt; Click <strong>Next</strong> &gt; Click <strong>Next</strong> &gt; Click <strong>Finish</strong>.</p></li>
</ol>

<h2>
<a id="user-content-run-the-s3sample-file" class="anchor" href="#run-the-s3sample-file" aria-hidden="true"><span class="octicon octicon-link"></span></a>Run the S3Sample file</h2>

<p>Select the S3Sample.java file visible on the left portion of Eclipse. From the Menu bar choose <strong>Run As</strong> &gt; <strong>Java Application</strong> to execute the code. </p>

<h2>
<a id="user-content-support-and-references" class="anchor" href="#support-and-references" aria-hidden="true"><span class="octicon octicon-link"></span></a>Support and References</h2>

<p>Use this script at your own risk.</p>

<p>a.  <a href="http://www.oracle.com/us/support/index.html">http://www.oracle.com/us/support/index.html</a><br>
b.  <a href="http://www.eclipse.org/forums/">http://www.eclipse.org/forums/</a><br>
c.      <a href="https://aws.amazon.com/premiumsupport/">https://aws.amazon.com/premiumsupport/</a><br>
d.      <a href="http://aws.amazon.com/sdk-for-java/">http://aws.amazon.com/sdk-for-java/</a><br>
e.      <a href="http://docs.aws.amazon.com/AWSJavaSDK/latest/javadoc/index.html">http://docs.aws.amazon.com/AWSJavaSDK/latest/javadoc/index.html</a>  </p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="http://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="http://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="/" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05624s from github-fe133-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-9643b0378c6bcb216adcdaaaa703eed77aa239aaf1c2ae44cadb2fb5099ec172.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-f188e08a7b4dddd01cad76f5a45c982117c6b794f999c8941cd5b9d3c6664762.js"></script>
      
      

  </body>
</html>

