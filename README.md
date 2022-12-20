# Portfolio
Hey this is the Portfolio repository where you can see the source codes
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fayaz ALi Malang</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"/> 
 
 <script>(function(w, d) { w.CollectId = "62c71fbffbae4770654709f5"; var h = d.head || d.getElementsByTagName("head")[0]; var s = d.createElement("script"); s.setAttribute("type", "text/javascript"); s.async=true; s.setAttribute("src", "https://collectcdn.com/launcher.js"); h.appendChild(s); })(window, document);</script>
 
 
 
 
 
 
</head>
<body>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">YA<span>Z.</span></a></div>
        
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About</a></li>
                <!--<li><a href="#services" class="menu-btn">Services</a></li>-->
                <!--<li><a href="#skills" class="menu-btn">Skills</a></li>-->
                <li><a href="#teams" class="menu-btn">Teams</a></li>
                <li><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>

    <!-- home section start -->
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hello, my name is</div>
                <div class="text-2">Fayaz Ali</div>
                <div class="text-3">And I'm a <span class="typing"></span></div>
                <a href="resume.pdf">Download Resume</a>
            </div>
        </div>
    </section>

    <!-- about section start -->
    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About me</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="jaba.jpg" alt="">
                </div>
                <div class="column right">
                    <div class="text">I'm Fayaz  and I'm a <span class="typing-2"></span></div>
                    <p>I am doing my Bachelor in Computer Science in south east European university.I am basically from Pakistan but right now i am studying here in North Macedonia</p>
                    <a href="https://mk.linkedin.com/in/fayaz-ali-b905b9211/de?trk=people-guest_people_search-card">Want to know More</a>
                </div>
            </div>
        </div>
    </section>
  <!-- teams section start -->
    <section class="teams" id="teams">
        <div class="max-width">
            <h2 class="title">My teams</h2>
            <div class="carousel owl-carousel">
               
                        
                
                <div class="card">
                    <div class="box">
                        <img src="WhatsApp Image 2022-08-04 at 6.23.03 PM (1).jpeg" alt="">
                        <div class="text">Hayat Ali shah</div>
                        <p>Hayat ali shah is my senior colleque who is working in frond end developer at some private company.</p>
                    </div>
                </div>
                
                <div class="card">
                    <div class="box">
                        <img src="peer.jpg" alt="">
                        <div class="text">Syed Peerzada</div>
                        <p>we are working in I-solve as full time intern and we are working together in one project</p>
                    </div>
                </div>
                
                 <div class="card">
                    <div class="box">
                        <img src="88.JPG" alt="">
                        <div class="text">Fayaz Ali</div>
                        <p>I am working in I-SOLVE as full time intern and working on with some small projects</p>
                    </div>
                </div>
                
            </div>
        </div>
    </section>

    <!-- contact section start -->
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact me</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Get in Touch</div>
                    <p>if you have any question then get in touch i will be happy to reach you </p>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Fayaz Ali</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">Tetovo, NorthMacedonia</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">fa30576@seeu.edu.mk</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message me</div>
                    <form action="https://formsubmit.co/aca3dff036e922e27cba25a9da65a87c" method="POST">
                    <input type="hidden" name="_captcha" value="false">
                    <input type="hidden" name="_next" value="https://fayazaliseeu.neocities.org/thanks.html">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" id="name" name="name" placeholder="Name" required>
                            </div>
                            <div class="field email">
                                <input type="email"  id="email" name="email" placeholder="Email" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" id="subject" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="field textarea">
                            <textarea cols="30" rows="10" name="message" placeholder="Message.." required></textarea>
                        </div>
                        <div class="_captcha">
                        </div>
                        <div class="button-area">
                            <button type="submit">Send</button>
                            
                            
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- footer section start -->
    <footer>
        <span>Created By <a href="https://fayazaliseeu.neocities.org/">Fayaz Ali</a> | <span class="far fa-copyright"></span> 2022 All rights reserved.</span>
    </footer>

    <script src="script.js"></script>
</body>
</html>
