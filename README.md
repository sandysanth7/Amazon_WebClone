# Amazon_WebClone

### HTML

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Amazon online shopping Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>

    <div class="topbar py-2">
        <div class="container-fluid d-flex align-items-center justify-content-between">
            <div class="d-flex align-items-center">
                <img src="https://tse2.mm.bing.net/th?id=OIP.cs6rsE5Ogsa4Hm_2Y6hiPwHaEK&pid=Api&P=0&h=180" alt="Amazon" height="30" />
                <div class="ms-3">
                    <small>Delivering to Chennai 600001</small><br>
                    <a href="#" class="text-white text-decoration-underline">Update location</a>
                </div>
            </div>

            <div class="input-group w-50 search-box">
                <button class="btn btn-light dropdown-toggle" type="button">All</button>
                <input type="text" class="form-control" placeholder="Search Amazon.in">
                <button class="btn btn-warning" type="button"><i class="bi bi-search"></i></button>
            </div>


            <div class="d-flex align-items-center">
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        <img src="https://flagcdn.com/in.svg" width="20" class="me-2">
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">English</a></li>
                        <li><a class="dropdown-item" href="#">Tamil</a></li>
                        <li><a class="dropdown-item" href="#">Telengu</a></li>

                    </ul>
                </li>

                <div class="me-4">
                    <small>Hello, sign in</small><br>
                    <strong>Account & Lists</strong>
                </div>
                <div class="me-4">
                    <small>Returns</small><br>
                    <strong>& Orders</strong>
                </div>
                <div>
                    <i class="bi bi-cart4 fs-4"></i><span class="ms-1">Cart</span>
                </div>
            </div>
        </div>
    </div>


    <div class="navbar-bottom py-2">
        <div class="container-fluid d-flex flex-wrap">
            <a href="#"><i class="bi bi-list"></i> All</a>
            <a href="#Fresh">Fresh</a>
            <a href="#MXPlayer">MX Player</a>
            <a href="#Sell">Sell</a>
            <a href="#aBestsellers">Bestsellers</a>
            <a href="#Mobiles">Mobiles</a>
            <a href="#Todaydeals">Today's Deals</a>
            <a href="#Prime">Prime</a>
            <a href="#Customer">Customer Service</a>
            <a href="#New releases">New Releases</a>
            <a href="#Electronics">Electronics</a>


        </div>
    </div>


    <div class="container-fluid  budget-banner  mb-4 d-flex flex-row justify-content-between">
        <h2>STARTING ₹99<br><small class="text-muted">Budget store</small></h2>
        <p>Top Brands | Wide Selection</p>
        <img src="https://economictimes.indiatimes.com/photo/msid-110364211,imgsize-21118/amazon-sale-on-budget-store-home-essentials-starting-at-just-rs-99.jpg" class="img-fluid" alt="Budget Store" style="max-height: 300px;">
    </div>

    <div class="Bottom-container">
        <div class="row g-4">
            <div class="col-md-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Appliances for your home | Up to 55% off</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG15/Irfan/GATEWAY/MSO/Appliances-QC-PC-186x116--B08RDL6H79._SY116_CB667322346_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG15/Irfan/GATEWAY/MSO/Appliances-QC-PC-186x116--B08345R1ZW._SY116_CB667322346_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG15/Irfan/GATEWAY/MSO/Appliances-QC-PC-186x116--B07G5J5FYP._SY116_CB667322346_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG15/Irfan/GATEWAY/MSO/186x116---wm._SY116_CB667322346_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">See more</a>
                    </div>
                </div>
            </div>

            <div class="col-md-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Revamp your home in style</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG20/Home/2024/Gateway/BTFGW/PCQC/New/1x/final/186x116_Home_furnishings_2._SY116_CB555624324_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG20/Home/2024/Gateway/BTFGW/PCQC/New/1x/final/186x116_Home_decor_1._SY116_CB555624324_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG20/Home/2024/Gateway/BTFGW/PCQC/New/1x/final/186x116_Home_storage_1._SY116_CB555624324_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/IMG20/Home/2024/Gateway/BTFGW/PCQC/New/1x/final/186x116_Home_lighting_2._SY116_CB555624324_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">Explore all</a>
                    </div>
                </div>
            </div>

            <div class="col-md-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Starting ₹149 | Headphones</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/june/CE/GW/QC/PC/PC_QuadCard_boAt_0.5x._SY116_CB553870684_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/june/CE/GW/QC/PC/PC_QuadCard_Boult_0.5x._SY116_CB553870684_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/june/CE/GW/QC/PC/PC_QuadCard_Noise_0.5x._SY116_CB553870684_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/june/CE/MSO/PD3/PC_QuadCard_Zeb_0.5x_1._SY116_CB570220221_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">See all offers</a>
                    </div>
                </div>
            </div>

            <div class="col-md-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Automotive essentials | Up to 60% off</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img17/Auto/2020/GW/PCQC/Glasscare1X._SY116_CB410830553_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img17/Auto/2020/GW/PCQC/Rim_tyrecare1x._SY116_CB410830552_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img17/Auto/2020/GW/PCQC/Vega_helmet_186x116._SY116_CB405090404_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img17/Auto/2020/GW/PCQC/Vaccum1x._SY116_CB410830552_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">See more</a>
                    </div>
                </div>
            </div>

        </div>
    </div>
    <div class="Bottom-container">
        <div class="row g-4">

            <div class="col-md-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Starting ₹199 | Amazon Brand & more</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img23/PB/March/Bikram/PC_QC_HOME_SIZE_186_2._SY116_CB567468236_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img23/PB/March/Bikram/PC_QC_HOME_SIZE_186_3._SY116_CB567468236_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img23/PB/March/Bikram/PC_QC_HOME_SIZE_186_4._SY116_CB567468236_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img23/PB/March/Bikram/PC_QC_HOME_SIZE_186_1._SY116_CB567468236_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">See more</a>
                    </div>
                </div>

            </div>



            <div class="col-md-sm-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Up to 60% off | Styles for women</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img22/Fashion/Gateway/BAU/BTF-Refresh/May/PC_WF/WF1-186-116._SY116_CB636048992_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img22/Fashion/Gateway/BAU/BTF-Refresh/May/PC_WF/WF2-186-116._SY116_CB636048992_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img22/Fashion/Gateway/BAU/BTF-Refresh/May/PC_WF/WF4-186-116._SY116_CB636048992_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img22/Fashion/Gateway/BAU/BTF-Refresh/May/PC_WF/WF3-186-116._SY116_CB636048992_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">End of season sale</a>
                    </div>
                </div>
            </div>

            <div class="col-md-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Under ₹499 | Deals on home improvement essentials</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img18/HomeImprovement/harsmisc/2025/March/Wipes_low_res_V1._SY116_CB549138744_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img18/HomeImprovement/harsmisc/2025/March/Shower_heads_low_res_V1._SY116_CB549138744_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img18/HomeImprovement/harsmisc/2025/March/Tools_low_res_V1._SY116_CB549138744_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img18/HomeImprovement/harsmisc/2025/March/Wallpapers_low_res_V1._SY116_CB549138744_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">Explore all</a>
                    </div>
                </div>
            </div>

            <div class="col-md-3 col-sm-6">
                <div class="grid-item">
                    <div class="section-title">Min. 40% off | Fun games that spark joy | Amazon brands</div>
                    <div class="row row-cols-2 g-2 mt-2">
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/AmazonBrands/GW_CPB_/QC_CC/Baby_toys/baby/QC_PC_186x116_9._SY116_CB563558900_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/AmazonBrands/GW_CPB_/QC_CC/Baby_toys/toys/QC_PC_186x116_12._SY116_CB541414575_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/AmazonBrands/GW_CPB_/QC_CC/Baby_toys/toys/QC_PC_186x116_13._SY116_CB541414575_.jpg" class="img-fluid"></div>
                        <div class="col"><img src="https://images-eu.ssl-images-amazon.com/images/G/31/img21/AmazonBrands/GW_CPB_/QC_CC/Baby_toys/toys/QC_PC_186x116_16._SY116_CB541411275_.jpg" class="img-fluid"></div>
                        <a href="#" class="see-more">See all offers</a>
                    </div>
                </div>
            </div>

        </div>
    </div>
    <div class="text-center">
        <div class="container">
            <h4 class="fw-bold mb-3">See personalized recommendations</h4>
            <button class="signin-btn">Sign in</button>
            <p class="mt-2">
                New customer? <a href="#" class="text-primary">Start here.</a>
            </p>
        </div>
    </div>

    <div class="footer">

        <div class="container">
            <div class="text-center mb-4">
                <button class="btn btn-secondary">Back to top</button>
            </div>
            <div class="row">
                <div class="col-md-3 col-sm-6 mb-4">
                    <h6>Get to Know Us</h6>
                    <a href="#">About Amazon</a>
                    <a href="#">Careers</a>
                    <a href="#">Press Releases</a>
                    <a href="#">Amazon Science</a>
                </div>
                <div class="col-md-3 col-sm-6 mb-4">
                    <h6>Connect with Us</h6>
                    <a href="#">Facebook</a>
                    <a href="#">Twitter</a>
                    <a href="#">Instagram</a>
                </div>
                <div class="col-md-3 col-sm-6 mb-4">
                    <h6>Make Money with Us</h6>
                    <a href="#">Sell on Amazon</a>
                    <a href="#">Sell under Amazon Accelerator</a>
                    <a href="#">Protect and Build Your Brand</a>
                    <a href="#">Amazon Global Selling</a>
                    <a href="#">Supply to Amazon</a>
                    <a href="#">Become an Affiliate</a>
                    <a href="#">Fulfilment by Amazon</a>
                    <a href="#">Advertise Your Products</a>
                    <a href="#">Amazon Pay on Merchants</a>
                </div>
                <div class="col-md-3 col-sm-6 mb-4">
                    <h6>Let Us Help You</h6>
                    <a href="#">Your Account</a>
                    <a href="#">Returns Centre</a>
                    <a href="#">Recalls and Product Safety Alerts</a>
                    <a href="#">100% Purchase Protection</a>
                    <a href="#">Amazon App Download</a>
                    <a href="#">Help</a>
                </div>
            </div>
            <div class="footer-logo">

            </div>
            <div class="language-select mt-3 py-4 me-4">
                <img src="https://tse2.mm.bing.net/th?id=OIP.cs6rsE5Ogsa4Hm_2Y6hiPwHaEK&pid=Api&P=0&h=180" alt="Amazon" width="100">
                <select>
                    <option>English</option>
                    <option>Tamil</option>
                    <option>Hindi</option>
                    <option>Telungu</option>
                </select>
                <select>
                    <option>India</option>
                </select>
            </div>
        </div>

    </div>
    <footer class="bg-dark text-light py-4">
        <div class="container">
            <div class="row text-center text-md-start">
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">AbeBooks</h6>
                    <p class="mb-0 small">Books, art<br>& collectibles</p>
                </div>
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">Amazon Web Services</h6>
                    <p class="mb-0 small">Scalable Cloud<br>Computing Services</p>
                </div>
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">Audible</h6>
                    <p class="mb-0 small">Download<br>Audio Books</p>
                </div>
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">IMDb</h6>
                    <p class="mb-0 small">Movies, TV<br>& Celebrities</p>
                </div>
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">Shopbop</h6>
                    <p class="mb-0 small">Designer<br>Fashion Brands</p>
                </div>
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">Prime Now</h6>
                    <p class="mb-0 small">2-Hour Delivery<br>on Everyday Items</p>
                </div>
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">Amazon Business</h6>
                    <p class="mb-0 small">Everything For<br>Your Business</p>
                </div>
                <div class="col-6 col-md-2 mb-3">
                    <h6 class="fw-bold">Amazon Prime Music</h6>
                    <p class="mb-0 small">100 million songs, ad-free<br>15 million podcast episodes</p>
                </div>
            </div>

            <hr class="border-secondary">

            <div class="text-center small">
                <a href="#" class="text-light me-3">Conditions of Use & Sale</a>
                <a href="#" class="text-light me-3">Privacy Notice</a>
                <a href="#" class="text-light">Interest-Based Ads</a>
                <p class="mt-2 mb-0">&copy; 1996–2025, Amazon.com, Inc. or its affiliates</p>
            </div>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```

### CSS STYLES

```
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');



