
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <title>Kilianf Fatras</title>
    <!-- Bootstrap core CSS -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom styles for this template -->
    <link href="main.css" rel="stylesheet">
    <script>
    (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
    (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
    m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
    })(window,document,'script','http://www.google-analytics.com/analytics.js','ga');
    ga('create', 'UA-48368675-1', 'auto');
    ga('send', 'pageview');
    </script>
  </head>
<body>
    <div class="container">
      <div class="row" style="padding:20px">
        <div class="hidden-xs col-sm-2 col-md-2" id="sidebar" role="navigation" style="margin-top:190px">
          <hr>
          <ul class="nav nav-pills nav-stacked">
            <li><a href="#research_interests" class="">Research interests</a></li>
            <li><a href="#papers" class=" active">Papers</a></li>
            <li><a href="#Workshops" class="">Workshops</a></li>
            <li><a href="#Projects" class="">Projects</a></li>
            <li><a href="#contact" class="">Contacts</a></li>
          </ul>
        </div>
        <div class="col-xs-13 col-sm-8 col-md-8">
          <div class="row">
            <div id="photo">
              <script type='text/javascript'>
              var proba_imgs = [ .1,.9]
              var images = [
              //"photos/id_circle2.png",
              //"photos/id_circle4.png",
              "images/kilian.png"
               //"images/wedgemount.jpg"
              ];
              var swapIndexA = Math.floor(Math.random() * images.length);
              var swapIndexB = Math.floor(Math.random() * images.length);
              var temp = images[swapIndexA];
              images[swapIndexA] = images[swapIndexB];
              images[swapIndexB] = temp;
              document.write("<img class=\"img-circle\" src='" + images.shift() + "' class=\"pull-left\" style=\"margin:20px 20px 20px 0; width:145px; height:150px; border-radius:100%\" onmouseover='this.src = this.src.replace(/(\\w+)(\\.\\w{3,4})$/, \"$1_over$2\");' onmouseout='this.src = this.src.replace(/_over\\./, \".\");' />");
              </script>
            </div>
            <h1>Kilian Fatras</h1>
            <p class="lead">Master Student<br>
                Ecole Polytechnique - ENSTA ParisTech<br>
            </p>
          </div>
        </div>

        <div class="col-xs-13 col-sm-8 col-md-8">
          <div class="row">
            <hr>
              <p>I am currently a graduate student interning at University of British Columbia under the supervision of Pr. <a href="http://www.cs.ubc.ca/~schmidtm/">Mark Schmidt</a>.
                I am pursuing a double degree between ENSTA ParisTech and Ecole Polytechnique in applied mathematics and machine learning.
                During this double degree, I was a UC Berkeley student for the fall semester 2018 where I had the chance to meet my former supervisor <a href="http://fa.bianp.net/">Fabian Pedregosa</a>.
                Next November, I will start a PhD in optimal transport and machine learning under the supervsion of Pr. <a href="http://people.irisa.fr/Nicolas.Courty/">Nicolas Courty</a> and Pr. <a href="https://remi.flamary.com/">Rémi Flamary</a> at INRIA Rennes. You can find my <a href="pdf/CV_kilian_fatras.pdf" class="">resume</a> here.
                </p>
            </div>
            <div class="row"><a name="research_interests"></a>
            <hr class="bigHr">
            <center><h3>Research interests</h3></center>
            <hr>
                <p>
                My work focuses on <b>optimization for machine learning</b> and the interaction between <b>optimal transport and machine learning</b>.
                </p>
          </div>
          <div class="row"><a name="papers"></a>
          <hr class="bigHr">
          <center><h3>Papers</h3></center>
          <hr>
          <h4 style="margin-bottom:30px">Optimization</h4>

	   <p> <i><strong> Variance Reduced Three Operator Splitting</strong></i><br>
            Fabian Pedregosa, Kilian Fatras and Mattia Casotto.<br>
        <p><b>Abstract</b>: Despite the rise to fame of incremental variance-reduced methods in recent years, their use in nonsmooth optimization is still limited to few simple cases. This is due to the fact that existing methods require to evaluate the proximity operator for the nonsmooth terms, which can be a costly operation for complex penalties. In this work we introduce two variance-reduced incremental methods based on SAGA and SVRG that can efficiently take into account complex penalties which can be expressed as a sum of proximal terms. This includes penalties such as total variation, group lasso with overlap and trend filtering, to name a few. Furthermore, we also develop sparse variants of the proposed algorithms which can take advantage of sparsity in the input data. Like other incremental methods, it only requires to evaluate the gradient of a single sample per iteration, and so is ideally suited for large scale applications. We provide a convergence rate analysis for the proposed methods and show that they converge with a fixed step-size, achieving in some cases the same asymptotic rate as their full gradient variants. Empirical benchmarks on 3 different datasets illustrate the practical advantages of the proposed methods.</p>
          <div class="btn-group-xs">
	 <a a href="https://arxiv.org/abs/1806.07294" class="btn btn-default">Paper</a>
            <a a href="#/" class="btn btn-default" data-toggle="collapse" data-target=".bibtex-2">bibtex</a>
            <pre class="bibtex-2 collapse">
