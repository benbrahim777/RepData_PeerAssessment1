


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>datasciencecoursera/PA1_template.md at master · rayryeng/datasciencecoursera</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="rayryeng/datasciencecoursera" name="twitter:title" /><meta content="datasciencecoursera - My work for the Data Science track on coursera" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/765375?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/765375?v=3&amp;s=400" property="og:image" /><meta content="rayryeng/datasciencecoursera" property="og:title" /><meta content="https://github.com/rayryeng/datasciencecoursera" property="og:url" /><meta content="datasciencecoursera - My work for the Data Science track on coursera" property="og:description" />
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

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="CEA72C16:54E4:726C0F:54FF1C82" name="octolytics-dimension-request_id" /><meta content="10237417" name="octolytics-actor-id" /><meta content="benbrahim777" name="octolytics-actor-login" /><meta content="0f7e0a17511070be81171a82452e6e081eda03ead8ab194a83ec8a490d8d0e41" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="zU0R5Tx5pkdJkjF5Vrdm0+ddJGFDWAI226XLatAxTXs2+vyefyT5eU8gUCW+/BH1Ch4LQn2GqRTk/CwIw0uioA==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-928d6711d0e2b8553a8ad09c40303249229e43320d9ebd7fa17e5a3947767863.css" media="all" rel="stylesheet" />
    <link href="https://assets-cdn.github.com/assets/github2-d0d38a15398bc7dc561dfd94104b43e7ea739ce35bc2a635607efc7655671dfc.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="e0ee8fbaadb13bc4e91ffe33c117b80c">

      
  <meta name="description" content="datasciencecoursera - My work for the Data Science track on coursera">
  <meta name="go-import" content="github.com/rayryeng/datasciencecoursera git https://github.com/rayryeng/datasciencecoursera.git">

  <meta content="765375" name="octolytics-dimension-user_id" /><meta content="rayryeng" name="octolytics-dimension-user_login" /><meta content="18779023" name="octolytics-dimension-repository_id" /><meta content="rayryeng/datasciencecoursera" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="18779023" name="octolytics-dimension-repository_network_root_id" /><meta content="rayryeng/datasciencecoursera" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/rayryeng/datasciencecoursera/commits/master.atom" rel="alternate" title="Recent Commits to datasciencecoursera:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/rayryeng/datasciencecoursera/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/rayryeng/datasciencecoursera/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
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
    <a class="header-nav-link name" href="/benbrahim777" data-ga-click="Header, go to profile, text:username">
      <img alt="Salah" class="avatar" data-user="10237417" height="20" src="https://avatars1.githubusercontent.com/u/10237417?v=3&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">benbrahim777</span>
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
      <span title="rayryeng/datasciencecoursera">This repository</span>
    </li>
      <li>
        <a href="/rayryeng/datasciencecoursera/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
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
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="017Tdex6TglUQUM/AGgg+rrTcgQENEIjw2bggnGEKkl8HcPAPbtYQG0VQO5iiHMHfjMzcRP+vv9cHcII6dddtQ==" /></div>
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
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="xkF17DqhQ1Qdwx+hEUQvF4XZFIvJL0ooyJliJJXKsc7HhZAXpE9MIvRptmHYdB5Dcj/FvuvpezMvhpzAXvWaRA==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="18779023" />

      <div class="select-menu js-menu-container js-select-menu">
        <a class="social-count js-social-count" href="/rayryeng/datasciencecoursera/watchers">
          2
        </a>
        <a href="/rayryeng/datasciencecoursera/subscription"
          class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
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

    <form accept-charset="UTF-8" action="/rayryeng/datasciencecoursera/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="+Zh8feSy1hgCtSLr60Qv2th8iUe96kUwsTNWkQCSZyyVvMmxzAdZEYiMwQfiBdiILaa4HRnCymaI42NXW0eW7Q==" /></div>
      <button
        class="minibutton with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar rayryeng/datasciencecoursera"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/rayryeng/datasciencecoursera/stargazers">
          2
        </a>
</form>
    <form accept-charset="UTF-8" action="/rayryeng/datasciencecoursera/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="kYjuC7EaYGLWc7K8OZbZor+JwFtQarpTsrwZgR5F28Ei3ipbnqX0qWoxgYoTiGpEMH6aagIfUI5KfGBj34vwCQ==" /></div>
      <button
        class="minibutton with-count js-toggler-target"
        aria-label="Star this repository" title="Star rayryeng/datasciencecoursera"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/rayryeng/datasciencecoursera/stargazers">
          2
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/rayryeng/datasciencecoursera/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="uJkD7U0gOXx2/q+V5bSUN8qsDYSwgLQE3oeu9hyxwpADmAwtvtLd1D84yDtblP9BVM8PF4ZdAvUbjNpeQM7+jg==" /></div>
            <button
                type="submit"
                class="minibutton with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of rayryeng/datasciencecoursera to your account"
                aria-label="Fork your own copy of rayryeng/datasciencecoursera to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/rayryeng/datasciencecoursera/network" class="social-count">8</a>
