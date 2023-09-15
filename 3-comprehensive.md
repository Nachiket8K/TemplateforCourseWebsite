<!DOCTYPE html>

<html lang="en-us">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1" name="viewport"/>
<meta content="IE=edge" http-equiv="X-UA-Compatible"/>
<meta content="Wowchemy 5.6.0 for Hugo" name="generator"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link as="style" href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&amp;display=swap" rel="preload"/>
<link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&amp;display=swap" media="print" onload="this.media='all'" rel="stylesheet"/>
<meta content="3) A comprehensive approach: the GDS Docker container (slightly more advanced and complicated installation) If meet the following requirements, Docker is a stable alternative and works out of the box:" name="description"/>
<link href="https://cusp.tbm.tudelft.nl/courses/epa1316/software/3-comprehensive/" hreflang="en-us" rel="alternate">
<meta content="#4da7e2" name="theme-color"/>
<script src="/js/mathjax-config.js"></script>
<link href="/css/vendor-bundle.min.16f785cdb553c8c4431db6775122af35.css" media="print" onload="this.media='all'" rel="stylesheet"/>
<link crossorigin="anonymous" href="https://cdn.jsdelivr.net/npm/academicons@1.9.1/css/academicons.min.css" integrity="sha512-W0xM4mr6dEP9nREo7Z9z+9X70wytKvMGeDsj7ps2+xg5QPrEBXC8tAW1IFnzjR6eoJ90JmCnFzerQJTLzIEHjA==" media="print" onload="this.media='all'" rel="stylesheet"/>
<link crossorigin="anonymous" href="https://cdn.jsdelivr.net/npm/leaflet@1.7.1/dist/leaflet.min.css" integrity="" media="print" onload="this.media='all'" rel="stylesheet"/>
<script async="" crossorigin="anonymous" integrity="" src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>
<link href="/css/wowchemy.6f389c40f29cb308dc64fcc64b98f536.css" rel="stylesheet">
<link href="/css/libs/chroma/github-light.min.css" media="print" onload="this.media='all'" rel="stylesheet" title="hl-light"/>
<link disabled="" href="/css/libs/chroma/dracula.min.css" media="print" onload="this.media='all'" rel="stylesheet" title="hl-dark"/>
<link href="/manifest.webmanifest" rel="manifest">
<link href="/media/icon_hu38c8316e677b7054cbb6a6936b86164f_6909_32x32_fill_lanczos_center_3.png" rel="icon" type="image/png">
<link href="/media/icon_hu38c8316e677b7054cbb6a6936b86164f_6909_180x180_fill_lanczos_center_3.png" rel="apple-touch-icon" type="image/png">
<link href="https://cusp.tbm.tudelft.nl/courses/epa1316/software/3-comprehensive/" rel="canonical">
<meta content="summary_large_image" property="twitter:card"/>
<meta content="@TrivikV" property="twitter:site"/>
<meta content="@TrivikV" property="twitter:creator"/>
<meta content="CUSP - Centre for Urban Science &amp; Policy at TU Delft" property="og:site_name"/>
<meta content="https://cusp.tbm.tudelft.nl/courses/epa1316/software/3-comprehensive/" property="og:url"/>
<meta content="Comprehensive Installation | CUSP - Centre for Urban Science &amp; Policy at TU Delft" property="og:title"/>
<meta content="3) A comprehensive approach: the GDS Docker container (slightly more advanced and complicated installation) If meet the following requirements, Docker is a stable alternative and works out of the box:" property="og:description"/><meta content="https://cusp.tbm.tudelft.nl/media/sharing.jpeg" property="og:image"/>
<meta content="https://cusp.tbm.tudelft.nl/media/sharing.jpeg" property="twitter:image"/><meta content="en-us" property="og:locale"/>
<meta content="2019-05-05T00:00:00+00:00" property="article:published_time"/>
<meta content="2019-05-05T00:00:00+00:00" property="article:modified_time"/>
<script crossorigin="anonymous" integrity="sha512-yXXqOFjdjHNH1GND+1EO0jbvvebABpzGKD66djnUfiKlYME5HGMUJHoCaeE4D5PTG2YsSJf6dwqyUUvQvS0vaA==" src="https://cdn.jsdelivr.net/gh/osano/cookieconsent@3.1.1/build/cookieconsent.min.js"></script>
<link crossorigin="anonymous" href="https://cdn.jsdelivr.net/gh/osano/cookieconsent@3.1.1/build/cookieconsent.min.css" integrity="sha512-LQ97camar/lOliT/MqjcQs5kWgy6Qz/cCRzzRzUCfv0fotsCTC9ZHXaPQmJV8Xu/PVALfJZ7BDezl5lW3/qBxg==" rel="stylesheet"/>
<script>
  window.addEventListener("load", function(){
    window.cookieconsent.initialise({
      "palette": {
        "popup": {
          "background": "#4da7e2",
          "text": "rgb(255, 255, 255)"
        },
        "button": {
          "background": "rgb(255, 255, 255)",
          "text": "#4da7e2"
        }
      },
      "theme": "classic",
      "content": {
        "message": "This website uses cookies to ensure you get the best experience on our website.",
        "dismiss": "Got it!",
        "link": "Learn more",
        "href": "https://www.cookiesandyou.com"
      }
    })});
  </script>
