# airforce-hvac-website
Repository for Airforce HVAC website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AIR FORCE HVAC CORP - Military Precision Climate Control | Emergency HVAC Services</title>
    <meta name="description" content="AIR FORCE HVAC CORP delivers military-grade HVAC excellence with 24/7 emergency response, commercial solutions, and luxury residential services. Military-trained technicians providing mission-critical climate control.">
    <meta name="keywords" content="HVAC, Air Force, military precision, emergency service, commercial HVAC, luxury residential, climate control, 24/7 service">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://vdltrxnu.manus.space/">
    <meta property="og:title" content="AIR FORCE HVAC CORP - Military Precision Climate Control">
    <meta property="og:description" content="Military-grade HVAC excellence with 24/7 emergency response, commercial solutions, and luxury residential services.">
    <meta property="og:image" content="https://vdltrxnu.manus.space/og-image.jpg">

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://vdltrxnu.manus.space/">
    <meta property="twitter:title" content="AIR FORCE HVAC CORP - Military Precision Climate Control">
    <meta property="twitter:description" content="Military-grade HVAC excellence with 24/7 emergency response, commercial solutions, and luxury residential services.">
    <meta property="twitter:image" content="https://vdltrxnu.manus.space/og-image.jpg">

    <link rel="icon" type="image/x-icon" href="/favicon.ico">
    
    <style>
        :root {
            --primary-blue: #1e3a8a;
            --secondary-blue: #3b82f6;
            --accent-gold: #fbbf24;
            --text-dark: #1f2937;
            --text-light: #6b7280;
            --white: #ffffff;
            --light-gray: #f9fafb;
            --border-gray: #e5e7eb;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--white);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header Styles */
        .header {
            background: var(--white);
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-blue);
        }

        .logo-icon {
            width: 40px;
            height: 40px;
            background: var(--primary-blue);
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-weight: bold;
        }

        .tagline {
            font-size: 0.9rem;
            color: var(--text-light);
            font-weight: 400;
        }

        .nav {
            display: flex;
            gap: 2rem;
            align-items: center;
        }

        .nav-button {
            padding: 0.5rem 1rem;
            border: none;
            background: transparent;
            color: var(--text-dark);
            font-weight: 500;
            cursor: pointer;
            border-radius: 6px;
            transition: all 0.3s ease;
        }

        .nav-button:hover {
            background: var(--light-gray);
        }

        .nav-button.active {
            background: var(--primary-blue);
            color: var(--white);
        }

        .emergency-contact {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .phone-number {
            font-weight: 600;
            color: var(--primary-blue);
        }

        .emergency-text {
            font-size: 0.8rem;
            color: var(--text-light);
        }

        .cta-button {
            background: var(--accent-gold);
            color: var(--text-dark);
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .cta-button:hover {
            background: #f59e0b;
            transform: translateY(-2px);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--secondary-blue) 100%);
            color: var(--white);
            padding: 8rem 0 4rem;
            margin-top: 80px;
            text-align: center;
        }

        .hero-badge {
            display: inline-block;
            background: rgba(255,255,255,0.2);
            padding: 0.5rem 1rem;
            border-radius: 25px;
            font-size: 0.9rem;
            margin-bottom: 2rem;
            border: 1px solid rgba(255,255,255,0.3);
        }

        .hero-title {
            font-size: 3.5rem;
            font-weight: 800;
            margin-bottom: 1.5rem;
            line-height: 1.1;
        }

        .hero-subtitle {
            font-size: 1.25rem;
            margin-bottom: 3rem;
            opacity: 0.9;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn-primary {
            background: var(--accent-gold);
            color: var(--text-dark);
            padding: 1rem 2rem;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .btn-secondary {
            background: transparent;
            color: var(--white);
            padding: 1rem 2rem;
            border: 2px solid var(--white);
            border-radius: 8px;
            font-weight: 600;
            font-size: 1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .btn-primary:hover {
            background: #f59e0b;
            transform: translateY(-2px);
        }

        .btn-secondary:hover {
            background: var(--white);
            color: var(--primary-blue);
        }

        /* Features Section */
        .features {
            padding: 4rem 0;
            background: var(--light-gray);
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .feature-card {
            background: var(--white);
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .feature-icon {
            width: 60px;
            height: 60px;
            background: var(--primary-blue);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1rem;
            color: var(--white);
            font-size: 1.5rem;
        }

        .feature-title {
            font-size: 1.25rem;
            font-weight: 600;
            margin-bottom: 1rem;
            color: var(--primary-blue);
        }

        .feature-description {
            color: var(--text-light);
        }

        /* Services Section */
        .services {
            padding: 4rem 0;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            color: var(--primary-blue);
        }

        .section-subtitle {
            text-align: center;
            font-size: 1.1rem;
            color: var(--text-light);
            margin-bottom: 3rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .service-card {
            background: var(--white);
            border: 1px solid var(--border-gray);
            border-radius: 12px;
            padding: 2rem;
            transition: all 0.3s ease;
        }

        .service-card:hover {
            box-shadow: 0 8px 30px rgba(0,0,0,0.15);
            transform: translateY(-3px);
        }

        .service-title {
            font-size: 1.5rem;
            font-weight: 600;
            margin-bottom: 1rem;
            color: var(--primary-blue);
        }

        .service-description {
            color: var(--text-light);
            margin-bottom: 1.5rem;
        }

        .service-features {
            list-style: none;
            margin-bottom: 2rem;
        }

        .service-features li {
            padding: 0.5rem 0;
            color: var(--text-dark);
            position: relative;
            padding-left: 1.5rem;
        }

        .service-features li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: var(--accent-gold);
            font-weight: bold;
        }

        .service-button {
            background: var(--primary-blue);
            color: var(--white);
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 6px;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.3s ease;
            width: 100%;
        }

        .service-button:hover {
            background: var(--secondary-blue);
        }

        /* About Section */
        .about {
            padding: 4rem 0;
            background: var(--light-gray);
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: center;
        }

        .about-text h2 {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
            color: var(--primary-blue);
        }

        .about-text p {
            color: var(--text-light);
            margin-bottom: 1.5rem;
        }

        .about-features {
            display: grid;
            grid-template-columns: 1fr;
            gap: 1rem;
        }

        .about-feature {
            display: flex;
            align-items: flex-start;
            gap: 1rem;
        }

        .about-feature-icon {
            width: 40px;
            height: 40px;
            background: var(--primary-blue);
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            flex-shrink: 0;
        }

        .about-feature-content h3 {
            font-weight: 600;
            margin-bottom: 0.5rem;
            color: var(--primary-blue);
        }

        .about-feature-content p {
            color: var(--text-light);
            font-size: 0.9rem;
        }

        /* Contact Section */
        .contact {
            padding: 4rem 0;
            background: var(--primary-blue);
            color: var(--white);
        }

        .contact-content {
            text-align: center;
        }

        .contact-title {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
        }

        .contact-subtitle {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-bottom: 3rem;
        }

        .contact-methods {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }

        .contact-method {
            background: rgba(255,255,255,0.1);
            padding: 2rem;
            border-radius: 12px;
            border: 1px solid rgba(255,255,255,0.2);
        }

        .contact-method h3 {
            font-size: 1.25rem;
            font-weight: 600;
            margin-bottom: 1rem;
        }

        .contact-method p {
            opacity: 0.9;
            margin-bottom: 1rem;
        }

        .contact-info {
            font-size: 1.1rem;
            font-weight: 600;
            margin-bottom: 1rem;
        }

        .contact-details {
            font-size: 0.9rem;
            opacity: 0.8;
        }

        .financing-features {
            list-style: none;
            text-align: left;
        }

        .financing-features li {
            padding: 0.25rem 0;
            position: relative;
            padding-left: 1.5rem;
        }

        .financing-features li:before {
            content: "•";
            position: absolute;
            left: 0;
            color: var(--accent-gold);
        }

        /* Footer */
        .footer {
            background: var(--text-dark);
            color: var(--white);
            padding: 2rem 0;
            text-align: center;
        }

        .footer p {
            opacity: 0.8;
        }

        /* Mobile Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 1rem;
            }

            .nav {
                flex-wrap: wrap;
                justify-content: center;
            }

            .emergency-contact {
                flex-direction: column;
                text-align: center;
            }

            .hero {
                padding: 6rem 0 3rem;
            }

            .hero-title {
                font-size: 2.5rem;
            }

            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }

            .about-content {
                grid-template-columns: 1fr;
            }

            .contact-methods {
                grid-template-columns: 1fr;
            }

            .services-grid {
                grid-template-columns: 1fr;
            }

            .features-grid {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 15px;
            }

            .hero-title {
                font-size: 2rem;
            }

            .section-title {
                font-size: 2rem;
            }

            .service-card,
            .feature-card {
                padding: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <div class="logo-icon">AF</div>
                    <div>
                        <div>AIR FORCE HVAC CORP</div>
                        <div class="tagline">Military Precision Climate Control</div>
                    </div>
                </div>
                
                <nav class="nav">
                    <button class="nav-button active">Home</button>
                    <button class="nav-button">Schedule</button>
                    <button class="nav-button">Financing</button>
                    <button class="nav-button">Contact</button>
                </nav>
                
                <div class="emergency-contact">
                    <div>
                        <div class="phone-number">(323) 629-5799</div>
                        <div class="emergency-text">24/7 Emergency Service</div>
                    </div>
                    <button class="cta-button">Call Now</button>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-badge">🎯 Military-Grade HVAC Excellence</div>
            <h1 class="hero-title">Mission-Critical<br>Climate Control</h1>
            <p class="hero-subtitle">
                When your comfort and business operations depend on reliable HVAC systems, 
                trust the precision and expertise that only military-trained professionals can deliver.
            </p>
            <div class="hero-buttons">
                <a href="tel:3236295799" class="btn-primary">⚡ Emergency Service - Call (323) 629-5799</a>
                <a href="#contact" class="btn-secondary">📧 Free Consultation</a>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="container">
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">⚡</div>
                    <h3 class="feature-title">24/7 Emergency Response</h3>
                    <p class="feature-description">Rapid deployment when failure is not an option</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🎖️</div>
                    <h3 class="feature-title">Military-Trained Technicians</h3>
                    <p class="feature-description">Precision and discipline in every service call</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">⭐</div>
                    <h3 class="feature-title">Premium Service Excellence</h3>
                    <p class="feature-description">Targeting commercial and luxury residential markets</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services">
        <div class="container">
            <h2 class="section-title">Strategic HVAC Solutions</h2>
            <p class="section-subtitle">
                From emergency response to luxury installations, we deliver HVAC solutions with military precision 
                for commercial facilities and discerning homeowners.
            </p>
            
            <div class="services-grid">
                <div class="service-card">
                    <h3 class="service-title">Emergency Response</h3>
                    <p class="service-description">24/7 rapid deployment for critical HVAC failures</p>
                    <ul class="service-features">
                        <li>Immediate system failure restoration</li>
                        <li>Critical component replacement</li>
                        <li>After-hours service availability</li>
                        <li>Priority parts procurement</li>
                    </ul>
                    <button class="service-button">Call Emergency Line</button>
                </div>
                
                <div class="service-card">
                    <h3 class="service-title">Commercial Solutions</h3>
                    <p class="service-description">Strategic climate control for business success</p>
                    <ul class="service-features">
                        <li>Office building climate control</li>
                        <li>Industrial HVAC systems</li>
                        <li>Preventive maintenance programs</li>
                        <li>Energy efficiency optimization</li>
                    </ul>
                    <button class="service-button">Request Commercial Quote</button>
                </div>
                
                <div class="service-card">
                    <h3 class="service-title">Luxury Residential</h3>
                    <p class="service-description">Premium climate control for discerning homeowners</p>
                    <ul class="service-features">
                        <li>Smart home HVAC integration</li>
                        <li>Custom system design</li>
                        <li>Zoned climate control</li>
                        <li>Energy efficiency excellence</li>
                    </ul>
                    <button class="service-button">Schedule Luxury Consultation</button>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <h2>From Military Service to Climate Control Excellence</h2>
                    <p>
                        AIR FORCE HVAC CORP was founded on the principle that the same precision, discipline, 
                        and commitment to excellence that protects our nation can be applied to civilian 
                        climate control challenges.
                    </p>
                    <a href="#contact" class="btn-primary">Learn More About Our Mission</a>
                </div>
                
                <div class="about-features">
                    <div class="about-feature">
                        <div class="about-feature-icon">🛡️</div>
                        <div class="about-feature-content">
                            <h3>Military-Grade Reliability</h3>
                            <p>Every project executed with military attention to detail and unwavering commitment to mission success.</p>
                        </div>
                    </div>
                    
                    <div class="about-feature">
                        <div class="about-feature-icon">🎯</div>
                        <div class="about-feature-content">
                            <h3>Strategic Problem Solving</h3>
                            <p>Military training teaches systematic problem-solving for complex HVAC challenges.</p>
                        </div>
                    </div>
                    
                    <div class="about-feature">
                        <div class="about-feature-icon">⭐</div>
                        <div class="about-feature-content">
                            <h3>Premium Service Excellence</h3>
                            <p>Targeting commercial and luxury residential markets with superior service quality.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="contact-content">
                <div style="text-align: center; margin-bottom: 2rem;">
                    <div style="font-size: 3rem; font-weight: 700; margin-bottom: 0.5rem;">24/7</div>
                    <div style="font-size: 1.5rem; opacity: 0.9;">Emergency Response</div>
                </div>
                
                <h2 class="contact-title">Ready for Immediate Deployment</h2>
                <p class="contact-subtitle">
                    Contact AIR FORCE HVAC CORP for emergency service, strategic consultations, or financing options.
                </p>
                
                <div class="contact-methods">
                    <div class="contact-method">
                        <h3>Emergency Hotline</h3>
                        <p>24/7 rapid response for critical HVAC failures</p>
                        <div class="contact-info">(323) 629-5799</div>
                        <div class="contact-details">Available 24/7 for urgent service needs and critical system failures</div>
                        <br>
                        <button class="btn-primary">Call Emergency Line</button>
                    </div>
                    
                    <div class="contact-method">
                        <h3>Strategic Planning</h3>
                        <p>Comprehensive consultations and project planning</p>
                        <div class="contact-info">AIRFORCEHVACPROS9@gmail.com</div>
                        <div class="contact-details">For commercial projects, luxury installations, and comprehensive system design</div>
                        <br>
                        <button class="btn-primary">Send Email</button>
                    </div>
                    
                    <div class="contact-method">
                        <h3>Instant Financing</h3>
                        <p>Quick approval for HVAC investments</p>
                        <ul class="financing-features">
                            <li>Instant pre-approval decisions</li>
                            <li>Multiple financing options</li>
                            <li>No credit check programs available</li>
                            <li>Flexible payment plans</li>
                        </ul>
                        <button class="btn-primary">Apply for Financing</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 AIR FORCE HVAC CORP. All rights reserved. | Military Precision Climate Control</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Phone number click handlers
        document.querySelectorAll('button, a').forEach(element => {
            if (element.textContent.includes('Call') || element.textContent.includes('Emergency Line')) {
                element.addEventListener('click', function(e) {
                    if (!this.href) {
                        e.preventDefault();
                        window.location.href = 'tel:3236295799';
                    }
                });
            }
            
            if (element.textContent.includes('Send Email')) {
                element.addEventListener('click', function(e) {
                    if (!this.href) {
                        e.preventDefault();
                        window.location.href = 'mailto:AIRFORCEHVACPROS9@gmail.com';
                    }
                });
            }
        });

        // Navigation active state
        document.querySelectorAll('.nav-button').forEach(button => {
            button.addEventListener('click', function() {
                document.querySelectorAll('.nav-button').forEach(btn => btn.classList.remove('active'));
                this.classList.add('active');
            });
        });

        // Header scroll effect
        window.addEventListener('scroll', function() {
            const header = document.querySelector('.header');
            if (window.scrollY > 100) {
                header.style.background = 'rgba(255, 255, 255, 0.95)';
                header.style.backdropFilter = 'blur(10px)';
            } else {
                header.style.background = 'var(--white)';
                header.style.backdropFilter = 'none';
            }
        });
    </script>
</body>
</html>
