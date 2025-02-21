<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HusoNode Validator</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    <style>
        :root {
            --primary-color: #006400;
            --secondary-color: #008000;
            --background-color: #001a00;
            --surface-color: rgba(0, 26, 0, 0.7);
            --hover-color: rgba(0, 38, 0, 0.8);
            --text-color: #c0c0c0;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: var(--background-color);
            min-height: 100vh;
            overflow-x: hidden;
            color: var(--text-color);
        }

        .header {
            background: var(--surface-color);
            padding: 1rem;
            position: fixed;
            width: 100%;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0, 100, 0, 0.2);
            display: flex;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(10px);
        }

        .logo-container {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .logo-img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: 2px solid var(--primary-color);
            box-shadow: 0 0 15px rgba(0, 100, 0, 0.3);
        }

        .logo-text {
            color: var(--primary-color);
            font-size: 2.2rem;
            font-weight: bold;
            text-shadow: 1px 1px 3px rgba(0, 100, 0, 0.5);
            letter-spacing: 1px;
        }

        .main-content {
            padding-top: 120px;
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .about-section, .contact-form {
            background: var(--surface-color);
            margin: 2rem auto;
            padding: 2rem;
            border-radius: 20px;
            max-width: 800px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 0 15px rgba(0, 100, 0, 0.1);
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
            width: 100%;
        }

        .about-section:hover, .contact-form:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0, 100, 0, 0.2);
        }

        .about-title, .form-title, .section-title {
            color: var(--primary-color);
            font-size: 2rem;
            margin-bottom: 1.5rem;
            text-shadow: 1px 1px 3px rgba(0, 100, 0, 0.3);
        }

        .about-text {
            color: var(--text-color);
            line-height: 1.8;
            font-size: 1.1rem;
        }

        .services-section {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin: 3rem 0;
            padding: 0 1rem;
            width: 100%;
        }

        .service-box {
            background: var(--surface-color);
            padding: 2rem;
            border-radius: 15px;
            width: 220px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 0 10px rgba(0, 100, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        .service-box:hover {
            transform: translateY(-8px) scale(1.05);
            background: var(--hover-color);
            box-shadow: 0 8px 20px rgba(0, 100, 0, 0.2);
        }

        .service-box i {
            color: var(--primary-color);
            font-size: 2.5rem;
            margin-bottom: 1rem;
            text-shadow: 1px 1px 2px rgba(0, 100, 0, 0.3);
        }

        .service-title {
            color: var(--primary-color);
            font-size: 1.4rem;
            text-shadow: 1px 1px 2px rgba(0, 100, 0, 0.3);
        }

        .projects-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2.5rem;
            padding: 3rem 1rem;
            margin: 2rem 0;
            width: 100%;
        }

        .project-bubble {
            background: var(--surface-color);
            border-radius: 20px;
            padding: 1.8rem;
            width: 280px;
            cursor: pointer;
            transition: all 0.4s;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 0 10px rgba(0, 100, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        .project-bubble:hover {
            transform: translateY(-8px) scale(1.02);
            background: var(--hover-color);
            box-shadow: 0 8px 25px rgba(0, 100, 0, 0.2);
        }

        .project-img {
            width: 100%;
            height: 160px;
            object-fit: cover;
            border-radius: 12px;
            margin-bottom: 1.2rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .project-title {
            color: var(--primary-color);
            font-size: 1.4rem;
            margin-bottom: 0.8rem;
            text-shadow: 1px 1px 2px rgba(0, 100, 0, 0.3);
        }

        .project-info {
            color: var(--text-color);
            font-size: 1rem;
            line-height: 1.6;
        }

        .stats {
            margin-top: 1.2rem;
            padding-top: 1.2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            display: flex;
            justify-content: space-between;
        }

        .stat {
            color: var(--primary-color);
            font-size: 0.9rem;
            font-weight: 500;
        }

        .form-group {
            margin-bottom: 1.2rem;
        }

        .form-input, .form-textarea {
            width: 100%;
            padding: 0.8rem;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            color: var(--text-color);
            margin-top: 0.5rem;
            font-size: 0.9rem;
            transition: all 0.3s;
        }

        .form-input:focus, .form-textarea:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 15px rgba(0, 100, 0, 0.2);
        }

        .form-textarea {
            min-height: 120px;
            resize: vertical;
        }

        .submit-btn {
            background: var(--hover-color);
            color: var(--primary-color);
            padding: 0.8rem 1.5rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 1rem;
            font-weight: 500;
            text-shadow: 1px 1px 2px rgba(0, 100, 0, 0.3);
            width: 100%;
        }

        .submit-btn:hover {
            background: rgba(255, 255, 255, 0.15);
            box-shadow: 0 0 20px rgba(0, 100, 0, 0.3);
            transform: translateY(-2px);
        }

        .contact-form {
            background: var(--surface-color);
            margin: 2rem auto;
            padding: 2rem;
            border-radius: 20px;
            max-width: 400px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 0 15px rgba(0, 100, 0, 0.1);
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
            width: 100%;
        }

        .contact-form:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0, 100, 0, 0.2);
        }

        .form-title {
            color: var(--primary-color);
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            text-shadow: 1px 1px 3px rgba(0, 100, 0, 0.3);
        }

        .footer {
            background: var(--surface-color);
            padding: 2rem;
            text-align: center;
            margin-top: 4rem;
            backdrop-filter: blur(10px);
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin-bottom: 1.5rem;
        }

        .social-link {
            color: var(--primary-color);
            font-size: 1.8rem;
            transition: all 0.3s;
        }

        .social-link:hover {
            color: var(--text-color);
            transform: translateY(-3px);
            text-shadow: 0 0 15px rgba(0, 100, 0, 0.5);
        }

        .section-title {
            color: var(--primary-color);
            font-size: 2rem;
            margin-bottom: 2rem;
            text-align: center;
            width: 100%;
            text-shadow: 1px 1px 3px rgba(0, 100, 0, 0.3);
        }

        #stars-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        @media (max-width: 768px) {
            .services-section {
                flex-direction: column;
                align-items: center;
            }
            
            .service-box {
                width: 90%;
            }
            
            .about-section,
            .contact-form {
                margin: 2rem 1rem;
                padding: 1.5rem;
            }

            .logo-text {
                font-size: 1.8rem;
            }
        }

        /* Mouse parıltıları için güncellenmiş stil */
        .mouse-sparkle {
            position: absolute;
            width: 6px;
            height: 6px;
            background: white;
            border-radius: 50%;
            pointer-events: none;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
    </style>
</head>
<body>
    <canvas id="stars-canvas"></canvas>
    
    <header class="header">
        <div class="logo-container">
            <img src="https://via.placeholder.com/50" alt="Logo" class="logo-img">
            <div class="logo-text">HusoNode</div>
        </div>
    </header>

    <div class="main-content">
        <div class="about-section">
            <h2 class="about-title">Hakkımda</h2>
            <p class="about-text">
                Buraya kendiniz hakkında bilgi ekleyebilirsiniz. Validator deneyiminiz, 
                teknik altyapınız ve blockchain ekosistemine katkılarınız hakkında bilgiler verebilirsiniz.
                Cosmos ekosistemindeki deneyiminiz ve vizyonunuz da burada paylaşılabilir.
            </p>
        </div>

        <div class="services-section">
            <div class="service-box">
                <i class="fas fa-server"></i>
                <h3 class="service-title">Services</h3>
            </div>
            <div class="service-box">
                <i class="fas fa-search"></i>
                <h3 class="service-title">Explorer</h3>
            </div>
        </div>

        <h2 class="section-title">Projelerimiz</h2>
        <div class="projects-section">
            <div class="project-bubble">
                <img src="https://via.placeholder.com/260x150" alt="Cosmos Hub" class="project-img">
                <h3 class="project-title">Cosmos Hub</h3>
                <p class="project-info">Internet of Blockchains'in merkezi. Güvenli ve ölçeklenebilir blockchain ağı.</p>
                <div class="stats">
                    <span class="stat">APR: 21.5%</span>
                    <span class="stat">Uptime: 99.9%</span>
                </div>
            </div>

            <div class="project-bubble">
                <img src="https://via.placeholder.com/260x150" alt="Osmosis" class="project-img">
                <h3 class="project-title">Osmosis</h3>
                <p class="project-info">Cosmos ekosisteminin önde gelen DEX'i. Yüksek likidite ve düşük ücretler.</p>
                <div class="stats">
                    <span class="stat">APR: 23.8%</span>
                    <span class="stat">Uptime: 99.8%</span>
                </div>
            </div>

            <div class="project-bubble">
                <img src="https://via.placeholder.com/260x150" alt="Juno" class="project-img">
                <h3 class="project-title">Juno</h3>
                <p class="project-info">Akıllı sözleşme platformu. CosmWasm destekli geliştirici dostu ekosistem.</p>
                <div class="stats">
                    <span class="stat">APR: 25.2%</span>
                    <span class="stat">Uptime: 99.9%</span>
                </div>
            </div>
        </div>

        <div class="contact-form">
            <h3 class="form-title">İletişime Geçin</h3>
            <form action="mailto:your-email@example.com" method="POST" enctype="text/plain">
                <div class="form-group">
                    <input type="text" class="form-input" placeholder="Adınız" required>
                </div>
                <div class="form-group">
                    <input type="email" class="form-input" placeholder="E-mail Adresiniz" required>
                </div>
                <div class="form-group">
                    <textarea class="form-textarea" placeholder="Mesajınız" required></textarea>
                </div>
                <button type="submit" class="submit-btn">Gönder</button>
            </form>
        </div>
    </div>

    <footer class="footer">
        <div class="social-links">
            <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
            <a href="#" class="social-link"><i class="fab fa-telegram"></i></a>
            <a href="#" class="social-link"><i class="fab fa-github"></i></a>
        </div>
    </footer>

    <script>
        const canvas = document.getElementById('stars-canvas');
        const ctx = canvas.getContext('2d');

        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;

        const stars = [];
        const maxStars = 200;

        for (let i = 0; i < maxStars; i++) {
            stars.push({
                x: Math.random() * canvas.width,
                y: Math.random() * canvas.height,
                radius: Math.random() * 1 + 0.5,
                vx: Math.random() * 0.2 - 0.1,
                vy: Math.random() * 0.2 - 0.1
            });
        }

        let mouseX = 0;
        let mouseY = 0;

        function animate() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);

            stars.forEach(star => {
                star.x += star.vx + (mouseX - canvas.width / 2) * 0.0002;
                star.y += star.vy + (mouseY - canvas.height / 2) * 0.0002;

                if (star.x < 0 || star.x > canvas.width) star.vx = -star.vx;
                if (star.y < 0 || star.y > canvas.height) star.vy = -star.vy;

                ctx.beginPath();
                ctx.arc(star.x, star.y, star.radius, 0, Math.PI * 2);
                ctx.fillStyle = 'rgba(0, 100, 0, 0.6)';
                ctx.fill();
            });

            requestAnimationFrame(animate);
        }

        animate();

        window.addEventListener('mousemove', (event) => {
            mouseX = event.clientX;
            mouseY = event.clientY;
        });

        window.addEventListener('resize', () => {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });

        // Mouse parıltıları efekti
        const sparkles = [];
        const maxSparkles = 20;

        function createSparkle(x, y) {
            const sparkle = document.createElement('div');
            sparkle.className = 'mouse-sparkle';
            sparkle.style.left = x + 'px';
            sparkle.style.top = y + 'px';
            document.body.appendChild(sparkle);
            return sparkle;
        }

        function updateSparkles(x, y) {
            if (sparkles.length < maxSparkles) {
                sparkles.push(createSparkle(x, y));
            } else {
                const oldestSparkle = sparkles.shift();
                oldestSparkle.remove();
                sparkles.push(createSparkle(x, y));
            }

            sparkles.forEach((sparkle, index) => {
                const scale = 1 - index / maxSparkles;
                sparkle.style.transform = `scale(${scale})`;
                sparkle.style.opacity = scale;
            });
        }

        let lastMoveTime = 0;
        const moveInterval = 50; // Her 50 milisaniyede bir parıltı oluştur

        document.addEventListener('mousemove', (e) => {
            const currentTime = Date.now();
            if (currentTime - lastMoveTime > moveInterval) {
                updateSparkles(e.clientX, e.clientY);
                lastMoveTime = currentTime;
            }
        });
    </script>
</body>
</html>