<title>Comprehensive Installation | CUSP - Centre for Urban Science &amp; Policy at TU Delft</title>
</link></link></link></link></link></link></head>
<body class="page-wrapper" data-offset="70" data-spy="scroll" data-target="#TableOfContents" data-wc-page-id="33bbd0807feb163024b554ab761490b9" id="top">
<script src="/js/wowchemy-init.min.1ee5462d74c6c0de1f8881b384ecc58d.js"></script>
<aside class="search-modal" id="search">
<div class="container">
<section class="search-header">
<div class="row no-gutters justify-content-between mb-3">
<div class="col-6">
<h1>Search</h1>
</div>
<div class="col-6 col-search-close">
<a aria-label="Close" class="js-search" href="#"><i aria-hidden="true" class="fas fa-times-circle text-muted"></i></a>
</div>
</div>
<div id="search-box">
<input aria-label="Search..." autocapitalize="off" autocomplete="off" autocorrect="off" class="form-control" id="search-query" name="q" placeholder="Search..." spellcheck="false" type="search"/>
</div>
</section>
<section class="section-search-results">
<div id="search-hits">
</div>
</section>
</div>
</aside>
<div class="page-header">
<header class="header--fixed">
<nav class="navbar navbar-expand-lg navbar-light compensate-for-scrollbar" id="navbar-main">
<div class="container-xl">
<div class="d-none d-lg-inline-flex">
<a class="navbar-brand" href="/"><img alt="CUSP - Centre for Urban Science &amp; Policy at TU Delft" src="/media/logo_hubf544d6f28f20c67a790d318df4382fe_107776_0x70_resize_lanczos_3.png"/></a>
</div>
<button aria-controls="navbar-content" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler" data-target="#navbar-content" data-toggle="collapse" type="button">
<span><i class="fas fa-bars"></i></span>
</button>
<div class="navbar-brand-mobile-wrapper d-inline-flex d-lg-none">
<a class="navbar-brand" href="/"><img alt="CUSP - Centre for Urban Science &amp; Policy at TU Delft" src="/media/logo_hubf544d6f28f20c67a790d318df4382fe_107776_0x70_resize_lanczos_3.png"/></a>
</div>
<div class="navbar-collapse main-menu-item collapse justify-content-start" id="navbar-content">
<ul class="navbar-nav d-md-inline-flex">
<li class="nav-item">
<a class="nav-link" href="/#aboutsite"><span>About</span></a>
</li>
<li class="nav-item">
<a class="nav-link" href="/research/"><span>Research</span></a>
</li>
<li class="nav-item">
<a class="nav-link" href="/teaching/"><span>Teaching</span></a>
</li>
<li class="nav-item">
<a class="nav-link" href="/people/"><span>People</span></a>
</li>
<li class="nav-item">
<a class="nav-link" href="/opportunities/"><span>Opportunities</span></a>
</li>
<li class="nav-item">
<a class="nav-link" href="/welcome/"><span>Philosophy</span></a>
</li>
</ul>
<ul class="navbar-nav ml-md-auto">
<li class="nav-item">
<a class="nav-link" href="https://www.citizens-collective.org/" rel="noopener" target="_blank"><span><span class="btn btn-primary d-none d-lg-inline-block mb-3 mb-md-0 ml-md-3">Citizens Collective</span></span></a>
</li>
</ul>
</div>
<ul class="nav-icons navbar-nav flex-row ml-auto d-flex pl-md-2">
<li class="nav-item d-none d-lg-inline-flex">
<a aria-label="Follow me on Twitter" class="nav-link" data-placement="bottom" data-toggle="tooltip" href="https://twitter.com/TrivikV" rel="noopener" target="_blank" title="Follow me on Twitter">
<i aria-hidden="true" class="fab fa-twitter"></i>
</a>
</li>
</ul>
</div>
</nav>
</header>
</div>
<div class="page-body">
<div class="container-fluid docs">
<div class="row flex-xl-nowrap">
<div class="col-12 col-md-3 col-xl-2 docs-sidebar">
<form class="docs-search d-flex align-items-center">
<button aria-controls="docs-nav" aria-expanded="false" aria-label="Toggle section navigation" class="btn docs-toggle d-md-none p-0 mr-md-3 w-100" data-target="#docs-nav" data-toggle="collapse" type="button">
<div class="d-flex">
<span class="d-md-none pl-1 flex-grow-1 text-left overflow-hidden">
        
        
          Software
        
      </span>
