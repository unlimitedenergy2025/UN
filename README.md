<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Unlimited Energy</title>
  <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">
  <style>
      body {
          font-family: 'Arial', sans-serif;
          margin: 0;
          padding: 0;
          background-color: #f4f4f4;
          color: #333;
      }

      /* Top navigation bar */
      nav {
          position: fixed;
          top: 0;
          left: 0;
          width: 100%;
          background-color: #326c9b;
          color: white;
          display: flex;
          justify-content: space-around;
          align-items: center;
          padding: 15px;
          z-index: 1000;
      }

      nav a {
          color: white;
          text-decoration: none;
          padding: 10px 20px;
          font-size: 1.1em; /* Reduced */
          text-align: center;
          display: inline-block;
          transition: background-color 0.3s;
      }

      nav a:hover {
          background-color: #1e4d74;
      }

      .logo {
          height: 40px;
      }

      /* Header Section */
      header {
          position: relative;
          width: 100%;
          height: 100vh;
          overflow: hidden;
          color: white;
          background-image: url('https://assets.onecompiler.app/42wttk5ev/434phag8s/UNLIMITED%20ENERGY.jpg');
          background-size: cover;
          background-position: center;
      }

      .header-overlay {
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          background: rgba(0, 0, 0, 0.5);
      }

      .header-content {
          position: absolute;
          top: 50%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          z-index: 2;
      }

      .header-content h1 {
          font-size: 2.8em; /* Reduced */
          font-weight: bold;
          color: white;
      }

      .header-content p {
          font-size: 1.3em; /* Reduced */
          color: white;
          margin-top: 10px;
      }

      /* Foundation Section */
      .foundation-section {
          position: relative;
          color: white;
          padding: 100px 20px;
          height: 600px;
          background-size: cover;
          background-position: center;
      }

      .foundation-overlay {
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          background: rgba(0, 0, 0, 0.5);
          z-index: 1;
      }

      .foundation-section h2 {
          font-size: 2.3em; /* Reduced */
          margin-bottom: 20px;
          z-index: 2;
          position: relative;
      }

      .foundation-section p {
          font-size: 1.1em; /* Reduced */
          line-height: 1.8;
          margin-bottom: 20px;
          max-width: 800px;
          margin-left: auto;
          margin-right: auto;
          z-index: 2;
          position: relative;
      }

      /* Gallery Section */
      .section-title {
          color: #326c9b;
          font-size: 1.8em; /* Reduced */
          margin: 40px 0 20px 0;
          text-align: center;
          font-weight: bold;
      }

      .swiper-container {
          width: 90%;
          max-width: 1200px;
          margin: 0 auto 50px auto;
          overflow: hidden;
      }

      .swiper-wrapper {
          display: flex;
      }

      .swiper-slide {
          width: 80%;
          margin-right: 20px;
          display: flex;
          justify-content: center;
          align-items: center;
          background: #fff;
          overflow: hidden;
      }

      .swiper-slide img {
          width: 100%;
          height: auto;
          border-radius: 10px;
          box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
      }

      .swiper-button-next, .swiper-button-prev {
          color: #326c9b;
      }

      .swiper-pagination-bullet-active {
          background: #326c9b;
      }

      /* Footer Section */
      footer {
          background-color: #326c9b;
          color: white;
          padding: 15px;
          text-align: center;
      }

      /* Contact Section */
      #contact {
          padding: 50px 20px;
          background-color: #f4f4f4;
          text-align: center;
      }

      .contact-title {
          font-size: 1.8em; /* Reduced */
          color: #326c9b;
          margin-bottom: 20px;
      }

      .contact-button {
          background-color: #326c9b;
          color: white;
          padding: 15px 25px;
          border: none;
          border-radius: 5px;
          font-size: 1.1em; /* Reduced */
          cursor: pointer;
          text-decoration: none;
      }

      .contact-button:hover {
          background-color: #1e4d74;
      }

      /* Smooth Scrolling */
      html {
          scroll-behavior: smooth;
      }

      /* Responsive Design */
      @media (max-width: 768px) {
          .header-content h1 {
              font-size: 1.8em; /* Reduced */
          }

          .header-content p {
              font-size: 1em; /* Reduced */
          }

          .foundation-section h2 {
              font-size: 1.8em; /* Reduced */
          }

          .foundation-section p {
              font-size: 1em; /* Reduced */
          }

          .swiper-container {
              width: 100%;
          }

          .swiper-slide img {
              width: 90%;
              height: auto;
          }
      }

      /* For very small devices */
      @media (max-width: 480px) {
          .header-content h1 {
              font-size: 1.3em; /* Reduced */
          }

          .header-content p {
              font-size: 0.9em; /* Reduced */
          }

          .swiper-button-next, .swiper-button-prev {
              font-size: 1em; /* Reduced */
          }

          .section-title {
              font-size: 1.3em; /* Reduced */
          }
      }
  </style>
</head>
<body>

