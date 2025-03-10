# Capstone1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cosmopolitan Memorial Chapels</title>
    <link rel="stylesheet" href="User.css">
    <script defer src="UserNav.js"></script>
</head>
<body>

    <!-- New White Background Container with Logo -->
    <div class="top-logo-container">
        <div class="top-logo">
            <img src="../LogoCosmo.png" alt="Company Logo" >
        </div>
    </div>

    <!-- Navigation Bar (Sticky) -->
    <nav>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#funeral-service">Funeral Service</a></li>
            <li><a href="#chapel-reservation">Chapel Reservation</a></li>
            <li><a href="#casket-selection">Casket Selection</a></li>
            <li><a href="#about-us">About Us</a></li>
        </ul>
        <!-- Navigation Bar -->
<div class="nav-buttons">
    <a href="tel:999-999-9" class="contact-btn">📞 999-999-9</a>
    <a href="#" class="Login-btn" id="login-btn">Log In</a>
</div>

<!-- Login Form (Initially Hidden) -->
<div id="login-container">
    <div class="login-box">
        <span class="close-btn">&times;</span>
        <h2>Login</h2>

        <!-- Standard Login Form -->
        <form>
            <label for="email"></label>
            <input type="email" id="email" placeholder="Enter your email" required>

            <label for="password"></label>
            <input type="password" id="password" placeholder="Enter your password" required>

            <button type="submit" class="submit-btn">Login</button>
        </form>

        <!-- Sign Up Button -->
        <div class="signup-btn-container">
            <a href="#" class="signup-btn">Sign Up</a>
        </div>

        <!-- Social Login Section (Below the Sign Up Button) -->
        <div class="social-login">
            <p>Login with</p>
            <a href="#" class="social-btn google-btn">
                <img src="../google.png" alt="Google" class="social-logo">
            </a>
            <a href="#" class="social-btn facebook-btn">
                <img src="../fb.png" alt="Facebook" class="social-logo">
            </a>
        </div>
    </div>
</div>

<!-- Sign Up Form (Initially Hidden) -->
<div id="signup-container">
    <div class="login-box">
        <span class="close-btn">&times;</span>
        <h2>Sign Up</h2>

        <!-- Sign Up Form -->
        <form>
            <label for="full-name"></label>
            <input type="text" id="full-name" placeholder="Enter your full name" required>

            <label for="email-signup"></label>
            <input type="email" id="email-signup" placeholder="Enter your email" required>

            <label for="password-signup"></label>
            <input type="password" id="password-signup" placeholder="Enter your password" required>

            <label for="confirm-password">Confirm Password</label>
            <input type="password" id="confirm-password" placeholder="Confirm your password" required>

            <button type="submit" class="submit-btn">Sign Up</button>
        </form>

       
    </div>
</div>


        
    </nav>
    
    

    <!-- Sections -->
    <section id="home" class="hero-section">
        <div class="hero">
            <div class="overlay"></div>
            <div class="hero-content">
                <h1>70.70.70</h1>
                <p>Creating healing experiences for you and your families for 70 years</p>
                <span class="quote">"To honor death as unique as every individual."</span>
                <button class="book-btn">Book Now</button>
            </div>
        </div>
    </section>

    <section id="funeral-service" class="section">
        <h2>Funeral Service Packages</h2>
        <div class="package-container">
            <!-- Basic Package -->
            <div class="package basic-package">
                <h3>Basic Package</h3>
                <div class="image-slider">
                    <button class="arrow-left" onclick="moveSlide(-1)">&#10094;</button>
                    <div class="slider-container">
                        <img src="../casket11.jpg" alt="Image 1" class="slider-image">
                        <img src="../casket12.jpg" alt="Image 2" class="slider-image">
                        <img src="../casket13.jpg" alt="Image 3" class="slider-image">
                        <img src="../casket11.jpg" alt="Image 4" class="slider-image">
                    </div>
                    <button class="arrow-right" onclick="moveSlide(1)">&#10095;</button>
                </div>
                <p>A simple yet respectful service for honoring your loved ones.</p>
                <p class="price">₱30,000</p>
                <button class="read-more-btn">Read More</button>
            </div>
    
            <!-- Standard Package -->
            <div class="package standard-package">
                <h3>Standard Package</h3>
                <div class="image-slider">
                    <button class="arrow-left" onclick="moveSlide(-1)">&#10094;</button>
                    <div class="slider-container">
                        <img src="../casket12.jpg" alt="Image 1" class="slider-image">
                        <img src="../casket11.jpg" alt="Image 2" class="slider-image">
                        <img src="../casket13.jpg" alt="Image 3" class="slider-image">
                        <img src="../casket11.jpg" alt="Image 4" class="slider-image">
                    </div>
                    <button class="arrow-right" onclick="moveSlide(1)">&#10095;</button>
                </div>
                <p>A comprehensive service offering additional options for a meaningful tribute.</p>
                <p class="price">₱50,000</p>
                <button class="read-more-btn">Read More</button>
            </div>
    
            <!-- Premium Package -->
            <div class="package premium-package">
                <h3>Premium Package</h3>
                <div class="image-slider">
                    <button class="arrow-left" onclick="moveSlide(-1)">&#10094;</button>
                    <div class="slider-container">
                        <img src="../casket13.jpg" alt="Image 1" class="slider-image">
                        <img src="../casket11.jpg" alt="Image 2" class="slider-image">
                        <img src="../casket12.jpg" alt="Image 3" class="slider-image">
                        <img src="../casket11.jpg" alt="Image 4" class="slider-image">
                    </div>
                    <button class="arrow-right" onclick="moveSlide(1)">&#10095;</button>
                </div>
                <p>The most luxurious and personalized service for honoring your loved ones.</p>
                <p class="price">₱80,000</p>
                <button class="read-more-btn">Read More</button>
            </div>
        </div>
    </section>
    
    
    

    <section id="chapel-reservation" class="section">
        <h2>Chapel Reservation</h2>
        <p>Reserve our chapel for your memorial service.</p>
    </section>

    <section id="casket-selection" class="section">
        <h2>Casket Selection</h2>
        <p>Choose from a wide selection of caskets for your loved one.</p>
    </section>

    <section id="about-us" class="section">
        <h2>About Us</h2>
        <p>Learn more about our history and mission.</p>
    </section>


 

</body>
</html>
