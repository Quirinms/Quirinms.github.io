<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
        <meta name="description" content="" />
        <meta name="author" content="" />
        <title>Deep Bionic</title>
        <link rel="icon" type="image/x-icon" href="assets/img/favicon.ico" />
        <!-- Font Awesome icons (free version)-->
        <script src="https://use.fontawesome.com/releases/v5.15.1/js/all.js" crossorigin="anonymous"></script>
        <!-- Google fonts-->
        <link href="https://fonts.googleapis.com/css?family=Varela+Round" rel="stylesheet" />
        <link href="https://fonts.googleapis.com/css?family=Nunito:200,200i,300,300i,400,400i,600,600i,700,700i,800,800i,900,900i" rel="stylesheet" />
        <!-- Core theme CSS (includes Bootstrap)-->
        <link href="css/styles.css" rel="stylesheet" />
    </head>
    <body id="page-top">
        <!-- Navigation-->
        <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
            <div class="container">
                <a class="navbar-brand js-scroll-trigger" href="#page-top">Start Bootstrap</a>
                <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                    Menu
                    <i class="fas fa-bars"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarResponsive">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#index">Home</a></li>
                        <li class="nav-item"><a class="nav-link js-scroll-trigger" href="projects">Projects</a></li>
                        <li class="nav-item"><a class="nav-link js-scroll-trigger" href="rpackages">R Packages</a></li>
                        <li class="nav-item"><a class="nav-link js-scroll-trigger" href="lectures">Lectures</a></li>
                        <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#publications">Publications</a></li>
                        <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#contactme">Contact Me</a></li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- Contact-->
        <section class="contact-section bg-black">
            <div class="container">
                <div class="row">
                    <div class="col-md-4 mb-3 mb-md-0">
                        <div class="card py-4 h-100">
                            <div class="card-body text-center">
                                <i class="fas fa-map-marked-alt text-primary mb-2"></i>
                                <h4 class="text-uppercase m-0">Address</h4>
                                <hr class="my-4" />
                                <div class="small text-black-50">4923 Market Street, Orlando FL</div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 mb-3 mb-md-0">
                        <div class="card py-4 h-100">
                            <div class="card-body text-center">
                                <i class="fas fa-envelope text-primary mb-2"></i>
                                <h4 class="text-uppercase m-0">Email</h4>
                                <hr class="my-4" />
                                <div class="small text-black-50"><a href="#!">hello@yourdomain.com</a></div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 mb-3 mb-md-0">
                        <div class="card py-4 h-100">
                            <div class="card-body text-center">
                                <i class="fas fa-mobile-alt text-primary mb-2"></i>
                                <h4 class="text-uppercase m-0">Phone</h4>
                                <hr class="my-4" />
                                <div class="small text-black-50">+1 (555) 902-8832</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="social d-flex justify-content-center">
                    <a class="mx-2" href="#!"><i class="fab fa-twitter"></i></a>
                    <a class="mx-2" href="#!"><i class="fab fa-facebook-f"></i></a>
                    <a class="mx-2" href="#!"><i class="fab fa-github"></i></a>
                </div>
            </div>
        </section>
        <!-- Footer-->
        <footer class="footer bg-black small text-center text-white-50"><div class="container">Copyright © Your Website 2020</div></footer>
        <!-- Bootstrap core JS-->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js"></script>
        <!-- Third party plugin JS-->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js"></script>
        <!-- Core theme JS-->
        <script src="js/scripts.js"></script>
    </body>
</html>


# R Packages



## Variable Declarations

| **var** | **let** | **const** |
|-----|-----|-----|
| Declares a variable, optionally initializing it to a value. | Declares a block-scoped, local variable, optionally initializing it to a value. | Declares a block-scoped, read-only named constant. |
| Variable declared by **`var`** must start with a letter, underscore ( _ ) or dollar sign ($) and can contain alphabetic, numeric, or underscore characters. | Variable declared by **`let`** must start with a letter, underscore ( _ ) or dollar sign ($) and can contain alphabetic, numeric, or underscore characters. | Variable declared by **`const`** must start with a letter, underscore ( _ ) or dollar sign ($) and can contain alphabetic, numeric, or underscore characters. |






<table class="tablelines">
  <thead>
    <tr>
      <th>P</th>
      <th>Q</th>
      <th>P * Q</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>T</td>
      <td>T</td>
      <td>T</td>
    </tr>
    <tr>
      <td>T</td>
      <td>F</td>
      <td>F</td>
    </tr>
    <tr>
      <td>F</td>
      <td>T</td>
      <td>F</td>
    </tr>
    <tr>
      <td>F</td>
      <td>F</td>
      <td>F</td>
    </tr>
  </tbody>
</table>

<table class="tablelines">
  <tbody>
    <tr>
      <td>a</td>
      <td>b</td>
      <td>c</td>
    </tr>
    <tr>
      <td>1</td>
      <td>2</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

<table class="tablelines">
  <thead>
    <tr>
      <th>Default aligned</th>
      <th style="text-align: left">Left aligned</th>
      <th style="text-align: center">Center aligned</th>
      <th style="text-align: right">Right aligned</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>First body part</td>
      <td style="text-align: left">Second cell</td>
      <td style="text-align: center">Third cell</td>
      <td style="text-align: right">fourth cell</td>
    </tr>
    <tr>
      <td>Second line</td>
      <td style="text-align: left">foo</td>
      <td style="text-align: center"><strong>strong</strong></td>
      <td style="text-align: right">baz</td>
    </tr>
    <tr>
      <td>Third line</td>
      <td style="text-align: left">quux</td>
      <td style="text-align: center">baz</td>
      <td style="text-align: right">bar</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>Second body</td>
      <td style="text-align: left"> </td>
      <td style="text-align: center"> </td>
      <td style="text-align: right"> </td>
    </tr>
    <tr>
      <td>2 line</td>
      <td style="text-align: left"> </td>
      <td style="text-align: center"> </td>
      <td style="text-align: right"> </td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Footer row</td>
      <td style="text-align: left"> </td>
      <td style="text-align: center"> </td>
      <td style="text-align: right"> </td>
    </tr>
  </tfoot>
</table>

<table class="tablelines">
  <tbody>
    <tr>
      <td>A simple</td>
      <td>table</td>
    </tr>
    <tr>
      <td>with multiple</td>
      <td>lines</td>
    </tr>
  </tbody>
</table>




| P | Q | P * Q |
| - | - | - |
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |
{: .tablelines}

|---|---|---|
|a  | b | c|
| 1|2|3|


| Name                | Licence    | Link | Authors                                                                                        |
|---------------------|------------|------|------------------------------------------------------------------------------------------------|
| DataVisualizations  | GPL-3      | CRAN | Michael Thrun, Felix Pape, Onno Hansen-Goos, Dirk Eddelbuettel, Craig Varrichio, Alfred Ultsch |
| DatabionicSwarm     | GPL-3      | CRAN | Michael Thrun                                                                                  |