<!-- Top Navigation Bar -->
<nav>
  <img src="https://assets.onecompiler.app/42r523uca/42tzejh5t/profile-240701193019IU18T.png" alt="Unlimited Energy Logo" class="logo">
  <a href="#foundation-section">Foundation</a>
  <a href="#origin-section">The Origin</a>
  <a href="#youth-participation">Youth Participation</a>
  <a href="#green-energy">Why Green Energy?</a>
  <a href="#volunteer-plan">Volunteer Plan</a>
  <a href="#contact">Contact</a>
</nav>

<!-- Header Section with Background Image -->
<header>
  <div class="header-overlay"></div>
  <div class="header-content">
      <h1>Unlimited Energy Initiative</h1>
      <p>Empowering Youth and Promoting Sustainability</p>
  </div>
</header>

<!-- Foundation Section with Background Image -->
<section id="foundation-section" class="foundation-section" style="background-image: url('https://assets.onecompiler.app/42r523uca/434p59yys/1D1A5517-min-1-e1709019652743.jpg');">
  <div class="foundation-overlay"></div>
  <h2>Role of His Royal Highness Foundation</h2>
  <p>
      "Youth are the backbone of the nation and the foundation of the future. It is essential to empower them and provide opportunities for them to lead change and shape Jordan’s future. At the Crown Prince Foundation, we are working towards achieving this goal by supporting initiatives that enhance their role in various fields."
      </blockquote>
      <p class="quote-author">– His Royal Highness Prince Hussein bin Abdullah II</p>
  </div>

  <div class="foundation-content">
      <p>
          The Crown Prince Foundation, led by His Royal Highness Prince Hussein bin Abdullah II, plays a pivotal role in supporting Jordanian youth through initiatives that aim to empower them and provide the necessary skills and resources to contribute to a sustainable future for Jordan. 
      </p>
      <p>
          Through its support of the "Unlimited Energy" initiative, the Foundation focuses on promoting renewable energy and sustainable practices, helping youth become active leaders in the transition to a greener future. The initiative provides youth with hands-on opportunities to engage in renewable energy projects and contribute to the achievement of sustainable development goals. His Royal Highness’s vision is to inspire youth to take part in the green energy sector and contribute to tackling climate change challenges.
      </p>
  <p>
  
  </p>
</section>

<!-- Youth Participation Section with Background Image -->
<section id="youth-participation" class="foundation-section" style="background-image: url('https://assets.onecompiler.app/42r523uca/434p59yys/4.jpg');">
  <div class="foundation-overlay"></div>
  <h2>The Role of Volunteering and Youth Participation</h2>
  <p>
      This initiative places a strong emphasis on engaging youth in renewable energy projects, recognizing that young people are critical to driving change. It aims to enhance their understanding of environmental issues and provide opportunities for skill development in the green energy sector. By involving them in hands-on projects, workshops, and community outreach programs, the initiative fosters leadership qualities, innovative thinking, and a deep sense of responsibility towards sustainability.
  </p>
  <p>
      Through volunteering, youth gain practical experience in the renewable energy field, empowering them to become change-makers in their communities. The initiative equips them with the tools to advocate for clean energy solutions, while also encouraging them to take on leadership roles in addressing climate change. By supporting youth in their efforts to transition to a greener future, the initiative helps cultivate a generation of environmentally conscious individuals dedicated to building a sustainable world.
  </p>
</section>

<!-- Green Energy Section with Background Image -->
<section id="green-energy" class="foundation-section" style="background-image: url('https://assets.onecompiler.app/42r523uca/434p59yys/2.jpg');">
  <div class="foundation-overlay"></div>
  <h2>Why Green Energy?</h2>
  <p>
      Green energy is crucial for environmental sustainability and economic growth. This initiative encourages youth to actively participate in the global shift to cleaner, renewable energy solutions. By promoting renewable energy sources like solar, wind, and hydropower, it aims to reduce reliance on fossil fuels and combat climate change.
  </p>
  <p>
      Through workshops, projects, and campaigns, the initiative empowers young people to lead the way in creating a greener future. It provides them with the skills and knowledge necessary to contribute to a sustainable world and helps foster innovation in the green energy sector.
  </p>
</section>

<!-- Contact Section -->
<section id="contact">
  <h2 class="contact-title">Contact Us</h2>
  <a href="mailto:energyunlimitedfh@gmail.com" class="contact-button">Send Email</a>
</section>

<!-- Footer Section -->
<footer>
  <p>All rights reserved © 2024 - Unlimited Energy Initiative</p>
</footer>

<!-- Swiper JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
<script>
  const swiper = new Swiper('.swiper-container', {
      slidesPerView: 'auto',
      spaceBetween: 20,
      loop: true,
      centeredSlides: true,
      navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
      },
      pagination: {
          el: '.swiper-pagination',
          clickable: true,
      },
      breakpoints: {
          640: {
              slidesPerView: 1.5,
              spaceBetween: 10,
          },
          1024: {
              slidesPerView: 3,
              spaceBetween: 20,
          },
      },
  });
</script>

</body>
</html>
