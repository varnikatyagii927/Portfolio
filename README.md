<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/68ec419216.js" crossorigin="anonymous"></script>
</head>

<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/logo.jpeg" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Front-End Developer</p>
                <h1>Hi, I Am <span>Varnika</span> <br> Tyagi</h1>
            </div>
        </div>
    </div>


    <!-- --------------about-------------- -->


    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/1.jpg">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About me</h1>
                    <p>"I have a need to produce results. I am the type of person to meet challenges head-on 
                        rather than sweep them under the rug and hope they go away. I am an enthusiastic and 
                        talented engineer and currently pursuing my bachelor's in technology from ABES 
                        Institute of Technology (AKTU)"    
                    </p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Hobbies</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>Languages</span><br>C/C++, Python</li>
                            <li><span>Front End</span><br>HTML, CSS, JavaScript</li>
                            <li><span>Backend</span><br>php, Python</li>
                            <li><span>Data Base</span><br>MySQL</li>
                            <li><span>VR</span><br>Unity, Blender</li>
                            <li><span>Others</span><br>Object Oriented Programming, Data Structure and Algorithem</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>Photography</span><br>Macro, Travel, Golden hour</li>
                            <li><span>Sketching</span><br>Cartoon, Figure, Sketch</li>
                            <li><span>Reading Books</span><br>Rich dad Poor dad, Five sec9nd rule</li>
                            <li><span>Travelling</span><br>Anywhere in the world</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2020-2024</span><br>B.Tech (Computer Science and Engineering)</li>
                            <li><span>2020</span><br>Intermediate (Science Stream - PCM)</li>
                            <li><span>2018</span><br>High School (Science Stream)</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ----------------------------services----------------------------- -->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Web Development</h2>
                    <p>I can develop a website and maintain it. I can create website which can range from a simple single static page of plain text to complex web application, electronic businesses, and social network services.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop-simple"></i>
                    <h2>Problem Solving</h2>
                    <p>I can define a problem, determine the cause of the problem then identify and prioritize diffent option at the end select the alternatives for a solution and implement a solution.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store"></i>
                    <h2>Database</h2>
                    <p>I can create a database to organize collection of structured information or data, typically stored electronically in a computer system. Data stored in the database which has been sent by the peoples collected bt the forms.</p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>


    <!-- -----------------------------portfolio---------------------------- -->

    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/work1.jpg">
                    <div class="layer">
                        <h3>Movie Recommender System</h3>
                        <p>Created an app using python</p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work2.jpg">
                    <div class="layer">
                        <h3>Database</h3>
                        <p>Created a form atteched with an database developed by MySQL</p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work3.jpg">
                    <div class="layer">
                        <h3>Supermarket Billing System</h3>
                        <p>Created a billing system using cpp</p>
                        <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
    </div>


    <!-- ---------------contact------------------- -->

    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-envelope"></i>varnikatyagi927@gmail.com</p>
                    <p><i class="fa-solid fa-mobile-screen-button"></i>7428665996</p>
                    <div class="social-icons">
                        <a href="https://www.facebook.com/varnika.tyagi.12720"><i class="fa-brands fa-facebook"></i></a>
                        <a href="https://twitter.com/Varnika94995200"><i class="fa-brands fa-twitter"></i></a>
                        <a href="http://instagram.com/varnikatyagi_._"><i class="fa-brands fa-instagram"></i></a>
                        <a href="https://www.linkedin.com/in/varnika-tyagi-1b6a081b1"><i
                                class="fa-brands fa-linkedin"></i></a>
                    </div>
                    <a href="images/Varnika Tyagi (4).pdf" download class="btn btn2">Download Resume</a>
                </div>
                <div class="contact-right">
                    <form name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" placeholder="Your Email" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="Submit" class="btn btn2">Submit</button>
                    </form>
                    <span id="msg"></span>
                </div>
            </div>
        </div>
        <div class="copy-right">
            <p>Copyright ⓒ Varnika. Made with <i class="fa-solid fa-heart"></i> by Varnika Tyagi</p>
        </div>
    </div>


    <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname) {
            for (tablink of tablinks) {
                tablink.classList.remove("active-link");
            }
            for (tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab")
        }
    </script>


    <script>
        var sidemeu = document.getElementById("sidemenu")

        function openmenu() {
            sidemeu.style.right = "0";
        }
        function closemenu() {
            sidemeu.style.right = "-200px";
        }
    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbzyQKodrpT1SsenVPX80rbNoMpwlQf_YZhrbdh64UkVJSlKuvMQE6nzKmykTNy8uz0/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")

        form.addEventListener('submit', e => {
            e.preventDefault()
            fetch(scriptURL, { method: 'POST', body: new FormData(form) })
                .then(response => {
                    msg.innerHTML = "Message sent successfully"
                    setTimeout(function(){
                        msg.innerHTML = ""
                    },5000)
                    form.reset()
                })
                .catch(error => console.error('Error!', error.message))
        })
    </script>
</body>

</html>