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
<meta content="Data Science sometimes requires the ability to be able to handle the overlapping of package dependencies in python which can disturb your working environment. Sometimes you might be experimenting with an earlier version of a package (or library) which requires earlier versions of other packages which can cause conflict as legacy code may raise errors or warnigns accordingly due to conflict." name="description"/>
<link href="https://cusp.tbm.tudelft.nl/courses/epa1316/software/environment/" hreflang="en-us" rel="alternate">
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
<link href="https://cusp.tbm.tudelft.nl/courses/epa1316/software/environment/" rel="canonical">
<meta content="summary_large_image" property="twitter:card"/>
<meta content="@TrivikV" property="twitter:site"/>
<meta content="@TrivikV" property="twitter:creator"/>
<meta content="CUSP - Centre for Urban Science &amp; Policy at TU Delft" property="og:site_name"/>
<meta content="https://cusp.tbm.tudelft.nl/courses/epa1316/software/environment/" property="og:url"/>
<meta content="Virtual Environments | CUSP - Centre for Urban Science &amp; Policy at TU Delft" property="og:title"/>
<meta content="Data Science sometimes requires the ability to be able to handle the overlapping of package dependencies in python which can disturb your working environment. Sometimes you might be experimenting with an earlier version of a package (or library) which requires earlier versions of other packages which can cause conflict as legacy code may raise errors or warnigns accordingly due to conflict." property="og:description"/><meta content="https://cusp.tbm.tudelft.nl/media/sharing.jpeg" property="og:image"/>
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
<title>Virtual Environments | CUSP - Centre for Urban Science &amp; Policy at TU Delft</title>
</link></link></link></link></link></link></head>
<body class="page-wrapper" data-offset="70" data-spy="scroll" data-target="#TableOfContents" data-wc-page-id="01bff35e4a9436e739861d247139babd" id="top">
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
<li class=""><a href="/courses/epa1316/software/3-comprehensive/">3. Comprehensive Installation</a></li>
<li class="active"><a href="/courses/epa1316/software/environment/">Virtual Environments</a></li>
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
<li><a href="#virtual-environments-with-anaconda">Virtual Environments with Anaconda</a></li>
<li><a href="#adding-the-virtual-environment-in-jupyter-notebooklab">Adding the Virtual Environment in Jupyter Notebook/Lab</a></li>
</ul>
</nav>
</div>
<main class="col-12 col-md-9 col-xl-8 py-md-3 pl-md-5 docs-content" role="main">
<article class="article">
<div class="docs-article-container">
</div>
<div class="docs-article-container">
<h1>Virtual Environments</h1>
<div class="article-style">
<p>Data Science sometimes requires the ability to be able to handle the overlapping of package dependencies in python which can disturb your working environment. Sometimes you might be experimenting with an earlier version of a package (or library) which requires earlier versions of other packages which can cause conflict as legacy code may raise errors or warnigns accordingly due to conflict.</p>
<p>To circumvent these troubling issues that recur and to become good at the craft, let us take a look at using virtual environments. Virtual environments can be characterized as empty places that are isolated from the local source and a place you can install new packages (different versions or whatnot).</p>
<div class="alert alert-block alert-info">
<b>Note:</b> It is recommended that for you create new virtual environments for each project to isolate their functionality and dependencies from each other. This will save you a lot of headache in the future. Senior batches of EPA have always regretted not doing this.
</div>
<h2 id="virtual-environments-with-anaconda">Virtual Environments with Anaconda</h2>
<p>This part of the tutorial assumes that you have installed Anaconda as your primary installation and that you are using jupyter lab / notebook from it. Anaconda really simplifies package management.</p>
<p>To begin we will first create a virtual environment by relying on the conda command. Remember, you apply these steps either on the Anaconda Prompt or the console!</p>
<pre><code class="language-shell">conda create -n myenv python=3.8
</code></pre>
<p>On the code above, myenv is the name of the virtual environment and python- is the version of python you want inside the virtual environment. Now we need to activate the created environment.</p>
<pre><code class="language-shell">conda activate myenv
</code></pre>
<p>With this, you activate the virtual environment and any packets / dependencies that you wish can be installed in this virtual environment. If you wish to get out of the virtual environment just type the code below:</p>
<pre><code class="language-shell">conda deactivate
</code></pre>
<p>You can also check all environments that you have already created in Anaconda by using:</p>
<pre><code class="language-shell">conda env list
</code></pre>
<p>and if you would like to remove any of them, you can run the code:</p>
<pre><code class="language-shell">conda env remove -n myenv
</code></pre>
<p>For adding new packages you use the following code below <strong>after activating your environment</strong>:</p>
<pre><code class="language-shell">conda install -n myenv numpy
</code></pre>
<p><code>numpy</code> is an example here. The syntax is</p>
<pre><code class="language-shell">conda install -n [environment name] [package name]
</code></pre>
<p>Also for a specific package &amp; version you use:</p>
<pre><code class="language-shell">conda install -n myenv numpy==2.18.4
</code></pre>
<p>Great! You are done!</p>
<h2 id="adding-the-virtual-environment-in-jupyter-notebooklab">Adding the Virtual Environment in Jupyter Notebook/Lab</h2>
<p>When you have created your virtual environment and installed Jupyter Lab or Notebook within the environment, at first Jupyter Notebook (being a standalone application) will not recognise the virtual environment. To set up the connection between the two, after activating your virtual environment run this code:</p>
<pre><code class="language-shell">pip install --user ipykernel
</code></pre>
<p>​
This command has added a package called <code>ipykernel</code>. Then we can manually add the virtual environment in the Jupyter Notebook. We can use this code:</p>
<pre><code class="language-shell">python -m ipykernel install --user --name=myenv
</code></pre>
<p>​
Where <code>myenv</code> is the name of the environment we have created. Now all is ready to be used! You can check in the Jupyter Lab interface or when you create a new Jupyter Notebook. You can see it as in below in the launcher now:</p>
<figure>
<div class="d-flex justify-content-center">
<div class="w-100"><img alt="" data-zoomable="" loading="lazy" src="../figs/jupyter_venv.png"/></div>
</div></figure>
<p>Lastly you can remove the virtual environment from Jupyter with:</p>
<pre><code class="language-shell">jupyter kernelspec uninstall myenv
</code></pre>
<p>​</p>
</div>
<div class="article-widget">
<div class="post-nav">
<div class="post-nav-item">
<div class="meta-nav">Previous</div>
<a href="/courses/epa1316/software/3-comprehensive/" rel="next">Comprehensive Installation</a>
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