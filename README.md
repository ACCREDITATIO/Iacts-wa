<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>IACTS West Africa</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
<style>
    body {margin:0;font-family:'Montserrat',sans-serif;color:#333;background-color:#f9f9f9;scroll-behavior:smooth;}
    header {background:#0d47a1;color:#fff;padding:20px 0;text-align:center;position:relative;}
    header h1 {margin:0;font-size:2em;animation:fadeInDown 1s;}
    nav {background:#1565c0;padding:10px;text-align:center;position:sticky;top:0;z-index:100;}
    nav a {color:#fff;text-decoration:none;margin:0 15px;font-weight:600;transition:color 0.3s;}
    nav a:hover {color:#ffca28;}
    .hero {background:url('https://images.unsplash.com/photo-1529070538774-1843cb3265df?fit=crop&w=1200&q=80') no-repeat center center/cover;color:#fff;padding:120px 20px;text-align:center;animation:fadeIn 1s;}
    .hero h2 {font-size:2.5em;margin:0;animation:fadeInUp 1.5s;}
    .hero p {font-size:1.2em;margin-top:10px;animation:fadeInUp 2s;}
    section {padding:60px 20px;text-align:center;}
    section h2 {color:#0d47a1;margin-bottom:30px;position:relative;}
    .features {display:flex;flex-wrap:wrap;justify-content:center;gap:20px;}
    .feature-card {background:#fff;border-radius:10px;padding:20px;width:300px;box-shadow:0 5px 15px rgba(0,0,0,0.1);transition:transform 0.3s,box-shadow 0.3s;}
    .feature-card:hover {transform:translateY(-5px);box-shadow:0 10px 20px rgba(0,0,0,0.2);}
    .testimonial {background:#e3f2fd;border-left:5px solid #0d47a1;margin:20px auto;padding:20px;width:80%;border-radius:10px;font-style:italic;}
    .btn {background:#0d47a1;color:#fff;padding:12px 25px;border:none;border-radius:5px;text-decoration:none;font-weight:600;transition:background 0.3s;}
    .btn:hover {background:#ffca28;color:#0d47a1;}
    footer {background:#0d47a1;color:#fff;text-align:center;padding:20px 0;}
    @media(max-width:768px){.features {flex-direction:column;align-items:center;}}
    @keyframes fadeIn {from{opacity:0;}to{opacity:1;}}
    @keyframes fadeInUp {from{opacity:0;transform:translateY(30px);}to{opacity:1;transform:translateY(0);}}
    @keyframes fadeInDown {from{opacity:0;transform:translateY(-30px);}to{opacity:1;transform:translateY(0);}}

    /* Contact Section Styles */
    .contact-cards {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        margin-top: 40px;
    }
    .contact-card {
        background: #fff;
        border-radius: 15px;
        padding: 25px 20px;
        width: 250px;
        box-shadow: 0 5px 20px rgba(0,0,0,0.1);
        transition: transform 0.3s, box-shadow 0.3s;
        text-align: center;
    }
    .contact-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    }
    .contact-card .icon {
        font-size: 2em;
        margin-bottom: 10px;
        display: block;
        color: #0d47a1;
    }
    .contact-card h3 {
        margin: 10px 0;
        color: #0d47a1;
    }
    .contact-card a {
        color: #1565c0;
        text-decoration: none;
        transition: color 0.3s;
    }
    .contact-card a:hover {
        color: #ffca28;
    }
    @media(max-width:768px){
        .contact-cards {flex-direction: column;align-items: center;}
    }

    /* Back to Top Button */
    #topBtn {
        display: none;
        position: fixed;
        bottom: 40px;
        right: 40px;
        z-index: 99;
        font-size: 18px;
        border: none;
        outline: none;
        background-color: #0d47a1;
        color: white;
        cursor: pointer;
        padding: 15px;
        border-radius: 50%;
        transition: background-color 0.3s;
    }
    #topBtn:hover {background-color: #ffca28;color:#0d47a1;}
</style>
</head>
<body>

<header>
    <h1>International Accreditation Commission for Theological Seminaries – West Africa</h1>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#admission">Admissions</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero">
    <h2>Accrediting Excellence in Theological Education</h2>
    <p>Join the network of accredited Bible schools, seminaries, and theological colleges across West Africa.</p>
    <a href="#admission" class="btn">Apply Now</a>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>IACTS-WA is committed to promoting <strong>high standards in theological education</strong>. We offer accreditation, mentorship, and guidance to Bible schools, seminaries, and colleges to strengthen credibility, quality, and academic excellence.</p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="features">
        <div class="feature-card">
            <h3>Institutional Accreditation</h3>
            <p>Comprehensive accreditation process aligned with international standards.</p>
        </div>
        <div class="feature-card">
            <h3>Quality Assurance</h3>
            <p>Ensuring curriculum, faculty, and facilities meet globally recognized standards.</p>
        </div>
        <div class="feature-card">
            <h3>Capacity Building</h3>
            <p>Training, mentorship, and development programs for staff and leadership.</p>
        </div>
        <div class="feature-card">
            <h3>Networking & Support</h3>
            <p>Connect with other accredited institutions across West Africa for partnerships.</p>
        </div>
        <div class="feature-card">
            <h3>Downloadable Resources</h3>
            <p>Access application forms, guidelines, and resources for accreditation and admissions.</p>
        </div>
        <div class="feature-card">
            <h3>Social Media & Promotion</h3>
            <p>Get listed on our website and social platforms to boost visibility and student recruitment.</p>
        </div>
    </div>
</section>

<section id="admission">
    <h2>Admissions Open</h2>
    <p>We welcome applications from Bible schools, seminaries, and Bible colleges seeking accreditation and recognition. Start your accreditation journey today!</p>
    <a href="forms/IACTS_Application_Form.pdf" class="btn" download>Download Application Form</a>
</section>

<section id="testimonials">
    <h2>Testimonials</h2>
    <div class="testimonial">
        "IACTS-WA accreditation gave our seminary credibility and opened doors for international partnerships." – <strong>Pastor Michael, Lagos</strong>
    </div>
    <div class="testimonial">
        "Their mentorship and support helped us improve our curriculum and faculty training." – <strong>Rev. Sarah, Accra</strong>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-cards">
        <div class="contact-card">
            <span class="icon">📧</span>
            <h3>Email</h3>
            <p><a href="mailto:obatimehinfolorunso@gmail.com">obatimehinfolorunso@gmail.com</a></p>
        </div>
        <div class="contact-card">
            <span class="icon">📱</span>
            <h3>Phone</h3>
            <p><a href="tel:+2348168931335">+2348168931335</a> & <a href="tel:+2348071033135">+2348071033135</a></p>
        </div>
        <div class="contact-card">
            <span class="icon">🌐</span>
            <h3>Website</h3>
            <p><a href="https://www.iacts-westafrica.org" target="_blank">iacts-westafrica.org</a></p>
        </div>
        <div class="contact-card">
            <span class="icon">📍</span>
            <h3>Address</h3>
            <p>[Insert Address]</p>
        </div>
        <div class="contact-card">
            <span class="icon">🔗</span>
            <h3>Social Media</h3>
            <p><a href="https://www.facebook.com/share/19NH83gS1h/" target="_blank">Facebook</a></p>
        </div>
    </div>
</section>

<footer>
    &copy; 2025 IACTS – West Africa | All Rights Reserved
</footer>

<!-- Back to Top Button -->
<button onclick="topFunction()" id="topBtn" title="Go to top">⬆️</button>

<script>
    //Get the button
    var topBtn = document.getElementById("topBtn");

    // When the user scrolls down 300px, show the button
    window.onscroll = function() {scrollFunction()};
    function scrollFunction() {
        if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
            topBtn.style.display = "block";
        } else {
            topBtn.style.display = "none";
        }
    }

    // Scroll to top when clicked
    function topFunction() {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
    }
</script>

</body>
</html>
