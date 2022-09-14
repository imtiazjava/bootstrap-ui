# bootstrap-ui

# Landpage of the website in bootstrap without using the grid system
```


------------------------------------------------------------------

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HOME PAGE</title>
    <link rel="stylesheet" href="../css/mycss.css">
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css"
      integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N"
      crossorigin="anonymous"
    />
  </head>
  <body>
     

    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
                <div class="container">
                    <a href="#" class="navbar-brand" style="font-size:30px">CGI</a>
                    <div class="collapse navbar-collapse">
                        <ul class="navbar-nav">
                            <li class="nav-item">
                                <a href="#" class="nav-link">HOME</a>
                            </li>
                            <li class="nav-item">
                                <a href="#" class="nav-link">SERVICE</a>
                            </li>
                            <li class="nav-item">
                                <a href="#" class="nav-link">ABOUTUS</a>
                            </li>
                            <li class="nav-item">
                                <a href="#" class="nav-link">LOGIN</a>
                            </li>
                            
                        
                        </ul>


                    </div>




                </div>


        
    </nav>

   <hr>

   <div class="myform">
                <form action="">
                        <div class="form-group">
                                 <input type="text" class="form-control w-50" id="pid" placeholder="ENTER PID">
                        </div>
                        
                        <div class="form-group">
                            <input type="text" class="form-control w-50" id="pname" placeholder="ENTER PNAME">
                        </div>
                        
                        <div class="form-group">
                            
                            <input type="text" class="form-control w-50" id="price" placeholder="ENTER PRICE">
                        </div>
                    
                        <button class="btn btn-success" style="width:470px">STORE</button>


                </form>


   </div>

   <hr>
   
   <div class="card d-inline-block ml-5" style="width:400px;">
    <img src="../images/1.png" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">The rise of AI Professionals in India</h5>
      <p class="card-text">There are two points in the evolution of any industry. First is the tipping point where it breaks off from a flat curve and embraces explosive growth due to direct or indirect factors. Second is a turning point that changes the direction of that industry per se.</p>
      <a href="https://talentsprint.com/blog/xp/the-rise-of-ai-professionals-in-india/" target="_blank" class="btn btn-primary">READ MORE...</a>
    </div>
  </div>
      
  <div class="card d-inline-block ml-4" style="width:400px;">
    <img src="../images/2.png" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">The rise of AI Professionals in India</h5>
      <p class="card-text">There are two points in the evolution of any industry. First is the tipping point where it breaks off from a flat curve and embraces explosive growth due to direct or indirect factors. Second is a turning point that changes the direction of that industry per se.</p>
      <a href="https://talentsprint.com/blog/xp/the-rise-of-ai-professionals-in-india/" target="_blank" class="btn btn-primary">READ MORE...</a>
    </div>
  </div>
   

  <div class="card d-inline-block ml-5" style="width:400px;">
    <img src="../images/3.png" class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">The rise of AI Professionals in India</h5>
      <p class="card-text">There are two points in the evolution of any industry. First is the tipping point where it breaks off from a flat curve and embraces explosive growth due to direct or indirect factors. Second is a turning point that changes the direction of that industry per se.</p>
      <a href="https://talentsprint.com/blog/xp/the-rise-of-ai-professionals-in-india/" target="_blank" class="btn btn-primary">READ MORE...</a>
    </div>
  </div>
   


  <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
    <div class="container">
        <p class="display-4" style="color:white"> copywrite-2022</p>
    </div>



</nav>

    <script
      src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
      integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.min.js"
      integrity="sha384-+sLIOodYLS7CIrQpBjl+C7nPvqq+FbNUBDunl/OZv93DB7Ln/533i8e/mZXLi/P+"
      crossorigin="anonymous"
    ></script>
  </body>
</html>

```

# Landpage of the website with bootstrap, Grid system:

