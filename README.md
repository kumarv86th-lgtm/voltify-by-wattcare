<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Voltify by WattCare | Electrical Service in Sanand & Ahmedabad</title>

<meta name="description" content="Voltify by WattCare provides reliable electrical services for homes, shops and small commercial spaces in Sanand and Ahmedabad.">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial,Helvetica,sans-serif;
    background:#f5f6f7;
    color:#10161c;
    line-height:1.6;
}

a{
    text-decoration:none;
    color:inherit;
}

header{
    position:sticky;
    top:0;
    z-index:1000;
    height:74px;
    padding:0 7%;
    display:flex;
    align-items:center;
    justify-content:space-between;
    background:#10161c;
    color:#fff;
    box-shadow:0 5px 25px #0003;
}

.logo{
    display:flex;
    align-items:center;
    gap:10px;
}

.logo-icon{
    width:40px;
    height:40px;
    border-radius:9px;
    background:#f7b500;
    color:#111;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:25px;
    font-weight:bold;
}

.logo h2{
    font-size:19px;
    letter-spacing:1.5px;
}

.logo small{
    display:block;
    color:#aaa;
    font-size:9px;
    letter-spacing:2px;
}

nav{
    display:flex;
    gap:28px;
    align-items:center;
}

nav a{
    color:#ddd;
    font-size:14px;
}

nav a:hover{
    color:#f7b500;
}

.call-btn{
    background:#f7b500;
    color:#111;
    padding:11px 18px;
    border-radius:6px;
    font-weight:bold;
}

.menu{
    display:none;
    font-size:28px;
    cursor:pointer;
}

/* HERO */

