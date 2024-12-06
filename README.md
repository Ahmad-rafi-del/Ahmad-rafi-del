- 👋 Hi, I’m @Ahmad-rafi-del
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Ahmad-rafi-del/Ahmad-rafi-del is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmad Rafi Arifuddin - UI/UX Designer</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header class="header">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="home" id="home">
        <div class="teks-content">AHMAD RAFI ARIFUDDIN</div>
        <div class="home-content">
            <div class="home-img">
                <img src="386.jpg" alt="Profile Picture">
            </div>
            <h1>Hi, It's <span class="name">Rafi</span></h1>
            <p class="profession">UI / UX Designer</p>
            <p class="description">Crafting intuitive and visually stunning digital experiences. I blend creativity with user-centric design to bring your ideas to life.</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-dribbble"></i></a>
            </div>
        </div>
    </section>

    <section class="about" id="about">
<div class="flip-card">
    <div class="flip-card-inner">
        <div class="flip-card-front">
            <p class="title">About me</p>
            <p>Hover Me</p>
        </div>
        <div class="flip-card-back">
            <p>With over 5 years of experience in UI/UX design, I've honed my skills in creating user-friendly interfaces that not only look great but also provide seamless experiences. My passion lies in solving complex design challenges and turning them into simple, elegant solutions.</p>
        </div>
    </div>
</div>
    </section>

    <section class="services" id="services">
        <h2>My Services</h2>
        <div class="service-grid">
            <div class="service-item">
                <div class="service-icon"><i class="fas fa-desktop"></i></div>
                <h3>UI Design</h3>
                <p>Creating visually appealing and intuitive user interfaces for web and mobile applications.</p>
            </div>
            <div class="service-item">
                <div class="service-icon"><i class="fas fa-user-friends"></i></div>
                <h3>UX Design</h3>
                <p>Enhancing user satisfaction by improving the usability and accessibility of digital products.</p>
            </div>
            <div class="service-item">
                <div class="service-icon"><i class="fas fa-mobile-alt"></i></div>
                <h3>Mobile App Design</h3>
                <p>Designing responsive and user-friendly mobile applications for iOS and Android platforms.</p>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Get In Touch</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer class="footer">
        <p>© 2024 Ahmad Rafi Arifuddin - UI/UX Designer. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #0a0a0a;
    color: #fff;
    overflow-x: hidden;
}

.header {
    position: fixed;
    top: 0;
    width: 100%;
    background-color: rgba(17, 17, 17, 0.8);
    backdrop-filter: blur(10px);
    z-index: 1000;
    transition: background-color 0.3s;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    padding: 15px 20px;
    transition: color 0.3s, background-color 0.3s;
    border-radius: 5px;
}

nav ul li a:hover {
    color: #ff0;
    background-color: rgba(255, 255, 0, 0.1);
}

.teks-content {
            position: absolute;
            align-items: center;
            justify-content: center;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 5em;
            color: rgba(255, 255, 0, 0.1);
            white-space: nowrap;
            z-index: -1;
            ciolor:yellow;
        }

        .home {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background: linear-gradient(45deg, #000, #111);
            text-align: center;
            overflow: hidden;
        }

        .home-content {
            max-width: 800px;
            padding: 20px;
            position: relative;
            z-index: 1;
        }

        .home-img img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 5px solid #ff0;
            box-shadow: 0 0 20px #ff0;
            transition: all 0.3s;
        }

        .home-img img:hover {
            box-shadow: 0 0 40px #ff0;
            transform: scale(1.05);
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

.name {
    color: #ff0;
    font-weight: bold;
}

.profession {
    color: #ff0;
    font-size: 1.5em;
    margin-bottom: 20px;
}

.description {
    font-size: 1.1em;
    line-height: 1.6;
    margin-bottom: 30px;
}

.social-icons {
    margin-top: 20px;
}

.social-icons a {
    color: #ff0;
    margin: 0 15px;
    font-size: 28px;
    transition: all 0.3s;
}

.social-icons a:hover {
    color: #fff;
    transform: translateY(-5px);
}

.about, .services, .contact {
    padding: 100px 50px;
    text-align: center;
}

/* From Uiverse.io by joe-watson-sbf */ 
.flip-card {
  position: center;
  background-color: transparent;
  width: 360px;
  height: 274px;
  perspective: 1000px;
  font-family: sans-serif;
}

.title {
  font-size: 1.5em;
  font-weight: 900;
  text-align: center;
  margin: 0;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  box-shadow: 0 8px 14px 0 rgba(0,0,0,0.2);
  position: absolute;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  border: 1px solid yellow;
  border-radius: 1rem;
}

.flip-card-front {
  background: linear-gradient(120deg, rgba(255, 255, 255, 0.1) 60%, yellow 88%,
     rgb(255, 211, 195) 40%, yellow 48%);
  color: yellow;
}

.flip-card-back {
  background: linear-gradient(120deg, rgba(255, 255, 255, 0.1) 30%, black 88%,
     black 40%, black 78%);
  color: white;
  transform: rotateY(180deg);
}
.services {
    background-color: #0a0a0a;
}

.contact {
    background-color: #111;
}

h2 {
    font-size: 2.5em;
    margin-bottom: 30px;
    color: #ff0;
}

.service-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-top: 50px;
}

.service-item {
    background-color: rgba(255, 255, 0, 0.1);
    padding: 30px;
    border-radius: 10px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.service-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 20px rgba(255, 255, 0, 0.2);
}

.service-icon {
    font-size: 40px;
    color: #ff0;
    margin-bottom: 20px;
}

form {
    max-width: 500px;
    margin: 0 auto;
}

input, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    background-color: rgba(255, 255, 255, 0.1);
    border: none;
    border-radius: 5px;
    color: #fff;
}

/* From Uiverse.io by Navarog21 */ 
button {
  width: 10em;
  position: relative;
  height: 3.5em;
  border: 3px ridge yellow;
  outline: none;
  background-color: transparent;
  color: yellow;
  transition: 1s;
  border-radius: 0.3em;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
}

button::after {
  content: "";
  position: absolute;
  top: -10px;
  left: 3%;
  width: 95%;
  height: 40%;
  background-color: #111;
  transition: 0.5s;
  transform-origin: center;
}

button::before {
  content: "";
  transform-origin: center;
  position: absolute;
  top: 80%;
  left: 3%;
  width: 95%;
  height: 40%;
  background-color: #111;
  transition: 0.5s;
}

button:hover::before, button:hover::after {
  transform: scale(0)
}

button:hover {
  box-shadow: inset 0px 0px 25px yellow;
}

.footer {
    background-color: #000;
    text-align: center;
    padding: 20px;
    font-size: 0.9em;
}

@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
    }

    nav ul li {
        margin: 10px 0;
    }

    .home-content {
        padding: 10px;
    }

    h1 {
        font-size: 2.5em;
    }

    .about, .services, .contact {
        padding: 50px 20px;
    }

    .teks-content {
        font-size: 3em;
    }
}
</html>
