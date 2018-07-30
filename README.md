<!DOCTYPE html>
<html>
<head>
    <script src="js/jquery.min.js" type="text/javascript"></script>

    <link rel="stylesheet" href="main.css">
<title>Welcome to my personal website !</title>
</head>
<body>

<div>
    <img src="kilian.png" alt = "photo" height="200" width="200" style="float: left; margin: 0px 15px 15px 0px;">
    <h1>Kilian Fatras</h1>
    <h2>Master student</h2>
    <h2>ENSTA ParisTech/ Ecole Polytechnique</h2>
<br style="clear:both" />
</div>


<ul>
<li><a href="#About"> About </a></li>
<li><a href="#Research_interests"> Research interests </a></li>
<li><a href="#Papers"> Papers </a></li>
<li><a href="#Coworkers"> Coworkers </a></li>
<li><a href="#Workshop"> Workshop </a></li>
<li><a href="#Networks"> Networks </a></li>
<li><a href="#Contacts"> Contacts </a></li>
</ul>

<div id="About" onclick="window.location.hash='About'; ">

<h1> <center>About</center> </h1>
<p>I am currently a graduate student interning at University of British Columbia under the supervision of Mark Schmidt.
I am pursuing a double degree between ENSTA ParisTech and Ecole Polytechnique in applied mathematics and machine learning.
During this double degree, I was a UC Berkeley student for the fall semester 2018.
Next November, I will start a PhD in optimal transport and machine learning under the supervsion of Pr. Nicolas Courty and Professor Rémi Flamary at INRIA Rennes.
</p>
</div>


<div id="Research_interests" onclick="window.location.hash='Research_interests'; ">
<h1> <center>Research interests</center> </h1>

<p>
My work focuses on <b>optimization for machine learning</b> and the interaction between <b>optimal transport and machine learning</b>.
</p>
</div>

<div id="Papers" onclick="window.location.hash='Papers'; ">
<h1> <center>Papers</center> </h1>
<p><a href="https://arxiv.org/abs/1806.07294">[Variance Reduced Three Operator Splitting]</a></p>
<p>Abstract : Despite the rise to fame of incremental variance-reduced methods in recent years, their use in nonsmooth optimization is still limited to few simple cases. This is due to the fact that existing methods require to evaluate the proximity operator for the nonsmooth terms, which can be a costly operation for complex penalties. In this work we introduce two variance-reduced incremental methods based on SAGA and SVRG that can efficiently take into account complex penalties which can be expressed as a sum of proximal terms. This includes penalties such as total variation, group lasso with overlap and trend filtering, to name a few. Furthermore, we also develop sparse variants of the proposed algorithms which can take advantage of sparsity in the input data. Like other incremental methods, it only requires to evaluate the gradient of a single sample per iteration, and so is ideally suited for large scale applications. We provide a convergence rate analysis for the proposed methods and show that they converge with a fixed step-size, achieving in some cases the same asymptotic rate as their full gradient variants. Empirical benchmarks on 3 different datasets illustrate the practical advantages of the proposed methods.</p>
</div>


<div id="Workshop" onclick="window.location.hash='Workshop'; ">
<h1> <center>Workshop</center> </h1>
<p>This section is empty for the moment !</p>
</div>

<div id="Coworkers" onclick="window.location.hash='Coworkers'; ">
<h1><center>Coworkers</center> </h1>
    <p>My PhD directors :
<a href="http://people.irisa.fr/Nicolas.Courty/">Nicolas Courty</a>
<a href="https://remi.flamary.com/">Rémi Flamary</a> </p>
<p>
    Friend and former supervisor :
<a href="http://fa.bianp.net/">Fabian Pedregosa</a>
</p>
</div>

<div id="Networks" onclick="window.location.hash='Networks'; ">
<h1> <center>Networks</center> </h1>
<p>I use several networks, do not hesitate to reach me out !
    <a href="https://www.linkedin.com/in/kilianfatras">LinkedIn</a>, <a href="https://github.com/kilianFatras"> GitHub</a>, <a href="https://twitter.com/FatrasKilian">Twitter</a></p>
</div>

<div id="Contacts" onclick="window.location.hash='Contacts'; ">
<h1> <center>Contacts</center> </h1>
<p>kilian(dot)fatras[at]gmail(dot)com</p>
</div>

</body>
</html>
