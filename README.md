<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HealthTrack - Your Health Companion</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation -->
    <header>
        <nav class="navbar">
            <div class="logo">HealthTrack</div>
            <ul class="nav-links">
                <li><a href="#features">Features</a></li>
                <li><a href="#community">Community</a></li>
                <li><a href="#download">Download</a></li>
            </ul>
            <a href="#download" class="cta-btn">Get the App</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Your Personalized Path to a Healthier Life</h1>
            <p>Track your fitness, nutrition, sleep, and more—all in one place.</p>
            <a href="#download" class="cta-btn hero-btn">Download the App</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <h2>App Features</h2>
        <div class="feature-cards">
            <div class="card">
                <img src="images/fitness.png" alt="Fitness Tracking">
                <h3>Fitness Tracking</h3>
                <p>Set and track your workouts, sync with wearables, and reach your fitness goals.</p>
            </div>
            <div class="card">
                <img src="images/nutrition.png" alt="Nutrition Guidance">
                <h3>Nutrition Guidance</h3>
                <p>Personalized meal plans and calorie tracking to support your diet goals.</p>
            </div>
            <div class="card">
                <img src="images/mindfulness.png" alt="Mindfulness & Mental Health">
                <h3>Mindfulness & Mental Health</h3>
                <p>Daily meditation guides and tools to reduce stress and improve well-being.</p>
            </div>
        </div>
    </section>

    <!-- Community Section -->
    <section id="community" class="community">
        <h2>Join the Community</h2>
        <p>Participate in health challenges, share your progress, and engage with a supportive community.</p>
    </section>

    <!-- Download Section -->
    <section id="download" class="download">
        <h2>Get Started Today!</h2>
        <p>Download HealthTrack from the App Store or Google Play and begin your health journey now.</p>
        <div class="app-buttons">
            <a href="#" class="app-store-btn">App Store</a>
            <a href="#" class="google-play-btn">Google Play</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 HealthTrack. All Rights Reserved.</p>
    </footer>
</body>
/* General Styling */
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

a {
    text-decoration: none;
    color: white;
}

h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

/* Navigation */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #2C3E50;
}

.logo {
    font-size: 24px;
    color: white;
    font-weight: 600;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links li {
    display: inline;
}

.cta-btn {
    background-color: #27AE60;
    padding: 10px 20px;
    border-radius: 25px;
    color: white;
    font-weight: 600;
}

.cta-btn:hover {
    background-color: #2ECC71;
}

/* Hero Section */
.hero {
    height: 100vh;
    background-image: url('images/hero-bg.jpg');
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
}

.hero-content {
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 48px;
}

.hero p {
    font-size: 20px;
    margin: 20px 0;
}

.hero-btn {
    font-size: 18px;
}

/* Features Section */
.features {
    padding: 50px;
    text-align: center;
    background-color: #f7f7f7;
}

.features h2 {
    font-size: 36px;
    margin-bottom: 40px;
}

.feature-cards {
    display: flex;
    justify-content: center;
    gap: 40px;
}

.card {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 300px;
}

.card img {
    max-width: 100px;
    margin-bottom: 20px;
}

.card h3 {
    font-size: 24px;
    margin-bottom: 10px;
}

.card p {
    color: #7f8c8d;
}

/* Community Section */
.community {
    background-color: #27AE60;
    color: white;
    padding: 50px;
    text-align: center;
}

.community h2 {
    font-size: 36px;
}

/* Download Section */
.download {
    padding: 50px;
    text-align: center;
}

.download h2 {
    font-size: 36px;
}

.app-buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.app-store-btn, .google-play-btn {
    background-color: #2C3E50;
    padding: 10px 20px;
    border-radius: 25px;
    color: white;
    font-weight: 600;
}

.app-store-btn:hover, .google-play-btn:hover {
    background-color: #34495E;
}

/* Footer */
footer {
    text-align: center;
    background-color: #2C3E50;
    padding: 20px;
    color: white;
}