@InProceedings{Pedregosa2018VRTOS,
  author      = {Pedregosa, Fabian and Fatras, Kilian and Casotto, Mattia},
  title       = {Variance Reduced Three Operator Splitting},
  journal     = {?},
  year        = {2018}
}</pre>
          </div><br>
            </div>

              <div class="row">
                <hr class="bigHr">
                <center><h3><a name="Workshops"></a>Workshops</h3></center>
                <hr>
                This section is empty for the moment !
              </div>
              <div class="row">
                <hr class="bigHr">
                <center><h3><a name="Projects"></a>Projects</h3></center>
                <hr>
                        <p>Here is a list of the different projects I contributed to:</p>
                    <ol style="list-style-type:circle">
                    <b><a href="https://pot.readthedocs.io/en/stable/">POT</a>: Python For Optimal Transport</b> is an open source library for optimal transport in Python.
                    </ol>
                </div>
              <div class="row">
                <hr class="bigHr">
                <center><h3><a name="contact"></a>Contacts</h3></center>
                <hr>
                <address>
                    <div>
                    <p>I use several networks, do not hesitate to reach me out !
                    </p>
                    </div>

                </address>
              </div>
                <div id="social-link">
                  <a href="https://www.linkedin.com/in/kilianfatras" style="text-decoration:none;"><span style="font: 80% Arial,sans-serif; color:#0783B6;"><img src="./icons/linkedin.png" height="20" width="20" alt="See LinkedIn profile" style="vertical-align:middle;" border="0" onmouseover="this.src='./icons/mouseoverlinkedin.png';" onmouseout="this.src='./icons/linkedin.png';" ></span></a>
                  <a href="https://github.com/kilianFatras" style="text-decoration:none;"><span style="font: 80% Arial,sans-serif; color:#0783B6;"><img src="./icons/Octocat.png" height="20" width="20" alt="See GitHub profile" style="vertical-align:middle;" border="0" onmouseover="this.src='./icons/GitHub-Mark-32px.png';" onmouseout="this.src='./icons/Octocat.png';" ></span></a>
                  <a href="https://twitter.com/FatrasKilian" style="text-decoration:none;"><span style="font: 80% Arial,sans-serif; color:#0783B6;"><img src="./icons/Twitter_Logo_Blue.png" height="20" width="20" alt="Send an email" style="vertical-align:middle;" border="0" onmouseover="this.src='./icons/Twitter_Logo_WhiteOnImage.png';" onmouseout="this.src='./icons/Twitter_Logo_Blue.png';" ></span></a>
                  <a href="mailto:kilian dot fatras at gmail dot com" style="text-decoration:none;"><span style="font: 80% Arial,sans-serif; color:#0783B6;"><img src="./icons/mail.png" height="20" width="20" alt="Send an email" style="vertical-align:middle;" border="0" onmouseover="this.src='./icons/mouseovermail.png';" onmouseout="this.src='./icons/mail.png';" ></span></a>
                </div>
              </div>
            </div>
          <footer>&copy; 2018</footer>
        <!-- Bootstrap core JavaScript
        ================================================== -->
        <!-- Placed at the end of the document so the pages load faster -->
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
        <script type='text/javascript' src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
        <script src="offcanvas.js"></script>
        <script src="code.js"></script>
        </div>
      </body>
    </html>