<span><i class="fas fa-chevron-down"></i></span>
</div>
</button>
<button class="form-control sidebar-search js-search d-none d-md-flex">
<i class="fas fa-search pr-2"></i>
<span class="sidebar-search-text">Search...</span>
<span class="sidebar-search-shortcut">/</span>
</button>
</form>
<nav class="collapse docs-links" id="docs-nav">
<ul class="nav docs-sidenav">
<li><a href="/courses/"><i class="fas fa-arrow-left pr-1"></i>Courses</a></li>
</ul>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/">EPA 1316 A</a>
<ul class="nav docs-sidenav">
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/introduction/">👋🏽 Introduction</a>
<ul class="nav docs-sidenav">
<li class=""><a href="/courses/epa1316/introduction/tobeginwith/">To Begin With</a></li>
<li class=""><a href="/courses/epa1316/introduction/overview/">Overview</a></li>
<li class=""><a href="/courses/epa1316/introduction/syllabus/">Syllabus</a></li>
<li class=""><a href="/courses/epa1316/introduction/schedule/">Schedule</a></li>
</ul>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/lectures/"><i class="fa fa-user-secret pr-1"></i>Lectures</a>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/labs/"><i class="fa fa-terminal pr-1"></i>Labs</a>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/discussions/"><i class="fa fa-people-group pr-1"></i>Discussions</a>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/assessment/"><i class="fa fa-graduation-cap pr-1"></i>Assessment</a>
<ul class="nav docs-sidenav">
<li class=""><a href="/courses/epa1316/assessment/assignment/">Assignments</a></li>
<li class=""><a href="/courses/epa1316/assessment/final-project/">Final Project</a></li>
<li class=""><a href="/courses/epa1316/assessment/project-template/">Project Template</a></li>
</ul>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/software/"><i class="fab fa-python pr-1"></i>Software</a>
<ul class="nav docs-sidenav">
<li class=""><a href="/courses/epa1316/software/1-standard/">1. Standard Installation</a></li>
<li class=""><a href="/courses/epa1316/software/2-minimalist/">2. Minimalist Installation</a></li>
<li class="active"><a href="/courses/epa1316/software/3-comprehensive/">3. Comprehensive Installation</a></li>
<li class=""><a href="/courses/epa1316/software/environment/">Virtual Environments</a></li>
</ul>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/resources/"><i class="fa fa-hand-holding-heart pr-1"></i>Resources</a>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/faq/"><i class="fa fa-hand-holding-hand pr-1"></i>FAQ</a>
</div>
</ul>
</div>
</nav>
</div>
<div class="d-none d-xl-block col-xl-2 docs-toc">
<ul class="nav toc-top">
<li><a class="docs-toc-title" href="#" id="back_to_top">Contents</a></li>
</ul>
<nav id="TableOfContents">
<ul>
<li><a href="#3-a-comprehensive-approach-the-gds-docker-container-slightly-more-advanced-and-complicated-installation">3) A comprehensive approach: the GDS Docker container (slightly more advanced and complicated installation)</a></li>
<li><a href="#mark-macos-installation-mark"><mark> <strong>MacOS Installation</strong> </mark></a></li>
<li><a href="#1-installation">1. Installation</a>
<ul>
<li><a href="#requirements">Requirements</a></li>
<li><a href="#docker-install-steps">Docker install steps</a></li>
<li><a href="#using-docker">Using Docker</a></li>
<li><a href="#installing-the-gds-environment">Installing the GDS environment</a></li>
<li><a href="#check-success">Check success</a></li>
</ul>
</li>
<li><a href="#2-running-python">2. Running Python</a>
<ul>
<li><a href="#running-the-container">Running the container</a></li>
<li><a href="#using-jupyter-notebook">Using Jupyter Notebook</a></li>
<li><a href="#ending-your-session">Ending your session</a></li>
</ul>
</li>
<li><a href="#mark-linux-installation-mark"><mark> <strong>Linux Installation</strong> </mark></a></li>
<li><a href="#1-installation-1">1. Installation</a>
<ul>
<li><a href="#requirements-1">Requirements</a></li>
<li><a href="#docker-install-steps-1">Docker install steps</a></li>
<li><a href="#installing-the-gds-container">Installing the GDS container</a></li>
<li><a href="#check-success-1">Check success</a></li>
</ul>
</li>
<li><a href="#2-running-python-1">2. Running Python</a>
<ul>
<li><a href="#running-the-container-1">Running the container</a></li>
<li><a href="#using-jupyter-notebook-1">Using Jupyter Notebook</a></li>
<li><a href="#ending-your-session-1">Ending your session</a></li>
</ul>
</li>
<li><a href="#mark-windows-mark"><mark> <strong>Windows</strong> </mark></a></li>
<li><a href="#1-installation-2">1. Installation</a>
<ul>
<li><a href="#requirements-2">Requirements</a></li>
<li><a href="#docker-install-steps-2">Docker install steps</a></li>
<li><a href="#installing-the-gds-container-1">Installing the GDS container</a></li>
<li><a href="#check-success-2">Check success</a></li>
</ul>
</li>
<li><a href="#2-running-python-2">2. Running Python</a>
<ul>
<li><a href="#running-the-container-2">Running the container</a></li>
<li><a href="#using-jupyter-notebook-2">Using Jupyter Notebook</a></li>
<li><a href="#ending-your-session-2">Ending your session</a></li>
</ul>
</li>
</ul>
</nav>
</div>
<main class="col-12 col-md-9 col-xl-8 py-md-3 pl-md-5 docs-content" role="main">
<article class="article">
<div class="docs-article-container">
</div>
<div class="docs-article-container">
<h1>Comprehensive Installation</h1>
<div class="article-style">
<h2 id="3-a-comprehensive-approach-the-gds-docker-container-slightly-more-advanced-and-complicated-installation">3) A comprehensive approach: the GDS Docker container (slightly more advanced and complicated installation)</h2>
<p>If meet the following requirements, <a href="https://www.docker.com/" rel="noopener" target="_blank">Docker</a> is a stable alternative and works out of the box:</p>
<ol>
<li>You have admin rights over your machine</li>
<li>You are running either Windows 10 Pro, macOS, or Linux distributions that are supported by Docker.</li>
</ol>
<p>It provides a stable platform to run complex software setups like that required in this context. Docker is a containerisation technology that allows to run pre-packaged (containerised) software under controlled environments. Relying on Docker, the <a href="https://github.com/darribas/gds_env" rel="noopener" target="_blank"><code>gds_env</code></a> project provides a containerised platform for Geographic/Urban Data Science.</p>
<p>This resource provides step-by-step descriptions on how to install and run Python from your own computer for all operating systems. See instructions below.</p>
<h2 id="mark-macos-installation-mark"><mark> <strong>MacOS Installation</strong> </mark></h2>
<div class="alert alert-note">
<div>
    If you want to install miniconda (recommended approach, go <a href="/courses/epa1316/software/">here</a>.)
  </div>
