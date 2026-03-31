# my-html-website-fictional-use-only-not-true-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARK Repair Shop | Professional Fixes</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: #333;
            scroll-behavior: smooth;
        }

        /* Navigation */
        nav {
            background: #1a1a1a;
            color: #fff;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #ff4d4d;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            transition: 0.3s;
        }

        nav ul li a:hover {
            color: #ff4d4d;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1581092160562-40aa08e78837?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 60vh;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        .hero h1 { font-size: 3rem; margin-bottom: 10px; }
        .hero p { font-size: 1.2rem; margin-bottom: 20px; }

        .btn {
            background: #ff4d4d;
            color: #fff;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        /* Services Section */
        .services {
            padding: 50px 5%;
            text-align: center;
            background: #f4f4f4;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .service-card {
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .service-card h3 { color: #ff4d4d; }

        /* Contact Section */
        .contact {
            padding: 50px 5%;
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        /* Footer */
        footer {
            background: #1a1a1a;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            nav ul { display: none; }
            .hero h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">MARK REPAIR</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero" id="home">
        <h1>Fixed Fast. Fixed Right.</h1>
        <p>Your trusted experts for all types of mechanical and electronic repairs.</p>
        <a href="#contact" class="btn">Get an Estimate</a>
    </section>

    <section class="services" id="services">
        <h2>Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Diagnostics</h3>
                <p>Advanced system testing to find the root cause of the problem quickly.</p>
            </div>
            <div class="service-card">
                <h3>Maintenance</h3>
                <p>Keep your equipment running smoothly with scheduled tune-ups.</p>
            </div>
            <div class="service-card">
                <h3>Part Replacement</h3>
                <p>We use high-quality, certified parts for every repair job.</p>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Visit Us</h2>
        <p><strong>Address:</strong> 123 Repair Lane, Fix-it Town</p>
        <p><strong>Phone:</strong> (555) 123-4567</p>
        <p><strong>Hours:</strong> Mon - Sat: 8:00 AM - 6:00 PM</p>
        <div style="margin-top: 20px;">
            <p>Ready to get started? Drop by or give us a call!</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 MARK Repair Shop. All rights reserved.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARK Repair Shop | Tech & Computer Specialists</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: #333;
            scroll-behavior: smooth;
            background-color: #f9f9f9;
        }

        /* Navigation */
        nav {
            background: #1a1a1a;
            color: #fff;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        nav .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #ff4d4d;
            letter-spacing: 1px;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
        }

        nav ul li { margin-left: 25px; }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: 500;
            transition: 0.3s;
        }

        nav ul li a:hover { color: #ff4d4d; }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.75)), 
                        url('https://images.unsplash.com/photo-1597740985671-2a8a3b80502e?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 50vh;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        .hero h1 { font-size: 3.5rem; margin-bottom: 10px; }
        .hero p { font-size: 1.3rem; margin-bottom: 25px; opacity: 0.9; }

        .btn {
            background: #ff4d4d;
            color: #fff;
            padding: 15px 35px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover { background: #e60000; }

        /* Services Section */
        .services { padding: 80px 5%; text-align: center; }
        .services h2 { font-size: 2.5rem; margin-bottom: 40px; color: #1a1a1a; }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .service-card {
            background: #fff;
            padding: 40px 30px;
            border-radius: 12px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.05);
            border-top: 5px solid #ff4d4d;
            transition: transform 0.3s;
        }

        .service-card:hover { transform: translateY(-10px); }
        .service-card h3 { font-size: 1.5rem; margin-bottom: 15px; color: #1a1a1a; }
        
        .service-card ul {
            list-style: none;
            padding: 0;
            text-align: left;
            display: inline-block;
        }

        .service-card ul li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }

        .service-card ul li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #ff4d4d;
            font-weight: bold;
        }

        /* Contact Section */
        .contact {
            padding: 80px 5%;
            background: #1a1a1a;
            color: #fff;
            text-align: center;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .contact-box h4 { color: #ff4d4d; margin-bottom: 5px; }

        /* Footer */
        footer {
            background: #000;
            color: #888;
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            nav ul { display: none; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">MARK REPAIR SHOP</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero" id="home">
        <h1>Fast & Reliable Tech Support</h1>
        <p>Expert repairs for Mobiles, Laptops, and PCs.</p>
        <a href="#contact" class="btn">Get Help Now</a>
    </section>

    <section class="services" id="services">
        <h2>Professional Repair Services</h2>
        <div class="services-grid">
            
            <div class="service-card">
                <h3>Mobile & Tablet</h3>
                <ul>
                    <li>Screen replacement</li>
                    <li>Battery replacement</li>
                    <li>Charging port repair</li>
                    <li>IC repair</li>
                    <li>Account Bypass (iCloud/Google)</li>
                </ul>
            </div>

            <div class="service-card">
                <h3>Laptop & PC</h3>
                <ul>
                    <li>LCD & Keyboard replacement</li>
                    <li>Reformat & OS Installation</li>
                    <li>Motherboard repair</li>
                    <li>Data recovery</li>
                    <li>Professional cleaning</li>
                </ul>
            </div>

            <div class="service-card">
                <h3>Specialty Repairs</h3>
                <ul>
                    <li>Water damage repair</li>
                    <li>Hinge repair</li>
                    <li>Fan replacement</li>
                    <li>System Diagnostics</li>
                </ul>
            </div>

        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>Expert service is just a call or visit away.</p>
        <div class="contact-info">
            <div class="contact-box">
                <h4>Call Us</h4>
                <p>(555) 012-3456</p>
            </div>
            <div class="contact-box">
                <h4>Visit Us</h4>
                <p>123 Tech Avenue, Suite 4</p>
            </div>
            <div class="contact-box">
                <h4>Hours</h4>
                <p>Mon-Sat: 9AM - 7PM</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 MARK Repair Shop. All rights reserved.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARK Repair Shop | Tech & Computer Specialists</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: #333;
            scroll-behavior: smooth;
            background-color: #f9f9f9;
        }

        /* Navigation */
        nav {
            background: #1a1a1a;
            color: #fff;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav .logo { font-size: 1.5rem; font-weight: bold; color: #ff4d4d; }
        nav ul { list-style: none; display: flex; margin: 0; }
        nav ul li { margin-left: 25px; }
        nav ul li a { color: #fff; text-decoration: none; transition: 0.3s; }
        nav ul li a:hover { color: #ff4d4d; }

        /* Promo Banner */
        .promo-banner {
            background: #ff4d4d;
            color: white;
            text-align: center;
            padding: 10px 0;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.75)), 
                        url('https://images.unsplash.com/photo-1597740985671-2a8a3b80502e?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 45vh;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .hero h1 { font-size: 3rem; margin: 0; }

        /* Services Grid */
        .section-padding { padding: 60px 5%; }
        .text-center { text-align: center; }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .service-card {
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            border-top: 4px solid #ff4d4d;
        }

        /* Pricing Table */
        .price-container {
            max-width: 900px;
            margin: 40px auto;
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th { background: #1a1a1a; color: #fff; padding: 15px; }
        td { padding: 15px; border-bottom: 1px solid #eee; text-align: center; }
        tr:hover { background: #fffcfc; }
        .price-tag { font-weight: bold; color: #ff4d4d; }

        /* Contact Section */
        .contact {
            background: #1a1a1a;
            color: #fff;
            padding: 60px 5%;
            text-align: center;
        }

        footer { background: #000; color: #777; text-align: center; padding: 20px; }

        @media (max-width: 768px) {
            nav ul { display: none; }
        }
    </style>
</head>
<body>

    <div class="promo-banner">
        🔥 Weekend Special: 50% OFF every Friday & Saturday! 🔥
    </div>

    <nav>
        <div class="logo">MARK REPAIR SHOP</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#pricing">Pricing</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero" id="home">
        <h1>Expert Tech Repairs</h1>
        <p>Quality service you can trust at prices you can afford.</p>
    </section>

    <section class="section-padding" id="services">
        <h2 class="text-center">Our Specialized Repairs</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Mobile & Tablet</h3>
                <p>Screen & battery replacement, port repairs, IC repair, and iCloud/Google bypass.</p>
            </div>
            <div class="service-card">
                <h3>Laptop & PC</h3>
                <p>LCD/Keyboard replacement, OS installation, motherboard repair, and data recovery.</p>
            </div>
            <div class="service-card">
                <h3>Specialty</h3>
                <p>Water damage recovery, hinge repair, and internal fan/cooling system replacement.</p>
            </div>
        </div>
    </section>

    <section class="section-padding" id="pricing" style="background:#f0f0f0;">
        <h2 class="text-center">Estimated Pricing</h2>
        <p class="text-center">Actual price may vary depending on parts and model.</p>
        
        <div class="price-container">
            <table>
                <thead>
                    <tr>
                        <th>Repair Service</th>
                        <th>Standard Price</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Laptop Screen Replacement</td>
                        <td class="price-tag">₱3,000 - ₱8,000</td>
                    </tr>
                    <tr>
                        <td>Keyboard or Component Issues</td>
                        <td class="price-tag">₱2,000 - ₱6,000</td>
                    </tr>
                    <tr>
                        <td>Laptop Hinge Repair</td>
                        <td class="price-tag">₱1,500 - ₱5,000</td>
                    </tr>
                    <tr>
                        <td>Cooling Fan Repair</td>
                        <td class="price-tag">₱1,000 - ₱3,000</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Ready to fix your device?</h2>
        <p>Visit us today or call (555) 012-3456</p>
        <p><strong>Location:</strong> 123 Tech Avenue, San Mateo</p>
    </section>

    <footer>
        <p>&copy; 2026 MARK Repair Shop. All rights reserved.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARK Repair Shop | Bulacan Tech Specialists</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: #333;
            scroll-behavior: smooth;
            background-color: #f9f9f9;
        }

        /* Navigation */
        nav {
            background: #1a1a1a;
            color: #fff;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav .logo { font-size: 1.5rem; font-weight: bold; color: #ff4d4d; }
        nav ul { list-style: none; display: flex; margin: 0; }
        nav ul li { margin-left: 25px; }
        nav ul li a { color: #fff; text-decoration: none; transition: 0.3s; }
        nav ul li a:hover { color: #ff4d4d; }

        /* Promo Banner */
        .promo-banner {
            background: #ff4d4d;
            color: white;
            text-align: center;
            padding: 10px 0;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-size: 0.9rem;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.75)), 
                        url('https://images.unsplash.com/photo-1597740985671-2a8a3b80502e?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 40vh;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .hero h1 { font-size: 3rem; margin: 0; }

        /* Services Grid */
        .section-padding { padding: 60px 5%; }
        .text-center { text-align: center; }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .service-card {
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            border-top: 4px solid #ff4d4d;
        }

        /* Pricing Table */
        .price-container {
            max-width: 900px;
            margin: 40px auto;
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        table { width: 100%; border-collapse: collapse; }
        th { background: #1a1a1a; color: #fff; padding: 15px; }
        td { padding: 15px; border-bottom: 1px solid #eee; text-align: center; }
        .price-tag { font-weight: bold; color: #ff4d4d; }

        /* Contact Section */
        .contact {
            background: #1a1a1a;
            color: #fff;
            padding: 60px 5%;
            text-align: center;
        }

        .location-info {
            margin-top: 20px;
            font-size: 1.2rem;
            color: #ff4d4d;
            font-weight: bold;
        }

        footer { background: #000; color: #777; text-align: center; padding: 20px; font-size: 0.85rem; }

        @media (max-width: 768px) {
            nav ul { display: none; }
            .hero h1 { font-size: 2.2rem; }
        }
    </style>
</head>
<body>

    <div class="promo-banner">
        🔥 WEEKEND SALE: 50% OFF EVERY FRIDAY & SATURDAY! 🔥
    </div>

    <nav>
        <div class="logo">MARK REPAIR SHOP</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#pricing">Pricing</a></li>
            <li><a href="#contact">Find Us</a></li>
        </ul>
    </nav>

    <section class="hero" id="home">
        <h1>Tech Repairs in Bulacan</h1>
        <p>Your trusted neighborhood experts for Mobile, Laptop, and PC fixes.</p>
    </section>

    <section class="section-padding" id="services">
        <h2 class="text-center">What We Fix</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Mobile & Tablet</h3>
                <p>Screen & battery replacement, charging port repair, IC repair, and iCloud/Google Account bypass.</p>
            </div>
            <div class="service-card">
                <h3>Laptop & PC</h3>
                <p>LCD/Keyboard replacement, Reformat/OS installation, motherboard repair, and data recovery.</p>
            </div>
            <div class="service-card">
                <h3>Specialty</h3>
                <p>Professional water damage repair, hinge repair, and cooling fan replacement.</p>
            </div>
        </div>
    </section>

    <section class="section-padding" id="pricing" style="background:#f0f0f0;">
        <h2 class="text-center">Price Guide</h2>
        <div class="price-container">
            <table>
                <thead>
                    <tr>
                        <th>Service</th>
                        <th>Standard Rate</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Laptop Screen Replacement</td>
                        <td class="price-tag">₱3,000 - ₱8,000</td>
                    </tr>
                    <tr>
                        <td>Keyboard or Component Issues</td>
                        <td class="price-tag">₱2,000 - ₱6,000</td>
                    </tr>
                    <tr>
                        <td>Laptop Hinge Repair</td>
                        <td class="price-tag">₱1,500 - ₱5,000</td>
                    </tr>
                    <tr>
                        <td>Cooling Fan Repair</td>
                        <td class="price-tag">₱1,000 - ₱3,000</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <p class="text-center"><em>*Visit us on Fri/Sat to get 50% off these rates!</em></p>
    </section>

    <section class="contact" id="contact">
        <h2>Visit Our Shop</h2>
        <p>Quality repairs are just around the corner.</p>
        
        <div class="location-info">
            5 Golden Street, Vigan, Bulacan
        </div>
        
        <div style="margin-top: 30px;">
            <p><strong>Phone:</strong> (555) 0912-345-6789</p>
            <p><strong>Operating Hours:</strong> Mon - Sat: 9:00 AM - 6:00 PM</p>
        </div>
    </section>

    <footer>
        <p>MARK Repair Shop | 5 Golden Street, Vigan, Bulacan</p>
        <p>&copy; 2026 All Rights Reserved.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARK | Bulacan Tech Cult</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">

    <style>
        /* Base Styling */
        :root {
            --bg-dark: #0a0a0a; /* Pure deep dark */
            --bg-accent: #111111; /* Slightly lighter dark for contrast */
            --magenta: #ff00ff; /* Electric Magenta */
            --cyan: #00ffff; /* Neon Cyan */
            --white: #ffffff;
            --text-gray: #b0b0b0;
            --glass: rgba(255, 255, 255, 0.05); /* Frosty effect */
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            line-height: 1.6;
            color: var(--white);
            background-color: var(--bg-dark);
            scroll-behavior: smooth;
        }

        /* The 'Drop' Promo Banner */
        .promo-banner {
            background-color: var(--magenta);
            color: black;
            text-align: center;
            padding: 8px 0;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 2px;
            font-size: 0.8rem;
            box-shadow: 0 0 15px var(--magenta);
            position: relative;
            z-index: 1001;
        }

        /* Retro-Futuristic Nav */
        nav {
            background: rgba(10, 10, 10, 0.9);
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        nav .logo { 
            font-size: 1.6rem; 
            font-weight: 800; 
            color: var(--white); 
            text-transform: uppercase; 
            letter-spacing: -1px;
        }
        
        nav .logo span { color: var(--magenta); }

        nav ul { list-style: none; display: flex; margin: 0; }
        nav ul li { margin-left: 25px; }
        nav ul li a { 
            color: var(--white); 
            text-decoration: none; 
            font-weight: 600; 
            text-transform: uppercase; 
            font-size: 0.85rem; 
            letter-spacing: 1px;
            transition: 0.3s; 
        }
        nav ul li a:hover { color: var(--cyan); }

        /* Cyber-Noir Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.85), rgba(0,0,0,0.85)), 
                        url('https://images.unsplash.com/photo-1599661046289-e318978fab67?q=80&w=2000&auto=format&fit=crop'); /* Neon Technician Image */
            background-size: cover;
            background-position: center;
            height: 50vh;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
        }

        .hero::after { /* Glitchy bottom border effect */
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 100%;
            height: 4px;
            background: linear-gradient(90deg, var(--magenta), var(--cyan));
        }

        .hero h1 { 
            font-size: 3.5rem; 
            margin: 0; 
            font-weight: 800; 
            text-transform: uppercase; 
            letter-spacing: -2px; 
            line-height: 1;
        }

        .hero h1 span {
            color: transparent;
            -webkit-text-stroke: 1.5px var(--white); /* Stretched outline font trend */
        }

        .hero p {
            color: var(--text-gray);
            font-size: 1rem;
            margin-top: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Services Grid: Glassmorphism */
        .section-padding { padding: 80px 5%; }
        .text-center { text-align: center; }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

        .service-card {
            background: var(--glass);
            backdrop-filter: blur(10px); /* Frosted glass effect */
            -webkit-backdrop-filter: blur(10px);
            padding: 40px 30px;
            border-radius: 15px;
            border: 1px solid rgba(255, 255, 255, 0.08);
            transition: transform 0.3s, border-color 0.3s, box-shadow 0.3s;
            position: relative;
            overflow: hidden;
        }

        /* Card Hover Effects: The Glow */
        .service-card:nth-child(1):hover { border-color: var(--magenta); box-shadow: 0 0 20px rgba(255, 0, 255, 0.3); transform: translateY(-5px); }
        .service-card:nth-child(2):hover { border-color: var(--cyan); box-shadow: 0 0 20px rgba(0, 255, 255, 0.3); transform: translateY(-5px); }
        .service-card:nth-child(3):hover { border-color: var(--magenta); box-shadow: 0 0 20px rgba(255, 0, 255, 0.3); transform: translateY(-5px); }

        .service-card h3 { 
            font-size: 1.3rem; 
            margin: 0; 
            text-transform: uppercase; 
            letter-spacing: 1px; 
            font-weight: 800;
        }

        .service-card:nth-child(odd) h3 { color: var(--magenta); }
        .service-card:nth-child(even) h3 { color: var(--cyan); }

        .service-card p { color: var(--text-gray); font-size: 0.95rem; margin-top: 15px; }

        /* Neo-Noir Pricing Table */
        .price-container {
            max-width: 900px;
            margin: 50px auto;
            background: var(--bg-accent);
            border-radius: 15px;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }

        table { width: 100%; border-collapse: collapse; }
        th { 
            background: #151515; 
            color: var(--white); 
            padding: 20px; 
            text-align: left; 
            font-weight: 800; 
            text-transform: uppercase; 
            letter-spacing: 1px; 
            border-bottom: 2px solid rgba(255, 255, 255, 0.1);
        }
        
        td { padding: 18px 20px; border-bottom: 1px solid rgba(255, 255, 255, 0.05); color: var(--text-gray); }
        tr:hover { background: rgba(255, 255, 255, 0.02); }
        
        .price-tag { 
            font-weight: bold; 
            color: var(--cyan); 
            text-align: right; 
            font-size: 1.1rem;
        }

        /* Contact Section */
        .contact {
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), 
                        url('https://images.unsplash.com/photo-1518770660439-4636190af475?q=80&w=2000&auto=format&fit=crop'); /* Neon Circuit Image */
            background-size: cover;
            background-position: center;
            color: var(--white);
            padding: 100px 5%;
            text-align: center;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        .location-info {
            margin: 30px 0;
            font-size: 2.5rem;
            color: var(--white);
            font-weight: 800;
            letter-spacing: -1px;
            line-height: 1.1;
        }

        .location-info span {
            color: var(--cyan);
            display: block;
            font-size: 1.2rem;
            font-weight: 400;
            letter-spacing: 3px;
            text-transform: uppercase;
            margin-top: 10px;
        }

        /* Footer */
        footer { 
            background: #000; 
            color: #444; 
            text-align: center; 
            padding: 30px; 
            font-size: 0.8rem; 
            text-transform: uppercase; 
            letter-spacing: 1px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
        }

        /* Mobile Optimization */
        @media (max-width: 768px) {
            nav ul { display: none; }
            .hero h1 { font-size: 2.2rem; }
            .location-info { font-size: 1.6rem; }
        }
    </style>
</head>
<body>

    <div class="promo-banner">
        ⚡ [DROP] Weekend Flex: 50% OFF Fri & Sat ⚡
    </div>

    <nav>
        <div class="logo">MARK <span>REPAIR</span></div>
        <ul>
            <li><a href="#home">Main</a></li>
            <li><a href="#services">Spec</a></li>
            <li><a href="#pricing">Rates</a></li>
            <li><a href="#contact">Loc</a></li>
        </ul>
    </nav>

    <section class="hero" id="home">
        <h1>Tech <span>Rituals</span> <br>Bulacan Zone</h1>
        <p>Premium fixes for Mobiles, Laptops, & PCs.</p>
    </section>

    <section class="section-padding" id="services">
        <h2 class="text-center" style="font-weight: 800; text-transform: uppercase; letter-spacing: -1px;">System capabilities</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Mobile//Tablet</h3>
                <p>Screen & battery swaps, port rescue, IC repair, and iCloud/Google Account bypass.</p>
            </div>
            <div class="service-card">
                <h3>Laptop//PC</h3>
                <p>LCD/Keyboard replacement, OS installation, motherboard repair, and data recovery.</p>
            </div>
            <div class="service-card">
                <h3>Special Ops</h3>
                <p>Water damage recovery, hinge repair, and internal fan/cooling system replacement.</p>
            </div>
        </div>
    </section>

    <section class="section-padding" id="pricing" style="background:var(--bg-accent);">
        <h2 class="text-center" style="font-weight: 800; text-transform: uppercase; letter-spacing: -1px;">RATE CARD [EST.]</h2>
        <div class="price-container">
            <table>
                <thead>
                    <tr>
                        <th>Module</th>
                        <th style="text-align: right;">Rate</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Laptop Screen Replacement</td>
                        <td class="price-tag">₱3K - ₱8K</td>
                    </tr>
                    <tr>
                        <td>Keyboard or Component Issues</td>
                        <td class="price-tag">₱2K - ₱6K</td>
                    </tr>
                    <tr>
                        <td>Laptop Hinge Repair</td>
                        <td class="price-tag">₱1.5K - ₱5K</td>
                    </tr>
                    <tr>
                        <td>Cooling Fan Repair</td>
                        <td class="price-tag">₱1K - ₱3K</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <p class="text-center" style="color: var(--magenta); font-size: 0.9rem; font-weight: 600;"><em>Activate Weekend Special for 50% OFF these rates.</em></p>
    </section>

    <section class="contact" id="contact">
        <h2>Enter the shop</h2>
        <p style="color: var(--text-gray);">Trusted neighborhood experts.</p>
        
        <div class="location-info">
            5 Golden Street, Vigan
            <span>Bulacan</span>
        </div>
        
        <div style="margin-top: 40px; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px; color: var(--text-gray);">
            <p><strong>Comms:</strong> (555) 0912-345-6789</p>
            <p><strong>Op Hours:</strong> Mon - Sat // 9:00 AM - 6:00 PM</p>
        </div>
    </section>

    <footer>
        <p>MARK REPAIR // Bulacan Sect // [EST. 2026]</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARK REPAIR | GOATED TECH 🛠️</title>
    <link href="https://fonts.googleapis.com/css2?family=Archivo+Black&family=Space+Grotesk:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        /* GEN ALPHA DESIGN SYSTEM: "THE BRAINROT UPDATE"
           Vibe: Max-Contrast, Neobrutalism, Neon-Glow
        */
        
        :root {
            --ultra-black: #050505;
            --neon-green: #00ff66;
            --neon-pink: #ff00ff;
            --neon-blue: #00d9ff;
            --neon-yellow: #f4ff00;
            --border-thick: 4px solid #000;
            --glass-bg: rgba(255, 255, 255, 0.1);
            --shadow-hard: 8px 8px 0px #000;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            cursor: crosshair; /* Very Gen Alpha / Gamer vibe */
        }

        body {
            background-color: var(--ultra-black);
            color: #fff;
            font-family: 'Space Grotesk', sans-serif;
            overflow-x: hidden;
        }

        /* --- KEY ANIMATIONS --- */
        @keyframes floating {
            0% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-15px) rotate(2deg); }
            100% { transform: translateY(0px) rotate(0deg); }
        }

        @keyframes glitch {
            0% { text-shadow: 2px 2px var(--neon-pink); }
            25% { text-shadow: -2px -2px var(--neon-blue); }
            50% { text-shadow: 2px -2px var(--neon-green); }
            100% { text-shadow: -2px 2px var(--neon-yellow); }
        }

        @keyframes rainbow-border {
            0% { border-color: var(--neon-pink); }
            33% { border-color: var(--neon-blue); }
            66% { border-color: var(--neon-green); }
            100% { border-color: var(--neon-pink); }
        }

        /* --- HEADER & PROMO --- */
        .hype-bar {
            background: var(--neon-yellow);
            color: #000;
            font-family: 'Archivo Black', sans-serif;
            padding: 12px;
            text-align: center;
            font-size: 1.2rem;
            text-transform: uppercase;
            border-bottom: var(--border-thick);
            animation: glitch 0.5s infinite;
        }

        nav {
            display: flex;
            justify-content: space-between;
            padding: 20px 5%;
            background: var(--ultra-black);
            border-bottom: var(--border-thick);
            position: sticky;
            top: 0;
            z-index: 999;
        }

        .logo {
            font-family: 'Archivo Black', sans-serif;
            font-size: 2rem;
            color: var(--neon-green);
            text-shadow: 4px 4px 0 #000;
        }

        /* --- HERO SECTION --- */
        .hero {
            height: 70vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(45deg, #0a0a0a 25%, #111 25%, #111 50%, #0a0a0a 50%, #0a0a0a 75%, #111 75%, #111 100%);
            background-size: 56px 56px;
            border-bottom: var(--border-thick);
        }

        .hero h1 {
            font-family: 'Archivo Black', sans-serif;
            font-size: clamp(3rem, 10vw, 8rem);
            line-height: 0.9;
            text-transform: uppercase;
            color: #fff;
            -webkit-text-stroke: 2px #000;
            filter: drop-shadow(8px 8px 0px var(--neon-pink));
            animation: floating 3s ease-in-out infinite;
        }

        .status-badge {
            background: var(--neon-blue);
            color: #000;
            padding: 10px 25px;
            font-weight: 800;
            border: var(--border-thick);
            box-shadow: var(--shadow-hard);
            margin-top: 20px;
            transform: rotate(-2deg);
        }

        /* --- SERVICES (THE GRID) --- */
        .container {
            padding: 80px 5%;
        }

        .section-title {
            font-family: 'Archivo Black', sans-serif;
            font-size: 3rem;
            text-align: center;
            margin-bottom: 50px;
            color: var(--neon-yellow);
            text-transform: uppercase;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .card {
            background: var(--glass-bg);
            border: var(--border-thick);
            padding: 40px;
            position: relative;
            transition: 0.3s;
            overflow: hidden;
            backdrop-filter: blur(10px);
        }

        .card:hover {
            transform: translate(-10px, -10px);
            box-shadow: 15px 15px 0px var(--neon-green);
            background: rgba(255, 255, 255, 0.15);
        }

        .card h3 {
            font-family: 'Archivo Black', sans-serif;
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: var(--neon-pink);
        }

        .card ul {
            list-style: none;
            font-weight: 500;
        }

        .card ul li::before {
            content: '🔥 ';
        }

        /* --- PRICING TABLE --- */
        .pricing-box {
            margin-top: 50px;
            background: #fff;
            color: #000;
            border: var(--border-thick);
            box-shadow: 15px 15px 0px var(--neon-blue);
            overflow: hidden;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th {
            background: #000;
            color: #fff;
            padding: 20px;
            text-align: left;
            font-family: 'Archivo Black', sans-serif;
        }

        td {
            padding: 20px;
            border-bottom: var(--border-thick);
            font-weight: 700;
        }

        .price {
            color: var(--neon-pink);
            font-family: 'Archivo Black', sans-serif;
        }

        /* --- LOCATION SECTION --- */
        .location-section {
            background: var(--neon-pink);
            color: #000;
            padding: 100px 5%;
            text-align: center;
            border-top: var(--border-thick);
            border-bottom: var(--border-thick);
        }

        .address-box {
            font-family: 'Archivo Black', sans-serif;
            font-size: clamp(1.5rem, 5vw, 4rem);
            line-height: 1;
            margin: 20px 0;
            text-transform: uppercase;
        }

        .btn-main {
            display: inline-block;
            background: #000;
            color: #fff;
            padding: 20px 50px;
            font-family: 'Archivo Black', sans-serif;
            text-decoration: none;
            border: 4px solid var(--neon-yellow);
            box-shadow: 10px 10px 0px var(--neon-blue);
            transition: 0.2s;
        }

        .btn-main:hover {
            transform: scale(1.1);
            box-shadow: 5px 5px 0px var(--neon-blue);
        }

        footer {
            padding: 40px;
            text-align: center;
            font-weight: 800;
            letter-spacing: 2px;
            color: #444;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 { font-size: 4rem; }
            nav { flex-direction: column; align-items: center; gap: 15px; }
        }
    </style>
</head>
<body>

    <div class="hype-bar">
        ⚠️ 50% OFF FRIDAY & SATURDAY IS LITERALLY GOATED ⚠️
    </div>

    <nav>
        <div class="logo">MARK REPAIR.exe</div>
        <div style="display: flex; gap: 20px;">
            <span style="color: var(--neon-blue); font-weight: 800;">[ HOME ]</span>
            <span style="color: var(--neon-pink); font-weight: 800;">[ SERVICES ]</span>
            <span style="color: var(--neon-green); font-weight: 800;">[ RATES ]</span>
        </div>
    </nav>

    <section class="hero">
        <p style="color: var(--neon-green); font-weight: 800;">// STATUS: NO CAP // BUILD: 2026 //</p>
        <h1>ULTRA<br>REPAIR</h1>
        <div class="status-badge">BULACAN'S #1 TECH SHOP</div>
    </section>

    <div class="container">
        <h2 class="section-title">THE LOADOUT 🛠️</h2>
        <div class="grid">
            <div class="card">
                <h3>MOBILE & TABLET</h3>
                <ul>
                    <li>Screen & Battery Swaps</li>
                    <li>Port Repair (W)</li>
                    <li>IC Repair</li>
                    <li>Account Bypass</li>
                </ul>
            </div>
            <div class="card">
                <h3>PC & LAPTOP</h3>
                <ul>
                    <li>LCD & Keyboards</li>
                    <li>OS Installs</li>
                    <li>Motherboard Fix</li>
                    <li>Data Recovery</li>
                </ul>
            </div>
            <div class="card">
                <h3>SPECIAL OPS</h3>
                <ul>
                    <li>Water Damage (L)</li>
                    <li>Hinge Repair</li>
                    <li>Fan Swaps</li>
                </ul>
            </div>
        </div>

        <h2 class="section-title" style="margin-top: 100px;">RATE CARD 💸</h2>
        <div class="pricing-box">
            <table>
                <thead>
                    <tr>
                        <th>SERVICE</th>
                        <th>RATES (EST)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Laptop Screen Replacement</td>
                        <td class="price">₱3,000 - ₱8,000</td>
                    </tr>
                    <tr>
                        <td>Keyboard / Components</td>
                        <td class="price">₱2,000 - ₱6,000</td>
                    </tr>
                    <tr>
                        <td>Hinge Repair</td>
                        <td class="price">₱1,500 - ₱5,000</td>
                    </tr>
                    <tr>
                        <td>Cooling Fan Repair</td>
                        <td class="price">₱1,000 - ₱3,000</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>

    <section class="location-section">
        <p>COORDINATES REVEALED:</p>
        <div class="address-box">
            5 GOLDEN STREET<br>VIGAN, BULACAN
        </div>
        <a href="#" class="btn-main">GET DIRECTIONS RN</a>
        <div style="margin-top: 30px; font-weight: 800;">
            COMMS: (555) 0912-345-6789 <br>
            VIBE CHECK: MON-SAT 9AM-6PM
        </div>
    </section>

    <footer>
        MARK REPAIR SHOP // BULACAN CHAPTER // © 2026 NO CAP
    </footer>

</body>
</html>