.hero{
    min-height:650px;
    padding:80px 7%;
    display:grid;
    grid-template-columns:1.15fr .85fr;
    gap:60px;
    align-items:center;
    background:
    radial-gradient(circle at 80% 20%,#fff2bf,transparent 30%),
    linear-gradient(135deg,#fafafa,#e9edf0);
}

.badge{
    display:inline-block;
    margin-bottom:18px;
    color:#8b6900;
    font-size:12px;
    letter-spacing:2px;
    font-weight:bold;
}

.hero h1{
    font-size:clamp(48px,7vw,82px);
    line-height:.98;
    letter-spacing:-4px;
    margin-bottom:25px;
}

.hero h1 span{
    color:#b67d00;
}

.hero p{
    max-width:650px;
    color:#626d75;
    font-size:17px;
}

.buttons{
    display:flex;
    gap:14px;
    margin:30px 0;
    flex-wrap:wrap;
}

.btn{
    padding:15px 25px;
    border-radius:6px;
    font-weight:bold;
    display:inline-block;
}

.primary{
    background:#10161c;
    color:white;
}

.primary:hover{
    background:#f7b500;
    color:#111;
}

.secondary{
    border:1px solid #aaa;
}

.trust{
    display:flex;
    flex-wrap:wrap;
    gap:22px;
    color:#59636b;
    font-size:12px;
}

/* HERO CARD */

.hero-card{
    background:#10161c;
    color:#fff;
    padding:35px;
    border-radius:22px;
    min-height:410px;
    box-shadow:0 25px 60px #0003;
}

.online{
    color:#72dc8b;
    font-size:11px;
    letter-spacing:1px;
}

.bolt{
    width:105px;
    height:105px;
    border-radius:50%;
    background:#f7b500;
    color:#111;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:58px;
    margin:30px 0 20px;
}

.hero-card h2{
    font-size:29px;
}

.hero-card p{
    color:#aaa;
    margin:10px 0 25px;
}

.quick{
    display:block;
    text-align:center;
    background:#f7b500;
    color:#111;
    padding:14px;
    border-radius:6px;
    font-weight:bold;
}

/* STATS */

.stats{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    background:#fff;
    padding:30px 7%;
    border-bottom:1px solid #ddd;
}

.stats div{
    text-align:center;
    border-right:1px solid #ddd;
}

.stats div:last-child{
    border:none;
}

.stats strong{
    display:block;
    font-size:27px;
}

.stats span{
    color:#68727b;
    font-size:13px;
}

/* SECTIONS */

section{
    padding:95px 7%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title small{
    color:#997100;
    letter-spacing:2px;
    font-weight:bold;
}

.section-title h2{
    font-size:48px;
    line-height:1.1;
    margin-top:10px;
    letter-spacing:-2px;
}

.section-title h2 span{
    color:#b67d00;
}

/* SERVICES */

.services{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:18px;
}

.service{
    background:#fff;
    padding:30px;
    border:1px solid #ddd;
    transition:.25s;
}

.service:hover{
    transform:translateY(-7px);
    box-shadow:0 18px 40px #0001;
}

.service-icon{
    width:50px;
    height:50px;
    border-radius:9px;
    background:#f1f2f3;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:25px;
    margin-bottom:18px;
}

.service h3{
    font-size:20px;
    margin-bottom:8px;
}

.service p{
    color:#68727b;
    font-size:14px;
}

/* BOOKING */

.booking{
    background:#e9edf0;
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:65px;
}

.booking h2{
    font-size:50px;
    line-height:1.05;
    letter-spacing:-2px;
    margin:14px 0;
}

.booking h2 span{
    color:#b67d00;
}

.booking-text{
    color:#657079;
    max-width:550px;
}

.contact-box{
    margin-top:30px;
    display:grid;
    gap:10px;
}

.contact-box a{
    font-weight:bold;
}

.form{
    background:#fff;
    padding:32px;
    border:1px solid #ddd;
    border-radius:10px;
}

.form label{
    display:block;
    font-size:12px;
    font-weight:bold;
    margin-bottom:13px;
}

.form input,
.form select,
.form textarea{
    width:100%;
    padding:13px;
    margin-top:6px;
    margin-bottom:16px;
    border:1px solid #d0d5d9;
    border-radius:5px;
    font:inherit;
}

.form textarea{
    min-height:100px;
    resize:vertical;
}

.form button{
    width:100%;
    border:0;
    cursor:pointer;
}

/* HOW */

.steps{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
}

.step{
    padding:30px;
    background:#fff;
    border:1px solid #ddd;
}

.step-number{
    font-size:12px;
    color:#9a7100;
    font-weight:bold;
}

.step h3{
    margin:12px 0 8px;
}

.step p{
    color:#68727b;
    font-size:14px;
}

/* WHY */

.why{
    background:#10161c;
    color:#fff;
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:70px;
}

.why h2{
    font-size:55px;
    line-height:1;
    letter-spacing:-2px;
}

.why h2 span{
    color:#f7b500;
}

.why p{
    color:#aaa;
    margin-top:20px;
}

.points{
    display:grid;
    gap:18px;
}

.point{
    border-bottom:1px solid #ffffff1c;
    padding-bottom:18px;
}

.point strong{
    display:block;
    color:#f7b500;
    margin-bottom:5px;
}

.point span{
    color:#bbb;
    font-size:14px;
}

/* AREAS */

.areas{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:12px;
}

.area{
    background:#fff;
    border:1px solid #ddd;
    padding:14px 22px;
    border-radius:30px;
    font-size:14px;
}

/* CTA */

.cta{
    margin:0 7% 80px;
    padding:65px;
    border-radius:20px;
    background:#f7b500;
    text-align:center;
}

.cta h2{
    font-size:45px;
    line-height:1.1;
    margin-bottom:12px;
}

.cta p{
    margin-bottom:25px;
}

.cta .btn{
    background:#10161c;
    color:white;
}

/* FOOTER */

footer{
    background:#10161c;
    color:#fff;
    padding:55px 7% 25px;
}

.footer-grid{
    display:grid;
    grid-template-columns:1.5fr 1fr 1fr;
    gap:50px;
}

footer h3{
    margin-bottom:14px;
}

footer p,
footer a{
    color:#aaa;
    font-size:14px;
}

footer a{
    display:block;
    margin:6px 0;
}

.copyright{
    border-top:1px solid #ffffff18;
    margin-top:40px;
    padding-top:20px;
    text-align:center;
    color:#777;
    font-size:12px;
}

/* FLOATING BUTTONS */

.float-buttons{
    position:fixed;
    right:18px;
    bottom:18px;
    z-index:999;
    display:flex;
    flex-direction:column;
    gap:10px;
}

.float-buttons a{
    width:52px;
    height:52px;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:22px;
    background:#10161c;
    color:#fff;
    box-shadow:0 8px 25px #0003;
}

.float-buttons a:hover{
    background:#f7b500;
    color:#111;
}

/* MOBILE */

@media(max-width:850px){

    header{
        padding:0 5%;
    }

    nav{
        display:none;
        position:absolute;
        top:74px;
        left:0;
        right:0;
        padding:20px;
        background:#10161c;
        flex-direction:column;
        gap:18px;
    }

    nav.active{
        display:flex;
    }

    .call-btn{
        display:none;
    }

    .menu{
        display:block;
    }

    .hero{
        grid-template-columns:1fr;
        padding:60px 5%;
    }

    .hero h1{
        font-size:55px;
    }

    .stats{
        grid-template-columns:repeat(2,1fr);
        gap:25px;
    }

    .stats div:nth-child(2){
        border:none;
    }

    section{
        padding:70px 5%;
    }

    .section-title h2{
        font-size:38px;
    }

    .services{
        grid-template-columns:1fr;
    }

    .booking{
        grid-template-columns:1fr;
        padding:70px 5%;
    }

    .booking h2{
        font-size:40px;
    }

    .steps{
        grid-template-columns:1fr;
    }

    .why{
        grid-template-columns:1fr;
        padding:70px 5%;
    }

    .why h2{
        font-size:45px;
    }

    .cta{
        margin:0 5% 60px;
        padding:45px 25px;
    }

    .cta h2{
        font-size:36px;
    }

    .footer-grid{
        grid-template-columns:1fr;
        gap:30px;
    }
}
</style>
</head>

<body>

<header>

<div class="logo">
    <div class="logo-icon">ϟ</div>
    <div>
        <h2>VOLTIFY</h2>
        <small>BY WATTCARE</small>
    </div>
</div>

<nav id="nav">
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#booking">Book Service</a>
    <a href="#why">Why Us</a>
    <a href="#contact">Contact</a>
</nav>

<a class="call-btn" href="tel:+919661951521">Call Now</a>

<div class="menu" onclick="toggleMenu()">☰</div>

</header>


<!-- HERO -->

<section class="hero" id="home">

<div>

<span class="badge">ELECTRICAL SERVICE • SANAND • AHMEDABAD</span>

<h1>
Electrical Problems.<br>
<span>Solved Fast.</span><br>
Done Right.
</h1>

<p>
Reliable electrical service for homes, shops and small commercial spaces.
From a faulty switch to MCB tripping, wiring, pumps and electrical panels —
Voltify by WattCare is built for safe and dependable work.
</p>

<div class="buttons">

<a href="#booking" class="btn primary">
Book a Service
</a>

<a href="tel:+919661951521" class="btn secondary">
☎ Call Now
</a>

</div>

<div class="trust">
<span>✓ Quick Response</span>
<span>✓ Reliable Work</span>
<span>✓ Fair Pricing</span>
<span>✓ Safety First</span>
</div>

</div>


<div class="hero-card">

<div class="online">● SERVICE REQUEST AVAILABLE</div>

<div class="bolt">ϟ</div>

<h2>Need an Electrician?</h2>

<p>
Tell us what is wrong. We will contact you and understand the problem.
</p>

<a href="#booking" class="quick">
REQUEST QUICK SERVICE →
</a>

</div>

</section>


<!-- STATS -->

<div class="stats">

<div>
<strong>⚡</strong>
<span>Electrical Service</span>
</div>

<div>
<strong>✓</strong>
<span>Safety Focused</span>
</div>

<div>
<strong>₹</strong>
<span>Fair Pricing</span>
</div>

<div>
<strong>24/7*</strong>
<span>Emergency Requests</span>
</div>

</div>


<!-- SERVICES -->

<section id="services">

<div class="section-title">
<small>WHAT WE DO</small>
<h2>Electrical Services<br><span>That You Can Trust.</span></h2>
</div>

<div class="services">

<div class="service">
<div class="service-icon">💡</div>
<h3>Light & Fan</h3>
<p>Light, fan, regulator, holder and basic electrical fault troubleshooting.</p>
</div>

<div class="service">
<div class="service-icon">⚡</div>
<h3>MCB & RCCB</h3>
<p>Tripping, short circuit, power failure and protection-device troubleshooting.</p>
</div>

<div class="service">
<div class="service-icon">🔌</div>
<h3>Switch & Socket</h3>
<p>Replacement and repair of switches, sockets, plugs and connections.</p>
</div>

<div class="service">
<div class="service-icon">🏠</div>
<h3>Wiring & Earthing</h3>
<p>Electrical wiring, loose connections, earthing checks and fault finding.</p>
</div>

<div class="service">
<div class="service-icon">💧</div>
<h3>Water Pump & Motor</h3>
<p>Basic electrical troubleshooting for domestic water pumps and motors.</p>
</div>

<div class="service">
<div class="service-icon">🏢</div>
<h3>Shop & Office</h3>
<p>Electrical maintenance for shops, offices and small commercial spaces.</p>
</div>

</div>

</section>


<!-- BOOKING -->

<section class="booking" id="booking">

<div>

<small class="badge">QUICK SERVICE REQUEST</small>

<h2>
Tell us the<br>
<span>problem.</span>
</h2>

<p class="booking-text">
Fill in the details below. Your request will open WhatsApp with a
ready-made message so you can send your service requirement quickly.
</p>

<div class="contact-box">
<a href="tel:+919661951521">☎ +91 96619 51521</a>
<a href="mailto:vkumar86th@gmail.com">✉ vkumar86th@gmail.com</a>
</div>

</div>


<div class="form">

<form onsubmit="sendWhatsApp(event)">

<label>
Your Name
<input id="name" type="text" placeholder="Enter your name" required>
</label>

<label>
Mobile Number
<input id="mobile" type="tel" placeholder="Enter mobile number" required>
</label>

<label>
Service Required
<select id="service" required>
<option value="">Select problem</option>
<option>Light / Fan Problem</option>
<option>MCB / RCCB Tripping</option>
<option>Short Circuit / Power Failure</option>
<option>Switch / Socket Problem</option>
<option>Wiring / Earthing</option>
<option>Water Pump / Motor</option>
<option>Shop / Office Electrical Work</option>
<option>Other Electrical Problem</option>
</select>
</label>

<label>
Location
<input id="location" type="text" placeholder="Sanand / Ahmedabad area" required>
</label>

<label>
Problem Description
<textarea id="problem" placeholder="Briefly describe the problem"></textarea>
</label>

<button class="btn primary" type="submit">
REQUEST SERVICE ON WHATSAPP →
</button>

</form>

</div>

</section>


<!-- HOW IT WORKS -->

<section>

<div class="section-title">
<small>SIMPLE PROCESS</small>
<h2>From Problem to<br><span>Solution.</span></h2>
</div>

<div class="steps">

<div class="step">
<span class="step-number">01 / TELL US</span>
<h3>Share the Problem</h3>
<p>Tell us what electrical issue you are facing.</p>
</div>

<div class="step">
<span class="step-number">02 / CONFIRM</span>
<h3>We Contact You</h3>
<p>We discuss your requirement and service location.</p>
</div>

<div class="step">
<span class="step-number">03 / DIAGNOSE</span>
<h3>Find the Cause</h3>
<p>The problem is checked before deciding the repair.</p>
</div>

<div class="step">
<span class="step-number">04 / FIX</span>
<h3>Safe & Reliable Work</h3>
<p>We aim for a proper and durable electrical solution.</p>
</div>

</div>

</section>


<!-- WHY -->

<section class="why" id="why">

<div>
<small class="badge">WHY VOLTIFY</small>

<h2>
Not Just a Repair.<br>
<span>A Better Service.</span>
</h2>

<p>
Our goal is simple: understand the electrical problem properly,
work safely and provide a practical solution at a fair price.
</p>
</div>


<div class="points">

<div class="point">
<strong>01 — Safety First</strong>
<span>Electrical safety is treated as the first priority during troubleshooting and repair.</span>
</div>

<div class="point">
<strong>02 — Clear Communication</strong>
<span>We explain the problem before proceeding with the work.</span>
</div>

<div class="point">
<strong>03 — Practical Solutions</strong>
<span>Focus on reliable repairs rather than unnecessary replacements.</span>
</div>

<div class="point">
<strong>04 — Fair Pricing</strong>
<span>Transparent communication about the work and expected charges.</span>
</div>

</div>

</section>


<!-- AREAS -->

<section>

<div class="section-title">
<small>SERVICE AREA</small>
<h2>Serving <span>Sanand & Ahmedabad</span></h2>
</div>

<div class="areas">

<div class="area">Sanand</div>
<div class="area">Sanand GIDC</div>
<div class="area">Ahmedabad</div>
<div class="area">Changodar</div>
<div class="area">Bavla</div>
<div class="area">Nearby Areas</div>

</div>

</section>


<!-- CTA -->

<div class="cta">

<h2>Got an Electrical Problem?</h2>

<p>
Don't let a small electrical problem become a bigger one.
Contact Voltify by WattCare.
</p>

<a href="https://wa.me/919661951521" class="btn">
WhatsApp Us →
</a>

</div>


<!-- FOOTER -->

<footer id="contact">

<div class="footer-grid">

<div>
<h3>⚡ VOLTIFY BY WATTCARE</h3>

<p>
Electrical Problems. Solved Fast. Done Right.
</p>

<p style="margin-top:12px;">
Electrical service for homes, shops and small commercial spaces.
</p>
</div>


<div>
<h3>Quick Links</h3>

<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#booking">Book Service</a>
<a href="#why">Why Us</a>
</div>


<div>
<h3>Contact</h3>

<a href="tel:+919661951521">
+91 96619 51521
</a>

<a href="mailto:vkumar86th@gmail.com">
vkumar86th@gmail.com
</a>

<a href="https://wa.me/919661951521">
WhatsApp
</a>

<p style="margin-top:10px;">
Sanand & Ahmedabad, Gujarat
</p>

</div>

</div>

<div class="copyright">
© 2026 Voltify by WattCare. All Rights Reserved.
</div>

</footer>


<!-- FLOATING BUTTONS -->

<div class="float-buttons">

<a href="tel:+919661951521" title="Call">
☎
</a>

<a href="https://wa.me/919661951521" title="WhatsApp">
☘
</a>

</div>


<script>

function toggleMenu(){
    document.getElementById("nav").classList.toggle("active");
}

function sendWhatsApp(event){

    event.preventDefault();

    const name = document.getElementById("name").value.trim();
    const mobile = document.getElementById("mobile").value.trim();
    const service = document.getElementById("service").value;
    const location = document.getElementById("location").value.trim();
    const problem = document.getElementById("problem").value.trim();

    const message =
`Hello Voltify by WattCare,

I need electrical service.

Name: ${name}
Mobile: ${mobile}
Service: ${service}
Location: ${location}
Problem: ${problem || "Not specified"}

Please contact me for service.`;

    const url =
    "https://wa.me/919661951521?text=" +
    encodeURIComponent(message);

    window.open(url, "_blank");
}

</script>

</body>
</html>
