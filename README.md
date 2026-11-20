# Commercial_Website_Using_FlexBox

# Ex02 Commercial Website
## Date: 08.11.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

### index.html
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Discover unique local kitchens and delicious food with Plate & Path.">

    <title>Plate & Path | Discover Your Next Favourite</title>

    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700;800&family=Playfair+Display:wght@600;700&display=swap"
          rel="stylesheet">
</head>

<body>

    <!-- NAVIGATION BAR -->
    <header>
        <nav class="navbar">

            <a href="#home" class="logo">
                plate<span>&</span>path.
            </a>

            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#discover">Discover</a>
                <a href="#about">Our Story</a>
                <a href="#contact">Contact</a>
            </div>

            <a href="#account" class="account-btn">
                My Account ↗
            </a>

        </nav>
    </header>


    <!-- HOMEPAGE -->
    <section id="home" class="hero">

        <div class="hero-content">

            <p class="eyebrow">
                GOOD FOOD. GREAT STORIES.
            </p>

            <h1>
                Every meal has
                <span>a story.</span>
            </h1>

            <p class="hero-description">
                Discover hidden kitchens, independent chefs
                and unforgettable flavours right around you.
            </p>

            <div class="hero-buttons">

                <a href="#discover" class="primary-btn">
                    Explore Food →
                </a>

                <a href="#about" class="secondary-btn">
                    Our Story
                </a>

            </div>

            <p class="hero-note">
                ✦ Made with love. Delivered with care.
            </p>

        </div>

        <div class="hero-image">

            <img
                src="https://images.unsplash.com/photo-1547592180-85f173990554?w=1000"
                alt="Freshly prepared delicious food"
            >

            <div class="image-tag">
                <strong>Freshly prepared</strong>
                <span>From local kitchens</span>
            </div>

        </div>

    </section>


    <!-- DISCOVER / PRODUCTS -->
    <section id="discover" class="discover section">

        <div class="section-heading">

            <div>
                <p class="eyebrow">THE FOOD JOURNEY</p>
                <h2>Something delicious awaits.</h2>
            </div>

            <p>
                Not just food. A collection of flavours
                worth discovering.
            </p>

        </div>


        <div class="food-container">

            <article class="food-card">

                <img
                    src="https://img.magnific.com/premium-photo/heritage-handi-biryani_1179130-15001.jpg"
                    alt="Indian biryani"
                >

                <div class="food-info">
                    <span class="food-category">LOCAL FAVOURITE</span>
                    <h3>Heritage Biryani</h3>
                    <p>Traditional spices, unforgettable flavour.</p>

                    <div class="food-bottom">
                        <strong>₹249</strong>
                        <a href="#account">Discover →</a>
                    </div>
                </div>

            </article>


            <article class="food-card">

                <img
                    src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=700"
                    alt="Gourmet burger"
                >

                <div class="food-info">
                    <span class="food-category">CHEF'S SPECIAL</span>
                    <h3>Signature Burger</h3>
                    <p>Handcrafted with fresh ingredients.</p>

                    <div class="food-bottom">
                        <strong>₹199</strong>
                        <a href="#account">Discover →</a>
                    </div>
                </div>

            </article>


            <article class="food-card">

                <img
                    src="https://images.unsplash.com/photo-1473093295043-cdd812d0e601?w=700"
                    alt="Italian pasta"
                >

                <div class="food-info">
                    <span class="food-category">COMFORT FOOD</span>
                    <h3>Garden Pasta</h3>
                    <p>A little Italian magic in every bite.</p>

                    <div class="food-bottom">
                        <strong>₹229</strong>
                        <a href="#account">Discover →</a>
                    </div>
                </div>

            </article>

        </div>

    </section>


    <!-- ABOUT US -->
    <section id="about" class="about section">

        <div class="about-image">

            <img
                src="https://images.unsplash.com/photo-1556911220-e15b29be8c8f?w=900"
                alt="Chef preparing food in a kitchen"
            >

        </div>

        <div class="about-content">

            <p class="eyebrow">MORE THAN A FOOD APP</p>

            <h2>
                Behind every dish,
                there's a person.
            </h2>

            <p>
                We believe the best food experiences aren't
                always found in the biggest restaurants.
                Sometimes, they're hidden in a small family
                kitchen or created by an independent chef.
            </p>

            <p>
                Plate & Path brings these kitchens closer
                to people who appreciate good food.
            </p>

            <a href="#contact" class="primary-btn">
                Get in Touch →
            </a>

        </div>

    </section>


    <!-- CONTACT -->
    <section id="contact" class="contact section">

        <div class="contact-heading">

            <p class="eyebrow">LET'S CONNECT</p>

            <h2>
                Have something cooking?
            </h2>

            <p>
                We'd love to hear from you.
            </p>

        </div>

        <div class="contact-container">

            <div class="contact-details">

                <h3>Reach out to us.</h3>

                <p>Email: hello@plateandpath.com</p>

                <p>Phone: +91 63660 XXXXX</p>

                <p>Location: Chennai, India</p>

            </div>


            <form class="contact-form">

                <input
                    type="text"
                    placeholder="Your name"
                    required
                >

                <input
                    type="email"
                    placeholder="Your email"
                    required
                >

                <textarea
                    placeholder="Tell us what's on your mind..."
                    rows="5"
                    required
                ></textarea>

                <button type="submit">
                    Send Message →
                </button>

            </form>

        </div>

    </section>


    <!-- USER ACCOUNT -->
    <section id="account" class="account section">

        <div class="account-content">

            <p class="eyebrow">YOUR FOOD JOURNEY</p>

            <h2>Your next favourite meal
                is waiting.
            </h2>

            <p>
                Create an account to explore local kitchens
                and keep track of your food discoveries.
            </p>

            <a href="mailto:hello@plateandpath.com"
               class="primary-btn">
                Join Plate & Path →
            </a>

        </div>

    </section>


    <!-- FOOTER -->
    <footer class="footer">

        <div class="footer-content">

            <div>
                <a href="#home" class="logo footer-logo">
                    plate<span>&</span>path.
                </a>

                <p>
                    Discover food. Discover people.
                    Discover stories.
                </p>
            </div>

            <div class="social-links">

                <a href="https://www.instagram.com/"
                   target="_blank"
                   rel="noopener noreferrer">
                    Instagram
                </a>

                <a href="https://www.facebook.com/"
                   target="_blank"
                   rel="noopener noreferrer">
                    Facebook
                </a>

                <a href="https://www.linkedin.com/"
                   target="_blank"
                   rel="noopener noreferrer">
                    LinkedIn
                </a>

            </div>

        </div>

        <div class="copyright">
            © 2026 Plate & Path. All rights reserved.
        </div>

    </footer>

