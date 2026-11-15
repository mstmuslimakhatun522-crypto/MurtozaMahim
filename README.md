# MurtozaMahim

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Murtoza Mahim | Self Development</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #0b1020;
    color: #edf2ff;
    line-height: 1.7;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

/* Navigation */

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 25px 0;
}

.logo {
    font-size: 25px;
    font-weight: bold;
    color: #65e0c2;
}

nav a {
    color: #ddd;
    text-decoration: none;
    margin-left: 22px;
}

nav a:hover {
    color: #65e0c2;
}

/* Hero Section */

.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    padding: 70px 0;
}

.hero-text {
    flex: 1;
}

.hero-text h4 {
    color: #65e0c2;
    letter-spacing: 3px;
}

.hero-text h1 {
    font-size: 65px;
    line-height: 1.1;
    margin: 20px 0;
}

.hero-text h1 span {
    color: #8b9cff;
}

.hero-text p {
    color: #aab6d2;
    font-size: 17px;
}

.btn {
    display: inline-block;
    margin-top: 25px;
    padding: 12px 25px;
    background: #8b9cff;
    color: #0b1020;
    border-radius: 10px;
    text-decoration: none;
    font-weight: bold;
}

/* My Pictures */

.photo-box {
    flex: 1;
    background: #151f38;
    padding: 15px;
    border-radius: 20px;
    border: 1px solid #303b55;
}

.photos {
    display: flex;
    gap: 10px;
}

.photos img {
    width: 50%;
    height: 320px;
    object-fit: cover;
    border-radius: 12px;
}

.photo-box p {
    text-align: center;
    color: #aab6d2;
    margin-top: 12px;
}

/* Sections */

section {
    padding: 55px 0;
}

.section-title {
    font-size: 35px;
    margin-bottom: 10px;
}

.subtitle {
    color: #aab6d2;
    margin-bottom: 25px;
}

/* Cards */

.cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.card {
    background: #151f38;
    padding: 25px;
    border-radius: 15px;
    border: 1px solid #303b55;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-7px);
    border-color: #65e0c2;
}

.card h3 {
    margin-bottom: 10px;
    color: #8b9cff;
}

.card p {
    color: #aab6d2;
}

/* Profile Table */

.profile {
    background: #151f38;
    padding: 25px;
    border-radius: 15px;
}

table {
    width: 100%;
    border-collapse: collapse;
}

th, td {
    padding: 15px;
    text-align: left;
    border-bottom: 1px solid #303b55;
}

th {
    color: #65e0c2;
}

/* Lists */

.list-box {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
}

ul, ol {
    padding-left: 25px;
    color: #aab6d2;
}

li {
    padding: 7px 0;
}

/* Quote */

.quote {
    background: #142d36;
    border-left: 4px solid #65e0c2;
    padding: 25px;
    border-radius: 10px;
    font-size: 20px;
    margin-top: 25px;
}

/* Footer */

footer {
    text-align: center;
    padding: 30px;
    margin-top: 50px;
    border-top: 1px solid #303b55;
    color: #aab6d2;
}

/* Responsive */

@media(max-width: 750px) {
    .hero {
        flex-direction: column;
    }

    .hero-text h1 {
        font-size: 45px;
    }

    .cards {
        grid-template-columns: 1fr;
    }

    .list-box {
        grid-template-columns: 1fr;
    }

    nav a {
        margin-left: 8px;
        font-size: 13px;
    }

    .photos img {
        height: 230px;
    }
}
</style>
</head>

<body>

<div class="container">

<!-- Navigation -->
<header>
    <div class="logo">MAHIM.</div>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#growth">Growth</a>
        <a href="#goals">Goals</a>
    </nav>
</header>

<!-- Hero Section -->
<div class="hero" id="home">

    <div class="hero-text">

        <h4>WELCOME TO MY PERSONAL WEBSITE</h4>

        <h1>
            Murtoza <br>
            <span>Mahim.</span>
        </h1>

        <p>
            I believe that self-development is a lifelong journey.
            Every day is a new opportunity to learn something,
            improve myself and become a better person.
        </p>

        <a href="#about" class="btn">
            Explore My Journey
        </a>

    </div>

    <div class="photo-box">

        <div class="photos">
            <img src="mirror.png"
                 style="object-position:left;"
                 alt="Mahim Photo 1">

            <img src="mirror.png"
                 style="object-position:right;"
                 alt="Mahim Photo 2">
        </div>

        <p>Small Steps. Big Dreams. Better Future.</p>

    </div>

