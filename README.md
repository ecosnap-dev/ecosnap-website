<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EcoSnap+ | Smart Recycling Solution</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background:#f4f9f4;
    color:#2e3d2f;
}

header{
    background:linear-gradient(135deg,#3ba55d,#1f6f4a);
    color:white;
    padding:80px 20px;
    text-align:center;
}

header h1{
    font-size:48px;
    margin-bottom:15px;
}

header p{
    font-size:18px;
    max-width:600px;
    margin:auto;
}

section{
    padding:60px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    font-size:32px;
    color:#1f6f4a;
}

.card-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    margin-bottom:15px;
    color:#3ba55d;
}

.packages{
    background:#e8f5e9;
}

.package{
    background:white;
    padding:30px;
    border-radius:15px;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.package h3{
    color:#1f6f4a;
    margin-bottom:10px;
}

.package-price{
    font-size:28px;
    font-weight:bold;
    margin:15px 0;
    color:#3ba55d;
}

.testimony{
    background:linear-gradient(135deg,#2e7d32,#66bb6a);
    color:white;
    border-radius:20px;
    padding:40px;
    max-width:800px;
    margin:auto;
    text-align:center;
}

footer{
    background:#1f6f4a;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}

button{
    padding:12px 25px;
    background:#3ba55d;
    border:none;
    color:white;
    border-radius:30px;
    cursor:pointer;
    margin-top:15px;
    transition:0.3s;
}

button:hover{
    background:#1f6f4a;
}
</style>
</head>
<body>

<header>
    <h1>EcoSnap+</h1>
    <p>Smart AI Recycling Bin System for a Cleaner, Greener Future.</p>
    <button>Learn More</button>
</header>

<section>
    <h2 class="section-title">Our Objective</h2>
    <div class="card-container">
        <div class="card">
            <h3>Reduce Waste Mismanagement</h3>
            <p>Improve recycling rates using AI-powered smart bins with 95%+ sorting accuracy.</p>
        </div>
        <div class="card">
            <h3>Digital Tracking</h3>
            <p>Track waste contributions and sustainability performance with real-time analytics.</p>
        </div>
        <div class="card">
            <h3>EcoPoint Rewards</h3>
            <p>Encourage participation with QR scanning and reward redemption system.</p>
        </div>
    </div>
</section>

<section>
    <h2 class="section-title">Product Features</h2>
    <div class="card-container">
        <div class="card">
            <h3>HD 8MP Camera</h3>
            <p>AI-powered waste recognition with 95%+ accuracy.</p>
        </div>
        <div class="card">
            <h3>Odour Control</h3>
            <p>Sealed lids and carbon filters for hygienic environment.</p>
        </div>
        <div class="card">
            <h3>Full HD Display</h3>
            <p>Large responsive screen with real-time feedback.</p>
        </div>
    </div>
</section>

<section class="packages">
    <h2 class="section-title">Service Packages</h2>
    <div class="card-container">
        <div class="package">
            <h3>Package 1</h3>
            <div class="package-price">RM 1,000</div>
            <p>3 Years Service</p>
            <p>Maintenance Every 2 Months</p>
            <p>Insurance Included</p>
            <button>Select Plan</button>
        </div>
        <div class="package">
            <h3>Package 2</h3>
            <div class="package-price">RM 2,890</div>
            <p>6 Years Service</p>
            <p>Full Maintenance</p>
            <p>Insurance & Warranty</p>
            <button>Select Plan</button>
        </div>
    </div>
</section>

<section>
    <h2 class="section-title">Testimony</h2>
    <div class="testimony">
        <p>
        “EcoSnap+ has significantly improved our campus waste management system.
        Recycling participation increased, hygiene improved, and sustainability reporting
        became easier. It is more than a recycling solution — it’s a smart environmental platform.”
        </p>
    </div>
</section>

<footer>
    <p>© 2026 EcoSnap+ | Built for a Greener Future 🌱</p>
</footer>

</body>
</html>
