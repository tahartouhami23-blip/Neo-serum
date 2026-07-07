# Neo-serum

<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Neo Serum</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<link
rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"/>

<style>
/*==========================
RESET
==========================*/
.contact-details{
    margin-top:30px;
}

.contact-details .item{
    display:flex;
    align-items:center;
    gap:15px;
    margin:18px 0;
    font-size:17px;
    color:#444;
}

.contact-details i{
    width:45px;
    height:45px;
    display:flex;
    align-items:center;
    justify-content:center;
    background:#007bff;
    color:#fff;
    border-radius:50%;
    font-size:18px;
}

.contact-form input,
.contact-form textarea{
    width:100%;
    padding:15px;
    margin-bottom:18px;
    border:1px solid #ddd;
    border-radius:8px;
    font-size:16px;
}

.contact-form button{
    width:100%;
    padding:15px;
    border:none;
    border-radius:8px;
    background:#007bff;
    color:#fff;
    font-size:17px;
    cursor:pointer;
    transition:.3s;
}

.contact-form button:hover{
    background:#0056b3;
}
*{
margin:0;
padding:0;
box-sizing:border-box;
}

html{
scroll-behavior:smooth;
}

body{
font-family:'Poppins',sans-serif;
background:#faf7f3;
color:#2d2d2d;
line-height:1.6;
overflow-x:hidden;
}

img{
max-width:100%;
display:block;
}

a{
text-decoration:none;
color:inherit;
}

ul{
list-style:none;
}

.container{
width:90%;
max-width:1280px;
margin:auto;
}

/*==========================
Announcement
==========================*/

.announcement{
background:#9a633d;
color:#fff;
text-align:center;
padding:10px;
font-size:14px;
font-weight:500;
}

/*==========================
Header
==========================*/

header{
position:sticky;
top:0;
z-index:999;
background:white;
box-shadow:0 8px 30px rgba(0,0,0,.05);
}

.nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:22px 0;
}

.logo h1{
font-size:38px;
font-family:'Cormorant Garamond',serif;
font-weight:700;
letter-spacing:2px;
line-height:1;
}

.logo span{
letter-spacing:6px;
font-size:12px;
color:#777;
}

nav ul{
display:flex;
gap:40px;
}

nav a{
font-size:15px;
transition:.3s;
font-weight:500;
}

nav a:hover{
color:#9a633d;
}

.nav-right{
display:flex;
align-items:center;
gap:25px;
}

.buy-btn{
background:#9a633d;
padding:14px 34px;
border-radius:8px;
color:white;
transition:.35s;
font-weight:600;
}

.buy-btn:hover{
background:#7d4d2e;
transform:translateY(-3px);
}

.nav-right i{
font-size:22px;
cursor:pointer;
}

/*==========================
Hero
==========================*/

.hero{
padding:90px 0;
}

.hero-grid{
display:grid;
grid-template-columns:1fr 1fr;
gap:70px;
align-items:center;
}

.hero-content h1{
font-family:'Cormorant Garamond',serif;
font-size:74px;
line-height:1.05;
font-weight:700;
}

.hero-content span{
color:#a16a43;
}

.hero-content p{
margin:30px 0;
font-size:18px;
color:#666;
max-width:540px;
}

.main-btn{
display:inline-flex;
align-items:center;
gap:12px;
background:#9a633d;
padding:18px 42px;
color:white;
border-radius:8px;
font-weight:600;
transition:.35s;
}

.main-btn:hover{
background:#7d4d2e;
transform:translateY(-5px);
}

.hero-image{
position:relative;
display:flex;
justify-content:center;
align-items:center;
}

.circle{
width:520px;
height:520px;
background:#efe5da;
border-radius:50%;
position:absolute;
}

.hero-image img{
position:relative;
z-index:2;
width:360px;
}

.leaf{
position:absolute;
right:0;
bottom:40px;
width:180px !important;
}

/*==========================
Features Icons
==========================*/

.features-icons{
display:flex;
gap:40px;
margin-top:60px;
flex-wrap:wrap;
}

