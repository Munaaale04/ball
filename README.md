<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Volleyball Club</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
    }

    body {
        background-color: #f4f8fb;
        color: #333;
    }

    header {
        background: #005f99;
        color: white;
        padding: 20px;
        text-align: center;
    }

    header h1 {
        font-size: 2.5rem;
    }

    nav {
        margin-top: 10px;
    }

    nav a {
        color: white;
        text-decoration: none;
        margin: 0 15px;
        font-weight: 600;
    }

    .hero {
        height: 80vh;
        background: url('https://images.unsplash.com/photo-1599058917212-d750089bc07e') no-repeat center center/cover;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        color: white;
    }

    .hero h2 {
        background: rgba(0,0,0,0.6);
        padding: 20px 30px;
        border-radius: 10px;
        font-size: 2rem;
    }

    .section {
        padding: 50px 20px;
        text-align: center;
    }

    .cards {
        display: flex;
        justify-content: center;
        gap: 30px;
        flex-wrap: wrap;
        margin-top: 30px;
    }

    .card {
        background: white;
        width: 280px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        overflow: hidden;
        transition: 0.3s;
    }

    .card:hover {
        transform: translateY(-10px);
    }

    .card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }

    .card h3 {
        padding: 15px;
        color: #005f99;
    }

    footer {
        background: #005f99;
        color: white;
        text-align: center;
        padding: 15px;
        margin-top: 30px;
    }

    @media (max-width: 768px) {
        .hero h2 {
            font-size: 1.5rem;
        }
    }
</style>
</head>
<body>

<header>
    <h1>Elite Volleyball Club</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Teams</a>
        <a href="#">Gallery</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Feel the Power. Play the Game.</h2>
</section>

<section class="section">
    <h2>Our Highlights</h2>
    <div class="cards">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1521417531039-4e6c5b1e33c5" alt="Volleyball Match">
            <h3>Competitive Matches</h3>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1508804185872-d7badad00f7d" alt="Volleyball Training">
            <h3>Professional Training</h3>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1505253213348-cd54c35b9a7b" alt="Beach Volleyball">
            <h3>Beach Volleyball</h3>
        </div>
    </div>
</section>

<footer>
    <p>© 2026 Elite Volleyball Club | All Rights Reserved</p>
</footer>

</body>
</html>