</form>        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/rayryeng" class="url fn" itemprop="url" rel="author"><span itemprop="title">rayryeng</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/rayryeng/datasciencecoursera" class="js-current-repository" data-pjax="#js-repo-pjax-container">datasciencecoursera</a></strong>

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
     data-issue-count-url="/rayryeng/datasciencecoursera/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/rayryeng/datasciencecoursera" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /rayryeng/datasciencecoursera">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/rayryeng/datasciencecoursera/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /rayryeng/datasciencecoursera/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
      <a href="/rayryeng/datasciencecoursera/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /rayryeng/datasciencecoursera/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>


      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/rayryeng/datasciencecoursera/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /rayryeng/datasciencecoursera/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/rayryeng/datasciencecoursera/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /rayryeng/datasciencecoursera/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/rayryeng/datasciencecoursera/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /rayryeng/datasciencecoursera/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/rayryeng/datasciencecoursera.git" readonly="readonly">
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
           value="git@github.com:rayryeng/datasciencecoursera.git" readonly="readonly">
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
           value="https://github.com/rayryeng/datasciencecoursera" readonly="readonly">
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


  <a href="github-windows://openRepo/https://github.com/rayryeng/datasciencecoursera" class="minibutton sidebar-button" title="Save rayryeng/datasciencecoursera to your computer and use it in GitHub Desktop." aria-label="Save rayryeng/datasciencecoursera to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/rayryeng/datasciencecoursera/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download the contents of rayryeng/datasciencecoursera as a zip file"
                   title="Download the contents of rayryeng/datasciencecoursera as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/rayryeng/datasciencecoursera/blob/a222864659ae509e98bd1536dabe45ec3042ef4f/RepData_PeerAssessment1/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:90e839a3d7c28407387a30ebaea146db -->

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
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
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
               href="/rayryeng/datasciencecoursera/blob/master/RepData_PeerAssessment1/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
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
    <a href="/rayryeng/datasciencecoursera/find/master"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/rayryeng/datasciencecoursera" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">datasciencecoursera</span></a></span></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/rayryeng/datasciencecoursera/tree/master/RepData_PeerAssessment1" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">RepData_PeerAssessment1</span></a></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="Raymond Phan" class="avatar" data-user="765375" height="24" src="https://avatars2.githubusercontent.com/u/765375?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/rayryeng" rel="author">rayryeng</a></span>
        <time datetime="2014-05-17T22:22:40Z" is="relative-time">May 17, 2014</time>
        <div class="commit-title">
            <a href="/rayryeng/datasciencecoursera/commit/b1be821ad7b85792130ffa9bf1ec48cba838b252" class="message" data-pjax="true" title="Commited Reproducible Research Peer Assessment #1">Commited Reproducible Research Peer Assessment #1</a>
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
            <img alt="Raymond Phan" data-user="765375" height="24" src="https://avatars2.githubusercontent.com/u/765375?v=3&amp;s=48" width="24" />
            <a href="/rayryeng">rayryeng</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">
      <div class="button-group">
        <a href="/rayryeng/datasciencecoursera/raw/master/RepData_PeerAssessment1/PA1_template.md" class="minibutton " id="raw-url">Raw</a>
          <a href="/rayryeng/datasciencecoursera/blame/master/RepData_PeerAssessment1/PA1_template.md" class="minibutton js-update-url-with-hash">Blame</a>
        <a href="/rayryeng/datasciencecoursera/commits/master/RepData_PeerAssessment1/PA1_template.md" class="minibutton " rel="nofollow">History</a>
      </div><!-- /.button-group -->

        <a class="octicon-button tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/rayryeng/datasciencecoursera?branch=master&amp;filepath=RepData_PeerAssessment1%2FPA1_template.md" aria-label="Open this file in GitHub for Windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/rayryeng/datasciencecoursera/edit/master/RepData_PeerAssessment1/PA1_template.md" aria-label="Clicking this button will fork this project so you can edit the file" class="tooltipped tooltipped-s inline-form edit-file-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="3yEVNzSFbDfOfqz6neWMfe75O1xRS0dc3aW3kxaTS9Bshsr16qqJ5ufEfxH113RrlJTwpBucpDZVyoWhTakAng==" /></div>
              <button class="web-edit-button"
                      type="submit"
                      data-hotkey="e"
                      data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/rayryeng/datasciencecoursera/delete/master/RepData_PeerAssessment1/PA1_template.md" aria-label="Fork this project and delete file" class="tooltipped tooltipped-s inline-form delete-file-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="tT8GA+u/deSaV4nklQV27mN6e71WzdEUu95LI274/ClqwFiVLr8+ZxvN6ncrHcTJjkDnnbqwGoxwJEmHPCxCiw==" /></div>
            <button class="web-edit-button"
                    type="submit"
                    data-disable-with>
              <span class="octicon octicon-trashcan "></span>
            </button>
</form>      </a>
    </div><!-- /.actions -->
    <div class="file-info">
        646 lines (532 sloc)
        <span class="file-info-divider"></span>
      35.041 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a id="user-content-reproducible-research-peer-assessment-assignment---week-2" class="anchor" href="#reproducible-research-peer-assessment-assignment---week-2" aria-hidden="true"><span class="octicon octicon-link"></span></a>Reproducible Research Peer Assessment Assignment - Week #2</h1>

<h1>
<a id="user-content-introduction" class="anchor" href="#introduction" aria-hidden="true"><span class="octicon octicon-link"></span></a>Introduction</h1>

<p>With the advancement of technology and the growth of the <strong>big data</strong> movement, it is now possible to collect a large amount of data about personal movement using activity monitoring devices.  Such examples are: <a href="http://www.fitbit.com/">Fitbit</a>, <a href="http://www.nike.com/us/en_us/c/nikeplus-fuelband">Nike Fuelband</a>, or <a href="https://jawbone.com/up">Jawbone Up</a>. These kinds of devices are part of the "quantified self" movement: those who  measurements about themselves on a regular basis in order to improve their health,  find patterns in their behaviour, or because they are simply technology geeks. However, these data remain severely underused due to the fact that the raw data are hard to obtain and there is a lack of statistical methods and software for processing and interpreting the data.</p>

<p>This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals throughout the day. The data consists of two months of data from an anonymous individual collected during the months of October and November 2012 and include the number of steps taken in 5 minute intervals each day.</p>

<p>The overall goal of this assignment is to make some basic exploratory data analysis to assess some activity patterns with regards to the anonymous individual's walking patterns.  For each day, there are readings taken at particular 5-minute intervals.  These readings correspond to the number of <strong>steps</strong> taken by the anonymous individual between the previous 5-minute interval to the current 5-minute interval.</p>

<h1>
<a id="user-content-data-layout" class="anchor" href="#data-layout" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Layout</h1>

<p>These intervals are assigned a unique ID which corresponds to the interval taken at that day.  As an example, the ID of <code>15</code> means that at the third observation (i.e. at the 15 minute mark), that is when the reading was taken for this day.  There are 61 days between October and November, and as such there are <code>61</code> observations recorded at the 15 minute mark.  Furthermore, there are 61 observations taken at the same time interval as they were taken each day within these two months.  As such, there are 61 observations for the 20 minute mark, the 30 minute mark, the 45 minute mark and so on.  In addition, for each day, there are <code>288</code> intervals / observations were recorded at per day.</p>

<p>As such, the data provided to us is a 3-column data frame:</p>

<ol class="task-list">
<li> Column 1 - <em>steps</em>: Indicates the number of steps taken during a neighbouring 5-minute interval (between 5 minutes and 10 minutes, 10 minutes and 15 minutes, etc.).  There were some instances where there were no readings taken, most likely due to the fact that the subject was sleeping or the device was shut off.  These are coded in as <code>NA</code> values.</li>
<li> Column 2 - <em>date</em>:  Indicates the date at which the measurement was taken.  This is in the <code>YYYY-MM-DD</code> format.</li>
<li> Column 3 - <em>interval</em>: The aforementioned ID that determines at which 5-minute interval the reading was taken at (5, 10, 15, 20, etc.)</li>
</ol>

<h1>
<a id="user-content-procedure" class="anchor" href="#procedure" aria-hidden="true"><span class="octicon octicon-link"></span></a>Procedure</h1>

<h2>
<a id="user-content-preamble" class="anchor" href="#preamble" aria-hidden="true"><span class="octicon octicon-link"></span></a>Preamble</h2>

<p>There are five steps overall in our analysis:</p>