------------------------------------------------------
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HOME PAGE</title>
    <link rel="stylesheet" href="../css/mycss.css">
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css"
      integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <div class="container">
        <div class="row">
          <div class="col-sm">

                <!-- navigation bar-->
                <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
                    <div class="container">
                        <a href="#" class="navbar-brand" style="font-size:30px">CGI</a>
                        <div class="collapse navbar-collapse">
                            <ul class="navbar-nav">
                                <li class="nav-item">
                                    <a href="#" class="nav-link">HOME</a>
                                </li>
                                <li class="nav-item">
                                    <a href="#" class="nav-link">SERVICE</a>
                                </li>
                                <li class="nav-item">
                                    <a href="#" class="nav-link">ABOUTUS</a>
                                </li>
                                <li class="nav-item">
                                    <a href="#" class="nav-link">LOGIN</a>
                                </li>
                                
                            
                            </ul>
    
    
                        </div>
    
    
    
    
                    </div>
    
    
            
        </nav>


          </div><!--close col-12 -->
           
        </div><!--close 1st row-->


        <div class="row mt-5">
                <div class="col-12-lg">
                  <div id="carouselExampleFade" class="carousel slide carousel-fade" data-ride="carousel">
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="../images/1.png"  alt="...">
                      </div>
                      <div class="carousel-item">
                        <img src="../images/2.png"  alt="...">
                      </div>
                      <div class="carousel-item">
                        <img src="../images/3.png"  alt="...">
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-target="#carouselExampleFade" data-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="sr-only">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-target="#carouselExampleFade" data-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="sr-only">Next</span>
                    </button>
                  </div>

                </div>


        </div><!--2nd row close-->

        <div class="row mt-5">
                <div class="col-lg-4 " class="d1">
                  <div class="card" style="width: 22rem;">
                    <img src="../images/2.png" class="card-img-top" alt="still loading..">
                    <div class="card-body">
                      <h5 class="card-title">Java</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      <a href="#" class="btn btn-primary">READ MORE</a>
                    </div>
                  </div>

                </div>
                <div class="col-lg-4 " class="d1">
                  <div class="card" style="width: 22rem;">
                    <img src="../images/1.png" class="card-img-top" alt="still loading..">
                    <div class="card-body">
                      <h5 class="card-title">Java</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      <a href="#" class="btn btn-primary">READ MORE</a>
                    </div>
                  </div>

                </div>

                <div class="col-lg-4 " class="d1">
                  <div class="card" style="width: 22rem;">
                    <img src="../images/3.png" class="card-img-top" alt="still loading..">
                    <div class="card-body">
                      <h5 class="card-title">Java</h5>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      <a href="#" class="btn btn-primary">READ MORE</a>
                    </div>
                  </div>

                </div>

        </div><!--3rd row close-->

        <div class="row mt-5">
              <div class="col-12">
                <table class="table table-success">
                  <thead>
                    <tr>
                      <th scope="col">#</th>
                      <th scope="col">PID</th>
                      <th scope="col">PNAME</th>
                      <th scope="col">PRICE</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th scope="row">1</th>
                      <td>1001</td>
                      <td>MOBILE</td>
                      <td>15000</td>
                    </tr>
                    <tr>
                      <th scope="row">2</th>
                      <td>1002</td>
                      <td>SMART WATCH</td>
                      <td>5000</td>
                    </tr>
                    <tr>
                      <th scope="row">3</th>
                      <td>1003</td>
                      <td>LAPTOP</td>
                      <td>75000</td>
                    </tr>
                  </tbody>
                </table>

              </div>

        </div>
        
        
        <div class="row mt-5">
                <div class="col-lg-12" class="d2">
                      <footer>
                            @copywrite-2022-CGI-BATCH2-PROJECT
                      </footer>

                </div>
        </div><!--close 5th row-->



      </div><!--close container-->




    <script
      src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
      integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.min.js"
      integrity="sha384-+sLIOodYLS7CIrQpBjl+C7nPvqq+FbNUBDunl/OZv93DB7Ln/533i8e/mZXLi/P+"
      crossorigin="anonymous"
    ></script>
  </body>
</html>


----------------------------------------------------------------------------------------------------------------
mycss.css
---------
img{
    width:1110px;
    height:450px;
    margin-left:10px;
}

.card .card-img-top{
    width:330px;
    height:250px;
    margin-top:10px;

}
.card-body .card-text
{
    width:20rem;
}

footer{
    background-color: black;
    color:white;
    font-size:30px;
    text-align: center;
}



```
