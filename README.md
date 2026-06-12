<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spec & Feats TTRPG | Forge Your Legend</title>
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #ffffff;
            background-color: #050505; /* Deep Black Base */
            
            /* Textless Background Image */
            background-image: url('watermarked_img_847893073935689386.png');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            background-repeat: no-repeat;
            line-height: 1.6;
        }

        /* Banner / Header Styling */
        .landing-header {
            width: 100%;
            display: flex;
            justify-content: center;
            background-color: rgba(0, 0, 0, 0.7);
            border-bottom: 4px solid #8a2be2; /* Deep Purple Accent */
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.9);
            position: relative;
            z-index: 10;
        }

        .banner-img {
            width: 100%;
            max-width: 1200px;
            height: auto;
            display: block;
        }

        /* Main Content Container */
        .landing-container {
            max-width: 1000px;
            margin: 40px auto;
            padding: 0 20px;
            display: flex;
            flex-direction: column;
            gap: 40px; /* Space between sections */
        }

        /* Glassmorphism / Dark Panel Effect */
        .panel {
            background: rgba(15, 15, 15, 0.85);
            border: 2px solid #ff0055; /* Crimson Red Highlight */
            border-radius: 12px;
            padding: 40px;
            text-align: center;
            box-shadow: 0 8px 32px rgba(138, 43, 226, 0.3); /* Purple Glow */
            backdrop-filter: blur(8px);
        }

        .panel h1, .panel h2 {
            color: #ff0055; /* Red Headers */
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 20px;
        }

        .panel p {
            font-size: 1.15rem;
            color: #e0e0e0;
            margin-bottom: 20px;
        }

        /* Features Grid */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .feature-card {
            background: rgba(0, 0, 0, 0.6);
            border: 1px solid #8a2be2; /* Purple Border */
            padding: 20px;
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(255, 0, 85, 0.4); /* Red Glow on Hover */
        }

        .feature-card h3 {
            color: #8a2be2; /* Purple Sub-headers */
            margin-bottom: 10px;
        }

        .feature-card p {
            font-size: 1rem;
            margin-bottom: 0;
        }

        /* Call to Action Button */
        .cta-button {
            display: inline-block;
            background: linear-gradient(45deg, #ff0055, #8a2be2); /* Red to Purple Gradient */
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            font-weight: bold;
            padding: 15px 40px;
            border-radius: 50px;
            text-transform: uppercase;
            letter-spacing: 1px;
            border: none;
            cursor: pointer;
            transition: filter 0.3s ease, transform 0.2s ease;
            margin-top: 20px;
        }

        .cta-button:hover {
            filter: brightness(1.2);
            transform: scale(1.05);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.9);
            border-top: 2px solid #ff0055;
            margin-top: 40px;
            color: #888;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- Header Banner -->
    <header class="landing-header">
        <!-- Logo Banner Image -->
        <img src="watermarked_img_15367214306389380753.png" alt="Spec & Feats TTRPG Banner" class="banner-img">
    </header>

    <!-- Landing Page Content -->
    <main class="landing-container">
        
        <!-- Hero / Intro Section -->
        <section class="panel">
            <h1>Enter the System</h1>
            <p>Welcome to <strong>Spec & Feats</strong>, a tabletop roleplaying game designed for infinite customization, tactical combat, and epic storytelling. Whether you are wielding arcane magic or swinging a battleaxe, your build defines your legacy.</p>
        </section>

        <!-- Features Section -->
        <section class="panel">
            <h2>Why Play Spec & Feats?</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <h3>Deep Customization</h3>
                    <p>No strict classes. Mix and match specs, feats, and abilities to build a character that perfectly matches your playstyle.</p>
                </div>
                <div class="feature-card">
                    <h3>Tactical Combat</h3>
                    <p>Every decision matters. Utilize the battlefield, combo your skills, and outsmart your enemies.</p>
                </div>
                <div class="feature-card">
                    <h3>Epic Lore</h3>
                    <p>Step into a world torn between ancient magic and blazing chaos. Write your own legend in the ashes.</p>
                </div>
            </div>
        </section>

        <!-- Call to Action Section -->
        <section class="panel">
            <h2>Ready to Forge Your Legend?</h2>
            <p>The core rules, character tools, and quickstart guide are in development. Prepare your builds and get ready to dive into the adventure.</p>
            <a href="#" class="cta-button">Download Quickstart Guide</a>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 Spec & Feats TTRPG. All rights reserved.</p>
    </footer>

</body>
</html>
