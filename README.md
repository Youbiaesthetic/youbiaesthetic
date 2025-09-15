```html
# 🌐 YoubiAesthetic - Portfolio & Services

Ce dépôt contient le site web **YoubiAesthetic**, un portfolio professionnel présentant les services esthétiques.

## 📞 Contact
- 📧 Email : [Youbiaesthetic@gmail.com](mailto:Youbiaesthetic@gmail.com)  
- 💼 LinkedIn : [Profil LinkedIn](https://www.linkedin.com/in/audrey-youbi-8b11ba1ba)  
- 🌍 Portfolio en ligne : [Lien GitHub Pages](https://USERNAME.github.io/REPOSITORY/)  

---

## 🖼 Aperçu
Le site comprend :
- Une **navbar** fixe
- Une section **Accueil**
- Une section **Services & Tarifs**
- Une section **À propos**
- Une section **Contact**
- Un **footer** avec les réseaux sociaux

---

## 💻 Code HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YoubiAesthetic - Esthétique à Coventry</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="logo">
            <img src="YoubiAesthetic_logo.png" alt="YoubiAesthetic_logo">
        </div>
        <ul class="nav-links">
            <li><a href="#home">Accueil</a></li>
            <li><a href="#services">Services & Tarifs</a></li>
            <li><a href="#about">À propos</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Accueil Section -->
    <section id="home" class="hero-section">
        <h1>Bienvenue chez YoubiAesthetic</h1>
        <p>Découvrez une expérience esthétique unique à Coventry.</p>
        <button onclick="window.location.href='mailto:Youbiaesthetic@gmail.com'">Prendre rendez-vous</button>
    </section>

    <!-- Services & Tarifs -->
    <section id="services">
        <h2>Nos Services & Tarifs</h2>
        <div class="service-list">
            <div class="service-item">
                <img src="photo2.jpg" alt="photo2">
                <h3>LIP FILLER</h3>
                <ul>
                    <li>0.5ML: £100</li>
                    <li>1ML: £150</li>
                </ul>
                <p>£30 consultation fee applies for anti-wrinkle treatments.</p>
            </div>

            <div class="service-item">
                <img src="photo1.jpg" alt="photo1">
                <h3>Anti-Wrinkle Treatment (Botox)</h3>
                <p>From £100</p>
            </div>

            <div class="service-item">
                <img src="https://images.squarespace-cdn.com/content/v1/61af7c40170a5d7dd8863ff2/6ebb4a14-edef-4bd0-a2b3-340166dce8cb/Aesthetician-performing-fat-dissolving--treatment.jpg" alt="Fat Dissolving">
                <h3>Fat Dissolving</h3>
                <p>Price upon consultation</p>
            </div>

            <div class="service-item">
                <img src="vitamins.jpg" alt="Vitamins">
                <h3>Vitamins</h3>
                <p>Price upon consultation</p>
            </div>

            <div class="service-item">
                <img src="https://www.pureholisticbeauty.co.uk/wp-content/uploads/2024/07/biotin-injections-benefits.png" alt="Biotin">
                <h3>Biotin</h3>
                <p>Price upon consultation</p>
            </div>

            <div class="service-item">
                <img src="https://th.bing.com/th/id/OIP.WwhxlNE54wNBH4m0-J_4CgHaDq?w=283&h=173&c=7&r=0&o=7&dpr=1.5&pid=1.7&rm=3" alt="Glutathione">
                <h3>Glutathione</h3>
                <p>Price upon consultation</p>
            </div>
        </div>
    </section>

    <!-- À propos -->
    <section id="about">
        <h2>À propos de nous</h2>
        <p>Notre clinique offre des services d'esthétique haut de gamme dans un cadre moderne et accueillant.</p>
        <p><a href="https://www.linkedin.com/in/audrey-youbi-8b11ba1ba">Suivez-nous sur LinkedIn</a></p>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contactez-nous</h2>
        <form action="mailto:Youbiaesthetic@gmail.com" method="POST" enctype="text/plain">
            <label for="name">Nom:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
        <div class="contact-info">
            <p>Email: <a href="mailto:Youbiaesthetic@gmail.com">Youbiaesthetic@gmail.com</a></p>
            <p>Téléphone: <a href="tel:+44 7404 555219">+44 7404 555219</a></p>
        </div>
        <div id="map">
            <h3>Nous trouver</h3>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1830.1077074477795!2d-1.4574634999999998!3d52.4024571!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48772bc8e08c3c27%3A0xfde8c8b689b7ed6b!2s17%20William%20McKee%20Close%2C%20Binley%2C%20Coventry%2C%20CV3%202RD%2C%20UK!5e0!3m2!1sen!2sus!4v1656079274793!5m2!1sen!2sus" width="600" height="450" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Suivez-nous sur les réseaux sociaux:</p>
        <div class="social-icons">
            <a href="https://www.tiktok.com/@youbiaesthetic?_t=ZN-8zk7gkanZ6U&_r=1"><img src="tiktok_icon.png" alt="TikTok"></a>
            <a href="https://www.instagram.com/youbiaesthetic"><img src="instagram_icon.png" alt="Instagram"></a>
            <a href="https://www.facebook.com/share/1CCV3CCuym/?mibextid=wwXIfr"><img src="facebook_icon.png" alt="Facebook"></a>
        </div>
    </footer>
</body>
</html>

```


```css
/* Reset de styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Navbar */
.navbar {
    position: fixed;
    width: 100%;
    top: 0;
    background-color: #333;
    padding: 10px 0;
    z-index: 1000;
}

.navbar .logo img {
    width: 120px;
    margin-left: 20px;
}

.navbar .nav-links {
    list-style: none;
    float: right;
    margin-right: 20px;
}

.navbar .nav-links li {
    display: inline-block;
    margin-left: 20px;
}

.navbar .nav-links a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Hero Section */
.hero-section {
    background-color: #3399ff;
    color: white;
    text-align: center;
    padding: 50px 20px;
}

.hero-section h1 {
    font-size: 40px;
}

.hero-section button {
    background-color: #ffcc00;
    padding: 10px 20px;
    border: none;
    font-size: 18px;
    cursor: pointer;
}

/* Services Section */
#services {
    padding: 50px 20px;
    text-align: center;
    background-color: #fff;
}

.service-list {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-top: 20px;
}

.service-item {
    background-color: #f4f4f4;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    transition: transform 0.3s ease;
}

.service-item:hover {
    transform: scale(1.05);
}

.service-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
}

.service-item h3 {
    font-size: 24px;
    margin: 15px 0;
    color: #333;
}

.service-item p {
    font-size: 16px;
    color: #555;
}

.service-item ul {
    list-style-type: none;
    margin: 10px 0;
    padding: 0;
}

.service-item ul li {
    font-size: 18px;
    color: #333;
    margin: 5px 0;
}

/* Contact Section */
#contact {
    background-color: #fff;
    padding: 50px 20px;
}

.contact-info p {
    font-size: 16px;
}

/* Social Media Icons */
.social-icons {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.social-icons a img {
    width: 40px;
}

/* Responsivité */
@media (max-width: 768px) {
    .navbar .nav-links {
        display: block;
        text-align: center;
    }

    .service-list {
        grid-template-columns: 1fr;
    }

    .hero-section h1 {
        font-size: 30px;
    }

    .service-item {
        padding: 10px;
    }

    .service-item h3 {
        font-size: 20px;
    }

    .service-item p {
        font-size: 14px;
    }
}

```
