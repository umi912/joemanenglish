<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Using Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Using Bootstrap 5 JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/js/bootstrap.bundle.min.js"></script>
    <title>JoeMan 九妹英語數位學習網-首頁</title>
    <style>
        .mybgcolor {
            background-image: linear-gradient(to top, #a8edea 0%, #fed6e3 100%);
        }
        .mybgcolor img {
            width: 90%;
        }
        .navbar {
            background-color: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .navbar-brand img {
            height: 30px;
        }
        .carousel-inner img {
            height: 500px;
            object-fit: cover;
        }
        .card {
            margin: 20px 0;
            border: none;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .card-title {
            font-weight: bold;
        }
        .alert {
            font-size: 1.2rem;
            margin-bottom: 0;
        }


        .btn-primary {
            background-image: linear-gradient(to top, #d299c2 0%, #fef9d7 100%);        
        }
        .bg-primary {
            background-image: linear-gradient(to right, #ffffff 0%, #bbc1bf 19%, #57c6e1 42%, #b49fda 79%, #7ac5d8 100%);        
        }
        .rounded {
            border-radius: 10px !important;
        }
        .contact-section {
            padding: 50px 0;
        }
        .contact-section h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .contact-section p {
            font-size: 1.2rem;
        }
  
        .navbar-brand img {
    height: 60px !important; /* 強制設定 */
}


        .carousel-indicators {
            position: absolute;
            bottom: -40px;
            left: 35%;
            transform: translateX(-50%);
        }
    </style>
</head>
<body>


    
    <nav class="navbar navbar-expand-lg navbar-light" style="background-image: linear-gradient(to top, #e3eeff 0%, #e3eeff 99%, #e3eeff 100%);">
        <div class="container-fluid">
            &emsp;<a class="navbar-brand" href="#"><img src="images/logo.png" alt="Logo" style="max-height: 100px;"></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="#" style="color: #304352; font-family: Courier New, monospace;">關於我們</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#" style="color: #304352; font-family: Courier New, monospace;">學習追蹤</a>
                    </li>
                    
                    <li class="nav-item">
                        <a class="nav-link" href="#" style="color: #304352; font-family: Courier New, monospace;">個人檔案</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown1" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false" style="color: #304352; font-family: Courier New, monospace;">課程總覽</a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown1" style="background-image: #e6dee9;">
                            <li><a class="dropdown-item" href="#" style="color: #304352; font-family: Courier New, monospace;">句子練習</a></li>
                            <li><a class="dropdown-item" href="#" style="color: #304352; font-family: Courier New, monospace;">情境演練</a></li>
                            <li><a class="dropdown-item" href="#" style="color: #304352; font-family: Courier New, monospace;">ABC單字練習</a></li>
                        </ul>
                    </li>
                </ul>
                <form class="d-flex" role="search" style="font-family: Arial, sans-serif;">
                    <div style="display: flex; align-items: center; border: 1px solid #fff; border-radius: 5px; overflow: hidden;">
                        <input type="search" id="mySearch" name="q" placeholder="站内搜索..."
                            aria-label="在全站内容中搜索" style="flex: 1; padding: 10px; border: none; outline: none;  color: #fff;">
                        <button type="submit" style="background-color: #2c3e50; border: none; padding: 10px 15px; cursor: pointer;">
                            <span style="font-weight: bold; color: #fff;"><img src="images/search.png" style="width: 21px; "></span>
                        </button>
                    </div>
                </form>
            </div>
        </div>
        
    </nav>
    
    <div class="container mt-4">
        <div class="row">
            <div class="col-12 col-sm-10 p-0 mx-auto">

                 <!-- Carousel -->
                 <div id="demo" class="carousel slide" data-bs-ride="carousel">
                    <!-- Indicators/dots -->
                    <div class="carousel-indicators">
                        <span class="indicator-dot active"><button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button></span>
                        <span class="indicator-dot"><button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button></span>
                        <span class="indicator-dot"><button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button></span>
                        <span class="indicator-dot"><button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button></span>
                        <span class="indicator-dot"><button type="button" data-bs-target="#demo" data-bs-slide-to="4"></button></span>
                        <span class="indicator-dot"><button type="button" data-bs-target="#demo" data-bs-slide-to="5"></button></span>
                        <span class="indicator-dot"><button type="button" data-bs-target="#demo" data-bs-slide-to="6"></button></span>
                        <span class="indicator-dot"><button type="button" data-bs-target="#demo" data-bs-slide-to="7"></button></span>
                    </div>

                    <!-- The slideshow/carousel -->
                    <div class="carousel-inner text-center">
                        <div class="carousel-item active">
                            <img src="images/c0.png"  alt="New York" class="d-block w-100">
                            <div class="carousel-caption">
                                
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/c1.png" class="d-block w-100">
                            <div class="carousel-caption">
                                
                            
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/c2.png" class="d-block w-100">
                            <div class="carousel-caption">
                                
                      
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/c3.png" class="d-block w-100">
                            <div class="carousel-caption">
                                
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/c4.png" class="d-block w-100">
                            <div class="carousel-caption">
                                
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/c5.png" class="d-block w-100">
                            <div class="carousel-caption">
                                
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/c6.png" class="d-block w-100">
                            <div class="carousel-caption">
                                
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/c7.png" class="d-block w-100">
                            <div class="carousel-caption">
                                
                            </div>
                        </div>
                    </div>

                    <!-- Left and right controls/icons -->
                    <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
                        <span class="carousel-control-next-icon"></span>
                    </button>
                </div>
            </div>
      
        </div>
    </div>

    <br>

    <div class="alert alert-success text-center" style="background-image: linear-gradient(to top, #e3eeff 0%, #e3eeff 99%, #e3eeff 100%);" width: 100%; display: flex; justify-content: center;">
        <strong style="color: #333;">狂賀！！！114年度 九妹英語學測滿級分學生破百！！！</strong>
    </div>
    
    
    <div class="container">
        <div class="row">
            <div class="col-12 col-md-4">
                <div class="card">
                    <img class="card-img-top" src="images/lenina1.jpg" alt="Card image">
                    <div class="card-body text-center">
                        <h4 class="card-title">【教師模式】<br> t</h4>
                        <p class="card-text">結合「閱讀指導」與「語音辨識」<br>讓教師高效備課，學生在互動式聽說讀寫中培養自學力，並同步記錄學習歷程。</p>
                        <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                            <font style="font-family: Montserrat; color: #2b122e;"><b>開始體驗</font></b></a>
                    </div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="card">
                    <img class="card-img-top" src="images/lenina2.jpg" alt="Card image">
                    <div class="card-body text-center">
                        <h4 class="card-title">【學習模式】<br>s</h4>
                        <p class="card-text">從基礎開始練習，搭配多元教材融合，學習紀錄給予你最即時的回饋，和朋友一起在學習中挑戰吧！</p>
                        <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-minou-puff-sleeve-embroidery-dresscream/2695/category/206/display/1/" class="btn btn-primary">
                            <font style="font-family: Montserrat; color: #2b122e;"><b>開始體驗</font></b></a>
                    </div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="card">
                    <img class="card-img-top" src="images/lenina3.jpg" alt="Card image">
                    <div class="card-body text-center">
                        <h4 class="card-title">【家長模式】<br>p</h4>
                        <p class="card-text">符合時事的英文主題課程，讓孩子可以提升閱讀素養與整體能力。遠端追蹤功能，讓您隨時隨地查看寶貝學習進度及狀況。</p>
                        <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-sonnet-check-ribbon-bamboo-sleeveless-shirtnavy/2680/category/206/display/1/" class="btn btn-primary">
                            <font style="font-family: Montserrat; color: #2b122e;"><b>開始體驗</font></b></a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="alert alert-success text-center" style="background-image: linear-gradient(to top, #f3e7e9 0%, #e3eeff 99%, #e3eeff 100%);">
        <strong style="color: #333;">當季主打課程！</strong>
    </div>    
    
    
    <div class="row mybgcolor text-center">

        <br>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image" >
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>

                <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-damier-square-neck-flower-dressviolet/2697/category/206/display/1/">

                </a>
            </div>
            </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
              </div>
            </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
            <div class="card">
                <img class="card-img-top" src="images/s1.jpg" alt="Card image">
                <div class="card-body text-center">
                    <h6 class="card-title">小六英語閱讀</h6>
                    <p class="card-text">針對該年齡段學生的新穎文章，搭配精美的彩色插圖。</p>
                    <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-berte-frill-neck-ribbon-ramie-shirtivory/2683/" class="btn btn-primary">
                        <font style="font-family: Montserrat; color: #2b122e;"><b>參加課程</font></b>
                    </a>
                </div>
            </div>
        </div>

            <div class="alert alert-success text-center" style="background-image: linear-gradient(to top, #f3e7e9 0%, #e3eeff 99%, #e3eeff 100%);">
                <strong style="color: #333;">本月銷售人氣排行!</strong>
            </div>    

            <div class="row mybgcolor text-center">
            <br>

            <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
                <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-doha-cotton-half-pantsbeige/2699/">
                <div><img src="images/s13.jpg" class="img-fluid"></a></div>
            </div>
            <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
                <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-fromage-woolen-knit-cardigancream/2689/category/206/display/1/">
                <div><img src="images/s14.jpg" class="img-fluid"></a></div>
            </div>
            <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
                <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-luxie-classic-linen-knit-jacketblack/2690/category/206/display/1/">
                <div><img src="images/s15.jpg" class="img-fluid"></a></div>
            </div>
            <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
                <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-harper-cotton-overall-pantsblue/2700/category/206/display/1/">
                <div><img src="images/s16.jpg" class="img-fluid"></a></div>
            </div>
            <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
                <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-doha-cotton-half-pantsbeige/2699/">
                <div><img src="images/s17.jpg" class="img-fluid"></a></div>
            </div>
            <div class="col-6 col-sm-4 col-md-3 col-lg-2 mb-3">
                <a href="https://lenina.kr/product/%EC%82%AC%EB%82%98-%EC%B0%A9%EC%9A%A9-dazzle-puff-sleeve-embroidery-shirtivory/2682/category/206/display/1/">
                <div><img src="images/s18.jpg" class="img-fluid"></a></div>
            </div>
   


    <div class="mt-4 p-5 bg-primary text-white rounded">
        <h1><font style="font-family: Brush Script MT, Brush Script Std, cursive; color: #ffecd2; font-size: 92px;">Lenina X Sana Summer</font></h1>
        <p><font style="font-family: DejaVu Sans Mono, monospace">AFTER-SALES SERVICE：633-81-00959<br>ADDRESS：7th Floor, Room 701, Yourong Technology Center,No. 144, Achasan-ro,Seongdong-gu, Seoul<br>EMAIL：showroomlaker@gmail.com</font></p>
        <a href="https://www.instagram.com/lenina_seoul?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==">
        <img src="images/ig.png" style="width: 48px; "></a>
        &emsp;
        <a href="https://twitter.com/JYPETWICE">
        <img src="images/x.png" style="width: 48px; "></a>
        &emsp;
        <a href="https://www.youtube.com/@user-df5gu9gq1c">
        <img src="images/yt.png" style="width: 48px; "></a>

    </div>
    </div>
    </div>
</div>
</body>
</html>