</div>

<!-- About Me -->
<section id="about">

    <h2 class="section-title">About Me</h2>

    <p class="subtitle">
        Here is some information about me.
    </p>

    <div class="profile">

        <table>

            <tr>
                <th>Full Name</th>
                <td>Murtoza Mahim</td>
            </tr>

            <tr>
                <th>Roll Number</th>
                <td>23</td>
            </tr>

            <tr>
                <th>House</th>
                <td>Bakul</td>
            </tr>

            <tr>
                <th>Personal Focus</th>
                <td>Self Development</td>
            </tr>

            <tr>
                <th>Mindset</th>
                <td>Positive and Growth Oriented</td>
            </tr>

        </table>

    </div>

    <div class="quote">
        "Your only competition is the person you were yesterday."
    </div>

</section>

<!-- Self Development -->
<section id="growth">

    <h2 class="section-title">My Self Development</h2>

    <p class="subtitle">
        The qualities I want to build in myself.
    </p>

    <div class="cards">

        <div class="card">
            <h3>📚 Continuous Learning</h3>
            <p>
                I want to learn new things every day,
                improve my knowledge and develop new skills.
            </p>
        </div>

        <div class="card">
            <h3>⏳ Time Management</h3>
            <p>
                Time is valuable. I want to use my time
                wisely and focus on important things.
            </p>
        </div>

        <div class="card">
            <h3>💪 Discipline</h3>
            <p>
                Discipline helps me stay focused,
                consistent and responsible.
            </p>
        </div>

        <div class="card">
            <h3>🧠 Positive Thinking</h3>
            <p>
                I believe that a positive mindset
                can help me overcome challenges.
            </p>
        </div>

        <div class="card">
            <h3>🤝 Good Character</h3>
            <p>
                Respect, honesty and kindness
                are important parts of a good personality.
            </p>
        </div>

        <div class="card">
            <h3>🌱 Self Confidence</h3>
            <p>
                I want to believe in myself,
                face challenges and never give up.
            </p>
        </div>

    </div>

</section>

<!-- My Goals -->
<section id="goals">

    <h2 class="section-title">My Goals & Habits</h2>

    <p class="subtitle">
        My daily actions will shape my future.
    </p>

    <div class="list-box">

        <div class="card">

            <h3>My Daily Habits</h3>

            <ul>
                <li>Wake up with a positive mindset.</li>
                <li>Study with full concentration.</li>
                <li>Learn something new every day.</li>
                <li>Manage my time properly.</li>
                <li>Stay healthy and active.</li>
                <li>Review my daily progress.</li>
            </ul>

        </div>

        <div class="card">

            <h3>My Personal Rules</h3>

            <ol>
                <li>Never stop learning.</li>
                <li>Never give up on my dreams.</li>
                <li>Respect everyone.</li>
                <li>Learn from my mistakes.</li>
                <li>Choose progress over perfection.</li>
                <li>Stay humble and disciplined.</li>
            </ol>

        </div>

    </div>

</section>

<!-- Growth Plan -->
<section>

    <h2 class="section-title">My Growth Plan</h2>

    <p class="subtitle">
        Four simple steps towards a better future.
    </p>

    <div class="cards">

        <div class="card">
            <h3>01. Set Goals</h3>
            <p>Know what I want to achieve in life.</p>
        </div>

        <div class="card">
            <h3>02. Take Action</h3>
            <p>Start working instead of just dreaming.</p>
        </div>

        <div class="card">
            <h3>03. Stay Consistent</h3>
            <p>Keep working even when things get difficult.</p>
        </div>

    </div>

</section>

<!-- Footer -->
<footer>

    <h3>Murtoza Mahim</h3>

    <p>Roll: 23 | House: Bakul</p>

    <p>
        Becoming a better version of myself,
        one day at a time.
    </p>

    <p>© 2026 Murtoza Mahim. All Rights Reserved.</p>

</footer>

</div>

</body>
</html>
