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