</div>
<h2 id="1-installation">1. Installation</h2>
<h3 id="requirements">Requirements</h3>
<p>To be able to complete this guide, your machine will need to meet the following requirements:</p>
<ol>
<li>A stable internet connection</li>
<li>~10GB of space on your hard drive</li>
<li>MacOS version 10.13 or newer i.e. High Sierra, Mojave or Catalina. If you are unsure what version you are running click on the Apple icon in the top left of the screen and then <strong>About this Mac</strong>.</li>
<li>Mac hardware must be a 2010 model or newer</li>
</ol>
<h3 id="docker-install-steps">Docker install steps</h3>
<ol>
<li>
<p>Go to the <a href="https://hub.docker.com/editions/community/docker-ce-desktop-mac/" rel="noopener" target="_blank">dockerhub website</a>.</p>
</li>
<li>
<p>Select the version according to your Apple chip.

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  <figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure1.png"/></div>
</div></figure></p>
</li>
<li>
<p>After you have installed the program and started it, the whale icon will appear in your taskbar as follows:

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  <figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure4.png"/></div>
</div></figure></p>
</li>
</ol>
<br/>
<p>You have successfully downloaded Docker!</p>
<h3 id="using-docker">Using Docker</h3>
<p>Now we have Docker installed we can use it to access Python and all the associated packages we need for the labs of this course.</p>
<div class="alert alert-note">
<div>
    Note: With this installation process, you will not be able to install other packages if you wish to experiment. However, this will be enough for the course.
  </div>
</div>
<h3 id="installing-the-gds-environment">Installing the GDS environment</h3>
<ol>
<li>Access your terminal: <strong>Launchpad</strong> &gt; <strong>Other</strong> &gt; <strong>Terminal</strong></li>
<li>In a fresh line in the terminal type the following to install the GDS environment container:</li>
</ol>
<pre><code class="language-shell">docker pull darribas/gds:6.1
</code></pre>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure5.png"/></div>
</div></figure>
<br/>
<ol start="3">
<li>This should now prompt a long download process that looks a bit like this:</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure6.png"/></div>
</div></figure>
<p>Dont be alarmed if it seems to take a very long time.</p>
<div class="alert alert-note">
<div>
<b>IMPORTANT</b>: <br/>
Make sure you are connected to the internet and it is a stable connection. This step involves the download of large amounts of data (~ 10GB) so it might take a while. However, it only needs to run once.
  </div>
</div>
<h3 id="check-success">Check success</h3>
<p>You will know the process has completed successfully when each line says ‘Pull complete’ and the new line shows your machine name.</p>
<p>If everything has gone according to plan, you should see <code>darribas/gds:6.1</code> show up on your terminal when you type <code>docker image ls</code> (note in the image below there are other containers that are not required, do not worry if you don’t have those or slightly different values on the ID and the “CREATED” columns, the important bit is having <code>darribas/gds:6.1</code> listed):</p>
<p><strong>NOTE</strong>: please ignore the version showing in the screenshot, follow that in
the command below</p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure8.png"/></div>
</div></figure>
<h2 id="2-running-python">2. Running Python</h2>
<p>The following sections cover how to start a python session using the docker container image you just installed, use it, and shut it down when you are done.</p>
<h3 id="running-the-container">Running the container</h3>
<ol>
<li>In the new terminal line type the following command to run the container: <code>docker run --rm -ti -p 8888:8888 -v ${PWD}:/home/jovyan/work darribas/gds:6.1</code></li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure7.png"/></div>
</div></figure>
<br/>
<p>You have now started a Python session.</p>
<div class="alert alert-note">
<div>
<b>IMPORTANT</b>: <br/>
Please do NOT close the terminal window until you are finished in this Python session.
  </div>