</body>
</html>

```

### style.css
```

/* =====================================
   1. GLOBAL STYLES
===================================== */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    font-family: 'DM Sans', sans-serif;
    background-color: #faf8f2;
    color: #26352b;
    line-height: 1.6;
}

:root {
    --green: #234735;
    --dark-green: #183526;
    --orange: #e58b48;
    --cream: #faf8f2;
    --light: #f0eee5;
    --text: #26352b;
}

a {
    text-decoration: none;
    color: inherit;
}

img {
    width: 100%;
    display: block;
    object-fit: cover;
}

.section {
    padding: 100px 8%;
}

.eyebrow {
    color: var(--orange);
    font-size: 12px;
    font-weight: 800;
    letter-spacing: 2px;
    margin-bottom: 18px;
}


/* =====================================
   2. NAVIGATION BAR
===================================== */

header {
    background: var(--cream);
    position: sticky;
    top: 0;
    z-index: 100;
    border-bottom: 1px solid #eae8df;
}

.navbar {
    min-height: 80px;
    padding: 15px 8%;

    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 25px;
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 27px;
    font-weight: 700;
}

.logo span {
    color: var(--orange);
}

.nav-links {
    display: flex;
    align-items: center;
    gap: 35px;
}

.nav-links a {
    font-size: 14px;
    font-weight: 600;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: var(--orange);
}

.account-btn {
    background: var(--green);
    color: white;
    padding: 12px 22px;
    border-radius: 30px;
    font-size: 13px;
    font-weight: 600;
    transition: 0.3s;
}

