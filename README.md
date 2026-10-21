<!-- Landing page Skillline: HTML, CSS e JavaScript reunidos em um único arquivo. -->
<!DOCTYPE html>
<html lang="pt-BR">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Skillline | Aprender ficou mais fácil
  </title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com" rel="preconnect"/>
  <link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet"/>
  <style>
   /* Estilos gerais e organização visual da página Skillline. */
:root
{
    --navy:#252746;
    --orange:#f39b08;
    --purple:#5146e5;
    --text:#252746;
    --muted:#777b91;
    --cream:#fff4e5
}
*
{
    box-sizing:border-box
}
html
{
    scroll-behavior:smooth;
    scroll-padding-top:80px
}
body
{
    font-family:'Poppins',Arial,sans-serif;
    color:var(--text);
    margin:0;
    font-size:14px
}
.hero-wrap
{
    background:var(--cream);
    border-radius:0 0 48% 5%;
    overflow:hidden;
    min-height:590px
}
.navbar .nav-link
{
    color:#333047;
    font-size:12px
}
.logo
{
    width:105px;
    height:auto;
    object-fit:contain
}
.btn-orange
{
    background:var(--orange);
    color:white;
    border:0;
    font-size:12px;
    font-weight:500
}
.btn-orange:hover
{
    background:#db8700;
    color:#fff
}
.hero-content
{
    padding-top:38px
}
.hero-copy
{
    padding-bottom:45px
}
.hero-copy h1
{
    font-size:clamp(30px,3vw,42px);
    font-weight:700;
    line-height:1.35;
    color:var(--navy);
    max-width:440px
}
.hero-copy h1 span,.section-heading h2 span
{
    color:var(--orange)
}
.hero-copy p
{
    font-size:13px;
    line-height:1.9;
    color:#77778b;
    max-width:390px;
    margin:20px 0 26px
}
.hero-picture
{
    display:flex;
    align-items:flex-end;
    justify-content:center;
    min-height:400px
}
.hero-girl
{
    max-height:475px;
    width:auto;
    max-width:100%;
    object-fit:contain;
    object-position:bottom
}
.watch-link
{
    display:inline-flex;
    align-items:center;
    gap:10px;
    color:#55556b;
    text-decoration:none;
    font-size:12px
}
.play
{
    width:36px;
    height:36px;
    border-radius:50%;
    display:inline-grid;
    place-items:center;
    color:#24b8dc;
    background:#fff;
    box-shadow:0 4px 15px #ddd;
    font-size:12px;
    padding-left:2px
}
.trusted
{
    padding-top:34px!important
}
.trusted p
{
    color:#77778b;
    font-size:13px;
    margin-bottom:28px
}
.brand-list
{
    display:flex;
    justify-content:center;
    gap:clamp(25px,7vw,90px);
    flex-wrap:wrap;
    color:#c5c5d0;
    font-size:20px;
    font-weight:700
}
.brand-list span:nth-child(2)
{
    font-weight:600;
    letter-spacing:-1px
}
.section-heading
{
    max-width:650px;
    margin:0 auto
}
.section-heading h2
{
    font-size:22px;
    font-weight:700;
    margin-bottom:15px
}
.section-heading p
{
    font-size:12px;
    line-height:1.9;
    color:var(--muted)
}
.services-section
{
    padding-top:45px!important
}
.service-card
{
    height:100%;
    text-align:center;
    background:#fff;
    border-radius:13px;
    padding:28px 22px 24px;
    box-shadow:0 8px 30px rgba(48,48,90,.08);
    border:1px solid #f3f3f8;
    transition:transform .2s
}
.service-card:hover
{
    transform:translateY(-5px)
}
.service-icon
{
    width:58px;
    height:58px;
    object-fit:contain;
    margin-bottom:18px
}
.service-card h3
{
    font-size:15px;
    line-height:1.6;
    font-weight:600;
    margin-bottom:13px
}
.service-card p
{
    font-size:11px;
    line-height:1.8;
    color:var(--muted);
    margin:0
}
.about-section
{
    padding-top:70px!important
}
.audience-row
{
    max-width:900px;
    margin:0 auto
}
.audience-card
{
    display:block;
    position:relative;
    overflow:hidden;
    border-radius:12px;
    color:#fff;
    min-height:220px;
    text-decoration:none;
    background:#ddd
}
.audience-card img
{
    width:100%;
    height:220px;
    object-fit:cover;
    display:block;
    filter:brightness(.78);
    transition:transform .3s
}
.audience-card:hover img
{
    transform:scale(1.04)
}
.audience-card span,.audience-card small
{
    position:absolute;
    left:0;
    right:0;
    text-align:center
}
.audience-card span
{
    top:43%;
    font-size:17px;
    font-weight:600;
    letter-spacing:.3px
}
.audience-card small
{
    top:56%;
    font-size:12px
}
.features-section
{
    padding-top:60px!important
}
.feature-image
{
    width:100%;
    height:auto
}
.feature-copy h3
{
    font-size:22px;
    line-height:1.5;
    font-weight:600;
    margin-bottom:18px
}
.feature-copy ul
{
    list-style:none;
    padding:0;
    margin:0
}
.feature-copy li
{
    font-size:12px;
    line-height:1.8;
    color:var(--muted);
    padding-left:24px;
    position:relative;
    margin-bottom:14px
}
.feature-copy li:before
{
    content:'✓';
    position:absolute;
    left:0;
    color:var(--orange);
    font-weight:700
}
.testimonial-section
{
    padding-top:55px!important;
    padding-bottom:90px!important
}
.testimonial-copy small
{
    color:#9a9aaf;
    font-size:10px;
    letter-spacing:2px
}
.testimonial-copy h2
{
    font-size:28px;
    font-weight:700;
    margin:12px 0
}
.testimonial-copy p
{
    font-size:12px;
    line-height:1.9;
    color:var(--muted)
}
.text-link
{
    color:var(--orange);
    font-size:12px;
    text-decoration:none;
    font-weight:600
}
.text-link span
{
    margin-left:10px
}
.testimonial-image
{
    width:100%;
    max-height:450px;
    object-fit:contain
}
.site-footer
{
    background:var(--navy);
    color:white;
    padding:48px 0 28px
}
.footer-logo
{
    width:210px;
    max-width:75%;
    height:auto;
    object-fit:contain;
    margin-bottom:30px
}
.site-footer h2
{
    font-size:15px;
    font-weight:500;
    margin-bottom:20px
}
.newsletter-form
{
    display:flex;
    gap:10px;
    max-width:390px;
    margin-bottom:25px
}
.newsletter-form input
{
    min-width:0;
    flex:1;
    border:1px solid #555776;
    border-radius:25px;
    background:transparent;
    color:white;
    padding:11px 16px;
    font:inherit;
    font-size:12px;
    outline:none
}
.newsletter-form input::placeholder
{
    color:#c1c2d1
}
.newsletter-form input:focus
{
    border-color:#8e87ff
}
.btn-purple
{
    background:var(--purple);
    color:#fff;
    border:0;
    padding:10px 20px;
    font-size:12px;
    white-space:nowrap
}
.btn-purple:hover
{
    background:#4035ce;
    color:#fff
}
.footer-links
{
    font-size:11px;
    color:#c3c4d3
}
.footer-links a
{
    color:inherit;
    text-decoration:none
}
.copyright
{
    font-size:10px;
    color:#a5a7be;
    margin:25px 0 0
}
@media(max-width:767px)
{
    .hero-wrap
    {
        border-radius:0 0 35% 3%;
        min-height:0
    }
    .hero-content
    {
        padding-top:25px
    }
    .hero-copy
    {
        padding:20px 18px 0
    }
    .hero-copy h1
    {
        font-size:32px
    }
    .hero-picture
    {
        min-height:0;
        padding:0 10px
    }
    .hero-girl
    {
        max-height:390px
    }
    .brand-list
    {
        font-size:17px;
        gap:22px 30px
    }
    .trusted
    {
        padding-bottom:20px!important
    }
    .service-card
    {
        padding:24px 18px
    }
    .about-section
    {
        padding-top:45px!important
    }
    .audience-card,.audience-card img
    {
        height:210px;
        min-height:210px
    }
    .feature-copy
    {
        padding:0 20px
    }
    .feature-copy h3
    {
        font-size:20px
    }
    .testimonial-copy
    {
        padding:0 18px
    }
    .testimonial-section
    {
        padding-bottom:55px!important
    }
    .newsletter-form
    {
        flex-direction:column
    }
    .newsletter-form button
    {
        width:100%
    }
    .navbar-nav
    {
        padding:12px 0;
        align-items:stretch!important
    }
    .navbar-nav .btn
    {
        display:inline-block;
        margin-top:5px
    }
    .logo
    {
        width:95px
    }
}
  </style>
 </head>
 <body>
  <header class="hero-wrap" id="inicio">
   <nav aria-label="Navegação principal" class="navbar navbar-expand-lg container py-3">
    <a class="navbar-brand" href="#inicio">
     <img alt="Skillline" class="logo" src="data:image/png;base64,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"/>
    </a>
    <button aria-controls="menu" aria-expanded="false" aria-label="Abrir menu" class="navbar-toggler" data-bs-target="#menu" data-bs-toggle="collapse" type="button">
     <span class="navbar-toggler-icon">
     </span>
    </button>
    <div class="collapse navbar-collapse" id="menu">
     <ul class="navbar-nav ms-auto align-items-lg-center gap-lg-4">
      <li class="nav-item">
       <a class="nav-link" href="#inicio">
        Início
       </a>
      </li>
      <li class="nav-item">
       <a class="nav-link" href="#funcionalidades">
        Funcionalidades
       </a>
      </li>
      <li class="nav-item">
       <a class="nav-link" href="#sobre">
        Sobre nós
       </a>
      </li>
      <li class="nav-item">
       <a class="btn btn-light rounded-pill px-4" href="#depoimentos">
        Entrar
       </a>
      </li>
      <li class="nav-item">
       <a class="btn btn-orange rounded-pill px-4" href="#inscricao">
        Cadastre-se
       </a>
      </li>
     </ul>
    </div>
   </nav>
   <div class="container hero-content">
    <div class="row align-items-center g-4">
     <div class="col-lg-5 hero-copy">
      <h1>
       Estudar online agora é
       <span>
        muito mais fácil
       </span>
      </h1>
      <p>
       Skillline é uma plataforma educacional que conecta instrutores e estudantes para tornar o aprendizado mais simples e divertido.
      </p>
      <div class="d-flex flex-wrap align-items-center gap-3">
       <a class="btn btn-orange rounded-pill px-4 py-2" href="#sobre">
        Junte-se
       </a>
       <a class="watch-link" href="#funcionalidades">
        <span class="play">
         ▶
        </span>
        Veja como funciona
       </a>
      </div>
     </div>
     <div class="col-lg-7 hero-picture">
      <img alt="Estudante sorrindo e segurando livros" class="img-fluid hero-girl" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA48AAAPBCAYAAABeO58TAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAOdEVYdFNvZnR3YXJlAEZpZ21hnrGWYwAQRT9JREFUeAHs/QmUJdl5Hoj9EW/f8r18uWftWVVd1VW9ItENNJZGgdjYIEgMxQElahkNPRrJI2ssemSOZs7Iw5LOjH1sWsc+R7ZGsj0aiSOdoQiborgTJMgCCLABdBe60d1V3V37nnvmy3z7FuH7R8Qf74/77ntZDQIk0P1/dV5FxI0bN/bI+93vXwAEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAoFAIBAIBAKBQCAQCAQCgUAgEAgEAsH3Bq7rWuPKcF79aNEKfnyZ6ljBdpapjXH708pN7evlkTJ2fN48HYd23Pu2GWxjafsArS2BQCAQCAQCgUAgeO9BI0XWuDpEuPRliJLKsWSTtcHrW0T6tDZHtcPL9WM1kdjI9rRvvk4v0851HOEUCAQCgUAgEAgEgnc/GFmyNKJlnT9/3oYoOTT94B3UHUXaIiSN2tJJ6AiyCqbj1c9HPzf+G0MYrVHtgUAgEAgEAoFAIBD8IIOZZSJ0U85RZpeR9VyZg9HECt4B+QJ2PEN19f3x/Y4iaqZ5JId8G73dgDzqiqhOkCPHOcLUdt9zhmFY+vXX2gR2bJH1TPUE7ZwEAoFAIBAIBAKB4LuDro4Z/Al1AqPPD5EzWg7IGegmpTCaQFkGQrof4RpaHrWtyax0RDujyiLb6qRTI2v7kWcwqKsjCacb9RUFnSCaSDOMIKACgUAgEAgEAoFA8NDQFbJR5AOipAzGKXsmk1FOBE0mrbpyB/uQPnYKI8mfvj8YTwLHnUeEkI5SMMccN+jtjCGMYVtYh1RRMBPBsWTR1CYMk1OBQCAQCAQCgUDwXoNJkWKw9HruPmahfB2MIYrcl1AnXJz8GNSzITIED0EeXc3EdFT9Mf6SEVPbESTTeG307UYd+zjC6o4wfx21vaktMqXVz3M/UqmdWwSakjpyvUAgEAgEAoFAIPghhztsNkqrdMKkE4GHIo/c9HEEOeFt6eaYAKMJmil6qTVqW10JhBEkiZHaCHHbh9iN26dOFke1FZbzY9CJtH4+/LwM13zfYx5xnsb7y9TjIZNl/T7y+y4QCAQCgUAgEAjeBTCYMyJGKU9Dpo0GQggm0gPw0KalnIiAvt9x7Yxqm8gMOyYYs2/rIdbBOzmGUe2aiLKh/aFzHkEO9XyTpmupk7mR18mwzjINHmj7DX/atRYIBAKBQCAQCAQ/SDCoUfp6nPAOf1huMtc0KV1gIEAmBdBAQIZIxjh1T9/3OOKpH8u4dkz7HrWPh6nDz9V9CEVT++2bUsR0bccQ9wgJNG273zXc5xqY9gema2u6//SswTCJNZlFCwQCgUAgEAgEgu8jjKaCRNyYgkR1vSkMkwMYQ9iozYchG0aiMs6vkO8fDOQGhokXkVdO4Gxd/RxX36QEmrbTppFjYdtGiCQFsKGfdvyRYw7W26Pa4NfIQFj1ZyByHvvdF3btH4o0vpO23WFlO3Ks7rCiKRAIBAKBQCAQCL6fcMebiQLAkMoEMKbTr5GvsXWp3VGmmAbTx1FEhatnel7EIeLF57/whS/E2HL4Y6RM335kmb6Nrm5qhC7cDztOvZ2huuOOk+YNxw5svYmkATwEgRxD+MB0vrTOQFbB0CaMaxtgpB+rEEeBQCAQCAQCgeC7ASdczKyPOvG86qhOuwdT6gYYQSzc8WkcjKTDHWM2+hBpI0YSUY1w8h9PR/FOSOLYegaFMELydMKn79+wD1q2RrTDt9cJ66jjtB5mkIDKx/ie2jCeWAJvQ7/X/P4CGImi6dkB03HyKLDaMzAUDdiwLIRTIBAIBAKBQCAIYCQFhjq87kjFB+Chgq+MM0fVI3LCOPKizUfI0RiFzhiwBfYhc1ytYyTQuH7UvmCEAojzurKpH4tJ+Rx1LOOO23SsBrLMiVuEIJquw6j7DAZVk6ZsoGLf50u/18E+AUaTSNDvrzs6FUvkeAxtCAQCgUAgEAgE721oauNIcqd3smGE+jOmHRjTsYcR2xvLDUqjrrINlb0T085x5Q9TTzM5NRJMg5/ikBqpm6zSuWv7s8YQR+udnKOBnIbXUz8n0MimrqiOuN6R+83qkQJomerAiGdyXBmMeVbdqJmyHg1YfyYBhDwKBAKBQCAQCN6rMJjiDS3DgKRxv0DQTBRBJ3UwmhCGbfMUCwb1EQCMipU1SmUykTSdlI3y/3tYJdFURkRLV99UWWzMdkafSRhB7vRzMkxjhmONmbZ5mPMbR0JHtWNQQ61R568Rt/0GKmwYTfr0QQsw1dO3N6inkXWjBi+AwZVorQKBQCAQCASCdyPcYTM8rsjQ9GGUnbA9rU2T4jNW+dHb5Z12pkTp5CEkMVrHf4jggJmwPBRRMxFQTsCQKOnkjZNI8IlbjOoF6+g3cv8jAvHwdk3k0zj/MCSVn6fp+ujKoXZtrDEq5TjVVt9PxFyYjsWgAr7j54sTQzAQSNOzB+bBDmD74fsDw4CLQCAQCAQCgUDwQ439CN7ITrjWkQeTugP7dN4Nas6QyuNq/oajFDJOXiCqHkVIDVeuRkVHNbXLj8E0hYAEauQsxvZj/OG6ESQyQjpZnZH7GldXI7F6vRgnvnTMhmtoJJE6gQYYJu6jFN59fuHAgOGZovsSPKLf3TMMw2TPZEo9ylSWg9eLROrV2hcIBAKBQCAQCH4wYeoU0zKbDnWKTSROmw6pK2OUyci8wYQVTPsAjXxoiuMQiQEYyq84pAjCCKVLVysN6uU4AjVEBIms0fIo0gYaycPfuXPn4jBMLG0YQT5hBAkdR1ppH1q7keM1mcWCgVybFFmtbkwj97aBzI4kp3RfDc/C0DPHny1tsGAoqqo78GkEgPHKtz44Mm4/YBgMYW0BwWTiKmavAoFAIBAIBIIfODyMYsMJ5DhzQb0zDWPI4xiCaY9Sl2AMyTCQEGu/bXRfP2CkbgSpMZp9MuUyNubH2/BIFCeHMEw8w7pYT68DI4gkbU91dAKqt6WT3jHlJoU2pl2/mOl67nf/RvlU0rOkq750bzVTWqOZ8qjncdRzCSMGU3QFkU/HbYcFI4hpCMPgCwgEAoFAIBAIBH8ucM1BPsDVokjCiI71GLJnDIZj6rBr29uG+QhpMLS7L+mA0UpVhMwYfPE4YbP3IXORdrRtjeQLRqiE+vyoOsBIqkFZjJiasvmxSqV2biGpNB3POzi/CJHWr/EoBdM0bzAHHnm/8R6zfVmjTJe153IcqQQwE0pdNYy8C9o24fII82wwKZlgIJcCgUAgEAgEAsH3HNy0TvPXQuzngwgAZrURYBAMxWV+jZzk6SaE++wroihyxWg/ZUr3XwRNATO1CcMK5Ujippcxs86xP04kicjoKt9++zQcm65uPtS2AONVRRM5HndcBh9KnUzaBsJqm45Dv68GIm8y8TWSyf1+YwioTh4BRg90jBxUwY1MgycwehAG9mnPGqFu6vMCgUAgEAgEAsE7h27yBqM7nqMII4zq1Jra0FUVMCg1OukEA2EETRXSyk3BV0YGWzGRhDGRSUeqdzCClI0iaCOIVxyGSZ1Xxk1IaZ4RzPiYdvj2cdMxaySXq4im+nFeD2CkIhnZn7bt0P7388sEA4GkdjhBNZFKWs8GKYaeA00l1gcYhgYTdDNpE4kbY14NYHjmNV/bsW1wP0hDPd0yIIRhW4FAIBAIBAKBYH9wVUPrsEbUR3eEzyJo5I+b2AGMNcszkcghZVHvTLNjGPI5ZCSCH0vY8R+hOoUqlUbYdLXM5lOTX6BejxMi3bxTzcd1n0VO1jTyFdeIHy/jpCzOtzMRuFHrqX2c0ryBLMZGtKu3N+oY4tr5jfzppNqkJsIwodTJYkRVHhGQJ6JgG8yPjURSM201DkC4w/69ACPeCTC8F/yd1EkiJ376uwkj3k83GsEVBAKBQCAQCASCPw1CsggwMgE6AOxrjmcs0zvCen29Q07zuro4ggSYgtNElCLu1wcGAjKCDA79DGaYkeURxIj2ZSRqejlECWO4bCJjGtkztT1EEvU6584NEby4aT9+/Qip9H7Ly8sJnRSbjl8/5xHXLLw3pnvBlVeDemrcdoRJb5hKhA9IaD6O+i9CFvXnS3/GNOV8KIcpDL8bRj/icUomtT0muI8O/v4JBAKBQCAQCAQRhGZsEO1MhmRwFKFj25tMSCPrRpjvATMT1Imiyb8x0hkfZWIIBiI5rmyfbY3mk6agLjpxNPkljvrpxAnMymKECJ5DYgaQwPU4BY+o4dRvy58fbg/JnD9/LvgBm8JIwkjt4fY4T1N/f9FtDOdiPBatrk4qh0x8OXk2kctRhBJGKJeG+zNkrqqRxXC7ET6yETX7YZ43w7sx6vm3DIpl5D19WJNWUzkMq5ERIukOB/MRCAQCgUAgELxXwJUOZrZmitqodzIBHqJTauiQDm0X/CJE0NBhj5C6ET6HI0mgQbkaIn26b5xWLzJv8iU0mGXyqcmkMyRLJpNO2IdAesv0C8jfgNAth0SSfoNtzxnJHwwRxMF2g/rRbfT1hn2GRBY0FZQTQdN5jlIGYZhs82vG64Tr2DW2TURS224otQpoZBKiyvRDDVwE24XPumnQhJeZTLJhDPkDw3toIJYA2iCNPjA04v0HGH7/BQKBQCAQCATvEVj69CHMSqkejOu8Aut0wvjOrW5Ktx8RtHSlUTdR1TrlXBGiMpPqZ2vTUTkJvfaIsJiijY4jQ6afT6B8QmeqxxVCnYB565BAeepjlAyaiFx0/XIiSgjBWD4gpKY2YERb0fWBGatHJMeZ3hrO32jaOrhug3lt/ZB6CWNUx3HKsL7O4D8b42bR3IR6lCo5Yn3kOdb8La1xpuIAwz6PMKzij4uMbNwOHu79FwgEAoFAIBC822DqZLIp72SOVTQAYD/VA+AhO6e8rh6cBMYoOLQ8ikhysqf5mA2ZNZoCrBjIxEgFjEgMV8BMvnukEnrEiptvnhuYjfokEuIAUSVxsH4wHZBKYOaqw2TwC2fOJEkB5OVngnKuEHr1v2Cub9omOIaErm4OttfVzQEh5sdv+pnMbU3Xh0i1IZDPkHppuqcGsjmKQNr6swOMTELU/HRfVVwzTx0K7gRmkjn0zrrDPsYA44nfyHf3u3j/h+BKoB2BQCAQCASCH3pY+6wb6njCcIfSW6ebrI6IdGrsvNKy