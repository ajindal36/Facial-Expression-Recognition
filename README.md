# module3
<!DOCTYPE html>
<html lang="zxx">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Assignment Solution for Module 3</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/styles.css">
    <link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Abril+Fatface" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
<style>
.btn-default,
.btn-primary,
.btn-success,
.btn-info,
.btn-warning,
.btn-danger {
  text-shadow: 0 -1px 0 rgba(0, 0, 0, .2);
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, .15), 0 1px 1px rgba(0, 0, 0, .075);
          box-shadow: inset 0 1px 0 rgba(255, 255, 255, .15), 0 1px 1px rgba(0, 0, 0, .075);
}
.btn-default:active,
.btn-primary:active,
.btn-success:active,
.btn-info:active,
.btn-warning:active,
.btn-danger:active,
.btn-default.active,
.btn-primary.active,
.btn-success.active,
.btn-info.active,
.btn-warning.active,
.btn-danger.active {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
          box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
}
.btn-default.disabled,
.btn-primary.disabled,
.btn-success.disabled,
.btn-info.disabled,
.btn-warning.disabled,
.btn-danger.disabled,
.btn-default[disabled],
.btn-primary[disabled],
.btn-success[disabled],
.btn-info[disabled],
.btn-warning[disabled],
.btn-danger[disabled],
fieldset[disabled] .btn-default,
fieldset[disabled] .btn-primary,
fieldset[disabled] .btn-success,
fieldset[disabled] .btn-info,
fieldset[disabled] .btn-warning,
fieldset[disabled] .btn-danger {
  -webkit-box-shadow: none;
          box-shadow: none;
}
.btn-default .badge,
.btn-primary .badge,
.btn-success .badge,
.btn-info .badge,
.btn-warning .badge,
.btn-danger .badge {
  text-shadow: none;
}
.btn:active,
.btn.active {
  background-image: none;
}
.btn-default {
  text-shadow: 0 1px 0 #fff;
  background-image: -webkit-linear-gradient(top, #fff 0%, #e0e0e0 100%);
  background-image:      -o-linear-gradient(top, #fff 0%, #e0e0e0 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#fff), to(#e0e0e0));
  background-image:         linear-gradient(to bottom, #fff 0%, #e0e0e0 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffffff', endColorstr='#ffe0e0e0', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-color: #dbdbdb;
  border-color: #ccc;
}
.btn-default:hover,
.btn-default:focus {
  background-color: #e0e0e0;
  background-position: 0 -15px;
}
.btn-default:active,
.btn-default.active {
  background-color: #e0e0e0;
  border-color: #dbdbdb;
}
.btn-default.disabled,
.btn-default[disabled],
fieldset[disabled] .btn-default,
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus,
.btn-default.disabled:active,
.btn-default[disabled]:active,
fieldset[disabled] .btn-default:active,
.btn-default.disabled.active,
.btn-default[disabled].active,
fieldset[disabled] .btn-default.active {
  background-color: #e0e0e0;
  background-image: none;
}
.btn-primary {
  background-image: -webkit-linear-gradient(top, #337ab7 0%, #265a88 100%);
  background-image:      -o-linear-gradient(top, #337ab7 0%, #265a88 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#337ab7), to(#265a88));
  background-image:         linear-gradient(to bottom, #337ab7 0%, #265a88 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff337ab7', endColorstr='#ff265a88', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-color: #245580;
}
.btn-primary:hover,
.btn-primary:focus {
  background-color: #265a88;
  background-position: 0 -15px;
}
.btn-primary:active,
.btn-primary.active {
  background-color: #265a88;
  border-color: #245580;
}
.btn-primary.disabled,
.btn-primary[disabled],
fieldset[disabled] .btn-primary,
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus,
.btn-primary.disabled:active,
.btn-primary[disabled]:active,
fieldset[disabled] .btn-primary:active,
.btn-primary.disabled.active,
.btn-primary[disabled].active,
fieldset[disabled] .btn-primary.active {
  background-color: #265a88;
  background-image: none;
}
.btn-success {
  background-image: -webkit-linear-gradient(top, #5cb85c 0%, #419641 100%);
  background-image:      -o-linear-gradient(top, #5cb85c 0%, #419641 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#5cb85c), to(#419641));
  background-image:         linear-gradient(to bottom, #5cb85c 0%, #419641 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff5cb85c', endColorstr='#ff419641', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-color: #3e8f3e;
}
.btn-success:hover,
.btn-success:focus {
  background-color: #419641;
  background-position: 0 -15px;
}
.btn-success:active,
.btn-success.active {
  background-color: #419641;
  border-color: #3e8f3e;
}
.btn-success.disabled,
.btn-success[disabled],
fieldset[disabled] .btn-success,
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus,
.btn-success.disabled:active,
.btn-success[disabled]:active,
fieldset[disabled] .btn-success:active,
.btn-success.disabled.active,
.btn-success[disabled].active,
fieldset[disabled] .btn-success.active {
  background-color: #419641;
  background-image: none;
}
.btn-info {
  background-image: -webkit-linear-gradient(top, #5bc0de 0%, #2aabd2 100%);
  background-image:      -o-linear-gradient(top, #5bc0de 0%, #2aabd2 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#5bc0de), to(#2aabd2));
  background-image:         linear-gradient(to bottom, #5bc0de 0%, #2aabd2 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff5bc0de', endColorstr='#ff2aabd2', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-color: #28a4c9;
}
.btn-info:hover,
.btn-info:focus {
  background-color: #2aabd2;
  background-position: 0 -15px;
}
.btn-info:active,
.btn-info.active {
  background-color: #2aabd2;
  border-color: #28a4c9;
}
.btn-info.disabled,
.btn-info[disabled],
fieldset[disabled] .btn-info,
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus,
.btn-info.disabled:active,
.btn-info[disabled]:active,
fieldset[disabled] .btn-info:active,
.btn-info.disabled.active,
.btn-info[disabled].active,
fieldset[disabled] .btn-info.active {
  background-color: #2aabd2;
  background-image: none;
}
.btn-warning {
  background-image: -webkit-linear-gradient(top, #f0ad4e 0%, #eb9316 100%);
  background-image:      -o-linear-gradient(top, #f0ad4e 0%, #eb9316 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#f0ad4e), to(#eb9316));
  background-image:         linear-gradient(to bottom, #f0ad4e 0%, #eb9316 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fff0ad4e', endColorstr='#ffeb9316', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-color: #e38d13;
}
.btn-warning:hover,
.btn-warning:focus {
  background-color: #eb9316;
  background-position: 0 -15px;
}
.btn-warning:active,
.btn-warning.active {
  background-color: #eb9316;
  border-color: #e38d13;
}
.btn-warning.disabled,
.btn-warning[disabled],
fieldset[disabled] .btn-warning,
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus,
.btn-warning.disabled:active,
.btn-warning[disabled]:active,
fieldset[disabled] .btn-warning:active,
.btn-warning.disabled.active,
.btn-warning[disabled].active,
fieldset[disabled] .btn-warning.active {
  background-color: #eb9316;
  background-image: none;
}
.btn-danger {
  background-image: -webkit-linear-gradient(top, #d9534f 0%, #c12e2a 100%);
  background-image:      -o-linear-gradient(top, #d9534f 0%, #c12e2a 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#d9534f), to(#c12e2a));
  background-image:         linear-gradient(to bottom, #d9534f 0%, #c12e2a 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffd9534f', endColorstr='#ffc12e2a', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-color: #b92c28;
}
.btn-danger:hover,
.btn-danger:focus {
  background-color: #c12e2a;
  background-position: 0 -15px;
}
.btn-danger:active,
.btn-danger.active {
  background-color: #c12e2a;
  border-color: #b92c28;
}
.btn-danger.disabled,
.btn-danger[disabled],
fieldset[disabled] .btn-danger,
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus,
.btn-danger.disabled:active,
.btn-danger[disabled]:active,
fieldset[disabled] .btn-danger:active,
.btn-danger.disabled.active,
.btn-danger[disabled].active,
fieldset[disabled] .btn-danger.active {
  background-color: #c12e2a;
  background-image: none;
}
.thumbnail,
.img-thumbnail {
  -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, .075);
          box-shadow: 0 1px 2px rgba(0, 0, 0, .075);
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  background-color: #e8e8e8;
  background-image: -webkit-linear-gradient(top, #f5f5f5 0%, #e8e8e8 100%);
  background-image:      -o-linear-gradient(top, #f5f5f5 0%, #e8e8e8 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#f5f5f5), to(#e8e8e8));
  background-image:         linear-gradient(to bottom, #f5f5f5 0%, #e8e8e8 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fff5f5f5', endColorstr='#ffe8e8e8', GradientType=0);
  background-repeat: repeat-x;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  background-color: #2e6da4;
  background-image: -webkit-linear-gradient(top, #337ab7 0%, #2e6da4 100%);
  background-image:      -o-linear-gradient(top, #337ab7 0%, #2e6da4 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#337ab7), to(#2e6da4));
  background-image:         linear-gradient(to bottom, #337ab7 0%, #2e6da4 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff337ab7', endColorstr='#ff2e6da4', GradientType=0);
  background-repeat: repeat-x;
}
.navbar-default {
  background-image: -webkit-linear-gradient(top, #fff 0%, #f8f8f8 100%);
  background-image:      -o-linear-gradient(top, #fff 0%, #f8f8f8 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#fff), to(#f8f8f8));
  background-image:         linear-gradient(to bottom, #fff 0%, #f8f8f8 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffffff', endColorstr='#fff8f8f8', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-radius: 4px;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, .15), 0 1px 5px rgba(0, 0, 0, .075);
          box-shadow: inset 0 1px 0 rgba(255, 255, 255, .15), 0 1px 5px rgba(0, 0, 0, .075);
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .active > a {
  background-image: -webkit-linear-gradient(top, #dbdbdb 0%, #e2e2e2 100%);
  background-image:      -o-linear-gradient(top, #dbdbdb 0%, #e2e2e2 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#dbdbdb), to(#e2e2e2));
  background-image:         linear-gradient(to bottom, #dbdbdb 0%, #e2e2e2 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffdbdbdb', endColorstr='#ffe2e2e2', GradientType=0);
  background-repeat: repeat-x;
  -webkit-box-shadow: inset 0 3px 9px rgba(0, 0, 0, .075);
          box-shadow: inset 0 3px 9px rgba(0, 0, 0, .075);
}
.navbar-brand,
.navbar-nav > li > a {
  text-shadow: 0 1px 0 rgba(255, 255, 255, .25);
}
.navbar-inverse {
  background-image: -webkit-linear-gradient(top, #3c3c3c 0%, #222 100%);
  background-image:      -o-linear-gradient(top, #3c3c3c 0%, #222 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#3c3c3c), to(#222));
  background-image:         linear-gradient(to bottom, #3c3c3c 0%, #222 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff3c3c3c', endColorstr='#ff222222', GradientType=0);
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  background-repeat: repeat-x;
  border-radius: 4px;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .active > a {
  background-image: -webkit-linear-gradient(top, #080808 0%, #0f0f0f 100%);
  background-image:      -o-linear-gradient(top, #080808 0%, #0f0f0f 100%);
  background-image: -webkit-gradient(linear, left top, left bottom, from(#080808), to(#0f0f0f));
  background-image:         linear-gradient(to bottom, #080808 0%, #0f0f0f 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff080808', endColorstr='#ff0f0f0f', GradientType=0);
  background-repeat: repeat-x;
  -webkit-box-shadow: inset 0 3px 9px rgba(0, 0, 0, .25);
          box-shadow: inset 0 3px 9px rgba(0, 0, 0, .25);
}
.navbar-inverse .navbar-brand,
.navbar-inverse .navbar-nav > li > a {
  text-shadow: 0 -1px 0 rgba(0, 0, 0, .25);
}
.navbar-static-top,
.navbar-fixed-top,
.navbar-fixed-bottom {
  border-radius: 0;
}
</style>
</head>
<body>
    <header>
        <nav id="header-nav" class="navbar navbar-default">
            <div class="container-fluid">
                <div class="navbar-header">
                    <div class="navbar-brand">
                        <a href="index.html"><h1>Food, LLC</h1></a>
                    </div>

                    <button type="button" class="navbar-toggle collapsed visible-xs" data-toggle="collapse" data-target="#collapsable-nav" aria-expanded="false">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                </div>

                <div id="collapsable-nav" class="collapse navbar-collapse">
                    <ul id="nav-list" class="nav navbar-nav navbar-right visible-xs text-center">
                        <li>
                            <a href="#chicken-tile"><br class="hidden-xs"> Chicken</a>
                        </li>
                        <li>
                            <a href="#beef-tile"><br class="hidden-xs"> Beef</a>
                        </li>
                        <li>
                            <a href="#sushi-tile"><br class="hidden-xs"> Sushi</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <div id="main-content" class="container">
        <h2 id="top-heading" class="text-center">Our Menu</h2>
        <div id="home-tiles" class="row">
            <div class="col-md-4 col-sm-6 col-xs-12">
                <div id="chicken-tile">
                    <section>
                        <h3 class="text-center">Chicken</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata
                            sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo
                            duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore
                            magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit
                            in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.
                            Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit
                            lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim
                            qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum
                            dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl
                            ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis. At vero eos et accusam et justo duo dolores et ea rebum.
                            Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
                            diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam
                            aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet.
                            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat. Consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore
                            magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing
                            elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
                            ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et
                            ea rebum. Stet clita kasd gubergren, no sea takimata sanctus. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero
                            eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt
                            ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet,
                            consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata
                            sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui
                            blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
                            Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum
                            dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue
                            nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim
                            ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu
                            feugiat nulla facilisis. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                            diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor
                            sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no
                            rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat. Consetetur
                            sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et
                        </p>
                        <p>
                            (End of Chicken section) <a href="#top-heading">Back to Top</a>
                        </p>
                    </section>
                </div>
            </div>
            <div class="col-md-4 col-sm-6 col-xs-12">
                <div id="beef-tile">
                    <section>
                        <h3 class="text-center">Beef</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata
                            sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo
                            duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore
                            magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit
                            in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.
                            Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit
                            lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim
                            qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum
                            dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl
                            ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis. At vero eos et accusam et justo duo dolores et ea rebum.
                            Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
                            diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam
                            aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet.
                            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat. Consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore
                            magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing
                            elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
                            ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et
                            ea rebum. Stet clita kasd gubergren, no sea takimata sanctus. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero
                            eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt
                            ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet,
                            consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata
                            sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui
                            blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
                            Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum
                            dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue
                            nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim
                            ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu
                            feugiat nulla facilisis. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
                            diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor
                            sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no
                            rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat. Consetetur
                            sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus
                            est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo
                            dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna
                            aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
                            tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum
                            dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et
                        </p>
                        <p>
                            (End of Beef section) <a href="#top-heading">Back to Top</a>
                        </p>
                    </section>
                </div>
            </div>
            <!-- <div class="clearfix visible-md-block"></div> -->
            <div class="col-md-4 col-sm-12 col-xs-12">
                <div id="sushi-tile">
                    <section>
                        <h3 class="text-center">Sushi</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata
                            sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo
                            duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore
                            magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit
                            in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.
                            Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit
                            lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim
                            qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum
                            dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl
                            ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis. At vero eos et accusam et justo duo dolores et ea rebum.
                            Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
                            diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam
                            aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet.
                            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat. Consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore
                            magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing
                            elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
                            ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et
                            ea rebum. Stet clita kasd gubergren, no sea takimata sanctus. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero
                            eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt
                            ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet,
                            consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata
                            sanctus est Lorem ipsum dolor sit amet. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui
                            blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
                            Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl
                        </p>
                        <p>
                            (End of Sushi section) <a href="#top-heading">Back to Top</a>
                        </p>
                    </section>
                </div>
            </div>
            <!-- <div class="clearfix visible-lg-block"></div> -->
        </div>
    </div>
    <div class="clearfix visible-lg-block"></div>


    <!-- jQuery (Bootstrap JS plugins depend on it) -->
    <script src="js/jquery-3.1.1.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <!-- <script src="js/script.js"></script> -->

</body>

</html>