<ol class="task-list">
<li> Loading in and preprocessing the data</li>
<li> Plotting a histogram of the total number of steps taken each day and calculating the mean and median of each day.</li>
<li> Determining the average daily activity pattern: Plotting a time-series plot for each 5-minute interval (the x-axis) with the average number of steps averaged across all days (the y-axis).  This means that for each 5-minute interval, calculate the average of the 61 observations taken at each interval.  We also calculate the median of the 61 observations taken at each interval as well.</li>
<li> Imputing missing values: There were some instances where the amount of steps read for an interval were missing.  These were coded in as <code>NA</code> values.  The presence of missing days may introduce bias into some calculations or summaries of the data.  In this step, a simple strategy was performed to replace the missing values in the dataset with a filler value.  This value was chosen to be the <strong>mean within the 5-minute interval the value was missing for</strong>.  For example, suppose on October 5, 2012, at the 10-minute interval there is missing data.  This data is filled in by the mean of whatever data was available overall (the 61 observations excluding the <code>NA</code> values) for this particular interval.  The analysis of Step #2 is repeated with similarities and differences being reported.</li>
<li> The last part of the analysis is to split up the data into weekdays and weekends and observe if there is any difference in activity patterns between these two classes.  The same kind of plot is repeated like in Step #3, but now there are two separate plots to reflect the activity on the weekdays and weekends.</li>
</ol>

<h2>
<a id="user-content-loading-in-and-preprocessing-data" class="anchor" href="#loading-in-and-preprocessing-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading in and preprocessing data</h2>

<p>Before we begin, it is imperative that the reader set the working directory to be where this R Markdown file (and subsequently all of the data for the analysis) is located.  This can be done with the <code>setwd()</code> command.</p>

<p>The first thing we obviously need to do is read in the data and clean it up so that it is presentable for analysis.  Dr. Roger Peng, being the most generous person on the planet, has already cleaned up the data for us.  However, the only thing that will be done is to convert the dates into a <code>POSIXlt</code> class for easier processing.  The data have been provided in a <code>.zip</code> archive file.  What we will do is unarchive the <code>.zip</code> file and read the data in using <code>read.csv()</code>.  After, the dates will be transformed into the <code>POSIXlt</code> class.</p>

<div class="highlight highlight-r"><pre>unzip(<span class="pl-s1"><span class="pl-pds">"</span>activity.zip<span class="pl-pds">"</span></span>)  <span class="pl-c"># Unzip archive</span>
<span class="pl-vo">dat</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s1"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>)  <span class="pl-c"># Read in data file</span>

