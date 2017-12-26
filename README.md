# signup form
# learning to use github
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  
  <style>

     input {
        width : 10%;  
     }
</style>
</head>
  

<body>
<img class="img-responsive" src="b.jpg" alt="Chania" width="50" height="50">
<div class="container">

  
  <form class="form-horizontal" action="/action_page.php">
     <div class="form-group">
      <label class="control-label col-sm-2" for="pwd">First Name:</label>
      <div class="col-sm-10">          
        <input type="name" class="form-control" id="pwd" placeholder="firstName" name="fname">
      </div>
    </div>
  <div class="form-group">
      <label class="control-label col-sm-2" for="pwd">Last Name:</label>
      <div class="col-sm-10">          
        <input type="name" class="form-control" id="pwd" placeholder="lastnameName" name="fname">
      </div>
    </div>
  
    <div class="form-group">
      <label class="control-label col-sm-2" for="email">Your Email:</label>
      <div class="col-sm-10">
        <input type="email" class="form-control" id="email" placeholder="Enter@email.com" name="email">
      </div>
    </div>
    <div class="form-group">
      <label class="control-label col-sm-2" for="pwd">Your Password:</label>
      <div class="col-sm-10">          
        <input type="password" class="form-control" id="pwd" placeholder="*********" name="pwd">
      </div>
    </div>
	<div class="form-group">
      <label class="control-label col-sm-2" for="pwd">Your Phone number:</label>
      <div class="col-sm-10">          
        <input type="password" class="form-control" id="pwd" placeholder="9874563210" name="pwd">
      </div>
    </div>
	
	
	
    
    <div class="form-group">        
      <div class="col-sm-offset-2 col-sm-10">
        <button type="submit" class="btn btn-default">SignUp</button>
      </div>
    </div>
  </form>
</div>
</body>
</html>