</div>
<ol start="2">
<li>To access this session go to your chosen web browser (e.g. Safari/Chrome) and type: <code>localhost:8888</code> into the search bar</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure10_new.png"/></div>
</div></figure>
<ol start="3">
<li>The page that loads will prompt you for a password or a token. This can be found in the text in the terminal following the last command you ran (step 9). A long series of numbers and letters will be preceded by <code>?token=</code>. Copy this long series of characters and paste into the password box in your browser.</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure9.png"/></div>
</div></figure>
<br/>
<ol start="4">
<li>Now that you are in Jupyter Lab you can open up a Python 3 notebook</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure11.png"/></div>
</div></figure>
<br/>
<h3 id="using-jupyter-notebook">Using Jupyter Notebook</h3>
<ul>
<li>This notebook is where you will run your code. Each shaded box is called a kernel. To test this out you can type <code>print('test')</code> into one of these kernels. To run the code use the shortcut <code>Ctrl + Enter</code>.</li>
</ul>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure12.png"/></div>
</div></figure>
<br/>
<div class="alert alert-note">
<div>
<p><b>IMPORTANT</b>: <br/>
Make sure you save files you want to keep <strong>ONLY</strong> <em>within</em> the <code>work</code> folder, as this will ensure they are saved on your machine.</p>
<p>Everything saved outside the <code>work</code> folder will be <em>destroyed</em> as soon as you shut down the session.</p>
</div>
</div>
<ul>
<li>You can access other files on your machine through the <code>work</code> folder in the File Browser. From here you can navigate to your Documents and designated folder for this module. For example, see below (this will depend on where you have stored the lab notebooks/data/other material for this course)</li>
</ul>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15a_new.png"/></div>
</div></figure>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15b.png"/></div>
</div></figure>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15c.png"/></div>
</div></figure>
<p>Here I am navigating to the folder that I have created for this module in my Documents. You can replace this with the pathway to the folder you create for this module.</p>
<br/>
<ul>
<li>You can save your notebook here using <strong>File</strong> &gt; <strong>Save notebook as</strong>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure13_new.png"/></div>
</div></figure></li>
</ul>
<br/>
<ul>
<li>And you can create new folders to organise your work

<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="resources/figs/chp1/Figure14_new.png"/></div>
</div></figure></li>
</ul>
<br/>
<h3 id="ending-your-session">Ending your session</h3>
<ul>
<li>
<p>Once you have finished in your Jupyter session and have saved all your work, you can end the session from the terminal.</p>
</li>
<li>
<p>Using <code>Ctrl + C</code> will prompt a <code>y/n</code> option. Either type <code>y</code> or <code>Ctrl + C</code> again to end the session.</p>
</li>
<li>
<p>You can now safely shut the terminal window.</p>
</li>
</ul>
<br/>
<p>Next time you go to run a Jupyter Notebook you will not need to repeat the whole process as you have already installed Docker and the GDS environment. Instead you can start from <a href="#running-the-container">Running the container</a> and carry on from there.</p>
<br/>
<hr/>
<br/>
<h2 id="mark-linux-installation-mark"><mark> <strong>Linux Installation</strong> </mark></h2>
<div class="alert alert-note">
<div>
    If you want to install miniconda (recommended approach, go <a href="/courses/epa1316/software/">here</a>.)
  </div>
</div>
<h2 id="1-installation-1">1. Installation</h2>
<h3 id="requirements-1">Requirements</h3>
<p>To be able to complete this guide, your machine will need to meet the following requirements:</p>
<ol>
<li>A stable internet connection</li>
<li>~10GB of space on your hard drive</li>
<li>A Linux distribution supported by Docker. You can check available distributions for ready installation on <a href="https://hub.docker.com/search?q=&amp;type=edition&amp;offering=community&amp;operating_system=linux" rel="noopener" target="_blank">this page</a>.</li>
</ol>
<p><strong>NOTE</strong> If you are running a different distribution (e.g. Arch Linux), there is a good chance Docker <em>will</em> work, but you will have to source your own instructions for installation. Once you have Docker up and running on your machine, you can move to <a href="#installing-the-gds-container">Installing the GDS container</a>.</p>
<h3 id="docker-install-steps-1">Docker install steps</h3>
<ol>
<li>Select the page for your distribution from the <a href="https://hub.docker.com/search?q=&amp;type=edition&amp;offering=community&amp;operating_system=linux" rel="noopener" target="_blank">Docker Hub list of supported distributions</a></li>
</ol>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp2/docker_distros.png"/></div>
</div></figure>
<br/></p>
<p>For this example, we will use Ubuntu.</p>
<ol start="2">
<li>Make sure that you meet the requirements to install Docker:</li>
</ol>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp2/ubuntu.png"/></div>
</div></figure>
<br/></p>
<ol start="3">
<li>Follow the steps specified on the official install guide:</li>
</ol>
<blockquote>
<p><a href="https://docs.docker.com/engine/install/ubuntu/" rel="noopener" target="_blank">https://docs.docker.com/engine/install/ubuntu/</a></p>
</blockquote>
<p>Once you complete these steps successfully, you will have Docker ready to go on your computer!</p>
<h3 id="installing-the-gds-container">Installing the GDS container</h3>
<p>Once you have Docker installed and running on your machine, installing everything you need to run Python and associated libraries boils down to the following two steps:</p>
<ol>
<li>Open your terminal app of choice (for example, Gnome Terminal)</li>
<li>Run the following command:</li>
</ol>
<p><strong>NOTE</strong>: please ignore the version showing in the screenshot, follow that in
the command below</p>
<pre><code class="language-shell">docker pull darribas/gds:6.1
</code></pre>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp2/terminal_pull.png"/></div>
</div></figure>
<br/></p>
<p>You will know this has completed when each line says ‘Pull complete’.</p>
<div class="alert alert-note">
<div>
<b>IMPORTANT</b>: <br/>
Make sure you are connected to the internet and it is a stable connection. This step involves the download of large amounts of data (ca. 10GB) so it might take a while. However, it only needs to be run once.
  </div>
