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
<meta content="Overview The final project is your opportunity to explore a topic in depth. These projects must run through the entire data science process (and do not forget that it is a chaotic process)." name="description"/>
<link href="https://cusp.tbm.tudelft.nl/courses/epa1316/assessment/final-project/" hreflang="en-us" rel="alternate">
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
<link href="https://cusp.tbm.tudelft.nl/courses/epa1316/assessment/final-project/" rel="canonical">
<meta content="summary_large_image" property="twitter:card"/>
<meta content="@TrivikV" property="twitter:site"/>
<meta content="@TrivikV" property="twitter:creator"/>
<meta content="CUSP - Centre for Urban Science &amp; Policy at TU Delft" property="og:site_name"/>
<meta content="https://cusp.tbm.tudelft.nl/courses/epa1316/assessment/final-project/" property="og:url"/>
<meta content="Final Project | CUSP - Centre for Urban Science &amp; Policy at TU Delft" property="og:title"/>
<meta content="Overview The final project is your opportunity to explore a topic in depth. These projects must run through the entire data science process (and do not forget that it is a chaotic process)." property="og:description"/><meta content="https://cusp.tbm.tudelft.nl/media/sharing.jpeg" property="og:image"/>
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
<title>Final Project | CUSP - Centre for Urban Science &amp; Policy at TU Delft</title>
</link></link></link></link></link></link></head>
<body class="page-wrapper" data-offset="70" data-spy="scroll" data-target="#TableOfContents" data-wc-page-id="2f9249c2fb4546e5443f6c2768dd9b36" id="top">
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
        
        
          Assessment
        
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
<li class="active"><a href="/courses/epa1316/assessment/final-project/">Final Project</a></li>
<li class=""><a href="/courses/epa1316/assessment/project-template/">Project Template</a></li>
</ul>
</div>
<div class="docs-toc-item">
<a class="docs-toc-link" href="/courses/epa1316/software/"><i class="fab fa-python pr-1"></i>Software</a>
<ul class="nav docs-sidenav">
<li class=""><a href="/courses/epa1316/software/1-standard/">1. Standard Installation</a></li>
<li class=""><a href="/courses/epa1316/software/2-minimalist/">2. Minimalist Installation</a></li>
<li class=""><a href="/courses/epa1316/software/3-comprehensive/">3. Comprehensive Installation</a></li>
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
<li><a href="#overview">Overview</a></li>
<li><a href="#final-projects">Final Projects</a></li>
<li><a href="#milestones-to-keep-track-of-your-work">Milestones (to keep track of your work)</a>
<ul>
<li></li>
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
<h1>Final Project</h1>
<div class="article-style">
<br/>
<h2 id="overview">Overview</h2>
<p>The final project is your opportunity to explore a topic in depth. These projects must run through the entire data science process (and do not forget that it is a chaotic process). Therefore, students must work together in teams, as projects often work in life outside of university.</p>
<div class="alert alert-note">
<div>
    The deadline is in week 10 of the course according to the <a href="/courses/epa1316/introduction/schedule/">schedule</a>. The exact date and time will be announced on Brightspace in consulation with other teachers so as not to burden students with submissions on the same day.
  </div>