.account-btn:hover {
    background: var(--orange);
    transform: translateY(-3px);
}


/* =====================================
   3. HERO SECTION
===================================== */

.hero {
    min-height: 620px;
    padding: 75px 8%;

    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 60px;
}

.hero-content {
    flex: 1;
}

.hero-content h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(42px, 5.5vw, 72px);
    line-height: 1.12;
    max-width: 600px;
    margin-bottom: 25px;
}

.hero-content h1 span {
    color: var(--orange);
    display: block;
}

.hero-description {
    max-width: 450px;
    color: #747b72;
    font-size: 16px;
    margin-bottom: 30px;
}

.hero-buttons {
    display: flex;
    align-items: center;
    gap: 15px;
    flex-wrap: wrap;
}

.primary-btn {
    display: inline-block;
    background: var(--green);
    color: white;
    padding: 15px 25px;
    border-radius: 5px;
    font-size: 14px;
    font-weight: 700;
    transition: all 0.3s ease;
}

.primary-btn:hover {
    background: var(--orange);
    transform: translateY(-4px);
}

.secondary-btn {
    padding: 14px 22px;
    border: 1px solid var(--green);
    border-radius: 5px;
    font-size: 14px;
    font-weight: 600;
    transition: 0.3s;
}

.secondary-btn:hover {
    background: var(--green);
    color: white;
}

.hero-note {
    margin-top: 35px;
    font-size: 12px;
    color: #82877c;
}

.hero-image {
    flex: 1;
    max-width: 550px;
    position: relative;
}

.hero-image img {
    height: 470px;
    border-radius: 180px 180px 12px 12px;
}

.image-tag {
    position: absolute;
    bottom: 25px;
    left: -30px;
    background: white;
    padding: 18px 25px;
    border-radius: 8px;
    box-shadow: 0 8px 30px #00000015;

    display: flex;
    flex-direction: column;
}

.image-tag span {
    font-size: 12px;
    color: #777;
}


/* =====================================
   4. DISCOVER SECTION
===================================== */

.discover {
    background: var(--light);
}

.section-heading {
    display: flex;
    justify-content: space-between;
    align-items: end;
    gap: 30px;
    margin-bottom: 45px;
}

.section-heading h2,
.about-content h2,
.contact-heading h2,
.account-content h2 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(30px, 4vw, 46px);
    line-height: 1.2;
}

.section-heading > p {
    max-width: 300px;
    color: #747b72;
}

.food-container {
    display: flex;
    gap: 28px;
    flex-wrap: wrap;
}

.food-card {
    flex: 1 1 260px;
    min-width: 0;
    background: white;
    border-radius: 10px;
    overflow: hidden;
    transition: transform 0.3s, box-shadow 0.3s;
}

.food-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 15px 35px #00000012;
}

.food-card img {
    height: 230px;
    transition: transform 0.5s;
}

.food-card:hover img {
    transform: scale(1.04);
}

.food-info {
    padding: 22px;
}

.food-category {
    color: var(--orange);
    font-size: 10px;
    font-weight: 800;
    letter-spacing: 1px;
}

.food-info h3 {
    font-family: 'Playfair Display', serif;
    font-size: 22px;
    margin: 8px 0;
}

.food-info p {
    color: #858980;
    font-size: 13px;
}

.food-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 22px;
}

.food-bottom strong {
    color: var(--green);
    font-size: 19px;
}

.food-bottom a {
    color: var(--orange);
    font-size: 13px;
    font-weight: 700;
}


/* =====================================
   5. ABOUT SECTION
===================================== */

.about {
    display: flex;
    align-items: center;
    gap: 80px;
}

.about-image,
.about-content {
    flex: 1;
}

.about-image img {
    height: 430px;
    border-radius: 8px;
}

.about-content h2 {
    margin-bottom: 25px;
}

.about-content > p:not(.eyebrow) {
    color: #777e73;
    margin-bottom: 18px;
    font-size: 15px;
}

.about-content .primary-btn {
    margin-top: 15px;
}


/* =====================================
   6. CONTACT SECTION
===================================== */

