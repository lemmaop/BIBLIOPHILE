# BIBLIOPHILE Online E-Book Website
HTML Code!!!!
    <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Bibliophile</title>

        <link rel="stylesheet" href="https://unpkg.com/swiper@7/swiper-bundle.min.css" />

        <!-- font awesome cdn link  -->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

        <!-- custom css file link  -->
        <link rel="stylesheet" href="style.css">

        <link rel="apple-touch-icon" sizes="180x180" href="favicon_io/apple-touch-icon.png">
        <link rel="icon" type="image/png" sizes="32x32" href="favicon_io/favicon-32x32.png">
        <link rel="icon" type="image/png" sizes="16x16" href="favicon_io/favicon-16x16.png">
        <link rel="manifest" href="favicon_io/site.webmanifest">
    </head>

    <body>

        <!-- header section starts  -->

        <header class="header">

            <div class="header-1">

                <a href="#" class="logo"> <i class="fas fa-book"></i> Bibliophile </a>

                <form action="" class="search-form">
                    
                    <input type="search" name="" placeholder="search here..." id="search-box">
                    <label for="search-box" class="fas fa-search"></label>
                </form>

                <div class="icons">
                    <div id="search-btn" class="fas fa-search"></div>
                    <a href="cart.html" class="fas fa-shopping-cart"></a>
                    <div id="login-btn" class="fas fa-user"></div>
                </div>

            </div>

            <div class="header-2">
                <nav class="navbar">
                    <a href="book.html">home</a>
                    <a href="">featured</a>
                    <a href="#">category</a>
                    <a href="#reviews">reviews</a>
                    <a href="feedback.html">feedback</a>
                </nav>
            </div>

        </header>

        <!-- header section ends -->

        <!-- bottom navbar  -->

        <nav class="bottom-navbar">
            <a href="#home" class="fas fa-home"></a>
            <a href="#featured" class="fas fa-list"></a>
            <a href="#arrivals" class="fas fa-tags"></a>
            <a href="#reviews" class="fas fa-comments"></a>
            <a href="#feedback" class="fas fa-feedback"></a>
        </nav>

        <!-- login form  -->

        <div class="login-form-container">

            <div id="close-login-btn" class="fas fa-times"></div>

            <form action="" id="login-form">
                <h3>login</h3>
                <span>username</span>
                <input type="email" name="" class="box" placeholder="enter your email" id="">
                <span>password</span>
                <input type="password" name="" class="box" placeholder="enter your password" id="">
                <div class="checkbox">
                    <input type="checkbox" name="" id="remember-me">
                    <label for="remember-me"> remember me</label>
                </div>
                <input type="submit" value="login" class="btn">
                <p>forget password ? <a href="sign.html">click here</a></p>
                <p>don't have an account ? <a href="sign.html">create one</a></p>
            </form>

        </div>

        <!-- home section starts  -->

        <section class="home" id="home">

            <div class="row">

                <div class="content">
                    <h3>New Arrivals</h3>
                    <p>There is no friend as loyal as books</p>
                    <a href="#" class="btn">shop now</a>
                </div>

                <div class="swiper books-slider">
                    <div class="swiper-wrapper">
                        <a href="#" class="swiper-slide"><img
                                src="book-1.png"
                                alt=""></a>
                        <a href="#" class="swiper-slide"><img
                                src="book-10.png"
                                alt=""></a>
                        <a href="#" class="swiper-slide"><img
                                src="book-2.png"
                                alt=""></a>
                        <a href="#" class="swiper-slide"><img
                                src="book-4.png"
                                alt=""></a>
                        <a href="#" class="swiper-slide"><img
                                src="discount-book-2.png"
                                alt=""></a>
                        <a href="#" class="swiper-slide"><img
                                src="book-5.png"
                                alt=""></a>
                    </div>
                    <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/stand.png"
                        class="stand" alt="">
                </div>

            </div>

        </section>

        <!-- home section ense  -->

        <!-- icons section starts  -->

        <section class="icons-container">

            <div class="icons">
                <i class="fas fa-shipping-fast"></i>
                <div class="content">
                    <h3>free shipping</h3>
                    <p>order over ₹500</p>
                </div>
            </div>

            <div class="icons">
                <i class="fas fa-lock"></i>
                <div class="content">
                    <h3>secure payment</h3>
                    <p>100 secure payment</p>
                </div>
            </div>

            <div class="icons">
                <i class="fas fa-redo-alt"></i>
                <div class="content">
                    <h3>easy returns</h3>
                    <p>10 days returns</p>
                </div>
            </div>

            <div class="icons">
                <i class="fas fa-headset"></i>
                <div class="content">
                    <h3>24/7 support</h3>
                    <p>call us anytime</p>
                </div>
            </div>

        </section>

        <!-- icons section ends -->

        <!-- featured section starts  -->

        <section class="featured" id="featured">

            <h1 class="heading"> <span>featured books</span> </h1>

            <div class="swiper featured-slider">

                <div class="swiper-wrapper">

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <a href="./product.html"> <img src="discount-book-2.png" alt=""> </a>
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹650 <span>$₹750</span></div>
                            <a href="#" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <a href="./product.html"> <img
                                    src="book-1.png"
                                    alt=""> </a>
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹700 <span>₹600</span></div>
                            <a href="#" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <a href="product.html"><img
                                    src="book-2.png"
                                    alt=""> </a>
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹800 <span>₹1000</span></div>
                            <a href="#" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <img src="book-5.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹600 <span>₹700</span></div>
                            <a href="#" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <img src="book-3.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹550 <span>₹600</span></div>
                            <a href="#" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <img src="book-4.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹600 <span>₹1200</span></div>
                            <a href="" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <img src="book-6.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹600 <span>₹500</span></div>
                            <a href="" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <img src="book-7.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹600 <span>₹700</span></div>
                            <a href="#" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <img src="book-8.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹800 <span>₹750</span></div>
                            <a href="" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <div class="icons">
                            <a href="#" class="fas fa-search"></a>
                            <a href="#" class="fas fa-eye"></a>
                        </div>
                        <div class="image">
                            <img src="book-9.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>featured books</h3>
                            <div class="price">₹550 <span>₹1200</span></div>
                            <a href="" class="btn add-to-cart">add to cart</a>
                        </div>
                    </div>

                </div>

                <div class="swiper-button-next"></div>
                <div class="swiper-button-prev"></div>

            </div>

        </section>

        <!-- featured section ends -->

        <!-- newsletter section starts -->

        <section class="newsletter">

            <form action="">
                <h3>subscribe for latest updates</h3>
                <input type="email" name="" placeholder="enter your email" id="" class="box">
                <input type="submit" value="subscribe" class="btn" class="sub" id="subscribe-btn">
            </form>

        </section>

        <!-- newsletter section ends -->

        <!-- category section starts  -->

        <section class="arrivals" id="arrivals">

            <h1 class="heading"> <span>Category</span> </h1>

            <div class="swiper arrivals-slider">

                <div class="swiper-wrapper">

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book-1.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 1</h3>
                        </div>
                    </a>

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book-4.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 2</h3>
                        </div>
                    </a>

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book-6.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 3</h3>
                        </div>
                    </a>

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book-7.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 4</h3>
                        </div>
                    </a>

                </div>

            </div>

            <div class="swiper arrivals-slider">

                <div class="swiper-wrapper">

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book-8.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 5</h3>
                        </div>
                    </a>

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book-9.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 6</h3>
                        </div>
                    </a>

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book-10.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 7</h3>
                        </div>
                    </a>

                    <a href="#" class="swiper-slide box">
                        <div class="image">
                            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/book3.png"
                                alt="">
                        </div>
                        <div class="content">
                            <h3>Semester 8</h3>
                        </div>
                    </a>

                </div>

            </div>

        </section>

        <!-- category section ends -->

        <!-- deal section starts  -->

        <section class="deal">

            <div class="content">
                <h3>deal of the day</h3>
                <h1>upto 50% off</h1>
                <p>Checkout before this deal expires at midnight.</p>
                <a href="#" class="btn">shop now</a>
            </div>

        </section>
        <!-- deal section ends -->
    <!-- about us section starts -->

    <section class="about-us" id="about-us">
        <h1 class="heading"> <span>AboutUs</span> </h1>
    
        <img src="Lovepik_com-380609421-old-man-reading-a-book-cartoon-illustration-vector-clipart-book-illustrations-revising.png" alt="About Us Image">
        <div class="content">
            <p>Welcome to Bibliophile - your ultimate destination for all things book-related! At Bibliophile, we are passionate about spreading the love for reading and providing book enthusiasts with a diverse range of literary experiences.</p>
            <p>Our journey began with a simple mission: to connect readers with their next great read, whether it's a gripping novel, an enlightening non-fiction book, or a helpful academic resource. With a carefully curated selection of books from various genres and authors, we strive to cater to the diverse tastes and preferences of our valued customers.</p>
            <p>Driven by our commitment to excellence, we not only offer an extensive collection of books but also provide exceptional customer service, ensuring a seamless and enjoyable shopping experience for every visitor to our website.</p>
            <p>As avid readers ourselves, we understand the transformative power of books and their ability to inspire, educate, and entertain. That's why we're dedicated to promoting literacy and fostering a vibrant reading culture in communities around the world.</p>
            <p>Join us on this literary journey and let Bibliophile be your trusted companion in exploring the wonderful world of books!</p>
        </div>
    </section>
        <!-- reviews section starts  -->

        <section class="reviews" id="reviews">

            <h1 class="heading"> <span>client's reviews</span> </h1>

            <div class="swiper reviews-slider">

                <div class="swiper-wrapper">

                    <div class="swiper-slide box">
                        <img src="IMG_E0511.JPG"
                            alt="">
                        <h3>Mehra</h3>
                        <p>First of all it customer service is excellent. We get all author book for Mumbai University.
                            People should try here affordable and best price.</p>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <img src="IMG_0250.JPG"
                            alt="">
                        <h3>Vaibhav</h3>
                        <p>Best book store almost all books are available for prepartion of exam related or other books are
                            available on reaonable price also.</p>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <img src="IMG-20220704-WA0030.jpg"
                            alt="">
                        <h3>Bharti</h3>
                        <p>Customer Service is good. Greetings to customer and making the required Books available to
                            Customers is very good.</p>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>
                    <div class="swiper-slide box">
                        <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/pic-4.png"
                            alt="">
                        <h3>Pooja </h3>
                        <p>This book centre have large amount of a books. The engineering study material all semester books
                            are available.then the peacefull and nice book centre.</p>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <img src="IMG20200312150604.jpg"
                            alt="">
                        <h3>Muskan</h3>
                        <p>I migrated to the online platform on Just books because I was finding it difficult to go to their
                            libraries before closing time.</p>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>

                    <div class="swiper-slide box">
                        <img src="IMG_E0353.JPG"
                            alt="">
                        <h3>Anshita</h3>
                        <p>I love the product because it is very easy to find. The book are in really organized manner you
                            can easily find the book you want.</p>
                        <div class="stars">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                    </div>

                </div>

            </div>

        </section>

        <!-- reviews section ends -->

        <!-- feedback section starts  -->

        <section class="blogs" id="blogs">

            <h1 class="heading"> <span>feedback</span> </h1>

            <section class="newsletter">

                <form action="">
                    <h3>give your feedback here...</h3>
                    <a href="./feedback.html" class="btn">Feedback</a>
                    <!-- <a href="./feedback.html"><input type="submit" value="feedback"> -->
                    </a>
                </form>

            </section>
        </section>

        <!-- feedback section ends -->
       <!-- Feature your stories starts -->