</div>
<h2 id="final-projects">Final Projects</h2>
<p>Choose one of the three projects mentioned below,</p>
<ul>
<li><a href="../../project/project-01.pdf">A</a> : Mobility, Built Environment &amp; Sustainability</li>
<li><a href="../../project/project-02.pdf">B</a> : Identifying the Health Vulnerability in a City</li>
<li><a href="../../project/project-03.pdf">C</a> : Modelling COVID-19 in India</li>
</ul>
<p>Some examples of good assignments from last year are listed below - [Final projects will be subjected to a plagiraism check, so please do not copy the hypothesis and analysis of students from last year].</p>
<ul>
<li><a href="../../project/AmbulanceCalls_D.pdf">A</a> : Ambulance Calls</li>
<li><a href="../../project/COVID_D.pdf">B</a> : COVID</li>
<li><a href="../../project/CycleNetwork_D.pdf">C</a> : Cycle Network</li>
<li><a href="../../project/Traffic_D.pdf">D</a> : Traffic</li>
</ul>
<h2 id="milestones-to-keep-track-of-your-work">Milestones (to keep track of your work)</h2>
<h4 id="1-group-creation-and-project-selection">1. Group Creation and Project Selection</h4>
<p>Form groups of&nbsp;4 students&nbsp;each. Each student needs to be part of a group. If you are going to drop the course, don’t sign up for the final project as that may delay the progress of other students.&nbsp;</p>
<p><strong>Some suggestions for creating effective groups,</strong></p>
<ul>
<li>Be inclusive of people who are not in The Netherlands (ex. Studying from their home country due to COVID restrictions).</li>
<li>Strive for diverse groups. (Machine Learning and AI suffer heavily from bias of individuals and communities. Diversity is crucial in meaningful and effective work.)&nbsp;</li>
<li>The most appealing option is to form a group with friends. However, I urge you to spend the first 5 weeks getting to know your peers (I will facilitate that in class) and then form groups where working with each other seems natural.</li>
<li>A&nbsp;group of 3 or 5 students will only be accepted as last resort. Please email me with a good motivation in case you want to form such a group.</li>
<li>Please email me if you haven’t found a group. I will make sure you do.&nbsp;</li>
<li>Keep in constant contact with your group.</li>
</ul>
<p><strong>If you have questions,</strong></p>
<p>We will be meeting with our respective TAs to discuss the final project, questions, problems, and concerns. We will meet between 1100-1300 on Wednesdays during Weeks 8, 9 and 10. Please make sure you organise this meeting with your TAs.&nbsp;</p>
<p>My suggestion is to spend week 7 on data collection and cleaning, problem scoping and getting to know each other, week 8 on EDA, and developing your models, and week 9 and 10 on visualisations, interpretations, and report.&nbsp;</p>
<p>If there are any questions about the final projects, please reach out to your TAs directly.&nbsp;</p>
<h4 id="2-scope-of-work-and-preliminary-eda">2. Scope of Work and Preliminary EDA</h4>
<p>Address the two most important things first:</p>
<ul>
<li>Project statement. The project goal in the posted project description is not fully formulated or tuned. Based on the project description and references, state a well-defined question that you’ll address in the project.</li>
<li>Preliminary EDA. Explain your plans for preliminary data exploration. Please take care when planning, so that team members can work individually on these tasks if need be. Stay in touch with your team and communicate regularly.</li>
</ul>
<h4 id="3-eda-and-revised-project-statement">3. EDA and Revised Project Statement</h4>
<p>Formulate the following for yourself:</p>
<ul>
<li>A description of the data: what type of data are you dealing with? What methods have
you used to explore the data (initial explorations, data cleaning and reconciliation, etc)?</li>
<li>Visualizations and captions that summarize the noteworthy findings of the EDA.</li>
<li>A revised project question based on the insights you gained through EDA.</li>
<li>A description of a baseline model that you are going to or in the process of building.</li>
</ul>
<h4 id="4-project-report">4. Project Report</h4>
<p>Submit your final project on Brightspace as a <strong>pdf</strong> (only one submission per group).</p>
<ul>
<li>Use the <a href="https://cusp.tbm.tudelft.nl/courses/epa1316/assessment/project-template/">project template</a> to write the final report.</li>
<li>You will be assessed using a <a href="../../resources/project-rubric.pdf">project rubric</a>.</li>
<li>You are required to also submit a peer evaluation of each team member on Buddycheck through Brightspace which may or may not affect your grade depending on the reports.</li>
</ul>
</div>
<div class="article-widget">
<div class="post-nav">
<div class="post-nav-item">
<div class="meta-nav">Previous</div>
<a href="/courses/epa1316/assessment/assignment/" rel="next">Assignments</a>
</div>
<div class="post-nav-item">
<div class="meta-nav">Next</div>
<a href="/courses/epa1316/assessment/project-template/" rel="prev">Project Template</a>
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