.features-icons div{
text-align:center;
}

.features-icons i{
font-size:34px;
color:#9a633d;
margin-bottom:15px;
}

.features-icons p{
font-size:14px;
}

/*==========================
Stats
==========================*/

.stats{
padding:40px 0 80px;
}

.stat-grid{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:25px;
}

.stat{
background:white;
border-radius:14px;
padding:35px;
text-align:center;
box-shadow:0 10px 35px rgba(0,0,0,.05);
transition:.35s;
}

.stat:hover{
transform:translateY(-8px);
}

.stat i{
font-size:36px;
color:#9a633d;
margin-bottom:18px;
}

.stat h3{
font-size:30px;
margin-bottom:8px;
}

.stat p{
color:#777;
}

/*==========================
Section Title
==========================*/

section h2{
font-family:'Cormorant Garamond',serif;
font-size:42px;
text-align:center;
margin-bottom:60px;
position:relative;
}

section h2::after{
content:'';
width:80px;
height:3px;
background:#9a633d;
position:absolute;
left:50%;
transform:translateX(-50%);
bottom:-15px;
}
/*==========================
WHY CHOOSE
==========================*/

.why{
    padding:80px 0;
}

.why-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:25px;
}

.box{
    background:#fff;
    padding:35px 30px;
    border-radius:15px;
    text-align:center;
    transition:.35s;
    box-shadow:0 10px 30px rgba(0,0,0,.05);
}

.box:hover{
    transform:translateY(-10px);
    box-shadow:0 20px 40px rgba(0,0,0,.1);
}

.box i{
    font-size:42px;
    color:#9a633d;
    margin-bottom:20px;
}

.box h3{
    margin-bottom:15px;
    font-size:22px;
}

.box p{
    color:#777;
    font-size:15px;
}

/*==========================
INGREDIENTS
==========================*/

.ingredients{
    padding:90px 0;
}

.ingredient-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:25px;
}

.card{
    background:#fff;
    border-radius:18px;
    overflow:hidden;
    transition:.35s;
    box-shadow:0 10px 30px rgba(0,0,0,.06);
}

.card:hover{
    transform:translateY(-12px);
}

.card img{
    width:100%;
    height:230px;
    object-fit:cover;
}

.card h3{
    text-align:center;
    margin-top:20px;
    font-size:22px;
}

.card p{
    text-align:center;
    color:#777;
    padding:15px 20px 30px;
}

/*==========================
HOW TO USE
==========================*/

.how{
    padding:80px 0;
}

.how-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
}

.steps,
.results{
    background:#fff;
    border-radius:20px;
    padding:45px;
    box-shadow:0 12px 35px rgba(0,0,0,.05);
}

.step{
    display:flex;
    align-items:center;
    gap:25px;
    margin:30px 0;
}

.step span{
    width:55px;
    height:55px;
    border-radius:50%;
    background:#9a633d;
    color:#fff;
    display:flex;
    justify-content:center;
    align-items:center;
    font-size:22px;
    font-weight:bold;
}

.results img{
    border-radius:15px;
    margin-top:25px;
}

/*==========================
REVIEWS
==========================*/

.reviews{
    padding:90px 0;
}

.slider{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:30px;
}

.review{
    background:#fff;
    border-radius:20px;
    padding:35px;
    text-align:center;
    box-shadow:0 10px 30px rgba(0,0,0,.05);
    transition:.35s;
}

.review:hover{
    transform:translateY(-8px);
}

.review img{
    width:85px;
    height:85px;
    border-radius:50%;
    margin:auto;
    margin-bottom:20px;
}

.review h3{
    margin-bottom:15px;
}

.review p{
    color:#666;
    font-size:15px;
}

/*==========================
FAQ
==========================*/

.faq{
    padding:80px 0;
}

.accordion .item{
    background:#fff;
    margin-bottom:18px;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 8px 20px rgba(0,0,0,.05);
}

.accordion button{
    width:100%;
    padding:22px;
    border:none;
    background:#fff;
    text-align:left;
    cursor:pointer;
    font-size:17px;
    font-weight:600;
}

