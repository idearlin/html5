
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<!-- 引入bootstrap里面的css文件 -->
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<!-- 2.引入bootstrap里面的js文件 -->
	<!-- 注意：引入之前要先引入jquery.js -->
	<!-- <src_tab键 -->
	<script type="text/javascript" src="js/jquery-3.1.0.min.js"></script>
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<style type="text/css">
		.navbar{
			margin-bottom:0;
		}
		.thumbnail{
			border-width:0;
		}
	</style>
</head>
<body>
<nav class="navbar navbar-inverse" role="navigation">
  <div class="container">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">project name</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <form class="navbar-form navbar-right" role="search">
        <div class="form-group">
          <input type="email" class="form-control" placeholder="Email">
          <input type="password" class="form-control" placeholder="Password">
        </div>
        <button type="submit" class="btn btn-success">Submit</button>
      </form>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
<div class="jumbotron">
  <div class="container">
  <h1>Hello, world!</h1>
  <p>This is a template for a simple marketing or informational website. It includes a large callout called a jumbotron and three supporting pieces of content. Use it as a starting point to create something more unique.</p>
  <p><a class="btn btn-primary btn-lg navbar-left" href="#" role="button">Learn more »</a></p>
</div>
</div>

<div class="container">
<div class="row">
  <div class="col-md-4">
    <div class="thumbnail">
      <div class="caption">
        <h2>Heading</h2>
        <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
        <p><a href="#" class="btn btn-default" role="button">View details »</a></p>
      </div>
    </div>
  </div>
  <div class="col-md-4">
    <div class="thumbnail">
      <div class="caption">
        <h2>Heading</h2>
        <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
        <p><a href="#" class="btn btn-default" role="button">View details »</a></p>
      </div>
    </div>
  </div>
  <div class="col-md-4">
    <div class="thumbnail">
      <div class="caption">
        <h2>Heading</h2>
        <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
        <p><a href="#" class="btn btn-default" role="button">View details »</a></p>
      </div>
    </div>
  </div>
</div>
</div>
<footer>
	<p>&copy;Company 2004</p>
</footer>
</body>
</html>
