
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tshims Service - Transport, Freight & Agricultural Solutions</title>
    <style>
        /* Add this to your existing CSS */
        .logo {
            display: flex;
            align-items: center;
            text-decoration: none;
        }
        
        .logo-text {
            font-size: 1.8rem;
            font-weight: bold;
            color: white;
            position: relative;
            padding-left: 40px; /* Space for the icon */
        }
        
        .logo-text::before {
            content: "";
            position: absolute;
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 30px;
            height: 30px;
            background-color: var(--accent-color);
            border-radius: 50%;
        }
        
        .logo-text::after {
            content: "TS";
            position: absolute;
            left: 0;
            top: 50%;
            transform: translateY(-50%);
            width: 30px;
            height: 30px;
            color: white;
            font-size: 0.9rem;
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        /* Rest of your existing CSS... */
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <a href="#" class="logo">
                    <span class="logo-text">Tshims Service</span>
                </a>
                
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Rest of your HTML content... -->
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tshims Service - Transport, Freight & Agricultural Solutions</title>
    <style>
        :root {
            --primary-color: #2e8b57;
            --secondary-color: #333;
            --accent-color: #ff7f50;
            --light-color: #f4f4f4;
            --dark-color: #222;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: var(--dark-color);
            background-color: #f9f9f9;
        }
        
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: white;
            text-decoration: none;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 2rem;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
        }
        
        .nav-links a:hover {
            color: var(--accent-color);
        }
        
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1581094794329-aa3b557b786e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            align-items: center;
            color: white;
            text-align: center;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        
        .btn {
            display: inline-block;
            background: var(--accent-color);
            color: white;
            padding: 0.8rem 1.8rem;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background: #ff6347;
            transform: translateY(-3px);
        }
        
        section {
            padding: 4rem 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            color: var(--primary-color);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-img {
            height: 200px;
            overflow: hidden;
        }
        
        .service-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .service-card:hover .service-img img {
            transform: scale(1.1);
        }
        
        .service-content {
            padding: 1.5rem;
        }
        
        .service-content h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
        }
        
        .about-content {
            display: flex;
            align-items: center;
            gap: 3rem;
            margin-top: 2rem;
        }
        
        .about-text {
            flex: 1;
        }
        
        .about-img {
            flex: 1;
            border-radius: 8px;
            overflow: hidden;
        }
        
        .about-img img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
        }
        
        .form-group textarea {
            height: 150px;
            resize: vertical;
        }
        
        footer {
            background: var(--secondary-color);
            color: white;
            padding: 3rem 0 1rem;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }
        
        .footer-column h3 {
            margin-bottom: 1.5rem;
            color: var(--accent-color);
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 0.8rem;
        }
        
        .footer-column ul li a {
            color: #ddd;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        
        .footer-column ul li a:hover {
            color: var(--accent-color);
        }
        
        .social-links {
            display: flex;
            gap: 1rem;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }
        
        .social-links a:hover {
            color: var(--accent-color);
        }
        
        .copyright {
            text-align: center;
            padding-top: 1.5rem;
            border-top: 1px solid #444;
        }
        
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .about-content {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <a href="#" class="logo">Tshims Service</a>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Your Trusted Partner for Comprehensive Services</h1>
            <p>From transportation and freight to agricultural products and telecom solutions - we deliver excellence in every service.</p>
            <a href="#contact" class="btn">Get In Touch</a>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2 class="section-title">Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1532635241-17e820acc59f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Transport Services">
                    </div>
                    <div class="service-content">
                        <h3>Transport Services</h3>
                        <p>Reliable and efficient transportation solutions for individuals and businesses. We handle local and long-distance logistics with care.</p>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Freight Services">
                    </div>
                    <div class="service-content">
                        <h3>Freight Services</h3>
                        <p>Secure and timely freight services for domestic and international shipments. Our logistics network ensures your goods arrive safely.</p>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Agricultural Products">
                    </div>
                    <div class="service-content">
                        <h3>Agricultural Products</h3>
                        <p>High-quality household farming products including seeds, tools, fertilizers, and more to support your agricultural needs.</p>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1512941937669-90cbf7b5a655?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Telecommunications">
                    </div>
                    <div class="service-content">
                        <h3>Telecom & Accessories</h3>
                        <p>Mobile devices, airtime, and the latest telecom accessories to keep you connected in today's digital world.</p>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Consultation Services">
                    </div>
                    <div class="service-content">
                        <h3>Consultation Services</h3>
                        <p>Expert advice and consultation for agribusiness and logistics to help you make informed decisions.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2 class="section-title">About Tshims Service</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>Tshims Service is a leading provider of comprehensive solutions in transportation, freight, agricultural products, and telecommunications. Founded with a commitment to excellence, we have grown to become a trusted partner for businesses and individuals alike.</p>
                    <p>Our team of professionals brings years of experience in their respective fields, ensuring that we deliver quality services tailored to meet your specific needs. We pride ourselves on reliability, efficiency, and customer satisfaction.</p>
                    <p>Whether you need to transport goods, source agricultural products, or stay connected with the latest telecom solutions, Tshims Service is your one-stop solution.</p>
                </div>
                <div class="about-img">
                    <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Our Team">
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2 class="section-title">Contact Us</h2>
            <div class="contact-form">
                <form>
                    <div class="form-group">
                        <label for="name">Full Name</label>
                        <input type="text" id="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email Address</label>
                        <input type="email" id="email" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">Phone Number</label>
                        <input type="tel" id="phone">
                    </div>
                    <div class="form-group">
                        <label for="service">Service Interested In</label>
                        <select id="service">
                            <option value="">Select a service</option>
                            <option value="transport">Transport Services</option>
                            <option value="freight">Freight Services</option>
                            <option value="agriculture">Agricultural Products</option>
                            <option value="telecom">Telecom & Accessories</option>
                            <option value="consultation">Consultation Services</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="message">Your Message</label>
                        <textarea id="message" required></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Tshims Service</h3>
                    <p>Your trusted partner for transport, freight, agricultural products, and telecom solutions.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook">f</i></a>
                        <a href="#"><i class="fab fa-twitter">t</i></a>
                        <a href="#"><i class="fab fa-instagram">ig</i></a>
                        <a href="#"><i class="fab fa-linkedin">in</i></a>
                    </div>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Services</h3>
                    <ul>
                        <li><a href="#">Transport</a></li>
                        <li><a href="#">Freight</a></li>
                        <li><a href="#">Agricultural Products</a></li>
                        <li><a href="#">Telecom & Accessories</a></li>
                        <li><a href="#">Consultation</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Info</h3>
                    <ul>
                        <li>123 Kampala (U), City</li>
                        <li>Phone: +256 75 694 2999</li>
                        <li>Email: info@tshimsservice.com</li>
                        <li>Hours: Mon-Fri 8am-5pm</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 Tshims Service. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