.content{
    display:none;
    padding:0 22px 22px;
    color:#666;
}

/*==========================
CTA
==========================*/

.cta{
    padding:90px 0;
}

.cta-box{
    background:#9a633d;
    border-radius:25px;
    color:#fff;
    padding:70px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.cta-box h2{
    color:#fff;
    margin:0;
}

.cta-box h2::after{
    display:none;
}

/*==========================
FOOTER
==========================*/

footer{
    background:#1f1f1f;
    color:#fff;
    padding:70px 0;
}

.footer{
    display:grid;
    grid-template-columns:2fr 1fr 1fr 1fr;
    gap:40px;
}

.footer h3{
    margin-bottom:20px;
}

.footer a{
    display:block;
    color:#bbb;
    margin-bottom:12px;
    transition:.3s;
}

.footer a:hover{
    color:#fff;
}

.social{
    display:flex;
    gap:18px;
}

.social i{
    width:45px;
    height:45px;
    border-radius:50%;
    background:#333;
    display:flex;
    justify-content:center;
    align-items:center;
    cursor:pointer;
    transition:.35s;
}

.social i:hover{
    background:#9a633d;
}

</style>
</head>

<body>



<!-- Header -->

<header>

<div class="container nav">

<div class="logo">

<h1>NEO</h1>

<span>SERUM</span>

</div>

<nav>

<ul>

<li><a href="#">Home</a></li>

<li><a href="#">Benefits</a></li>

<li><a href="#">Ingredients</a></li>

<li><a href="#">Reviews</a></li>

<li><a href="#">FAQ</a></li>

</ul>

</nav>

<div class="nav-right">



<i class="fa-solid fa-bag-shopping"></i>

</div>

</div>

</header>

<!-- Hero -->

<section class="hero">

<div class="container hero-grid">

<div class="hero-content">

<h1>

La puissance de la nature, 



<span>L’innovation en plus</span>

</h1>

<p>
NEO transforme les écorces d'agrumes et les pelures d’oignons 

en un sérum capillaire innovant 

grâce  une technologie de nanoémulsion, 

alliant efficacité et respect de l'environnement 

</p>

<a href="#" class="main-btn">

Découvrir NÉO


<i class="fa-solid fa-arrow-right"></i>

</a>

<div class="features-icons">

<div>

<i class="fa-brands fa-envira"></i>

<p>Natural Formula


</p>

</div>

<div>

<i class="fa-solid fa-droplet"></i>

<p>Deep Hydration

</p>

</div>

<div>

<i class="fa-regular fa-sun"></i>

<p>Bright Skin</p>

</div>

<div>

<i class="fa-solid fa-shield-heart"></i>

<p> Dermatologist Tested</p>

</div>

</div>

</div>


<div class="hero-image">

<div class="circle"></div>

<img src="images/serum.png" alt="Serum">

<img class="leaf" src="images/leaf.png">

</div>

</div>

</section>


<section class="hero">

<div class="container hero-grid">

<div class="hero-content">

<h1>

À PROPOS de NÉO


</h1>
<h3>
    

<span >TRANSFORMER LES DÉCHETS VÉGÉTAUX EN INNOVATION CAPILLAIRE

</span>

</h3>
<p>
NÉO est un projet innovant qui valorise les écorces d'oranges et les pelures d'oignons
en les transformant en un sérum capillaire écoresponsable
grace a la technologie de nano émulsion
Notre objectif est de proposer une solution naturelle,efficace et durable
contre la chute des cheuveux,
tout en donnant une seconde vie aux dechets veetaux
dans une demarche deconomie circulaire

</p>





<div class="features-icons">

<div>

<i class="fa-brands fa-envira"></i>

<p>
<h3>Actifs naturels</h3>
<br>
Des extraits <br>
végétaux <br>
riches en <br>
composés bioactifs


</p>

</div>

<div>

<i class="fa-solid fa-droplet"></i>

<p> <h3>Écoresponsable</h3>
<br>
valorisation
des <br>
déchés végétaux<br>
dans
une démarche <br>
d'économie<br>
circulaire

</p>

</div>



<div>

<i class="fa-solid fa-shield-heart"></i>

<p> <h3>Soin sain</h3>
<br>
Sans colorants,<br>
formulation naturelle
</p>

</div>
<div>

<i class="fa-solid fa-shield-heart"></i>

<p> <h3>Notre mission

</h3>
<br>
Allier science,<br>
nature
et<br>
durabilité

</p>

</div>

</div>

</div>



<div class="hero-image">

<div class="circle"></div>

<img src="images/serum.png" alt="Serum">

<img class="leaf" src="images/leaf.png">

</div>

</div>

</section>

<!-- Statistics -->

<section class="stats">
<div class="container">
    <h1>INRÉDIENTS</h1>
</div>
<div class="container stat-grid">
    
<div class="stat">

<i class="fa-regular fa-face-smile"></i>

<h3>10,000+</h3>

<p>Happy Customers</p>

</div>


<div class="stat">

<i class="fa-regular fa-face-smile"></i>

<h3>10,000+</h3>

<p>Happy Customers</p>

</div>

<div class="stat">

<i class="fa-regular fa-star"></i>

<h3>98%</h3>

<p>Positive Reviews</p>

</div>

<div class="stat">

<i class="fa-solid fa-truck-fast"></i>

<h3>FREE</h3>

<p>Shipping Over $50</p>

</div>

<div class="stat">

<i class="fa-solid fa-shield"></i>

<h3>30 Days</h3>

<p>Money Back Guarantee</p>

</div>

</div>

</section>

<!-- Why Choose -->

<section class="why">

<div class="container">

<h2>

WHY CHOOSE NEO SERUM?

</h2>

<div class="why-grid">

<div class="box">

<i class="fa-brands fa-envira"></i>

<h3>Natural Formula</h3>

<p>

Made with clean premium ingredients.

</p>

</div>

<div class="box">

<i class="fa-solid fa-droplet"></i>

<h3>Deep Hydration</h3>

<p>

Penetrates deeply and locks moisture.

</p>

</div>

<div class="box">

<i class="fa-regular fa-sun"></i>

<h3>Brightens Skin</h3>

<p>

Improves tone and glow.

</p>

</div>

<div class="box">

<i class="fa-solid fa-shield-heart"></i>

<h3>Dermatologist Tested</h3>

<p>

Suitable for all skin types.

</p>

</div>

</div>

</div>

</section>

<!-- Ingredients -->

<section class="ingredients">

<div class="container">

<h2>

INRÉDIENTS
</h2>

<div class="ingredient-grid">
    <div class="card">

<img src="images/vitamin.jpg">

<h3>Nano ÉMULSION</h3>

<p>
technologie d'encapsulation
des actifs
</p>

</div>


<div class="card">

<img src="images/vitamin.jpg">

<h3>Glycérine</h3>

<p>
Hydrate et protège la fibre capillaire
</p>

</div>

<div class="card">

<img src="images/niacinamide.jpg">

<h3>VITAMINE E</h3>

<p>protège et nourrit les cheveux
</p>

</div>

<div class="card">

<img src="images/hyaluronic.jpg">

<h3>Huile ESSENTIELLE
</h3>

<p>propriétés anti oxydante et agréable fragrance
</p>

</div>

<div class="card">

<img src="images/aloe.jpg">

<h3>POLYPHENOLS ET FLAVONOIDES
</h3>

<p>Composées bioactifs aux propriétés antioxydant
</p>

</div>

<div class="card">

<img src="images/aloe.jpg">

<h3>écorce d'oranges 
</h3>

<p>Riche en antioxydants et 

vitamine C
</p>

</div>
<div class="card">

<img src="images/aloe.jpg">

<h3>Pelures d'oignions

</h3>

<p>source naturelle des polyphénols
de flavonoïdes et
de soufre
</p>

</div>
</div>

</div>

</section>

<section class="hero">

<div class="container hero-grid">

<div class="hero-content">

<h1>

ECORESPENSABILITE


</h1>

<p>
Notre engagement <br>

<h3> Une beauté responsable 

Un avenir durable</h3> <br>

Chez NEO la beauté ne doit jamais se faire au détriment de la planète 

Nous noua engageons a concevoir des produits 

respectueux de l'environnement a chaque étape de leur cycle de vie  

</p>


<div class="features-icons">


<p>

<h3>
    Une production durable vert une consommation durable 
</h3> 




</p>

</div>


</div>
</div>

</div>

</section>

<section class="contact" id="contact">
    <div class="container">

        <div class="contact-info">
            <h2>NOUS CONTACTER</h2>

            <p>
                Une question, une suggestion ou l'envie d’en savoir plus sur <strong>NEO</strong> ?
            </p>

            <p>
                Nous sommes à votre écoute.
            </p>

            <p>
                Écrivez-nous ou suivez-nous sur nos réseaux sociaux.
            </p>

            <div class="contact-details">
                <div class="item">
                    <i class="fas fa-envelope"></i>
                    <span>contactneo-serum.com

</span>
                </div>

                <div class="item">
                    <i class="fas fa-phone"></i>
                    <span>+213654822556</span>
                </div>

                <div class="item">
                    <i class="fab fa-instagram"></i>
                    <span> @Neo-serum </span>
                </div>
            </div>
        </div>

    </div>
</section>




<!-- CTA -->

<section class="cta">

<div class="container">

<div class="cta-box">

<h2>

Ready for Healthy Glowing Skin?

</h2>

<a href="#" class="main-btn">

Shop Now

</a>

</div>

</div>

</section>

<!-- Footer -->

<footer>

<div class="container footer">

<div>

<h2>NEO SERUM</h2>

<p>

Healthy Skin Starts Here.

</p>

</div>

<div>

<h3>Quick Links</h3>

<a href="#">Home</a>

<a href="#">Benefits</a>

<a href="#">Ingredients</a>

<a href="#">Reviews</a>

</div>

<div>

<h3>Customer Care</h3>

<a href="#">Shipping</a>

<a href="#">Returns</a>

<a href="#">Privacy</a>

<a href="#">Contact</a>

</div>

<div>

<h3>Follow Us</h3>

<div class="social">

<i class="fab fa-instagram"></i>

<i class="fab fa-facebook"></i>

<i class="fab fa-tiktok"></i>

</div>

</div>

</div>

</footer>

<script>
// Sticky Header

window.addEventListener("scroll",()=>{

const header=document.querySelector("header");

if(window.scrollY>60){

header.classList.add("sticky");

}else{

header.classList.remove("sticky");

}

});

// FAQ Accordion

const buttons=document.querySelectorAll(".accordion button");

buttons.forEach(button=>{

button.addEventListener("click",()=>{

const content=button.nextElementSibling;

const isOpen=content.style.display==="block";

document.querySelectorAll(".content").forEach(item=>{

item.style.display="none";

});

if(!isOpen){

content.style.display="block";

}

});

});

// Smooth Scroll

document.querySelectorAll('a[href^="#"]').forEach(anchor=>{

anchor.addEventListener("click",function(e){

e.preventDefault();

const target=document.querySelector(this.getAttribute("href"));

if(target){

target.scrollIntoView({

behavior:"smooth"

});

}

});

});

// Reveal Animation

const observer=new IntersectionObserver(entries=>{

entries.forEach(entry=>{

if(entry.isIntersecting){

entry.target.style.opacity="1";

entry.target.style.transform="translateY(0)";

}

});

});

document.querySelectorAll(".box,.card,.review,.stat").forEach(el=>{

el.style.opacity="0";

el.style.transform="translateY(40px)";

el.style.transition=".8s";

observer.observe(el);

});

// Auto Review Slider

const slider=document.querySelector(".slider");

let index=0;

setInterval(()=>{

if(window.innerWidth<992)return;

index++;

if(index>2)index=0;

slider.style.transform=`translateX(-${index*33.33}%)`;

slider.style.transition=".6s";

},4000);
</script>

</body>
</html>
