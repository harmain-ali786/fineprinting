# fineprinting <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FinePrinting | Premium Perfume Box Printing UAE</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* CSS Reset and Base Styles */
        :root {
            --primary: #0a0a0a;
            --secondary: #d4af37;
            --accent: #1a237e;
            --light: #ffffff;
            --dark: #121212;
            --gray: #f5f5f5;
            --transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            color: var(--primary);
            background-color: var(--light);
            overflow-x: hidden;
            line-height: 1.6;
        }

        h1, h2, h3, h4, h5, h6 {
            font-family: 'Playfair Display', serif;
            font-weight: 600;
            line-height: 1.2;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        ul {
            list-style: none;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: var(--secondary);
            color: var(--primary);
            border: none;
            border-radius: 4px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            cursor: pointer;
            transition: var(--transition);
            position: relative;
            overflow: hidden;
            z-index: 1;
        }

        .btn:before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: 0.5s;
            z-index: -1;
        }

        .btn:hover:before {
            left: 100%;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .btn-secondary {
            background-color: transparent;
            border: 2px solid var(--secondary);
            color: var(--secondary);
        }

        .btn-secondary:hover {
            background-color: var(--secondary);
            color: var(--primary);
        }

        .section {
            padding: 100px 0;
            position: relative;
        }

        .section-title {
            font-size: 2.5rem;
            margin-bottom: 30px;
            position: relative;
            display: inline-block;
        }

        .section-title:after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 60px;
            height: 3px;
            background-color: var(--secondary);
        }

        .text-center {
            text-align: center;
        }

        .text-center .section-title:after {
            left: 50%;
            transform: translateX(-50%);
        }

        /* Header Styles */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 20px 0;
            z-index: 1000;
            transition: var(--transition);
        }

        header.scrolled {
            background-color: rgba(10, 10, 10, 0.95);
            padding: 15px 0;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--secondary);
            font-family: 'Playfair Display', serif;
        }

        .logo span {
            color: var(--light);
        }

        .nav-links {
            display: flex;
            gap: 30px;
        }

        .nav-links a {
            color: var(--light);
            font-weight: 500;
            position: relative;
            padding: 5px 0;
        }

        .nav-links a:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background-color: var(--secondary);
            transition: var(--transition);
        }

        .nav-links a:hover:after {
            width: 100%;
        }

        .hamburger {
            display: none;
            cursor: pointer;
            width: 30px;
            height: 20px;
            position: relative;
            z-index: 1001;
        }

        .hamburger span {
            display: block;
            width: 100%;
            height: 2px;
            background-color: var(--light);
            position: absolute;
            left: 0;
            transition: var(--transition);
        }

        .hamburger span:nth-child(1) {
            top: 0;
        }

        .hamburger span:nth-child(2) {
            top: 50%;
            transform: translateY(-50%);
        }

        .hamburger span:nth-child(3) {
            bottom: 0;
        }

        .hamburger.active span:nth-child(1) {
            top: 50%;
            transform: translateY(-50%) rotate(45deg);
        }

        .hamburger.active span:nth-child(2) {
            opacity: 0;
        }

        .hamburger.active span:nth-child(3) {
            bottom: 50%;
            transform: translateY(50%) rotate(-45deg);
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            min-height: 700px;
            background: linear-gradient(rgba(10, 10, 10, 0.7), rgba(10, 10, 10, 0.7)), url('https://images.unsplash.com/photo-1594035910387-fea47794261f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1480&q=80') no-repeat center center/cover;
            color: var(--light);
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
        }

        .hero-content {
            max-width: 600px;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            line-height: 1.1;
        }

        .hero p {
            font-size: 1.1rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .hero-btns {
            display: flex;
            gap: 20px;
        }

        .model-viewer-container {
            position: absolute;
            right: -100px;
            top: 50%;
            transform: translateY(-50%);
            width: 600px;
            height: 600px;
            background: rgba(255,255,255,0.1);
            border-radius: 50%;
            backdrop-filter: blur(10px);
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .model-viewer {
            width: 100%;
            height: 100%;
        }

        /* About Section */
        .about {
            background-color: var(--gray);
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
            align-items: center;
        }

        .about-image {
            position: relative;
            height: 500px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 20px 30px rgba(0,0,0,0.1);
        }

        .about-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }

        .about-image:hover img {
            transform: scale(1.05);
        }

        .about-text h2 {
            margin-bottom: 20px;
        }

        .about-text p {
            margin-bottom: 20px;
        }

        /* Services Section */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

        .service-card {
            background-color: var(--light);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            transition: var(--transition);
            position: relative;
            z-index: 1;
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.1);
        }

        .service-card:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, var(--secondary), var(--accent));
            opacity: 0;
            transition: var(--transition);
            z-index: -1;
        }

        .service-card:hover:before {
            opacity: 0.1;
        }

        .service-img {
            height: 200px;
            overflow: hidden;
        }

        .service-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }

        .service-card:hover .service-img img {
            transform: scale(1.1);
        }

        .service-content {
            padding: 25px;
        }

        .service-content h3 {
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        /* Portfolio Section */
        .portfolio {
            background-color: var(--gray);
        }

        .portfolio-filter {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 40px;
        }

        .filter-btn {
            padding: 8px 20px;
            background-color: transparent;
            border: 1px solid var(--primary);
            border-radius: 30px;
            cursor: pointer;
            transition: var(--transition);
        }

        .filter-btn.active, .filter-btn:hover {
            background-color: var(--secondary);
            border-color: var(--secondary);
            color: var(--primary);
        }

        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 30px;
        }

        .portfolio-item {
            position: relative;
            border-radius: 10px;
            overflow: hidden;
            height: 300px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .portfolio-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }

        .portfolio-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to bottom, rgba(212, 175, 55, 0.8), rgba(26, 35, 126, 0.8));
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            opacity: 0;
            transition: var(--transition);
        }

        .portfolio-item:hover .portfolio-overlay {
            opacity: 1;
        }

        .portfolio-item:hover .portfolio-img {
            transform: scale(1.1);
        }

        .portfolio-overlay h3 {
            color: var(--light);
            font-size: 1.5rem;
            margin-bottom: 10px;
            transform: translateY(20px);
            transition: var(--transition);
        }

        .portfolio-overlay p {
            color: var(--light);
            transform: translateY(20px);
            transition: var(--transition);
            transition-delay: 0.1s;
        }

        .portfolio-item:hover .portfolio-overlay h3,
        .portfolio-item:hover .portfolio-overlay p {
            transform: translateY(0);
        }

        /* Pricing Calculator */
        .calculator {
            background-color: var(--accent);
            color: var(--light);
            padding: 50px;
            border-radius: 10px;
            margin-top: 50px;
        }

        .calculator h3 {
            margin-bottom: 30px;
            font-size: 1.8rem;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 10px;
            font-weight: 500;
        }

        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: none;
            border-radius: 4px;
            background-color: rgba(255,255,255,0.1);
            color: var(--light);
            font-size: 1rem;
        }

        .form-control:focus {
            outline: 2px solid var(--secondary);
        }

        .range-slider {
            width: 100%;
            height: 8px;
            -webkit-appearance: none;
            background: rgba(255,255,255,0.2);
            border-radius: 10px;
            outline: none;
            margin-top: 10px;
        }

        .range-slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: var(--secondary);
            cursor: pointer;
            transition: var(--transition);
        }

        .range-slider::-webkit-slider-thumb:hover {
            transform: scale(1.2);
        }

        .calculator-result {
            background-color: rgba(0,0,0,0.2);
            padding: 20px;
            border-radius: 5px;
            margin-top: 30px;
        }

        .calculator-result h4 {
            margin-bottom: 15px;
            font-size: 1.3rem;
        }

        .total-price {
            font-size: 2rem;
            font-weight: 700;
            color: var(--secondary);
        }

        /* Contact Section */
        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 50px;
        }

        .contact-info h3 {
            margin-bottom: 20px;
        }

        .contact-details {
            margin-bottom: 30px;
        }

        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }

        .contact-icon {
            width: 50px;
            height: 50px;
            background-color: var(--secondary);
            color: var(--primary);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-right: 15px;
            font-size: 1.2rem;
        }

        .contact-text h4 {
            margin-bottom: 5px;
        }

        .contact-form .form-group {
            margin-bottom: 25px;
        }

        .form-floating {
            position: relative;
        }

        .form-floating label {
            position: absolute;
            top: 15px;
            left: 15px;
            color: var(--primary);
            transition: var(--transition);
            pointer-events: none;
        }

        .form-floating input:focus + label,
        .form-floating textarea:focus + label,
        .form-floating input:not(:placeholder-shown) + label,
        .form-floating textarea:not(:placeholder-shown) + label {
            top: -10px;
            left: 10px;
            font-size: 0.8rem;
            background-color: var(--light);
            padding: 0 5px;
            color: var(--secondary);
        }

        .form-floating input,
        .form-floating textarea {
            width: 100%;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
        }

        .form-floating textarea {
            min-height: 150px;
            resize: vertical;
        }

        .map-container {
            height: 400px;
            margin-top: 50px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        /* Footer */
        footer {
            background-color: var(--dark);
            color: var(--light);
            padding: 80px 0 30px;
        }

        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 50px;
        }

        .footer-col h3 {
            margin-bottom: 25px;
            font-size: 1.3rem;
            position: relative;
            display: inline-block;
        }

        .footer-col h3:after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 40px;
            height: 2px;
            background-color: var(--secondary);
        }

        .footer-col p {
            margin-bottom: 20px;
            opacity: 0.8;
        }

        .footer-links li {
            margin-bottom: 15px;
        }

        .footer-links a {
            opacity: 0.8;
            transition: var(--transition);
        }

        .footer-links a:hover {
            opacity: 1;
            color: var(--secondary);
            padding-left: 5px;
        }

        .social-links {
            display: flex;
            gap: 15px;
        }

        .social-link {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: rgba(255,255,255,0.1);
            display: flex;
            justify-content: center;
            align-items: center;
            transition: var(--transition);
        }

        .social-link:hover {
            background-color: var(--secondary);
            color: var(--primary);
            transform: translateY(-5px);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255,255,255,0.1);
        }

        /* Fixed CTA Buttons */
        .fixed-cta {
            position: fixed;
            bottom: 30px;
            right: 30px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            z-index: 999;
        }

        .whatsapp-cta {
            background-color: #25D366;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.8rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: var(--transition);
        }

        .whatsapp-cta:hover {
            transform: scale(1.1);
        }

        .quote-cta {
            background-color: var(--secondary);
            color: var(--primary);
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.5rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: var(--transition);
        }

        .quote-cta:hover {
            transform: scale(1.1);
        }

        /* Animation Classes */
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .scale-in {
            opacity: 0;
            transform: scale(0.8);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }

        .scale-in.visible {
            opacity: 1;
            transform: scale(1);
        }

        /* Responsive Styles */
        @media (max-width: 1200px) {
            .model-viewer-container {
                right: -200px;
                width: 500px;
                height: 500px;
            }
        }

        @media (max-width: 992px) {
            .section {
                padding: 80px 0;
            }

            .hero h1 {
                font-size: 3rem;
            }

            .about-content {
                grid-template-columns: 1fr;
            }

            .about-image {
                height: 400px;
            }

            .contact-container {
                grid-template-columns: 1fr;
            }

            .model-viewer-container {
                display: none;
            }

            .hero-content {
                max-width: 100%;
                text-align: center;
            }

            .hero-btns {
                justify-content: center;
            }
        }

        @media (max-width: 768px) {
            .section {
                padding: 60px 0;
            }

            .section-title {
                font-size: 2rem;
            }

            .nav-links {
                position: fixed;
                top: 0;
                right: -100%;
                width: 80%;
                max-width: 300px;
                height: 100vh;
                background-color: var(--dark);
                flex-direction: column;
                justify-content: center;
                align-items: center;
                transition: var(--transition);
                z-index: 1000;
            }

            .nav-links.active {
                right: 0;
            }

            .hamburger {
                display: block;
            }

            .portfolio-grid {
                grid-template-columns: 1fr;
            }

            .footer-container {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 576px) {
            .hero h1 {
                font-size: 2.5rem;
            }

            .hero-btns {
                flex-direction: column;
                gap: 15px;
            }

            .btn {
                width: 100%;
                text-align: center;
            }

            .calculator {
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header id="header">
        <div class="container header-container">
            <a href="#" class="logo">Fine<span>Printing</span></a>
            <nav>
                <div class="hamburger">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content fade-in">
                <h1>Premium Perfume Box Printing in UAE</h1>
                <p>Elevate your brand with our exquisite custom perfume packaging solutions. Luxury designs, impeccable craftsmanship, and attention to detail that sets your product apart.</p>
                <div class="hero-btns">
                    <a href="#contact" class="btn">Get a Quote</a>
                    <a href="#portfolio" class="btn btn-secondary">View Portfolio</a>
                </div>
            </div>
            <div class="model-viewer-container scale-in">
                <!-- 3D Model Viewer Placeholder - Would use model-viewer or similar in production -->
                <div class="model-viewer" id="perfume-box-model">
                    <img src="https://images.unsplash.com/photo-1594035910387-fea47794261f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=880&q=80" alt="Luxury Perfume Box">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section about" id="about">
        <div class="container">
            <div class="about-content">
                <div class="about-image fade-in">
                    <img src="https://images.unsplash.com/photo-1605733513597-a8f83490f9b8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="FinePrinting Team">
                </div>
                <div class="about-text fade-in">
                    <h2 class="section-title">About FinePrinting</h2>
                    <p>Founded by a Pakistani entrepreneur in the heart of UAE, FinePrinting has established itself as a leader in premium perfume box printing. Our journey began with a passion for exquisite packaging and a commitment to quality that reflects the luxury of the fragrances within.</p>
                    <p>With state-of-the-art printing technology and a team of skilled artisans, we bring your packaging vision to life. Every box we create tells a story of craftsmanship, elegance, and attention to detail.</p>
                    <p>Our mission is to provide packaging solutions that not only protect your product but elevate your brand and create an unforgettable unboxing experience for your customers.</p>
                    <a href="#services" class="btn">Our Services</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="section" id="services">
        <div class="container">
            <div class="text-center fade-in">
                <h2 class="section-title">Our Premium Services</h2>
                <p>We offer a complete range of luxury packaging solutions tailored to your brand's unique identity</p>
            </div>
            <div class="services-grid">
                <div class="service-card fade-in">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1600857544200-b2f666a9a2ec?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Custom Box Printing">
                    </div>
                    <div class="service-content">
                        <h3>Custom Box Printing</h3>
                        <p>Fully customized perfume box designs printed with high-resolution quality on premium materials to match your brand aesthetic.</p>
                    </div>
                </div>
                <div class="service-card fade-in">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1605733511310-0bbfabc1b0b3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Foil Stamping">
                    </div>
                    <div class="service-content">
                        <h3>Foil Stamping</h3>
                        <p>Add metallic gold, silver, or colored foil accents to create eye-catching, luxurious packaging that stands out.</p>
                    </div>
                </div>
                <div class="service-card fade-in">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1605733511316-fe5a683daf83?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Embossing/Debossing">
                    </div>
                    <div class="service-content">
                        <h3>Embossing/Debossing</h3>
                        <p>Create tactile, dimensional designs that add depth and sophistication to your perfume packaging.</p>
                    </div>
                </div>
                <div class="service-card fade-in">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1605733511316-7a81b162a5e3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Spot UV Coating">
                    </div>
                    <div class="service-content">
                        <h3>Spot UV Coating</h3>
                        <p>Highlight specific design elements with glossy or matte UV coatings for contrast and visual interest.</p>
                    </div>
                </div>
                <div class="service-card fade-in">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1605733511316-7a81b162a5e3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Die-Cut Windows">
                    </div>
                    <div class="service-content">
                        <h3>Die-Cut Windows</h3>
                        <p>Showcase your fragrance with precision-cut windows that allow customers to see the product while maintaining elegance.</p>
                    </div>
                </div>
                <div class="service-card fade-in">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1605733511316-7a81b162a5e3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Custom Inserts">
                    </div>
                    <div class="service-content">
                        <h3>Custom Inserts</h3>
                        <p>Protect your fragrance bottles with perfectly fitted foam, velvet, or cardboard inserts for a premium unboxing experience.</p>
                    </div>
                </div>
            </div>
            
            <!-- Pricing Calculator -->
            <div class="calculator fade-in">
                <h3>Custom Packaging Calculator</h3>
                <form id="pricing-calculator">
                    <div class="form-group">
                        <label for="box-type">Box Type</label>
                        <select id="box-type" class="form-control">
                            <option value="standard">Standard Rigid Box</option>
                            <option value="magnetic">Magnetic Closure Box</option>
                            <option value="drawer">Drawer Style Box</option>
                            <option value="special">Special Shape Box</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="quantity">Quantity: <span id="quantity-value">500</span></label>
                        <input type="range" id="quantity" class="range-slider" min="100" max="10000" step="100" value="500">
                    </div>
                    <div class="form-group">
                        <label for="size">Size (cm)</label>
                        <input type="text" id="size" class="form-control" placeholder="e.g., 10x10x5">
                    </div>
                    <div class="form-group">
                        <label>Finishing Options</label>
                        <div style="display: flex; flex-wrap: wrap; gap: 15px; margin-top: 10px;">
                            <label style="display: flex; align-items: center; gap: 5px;">
                                <input type="checkbox" name="finishing" value="foil"> Foil Stamping
                            </label>
                            <label style="display: flex; align-items: center; gap: 5px;">
                                <input type="checkbox" name="finishing" value="emboss"> Embossing
                            </label>
                            <label style="display: flex; align-items: center; gap: 5px;">
                                <input type="checkbox" name="finishing" value="uv"> Spot UV
                            </label>
                            <label style="display: flex; align-items: center; gap: 5px;">
                                <input type="checkbox" name="finishing" value="window"> Die-Cut Window
                            </label>
                        </div>
                    </div>
                    <button type="button" class="btn" id="calculate-btn">Calculate Price</button>
                    <div class="calculator-result" id="calculator-result" style="display: none;">
                        <h4>Estimated Price</h4>
                        <p>Your custom perfume boxes will cost approximately:</p>
                        <div class="total-price">AED <span id="total-price">0</span></div>
                        <p style="margin-top: 10px;">* This is an estimate. Final pricing may vary based on design complexity.</p>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section class="section portfolio" id="portfolio">
        <div class="container">
            <div class="text-center fade-in">
                <h2 class="section-title">Our Portfolio</h2>
                <p>Explore our collection of exquisite perfume packaging designs created for luxury brands</p>
            </div>
            <div class="portfolio-filter fade-in">
                <button class="filter-btn active" data-filter="all">All</button>
                <button class="filter-btn" data-filter="luxury">Luxury</button>
                <button class="filter-btn" data-filter="minimalist">Minimalist</button>
                <button class="filter-btn" data-filter="vintage">Vintage</button>
                <button class="filter-btn" data-filter="modern">Modern</button>
            </div>
            <div class="portfolio-grid">
                <div class="portfolio-item fade-in" data-category="luxury">
                    <img src="https://images.unsplash.com/photo-1605733513597-a8f83490f9b8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Luxury Perfume Box" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <h3>Golden Elegance</h3>
                        <p>Foil stamping on black matte finish</p>
                    </div>
                </div>
                <div class="portfolio-item fade-in" data-category="minimalist">
                    <img src="https://images.unsplash.com/photo-1605733511316-7a81b162a5e3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Minimalist Perfume Box" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <h3>Pure Simplicity</h3>
                        <p>Matte white with debossed logo</p>
                    </div>
                </div>
                <div class="portfolio-item fade-in" data-category="vintage">
                    <img src="https://images.unsplash.com/photo-1605733511316-fe5a683daf83?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Vintage Perfume Box" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <h3>Vintage Charm</h3>
                        <p>Antique gold with floral motifs</p>
                    </div>
                </div>
                <div class="portfolio-item fade-in" data-category="modern">
                    <img src="https://images.unsplash.com/photo-1605733511310-0bbfabc1b0b3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Modern Perfume Box" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <h3>Modern Edge</h3>
                        <p>Geometric patterns with spot UV</p>
                    </div>
                </div>
                <div class="portfolio-item fade-in" data-category="luxury">
                    <img src="https://images.unsplash.com/photo-1600857544200-b2f666a9a2ec?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Luxury Perfume Box" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <h3>Royal Collection</h3>
                        <p>Velvet finish with metal accents</p>
                    </div>
                </div>
                <div class="portfolio-item fade-in" data-category="minimalist">
                    <img src="https://images.unsplash.com/photo-1605733511316-7a81b162a5e3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Minimalist Perfume Box" class="portfolio-img">
                    <div class="portfolio-overlay">
                        <h3>Nordic Style</h3>
                        <p>Clean typography on kraft paper</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section" id="contact">
        <div class="container">
            <div class="text-center fade-in">
                <h2 class="section-title">Get In Touch</h2>
                <p>Ready to create stunning packaging for your perfume brand? Contact us today!</p>
            </div>
            <div class="contact-container">
                <div class="contact-info fade-in">
                    <h3>Contact Information</h3>
                    <div class="contact-details">
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div class="contact-text">
                                <h4>Our Location</h4>
                                <p>Dubai Industrial City, UAE</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-phone-alt"></i>
                            </div>
                            <div class="contact-text">
                                <h4>Phone Number</h4>
                                <p>+971 50 123 4567</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div class="contact-text">
                                <h4>Email Address</h4>
                                <p>info@fineprinting.ae</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fab fa-whatsapp"></i>
                            </div>
                            <div class="contact-text">
                                <h4>WhatsApp</h4>
                                <p>+971 50 123 4567</p>
                            </div>
                        </div>
                    </div>
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-pinterest-p"></i></a>
                    </div>
                </div>
                <div class="contact-form fade-in">
                    <form id="contact-form">
                        <div class="form-group form-floating">
                            <input type="text" id="name" placeholder=" " required>
                            <label for="name">Your Name</label>
                        </div>
                        <div class="form-group form-floating">
                            <input type="email" id="email" placeholder=" " required>
                            <label for="email">Email Address</label>
                        </div>
                        <div class="form-group form-floating">
                            <input type="tel" id="phone" placeholder=" ">
                            <label for="phone">Phone Number</label>
                        </div>
                        <div class="form-group form-floating">
                            <textarea id="message" placeholder=" " required></textarea>
                            <label for="message">Your Message</label>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
            <div class="map-container fade-in">
                <!-- Google Maps Embed -->
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3608.9630615979466!2d55.27046941501057!3d25.23492298387544!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3e5f43348a67e24b%3A0xff45e502e1ceb7e2!2sBurj%20Khalifa!5e0!3m2!1sen!2sae!4v1620000000000!5m2!1sen!2sae" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div class="footer-col">
                    <h3>FinePrinting</h3>
                    <p>Premium perfume box printing services in UAE. We specialize in creating luxurious, custom packaging solutions that elevate your brand.</p>
                    <p>Founded by a Pakistani entrepreneur with a passion for exquisite craftsmanship.</p>
                </div>
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#portfolio">Portfolio</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Services</h3>
                    <ul class="footer-links">
                        <li><a href="#">Custom Box Printing</a></li>
                        <li><a href="#">Foil Stamping</a></li>
                        <li><a href="#">Embossing/Debossing</a></li>
                        <li><a href="#">Spot UV Coating</a></li>
                        <li><a href="#">Die-Cut Windows</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h3>Newsletter</h3>
                    <p>Subscribe to our newsletter for the latest updates and offers.</p>
                    <form id="newsletter-form">
                        <div class="form-group">
                            <input type="email" placeholder="Your Email" class="form-control" required>
                        </div>
                        <button type="submit" class="btn">Subscribe</button>
                    </form>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 FinePrinting. All Rights Reserved. | Designed with <i class="fas fa-heart" style="color: #d4af37;"></i> in UAE</p>
            </div>
        </div>
    </footer>

    <!-- Fixed CTA Buttons -->
    <div class="fixed-cta">
        <a href="https://wa.me/971501234567" class="whatsapp-cta">
            <i class="fab fa-whatsapp"></i>
        </a>
        <a href="#contact" class="quote-cta">
            <i class="fas fa-envelope"></i>
        </a>
    </div>

    <!-- JavaScript -->
    <script>
        // Mobile Navigation
        const hamburger = document.querySelector('.hamburger');
        const navLinks = document.querySelector('.nav-links');
        const header = document.getElementById('header');

        hamburger.addEventListener('click', () => {
            hamburger.classList.toggle('active');
            navLinks.classList.toggle('active');
        });

        // Close mobile menu when clicking a link
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                hamburger.classList.remove('active');
                navLinks.classList.remove('active');
            });
        });

        // Header scroll effect
        window.addEventListener('scroll', () => {
            if (window.scrollY > 100) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Portfolio filtering
        const filterButtons = document.querySelectorAll('.filter-btn');
        const portfolioItems = document.querySelectorAll('.portfolio-item');

        filterButtons.forEach(button => {
            button.addEventListener('click', () => {
                // Remove active class from all buttons
                filterButtons.forEach(btn => btn.classList.remove('active'));
                // Add active class to clicked button
                button.classList.add('active');
                
                const filterValue = button.getAttribute('data-filter');
                
                portfolioItems.forEach(item => {
                    if (filterValue === 'all' || item.getAttribute('data-category') === filterValue) {
                        item.style.display = 'block';
                    } else {
                        item.style.display = 'none';
                    }
                });
            });
        });

        // Pricing calculator
        const quantitySlider = document.getElementById('quantity');
        const quantityValue = document.getElementById('quantity-value');
        const calculateBtn = document.getElementById('calculate-btn');
        const calculatorResult = document.getElementById('calculator-result');
        const totalPrice = document.getElementById('total-price');

        quantitySlider.addEventListener('input', () => {
            quantityValue.textContent = quantitySlider.value;
        });

        calculateBtn.addEventListener('click', () => {
            // Simple pricing calculation (would be more complex in real implementation)
            const boxType = document.getElementById('box-type').value;
            const quantity = parseInt(quantitySlider.value);
            const finishingOptions = document.querySelectorAll('input[name="finishing"]:checked');
            
            let basePrice;
            switch(boxType) {
                case 'standard':
                    basePrice = 5;
                    break;
                case 'magnetic':
                    basePrice = 8;
                    break;
                case 'drawer':
                    basePrice = 10;
                    break;
                case 'special':
                    basePrice = 12;
                    break;
                default:
                    basePrice = 5;
            }
            
            // Add cost for finishing options
            let finishingCost = 0;
            finishingOptions.forEach(option => {
                finishingCost += 1.5;
            });
            
            // Quantity discount
            let discount = 0;
            if (quantity > 5000) {
                discount = 0.15;
            } else if (quantity > 2000) {
                discount = 0.1;
            } else if (quantity > 1000) {
                discount = 0.05;
            }
            
            // Calculate total
            let pricePerUnit = basePrice + finishingCost;
            let total = pricePerUnit * quantity;
            total = total - (total * discount);
            
            // Display result
            totalPrice.textContent = Math.round(total);
            calculatorResult.style.display = 'block';
            
            // Scroll to result
            calculatorResult.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
        });

        // Form submission
        const contactForm = document.getElementById('contact-form');
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Thank you for your message! We will contact you soon.');
            contactForm.reset();
        });

        const newsletterForm = document.getElementById('newsletter-form');
        newsletterForm.addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Thank you for subscribing to our newsletter!');
            newsletterForm.reset();
        });

        // Scroll animations
        const fadeElements = document.querySelectorAll('.fade-in, .scale-in');
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, {
            threshold: 0.1
        });

        fadeElements.forEach(element => {
            observer.observe(element);
        });

        // Simple 3D model interaction for the perfume box (placeholder)
        const modelViewer = document.getElementById('perfume-box-model');
        if (modelViewer) {
            let rotation = 0;
            setInterval(() => {
                rotation += 0.5;
                modelViewer.style.transform = `rotateY(${rotation}deg)`;
            }, 50);
        }
    </script>
</body>
</html>