.topbar {
    background-color: #131921;
    color: white;
    position: static;
}

.search-box input {
    border: none;
    outline: none;
}

.navbar-bottom {
    background-color: #232f3e;
}

.navbar-bottom a {
    color: white;
    text-decoration: none;
    padding: 0.5rem;
}

.section-title {
    font-weight: bold;
    font-size: 1.2rem;
}

.grid-item {
    background: #fff;
    padding: 1rem;
    border: 1px solid #eee;
    border-radius: 0.5rem;
    height: 100%;
}

.section-title {
    font-weight: bold;
    font-size: 1.2rem;
}

.item-box img {
    width: 100%;
    height: auto;
    object-fit: cover;
}


.budget-banner {

    background: linear-gradient(right, #ffe9d2, #ffdabf);
    padding: 2rem;
}

.budget-banner h2 {
    font-weight: 700;
}

.grid-item {
    background: #fff;
    padding: 1rem;
    border: 1px solid #eee;
    border-radius: 0.5rem;
    height: 100%;
}

.see-more {
    margin-top: 12px;
    color: #007185;
    font-size: 14px;
    text-decoration: none;
    display: inline-block;
}

.footer {
    background-color: #232f3e;
    color: white;
    padding: 40px 20px;
}

.footer a {
    color: #ddd;
    text-decoration: none;
    display: block;
    margin-bottom: 8px;
}

.footer a:hover {
    text-decoration: underline;
}

.footer-logo {
    text-align: center;
    margin-top: 30px;
}

.language-select {
    background-color: #37475a;
    padding: 10px;
    text-align: center;
}

.language-select select {
    background-color: #232f3e;
    color: white;
    border: none;
    padding: 5px 10px;
}

#signin-section {
    padding: 60px 20px;
    background-color: #ffffff;
    border-top: 1px solid #ddd;
    border-bottom: 1px solid #ddd;
}

.signin-btn {
    background-color: #ffd814;
    color: #111;
    font-weight: 500;
    border: none;
    border-radius: 999px;
    padding: 10px 30px;
    margin: 15px 0;

}

.signin-btn:hover {
    background-color: #f7ca00;
}
```