</div>
<h3 id="check-success-1">Check success</h3>
<p>If everything has gone according to plan, you should see <code>darribas/gds:6.1</code> show up on your terminal when you type <code>docker image ls</code> (note in the image below there are other containers that are not required, do not worry if you don’t have those or slightly different values on the ID and the “CREATED” columns, the important bit is having <code>darribas/gds:6.1</code> listed):</p>
<p><strong>NOTE</strong>: please ignore the version showing in the screenshot, follow that in
the command below</p>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp2/docker_image_ls.png"/></div>
</div></figure>
<br/></p>
<h2 id="2-running-python-1">2. Running Python</h2>
<p>The following sections cover how to start a python session using the docker container image you just installed, use it, and shut it down when you are done.</p>
<h3 id="running-the-container-1">Running the container</h3>
<p>To start up Python through Docker, follow these steps:</p>
<ol>
<li>In a new terminal line, type the following command to run the container and hit enter:</li>
</ol>
<p><strong>NOTE</strong>: please ignore the version showing in the screenshot, follow that in
the command below</p>
<pre><code class="language-shell">docker run --rm -ti -p 8888:8888 -v ${PWD}:/home/jovyan/work darribas/gds:6.1
</code></pre>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp2/docker_run.png"/></div>
</div></figure>
<br/>
<p>You have now started a Python session.</p>
<div class="alert alert-note">
<div>
<p><b>IMPORTANT</b>: <br/></p>
<p>Please do NOT close the terminal window until you are finished in this Python session</p>
</div>
</div>
<ol start="2">
<li>To access this session go to your chosen web browser (e.g. Firefox/Chrome) and type: <code>localhost:8888</code> into the search bar</li>
</ol>
<br/>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure10.png"/></div>
</div></figure>
<ol start="3">
<li>The page that loads will prompt you for a password or a token. This can be found in the text in the terminal following the last command you ran. A long series of numbers and letters will be preceded by <code>?token=</code>. Copy this long series of characters and paste into the password box in your browser.</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp2/docker_token.png"/></div>
</div></figure>
<ol start="4">
<li>Now that you are in Jupyter Lab you can open up a Python 3 notebook</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure11.png"/></div>
</div></figure>
<br/>
<h3 id="using-jupyter-notebook-1">Using Jupyter Notebook</h3>
<ul>
<li>This notebook is where you will run your code. Each shaded box is called a kernel. To test this out you can type <code>print('test')</code> into one of these kernels. To run the code use the shortcut <code>Ctrl + Enter</code>.</li>
</ul>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure12.png"/></div>
</div></figure>
<br/>
<div class="alert alert-note">
<div>
<p><b>IMPORTANT</b>: <br/></p>
<p>Make sure you save files you want to keep <strong>ONLY</strong> <em>within</em> the <code>work</code> folder, as this will ensure they are saved on your machine.</p>
<p>Everything saved outside the <code>work</code> folder will be <em>destroyed</em> as soon as you shut down the session.</p>
</div>
</div>
<ul>
<li>You can save your notebook using <strong>File</strong> &gt; <strong>Save notebook as</strong>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure13.png"/></div>
</div></figure></li>
</ul>
<br/>
<ul>
<li>You can create new folders to organise your work

<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure14.png"/></div>
</div></figure></li>
</ul>
<br/>
<ul>
<li>And you can access other files on your machine through the ‘work’ folder in the File Browser. From here you can navigate to your Documents and designated folder for this module</li>
</ul>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15a.png"/></div>
</div></figure>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15b.png"/></div>
</div></figure>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15c.png"/></div>
</div></figure>
<br/></p>
<h3 id="ending-your-session-1">Ending your session</h3>
<ul>
<li>
<p>Once you have finished in your Jupyter session and have saved all your work, you can end the session from the terminal.</p>
</li>
<li>
<p>Using <code>Ctrl + C</code> will prompt a <code>y/n</code> option. Either type <code>y</code> or <code>Ctrl + C</code> again to end the session.</p>
</li>
<li>
<p>You can now safely shut the terminal window.</p>
</li>
</ul>
<br/>
<p>Next time you go to run a Jupyter Notebook you will not need to repeat the whole process as you have already installed Docker and the GDS environment. Instead you can start from <a href="#running-the-container">Running Python through Docker</a> and carry on from there.</p>
<br>
<hr/>
<br>
<h2 id="mark-windows-mark"><mark> <strong>Windows</strong> </mark></h2>
<div class="alert alert-note">
<div>
    If you want to install miniconda (recommended approach, go <a href="/courses/epa1316/software/">here</a>.)
  </div>