<section class="feature-stories" id="feature-stories">
    <h1 class="heading"> <span>Feature Your Stories</span> </h1>
    <p>Do you have an interesting story to share with the world? We'd love to feature it on Bibliophile! Whether it's a personal experience, a fictional tale, or a thought-provoking essay, we welcome submissions from all genres and perspectives.
    Submit your story using the form below, and our team will review it for potential publication on our website. Join us in spreading the joy of storytelling and inspiring readers around the globe!</p>
    <form action="#" class="story-form">
        <br>
        <label for="story-title">Story Title:</label><br>
        <input type="text" id="story-title" name="story-title" required><br>
        <label for="author-name">Your Name:</label><br>
        <input type="text" id="author-name" name="author-name" required><br>
        <label for="story-content">Your Story:</label><br>
        <textarea id="story-content" name="story-content" rows="5" required></textarea><br>
        <button type="submit">Submit</button>
    </form>
</section>
<!-- Feature your stories ends -->
        <!-- footer section starts  -->

        <section class="footer">

            <div class="box-container">

                <div class="box">
                    <h3>our locations</h3>
                    <a href="#"> <i class="fas fa-map-marker-alt"></i> india </a>
                    <a href="#"> <i class="fas fa-map-marker-alt"></i> USA </a>
                </div>

                <div class="box">
                    <h3>quick links</h3>
                    <a href="./index.html"> <i class="fas fa-arrow-right"></i> home </a>
                    <a href="#"> <i class="fas fa-arrow-right"></i> featured </a>
                    <a href="#"> <i class="fas fa-arrow-right"></i> Category </a>
                    <a href="#"> <i class="fas fa-arrow-right"></i> reviews </a>
                    <a href="./feedback.html"> <i class="fas fa-arrow-right"></i> feedback </a>
                </div>

                <div class="box">
                    <h3>extra links</h3>
                    <a href="#"> <i class="fas fa-arrow-right"></i> account info </a>
                    <a href="#"> <i class="fas fa-arrow-right"></i> ordered items </a>
                    <a href="#"> <i class="fas fa-arrow-right"></i> privacy policy </a>
                    <a href="#"> <i class="fas fa-arrow-right"></i> payment method </a>
                    <a href="#"> <i class="fas fa-arrow-right"></i> our serivces </a>
                </div>

                <div class="box">
                    <h3>contact info</h3>
                    <a href="#"> <i class="fas fa-phone"></i> 6280478697 </a>
                    <a href="#"> <i class="fas fa-phone"></i> 8627832748 </a>
                    <a href="#"> <i class="fas fa-envelope"></i> bibliophile2024@gmail.com </a>
                    <a href="#"> <i class="fas fa-envelope"></i> teambiblio2024@gmail.com </a>
                    <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/worldmap.png"
                        class="map" alt="">
                </div>

            </div>

            <div class="share">
                <a href="#" class="fab fa-facebook-f"></a>
                <a href="" class="fab fa-twitter"></a>
                <a href="" class="fab fa-instagram"></a>
                <a href="" class="fab fa-linkedin"></a>
                <a href="" class="fab fa-linkedin"></a>
            </div>

            <div class="credit"> created by <span>Team Bibliophile </span>copyright ©2022 all rights reserved! </div>

        </section>

        <!-- footer section ends -->

        <!-- loader  -->

        <div class="loader-container">
            <img src="https://raw.githubusercontent.com/KordePriyanka/Books4MU-Book-Store-Website-/main/image/loader-img.gif"
                alt="">
        </div>


        <script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>

        <!-- custom js file link  -->
        <script src="script.js"></script>

    </body>

    </html>
