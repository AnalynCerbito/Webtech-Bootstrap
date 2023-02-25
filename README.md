<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bootstrap Fluid Layout Example</title>
<link rel="stylesheet" href="css/bootstrap.min.css">
<script src="js/bootstrap.bundle.min.js"></script>
</head>
<body style="background-color:rgb(234, 189, 154);">
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <a href="#" class="navbar-brand">Pinoy Recipies</a>
        <button type="button" class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
            <div class="navbar-nav">
                <a href="#" class="nav-item nav-link active">Home</a>
                <a href="#" class="nav-item nav-link">Services</a>
                <a href="#" class="nav-item nav-link">About</a>
                <a href="#" class="nav-item nav-link">Contact</a>
            </div>
            <div class="navbar-nav ms-auto">  
                <a href="#" class="nav-item nav-link">Register</a>            	
                <a href="#" class="nav-item nav-link">Login</a>
            </div>
        </div>
    </div>
</nav> 
<div class="container-fluid">
    <div class="p-3 my-4 bg-light rounded-3">
        <h1 class="text-center text-secondary"> <p><i> Platong Pinoy</i></p></h1>
        <div class="row p-3">
            <div class="col bg-warning tetx-white" style="text-align: justify;">
                Want to know more about Filipino food? Here are 15 traditional dishes to treat yourself as well
                 as more information about Filipino cuisine and what makes it so special.
                The Philippines is home to people who love to celebrate food. Filipino cuisine
                 is an integral part of the culture and Filipinos are some of the most hospitable people in the world.
            </div>
            <div class="col bg-warning tetx-white"  style="text-align: justify;">
                With a myriad of cultural influences incorporated into its food, Philippines 
                boasts many exotic dishes aspart of their cuisine borrowed from Spanish, American, Malaysian and Chinese cultures
                incorporated into the food scene. In this article, we look at a selection of famous food items that you must try from 
                the fabulous Philippines.


            </div>
            <div class="row p-3">
                <div class="col"  style="display: flex;justify-content: center;"></div>
                    <h2 class="text-center text-danger"> Top 3 Most Loved Filipino Food</h2>
                </div>
        </div>
        </div>
        <div class="row">
            <div class="col" style="display: flex;justify-content: center;">
                <img src="food1.jpg" class="img-fluid rounded" alt="Responsive image">
            </div>
            <div class="col" style="display: flex;justify-content: center;">
                <img src="food2.jpg" class="img-fluid rounded" alt="Responsive image">                                                                                                                               
             </div>
            <div class="col" style="display: flex;justify-content: center;">
                <img src="food3.jpg" class="img-fluid rounded" alt="Responsive image">
            </div>
        </div>
    </div>

    <div class="row p-2">
        <div class="col-md-4" style="text-align: justify;">
            <p><em>Adobo Pork Adobo is made with succulent pork belly braised in vinegar, soy sauce, garlic, and onions. 
                A delicious balance of salty and savory, this hearty stew is the Philippines national dish for a good reason!</em></p>
            
        </div>
        <div class="col-md-4" style="text-align: justify;">
            <p><em>Sinigang uses pork as the main ingredient. Other proteins and seafood can also be used. 
                Beef, shrimp, fish are commonly used to cook sinigang. The chicken version, 
                on the other hand, is called sinampalukang manok. </em></p>
        </div>
        <div class="col-md-4" style="text-align: justify;">
            <p><em>This perennial Filipino favorite usually starts with a base of oxtails, beef stew cuts, pork hocks or tripe. 
                Traditionally, the choice meat is simmered for hours to desired tenderness and and along with a 
                variety of vegetables such as banana heart, long beans and eggplant, its pulled together into a stew with ground 
                peanuts for flavor, toasted ground rice for thickening  and annatto for coloring. Because of the dishs very
                 involved cooking process, it is usually reserved for special occasions but by using convenient rice flour and
                  peanut butter, it is simplified enough to be everyday dinner-friendly.</em></p>
        </div>
        
    <hr>
    <footer>
        <div class="row text-secondary">
            <div class="col-md-3">
                <p><h3><em>Platong Pinoy Recipes</em></h3></p>
            </div>
            <div class="col-md-6 text-md-end">
                <a href="#" class="text-dark">Terms of Use</a> 
                <span class="text-muted mx-2">|</span> 
                <a href="#" class="text-dark">Privacy Policy</a>
            </div>
        </div>

        <div class="container px-4 py-2 mx-auto">
            <div class="row">
                <div class="d-flex flex-xlg-row flex-column-reverse">
                    <div class="card card3">
                        <div class="row justify-content-center my-auto">
                            <div class="col-md-8 col-10 my-5 bg-warning">
                                <div class="row justify-content-center px-3 mb-3">
                            
                                </div>
                                <h3 class="mb-5 text-center heading text-secondary"><p><i>Platong Pinoy</i></p></Platong></h3>
        
                                <h6 class="msg-info">Please login to your account</h6>
        
                                <div class="form-group">
                                    <label class="form-control-label text-muted">Username</label>
                                    <input type="text" id="email" name="email" placeholder="Phone no or email id" class="form-control">
                                </div>
        
                                <div class="form-group">
                                    <label class="form-control-label text-muted">Password</label>
                                    <input type="password" id="psw" name="psw" placeholder="Password" class="form-control">
                                </div>
        
                                <div class="row justify-content-center my-3 px-3">
                                    <button class="btn-block btn-color">Login to Platong Pinoy</button>
                                </div>
        
                                <div class="row justify-content-center my-2">
                                    <a href="#"><small class="text-muted">Forgot Password?</small></a>
                                </div>
                            </div>
                        </div>
                        <div class="bottom text-center mb-2">
                            <p href="#" class="sm-text mx-auto mb-3">Don't have an account?<button class="btn btn-white ml-2">Create new</button></p>
                        </div>
                    </div>
                    <div class="card text-center">
                        <div class="card-header">Featured</div>
                        <div class="card-body">
                            <h5 class="card-title">PLATONG PINOY</h5>
                            <p class="card-text">Philippine cuisine is distinguished by its bold combination of sweet, sour, and salty flavors.Other Asian cuisines may be known for a more subtle delivery and presentation, Filipino cuisine is often delivered all at once in a single presentation.</p>
                            <a href="#" class="btn btn-primary">Know more</a>
                        </div>
                        <div class="card-footer text-muted">Register now for more exciting Filipino Recipes</div>
                    </div>
                    
                    </div>
                </div>
            </div>
            <ul class="list-inline">
                <li class="list-inline-item">Home</li>
                <li class="list-inline-item">Products</li>
                <li class="list-inline-item">About Us</li>
                <li class="list-inline-item">Contact</li>
            </ul>
        </div>
    </footer>
</div>
</body>
</html>
