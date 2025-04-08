# safety
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Safety Tracker</title>
    <style>
        /* Reset some basic elements */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        
        .container {
            width: 80%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header */
        header {
            background-color: #1a4673;
            color: white;
            padding: 20px 0;
            border-bottom: 3px solid #ff9800;
        }
        
        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 30px;
            font-weight: bold;
        }
        
        .highlight {
            color: #ff9800;
        }
        
        /* Navigation */
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav li {
            padding: 0 20px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        
        nav a:hover {
            color: #ff9800;
        }
        
        /* Showcase */
        .showcase {
            min-height: 400px;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('/api/placeholder/1200/400') no-repeat center center/cover;
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 0 20px;
        }
        
        .showcase h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .showcase p {
            font-size: 20px;
            max-width: 600px;
            margin: 0 auto 30px auto;
        }
        
        .btn {
            display: inline-block;
            background: #ff9800;
            color: white;
            padding: 10px 30px;
            border: none;
            cursor: pointer;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            text-transform: uppercase;
            font-weight: bold;
        }
        
        .btn:hover {
            background: #e68a00;
        }
        
        /* Features */
        .features {
            padding: 50px 0;
            background: #fff;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }
        
        .feature-box {
            padding: 30px;
            background: #f4f4f4;
            text-align: center;
            border-radius: 5px;
            border-top: 3px solid #1a4673;
        }
        
        .feature-box h3 {
            margin-bottom: 15px;
            color: #1a4673;
        }
        
        .feature-box p {
            margin-bottom: 20px;
        }
        
        /* About section */
        .about {
            padding: 50px 0;
            background: #1a4673;
            color: white;
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            align-items: center;
        }
        
        /* Contact Form */
        .contact {
            padding: 50px 0;
        }
        
        .contact h2 {
            margin-bottom: 30px;
            color: #1a4673;
        }
        
        .contact form {
            max-width: 600px;
            margin: 0 auto;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        
        .form-group textarea {
            height: 150px;
        }
        
        /* Form status messages */
        .form-status {
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 5px;
            display: none;
        }
        
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        
        /* Footer */
        footer {
            background: #1a4673;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            header .container {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 20px;
            }
            
            .about-content {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">Safety<span class="highlight">Tracker</span></div>
            <nav>
                <ul>
                    <li><a href="#" class="current">Home</a></li>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Showcase -->
    <section class="showcase">
        <h1>Workplace Safety Monitoring</h1>
        <p>Advanced real-time tracking and analytics to prevent incidents before they happen. Protect your team with data-driven safety solutions.</p>
        <a href="#features" class="btn">Explore Features</a>
    </section>

    <!-- Features -->
    <section id="features" class="features">
        <div class="container">
            <h2>Our Features</h2>
            <div class="feature-grid">
                <div class="feature-box">
                    <h3>Real-time Monitoring</h3>
                    <p>Track safety metrics and workplace conditions with continuous monitoring and instant alerts.</p>
                </div>
                <div class="feature-box">
                    <h3>Incident Prevention</h3>
                    <p>Use predictive analytics to identify potential hazards before accidents occur.</p>
                </div>
                <div class="feature-box">
                    <h3>Compliance Reporting</h3>
                    <p>Generate comprehensive safety reports that meet industry and regulatory requirements.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="about">
        <div class="container">
            <div class="about-content">
                <div>
                    <h2>About Safety Tracker</h2>
                    <p>Safety Tracker was developed by industry professionals with over 20 years of workplace safety experience. Our platform combines cutting-edge technology with practical safety knowledge to create a solution that truly works.</p>
                    <p>We believe that every worker deserves to return home safely after each shift. Our mission is to revolutionize workplace safety through accessible, data-driven tools that empower safety managers and protect employees.</p>
                </div>
                <div>
                    <img src="/api/placeholder/500/300" alt="Safety Monitoring Dashboard" style="width: 100%; border-radius: 5px;">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <div id="form-success" class="form-status success">Thank you for contacting us! Your message has been sent to our team.</div>
            <div id="form-error" class="form-status error">There was a problem sending your message. Please try again later.</div>
            
            <!-- IMPORTANT: Replace your-email@example.com with your actual email address -->
            <form id="contact-form" action="https://formsubmit.co/your-email@example.com" method="POST">
                <!-- FormSubmit configuration -->
                <input type="hidden" name="_subject" value="New Safety Tracker Demo Request">
                <input type="hidden" name="_template" value="table">
                <input type="text" name="_honey" style="display:none">
                <input type="hidden" name="_captcha" value="false">
                
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="company">Company</label>
                    <input type="text" id="company" name="company">
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" required></textarea>
                </div>
                <button type="submit" class="btn">Request Demo</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 SafetyTracker. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        // Form submission handling
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            // Note: We're not preventing default form submission here
            // because we want the form to actually submit to FormSubmit

            // Show success message (will only be visible momentarily before page redirects)
            document.getElementById('form-success').style.display = 'block';
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
