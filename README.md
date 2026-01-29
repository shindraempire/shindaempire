<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Shindra Gold Empire - Premium 18K-24K Italian Gold & Diamond Jewelry. Fort Worth, TX. Visit shindraempire.com. Wholesale & Retail. Worldwide Shipping.">
    <meta property="og:url" content="https://shindraempire.com">
    <meta property="og:title" content="Shindra Gold Empire | Premium Italian Gold & Diamond Jewelry">
    <meta property="og:description" content="Legacy Built in 18K-24K Purity. Premium Italian gold jewelry in Fort Worth, TX. Wholesale & Retail. Worldwide Shipping.">
    <meta property="og:type" content="website">
    <link rel="canonical" href="https://shindraempire.com">
    <title>Shindra Gold Empire | Premium Italian Gold & Diamond Jewelry</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700;900&family=Open+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --gold-primary: #D4AF37;
            --gold-secondary: #B8860B;
            --gold-bright: #FFD700;
            --dark-bg: #0a0a0a;
            --dark-navy: #1a1a2e;
            --text-light: #f5f5f5;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        h1, h2, h3, h4 {
            font-family: 'Playfair Display', serif;
            color: var(--gold-primary);
        }

        /* Header & Navigation */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(10, 10, 10, 0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            border-bottom: 2px solid var(--gold-primary);
            box-shadow: 0 2px 20px rgba(212, 175, 55, 0.2);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 5%;
            max-width: 1400px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 900;
            color: var(--gold-primary);
            font-family: 'Playfair Display', serif;
            text-shadow: 0 0 10px rgba(212, 175, 55, 0.5);
        }

        .logo span {
            color: var(--gold-bright);
        }

        .nav-links {
            display: flex;
            gap: 2.5rem;
            list-style: none;
        }

        .nav-links a {
            color: var(--text-light);
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
            font-size: 0.95rem;
            position: relative;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--gold-primary);
            transition: width 0.3s;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .nav-links a:hover {
            color: var(--gold-primary);
        }

        .menu-toggle {
            display: none;
            flex-direction: column;
            gap: 5px;
            cursor: pointer;
        }

        .menu-toggle span {
            width: 28px;
            height: 3px;
            background: var(--gold-primary);
            transition: 0.3s;
            border-radius: 3px;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, rgba(10, 10, 10, 0.9), rgba(26, 26, 46, 0.9)), 
                        radial-gradient(circle at 30% 50%, rgba(212, 175, 55, 0.1) 0%, transparent 50%),
                        radial-gradient(circle at 70% 50%, rgba(255, 215, 0, 0.05) 0%, transparent 50%);
            background-size: cover;
            background-position: center;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(212, 175, 55, 0.03) 1px, transparent 1px);
            background-size: 50px 50px;
            animation: shimmer 20s linear infinite;
        }

        @keyframes shimmer {
            0% { transform: translate(0, 0); }
            100% { transform: translate(50px, 50px); }
        }

        .hero-content {
            z-index: 2;
            animation: fadeInUp 1s ease-out;
            max-width: 900px;
            padding: 0 2rem;
        }

        .hero h1 {
            font-size: 4.5rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
            font-weight: 900;
            letter-spacing: 2px;
        }

        .hero .tagline {
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            color: var(--gold-bright);
            font-weight: 600;
            font-family: 'Playfair Display', serif;
        }

        .hero .subtitle {
            font-size: 1.2rem;
            margin-bottom: 2.5rem;
            color: var(--text-light);
        }

        .hero-buttons {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .cta-button {
            display: inline-block;
            padding: 1.2rem 3rem;
            background: linear-gradient(135deg, var(--gold-primary), var(--gold-secondary));
            color: var(--dark-bg);
            text-decoration: none;
            font-weight: 700;
            border-radius: 50px;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.4);
            font-size: 1.1rem;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 25px rgba(212, 175, 55, 0.6);
        }

        .cta-button.secondary {
            background: transparent;
            border: 2px solid var(--gold-primary);
            color: var(--gold-primary);
        }

        .cta-button.secondary:hover {
            background: var(--gold-primary);
            color: var(--dark-bg);
        }

        /* Sections */
        section {
            padding: 6rem 5%;
            max-width: 1400px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-size: 3rem;
            margin-bottom: 3.5rem;
            position: relative;
            padding-bottom: 1.5rem;
            font-weight: 700;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 4px;
            background: linear-gradient(90deg, var(--gold-primary), var(--gold-bright), var(--gold-secondary));
            border-radius: 2px;
        }

        /* About Section */
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }

        .about-text h3 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
        }

        .about-text p {
            margin-bottom: 1.5rem;
            line-height: 1.9;
            font-size: 1.1rem;
        }

        .about-image {
            height: 450px;
            background: linear-gradient(135deg, var(--gold-primary), var(--gold-bright));
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 5rem;
            box-shadow: 0 15px 40px rgba(212, 175, 55, 0.4);
            position: relative;
            overflow: hidden;
        }

        .about-image::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.1) 0%, transparent 70%);
            animation: rotate 15s linear infinite;
        }

        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .contact-info-box {
            background: var(--dark-navy);
            padding: 2rem;
            border-radius: 10px;
            border: 2px solid var(--gold-primary);
            margin-top: 2rem;
        }

        .contact-info-box h4 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .contact-info-box p {
            margin-bottom: 0.8rem;
            font-size: 1.05rem;
        }

        .contact-info-box a {
            color: var(--gold-bright);
            text-decoration: none;
            font-weight: 600;
        }

        .contact-info-box a:hover {
            text-decoration: underline;
        }

        /* Products Grid */
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 2.5rem;
        }

        .product-card {
            background: var(--dark-navy);
            border-radius: 15px;
            overflow: hidden;
            transition: all 0.3s;
            border: 2px solid rgba(212, 175, 55, 0.2);
            position: relative;
        }

        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(212, 175, 55, 0.5);
            border-color: var(--gold-primary);
        }

        .product-image {
            height: 350px;
            background: var(--dark-bg);
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            position: relative;
        }

        .product-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }

        .product-card:hover .product-image img {
            transform: scale(1.05);
        }

        .product-badge {
            position: absolute;
            top: 15px;
            right: 15px;
            background: var(--gold-primary);
            color: var(--dark-bg);
            padding: 0.5rem 1rem;
            border-radius: 25px;
            font-weight: 700;
            font-size: 0.85rem;
            box-shadow: 0 2px 10px rgba(212, 175, 55, 0.5);
        }

        .product-info {
            padding: 2rem;
        }

        .product-info h3 {
            font-size: 1.6rem;
            margin-bottom: 0.8rem;
        }

        .product-weight {
            color: var(--gold-bright);
            font-weight: 600;
            font-size: 1.1rem;
            margin-bottom: 0.8rem;
        }

        .product-info p {
            color: rgba(245, 245, 245, 0.8);
            margin-bottom: 1.5rem;
            line-height: 1.7;
        }

        .product-buttons {
            display: flex;
            gap: 1rem;
        }

        .btn-price {
            flex: 1;
            padding: 0.9rem;
            background: linear-gradient(135deg, var(--gold-primary), var(--gold-secondary));
            color: var(--dark-bg);
            border: none;
            border-radius: 8px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 0.95rem;
        }

        .btn-price:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.5);
        }

        .btn-whatsapp {
            padding: 0.9rem 1.5rem;
            background: #25D366;
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .btn-whatsapp:hover {
            background: #128C7E;
            transform: translateY(-2px);
        }

        /* Features Grid */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2.5rem;
            margin-top: 2rem;
        }

        .feature-box {
            text-align: center;
            padding: 2.5rem;
            background: var(--dark-navy);
            border-radius: 15px;
            border: 2px solid rgba(212, 175, 55, 0.2);
            transition: all 0.3s;
        }

        .feature-box:hover {
            transform: translateY(-8px);
            border-color: var(--gold-primary);
            box-shadow: 0 10px 30px rgba(212, 175, 55, 0.3);
        }

        .feature-icon {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
        }

        .feature-box h3 {
            font-size: 1.4rem;
            margin-bottom: 0.8rem;
        }

        .feature-box p {
            color: rgba(245, 245, 245, 0.8);
            line-height: 1.7;
        }

        /* Testimonials */
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2.5rem;
            margin-top: 2rem;
        }

        .testimonial-card {
            background: var(--dark-navy);
            padding: 2.5rem;
            border-radius: 15px;
            border: 2px solid rgba(212, 175, 55, 0.2);
            position: relative;
        }

        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: -20px;
            left: 20px;
            font-size: 6rem;
            color: var(--gold-primary);
            font-family: 'Playfair Display', serif;
            opacity: 0.3;
        }

        .testimonial-text {
            font-size: 1.1rem;
            line-height: 1.8;
            margin-bottom: 1.5rem;
            font-style: italic;
        }

        .testimonial-author {
            color: var(--gold-primary);
            font-weight: 700;
            font-size: 1.1rem;
        }

        .testimonial-location {
            color: rgba(245, 245, 245, 0.6);
            font-size: 0.95rem;
        }

        /* Contact Form */
        .contact-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
        }

        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 1.8rem;
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        .form-group label {
            margin-bottom: 0.7rem;
            color: var(--gold-primary);
            font-weight: 600;
            font-size: 1.05rem;
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            padding: 1rem;
            background: rgba(26, 26, 46, 0.8);
            border: 2px solid rgba(212, 175, 55, 0.3);
            border-radius: 8px;
            color: var(--text-light);
            font-family: 'Open Sans', sans-serif;
            transition: all 0.3s;
            font-size: 1rem;
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--gold-primary);
            box-shadow: 0 0 10px rgba(212, 175, 55, 0.3);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 150px;
        }

        .submit-btn {
            padding: 1.2rem 2.5rem;
            background: linear-gradient(135deg, var(--gold-primary), var(--gold-secondary));
            color: var(--dark-bg);
            border: none;
            border-radius: 50px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 1.1rem;
        }

        .submit-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(212, 175, 55, 0.5);
        }

        .contact-info {
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }

        .info-box {
            padding: 2rem;
            background: var(--dark-navy);
            border-radius: 12px;
            border: 2px solid rgba(212, 175, 55, 0.2);
        }

        .info-box h3 {
            font-size: 1.4rem;
            margin-bottom: 1.2rem;
        }

        .info-box p {
            margin-bottom: 0.7rem;
            font-size: 1.05rem;
        }

        .info-box a {
            color: var(--gold-primary);
            text-decoration: none;
            font-weight: 600;
        }

        .info-box a:hover {
            color: var(--gold-bright);
            text-decoration: underline;
        }

        .social-links {
            display: flex;
            gap: 1.2rem;
            margin-top: 1.2rem;
        }

        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background: var(--gold-primary);
            color: var(--dark-bg);
            border-radius: 50%;
            font-size: 1.5rem;
            transition: all 0.3s;
            text-decoration: none;
        }

        .social-links a:hover {
            transform: scale(1.15);
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.5);
        }

        /* Policy Notice */
        .policy-notice {
            background: rgba(184, 134, 11, 0.15);
            border: 2px solid var(--gold-secondary);
            border-radius: 15px;
            padding: 2.5rem;
            margin: 3rem 0;
            text-align: center;
        }

        .policy-notice h3 {
            font-size: 1.8rem;
            margin-bottom: 1.2rem;
        }

        .policy-notice p {
            font-size: 1.15rem;
            line-height: 1.9;
        }

        /* Footer */
        footer {
            background: var(--dark-navy);
            padding: 4rem 5% 2rem;
            border-top: 3px solid var(--gold-primary);
        }

        .footer-content {
            max-width: 1400px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 3rem;
        }

        .footer-section h3 {
            margin-bottom: 1.5rem;
            font-size: 1.5rem;
        }

        .footer-section ul {
            list-style: none;
        }

        .footer-section ul li {
            margin-bottom: 0.8rem;
        }

        .footer-section a {
            color: var(--text-light);
            text-decoration: none;
            transition: color 0.3s;
            font-size: 1.05rem;
        }

        .footer-section a:hover {
            color: var(--gold-primary);
        }

        .footer-bottom {
            text-align: center;
            margin-top: 3rem;
            padding-top: 2rem;
            border-top: 1px solid rgba(212, 175, 55, 0.3);
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .fade-in {
            opacity: 0;
            animation: fadeInUp 0.8s ease-out forwards;
        }

        /* Responsive Design */
        @media (max-width: 968px) {
            .about-content,
            .contact-content {
                grid-template-columns: 1fr;
            }

            .products-grid {
                grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            }
        }

        @media (max-width: 768px) {
            .menu-toggle {
                display: flex;
            }

            .nav-links {
                position: fixed;
                top: 75px;
                right: -100%;
                flex-direction: column;
                background: rgba(10, 10, 10, 0.98);
                width: 100%;
                padding: 2rem;
                transition: right 0.3s;
                border-top: 2px solid var(--gold-primary);
                gap: 1.5rem;
            }

            .nav-links.active {
                right: 0;
            }

            .hero h1 {
                font-size: 3rem;
            }

            .hero .tagline {
                font-size: 1.2rem;
            }

            .hero .subtitle {
                font-size: 1rem;
            }

            .section-title {
                font-size: 2.2rem;
            }

            section {
                padding: 4rem 5%;
            }

            .hero-buttons {
                flex-direction: column;
            }

            .testimonials-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <div class="logo">✨ Shindra <span>Gold Empire</span></div>
            <div class="menu-toggle" onclick="toggleMenu()">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <ul class="nav-links" id="navLinks">
                <li><a href="#home" onclick="closeMenu()">Home</a></li>
                <li><a href="#about" onclick="closeMenu()">About</a></li>
                <li><a href="#products" onclick="closeMenu()">Products</a></li>
                <li><a href="#testimonials" onclick="closeMenu()">Testimonials</a></li>
                <li><a href="#contact" onclick="closeMenu()">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Shindra Gold Empire</h1>
            <p class="tagline">Legacy Built in 18K-24K Purity</p>
            <p class="subtitle">Strictly New Gold Worldwide | Premium Italian Craftsmanship</p>
            <div class="hero-buttons">
                <a href="#products" class="cta-button">Shop Collection</a>
                <a href="http://api.whatsapp.com/send?phone=12146098182" class="cta-button secondary" target="_blank">WhatsApp Us</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2 class="section-title">About Shindra Gold Empire</h2>
        <div class="about-content">
            <div class="about-text fade-in">
                <h3>Excellence in Every Detail</h3>
                <p>Welcome to Shindra Gold Empire, your premier destination for luxury Italian gold jewelry in Fort Worth, Texas. We specialize in premium 18K-24K gold and diamond collections that embody timeless elegance and superior craftsmanship.</p>
                <p>Our commitment to quality ensures that every piece is crafted with precision and passion. We offer both wholesale and retail options, making luxury accessible to discerning customers worldwide.</p>
                <p><strong>New Gold Only</strong> - We exclusively deal in brand new, certified gold jewelry, ensuring you receive only the finest quality pieces with guaranteed authenticity.</p>
                
                <div class="contact-info-box">
                    <h4>📍 Visit Us</h4>
                    <p><strong>5041 Saunders Rd Ste 155</strong></p>
                    <p>Fort Worth, TX 76119</p>
                    <p style="margin-top: 1rem;">📧 <a href="mailto:contactshindraempire@gmail.com">contactshindraempire@gmail.com</a></p>
                    <p>📱 <a href="tel:+12146098182">+1 (214) 609-8182</a></p>
                </div>
            </div>
            <div class="about-image fade-in">
                💎
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products">
        <h2 class="section-title">Our Premium Collection</h2>
        <div class="products-grid" id="productsGrid">
            <!-- Products will be loaded here -->
        </div>
    </section>

    <!-- Features Section -->
    <section id="features">
        <h2 class="section-title">Why Choose Shindra Gold Empire</h2>
        <div class="features-grid">
            <div class="feature-box fade-in">
                <div class="feature-icon">🌟</div>
                <h3>Premium Quality</h3>
                <p>18K-24K Italian gold with certified authenticity. Only the finest materials and craftsmanship.</p>
            </div>
            <div class="feature-box fade-in">
                <div class="feature-icon">🌍</div>
                <h3>Worldwide Shipping</h3>
                <p>Secure, insured delivery to your doorstep anywhere in the world. Professional packaging guaranteed.</p>
            </div>
            <div class="feature-box fade-in">
                <div class="feature-icon">🏪</div>
                <h3>Wholesale & Retail</h3>
                <p>Competitive pricing for both individual buyers and bulk orders. Special rates for wholesalers.</p>
            </div>
            <div class="feature-box fade-in">
                <div class="feature-icon">✅</div>
                <h3>Certified Authentic</h3>
                <p>Every piece comes with authenticity certification and hallmarking for your peace of mind.</p>
            </div>
            <div class="feature-box fade-in">
                <div class="feature-icon">🆕</div>
                <h3>New Gold Only</h3>
                <p>We deal exclusively in brand new jewelry - never pre-owned or recycled gold.</p>
            </div>
            <div class="feature-box fade-in">
                <div class="feature-icon">💰</div>
                <h3>Current Gold Rates</h3>
                <p>Prices based on current market rates. Contact us for today's pricing on any piece.</p>
            </div>
        </div>

        <!-- Policy Notice -->
        <div class="policy-notice fade-in">
            <h3>⚠️ Important Policy Notice</h3>
            <p><strong>No Exchange or Refund Policy</strong></p>
            <p>All sales are final. We do not offer exchanges or refunds on any purchases. Please ensure you review all product details and specifications carefully before placing your order. Our team is available to answer any questions prior to purchase.</p>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <h2 class="section-title">What Our Customers Say</h2>
        <div class="testimonials-grid">
            <div class="testimonial-card fade-in">
                <p class="testimonial-text">Beautiful craftsmanship! The quality of the gold is exceptional and exactly as described. Very professional service from start to finish.</p>
                <p class="testimonial-author">Sarah M.</p>
                <p class="testimonial-location">Dallas, TX</p>
            </div>
            <div class="testimonial-card fade-in">
                <p class="testimonial-text">Affordable price and trusted. I've purchased multiple pieces and each one exceeds my expectations. Highly recommended for quality Italian gold!</p>
                <p class="testimonial-author">Jubril Adams</p>
                <p class="testimonial-location">Chicago, IL</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2 class="section-title">Contact Us</h2>
        <div class="contact-content">
            <form class="contact-form fade-in" onsubmit="handleSubmit(event)">
                <div class="form-group">
                    <label for="name">Full Name *</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address *</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone">
                </div>
                <div class="form-group">
                    <label for="inquiry">Inquiry Type *</label>
                    <select id="inquiry" name="inquiry" required>
                        <option value="">Select...</option>
                        <option value="retail">Retail Purchase</option>
                        <option value="wholesale">Wholesale Inquiry</option>
                        <option value="pricing">Price Quote</option>
                        <option value="general">General Question</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="message">Message *</label>
                    <textarea id="message" name="message" required></textarea>
                </div>
                <button type="submit" class="submit-btn">Send Inquiry</button>
            </form>

            <div class="contact-info fade-in">
                <div class="info-box">
                    <h3>📧 Email</h3>
                    <p><a href="mailto:contactshindraempire@gmail.com">contactshindraempire@gmail.com</a></p>
                </div>
                <div class="info-box">
                    <h3>📱 Phone & WhatsApp</h3>
                    <p><a href="tel:+12146098182">+1 (214) 609-8182</a></p>
                    <p><a href="http://api.whatsapp.com/send?phone=12146098182" target="_blank">Chat on WhatsApp</a></p>
                </div>
                <div class="info-box">
                    <h3>📍 Location</h3>
                    <p><strong>5041 Saunders Rd Ste 155</strong></p>
                    <p>Fort Worth, TX 76119</p>
                </div>
                <div class="info-box">
                    <h3>🌐 Follow Us</h3>
                    <div class="social-links">
                        <a href="https://www.tiktok.com/@shindra_goldempire" target="_blank" title="TikTok">🎵</a>
                        <a href="http://api.whatsapp.com/send?phone=12146098182" target="_blank" title="WhatsApp">💬</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>Shindra Gold Empire</h3>
                <p>Premium 18K-24K Italian gold and diamond jewelry. Serving Fort Worth and customers worldwide.</p>
                <p style="margin-top: 1.5rem; color: var(--gold-primary); font-weight: 600;">✨ Legacy Built in 18K-24K Purity ✨</p>
            </div>
            <div class="footer-section">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Services</h3>
                <ul>
                    <li><a href="#products">Retail Sales</a></li>
                    <li><a href="#products">Wholesale Orders</a></li>
                    <li><a href="#contact">Price Quotes</a></li>
                    <li><a href="#features">Worldwide Shipping</a></li>
                    <li><a href="#features">Authenticity Certificates</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Contact</h3>
                <ul>
                    <li><a href="mailto:contactshindraempire@gmail.com">contactshindraempire@gmail.com</a></li>
                    <li><a href="tel:+12146098182">+1 (214) 609-8182</a></li>
                    <li><a href="http://api.whatsapp.com/send?phone=12146098182" target="_blank">WhatsApp Chat</a></li>
                    <li>5041 Saunders Rd Ste 155, Fort Worth, TX</li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 Shindra Gold Empire. All Rights Reserved.</p>
            <p style="margin-top: 0.8rem; font-size: 0.95rem;">Premium Italian Gold & Diamond Jewelry | 18K-24K | Worldwide Shipping</p>
        </div>
    </footer>

    <script>
        // Products Data
        const products = [
            {
                id: 1,
                name: "Tri-Tone Heart Jewelry Set",
                weight: "61g",
                description: "Exquisite complete set featuring necklace, earrings, ring and bracelet in tri-tone gold (yellow, white, rose). Stunning heart designs throughout.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_30_AM__1_.jpeg",
                badge: "Complete Set"
            },
            {
                id: 2,
                name: "Geometric Tri-Tone Luxury Set",
                weight: "84.1g",
                description: "Bold geometric design set with necklace, earrings and bracelet in tri-tone finish. Perfect statement pieces for special occasions.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_30_AM.jpeg",
                badge: "Luxury Set"
            },
            {
                id: 3,
                name: "Golden Heart Collection Set",
                weight: "53g (37.7g necklace + 15.3g earrings)",
                description: "Beautiful beaded necklace with heart pendant and matching heart earrings in premium gold finish.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__1_.jpeg",
                badge: "Best Seller"
            },
            {
                id: 4,
                name: "White Gold Heart Pendant Set",
                weight: "10.5g (5.9g necklace + 4.6g earrings)",
                description: "Elegant white gold heart pendant necklace with matching heart stud earrings. Delicate and timeless design.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__2_.jpeg",
                badge: "Elegant"
            },
            {
                id: 5,
                name: "Heart Jewelry Set with Rings",
                weight: "10.3g",
                description: "Sophisticated set featuring heart-themed bracelet and matching rings. Perfect for everyday luxury.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__3_.jpeg",
                badge: "New"
            },
            {
                id: 6,
                name: "Pineapple Design Jewelry Set",
                weight: "9.8g",
                description: "Unique pineapple-themed bracelet and rings set. Textured gold finish with intricate detailing.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__4_.jpeg",
                badge: "Unique"
            },
            {
                id: 7,
                name: "Triple Heart Drop Earrings - Gold",
                weight: "9.8g",
                description: "Stunning cascading heart earrings in polished yellow gold. Statement pieces that catch the light beautifully.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__5_.jpeg",
                badge: "Statement"
            },
            {
                id: 8,
                name: "Tri-Color Triple Heart Earrings",
                weight: "9.6g",
                description: "Beautiful tri-tone cascading heart earrings featuring rose, yellow, and white gold finishes.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__6_.jpeg",
                badge: "Tri-Tone"
            },
            {
                id: 9,
                name: "Gold Leaf Hoop Earrings",
                weight: "7g",
                description: "Elegant textured leaf design hoop earrings in lustrous gold. Perfect balance of classic and contemporary.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__7_.jpeg",
                badge: "Classic"
            },
            {
                id: 10,
                name: "Tri-Tone Leaf Hoop Earrings",
                weight: "7.2g",
                description: "Sophisticated leaf design hoops in tri-tone finish. Artistic and eye-catching design.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__8_.jpeg",
                badge: "Artistic"
            },
            {
                id: 11,
                name: "Gold Flower Stud Earrings",
                weight: "8.3g",
                description: "Delicate flower petal design earrings in radiant yellow gold. Feminine and elegant.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__9_.jpeg",
                badge: "Feminine"
            },
            {
                id: 12,
                name: "Tri-Tone Flower Stud Earrings",
                weight: "8.4g",
                description: "Beautiful flower petal earrings featuring rose, yellow, and white gold tones. Sophisticated elegance.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__10_.jpeg",
                badge: "Elegant"
            },
            {
                id: 13,
                name: "White Gold Heart Pendant Set",
                weight: "9.7g (5.1g necklace + 4.6g earrings)",
                description: "Refined white gold heart necklace and earring set. Perfect for special occasions or daily wear.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM__11_.jpeg",
                badge: "Premium"
            },
            {
                id: 14,
                name: "Golden Beaded Heart Set",
                weight: "37g (28.6g necklace + 8.4g earrings)",
                description: "Luxurious beaded necklace with heart pendant and matching heart earrings. Statement piece collection.",
                image: "WhatsApp_Image_2026-01-29_at_12_18_31_AM.jpeg",
                badge: "Luxury"
            }
        ];

        // Load Products
        function loadProducts() {
            const grid = document.getElementById('productsGrid');
            grid.innerHTML = products.map(product => `
                <div class="product-card fade-in">
                    <div class="product-image">
                        <img src="${product.image}" alt="${product.name}">
                        <div class="product-badge">${product.badge}</div>
                    </div>
                    <div class="product-info">
                        <h3>${product.name}</h3>
                        <p class="product-weight">Weight: ${product.weight}</p>
                        <p>${product.description}</p>
                        <div class="product-buttons">
                            <button class="btn-price" onclick="contactForPrice('${product.name}')">Contact for Price</button>
                            <a href="http://api.whatsapp.com/send?phone=12146098182&text=Hi! I'm interested in ${encodeURIComponent(product.name)} (${product.weight})" class="btn-whatsapp" target="_blank">💬</a>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // Contact for Price
        function contactForPrice(productName) {
            window.location.href = `mailto:contactshindraempire@gmail.com?subject=Price Inquiry: ${productName}&body=Hello, I would like to know the current price for ${productName}. Thank you!`;
        }

        // Mobile Menu Toggle
        function toggleMenu() {
            const navLinks = document.getElementById('navLinks');
            navLinks.classList.toggle('active');
        }

        function closeMenu() {
            const navLinks = document.getElementById('navLinks');
            navLinks.classList.remove('active');
        }

        // Form Submission
        function handleSubmit(event) {
            event.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const inquiry = document.getElementById('inquiry').value;
            const message = document.getElementById('message').value;
            
            const subject = `Inquiry from ${name} - ${inquiry}`;
            const body = `Name: ${name}\nEmail: ${email}\nInquiry Type: ${inquiry}\n\nMessage:\n${message}`;
            
            window.location.href = `mailto:contactshindraempire@gmail.com?subject=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;
            
            alert(`Thank you, ${name}! Your inquiry will be sent via your email client.\n\n✨ Shindra Gold Empire appreciates your interest!`);
        }

        // Fade-in animation on scroll
        function revealOnScroll() {
            const fadeElements = document.querySelectorAll('.fade-in');
            
            fadeElements.forEach(element => {
                const elementTop = element.getBoundingClientRect().top;
                const windowHeight = window.innerHeight;
                
                if (elementTop < windowHeight - 100) {
                    element.style.opacity = '1';
                    element.style.animation = 'fadeInUp 0.8s ease-out forwards';
                }
            });
        }

        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    const offsetTop = target.offsetTop - 80;
                    window.scrollTo({
                        top: offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Header background on scroll
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            if (window.scrollY > 50) {
                header.style.background = 'rgba(10, 10, 10, 0.98)';
            } else {
                header.style.background = 'rgba(10, 10, 10, 0.95)';
            }
            revealOnScroll();
        });

        // Initialize
        window.addEventListener('load', function() {
            loadProducts();
            revealOnScroll();
        });
    </script>
</body>
</html>
