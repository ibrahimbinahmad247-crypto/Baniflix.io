# Baniflix.io
StreamBD - ফ্রি মুভি ও সিরিজ প্ল্যাটফর্ম
<!DOCTYPE html>
<html>
<head>
    <title>বানিফিক্স - Netflix Clone | Portfolio</title>
    <style>
        body { 
            font-family: Arial; 
            background: #000; 
            color: white; 
            text-align: center; 
            padding: 20px;
        }
        .portfolio {
            max-width: 800px;
            margin: 0 auto;
        }
        .demo { 
            background: #141414; 
            padding: 30px; 
            border-radius: 15px; 
            margin: 20px 0;
        }
        .btn {
            background: #e50914;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 8px;
            font-size: 18px;
            cursor: pointer;
            margin: 10px;
            text-decoration: none;
            display: inline-block;
        }
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .skill {
            background: #222;
            padding: 20px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="portfolio">
        <h1>🎬 বানিফিক্স - Netflix Clone</h1>
        <p>আমি Mobile দিয়ে Netflix এর মতো সম্পূর্ণ Streaming Website তৈরি করেছি!</p>
        
        <div class="demo">
            <h2>📱 Features:</h2>
            <ul style="text-align: left; display: inline-block;">
                <li>✅ Netflix-style Design</li>
                <li>✅ Video Player</li>
                <li>✅ Movie Grid</li>
                <li>✅ Mobile Responsive</li>
                <li>✅ Dark Theme</li>
                <li>✅ Professional UI</li>
            </ul>
        </div>

        <div class="skills">
            <div class="skill">
                <h3>HTML5</h3>
                <p>⭐⭐⭐⭐⭐</p>
            </div>
            <div class="skill">
                <h3>CSS3</h3>
                <p>⭐⭐⭐⭐⭐</p>
            </div>
            <div class="skill">
                <h3>JavaScript</h3>
                <p>⭐⭐⭐⭐</p>
            </div>
            <div class="skill">
                <h3>Mobile Dev</h3>
                <p>⭐⭐⭐⭐⭐</p>
            </div>
        </div>

        <h2>💼 আমি এমন আরও তৈরি করতে পারি:</h2>
        <ul style="text-align: left; display: inline-block;">
            <li>🎥 Movie Streaming Website</li>
            <li>📱 Mobile Apps</li>
            <li>🛒 E-commerce Website</li>
            <li>💰 Subscription Platform</li>
            <li>🎨 Portfolio Website</li>
        </ul>

        <div style="margin: 40px 0;">
            <a href="#" class="btn" onclick="copyWhatsApp()">📱 WhatsApp এ যোগাযোগ</a>
            <a href="#" class="btn">💼 Fiverr Profile</a>
            <a href="#" class="btn">📧 Email পাঠান</a>
        </div>

        <p style="font-size: 14px; color: #ccc;">
            🚀 Mobile দিয়ে তৈরি | ২০২৫ | ibrahimbinahmad247-crypto
        </p>
    </div>

    <script>
        function copyWhatsApp() {
            const message = "হ্যালো! আমি আপনার জন্য Netflix মতো website তৈরি করতে পারি।";
            const whatsappNumber = "8801XXXXXXXXX"; // আপনার নম্বর দিন
            const url = `https://wa.me/${whatsappNumber}?text=${encodeURIComponent(message)}`;
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>বানিফিক্স - Netflix Clone | Portfolio</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #000 0%, #141414 100%);
            color: white;
            line-height: 1.6;
            overflow-x: hidden;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9)), 
                        url('https://images.unsplash.com/photo-1489599552549-d5a974173e96?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            border-radius: 20px;
            margin-bottom: 40px;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            background: linear-gradient(45deg, #e50914, #f5a623);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 30px;
            opacity: 0.9;
        }
        .demo {
            background: #141414;
            padding: 40px;
            border-radius: 20px;
            margin: 40px 0;
            border: 2px solid #333;
            box-shadow: 0 20px 40px rgba(0,0,0,0.5);
        }
        .demo h2 {
            color: #e50914;
            margin-bottom: 25px;
            font-size: 2rem;
        }
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .feature {
            background: #222;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .feature:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(224, 9, 20, 0.3);
        }
        .feature i {
            font-size: 3rem;
            color: #e50914;
            margin-bottom: 15px;
        }
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 25px;
            margin: 50px 0;
        }
        .skill {
            background: linear-gradient(135deg, #222 0%, #333 100%);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            border: 2px solid #444;
        }
        .skill h3 {
            color: #e50914;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }
        .stars {
            color: #f5a623;
            font-size: 1.5rem;
        }
        .services {
            background: #141414;
            padding: 50px 20px;
            border-radius: 20px;
            margin: 50px 0;
        }
        .services h2 {
            text-align: center;
            color: #e50914;
            margin-bottom: 40px;
            font-size: 2.5rem;
        }
        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }
        .service {
            background: #222;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }
        .service:hover {
            border-color: #e50914;
            transform: translateY(-5px);
        }
        .service i {
            font-size: 3.5rem;
            color: #e50914;
            margin-bottom: 20px;
        }
        .btn {
            background: linear-gradient(45deg, #e50914, #f5a623);
            color: white;
            padding: 18px 40px;
            border: none;
            border-radius: 50px;
            font-size: 1.2rem;
            font-weight: bold;
            cursor: pointer;
            margin: 10px;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(224, 9, 20, 0.3);
        }
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(224, 9, 20, 0.5);
        }
        .btn-secondary {
            background: transparent;
            color: #fff;
            border: 2px solid #e50914;
        }
        .contact-section {
            background: linear-gradient(135deg, #e50914 0%, #f5a623 100%);
            padding: 60px 20px;
            border-radius: 20px;
            margin: 60px 0;
            text-align: center;
        }
        .contact-section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: white;
        }
        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            .demo, .services { padding: 20px; }
            .features, .service-grid { grid-template-columns: 1fr; }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <!-- Hero Section -->
        <section class="hero">
            <h1><i class="fas fa-play-circle"></i> বানিফিক্স</h1>
            <p class="hero-subtitle">আমি Mobile দিয়ে Netflix এর মতো সম্পূর্ণ Streaming Website তৈরি করেছি!</p>
            <p style="font-size: 1.1rem; opacity: 0.8;">✅ Professional Design | ✅ Video Player | ✅ Mobile Responsive</p>
        </section>

        <!-- Features Demo -->
        <section class="demo">
            <h2><i class="fas fa-star"></i> Features যা তৈরি করেছি:</h2>
            <div class="features">
                <div class="feature">
                    <i class="fas fa-tv"></i>
                    <h3>Netflix-style Design</h3>
                    <p>Professional Dark Theme এবং Modern UI</p>
                </div>
                <div class="feature">
                    <i class="fas fa-play-circle"></i>
                    <h3>Video Player</h3>
                    <p>Full-screen Video Streaming সহ Controls</p>
                </div>
                <div class="feature">
                    <i class="fas fa-th-large"></i>
                    <h3>Movie Grid</h3>
                    <p>Responsive Movie এবং Series Layout</p>
                </div>
                <div class="feature">
                    <i class="fas fa-mobile-alt"></i>
                    <h3>Mobile Responsive</h3>
                    <p>সব Device এ Perfect দেখাবে</p>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="skills">
            <h2 style="text-align: center; margin-bottom: 40px; color: #e50914;">🛠️ আমার Skills</h2>
            <div class="skill">
                <h3><i class="fab fa-html5"></i> HTML5</h3>
                <p class="stars">⭐⭐⭐⭐⭐</p>
            </div>
            <div class="skill">
                <h3><i class="fab fa-css3-alt"></i> CSS3</h3>
                <p class="stars">⭐⭐⭐⭐⭐</p>
            </div>
            <div class="skill">
                <h3><i class="fab fa-js-square"></i> JavaScript</h3>
                <p class="stars">⭐⭐⭐⭐⭐</p>
            </div>
            <div class="skill">
                <h3><i class="fas fa-mobile-alt"></i> Mobile Dev</h3>
                <p class="stars">⭐⭐⭐⭐⭐</p>
            </div>
        </section>

        <!-- Services Section -->
        <section class="services">
            <h2>💼 আমি এমন আরও তৈরি করতে পারি:</h2>
            <div class="service-grid">
                <div class="service">
                    <i class="fas fa-video"></i>
                    <h3>🎬 Movie Streaming Website</h3>
                    <p>Netflix/Crunchyroll স্টাইলের সম্পূর্ণ প্ল্যাটফর্ম</p>
                </div>
                <div class="service">
                    <i class="fas fa-mobile-alt"></i>
                    <h3>📱 Mobile Apps</h3>
                    <p>PWA এবং Responsive Web Applications</p>
                </div>
                <div class="service">
                    <i class="fas fa-shopping-cart"></i>
                    <h3>🛒 E-commerce Website</h3>
                    <p>Daraz/Amazon স্টাইলের Online Store</p>
                </div>
                <div class="service">
                    <i class="fas fa-users"></i>
                    <h3>👥 Subscription Platform</h3>
                    <p>Member Login এবং Payment System</p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="contact-section">
            <h2>🚀 আপনার জন্য Website তৈরি করতে চান?</h2>
            <p style="font-size: 1.2rem; margin-bottom: 30px;">৩ দিনের মধ্যে সম্পূর্ণ Professional Website!</p>
            <div>
                <a href="#" class="btn" onclick="contactWhatsApp()">
                    <i class="fab fa-whatsapp"></i> WhatsApp এ যোগাযোগ
                </a>
                <a href="#" class="btn btn-secondary" onclick="contactEmail()">
                    <i class="fas fa-envelope"></i> Email পাঠান
                </a>
                <a href="#" class="btn" onclick="hireNow()">
                    <i class="fas fa-briefcase"></i> এখনই নিয়োগ করুন
                </a>
            </div>
            <p style="margin-top: 30px; font-size: 1.1rem; opacity: 0.9;">
                💰 <strong>দাম শুরু: ৳5,000</strong> | ⏱️ <strong>Delivery: 3 দিন</strong>
            </p>
        </section>
    </div>

    <script>
        function contactWhatsApp() {
            const message = encodeURIComponent(
                https://ibrahimbinahmad247-crypto.github.io/Banifix.io/
