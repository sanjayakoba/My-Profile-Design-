<!doctype html>
<html lang="en">
<head>

  <meta charset="utf-8" />
	<link rel="apple-touch-icon" sizes="76x76" href="assets/img/apple-icon.png">
	<link rel="icon" type="image/png" sizes="96x96" href="assets/img/favicon.png">
	<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />

	<title>User Profile</title>

	<meta content='width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0' name='viewport' />
    <meta name="viewport" content="width=device-width" />


    <!-- Bootstrap core CSS     -->
    <link href="assets/css/bootstrap.min.css" rel="stylesheet" />
	
	<!-- Animate CSS     -->
    <link href="assets/css/animate.min.css" rel="stylesheet" />

    <!--  Paper Dashboard core CSS    -->
    <link href="assets/css/my_account.css" rel="stylesheet"/>

    <!--  CSS for Demo Purpose, don't include it in your project     -->

    <!--  Fonts and icons     -->
    <link href="http://maxcdn.bootstrapcdn.com/font-awesome/latest/css/font-awesome.min.css" rel="stylesheet">
    <link href='https://fonts.googleapis.com/css?family=Muli:400,300' rel='stylesheet' type='text/css'>
    <link href="assets/css/themify-icons.css" rel="stylesheet">
  
</head>
<body>
<div style="background-image: url('/Loginassets/gwk.jpg');">
    <div id="main">
        <!-- CONTENT-->
        <div class="container" style="padding-top: 4%;">
            <div align="center">
                <h3 class="hr-sxsmall">My Account</h3>
            </div>
            <br>
           

           
      <div class="main-panel">
		     <div class="content">
               <div class="container-fluid">
					<div class="row">
                      <div class="col-lg-4 col-md-5">
                        <div class="card card-user">
                            <div class="image">
                                <img src="assets/img/background.jpg" alt="..."/>
                            </div>
                            <div class="content">
                                <div class="author">
                                  <img class="avatar border-white" src="assets/img/faces/face-2.jpg" alt="..."/>
                                
                                </div>
                            </div>
                            <hr>
                        </div>
					</div>
		 
                    <div class="col-lg-8 col-md-7">
                        <div class="card">
                            <div style="background-color:rgb(0, 186, 242);height:50px">
                                <h4 class="title" style="text-align:center;padding:10px">Edit Profile</h4>
                            </div>
                            <div class="content">
                                <form>
                                    <!--<div class="row">
                                        <div class="col-md-5">
                                            <div class="form-group">
                                                <label>Company</label>
                                                <input type="text" class="form-control border-input" placeholder="Company" value="Creative Code Inc.">
                                            </div>
                                        </div>
                                        <div class="col-md-3">
                                            <div class="form-group">
                                                <label>Username</label>
                                                <input type="text" class="form-control border-input" placeholder="Username" value="michael23">
                                            </div>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="form-group">
                                                <label for="exampleInputEmail1">Email address</label>
                                                <input type="email" class="form-control border-input" placeholder="Email">
                                            </div>
                                        </div>
                                    </div> -->

                                    <div class="row">
                                        <div class="col-md-12">
                                            <div class="form-group">
                                                <label>Full Name</label>
                                                <input type="text" class="form-control border-input" placeholder="Company" value="Chet">
                                            </div>
                                        </div>
									</div>
									
									<div class="row">
                                        <div class="col-md-12">
                                            <div class="form-group">
                                                <label>Password</label>
                                                <input type="password" class="form-control border-input" placeholder="Last Name" value="Faker">
                                            </div>
                                        </div>
									</div>

									<div class="row">
										<div class="col-md-12">
                                            <div class="form-group">
                                                <label>DOB</label>
                                                <input type="date" class="form-control border-input" placeholder="Last Name" value="Faker">
                                            </div>
                                        </div>
									</div>
									
									<div class="row">
                                        <div class="col-md-12">
                                            <div class="form-group">
                                                <label>Phone No.</label>
                                                <input type="number" class="form-control border-input" placeholder="Phone" value="Melbourne">
                                            </div>
                                        </div>
									</div>
									
									<div class="row">
                                        <div class="col-md-12">
                                            <div class="form-group">
                                                <label for="exampleInputEmail1">Email address</label>
                                                <input type="email" class="form-control border-input" placeholder="Email">
                                            </div>
                                        </div>
									</div>

									<div class="row">
										<div class="col-md-12">
											<div class="form-group">
												<label>Gender</label>
												<label>
													<input class="radio" type="radio" name="gender" value="male">
													<h5 class="radio icons first-icon second-icon">Male</h5>
												</label>
												<label>
													<input class="radio" type="radio" name="gender" value="male">
													<h5 class="radio icons first-icon second-icon">Female</h5>
												</label>
												<label>
													<input class="radio" type="radio" name="gender" value="male">
													<h5 class="radio icons first-icon second-icon">Other</h5>
												</label>
											</div>
										</div>
									</div>	
										
									<div class="row">
                                        <div class="col-md-12">
                                            <div class="form-group">
                                                <label>Blood Group</label>
                                                <select class="form-control">
													<option value="">-Select Blood Group-</option>
													<option value="A-">A- </option>
													<option value="A+">A+ </option>
													<option value="B+">B+ </option>
													<option value="B-">B- </option>
													<option value="O+">O+ </option>
													<option value="O-">O- </option>
													<option value="AB+">AB+ </option>
													<option value="AB-">AB- </option>
												</select>
                                            </div>
                                        </div>
									</div>
									<!--<div class="row">
                                        <div class="col-md-12">
                                            <div class="form-group">
                                                <label>About Me</label>
                                                <textarea rows="5" class="form-control border-input" placeholder="Here can be your description" value="Mike">Oh so, your weak rhyme
                                      You doubt I'll bother, reading into it
                                  I'll probably won't, left to my own devices
                              But that's the difference in our opinions.</textarea>
                                            </div>
                                        </div>
                                    </div> -->
                                    <div class="text-center">
                                        <button type="submit" class="btn btn-info btn-fill btn-wd">Update Profile</button>
                                    </div>
                                    <div class="clearfix"></div>
                                </form>
                            </div>
                        </div>
                    </div>


                </div>
            </div>
        </div>
     </div>
   
</div>
</div>
</div>

</body>

 

</html>
