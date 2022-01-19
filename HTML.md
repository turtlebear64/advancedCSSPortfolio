# advancedCSSPortfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nicolas Danciu's Portfolio</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">Portfo<span>lio.</span></a></div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About Me</a></li>
                <li><a href="#services" class="menu-btn">Github</a></li>
                <li><a href="#skills" class="menu-btn">Current Skills</a></li>
                <li><a href="#teams" class="menu-btn">Education</a></li>
                <li><a href="#contact" class="menu-btn">Contact Info</a></li>
            </ul>
            <div class="menu-btn">
            </div>
        </div>
    </nav>
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hi!, my name is</div>
                <div class="text-2">Nicolas Danciu</div>
                <div class="text-3">welcome to my page <span class="typing"></span></div>
                <a href="mailto:nixrom1@gmail.com?subject=subject&cc=cc@example.com">Quick Contact</a>
            </div>
        </div>
    </section>

    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About me</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="https://images.pexels.com/photos/837358/pexels-photo-837358.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260") alt="">
                </div>
                <div class="column right">
                    <div class="text">My name is Nicolas and I'm<span class="typing-2"></span></div>
                    <p>currently trading on the stock market but I'd like to pursue something else in my life so I chose to learn how to code as a start.</p>
                    <a href="mailto:nixrom1@example.com?subject=subject&cc=cc@example.com">More about me</a>
                </div>
            </div>
        </div>
    </section>
    <section class="services" id="services">
        <div class="max-width">
            <h2 class="title">My Github</h2>
            <div class="serv-content">
                <div class="card">
                    <div class="card1">
                        <div class="card2">
                    <div class="box">
                        <div class="text">Link to my Github</div>
                        <a href=https://github.com/turtlebear64>My Github Page</a>
                    </div>
                </div>
                    </div>
                </div>
               </div>
            </div>
        </div>
    </section>
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">My current skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My skills and Education</div>
                    <p>So far, just HTML and CSS but moving right along to Javascript. Looking forward to much learning ahead!</p>
                    <a href="https://developer.mozilla.org/en-US/">Read more</a>
                </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</section>
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Quick Contact</div>
                    <p>Available for contact at any time of day</p>
                    <div class="icons">
                        <div class="row">
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Nicolas Danciu</div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">New Jersey</div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">nixrom1@gmail.com</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Contact Form</div>
                    <form action="#">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" placeholder="Name" required>
                            </div>
                            <div class="field email">
                                <input type="email" placeholder="Email" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" placeholder="Subject" required>
                        </div>
                        <div class="field textarea">
                            <textarea cols="30" rows="10" placeholder="Content of message" required></textarea>
                        </div>
                        <div class="button-area">
                            <button type="submit">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <footer> <!--I apologize for using a lot of divs, just found it way easier.-->
   <p>Thanks for browsing</p>
    </footer>
</body>
</html>