</div>
<h2 id="1-installation-2">1. Installation</h2>
<h3 id="requirements-2">Requirements</h3>
<p>To be able to complete this guide, your machine will need to meet the following requirements:</p>
<ol>
<li>A stable internet connection</li>
<li>~10GB of space on your hard drive</li>
<li>Microsoft Windows 10 Professional, Education, Enterprise 64-bit, or Windows 10 Home 64-bit with WSL 2. You can see the full requirements on the official <a href="https://docs.docker.com/docker-for-windows/install/" rel="noopener" target="_blank">Docker for Windows page</a>.</li>
</ol>
<h3 id="docker-install-steps-2">Docker install steps</h3>
<p>Once you have everything required ready to go, the first step is to install the Docker Desktop App for Windows. Here are the steps you can follow:</p>
<ol>
<li>Head over to <a href="https://hub.docker.com/editions/community/docker-ce-desktop-windows/" rel="noopener" target="_blank">Docker Hub</a> to download a copy of Docker for Windows:</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/docker_hub.png"/></div>
</div></figure>
<ol start="2">
<li>Follow the instructions on the installation wizard to authorize the installer and proceed with the install.</li>
</ol>
<p>You can check if the process has completed successfully by following these steps:</p>
<ol>
<li>Open PowelShell from the “Start Menu”</li>
</ol>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/powershell.png"/></div>
</div></figure>
<br/></p>
<ol start="2">
<li>Check Docker is available by printing out the version you have installed:</li>
</ol>
<pre><code class="language-shell">docker --version
</code></pre>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/docker_version.png"/></div>
</div></figure>
<br/></p>
<p>Note that you might have installed a slightly different version and that is totally okay. What you want to make sure is that it successfully prints out a version instead of a warning/error message (usually in red).</p>
<h3 id="installing-the-gds-container-1">Installing the GDS container</h3>
<p>Once you have Docker installed and running on your machine, installing everything you need to run Python and associated libraries boils down to the following two steps:</p>
<ol>
<li>Open PowerShell following the same steps as above (you can use the same window as before or a fresh new one).</li>
<li>Run (type and hit “Enter”) the following command:</li>
</ol>
<p><strong>NOTE</strong>: please ignore the version showing in the screenshot, follow that in
the command below</p>
<pre><code class="language-shell">docker pull darribas/gds:6.1
</code></pre>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/pull_gds.png"/></div>
</div></figure>
<br/></p>
<p>You will know this has completed when each line says ‘Pull complete’.</p>
<div class="alert alert-note">
<div>
<p><b>IMPORTANT</b>: <br/></p>
<p>Make sure you are connected to the internet and it is a stable connection. This step involves the download of large amounts of data (ca. 10GB) so it might take a while. However, it only needs to run once.</p>
</div>
</div>
<h3 id="check-success-2">Check success</h3>
<p>If everything has gone according to plan, you should see <code>darribas/gds:6.1</code> show up on your terminal when you type <code>docker image ls</code> (note in the image below there are other containers that are not required, do not worry if you don’t have those or slightly different values on the ID and the “CREATED” columns, the important bit is having <code>darribas/gds:6.1</code> listed):</p>
<p><strong>NOTE</strong>: please ignore the version showing in the screenshot, follow that in
the command below</p>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/docker_success.png"/></div>
</div></figure>
<br/></p>
<h2 id="2-running-python-2">2. Running Python</h2>
<p>The following sections cover how to start a python session using the docker container image you just installed, use it, and shut it down when you are done.</p>
<h3 id="running-the-container-2">Running the container</h3>
<p>To start up Python through Docker, follow these steps:</p>
<ol>
<li>In a new PowerShell window, type the following command to run the container and hit enter:</li>
</ol>
<p><strong>NOTE</strong>: please ignore the version showing in the screenshot, follow that in
the command below</p>
<pre><code class="language-shell">docker run --rm -ti -p 8888:8888 -v ${PWD}:/home/jovyan/work darribas/gds:6.1
</code></pre>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/docker_run.png"/></div>
</div></figure>
<p>You have now started a Python session.</p>
<div class="alert alert-note">
<div>
<p><b>IMPORTANT</b>: <br/></p>
<p>Please do NOT close the PowerShell window until you are finished in this Python session</p>
</div>
</div>
<ol start="2">
<li>To access this session go to your chosen web browser (e.g. Firefox/Chrome) and type: <code>localhost:8888</code> into the search bar. You should see something similar to:</li>
</ol>
<br/>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/jupyter_token.png"/></div>
</div></figure>
<ol start="3">
<li>The page that loads will prompt you for a password or a token. This can be found in the text in the terminal following the last command you ran. This will be a long series of numbers and letters will be preceded by <code>?token=</code>. Copy this long series of characters and paste into the password box in your browser.</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/docker_token.png"/></div>
</div></figure>
<ol start="4">
<li>Now you are in Jupyter Lab, it should look like this, more or less:</li>
</ol>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp3/lab.png"/></div>
</div></figure>
<br/>
<h3 id="using-jupyter-notebook-2">Using Jupyter Notebook</h3>
<ul>
<li>This notebook is where you will run your code. Each shaded box is called a kernel. To test this out you can type <code>print('test')</code> into one of these kernels. To run the code use the shortcut <code>Ctrl + Enter</code>.</li>
</ul>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure12.png"/></div>
</div></figure>
<br/>
<div class="alert alert-note">
<div>
<p><b>IMPORTANT</b>: <br/></p>
<p>Make sure you save files you want to keep <strong>ONLY</strong> <em>within</em> the <code>work</code> folder, as this will ensure they are saved on your machine.</p>
<p>Everything saved outside the <code>work</code> folder will be <em>destroyed</em> as soon as you shut down the session.</p>
</div>
</div>
<ul>
<li>You can save your notebook using <strong>File</strong> &gt; <strong>Save notebook as</strong>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure13.png"/></div>
</div></figure></li>
</ul>
<br/>
<ul>
<li>You can create new folders to organise your work

