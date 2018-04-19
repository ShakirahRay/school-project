# school-project

/* ========================================================= */

/*  IMPORTS for fonts */

@import url('https://fonts.googleapis.com/css?family=Roboto');
@import url('https://fonts.googleapis.com/css?family=Open+Sans');
@import url('https://fonts.googleapis.com/css?family=Arimo|Lobster');


/* ========================================================= */

/*  Font Style Rules */

body {
    font-family: 'Arimo', sans-serif;
}

/* ========================================================= */

/* Text Style Rules */

h1 {

    font-family: 'Lobster', cursive;
    font-size: 36px;
    text-transform: uppercase;
    font-weight: 600;
    margin-bottom: 0px;
    color: #FFCAD4;
}

h2 {
    font-family: 'Lobster', cursive;
    font-size: 36px;
    text-transform: uppercase;
    font-weight: 600;
    margin-bottom: 30px;
    color: #FFCAD4;
}

h4 {
    font-family: 'Lobster', cursive;
    font-size: 24px;
    line-height: 1.375em;
    font-weight: 400;
    margin-bottom: 30px;
    color: #FFCAD4;
}

p {
    font-family: 'Arimo', sans-serif;
    font-size: 18px;
    font-weight: 400;
    line-height: 1.8;
    color: #333745;
}

/* HR Styles */

hr {
    border-top: 10px dashed #333745;
}

/* ========================================================= */

/*  Rules */

/* Container Section */

.box2 {padding: 40px;
border: 25px solid black;}

.box {
    width: 100px;
    border: 25px solid green;
    padding: 25px;
    margin: px;
}

.container-fluid,
.container {
    padding: 5px 20px;
}

.text-spacing {
    padding: 20px;
    font: 'Arimo', sans-serif;
}

.section-spacing {
    padding: 1.0em;
}

/* ========================================================= */

/* Color Style Rules

    Reference:  coolors.co

    .pink   #F391A0
    .red    #DB504A
    .lavender #7C606B
    .purple #361134
    .white  #F7F5FB
*/

.bg-red {
    background-color: #DB504A;
    color: #F7F5FB !important;
}

.bg-lavender {
    background-color: #7C606B;
    color: #F7F5FB !important;
    font:  'Arimo', sans-serif;
}

.bg-purple {
    background-color: #361134;
    color: #F7F5FB !important;
}

.bg-white {
    background-color: #F7F5FB;
    color: #333745 !important;
}

.bg-pink {
    background-color: #F391A0;
    color: #F7F5FB !important;
}

.text-white {
    color: #F7F5FB !important;
}

/* ========================================================= */

/* Button Styles */

.btn {
    border: 1px solid #F391A0;
    background-color: #F391A0 !important;
    color: #F7F5FB;
}

.btn:hover {
    border: 1px solid #DB504A;
    background-color: #F7F5FB !important;
    color: #DB504A;
}

/* ========================================================= */

/* Tabs */

/* Tabs .borders :: Add borders to tab content */

.nav-tabs .nav-link {
    background-color: #F7F5FB;
    color: #DB504A !important;
    border-color: #DB504A;
}

.nav-tabs .nav-link:focus,
.nav-tabs .nav-link:hover {
    background-color: #F7F5FB;
    color: #DB504A !important;
    border-color: #DB504A;
}

.nav-tabs .nav-link,
.nav-tabs .nav-item.show .nav-link {
    background-color: #DB504A;
    color: #F7F5FB !important;
    border-color: #F7F5FB;
    display: flow-root;

}


/* ========================================================= */

/* Navbar */

.navbar {
    background-color: #DB504A;
}

.navbar .navbar-brand {
    color: #ecf0f1;
}

.navbar .navbar-brand:hover,
.navbar .navbar-brand:focus {
    color: #f7f5fb;
}

.navbar .navbar-text {
    color: #ecf0f1;
}

.navbar .navbar-nav .nav-link {
    color: #ecf0f1;
    border-radius: .25rem;
    margin: 0 0.25em;
}

.navbar .navbar-nav .nav-link:not(.disabled):hover,
.navbar .navbar-nav .nav-link:not(.disabled):focus {
    color: #f7f5fb;
}

.navbar .navbar-nav .nav-item.active .nav-link,
.navbar .navbar-nav .nav-item.active .nav-link:hover,
.navbar .navbar-nav .nav-item.active .nav-link:focus,
.navbar .navbar-nav .nav-item.show .nav-link,
.navbar .navbar-nav .nav-item.show .nav-link:hover,
.navbar .navbar-nav .nav-item.show .nav-link:focus {
    color: #f7f5fb;
    background-color: #DB504A;
}

.navbar .navbar-toggle {
    border-color: #DB504A;
}

.navbar .navbar-toggle:hover,
.navbar .navbar-toggle:focus {
    background-color: #DB504A;
}

.navbar .navbar-toggle .navbar-toggler-icon {
    color: #ecf0f1;
}

.navbar .navbar-collapse,
.navbar .navbar-form {
    border-color: #ecf0f1;
}

.navbar .navbar-link {
    color: #ecf0f1;
}

.navbar .navbar-link:hover {
    color: #f7f5fb;
}