<span class="pl-c"># Turn the date data into a valid date class Allows for easier processing</span>
<span class="pl-c"># Dates are in YYYY-MM-DD format</span>
<span class="pl-vo">dates</span> <span class="pl-k">&lt;-</span> strptime(<span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">date</span>, <span class="pl-s1"><span class="pl-pds">"</span>%Y-%m-%d<span class="pl-pds">"</span></span>)
<span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">date</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">dates</span>

<span class="pl-c"># Keep a list of all possible days</span>
<span class="pl-vo">uniqueDates</span> <span class="pl-k">&lt;-</span> unique(<span class="pl-vo">dates</span>)
<span class="pl-c"># Keep a list of all possible intervals</span>
<span class="pl-vo">uniqueIntervals</span> <span class="pl-k">&lt;-</span> unique(<span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">interval</span>)</pre></div>

<p>As for <code>uniqueDates</code> and <code>uniqueIntervals</code>, these are variables that store a list of all possible dates and intervals.  These will primarily be used to help plot our necessary data and for data processing.</p>

<h2>
<a id="user-content-what-is-the-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-the-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the mean total number of steps taken per day?</h2>

<p>First, let's plot a histogram of the total number of steps taken for each day.  Before we do this, let's split up the data into individual data frames where each data frame represents the data for a particular day.  After this, we will create a vector that accumulates all of the steps taken for each day and let it get stored into a vector.  Each element in this vector represents the total number of steps taken for a particular day (61 in total).  It should be noted that <code>NA</code> values will be ignored for the time being.  After, we will plot a histogram where the x-axis represents the particular day in question, while the y-axis denotes how many steps were taken in total for each day.  We will also calculate what the mean and median number of steps per day were as well.</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Part 2 - Create a histogram of the total number of steps taken each day</span>
<span class="pl-c"># First split up the data frame for steps by day</span>
<span class="pl-vo">stepsSplit</span> <span class="pl-k">&lt;-</span> split(<span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-vo">dates</span><span class="pl-k">$</span><span class="pl-vo">yday</span>)

<span class="pl-c"># Next find the total number of steps over each day</span>
<span class="pl-vo">totalStepsPerDay</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">stepsSplit</span>, <span class="pl-vo">sum</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)

<span class="pl-c"># Plot a (pseudo) histogram where the x-axis denotes the day and the y-axis</span>
<span class="pl-c"># denotes the total number of steps taken for each day</span>
plot(<span class="pl-vo">uniqueDates</span>, <span class="pl-vo">totalStepsPerDay</span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Histogram of steps taken each day<span class="pl-pds">"</span></span>, 
    <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Date (October to November 2012)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Frequency<span class="pl-pds">"</span></span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>h<span class="pl-pds">"</span></span>, 
    <span class="pl-v">lwd</span> <span class="pl-k">=</span> <span class="pl-c1">4</span>, <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>blue<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/rayryeng/datasciencecoursera/blob/master/RepData_PeerAssessment1/figure/unnamed-chunk-2.png" target="_blank"><img src="/rayryeng/datasciencecoursera/raw/master/RepData_PeerAssessment1/figure/unnamed-chunk-2.png" alt="plot of chunk unnamed-chunk-2" style="max-width:100%;"></a> </p>

<p>The mean steps per day are:</p>

<div class="highlight highlight-r"><pre><span class="pl-vo">meanStepsPerDay</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">stepsSplit</span>, <span class="pl-vo">mean</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
<span class="pl-vo">meanDataFrame</span> <span class="pl-k">&lt;-</span> <span class="pl-st">data.frame</span>(<span class="pl-v">date</span> <span class="pl-k">=</span> <span class="pl-vo">uniqueDates</span>, <span class="pl-v">meanStepsPerDay</span> <span class="pl-k">=</span> <span class="pl-vo">meanStepsPerDay</span>, 
    <span class="pl-v">row.names</span> <span class="pl-k">=</span> <span class="pl-c1">NULL</span>)
<span class="pl-vo">meanDataFrame</span></pre></div>

<pre><code>##          date meanStepsPerDay
## 1  2012-10-01             NaN
## 2  2012-10-02          0.4375
## 3  2012-10-03         39.4167
## 4  2012-10-04         42.0694
## 5  2012-10-05         46.1597
## 6  2012-10-06         53.5417
## 7  2012-10-07         38.2465
## 8  2012-10-08             NaN
## 9  2012-10-09         44.4826
## 10 2012-10-10         34.3750
## 11 2012-10-11         35.7778
## 12 2012-10-12         60.3542
## 13 2012-10-13         43.1458
## 14 2012-10-14         52.4236
## 15 2012-10-15         35.2049
## 16 2012-10-16         52.3750
## 17 2012-10-17         46.7083
## 18 2012-10-18         34.9167
## 19 2012-10-19         41.0729
## 20 2012-10-20         36.0938
## 21 2012-10-21         30.6285
## 22 2012-10-22         46.7361
## 23 2012-10-23         30.9653
## 24 2012-10-24         29.0104
## 25 2012-10-25          8.6528
## 26 2012-10-26         23.5347
## 27 2012-10-27         35.1354
## 28 2012-10-28         39.7847
## 29 2012-10-29         17.4236
## 30 2012-10-30         34.0938
## 31 2012-10-31         53.5208
## 32 2012-11-01             NaN
## 33 2012-11-02         36.8056
## 34 2012-11-03         36.7049
## 35 2012-11-04             NaN
## 36 2012-11-05         36.2465
## 37 2012-11-06         28.9375
## 38 2012-11-07         44.7326
## 39 2012-11-08         11.1771
## 40 2012-11-09             NaN
## 41 2012-11-10             NaN
## 42 2012-11-11         43.7778
## 43 2012-11-12         37.3785
## 44 2012-11-13         25.4722
## 45 2012-11-14             NaN
## 46 2012-11-15          0.1424
## 47 2012-11-16         18.8924
## 48 2012-11-17         49.7882
## 49 2012-11-18         52.4653
## 50 2012-11-19         30.6979
## 51 2012-11-20         15.5278
## 52 2012-11-21         44.3993
## 53 2012-11-22         70.9271
## 54 2012-11-23         73.5903
## 55 2012-11-24         50.2708
## 56 2012-11-25         41.0903
## 57 2012-11-26         38.7569
## 58 2012-11-27         47.3819
## 59 2012-11-28         35.3576
## 60 2012-11-29         24.4688
## 61 2012-11-30             NaN
</code></pre>

<p>The median steps per day are:</p>

<div class="highlight highlight-r"><pre><span class="pl-vo">medianStepsPerDay</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">stepsSplit</span>, <span class="pl-vo">median</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
<span class="pl-vo">medianDataFrame</span> <span class="pl-k">&lt;-</span> <span class="pl-st">data.frame</span>(<span class="pl-v">date</span> <span class="pl-k">=</span> <span class="pl-vo">uniqueDates</span>, <span class="pl-v">medianStepsPerDay</span> <span class="pl-k">=</span> <span class="pl-vo">medianStepsPerDay</span>, 
    <span class="pl-v">row.names</span> <span class="pl-k">=</span> <span class="pl-c1">NULL</span>)
<span class="pl-vo">medianDataFrame</span></pre></div>

<pre><code>##          date medianStepsPerDay
## 1  2012-10-01                NA
## 2  2012-10-02                 0
## 3  2012-10-03                 0
## 4  2012-10-04                 0
## 5  2012-10-05                 0
## 6  2012-10-06                 0
## 7  2012-10-07                 0
## 8  2012-10-08                NA
## 9  2012-10-09                 0
## 10 2012-10-10                 0
## 11 2012-10-11                 0
## 12 2012-10-12                 0
## 13 2012-10-13                 0
## 14 2012-10-14                 0
## 15 2012-10-15                 0
## 16 2012-10-16                 0
## 17 2012-10-17                 0
## 18 2012-10-18                 0
## 19 2012-10-19                 0
## 20 2012-10-20                 0
## 21 2012-10-21                 0
## 22 2012-10-22                 0
## 23 2012-10-23                 0
## 24 2012-10-24                 0
## 25 2012-10-25                 0
## 26 2012-10-26                 0
## 27 2012-10-27                 0
## 28 2012-10-28                 0
## 29 2012-10-29                 0
## 30 2012-10-30                 0
## 31 2012-10-31                 0
## 32 2012-11-01                NA
## 33 2012-11-02                 0
## 34 2012-11-03                 0
## 35 2012-11-04                NA
## 36 2012-11-05                 0
## 37 2012-11-06                 0
## 38 2012-11-07                 0
## 39 2012-11-08                 0
## 40 2012-11-09                NA
## 41 2012-11-10                NA
## 42 2012-11-11                 0
## 43 2012-11-12                 0
## 44 2012-11-13                 0
## 45 2012-11-14                NA
## 46 2012-11-15                 0
## 47 2012-11-16                 0
## 48 2012-11-17                 0
## 49 2012-11-18                 0
## 50 2012-11-19                 0
## 51 2012-11-20                 0
## 52 2012-11-21                 0
## 53 2012-11-22                 0
## 54 2012-11-23                 0
## 55 2012-11-24                 0
## 56 2012-11-25                 0
## 57 2012-11-26                 0
## 58 2012-11-27                 0
## 59 2012-11-28                 0
## 60 2012-11-29                 0
## 61 2012-11-30                NA
</code></pre>

<p>The median measure may look a bit puzzling, but if you observe the data for the amount of steps over some of the days, you will see that a majority of the steps taken are zero and so the mean would logically represent the 50th percentile.  Here is a sample between October 10th to October 12th of 2012:</p>

<div class="highlight highlight-r"><pre><span class="pl-vo">stepsSplit</span>[<span class="pl-c1">10</span><span class="pl-k">:</span><span class="pl-c1">12</span>]</pre></div>

<pre><code>## $`283`
##   [1]  34  18   7   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [18]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [35]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [52]   0   0   0   0   0   0   0   0   0   0  34   0   0   0   0   0   0
##  [69]   0   0   0   0   0   7   9  36   0  47  67   0  49  23  15  29  42
##  [86]  49  92  28  33  63  97  90 101  55  75  40  47  22  61   0   0   0
## [103]   0   0   0  60  54  16 135  61  69  32   0   0  17   0   0  69   0
## [120]  20 400 105 292 291  30   0   0  40  38   0   0   0   0   0   0  72
## [137]  37   0   0  25  17   0   0  88   7 413 326  93 334 317   0   0   0
## [154]   0  68 129   0   0   0   0   0   0   0   0   0   0   0   0   0   0
## [171] 103 119   0   0   0  70 125   0   0   0   0   0   0   0   0   0 176
## [188]  71  43 340   7  13  15   0   0   0   0   0   0   0   0   0   0  15
## [205]  50 271 106 272 308   0   0 111 281  11 139  36   0   0   0   0   0
## [222]   0  58  63 260  82 310   0   0   0   8  12 364 219   0   0   0 174
## [239] 205  12   0   0  11  17   0   0  37   0   0 105  34   0 152   0   0
## [256]   0   0   0   0   0   0   0   0   0   0   0   0 112  23  12   8   0
## [273]   0   0   0   0   7   0   0   0   0   0   0   0   0   0   8   0
## 
## $`284`
##   [1]   0   0   0   8   0   0   0   0   0   0   0   0   0   0   8   0   0
##  [18]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [35]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [52]   0   0   0   0   0 139  15   0   0   0   0   0   0   0   0   0   0
##  [69]   0   0   0  11   0  10  40   0   0  32  34 105  33   8  16  18   0
##  [86]   9   0   0  27  22   0  50   0   0   0  23  43  70 619 743 446 748
## [103] 424 747 739 741 726 166 548 343  13  26  64   0   0   0   0   0   0
## [120]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
## [137]   0   7  46   0   0   0   0   0   0   0   0  31  45   0   0   0   0
## [154]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
## [171]   0   0   0   0  22  27   0   0   0   0   0   0   0   0   0   0  75
## [188] 119 395  78 292 416  35   0   0  27  32   0   0   0   0   0  49  57
## [205]  34   0   0   0   0   0  39  30   9  41   7   0   0  40  22  31  19
## [222]   0   8  22  62  60   0   0   0   0   0   0   0   0   0   0   0   0
## [239]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0  95
## [256]   0  91  50  31   0   0   0  20  11   0   0   0   0   0   0   0   0
## [273]   0   0   0   0  11   0   0   0   0   4   0   0   0   0   0   0
## 
## $`285`
##   [1]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [18]   0  38   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [35]   7   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [52]   0   0   0  48   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [69]  30  92   0  11   0  10  19 111  38  16  29   9  45  35  53  43   8
##  [86]  40   0  32  57  35 117 117  25  95  29 141  51 123 440 687 614 474
## [103] 750 742 770 735 746 748 802 280  31   0   0   0   0   0   0   7  92
## [120]   0   0   0   0   0  46   7   0 328 156   0   0   0 129 339 150   0
## [137]   0   0  70   0   9   0   0   0  70   0   0   0   0   0   0   0  18
## [154]  91   0   0   0  75   0   0   0   0  99   0   0   0   0  96  16  20
## [171] 144 321 267   0   0   0   0   0   9   0   0  24  78   0  26  35   0
## [188]   0   0 365  90 432 275  34   0  92  15   0   0   0   0  20  10   9
## [205]   0   0  32  24   0   0  38  40  19  71   2  21   0 433 463 511 298
## [222] 500 473 506  24  35  41  46   0   0   0  16  23   0   0   0  18  54
## [239]  36   0   0   0   0   0   0   0   0   0   0  18  30  23  70 113   0
## [256]   0   0   0   0   0   0   0   0   0   0   0   0   9   0   0   8   0
## [273]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
</code></pre>

<h2>
<a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the average daily activity pattern?</h2>

<p>What we now need to do is split up this data again so that individual data frames represent the steps taken <strong>over each time interval</strong>.  As such, there will be a data frame for interval 5, another data frame for interval 10 and so on.  Once we extract out these individual data frames, we thus compute the mean for each time interval.  It is imperative to note that we again will ignore <code>NA</code> values.  We will thus plot the data as a time-series plot (of <code>type="l"</code>).  Once we have done this, we will locate where in the time-series plot the maximum is located and will draw a red vertical line to denote this location:</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Part 3 - Time-series plot (type='l') x-axis - Time interval (5, 10, 15,</span>
<span class="pl-c"># ...)  y-axis - Average number of steps taken across all days for this time</span>
<span class="pl-c"># interval</span>

<span class="pl-c"># Split up the data according to the interval</span>
<span class="pl-vo">intervalSplit</span> <span class="pl-k">&lt;-</span> split(<span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">interval</span>)

<span class="pl-c"># Find the average amount of steps per time interval - ignore NA values</span>
<span class="pl-vo">averageStepsPerInterval</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">intervalSplit</span>, <span class="pl-vo">mean</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)

<span class="pl-c"># Plot the time-series graph</span>
plot(<span class="pl-vo">uniqueIntervals</span>, <span class="pl-vo">averageStepsPerInterval</span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average number of steps per interval across all days<span class="pl-pds">"</span></span>, 
    <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Interval<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average # of steps across all days<span class="pl-pds">"</span></span>, <span class="pl-v">lwd</span> <span class="pl-k">=</span> <span class="pl-c1">2</span>, 
    <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>blue<span class="pl-pds">"</span></span>)

<span class="pl-c"># Find the location of where the maximum is</span>
<span class="pl-vo">maxIntervalDays</span> <span class="pl-k">&lt;-</span> max(<span class="pl-vo">averageStepsPerInterval</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
<span class="pl-vo">maxIndex</span> <span class="pl-k">&lt;-</span> as.numeric(which(<span class="pl-vo">averageStepsPerInterval</span> <span class="pl-k">==</span> <span class="pl-vo">maxIntervalDays</span>))

<span class="pl-c"># Plot a vertical line where the max is</span>
<span class="pl-vo">maxInterval</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">uniqueIntervals</span>[<span class="pl-vo">maxIndex</span>]
abline(<span class="pl-v">v</span> <span class="pl-k">=</span> <span class="pl-vo">maxInterval</span>, <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>red<span class="pl-pds">"</span></span>, <span class="pl-v">lwd</span> <span class="pl-k">=</span> <span class="pl-c1">3</span>)</pre></div>

<p><a href="/rayryeng/datasciencecoursera/blob/master/RepData_PeerAssessment1/figure/unnamed-chunk-6.png" target="_blank"><img src="/rayryeng/datasciencecoursera/raw/master/RepData_PeerAssessment1/figure/unnamed-chunk-6.png" alt="plot of chunk unnamed-chunk-6" style="max-width:100%;"></a> </p>

<p>With reference to the above plot, the interval that records the maximum number of steps averaged across all days is:</p>

<div class="highlight highlight-r"><pre><span class="pl-vo">maxInterval</span></pre></div>

<pre><code>## [1] 835
</code></pre>

<h2>
<a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing missing values</h2>

<p>First, let's calculate the total number of missing values there are.  This denotes the total number of observations that did not have any steps recorded (i.e. those rows which are <code>NA</code>)</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Part 4 - Calculate total amount of missing values in the data set Use</span>
<span class="pl-c"># complete.cases to find a logical vector that returns TRUE if it is a</span>
<span class="pl-c"># complete row (a.k.a. no NA values) and FALSE otherwise</span>
<span class="pl-vo">completeRowsBool</span> <span class="pl-k">&lt;-</span> complete.cases(<span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)
<span class="pl-vo">numNA</span> <span class="pl-k">&lt;-</span> sum(as.numeric(<span class="pl-k">!</span><span class="pl-vo">completeRowsBool</span>))
<span class="pl-vo">numNA</span></pre></div>

<pre><code>## [1] 2304
</code></pre>

<p>The strategy that we will use to fill in the missing values in the data set is to replace all <code>NA</code> values with the mean of that particular 5-minute interval the observation falls on.  Now that we have devised this strategy, let's replace all of the <code>NA</code> values with the aforementioned strategy.</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Modify the meanStepsPerDay vector that contains the mean steps taken for</span>
<span class="pl-c"># this 5 minute interval Each day consists of 288 intervals and there are 61</span>
<span class="pl-c"># days in total First remove NaN values and replace with 0.  NaN values are</span>
<span class="pl-c"># produced when the entire day was filled with NA values Essentially the</span>
<span class="pl-c"># mean and median would be zero anyway!</span>
<span class="pl-vo">meanStepsPerDay</span>[is.nan(<span class="pl-vo">meanStepsPerDay</span>)] <span class="pl-k">&lt;-</span> <span class="pl-c1">0</span>

<span class="pl-c"># Now create a replicated vector 288 times The reason why we're doing this</span>
<span class="pl-c"># is because the slots in the vector naturally line up with the interval for</span>
<span class="pl-c"># a particular day.  Now, all we have to do is find where in the data set</span>
<span class="pl-c"># there are missing steps, and simply do a copy from one vector to the other</span>
<span class="pl-vo">meanColumn</span> <span class="pl-k">&lt;-</span> rep(<span class="pl-vo">meanStepsPerDay</span>, <span class="pl-c1">288</span>)

<span class="pl-c"># The steps before replacement</span>
<span class="pl-vo">rawSteps</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">dat</span><span class="pl-k">$</span><span class="pl-vo">steps</span>

<span class="pl-c"># Find any values that are NA in the raw steps data</span>
<span class="pl-vo">stepsNA</span> <span class="pl-k">&lt;-</span> is.na(<span class="pl-vo">rawSteps</span>)

<span class="pl-c"># Now replace these values with their corresponding mean</span>
<span class="pl-vo">rawSteps</span>[<span class="pl-vo">stepsNA</span>] <span class="pl-k">&lt;-</span> <span class="pl-vo">meanColumn</span>[<span class="pl-vo">stepsNA</span>]

<span class="pl-c"># Throw these back into a new data frame</span>
<span class="pl-vo">datNew</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">dat</span>
<span class="pl-vo">datNew</span><span class="pl-k">$</span><span class="pl-vo">steps</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">rawSteps</span></pre></div>

<p>Now that this is finished, let's plot a histogram of the new data:</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Repeat Part 2 now First split up the data frame for steps by day</span>
<span class="pl-vo">stepsSplitNew</span> <span class="pl-k">&lt;-</span> split(<span class="pl-vo">datNew</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-vo">dates</span><span class="pl-k">$</span><span class="pl-vo">yday</span>)

<span class="pl-c"># Next find the total number of steps over each day There should not be an</span>
<span class="pl-c"># NA values and so we don't need to set the flag</span>
<span class="pl-vo">totalStepsPerDayNew</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">stepsSplitNew</span>, <span class="pl-vo">sum</span>)

<span class="pl-c"># Plot a (pseudo) histogram where the x-axis denotes the day and the y-axis</span>
<span class="pl-c"># denotes the total number of steps taken for each day</span>
par(<span class="pl-v">mfcol</span> <span class="pl-k">=</span> c(<span class="pl-c1">2</span>, <span class="pl-c1">1</span>))
<span class="pl-c"># Plot the original histogram first</span>
plot(<span class="pl-vo">uniqueDates</span>, <span class="pl-vo">totalStepsPerDay</span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Histogram of steps taken each day before imputing<span class="pl-pds">"</span></span>, 
    <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Date (October to November 2012)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Frequency<span class="pl-pds">"</span></span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>h<span class="pl-pds">"</span></span>, 
    <span class="pl-v">lwd</span> <span class="pl-k">=</span> <span class="pl-c1">4</span>, <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>blue<span class="pl-pds">"</span></span>)
<span class="pl-c"># Plot the modified histogram after</span>
plot(<span class="pl-vo">uniqueDates</span>, <span class="pl-vo">totalStepsPerDayNew</span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Histogram of steps taken each day after imputing<span class="pl-pds">"</span></span>, 
    <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Date (October to November 2012)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Frequency<span class="pl-pds">"</span></span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>h<span class="pl-pds">"</span></span>, 
    <span class="pl-v">lwd</span> <span class="pl-k">=</span> <span class="pl-c1">4</span>, <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>blue<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/rayryeng/datasciencecoursera/blob/master/RepData_PeerAssessment1/figure/unnamed-chunk-10.png" target="_blank"><img src="/rayryeng/datasciencecoursera/raw/master/RepData_PeerAssessment1/figure/unnamed-chunk-10.png" alt="plot of chunk unnamed-chunk-10" style="max-width:100%;"></a> </p>

<p>With this new data, let's calculate the mean over all days (like in Part 2).  As a side-by-side comparison, we will place the data before imputing, as well as the new one in the same data frame.  Bear in mind that we have replaced all of the <code>NaN</code> values to <code>0</code>.  As such, the mean steps per day of the new data are:</p>

<div class="highlight highlight-r"><pre><span class="pl-vo">meanStepsPerDayNew</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">stepsSplitNew</span>, <span class="pl-vo">mean</span>)
<span class="pl-vo">meanDataFrameNew</span> <span class="pl-k">&lt;-</span> <span class="pl-st">data.frame</span>(<span class="pl-v">date</span> <span class="pl-k">=</span> <span class="pl-vo">uniqueDates</span>, <span class="pl-v">meanStepsPerDay</span> <span class="pl-k">=</span> <span class="pl-vo">meanStepsPerDay</span>, 
    <span class="pl-v">meanStepsPerDayNew</span> <span class="pl-k">=</span> <span class="pl-vo">meanStepsPerDayNew</span>, <span class="pl-v">row.names</span> <span class="pl-k">=</span> <span class="pl-c1">NULL</span>)
<span class="pl-vo">meanDataFrameNew</span></pre></div>

<pre><code>##          date meanStepsPerDay meanStepsPerDayNew
## 1  2012-10-01          0.0000            32.3355
## 2  2012-10-02          0.4375             0.4375
## 3  2012-10-03         39.4167            39.4167
## 4  2012-10-04         42.0694            42.0694
## 5  2012-10-05         46.1597            46.1597
## 6  2012-10-06         53.5417            53.5417
## 7  2012-10-07         38.2465            38.2465
## 8  2012-10-08          0.0000            32.2632
## 9  2012-10-09         44.4826            44.4826
## 10 2012-10-10         34.3750            34.3750
## 11 2012-10-11         35.7778            35.7778
## 12 2012-10-12         60.3542            60.3542
## 13 2012-10-13         43.1458            43.1458
## 14 2012-10-14         52.4236            52.4236
## 15 2012-10-15         35.2049            35.2049
## 16 2012-10-16         52.3750            52.3750
## 17 2012-10-17         46.7083            46.7083
## 18 2012-10-18         34.9167            34.9167
## 19 2012-10-19         41.0729            41.0729
## 20 2012-10-20         36.0938            36.0938
## 21 2012-10-21         30.6285            30.6285
## 22 2012-10-22         46.7361            46.7361
## 23 2012-10-23         30.9653            30.9653
## 24 2012-10-24         29.0104            29.0104
## 25 2012-10-25          8.6528             8.6528
## 26 2012-10-26         23.5347            23.5347
## 27 2012-10-27         35.1354            35.1354
## 28 2012-10-28         39.7847            39.7847
## 29 2012-10-29         17.4236            17.4236
## 30 2012-10-30         34.0938            34.0938
## 31 2012-10-31         53.5208            53.5208
## 32 2012-11-01          0.0000            32.0149
## 33 2012-11-02         36.8056            36.8056
## 34 2012-11-03         36.7049            36.7049
## 35 2012-11-04          0.0000            32.4505
## 36 2012-11-05         36.2465            36.2465
## 37 2012-11-06         28.9375            28.9375
## 38 2012-11-07         44.7326            44.7326
## 39 2012-11-08         11.1771            11.1771
## 40 2012-11-09          0.0000            32.3079
## 41 2012-11-10          0.0000            32.8707
## 42 2012-11-11         43.7778            43.7778
## 43 2012-11-12         37.3785            37.3785
## 44 2012-11-13         25.4722            25.4722
## 45 2012-11-14          0.0000            32.9865
## 46 2012-11-15          0.1424             0.1424
## 47 2012-11-16         18.8924            18.8924
## 48 2012-11-17         49.7882            49.7882
## 49 2012-11-18         52.4653            52.4653
## 50 2012-11-19         30.6979            30.6979
## 51 2012-11-20         15.5278            15.5278
## 52 2012-11-21         44.3993            44.3993
## 53 2012-11-22         70.9271            70.9271
## 54 2012-11-23         73.5903            73.5903
## 55 2012-11-24         50.2708            50.2708
## 56 2012-11-25         41.0903            41.0903
## 57 2012-11-26         38.7569            38.7569
## 58 2012-11-27         47.3819            47.3819
## 59 2012-11-28         35.3576            35.3576
## 60 2012-11-29         24.4688            24.4688
## 61 2012-11-30          0.0000            32.2280
</code></pre>

<p>Like the above, the median steps per day are:</p>

<div class="highlight highlight-r"><pre><span class="pl-vo">medianStepsPerDayNew</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">stepsSplitNew</span>, <span class="pl-vo">median</span>)
<span class="pl-vo">medianDataFrameNew</span> <span class="pl-k">&lt;-</span> <span class="pl-st">data.frame</span>(<span class="pl-v">date</span> <span class="pl-k">=</span> <span class="pl-vo">uniqueDates</span>, <span class="pl-v">medianStepsPerDay</span> <span class="pl-k">=</span> <span class="pl-vo">medianStepsPerDay</span>, 
    <span class="pl-v">medianStepsPerDayNew</span> <span class="pl-k">=</span> <span class="pl-vo">medianStepsPerDayNew</span>, <span class="pl-v">row.names</span> <span class="pl-k">=</span> <span class="pl-c1">NULL</span>)
<span class="pl-vo">medianDataFrameNew</span></pre></div>

<pre><code>##          date medianStepsPerDay medianStepsPerDayNew
## 1  2012-10-01                NA                36.09
## 2  2012-10-02                 0                 0.00
## 3  2012-10-03                 0                 0.00
## 4  2012-10-04                 0                 0.00
## 5  2012-10-05                 0                 0.00
## 6  2012-10-06                 0                 0.00
## 7  2012-10-07                 0                 0.00
## 8  2012-10-08                NA                36.09
## 9  2012-10-09                 0                 0.00
## 10 2012-10-10                 0                 0.00
## 11 2012-10-11                 0                 0.00
## 12 2012-10-12                 0                 0.00
## 13 2012-10-13                 0                 0.00
## 14 2012-10-14                 0                 0.00
## 15 2012-10-15                 0                 0.00
## 16 2012-10-16                 0                 0.00
## 17 2012-10-17                 0                 0.00
## 18 2012-10-18                 0                 0.00
## 19 2012-10-19                 0                 0.00
## 20 2012-10-20                 0                 0.00
## 21 2012-10-21                 0                 0.00
## 22 2012-10-22                 0                 0.00
## 23 2012-10-23                 0                 0.00
## 24 2012-10-24                 0                 0.00
## 25 2012-10-25                 0                 0.00
## 26 2012-10-26                 0                 0.00
## 27 2012-10-27                 0                 0.00
## 28 2012-10-28                 0                 0.00
## 29 2012-10-29                 0                 0.00
## 30 2012-10-30                 0                 0.00
## 31 2012-10-31                 0                 0.00
## 32 2012-11-01                NA                35.94
## 33 2012-11-02                 0                 0.00
## 34 2012-11-03                 0                 0.00
## 35 2012-11-04                NA                36.17
## 36 2012-11-05                 0                 0.00
## 37 2012-11-06                 0                 0.00
## 38 2012-11-07                 0                 0.00
## 39 2012-11-08                 0                 0.00
## 40 2012-11-09                NA                35.94
## 41 2012-11-10                NA                36.09
## 42 2012-11-11                 0                 0.00
## 43 2012-11-12                 0                 0.00
## 44 2012-11-13                 0                 0.00
## 45 2012-11-14                NA                36.09
## 46 2012-11-15                 0                 0.00
## 47 2012-11-16                 0                 0.00
## 48 2012-11-17                 0                 0.00
## 49 2012-11-18                 0                 0.00
## 50 2012-11-19                 0                 0.00
## 51 2012-11-20                 0                 0.00
## 52 2012-11-21                 0                 0.00
## 53 2012-11-22                 0                 0.00
## 54 2012-11-23                 0                 0.00
## 55 2012-11-24                 0                 0.00
## 56 2012-11-25                 0                 0.00
## 57 2012-11-26                 0                 0.00
## 58 2012-11-27                 0                 0.00
## 59 2012-11-28                 0                 0.00
## 60 2012-11-29                 0                 0.00
## 61 2012-11-30                NA                35.94
</code></pre>

<p>By looking at the above data frames, the only values that have changed are those days where all of the observations were missing (i.e. those days having all zeroes / <code>NA</code>).  The rest of the observations have stayed the same, which actually make sense.  The reason why this is is because if you insert more data values into a vector that are the mean of that particular vector, taking the mean will still give you the same answer.  With regards to the median vector, those rows that were filled with <code>NA</code> had all of their observations on that day filled with the mean value and so the median would obviously be the mean as well.</p>

<h2>
<a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<p>With the new data set we have just created, we are going to split up the data into two data frames - one data frame consists of all steps taken on a weekday, while the other data frame consists of all steps taken on a weekend.  The following <code>R</code> code illustrates this for us:</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Part 5 - Now split up the data so that it's sorted by weekday or weekend</span>
<span class="pl-c"># We have casted the dates to a POSIXlt class so wday is part of this class</span>
<span class="pl-c"># wday is an integer ranging from 0 to 6 that represents the day of the week</span>
<span class="pl-c"># 0 is for Sunday, 1 is for Monday, going up to 6 for Saturday Store this</span>
<span class="pl-c"># into wdays</span>
<span class="pl-vo">wdays</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">dates</span><span class="pl-k">$</span><span class="pl-vo">wday</span>

<span class="pl-c"># Create a new factor variable that classifies the day as either a weekday</span>
<span class="pl-c"># or weekend First, create a numeric vector with 2 levels - 1 is for a</span>
<span class="pl-c"># weekday, 2 for a weekend</span>
<span class="pl-vo">classifywday</span> <span class="pl-k">&lt;-</span> rep(<span class="pl-c1">0</span>, <span class="pl-c1">17568</span>)  <span class="pl-c"># 17568 observations overall</span>

<span class="pl-c"># Any days that are from Monday to Friday, set the numeric vector in these</span>
<span class="pl-c"># positions as 1</span>
<span class="pl-vo">classifywday</span>[<span class="pl-vo">wdays</span> <span class="pl-k">&gt;</span><span class="pl-k">=</span> <span class="pl-c1">1</span> <span class="pl-k">&amp;</span> <span class="pl-vo">wdays</span> <span class="pl-k">&lt;</span><span class="pl-k">=</span> <span class="pl-c1">5</span>] <span class="pl-k">&lt;-</span> <span class="pl-c1">1</span>

<span class="pl-c"># Any days that are on Saturday or Sunday, set the numeric vector in these</span>
<span class="pl-c"># positions as 2</span>
<span class="pl-vo">classifywday</span>[<span class="pl-vo">wdays</span> <span class="pl-k">==</span> <span class="pl-c1">6</span> <span class="pl-k">|</span> <span class="pl-vo">wdays</span> <span class="pl-k">==</span> <span class="pl-c1">0</span>] <span class="pl-k">&lt;-</span> <span class="pl-c1">2</span>

<span class="pl-c"># Create a new factor variable that has labels Weekdays and Weekends</span>
<span class="pl-vo">daysFactor</span> <span class="pl-k">&lt;-</span> <span class="pl-st">factor</span>(<span class="pl-vo">classifywday</span>, <span class="pl-v">levels</span> <span class="pl-k">=</span> c(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>), <span class="pl-v">labels</span> <span class="pl-k">=</span> c(<span class="pl-s1"><span class="pl-pds">"</span>Weekdays<span class="pl-pds">"</span></span>, 
    <span class="pl-s1"><span class="pl-pds">"</span>Weekends<span class="pl-pds">"</span></span>))

<span class="pl-c"># Create a new column that contains this factor for each day</span>
<span class="pl-vo">datNew</span><span class="pl-k">$</span><span class="pl-vo">typeOfDay</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">daysFactor</span>

<span class="pl-c"># Now split up into two data frames</span>
<span class="pl-vo">datWeekdays</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">datNew</span>[<span class="pl-vo">datNew</span><span class="pl-k">$</span><span class="pl-vo">typeOfDay</span> <span class="pl-k">==</span> <span class="pl-s1"><span class="pl-pds">"</span>Weekdays<span class="pl-pds">"</span></span>, ]
<span class="pl-vo">datWeekends</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">datNew</span>[<span class="pl-vo">datNew</span><span class="pl-k">$</span><span class="pl-vo">typeOfDay</span> <span class="pl-k">==</span> <span class="pl-s1"><span class="pl-pds">"</span>Weekends<span class="pl-pds">"</span></span>, ]</pre></div>

<p>Now that we have accomplished this, let's split up the data for each data frame so that we will have two sets of individual data frames.  One set is for weekdays and within this data frame are individual data frames.  Each data frame contains the steps for each interval recorded on a weekday.  The other set is for weekends, and within this data frame are individual data frames.  Like previously, each data frame here contains the steps for each interval recorded on a weekday.  Once we have these two sets of data frames, we will now calculate the mean amount of steps for each interval for the weekdays data frame and weekends data frame.  This will result in two vectors - one for the weekdays and the other for weekends.  The following <code>R</code> code does this for us:</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Further split up the Weekdays and Weekends into their own intervals</span>
<span class="pl-vo">datSplitWeekdays</span> <span class="pl-k">&lt;-</span> split(<span class="pl-vo">datWeekdays</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-vo">datWeekdays</span><span class="pl-k">$</span><span class="pl-vo">interval</span>)
<span class="pl-vo">datSplitWeekends</span> <span class="pl-k">&lt;-</span> split(<span class="pl-vo">datWeekends</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-vo">datWeekends</span><span class="pl-k">$</span><span class="pl-vo">interval</span>)

<span class="pl-c"># Find the average for each interval</span>
<span class="pl-vo">meanStepsPerWeekdayInterval</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">datSplitWeekdays</span>, <span class="pl-vo">mean</span>)
<span class="pl-vo">meanStepsPerWeekendInterval</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-vo">datSplitWeekends</span>, <span class="pl-vo">mean</span>)

par(<span class="pl-v">mfcol</span> <span class="pl-k">=</span> c(<span class="pl-c1">2</span>, <span class="pl-c1">1</span>))
plot(<span class="pl-vo">uniqueIntervals</span>, <span class="pl-vo">meanStepsPerWeekdayInterval</span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average number of steps per interval across all weekdays<span class="pl-pds">"</span></span>, 
    <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Interval<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average # of steps across all weekdays<span class="pl-pds">"</span></span>, <span class="pl-v">lwd</span> <span class="pl-k">=</span> <span class="pl-c1">2</span>, 
    <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>blue<span class="pl-pds">"</span></span>)
plot(<span class="pl-vo">uniqueIntervals</span>, <span class="pl-vo">meanStepsPerWeekendInterval</span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average number of steps per interval across all weekends<span class="pl-pds">"</span></span>, 
    <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Interval<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average # of steps across all weekends<span class="pl-pds">"</span></span>, <span class="pl-v">lwd</span> <span class="pl-k">=</span> <span class="pl-c1">2</span>, 
    <span class="pl-v">col</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>blue<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/rayryeng/datasciencecoursera/blob/master/RepData_PeerAssessment1/figure/unnamed-chunk-14.png" target="_blank"><img src="/rayryeng/datasciencecoursera/raw/master/RepData_PeerAssessment1/figure/unnamed-chunk-14.png" alt="plot of chunk unnamed-chunk-14" style="max-width:100%;"></a> </p>

<p>What is interesting about this plot is that it very much sums up the activity that any normal person would undergo depending on whether it is a weekday or weekend.  For both days, the intervals between <code>0</code> and about <code>525</code> are uniform.  This most likely represents when the subject was sleeping.  The differences start at between <code>525</code> and roughly <code>800</code>.  On the weekdays, movement is most likely attributed to the subject getting ready to go to work or starting their day.  On the weekends, movement is less frequent.  This could be attributed to the subject sleeping in and perhaps making breakfast to start their day.</p>

<p>There is a huge jump at roughly <code>830</code> for the weekdays.  This could be attributed to the subject walking or making their way to work.  On the weekends this behaviour is mimicked as well, perhaps due to making their way to begin engaging in some extracurricular activities that the subject is engaged in.  Now where it really gets different is at roughly the <code>1000</code> mark.  On the weekdays, this could be reflected with the subject being at work and there is not much movement.  A good indication of this behaviour could be attributed to the fact that the subject has a low stress job that requires minimal movement.  On the weekends, the behaviour varies wildly.  This could be attributed to the extra amount of movement required to engage in such extracurricular activities.</p>

<p>Where it starts to become similar again is at roughly the <code>1700</code> mark. This could mean that during the weekdays, the subject is getting ready to head home for the day which is why there is an increased amount of moment in comparison to the interval between <code>1000</code> to <code>1700</code>.  At the same time with the weekends, there is a relative amount of increased moment after the <code>1700</code> mark but it could reflect that at this time of day, the subject may be socializing.</p>

<p>All in all, this seems to reflect the behaviour of an individual going through a normal work day during the weekdays, and having a relaxing time on the weekends.</p>
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
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.06219s from github-fe133-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
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


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-4bf9533935259bb898a8d60e1958f4d047968c430eae889800a187e279faf38f.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-b00b171df9a5abd04c9ba116c3d8550fc466e3323e2d415771fc67bc071e10fb.js"></script>
      
      

  </body>
</html>

