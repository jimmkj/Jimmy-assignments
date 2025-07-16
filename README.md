<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jimmy Group of Writers - Professional Assignment Help</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .services, .subjects, .guarantees {
            padding: 3rem 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            color: var(--primary);
            position: relative;
        }
        
        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: var(--secondary);
            margin: 10px auto;
        }
        
        .service-grid, .subject-grid, .guarantee-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .service-card, .subject-card, .guarantee-card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .service-card:hover, .subject-card:hover, .guarantee-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.1);
        }
        
        .service-icon, .subject-icon, .guarantee-icon {
            font-size: 2.5rem;
            color: var(--secondary);
            margin-bottom: 1rem;
        }
        
        .contact {
            background: var(--primary);
            color: white;
            padding: 3rem 0;
            text-align: center;
        }
        
        .contact-links {
            margin-top: 2rem;
        }
        
        .btn {
            display: inline-block;
            background: var(--accent);
            color: white;
            padding: 12px 24px;
            border-radius: 4px;
            text-decoration: none;
            font-weight: bold;
            margin: 10px;
            transition: background 0.3s;
        }
        
        .btn:hover {
            background: #c0392b;
        }
        
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .service-grid, .subject-grid, .guarantee-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Jimmy Group of Writers</h1>
            <p class="tagline">First Class Quality Assured</p>
        </div>
    </header>
    
    <section class="services">
        <div class="container">
            <h2 class="section-title">Our Assignment Help Services</h2>
            <div class="service-grid">
                <div class="service-card">
                    <div class="service-icon">📚</div>
                    <h3>Thesis & Dissertation</h3>
                    <p>Expert assistance with all aspects of your thesis or dissertation writing.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">📋</div>
                    <h3>Online Exams & Coursework</h3>
                    <p>Professional help with online exams and coursework assignments.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">📒</div>
                    <h3>Proposals</h3>
                    <p>Well-researched and compelling research proposals.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">📝</div>
                    <h3>Research Papers</h3>
                    <p>High-quality research papers tailored to your requirements.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">📚</div>
                    <h3>Literature Reviews</h3>
                    <p>Comprehensive literature reviews with proper citations.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">📋</div>
                    <h3>Reflective Writing</h3>
                    <p>Thoughtful and insightful reflective writing pieces.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">📓</div>
                    <h3>Research Summary</h3>
                    <p>Concise and accurate summaries of research findings.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section class="subjects">
        <div class="container">
            <h2 class="section-title">Our Core Subjects</h2>
            <div class="subject-grid">
                <div class="subject-card">
                    <div class="subject-icon">💰</div>
                    <h3>Economics & Marketing</h3>
                    <p>Expert assistance with all economics and marketing assignments.</p>
                </div>
                
                <div class="subject-card">
                    <div class="subject-icon">📊</div>
                    <h3>Finance & Accounting</h3>
                    <p>Professional help with finance and accounting coursework.</p>
                </div>
                
                <div class="subject-card">
                    <div class="subject-icon">🚚</div>
                    <h3>Supply Chain</h3>
                    <p>Comprehensive supply chain management solutions.</p>
                </div>
                
                <div class="subject-card">
                    <div class="subject-icon">⚖️</div>
                    <h3>Law</h3>
                    <p>Specialized legal writing and case analysis.</p>
                </div>
                
                <div class="subject-card">
                    <div class="subject-icon">🔧</div>
                    <h3>Engineering (All Disciplines)</h3>
                    <p>Technical writing for all engineering fields.</p>
                </div>
                
                <div class="subject-card">
                    <div class="subject-icon">💻</div>
                    <h3>Programming</h3>
                    <p>C++, C, JavaScript, SQL, Android apps, HTML/CSS, R coding, Web Development, AI/ML</p>
                </div>
            </div>
        </div>
    </section>
    
    <section class="guarantees">
        <div class="container">
            <h2 class="section-title">We Guarantee You</h2>
            <div class="guarantee-grid">
                <div class="guarantee-card">
                    <div class="guarantee-icon">⭐</div>
                    <h3>Excellent Grades</h3>
                    <p>We deliver high-quality work that helps you achieve top grades.</p>
                </div>
                
                <div class="guarantee-card">
                    <div class="guarantee-icon">⏱️</div>
                    <h3>On-Time Delivery</h3>
                    <p>Your assignments are delivered promptly, every time.</p>
                </div>
                
                <div class="guarantee-card">
                    <div class="guarantee-icon">🤖</div>
                    <h3>0% AI Content</h3>
                    <p>100% original, human-written content with proper citations.</p>
                </div>
                
                <div class="guarantee-card">
                    <div class="guarantee-icon">🌐</div>
                    <h3>24/7 Services</h3>
                    <p>Round-the-clock support for all your academic needs.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section class="contact">
        <div class="container">
            <h2 class="section-title">Contact Us</h2>
            <p>Get instant help with your assignments from our expert writers.</p>
            
            <div class="contact-links">
                <a href="https://wa.me/qr/4PKBWS2XMM4VF1" class="btn">DM on WhatsApp</a>
                <a href="https://chat.whatsapp.com/K4pGzREL0Io5XN9v5McvbQ" class="btn">Join WhatsApp Group</a>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>&copy; 2023 Jimmy Group of Writers. All rights reserved.</p>
            <p>First Class Quality Assured</p>
        </div>
    </footer>
</body>
</html>
