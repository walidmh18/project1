
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spense</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="celebrate"><p> &#127881 To celebrate Spense's launch, we will be waiving all feesfor the entire month of april. <span>You will bw recieving 100% of the earnings.</span> &#127881</p></div>
    <nav id="navbar">
        <a class="navLogo" href="#">spense.</a>
        <div class="navMenuContainerContaier"  onclick="navOpening()"></div>
        <div class="navMenuContainer">
            <ul class="navEls">
                <li class="navEl"><a class="active" href="" onclick="if (screen.width<= 425) {
                    navOpening()
                }">business</a></li>
                <li class="navEl"><a href="" onclick="if (screen.width<= 425) {
                    navOpening()
                }">pricing</a></li>
                <li class="navEl"><a href="" onclick="if (screen.width<= 425) {
                    navOpening()
                }">features</a></li>
            </ul>
            <div class="navGetStarted">
                <a class="loginBtn" href="#">login</a>
                <a class="getStartedBtn" href="#">get started</a>
            </div>
            <div id="navClose" onclick="navOpening()">
                </div>
        </div>
        
        
        <div id="navOpen" class="hamburgerMenu">
            <svg onclick="navOpening()" width="24" height="20" viewBox="0 0 24 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M24 4H0V0H24V4ZM24 8H0V12H24V8ZM24 16H0V20H24V16Z" fill="black"/>
                </svg>
                
        </div>
    </nav>

    <section id="business">
        <div class="businessText">
            <h1>Share your unfiltered <br>thoughts. Get paid.</h1>
            <p>Spense is an open platform for individuals to share their unfiltered thoughts. discuss the topics you love, and get paid for doing just that.
            </p>
            <div class="sec1Features">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 0C5.373 0 0 5.373 0 12C0 18.627 5.373 24 12 24C18.627 24 24 18.627 24 12C24 5.373 18.627 0 12 0ZM10.75 17.292L6.25 12.928L8.107 11.07L10.75 13.576L16.393 7.792L18.25 9.649L10.75 17.292Z" fill="black"/>
                </svg> <p>recieve 99% off the earnings.</p>
            </div>
            <div class="sec1Features">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 0C5.373 0 0 5.373 0 12C0 18.627 5.373 24 12 24C18.627 24 24 18.627 24 12C24 5.373 18.627 0 12 0ZM10.75 17.292L6.25 12.928L8.107 11.07L10.75 13.576L16.393 7.792L18.25 9.649L10.75 17.292Z" fill="black"/>
                </svg> <p>Get paid via Debit Card, ACH, or PayPal.</p>
            </div>
            <div class="sec1Features">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 0C5.373 0 0 5.373 0 12C0 18.627 5.373 24 12 24C18.627 24 24 18.627 24 12C24 5.373 18.627 0 12 0ZM10.75 17.292L6.25 12.928L8.107 11.07L10.75 13.576L16.393 7.792L18.25 9.649L10.75 17.292Z" fill="black"/>
                </svg> <p>Withdraw your earnings anytime.</p>
            </div>
            <div class="getStartedForm">
                <form action="getstarted">
                    <input type="email" placeholder="john@example.com">
                    <input class="getStartedBtn" type="submit" value="Get Started">
                </form>
            </div>
        </div>
        <div class="businessImg">
            <img class="herodesk" src="images/Hero Image (Desktop).png" alt="">
            <img class="herotablet" src="images/Hero Image (Tablet).png" alt="">
            <img class="heromobile" src="images/Hero Image (Mobile).png" alt="">

        </div>
    </section>
    <div class="logos">
        <div class="mobileLogos tabletLogos desktopLogos">
            <img src="images/Facebook Logo.png" alt="">
            <img src="images/Dribbble Logo.png" alt="">
            <img src="images/Youtube Logo.png" alt="">

        </div>
        <div class=" tabletLogos desktopLogos">
            <img src="images/Pinterest Logo.png" alt="">
            <img src="images/Twitter Logo.png" alt="">
        </div>
        <div class="desktopLogos">
            <img src="images/Reddit Logo.png" alt="">
            <img src="images/Google Logo.png" alt="">
            <img src="images/Slack Logo.png" alt="">
        </div>
    </div>
    <section id="sec2">
        <div class="sec2Text">
            <h1 class="secH1">Secure your money <br>with Escrow.</h1>
            <p class="secP">Spense uses Escrow to secure all paiments. We believe Escrow offers the highest level of security for your paiments, so you never need to woory about scams </p>
            <a class="secAnchor" href="#">Learn more about Escrow →</a>
        </div>
        <div class="sec2Img">
            <img class="phonedesk" src="images/Phone Mockup (Desktop).png" alt="">
            <img class="phonetablet" src="images/Phone Mockup (Tablet).png" alt="">
            <img class="phonemobile" src="images/Phone Mockup (Mobile).png" alt="">

        </div>
    </section>
    <section id="sec3">
        <div class="sec3Txt">
            <h1 class="secH1">A text editor like no other.</h1>
            <p class="secP">our text editor pulls you into focus mode with its simplistic design and usability so you can put out your best writings.</p>
            <a class="secAnchor" href="#">Text Editor Live Demo →</a>
        </div>
        <div class="sec3Img">
            <img src="images/Text Editor.png" alt="">
        </div>
    </section>
    <footer>
        <div class="footerCol footerCol1">
            <h2>spense.</h2>
            <p>Spense is an open platform for individuals to share their unfiltered thoughts. discuss the topics you love, and get paid for doing just that.</p>
        </div>
        <div class="footerCol">
            <h2>Sitemap</h2>
            <ul>
                <li><a href="#">Homepage</a></li>
            </ul>
        </div>
        <div class="footerCol">
            <h2>Resources</h2>
            <ul>
                <li><a href="#">Support</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="#">FAQ</a></li>
            </ul>
        </div>
        <div class="footerCol">
            <h2>Company</h2>
            <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Customers</a></li>
                <li><a href="#">Blog</a></li>
            </ul>
        </div>
        <div class="footerCol">
            <h2>Opportunities</h2>
            <ul>
                <li><a href="#">Jobs</a></li>
            </ul>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
