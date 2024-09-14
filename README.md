<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
        integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
        crossorigin="anonymous" referrerpolicy="no-referrer">
    <link rel="stylesheet" href="V3style.css">

</head>

<body>
    <div class="links">
        <a href="#about" class="link-item"><i class="fas fa-user"></i> About</a>
        <a href="#contact" class="link-item"><i class="fab fa-facebook-f"></i> Contact</a>
        <a href="#my-work" class="link-item"><i class="fas fa-briefcase"></i> My Work</a>
    </div>


  <header class="home">
        <div class="container">
            <div class="items">
                <div class="item">
                    <div class="card">
                        <h2><span>Hi,</span><br> I'm <strong> Jairus Mosomos </strong></h2>
                        <h1> A first year college <br> At UPHSD Molino campus </h1>
                        <h3>"It's more like a Hobby than a job for me"</h3>
                    </div>
                </div>
                <div class="item">
                    <div class="card-tags">
                        <h2>I Do</h2>
                        <div class="tags">
                            <span>Photography</span>
                            <span>Art</span>
                        </div>
                    </div>
                </div>
            </div>


  </div>
    </header>
    <section class="about" id="about">
        <div class="container">
            <div class="items">
                <div class="item">
                    <div class="image">
                        <img src="9ce06ae9-c6fd-4696-a018-0254179ac1b5.jpg" alt="srcset">
                </div>
                <div class="items">
                    <h1>I'm Jairus Mosomos</h1>
                <div class="desc">
                  <img src="Quotation-marks-white-01.png" width="50" alt="srcset">
                    <p>
                       I want to specialize in software design for my computer science course, I want to grow by
                       tackling challenges, seeing them as opportunities to learn and improve. My goal is simple: to
                       find happiness in my work and enjoy what I do.
                   <img src="Quotation-marks-white-01.png" width="50" alt="srcset">
                    </p> 
                </div>
            </div>
        </div>
    </section>
    <section id="my-work" class="my-work">
        <h2>My Work</h2>
        <div class="gallery">
            <div class="gallery-item">
                <img src="IMG_20240409_153157.jpg" alt="Project 1">
                <p>Church in Taal</p>
            </div>
            <div class="gallery-item">
                <img src="IMG_20240423_160106 (1).jpg" alt="Project 2">
                <p>Chinese Violet Asystasia</p>
            </div>
            <div class="gallery-item">
                <img src="IMG_20240423_213239.jpg" alt="Project 3">
                <p>Nodeweed Syndrella</p>
            </div>
            <div class="gallery-item">
                <img src="IMG_20240423_213313_edit_471104565207786 (1).jpg" alt="Project 4">
                <p>Sticky Nightshade</p>
            </div>
            <div class="gallery-item">
                <img src="Screenshot_20230929_235531.jpg" alt="Project 5">
                <p>Plumbago</p>
            </div>
            <div class="gallery-item">
                <img src="new 6.jpg" alt="Project 6">
                <p>UPHSD Molino Campus, Field</p>
            </div>
            <div class="gallery-item">
                <img src="new 7.jpg" alt="Project 7">
                <p>UPHSD Molino Campus, Chapel</p>
            </div>
            <div class="gallery-item">
                <img src="new 8.jpg" alt="Project 8">
                <p>Church in Taal</p>
            </div>
            <div class="gallery-item">
                <img src="new 9.jpeg" alt="Project 9">
                <p>Looc, Nasugbu Batangas, "Palayan"</p>
            </div>
        </div>
    </section>



    
    
  <footer id="contact">
        <div class="footer-content">
            <h3>Contact</h3>
             <a href="https://mail.google.com"><i class="fa-regular fa-envelope"></i> jairusjohnmosomos@gmail.com</a>
            <div class="socials">
                <a href="https://www.facebook.com/jairusjohn.mosomos" target="_blank"><i class="fab fa-facebook-f"></i>
                    Facebook</a>
            </div>
        </div>
    </footer>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const navToggle = document.querySelector('.nav-toggle');
            const topNav = document.querySelector('.top-nav');
            const goUpButton = document.querySelector('.go-up');

  navToggle.addEventListener('click', function() {
                topNav.classList.toggle('active');
            });

  goUpButton.addEventListener('click', function() {
                window.scrollTo({ top: 0, behavior: 'smooth' });
            });
        });
    </script>

 

</body>
</html>
