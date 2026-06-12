<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spec & Feats TTRPG</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header Banner Section -->
    <header class="main-banner">
        <img src="watermarked_img_15367214306389380753.png" alt="Spec & Feats TTRPG Banner" class="banner-img">
    </header>

    <!-- Main Content Area -->
    <main class="content-container">
        <section class="welcome-box">
            <h2>Welcome to the System</h2>
            <p>Prepare your builds, calculate your proficiencies, and get ready to dive into the adventure. This space will house the core rules, character tools, and mechanics for the Spec & Feats TTRPG system.</p>
        </section>
    </main>

</body>
</html>


/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #ffffff;
    background-color: #0d0d0d;
    
    /* Using the textless image as the main page background */
    background-image: url('watermarked_img_847893073935689386.png');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    background-repeat: no-repeat;
    min-height: 100vh;
}

/* Banner Styling */
.main-banner {
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent backing */
    border-bottom: 3px solid #8a2be2; /* Crimson/Purple accent line */
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.7);
}

.banner-img {
    width: 100%;
    max-width: 1200px; /* Keeps the banner sharp on wider screens */
    height: auto;
    display: block;
}

/* Content Layout */
.content-container {
    max-width: 1000px;
    margin: 40px auto;
    padding: 20px;
    display: flex;
    justify-content: center;
}

/* Styled Content Box overlaying the background */
.welcome-box {
    background: rgba(20, 20, 20, 0.85); /* Dark tint to make text readable */
    border: 2px solid #ff0055; /* Crimson/Red highlight border */
    border-radius: 8px;
    padding: 30px;
    text-align: center;
    box-shadow: 0 0 20px rgba(138, 43, 226, 0.4); /* Subtle purple glow */
    backdrop-filter: blur(5px); /* Softens the background art behind text */
}

.welcome-box h2 {
    font-size: 2rem;
    margin-bottom: 15px;
    color: #ff0055;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.welcome-box p {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #e0e0e0;
}