<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure14.png"/></div>
</div></figure></li>
</ul>
<br/>
<ul>
<li>And you can access other files on your machine through the ‘work’ folder in the File Browser. From here you can navigate to your Documents and designated folder for this module</li>
</ul>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15a.png"/></div>
</div></figure>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15b.png"/></div>
</div></figure>
<p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/chp1/Figure15c.png"/></div>
</div></figure>
<br/></p>
<h3 id="ending-your-session-2">Ending your session</h3>
<ul>
<li>
<p>Once you have finished in your Jupyter session and have saved all your work, you can end the session from the terminal.</p>
</li>
<li>
<p>Using <code>Ctrl + C</code> will prompt a <code>y/n</code> option. Either type <code>y</code> or <code>Ctrl + C</code> again to end the session.</p>
</li>
<li>
<p>You can now safely shut the terminal window.</p>
</li>
</ul>
<br/>
<p>Next time you go to run a Jupyter Notebook you will not need to repeat the whole process as you have already installed Docker and the GDS environment. Instead you can start from <a href="#winpro_run">Running Python through Docker</a> and carry on from there.</p>
<br/>
<p>This resource is adapted from Arribas-Bel, Dani. 2019. gds_env: A Containerised Platform for Geographic Data Science (version 6.1). <a href="https://darribas.org/gds_env" rel="noopener" target="_blank">https://darribas.org/gds_env</a>.</p>
</br></br></div>
<div class="article-widget">
<div class="post-nav">
<div class="post-nav-item">
<div class="meta-nav">Previous</div>
<a href="/courses/epa1316/software/2-minimalist/" rel="next">Minimalist Installation</a>
</div>
<div class="post-nav-item">
<div class="meta-nav">Next</div>
<a href="/courses/epa1316/software/environment/" rel="prev">Virtual Environments</a>
</div>
</div>
</div>
</div>
<div class="body-footer">
<p>Last updated on May 5, 2019</p>
</div>
</article>
<footer class="site-footer">
<p class="powered-by">
<a href="/license/">LICENSE: CC-BY-SA <br/> <i class="fab fa-creative-commons fa-2x"></i><i class="fab fa-creative-commons-by fa-2x"></i><i class="fab fa-creative-commons-sa fa-2x"></i> </a><br/>
</p>
<p class="powered-by">
    © 2023 CUSP · 

    Made with <i class="far fa-heart" style="color:#4DA7E2"></i>,
    help from <a href="https://github.com/rbind/apreshill" rel="noopener" target="_blank"><i class="fas fa-code-branch"></i></a>,
    and the
    <a href="https://wowchemy.com/" rel="noopener" target="_blank">Wowchemy theme</a> for
    <a href="https://gohugo.io" rel="noopener" target="_blank">Hugo</a>.
    <a href="/credits" rel="noopener" target="_blank">Credits</a>.

    
    <span aria-hidden="true" class="float-right">
<a href="#" id="back_to_top">
<span class="button_icon">
<i class="fas fa-chevron-up fa-2x"></i>
</span>
</a>
</span>
</p>
</footer>
</main>
</div>
</div>
</div>
<div class="page-footer">
</div>
<script src="/js/vendor-bundle.min.46271ef31da3f018e9cd1b59300aa265.js"></script>
<script crossorigin="anonymous" integrity="" src="https://cdn.jsdelivr.net/npm/leaflet@1.7.1/dist/leaflet.min.js"></script>
<script crossorigin="anonymous" integrity="sha512-I7w3ZdSFzw5j3jU3ZkNikBNeIrl3i+hEuEdwNmqUJvwNcaBUNcijnP2gd9DtGlgVYDplfjGoD8vTNsID+lCjqg==" src="https://cdn.jsdelivr.net/gh/bryanbraun/anchorjs@4.2.2/anchor.min.js"></script>
<script>
  anchors.add();
</script>
<script id="search-hit-fuse-template" type="text/x-template">
    <div class="search-hit" id="summary-{{key}}">
      <div class="search-hit-content">
        <div class="search-hit-name">
          <a href="{{relpermalink}}">{{title}}</a>
          <div class="article-metadata search-hit-type">{{type}}</div>
          <p class="search-hit-description">{{snippet}}</p>
        </div>
      </div>
    </div>
  </script>
<script crossorigin="anonymous" integrity="sha512-o38bmzBGX+hD3JHWUFCDA09btWaqrNmoJ3RXLlrysA7PP01Kgs4UlE4MhelE1v5dJR3+cxlR4qQlotsW7jKsnw==" src="https://cdn.jsdelivr.net/gh/krisk/Fuse@v3.2.1/dist/fuse.min.js"></script>
<script crossorigin="anonymous" integrity="sha512-mhbv5DqBMgrWL+32MmsDOt/OAvqr/cHimk6B8y/bx/xS88MVkYGPiVv2ixKVrkywF2qHplNRUvFsAHUdxZ3Krg==" src="https://cdn.jsdelivr.net/gh/julmot/mark.js@8.11.1/dist/jquery.mark.min.js"></script>
<script id="page-data" type="application/json">{"use_headroom":false}</script>
<script src="/en/js/wowchemy.min.a6238d5886fa4a2f7cf92df25709326f.js"></script>
<script src="/js/wowchemy-map.a26e9d2f7238ba5b868384f1c5bc6477.js" type="module"></script>
</body>
</html>