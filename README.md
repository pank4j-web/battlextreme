<!DOCTYPE html>
<html lang="en">
    <head>

        <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BattleXtreme</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 0; padding: 0; }
        header { background: #222; color: #fff; padding: 15px; font-size: 24px; }
        nav a { margin: 10px; color: white; text-decoration: none; }
        section { padding: 20px; }
        footer { background: #222; color: white; padding: 10px; margin-top: 20px; }
        .container { max-width: 800px; margin: auto; }
        .btn { display: inline-block; padding: 10px 20px; background: #ff9800; color: white; text-decoration: none; margin-top: 10px; }
        .banner { width: 100%; max-width: 800px; height: auto; display: auto; margin: auto; }
        
    </style>
</head>
<body>
    <header>
        BattleXtreme
        <nav>
            <a href="#home">Home</a>
            <a href="#register">Register</a>
            <a href="#leaderboard">Leaderboard</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    
    <section id="home">
        <div class="container">
            <img src="bgmi-banner.jpg" alt="BGMI Tournament Banner" class="banner">
            <h2>Welcome to the Ultimate BattleXtreme Tournament!</h2>
            <p>Join and compete for glory.</p>
            <a href="#register" class="btn">Register Now</a>
        </div>
    </section>

    <section id="register">
        <div class="container">
            <h2>Register for the Tournament</h2>
            <form>
                <input type="text" placeholder="Player Name" required><br><br>
                <input type="text" placeholder="In-Game ID" required><br><br>
                <input type="email" placeholder="Email" required><br><br>
                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </section>

    <section id="leaderboard">
        <div class="container">
            <h1>Leaderboard</h1>
            <h2>Top players will be displayed here!</h2>
            <h3>week 1 winners are :</h3>
            <p>1. prashant</p>
            <p>2. pankaj</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: support@battlextreme.com</p>
        </div>
    </section>

    <footer>
        &copy; 2025 BattleXtreme | All Rights Reserved
    </footer>
</body>
</html>
