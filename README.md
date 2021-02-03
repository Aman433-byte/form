 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- og description for social media's . most important!  -->
    <!--facebook OG-->
    <meta property="og:title" content="Sulphuric Bench" />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://mahtamun-hoque-fahim.github.io/sulphuric-bench" />
    <meta property="og:image" content="https://mahtamun-hoque-fahim.github.io/sulphuric-bench/social-preview.jpg" />
    <meta property="fb:app_id" content="514902809457075" />
    <meta property="og:description" content="Excel Your Learning" />

    <!-- for twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:site" content="@mahtamun-hoque-fahim" />
    <meta name="twitter:creator" content="@mahtamunF" />
    <meta property="og:url" content="http://mahtamun-hoque-fahim.github.io/sulphuric-bench" />
    <meta property="og:title" content="Sulphuric Bench" />
    <meta property="og:description" content="Excel Your Learning" />
    <meta property="og:image" content="https://mahtamun-hoque-fahim.github.io/sulphuric-bench/social-preview.jpg" />

    <!-- Phone browsers status bar colors-->
    <!-- for android phone browsers -->
    <meta name="theme-color" content="#0cb1ff" />
    <!-- Windows Phone -->
    <meta name="msapplication-navbutton-color" content="#0cb1ff">
    <!-- iOS Safari -->
    <meta name="apple-mobile-web-app-status-bar-style" content="#0cb1ff">
    <!-- favicon -->
    <link rel="icon" href="favicon.png">

    <!-- fontawsome -->
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.1/css/all.css">

    <!-- font 1 -->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Dosis:wght@200&display=swap" rel="stylesheet">

    <!-- font 2 -->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Megrim&display=swap" rel="stylesheet">

    <!-- bootstrap  -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- my custom css -->
    <link rel="stylesheet" href="style.css">
    <title>Sulphuric Bench </title>
</head>

<body>
    <!-- this is navbar -->
    <nav class="navbar navbar-expand-lg sticky-top link-act navbar-light nav-bg">
        <div class="container-fluid">
            <a class="navbar-brand" href="#home"><img id="nav-logo" src="sulphuric logo.png" alt=""></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="#who_we_are">Who we are </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="#latest_work">Our Latest Videos</a>
                    </li>
                </ul>
            </div>
            <form class="d-flex">
                <input class="form-control shadow me-2" type="search" placeholder="Search Here" aria-label="Search">
                <button class="btn btn-light shadow" type="submit">Search</button>
            </form>
        </div>
    </nav>

    <!-- this is home  -->
    <!-- this is header  -->
    <div id="home" class="header vh-90 p-4">
        <div class="container-fluid">
            <img class="img-fluid header-pic" src="Circles.gif" alt="">
        </div>
        <div class="header-text shadow p-4">
            <h1 class="text-center text-white hdr-text">SULPHURIC BENCH</h1>
            <h4 class="text-center text-white hdr-text">Excel your learning </h4>
        </div>
    </div>

    <!-- who we ar  -->
    <!-- card-1  -->
    <div id="who_we_are" class="row">
        <div class="card m-5 shadow" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-auto">
                    <img src="Quality edu.gif" alt="..." class="img-fluid quality-edu-pic">
                </div>
                <div class="col-md-auto">
                    <div class="card-body">
                        <h4 class="card-title">Get Quality Education For Free</h4>
                        <p class="card-text">This online platform called Sulfuric Bench is aimed at making educational
                            activities more complete. </p>

                    </div>
                </div>
            </div>
        </div>

        <!-- card-2  -->
        <div class="card m-5 shadow" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-auto">
                    <img src="from Home.gif" alt="..." class="img-fluid quality-edu-pic">
                </div>
                <div class="col-md-auto">
                    <div class="card-body">
                        <h4 class="card-title">Learn Wherever You Are</h4>
                        <p class="card-text">Learn as much as you wish from here from any corner of the world. Just a
                            device and internet connection needed for it! </p>

                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container-fluid">
        <hr>
    </div>
    <!-- announcement -->
    <div class="announcement">
        <h1 class="text-center p-4 display-4">
            Checkout our new video!
        </h1>

        <!-- video  -->
        <div id="latest_work" class="container-fluid video ">
            <iframe class="shadow" max-width="560" max-height="315"
                src="https://www.youtube-nocookie.com/embed/eKtPfjt4Ggc" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
        </div>
    </div>
    <br>
    <br>
    <br>

    <div class=" row footer-text ">
        <div class="container ">
            <p class="py-6 ">This is a open source landing page built for <button
                    href="https://facebook.com/sulphuric.bench" class="btn btn-primary shadow">Sulphuric Bench</button>
            </p>
        </div>
        <div class="made-by p-9">
            <p>Made with ❤ by<a class="btn btn-primary m-2 shadow"
                    href="https://github.com/mahtamun-hoque-fahim">Fahim</a></p>
        </div>
    </div>








</body>

<html>


