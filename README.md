# MY-PORTFOLIO

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Anubhav Personal Portfolio</title>
    <link rel="stylesheet" href="style.css"/>
    <link rel="stylesheet" href="responsive.css">
    <!-- font-awesome cdn link -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer"/>
    <!-- Remix icon CDN -->
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css" rel="stylesheet"/>
    <link rel="shortcut icon" href="image/Favicon.jpg" type="image/x-icon">
  </head>
  <body>
    <!-- Start Header Section -->
    <div class="header" id="home">
        <div class="header-container">
            <nav>
                <div class="logo"><i class="fa-solid fa-mug-hot"></i> Anubhav</div>
                <ul id="menu">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skill">Skills</a></li>
                    <li><a href="#education-sec">Education</a></li>
                    <li><a href="#project">Projects</a></li>
                    <li><a href="#contact">Contact</a></li> 
                    <i class="" id="closeMenu"></i>
                </ul>
                <i class="" id="openMenu"></i>
            </nav>

            <div class="hero-section">
                <div class="left-content">
                    <h1>Hi There, <br>I'm <span>Anubhav Kumar Yaduvanshi</span></h1>
                    <p>I'm a Programmer<span id="auto-type"></span></p>

                    <ul class="social-media">
                       
                        <li><a href="https://www.instagram.com/wishmaster_anubhav007/" target="_blank"><i class="fa-brands fa-instagram"></i></a></li>

                        <li><a href="www.linkedin.com/in/anubhav-yaduvanshi-237b7229b" target="_blank"><i class="fa-brands fa-linkedin-in"></i></a></li>
                        
                    </ul>
                </div>
                
                <div class="card-content">
                    <img src="img.jpg">
                </div>
            </div>
        </div>
    </div>
    <!-- End Header Section -->


    <!-- Start About Section -->
    <div id="about">
        <div class="about-container">
            <h1 class="sub-title"><i class=""></i> About Me</h1>
            <div class="row">
                <div class="about-card">
                    <img src="img2.jpg">
                </div>
    
                <div id="right-about-sec">

                    <p class="info">Hi There! I am Anubhav Kumar Yaduvanshi, a third-year Bachelor of Computer Applications (BCA) student specializing in Data Science & Artificial Intelligence at Babu Banarasi Das University. With a deep fascination for coding , programming , and cutting-edge technologies, I am on the mission to transform data into intelligent solution and explore the limitless possibilities of AI . I am eager to dive deep into the world of programming and software development. My journey in the realm of technology has just begun, but my enthusiasm for learning and growing in this field is boundless. My journey revolves around problem-solving , innovation , and continuous learning .</p>

                    <div class="tab-titles">
                        <p class="tab-links"  onclick="opentab('motivation')">Motivation</p>
                    </div>

                    <div class=tab-contents" id="Motivation">
                        <ul>
                            <li><span>The more you code , The more you learn ,The more you learn , The better you code.</span><br></li>
                        </ul>
                    </div>

                </div>
            </div>
        </div>
    </div>
    <!-- End About Section -->


    <!-- Start Skills Section -->
    <div id="skill">
        <div class="skill-container">
            <h1><i class="fa-solid fa-ghost"></i> My Skill's</h1>
            <div class="innerSkill-content">
                <div class="box">
                    <img src="JavaScript.png">
                    <p>JavaScript</p>
                </div>
    
                <div class="box">
                    <img src="html.png">
                    <p>HTML5</p>
                </div>
    
                <div class="box">
                    <img src="CSS.png">
                    <p>CSS3</p>
                </div>
                <div class="box">
                    <img src="MySQL.png">
                    <p>MySQL</p>
                </div>
    
                <div class="box">
                    <img src="Python.png">
                    <p>Python</p>
                </div>
                <div class= "box">
                    <img src="prompt engineer.jpg" alt="">
                </div>
                <DIV class="BOX">
                    <img src="power BI.png" alt="">
                </DIV>
            </div>
        </div>
    </div>
    <!-- End Skills Section -->

    <!-- Start Education section -->
    <div id="education-sec">
        <div class="education-container">
            <div class="edu-head">
                <h1><i class="fa-solid fa-graduation-cap"></i> My Education</h1>
                <p>The beautiful thing about learning is that no one can take it away from you.</p>
            </div>

            <div class="college-card">
                <img src="bbdu.jpg">
                <div class="college-info">
                    <h1>Bachelor of Computer Application - DS & AI</h1>
                    <p>Babu Banarasi Das University - Lucknow</p>
                    <p class="sec-p">2023 - 2026| Pursuing</p>
                </div>
            </div>
        </div>
    </div>
    <!-- End Education Section -->

    <!-- Start Project Section -->
    <div id="project">
        <div class="project-container">
            <h1><i class="fa-solid fa-laptop"></i> My Project's</h1>

            <div class="project-list">
        

                <div class="box">
                    <img src="Tic tac.jpg">
                    <div class="layer">
                        <h3>Tic Tac Toe</h3>
                        <p>I created Tic tac toe game using HTML, CSS, JavaScript and You can try it with your friends</p>
                        <div class="view">
                            <a href="https://tictac0.vercel.app/" target="_blank" class="btn"><i class="ri-eye-line"></i>View</a>
                            <a href="https://github.com/Anubhav kumar yaduvanshi-0/Tic-Tac-Toe-Game"  class="btn"><i class="ri-codepen-line"></i>Code</a>
                        </div>
                    </div>
                </div>
                
            </div>

           <a href="#" class="btn-2">See More<i class="ri-arrow-right-s-fill"></i></a>
        </div>
    </div>
    <!-- End Project Section -->

    <!-- Start Contact section -->
    <div id="contact">
        <div class="contact-container">
            <h1><i class="fa-solid fa-user"></i> Contact Me</h1>
            <div class="row">
                <div class="left-contact">
                    <p><i class="fa-solid fa-envelope"></i> anubhavbhai3400@gmail.com</p>
                    <p><i class="fa-solid fa-phone"></i> +91 726-883-8150</p>
                    <div id="msg"></div>
                </div>
                <div class="right-contact">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Name" required>
                        <input type="email" name="Email" placeholder="Email" required>
                        <textarea name="Message" placeholder="Message" rows="5" required></textarea>
                        <button type="submit" class="sub-btn">Submit <i class="fa-solid fa-paper-plane"></i></button>
                    </form>
                </div>
            </div>
        </div>
    </div>
    <!-- End Contact Section -->

    <!-- Start Footer Section -->
    <footer>
        <div class="container">
            <div class="copyright">
                <h3>Anubhav's Portfolio</h3>
                <p>Thanks for visiting my personal portfolio website, If you have any questions or feedback, please feel free to reach out</p>
            </div>
            <div class="quic-links">
                <h3>Quic Links</h3>
                <a href="#home"><i class="ri-send-plane-2-line"></i> Home</a>
                <a href="#about"><i class="ri-send-plane-2-line"></i> About</a>
                <a href="#skill"><i class="ri-send-plane-2-line"></i> Skills</a>
                <a href="#education-sec"><i class="ri-send-plane-2-line"></i> Education</a>
                <a href="#project"><i class="ri-send-plane-2-line"></i> Projects</a>
                <a href="#contact"><i class="ri-send-plane-2-line"></i> Contact</a> 
                
            </div>
            <div class="contact-info">
                <h3>Contact info</h3>
                <p><i class="fa-solid fa-envelope"></i> anubhavbhai3400@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i> +91 726-883-8150</p>
                <p><i class="ri-map-pin-user-fill"></i> Lucknow</p>
                
                <ul class="footer-social">
    
                    <li><a href="https://www.instagram.com/wishmaster_anubhav007/" target="_blank"><i class="fa-brands fa-instagram"></i></a></li>
    
                    <li><a href="www.linkedin.com/in/anubhav-yaduvanshi-237b7229b"target="_blank"><i class="fa-brands fa-linkedin-in"></i></a></li>
    
                </ul>
            </div>
        </div>
        <div id="copyright-message">
            <p>Copyright &copy; Anubhav, Made with <i class="ri-heart-fill"></i> By <span>Anubhav kumar yaduvanshi</span></p>
        </div>
    </footer>
    <!-- End Footer Section -->

    <!-- GSAP CDN -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.2/gsap.min.js"></script>
    <!-- Auto Type CDN -->
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <!-- My Script -->
    <script src="script.js"></script>

    <!-- Submited Message Script -->
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbzB-mRePqb3-2SGGLfKcbMTJwh2CLwpOo2h9yEKRl_ufxoDgRnnKRR5hWMBD9VfOxlayg/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg");
      
        form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => {
                msg.innerHTML = "Message sent successfully";
                setTimeout(function(){
                    msg.innerHTML = "";
                },2000)

                form.reset()
            })
            .catch(error => console.error('Error!', error.message))
        })
      </script>
  </body>
</html>
