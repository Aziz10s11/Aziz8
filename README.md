# Aziz8
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coach Aziz | مدرب رياضي</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: Arial, sans-serif;
}

body{
  background:#0f0f0f;
  color:white;
}

/* HERO */
.hero{
  height:100vh;
  background-image:url("https://images.unsplash.com/photo-1517836357463-d25dfeac3438");
  background-size:cover;
  background-position:center;
  display:flex;
  align-items:center;
  justify-content:center;
  position:relative;
}

/* LOGO */
.logo {
  position: absolute;
  top: 20px;
  left: 20px;
  font-size: 20px;
  font-weight: bold;
  color: #25D366;
  display: flex;
  align-items: center;
  gap: 8px;
  padding: 8px 14px;
  border: 2px solid #25D366;
  border-radius: 12px;
  background: rgba(0,0,0,0.4);
  backdrop-filter: blur(6px);
  z-index: 10;
  transition: 0.3s;
}

.logo:hover {
  transform: scale(1.05);
  background: rgba(37, 211, 102, 0.15);
}

.hero::before{
  content:"";
  position:absolute;
  width:100%;
  height:100%;
  background:rgba(0,0,0,0.65);
}

.hero-content{
  position:relative;
  text-align:center;
  max-width:700px;
}

.hero h1{
  font-size:60px;
  margin-bottom:10px;
}

.hero p{
  font-size:20px;
  line-height:1.6;
  margin-top:10px;
}

.btn{
  display:inline-block;
  margin-top:25px;
  padding:18px 40px;
  background:#25D366;
  color:white;
  text-decoration:none;
  font-size:20px;
  border-radius:12px;
  transition:0.3s;
}

.btn:hover{
  background:#1ebe5d;
}

/* SECTIONS */
section{
  padding:70px 20px;
  text-align:center;
}

/* ABOUT */
.about{ background:#111; }
.about h2{ font-size:40px; margin-bottom:20px; }
.about p{ max-width:800px; margin:auto; font-size:18px; line-height:1.8; color:#ccc; }

/* SERVICES */
.services{ background:#0f0f0f; }
.services h2{ font-size:40px; margin-bottom:40px; }

.cards{
  display:flex;
  justify-content:center;
  gap:20px;
  flex-wrap:wrap;
}

.card{
  background:#1c1c1c;
  padding:25px;
  width:250px;
  border-radius:12px;
  transition:0.3s;
}

.card:hover{
  transform:translateY(-5px);
  background:#222;
}

.card h3{
  color:#25D366;
}

/* RESULTS */
.results{ background:#111; }

.result-boxes{
  display:flex;
  justify-content:center;
  gap:20px;
  flex-wrap:wrap;
}

.box{
  background:#1c1c1c;
  padding:30px;
  width:200px;
  border-radius:10px;
}

.box h3{
  font-size:30px;
  color:#25D366;
}

/* TESTIMONIALS */
.testimonials{ background:#0f0f0f; }

.testimonial{
  max-width:600px;
  margin:20px auto;
  background:#1c1c1c;
  padding:20px;
  border-radius:10px;
  color:#ccc;
}

/* IMAGE SHOWCASE */
.image-showcase{
  background:#0f0f0f;
  padding:80px 20px;
}

.main-image{
  position:relative;
  border-radius:15px;
  overflow:hidden;
}

.main-image img{
  width:100%;
  height:500px;
  object-fit:cover;
  transition:0.4s;
}

.main-image:hover img{
  transform:scale(1.05);
}

.image-overlay{
  position:absolute;
  bottom:0;
  width:100%;
  padding:20px;
  background:linear-gradient(to top, rgba(0,0,0,0.8), transparent);
}

.image-overlay h3{
  color:#25D366;
  font-size:28px;
}

.overlay-btn{
  display:inline-block;
  margin-top:15px;
  padding:12px 24px;
  background:#25D366;
  color:white;
  border-radius:10px;
  text-decoration:none;
}

/* GALLERY */
.small-gallery{
  display:flex;
  gap:15px;
  flex-wrap:wrap;
  justify-content:center;
  margin-top:25px;
}

.small-gallery img{
  width:180px;
  height:120px;
  object-fit:cover;
  border-radius:10px;
}

/* SCROLL ANIMATION */
.reveal{
  opacity:0;
  transform:translateY(40px);
  transition:0.8s;
}

.reveal.active{
  opacity:1;
  transform:translateY(0);
}

/* FLOAT WHATSAPP */
.whatsapp-float{
  position:fixed;
  width:60px;
  height:60px;
  bottom:20px;
  right:20px;
  background:#25D366;
  color:white;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:28px;
  text-decoration:none;
  z-index:9999;
}

</style>
</head>

<body>

<!-- HERO -->
<section class="hero">

  <!-- LOGO -->
  <div class="logo">💪⚽ Coach Aziz 10</div>

  <div class="hero-content">
    <h1>Coach Aziz 💪</h1>
    <p>مدرب رياضي محترف لتطوير الأداء البدني</p>

    <a class="btn" href="https://wa.me/213XXXXXXXXX">📲 احجز عبر واتساب</a>
  </div>
</section>

<!-- IMAGE -->
<section class="image-showcase reveal">

  <div class="main-image reveal">
    <img src="https://images.unsplash.com/photo-1517836357463-d25dfeac3438">

    <div class="image-overlay">
      <h3>Coach Aziz 10</h3>
      <p>تدريب احترافي عالي المستوى</p>

      <a class="overlay-btn" href="https://wa.me/213XXXXXXXXX">احجز جلسة</a>
    </div>
  </div>

  <div class="small-gallery reveal">
    <img src="https://images.unsplash.com/photo-1599058917765-a780eda07a3e">
    <img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b">
    <img src="https://images.unsplash.com/photo-1558611848-73f7eb4001a1">
  </div>

</section>

<!-- ABOUT -->
<section class="about reveal">
  <h2>من أنا</h2>
  <p>مدرب رياضي متخصص في القوة واللياقة</p>
</section>

<!-- SERVICES -->
<section class="services reveal">
  <h2>خدماتي</h2>

  <div class="cards">
    <div class="card"><h3>⚽ كرة القدم</h3></div>
    <div class="card"><h3>🥊 كيك بوكسينغ</h3></div>
    <div class="card"><h3>💪 كمال الأجسام</h3></div>
  </div>
</section>

<!-- RESULTS -->
<section class="results reveal">
  <h2>النتائج</h2>

  <div class="result-boxes">
    <div class="box"><h3>+50</h3></div>
    <div class="box"><h3>+3 سنوات</h3></div>
    <div class="box"><h3>100%</h3></div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials reveal">
  <h2>آراء العملاء</h2>

  <div class="testimonial">تجربة ممتازة 💪</div>
</section>

<!-- FLOAT WHATSAPP -->
<a class="whatsapp-float" href="https://wa.me/213XXXXXXXXX">💬</a>

<script>
const elements=document.querySelectorAll('.reveal');

window.addEventListener('scroll',()=>{
  elements.forEach(el=>{
    if(el.getBoundingClientRect().top<window.innerHeight-100){
      el.classList.add('active');
    }
  });
});
</script>

</body>
</html>
