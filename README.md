<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#073b75">

<title>ALL INDIA BANKING | Banking Services & Latest Updates</title>

<meta name="description"
content="ALL INDIA BANKING - Bank account opening assistance, BC/CSP information, banking services, documents and latest updates.">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, "Noto Sans Devanagari", sans-serif;
    background: #f4f7fb;
    color: #172337;
    line-height: 1.7;
}

:root {
    --blue: #073b75;
    --dark: #05264c;
    --gold: #f4b942;
    --white: #ffffff;
    --green: #128c4b;
}

a {
    text-decoration: none;
}

header {
    background: linear-gradient(120deg, var(--dark), #1265aa);
    color: white;
    padding: 22px 15px;
    text-align: center;
}

.logo {
    font-size: 29px;
    font-weight: 900;
    letter-spacing: 1px;
}

.logo span {
    color: var(--gold);
}

.tagline {
    font-size: 14px;
    margin-top: 5px;
}

nav {
    background: #ffffff;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 5px;
    padding: 10px;
    box-shadow: 0 3px 12px #00000012;
    position: sticky;
    top: 0;
    z-index: 100;
}

nav a {
    color: var(--blue);
    padding: 8px 12px;
    font-size: 13px;
    font-weight: bold;
    border-radius: 6px;
}

nav a:hover {
    background: #eaf2ff;
}

.ticker {
    background: #fff2cf;
    border-bottom: 2px solid var(--gold);
    display: flex;
    overflow: hidden;
    align-items: center;
}

.ticker-label {
    flex-shrink: 0;
    background: #b51f25;
    color: white;
    padding: 9px 12px;
    font-size: 12px;
    font-weight: bold;
}

.ticker-track {
    overflow: hidden;
    white-space: nowrap;
    flex: 1;
}

.ticker-text {
    display: inline-block;
    padding-left: 100%;
    animation: ticker 24s linear infinite;
    color: #772019;
    font-size: 13px;
    font-weight: bold;
}

@keyframes ticker {
    from { transform: translateX(0); }
    to { transform: translateX(-100%); }
}

.hero {
    padding: 55px 20px;
    text-align: center;
    color: white;
    background: linear-gradient(135deg, #073b75, #1685c5);
}

.hero h1 {
    font-size: 31px;
    line-height: 1.3;
    margin-bottom: 15px;
}

.hero h1 span {
    color: var(--gold);
}

.hero p {
    max-width: 650px;
    margin: auto;
    font-size: 15px;
}

.buttons {
    margin-top: 24px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 12px;
}

.btn {
    display: inline-block;
    padding: 12px 20px;
    border-radius: 7px;
    font-size: 14px;
    font-weight: bold;
}

.btn-gold {
    background: var(--gold);
    color: #15243a;
}

.btn-white {
    background: white;
    color: var(--blue);
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 30px 15px;
}

.section-title {
    text-align: center;
    color: var(--blue);
    font-size: 25px;
    margin-bottom: 8px;
}

.section-desc {
    text-align: center;
    color: #617086;
    margin-bottom: 25px;
    font-size: 14px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 17px;
}

.card {
    background: white;
    border-radius: 12px;
    padding: 22px;
    box-shadow: 0 4px 17px #12345a0d;
    border: 1px solid #e6edf5;
}

.card h3 {
    color: var(--blue);
    margin-bottom: 9px;
    font-size: 17px;
}

.card p, .card li {
    color: #566477;
    font-size: 14px;
}

.icon {
    font-size: 31px;
    margin-bottom: 9px;
}

ul {
    padding-left: 20px;
}

.update-card {
    border-left: 4px solid var(--gold);
}

.date {
    color: #8b650c;
    font-size: 12px;
    font-weight: bold;
    margin-bottom: 5px;
}

.feedback-name {
    color: var(--green);
    font-weight: bold;
    margin-top: 12px;
}

.feedback-note {
    font-size: 12px;
    color: #7b8492;
    margin-top: 15px;
}

.contact-box {
    background: linear-gradient(135deg, #073b75, #1265aa);
    color: white;
    border-radius: 14px;
    padding: 30px 20px;
    text-align: center;
}

.contact-box h2 {
    margin-bottom: 10px;
}

.contact-box p {
    font-size: 14px;
}

.whatsapp {
    position: fixed;
    right: 16px;
    bottom: 18px;
    background: #20bd5a;
    color: white;
    padding: 12px 16px;
    border-radius: 50px;
    box-shadow: 0 4px 15px #0003;
    font-weight: bold;
    font-size: 14px;
    z-index: 200;
}

footer {
    background: #061d37;
    color: white;
    text-align: center;
    padding: 25px 15px;
    font-size: 13px;
}

footer p {
    margin: 5px 0;
}

.admin-area {
    background: #eaf0f8;
    padding: 25px 15px;
}

.admin-box {
    max-width: 500px;
    margin: auto;
    background: white;
    padding: 22px;
    border-radius: 12px;
    box-shadow: 0 4px 15px #00000010;
}

.admin-box h2 {
    color: var(--blue);
    margin-bottom: 12px;
}

.admin-box label {
    display: block;
    margin-top: 12px;
    font-size: 14px;
    font-weight: bold;
}

.admin-box input,
.admin-box textarea {
    width: 100%;
    padding: 11px;
    border: 1px solid #ccd5e1;
    border-radius: 6px;
    margin-top: 5px;
    font: inherit;
}

.admin-box button {
    margin-top: 12px;
    padding: 11px 16px;
    border: 0;
    background: var(--blue);
    color: white;
    border-radius: 6px;
    font-weight: bold;
    cursor: pointer;
}

.admin-warning {
    color: #a32929;
    font-size: 13px;
    margin-top: 12px;
}

#adminContent {
    display: none;
}

@media (max-width: 600px) {
    .logo {
        font-size: 24px;
    }

    .hero h1 {
        font-size: 25px;
    }

    .section-title {
        font-size: 22px;
    }

    nav a {
        padding: 7px;
        font-size: 12px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">ALL INDIA <span>BANKING</span></div>
    <p class="tagline">आपकी बैंकिंग जानकारी, आपकी सुविधा</p>
    <p class="tagline">Banking Information | Customer Assistance | Latest Updates</p>
</header>

<nav>
    <a href="#home">होम</a>
    <a href="#services">सेवाएँ</a>
    <a href="#documents">दस्तावेज़</a>
    <a href="#updates">Latest Updates</a>
    <a href="#feedback">Customer Feedback</a>
    <a href="#contact">संपर्क करें</a>
</nav>

<div class="ticker">
    <div class="ticker-label">LATEST UPDATES</div>
    <div class="ticker-track">
        <div class="ticker-text">
            ALL INDIA BANKING में आपका स्वागत है।
            बैंकिंग सेवाओं और BC/CSP से संबंधित जानकारी के लिए संपर्क करें।
            किसी भी योजना या भर्ती की जानकारी आधिकारिक वेबसाइट से अवश्य जाँचें।
        </div>
    </div>
</div>

<section class="hero" id="home">
    <h1>Welcome to <span>ALL INDIA BANKING</span></h1>
    <p>
        बैंकिंग सेवाओं की जानकारी, Bank Account Opening Assistance,
        BC/CSP से जुड़ी जानकारी और नवीनतम अपडेट एक ही जगह पर प्राप्त करें।
    </p>

    <div class="buttons">
        <a class="btn btn-gold"
           href="https://wa.me/918294392530?text=Hello%20ALL%20INDIA%20BANKING%2C%20mujhe%20jaankari%20chahiye"
           target="_blank" rel="noopener">
           WhatsApp पर संपर्क करें
        </a>

        <a class="btn btn-white" href="#services">
            सभी सेवाएँ देखें
        </a>
    </div>
</section>

<section class="container" id="services">
    <h2 class="section-title">हमारी सेवाएँ</h2>
    <p class="section-desc">
        बैंकिंग से जुड़ी जानकारी और सहायता के लिए हमसे संपर्क करें।
    </p>

    <div class="grid">

        <div class="card">
            <div class="icon">🏦</div>
            <h3>Bank Account Opening</h3>
            <p>
                बैंक खाता खोलने की प्रक्रिया, पात्रता और जरूरी दस्तावेज़ों
                की जानकारी प्राप्त करें।
            </p>
        </div>

        <div class="card">
            <div class="icon">💳</div>
            <h3>BC / CSP Information</h3>
            <p>
                Banking Correspondent और CSP से जुड़ी जानकारी,
                प्रक्रिया तथा आधिकारिक आवेदन के बारे में पूछें।
            </p>
        </div>

        <div class="card">
            <div class="icon">📋</div>
            <h3>Banking Work Information</h3>
            <p>
                बैंकिंग एजेंट के काम, आवश्यक योग्यता और उपलब्ध अवसरों
                के बारे में जानकारी प्राप्त करें।
            </p>
        </div>

        <div class="card">
            <div class="icon">📢</div>
            <h3>Latest Updates</h3>
            <p>
                बैंकिंग सेवाओं, आवेदन प्रक्रियाओं और महत्वपूर्ण सूचनाओं
                के अपडेट देखें।
            </p>
        </div>

    </div>
</section>

<section class="container" id="documents">
    <h2 class="section-title">जरूरी दस्तावेज़</h2>
    <p class="section-desc">
        दस्तावेज़ बैंक और सेवा के अनुसार अलग-अलग हो सकते हैं।
    </p>

    <div class="grid">

        <div class="card">
            <h3>खाता खोलने के लिए</h3>
            <ul>
                <li>आधार कार्ड या मान्य पहचान प्रमाण</li>
                <li>PAN कार्ड या लागू वैकल्पिक दस्तावेज़</li>
                <li>मोबाइल नंबर</li>
                <li>पते का प्रमाण, जहाँ आवश्यक हो</li>
                <li>बैंक द्वारा माँगे गए अन्य दस्तावेज़</li>
            </ul>
        </div>

        <div class="card">
            <h3>BC / CSP आवेदन</h3>
            <ul>
                <li>पहचान और पते का प्रमाण</li>
                <li>PAN कार्ड, जहाँ आवश्यक हो</li>
                <li>शैक्षणिक प्रमाणपत्र, यदि माँगा जाए</li>
                <li>फोटो और बैंक संबंधी विवरण</li>
                <li>संबंधित बैंक/कंपनी की शर्तें</li>
            </ul>
        </div>

    </div>
</section>

<section class="container" id="updates">
    <h2 class="section-title">Latest Updates</h2>
    <p class="section-desc">
        महत्वपूर्ण सूचनाएँ और नई जानकारी।
    </p>

    <div class="grid">

        <div class="card update-card">
            <div class="date">BANKING INFORMATION</div>
            <h3>बैंक खाता खोलने की जानकारी</h3>
            <p>
                खाता खोलने से पहले संबंधित बैंक की आधिकारिक वेबसाइट पर
                पात्रता और आवश्यक दस्तावेज़ जाँचें।
            </p>
        </div>

        <div class="card update-card">
            <div class="date">BC / CSP INFORMATION</div>
            <h3>BC / CSP से जुड़ी जानकारी</h3>
            <p>
                आवेदन करने से पहले संबंधित बैंक या अधिकृत सेवा प्रदाता
                से प्रक्रिया और शुल्क की पुष्टि करें।
            </p>
        </div>

        <div class="card update-card">
            <div class="date">IMPORTANT NOTICE</div>
            <h3>सुरक्षित बैंकिंग</h3>
            <p>
                अपना OTP, ATM PIN, UPI PIN या बैंक पासवर्ड किसी के साथ
                साझा न करें।
            </p>
        </div>

    </div>
</section>

<section class="container" id="feedback">
    <h2 class="section-title">Customer Feedback</h2>
    <p class="section-desc">
        ग्राहकों की राय हमारे लिए महत्वपूर्ण है।
    </p>

    <div class="grid">

        <div class="card">
            <div class="icon">💬</div>
            <p>
                ग्राहक की वास्तविक प्रतिक्रिया यहाँ उनकी अनुमति से
                प्रकाशित की जा सकती है।
            </p>
            <div class="feedback-name">ग्राहक प्रतिक्रिया</div>
        </div>

        <div class="card">
            <div class="icon">⭐</div>
            <p>
                अपनी सेवा से संबंधित अनुभव साझा करने के लिए WhatsApp
                के माध्यम से संपर्क करें।
            </p>
            <div class="feedback-name">अपनी राय साझा करें</div>
        </div>

    </div>

    <p class="feedback-note">
        नोट: यहाँ केवल वास्तविक ग्राहकों की अनुमति प्राप्त प्रतिक्रिया
        प्रकाशित करें। उदाहरण के नाम या नकली समीक्षाएँ प्रकाशित न करें।
    </p>
</section>

<section class="container" id="contact">
    <div class="contact-box">
        <h2>हमसे संपर्क करें</h2>
        <p>
            बैंकिंग सेवाओं और जानकारी के लिए WhatsApp पर अपना प्रश्न भेजें।
        </p>

        <div class="buttons">
            <a class="btn btn-gold"
               href="https://wa.me/918294392530?text=Hello%2C%20mujhe%20banking%20service%20ki%20jaankari%20chahiye"
               target="_blank" rel="noopener">
                WhatsApp पर मैसेज करें
            </a>
        </div>
    </div>
</section>

<!-- ADMIN PANEL: यह केवल शुरुआती डेमो है, सुरक्षित ऑनलाइन लॉगिन नहीं। -->
<section class="admin-area" id="admin">
    <div class="admin-box">
        <h2>🔐 Admin Panel</h2>
        <p>
            यह शुरुआती Admin Panel डेमो है। वास्तविक सुरक्षित लॉगिन और
            ऑनलाइन अपडेट सेव करने के लिए बैकएंड जोड़ना जरूरी है।
        </p>

        <div id="adminLogin">
            <label for="adminUser">Admin Username</label>
            <input id="adminUser" type="text" autocomplete="username"
                   placeholder="Username">

            <label for="adminPass">Admin Password</label>
            <input id="adminPass" type="password"
                   autocomplete="current-password"
                   placeholder="Password">

            <button type="button" onclick="demoAdminLogin()">
                Login Demo
            </button>

            <p class="admin-warning">
                इस डेमो में वास्तविक सुरक्षित प्रमाणीकरण नहीं है।
                इसमें कोई असली बैंकिंग पासवर्ड या संवेदनशील जानकारी न डालें।
            </p>
        </div>

        <div id="adminContent">
            <h3>Update Draft</h3>

            <label for="newUpdate">नई सूचना लिखें</label>
            <textarea id="newUpdate" rows="4"
                      placeholder="नई सूचना यहाँ लिखें"></textarea>

            <button type="button" onclick="saveLocalDraft()">
                इस डिवाइस पर Draft Save करें
            </button>

            <p id="draftStatus"></p>

            <button type="button" onclick="demoLogout()">
                Logout
            </button>

            <p class="admin-warning">
                Draft केवल इसी ब्राउज़र में सेव होगा। यह लाइव वेबसाइट पर
                दूसरे विज़िटर्स को नहीं दिखेगा।
            </p>
        </div>
    </div>
</section>

<footer>
    <p><strong>ALL INDIA BANKING</strong></p>
    <p>Banking Information & Customer Assistance</p>
    <p>WhatsApp Contact: 8294392530</p>
    <p>
        यह एक स्वतंत्र सूचना एवं सहायता वेबसाइट है।
        यह किसी बैंक की आधिकारिक वेबसाइट होने का दावा नहीं करती।
    </p>
    <p>© <span id="year"></span> ALL INDIA BANKING. All Rights Reserved.</p>
</footer>

<a class="whatsapp"
   href="https://wa.me/918294392530"
   target="_blank" rel="noopener">
   WhatsApp Chat
</a>

<script>
document.getElementById("year").textContent =
    new Date().getFullYear();

/*
  Demo login:
  यह सुरक्षा व्यवस्था नहीं है।
  इसे वास्तविक वेबसाइट की सुरक्षा के लिए इस्तेमाल न करें।
*/
function demoAdminLogin() {
    alert(
      "यह केवल Admin Panel का डेमो है। " +
      "सुरक्षित लॉगिन के लिए Firebase Authentication " +
      "या किसी अन्य बैकएंड को जोड़ना होगा।"
    );
}

function saveLocalDraft() {
    const text = document.getElementById("newUpdate").value.trim();

    if (!text) {
        document.getElementById("draftStatus").textContent =
            "पहले सूचना लिखें।";
        return;
    }

    try {
        localStorage.setItem("allIndiaBankingDraft", text);

        document.getElementById("draftStatus").textContent =
            "Draft इसी डिवाइस के ब्राउज़र में सेव हो गया है।";
    } catch (error) {
        document.getElementById("draftStatus").textContent =
            "Draft सेव नहीं हो पाया।";
    }
}
</script>

</body>
</html>