.contact {
    background: var(--light);
}

.contact-heading {
    text-align: center;
    margin-bottom: 55px;
}

.contact-heading > p:last-child {
    color: #777e73;
    margin-top: 12px;
}

.contact-container {
    display: flex;
    gap: 70px;
    justify-content: space-between;
}

.contact-details,
.contact-form {
    flex: 1;
}

.contact-details h3 {
    font-family: 'Playfair Display', serif;
    font-size: 26px;
    margin-bottom: 25px;
}

.contact-details p {
    margin-bottom: 18px;
    color: #73796e;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 16px;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 16px;
    border: 1px solid #deded3;
    background: white;
    border-radius: 5px;
    font-family: inherit;
    font-size: 14px;
    outline: none;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: var(--green);
}

.contact-form textarea {
    resize: vertical;
}

.contact-form button {
    padding: 16px;
    border: none;
    background: var(--green);
    color: white;
    font-size: 14px;
    font-weight: 700;
    cursor: pointer;
    transition: 0.3s;
    border-radius: 5px;
}

.contact-form button:hover {
    background: var(--orange);
}


/* =====================================
   7. ACCOUNT SECTION
===================================== */

.account {
    background: var(--green);
    color: white;
    text-align: center;
}

.account-content {
    max-width: 650px;
    margin: auto;
}

.account-content h2 {
    margin-bottom: 20px;
}

.account-content > p:not(.eyebrow) {
    color: #d2ddd4;
    margin-bottom: 30px;
}

.account .primary-btn {
    background: var(--orange);
}

.account .primary-btn:hover {
    background: white;
    color: var(--green);
}


/* =====================================
   8. FOOTER
===================================== */

.footer {
    background: var(--dark-green);
    color: white;
    padding: 55px 8% 20px;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 30px;
    flex-wrap: wrap;
}

.footer-logo {
    display: inline-block;
    margin-bottom: 12px;
}

.footer-content p {
    color: #bdc9bf;
    font-size: 13px;
}

.social-links {
    display: flex;
    gap: 25px;
    flex-wrap: wrap;
}

.social-links a {
    font-size: 13px;
    transition: color 0.3s;
}

.social-links a:hover {
    color: var(--orange);
}

.copyright {
    border-top: 1px solid #ffffff25;
    margin-top: 40px;
    padding-top: 20px;
    text-align: center;
    color: #aebbb0;
    font-size: 12px;
}


/* =====================================
   9. RESPONSIVE DESIGN
===================================== */

@media (max-width: 900px) {

    .navbar {
        flex-wrap: wrap;
    }

    .nav-links {
        gap: 18px;
    }

    .hero {
        gap: 30px;
    }

    .hero-image img {
        height: 380px;
    }

    .about {
        gap: 40px;
    }

    .contact-container {
        gap: 35px;
    }
}


@media (max-width: 650px) {

    .section {
        padding: 65px 6%;
    }

    .navbar {
        justify-content: center;
        padding: 18px 6%;
    }

    .logo {
        width: 100%;
        text-align: center;
    }

    .nav-links {
        justify-content: center;
        flex-wrap: wrap;
        gap: 15px;
    }

    .nav-links a {
        font-size: 12px;
    }

    .account-btn {
        display: none;
    }

    .hero {
        flex-direction: column;
        align-items: stretch;
        padding: 55px 6%;
    }

    .hero-image {
        max-width: 100%;
    }

    .hero-image img {
        height: 350px;
    }

    .image-tag {
        left: 10px;
    }

    .section-heading {
        flex-direction: column;
        align-items: flex-start;
    }

    .about {
        flex-direction: column;
        gap: 35px;
    }

    .about-image img {
        height: 300px;
    }

    .contact-container {
        flex-direction: column;
    }

    .footer-content {
        flex-direction: column;
        text-align: center;
    }

    .social-links {
        justify-content: center;
    }

}

```


## OUTPUT

### Home

![Home]("./output-01.png")

### Discover
![Discover]("./output-02.png")

### Our Story
![Our Story]("./output-03.png")

### Contact Us
![Contact Us]("./output-04.png")

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.