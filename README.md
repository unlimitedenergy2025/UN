
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>طاقة بلا حدود | Unlimited Energy</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #2ecc71;
            --secondary-color: #27ae60;
            --dark-color: #2c3e50;
            --light-color: #ecf0f1;
            --accent-color: #f39c12;
            --text-color: #333;
            --text-light: #7f8c8d;
            --transition: all 0.3s ease;
            --box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Tajawal', 'Poppins', sans-serif;
            color: var(--text-color);
            line-height: 1.6;
            overflow-x: hidden;
            background-color: #f9f9f9;
        }
        
        body[dir="ltr"] {
            font-family: 'Poppins', 'Tajawal', sans-serif;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header Styles */
        header {
            background-color: white;
            box-shadow: var(--box-shadow);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            transition: var(--transition);
        }
        
        header.scrolled {
            background-color: rgba(255, 255, 255, 0.95);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
        }
        
        .logo img {
            height: 50px;
            margin-inline-end: 15px;
        }
        
        .logo h1 {
            font-size: 1.5rem;
            color: var(--dark-color);
            font-weight: 700;
        }
        
        .logo span {
            color: var(--primary-color);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-inline-start: 25px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: var(--dark-color);
            font-weight: 500;
            transition: var(--transition);
            position: relative;
            padding: 5px 0;
        }
        
        nav ul li a::after {
            content: '';
            position: absolute;
            bottom: 0;
            right: 0;
            width: 0;
            height: 2px;
            background-color: var(--primary-color);
            transition: var(--transition);
        }
        
        nav ul li a:hover::after {
            width: 100%;
            left: 0;
        }
        
        nav ul li a:hover {
            color: var(--primary-color);
        }
        
        .language-switcher {
            display: flex;
            align-items: center;
            margin-inline-start: 20px;
        }
        
        .language-switcher button {
            background: none;
            border: none;
            cursor: pointer;
            font-size: 0.9rem;
            color: var(--dark-color);
            padding: 5px 10px;
            border-radius: 5px;
            transition: var(--transition);
        }
        
        .language-switcher button.active {
            background-color: var(--primary-color);
            color: white;
        }
        
        .hamburger {
            display: none;
            cursor: pointer;
            font-size: 1.5rem;
            color: var(--dark-color);
        }
        
        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://assets.onecompiler.app/42wttk5ev/434phag8s/UNLIMITED%20ENERGY.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            margin-top: 80px;
            animation: fadeIn 1.5s ease-in-out;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .hero h2 {
            font-size: 3rem;
            margin-bottom: 20px;
            animation: slideUp 1s ease;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            animation: slideUp 1.2s ease;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 500;
            transition: var(--transition);
            border: 2px solid var(--primary-color);
            animation: slideUp 1.4s ease;
        }
        
        .btn:hover {
            background-color: transparent;
            color: var(--primary-color);
            transform: translateY(-3px);
        }
        
        .btn-outline {
            background-color: transparent;
            color: white;
            border: 2px solid white;
            margin-inline-start: 15px;
        }
        
        .btn-outline:hover {
            background-color: white;
            color: var(--dark-color);
        }
        
        /* About Section */
        .section {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            position: relative;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            color: var(--dark-color);
            display: inline-block;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background-color: var(--primary-color);
        }
        
        .about-content {
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            gap: 40px;
        }
        
        .about-text {
            flex: 1;
            min-width: 300px;
        }
        
        .about-text h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--dark-color);
        }
        
        .about-text p {
            margin-bottom: 15px;
            color: var(--text-light);
        }
        
        .about-image {
            flex: 1;
            min-width: 300px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--box-shadow);
            animation: fadeInRight 1s ease;
        }
        
        .about-image img {
            width: 100%;
            height: auto;
            display: block;
            transition: var(--transition);
        }
        
        .about-image:hover img {
            transform: scale(1.05);
        }
        
        /* Partners Section */
        .partners {
            background-color: var(--light-color);
        }
        
        .partners-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
      .partner-card {
    background-color: #ffffff; /* يمكنك تغيير هذا اللون إلى ما تريد */
    border-radius: 10px;
    padding: 30px;
    text-align: center;
    box-shadow: var(--box-shadow);
    transition: var(--transition);

        }
        
        .partner-card:hover {
            transform: translateY(-10px);
        }
        
        .partner-card img {
            height: 80px;
            margin-bottom: 20px;
            object-fit: contain;
        }
        
        .partner-card h3 {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: var(--dark-color);
        }
        
        /* Team Section */
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .team-member {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--box-shadow);
            transition: var(--transition);
            text-align: center;
        }
        
        .team-member:hover {
            transform: translateY(-10px);
        }
        
        .member-image {
            height: 250px;
            overflow: hidden;
        }
        
        .member-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: var(--transition);
        }
        
        .team-member:hover .member-image img {
            transform: scale(1.1);
        }
        
        .member-info {
            padding: 20px;
        }
        
        .member-info h3 {
            font-size: 1.3rem;
            margin-bottom: 5px;
            color: var(--dark-color);
        }
        
        .member-info p {
            color: var(--text-light);
            font-size: 0.9rem;
        }
        
        /* Achievements Section */
        .achievements {
            background: linear-gradient(rgba(46, 204, 113, 0.9), rgba(39, 174, 96, 0.9)), url('https://assets.onecompiler.app/42r523uca/434p59yys/1D1A5517-min-1-e1709019652743.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: white;
            text-align: center;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .stat-item {
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            backdrop-filter: blur(5px);
            transition: var(--transition);
        }
        
        .stat-item:hover {
            transform: translateY(-10px);
            background-color: rgba(255, 255, 255, 0.2);
        }
        
        .stat-item i {
            font-size: 3rem;
            margin-bottom: 15px;
            color: white;
        }
        
        .stat-item h3 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        .stat-item p {
            font-size: 1.1rem;
        }
        
        /* Why Green Energy Section */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .feature-card {
            background-color: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: var(--box-shadow);
            transition: var(--transition);
            text-align: center;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
        }
        
        .feature-card i {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin-bottom: 20px;
        }
        
        .feature-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--dark-color);
        }
        
        .feature-card p {
            color: var(--text-light);
        }
        
        /* Contact Section */
        .contact {
            background-color: var(--light-color);
        }
        
        .contact-container {
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
        }
        
        .contact-info {
            flex: 1;
            min-width: 300px;
        }
        
        .contact-info h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--dark-color);
        }
        
        .contact-details {
            margin-bottom: 30px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .contact-item i {
            font-size: 1.2rem;
            color: var(--primary-color);
            margin-inline-end: 15px;
            width: 30px;
            text-align: center;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background-color: var(--primary-color);
            color: white;
            border-radius: 50%;
            transition: var(--transition);
        }
        
        .social-links a:hover {
            background-color: var(--dark-color);
            transform: translateY(-5px);
        }
        
        .contact-form {
            flex: 1;
            min-width: 300px;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: var(--box-shadow);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #8fa4f2;
            border-radius: 5px;
            font-family: inherit;
            transition: var(--transition);
        }
        
        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(46, 204, 113, 0.2);
        }
        
        .form-group textarea {
            height: 150px;
            resize: vertical;
        }
        
        /* Footer */
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 50px 0 20px;
        }
        
        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .footer-col h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-col h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background-color: var(--primary-color);
        }
        
        .footer-col p {
            margin-bottom: 15px;
            color: #bdc3c7;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 10px;
        }
        
        .footer-links a {
            color: #bdc3c7;
            text-decoration: none;
            transition: var(--transition);
        }
        
        .footer-links a:hover {
            color: var(--primary-color);
            padding-inline-start: 5px;
        }
        
        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #bdc3c7;
            font-size: 0.9rem;
        }
        
        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes slideUp {
            from { 
                opacity: 0;
                transform: translateY(30px);
            }
            to { 
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes fadeInRight {
            from { 
                opacity: 0;
                transform: translateX(50px);
            }
            to { 
                opacity: 1;
                transform: translateX(0);
            }
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            .hero h2 {
                font-size: 2.5rem;
            }
            
            .section-title h2 {
                font-size: 2rem;
            }
        }
        
        @media (max-width: 768px) {
            .header-container {
                flex-wrap: wrap;
            }
            
            nav {
                width: 100%;
                order: 3;
                margin-top: 15px;
                display: none;
            }
            
            nav.active {
                display: block;
            }
            
            nav ul {
                flex-direction: column;
            }
            
            nav ul li {
                margin: 10px 0;
                margin-inline-start: 0;
            }
            
            .hamburger {
                display: block;
            }
            
            .hero h2 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .btn {
                padding: 10px 20px;
            }
        }
        
        @media (max-width: 576px) {
            .hero {
                height: auto;
                padding: 100px 0;
            }
            
            .section {
                padding: 50px 0;
            }
            
            .section-title h2 {
                font-size: 1.8rem;
            }
            
            .about-content {
                flex-direction: column;
            }
            
            .contact-container {
                flex-direction: column;
            }
        }
        /* أنماط المدونة */
.blog-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 40px;
}

.blog-post {
    background-color: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
}

.blog-post:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.blog-image {
    height: 200px;
    overflow: hidden;
}

.blog-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: all 0.3s ease;
}

.blog-content {
    padding: 20px;
}

.blog-content h3 {
    font-size: 1.3rem;
    margin-bottom: 10px;
    color: #2c3e50;
}

.blog-content p {
    color: #7f8c8d;
    margin-bottom: 15px;
}

.blog-date {
    font-size: 0.8rem;
    color: #7f8c8d;
}

.blog-admin {
    background-color: #f8f9fa;
    padding: 30px;
    border-radius: 10px;
    margin-top: 30px;
}
    </style>
</head>
<body>
    <!-- Header -->
    <header id="header">
        <div class="container header-container">
            <div class="logo">
                <img src="https://assets.onecompiler.app/42r523uca/42tzejh5t/profile-240701193019IU18T.png" alt="طاقة بلا حدود">
                <h1>طاقة <span>بلا حدود</span></h1>
            </div>
            
            <nav id="nav">
                <ul>
                    <li><a href="#about">من نحن</a></li>
                    <li><a href="#partners">شركاؤنا</a></li>
                    <li><a href="#team">فريق العمل</a></li>
                    <li><a href="#achievements">إنجازاتنا</a></li>
                    <li><a href="#contact">تواصل معنا</a></li>
                </ul>
            </nav>
            
            <div class="language-switcher">
                <button id="ar-btn" class="active">العربية</button>
                <button id="en-btn">English</button>
            </div>
            
            <div class="hamburger" id="hamburger">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h2 class="ar-text">طاقة بلا حدود</h2>
            <h2 class="en-text" style="display: none;">Unlimited Energy</h2>
            <p class="ar-text">مبادرة شبابية لتطوير الطاقة المتجددة وبناء مستقبل مستدام</p>
            <p class="en-text" style="display: none;">A youth initiative to develop renewable energy and build a sustainable future</p>
            <div class="hero-buttons">
                <a href="#about" class="btn ar-text">اكتشف المزيد</a>
                <a href="#about" class="btn en-text" style="display: none;">Discover More</a>
                <a href="#contact" class="btn btn-outline ar-text">تواصل معنا</a>
                <a href="#contact" class="btn btn-outline en-text" style="display: none;">Contact Us</a>
            </div>
        </div>
    </section>
    
    <!-- About Section -->
    <section class="section" id="about">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">⚡ من نحن</h2>
                <h2 class="en-text" style="display: none;">⚡ About Us</h2>
            </div>
            
            <div class="about-content">
                <div class="about-text">
                    <h3 class="ar-text">طاقة بلا حدود</h3>
                    <h3 class="en-text" style="display: none;">Unlimited Energy</h3>
                    <p class="ar-text">"طاقة بلا حدود" هي مبادرة شبابية تأسست على يد فرحان وحسام من المملكة الأردنية الهاشمية، بعد انخراطهما في مؤسسة ولي العهد. جاءت فكرتها من إيمانهم العميق بأهمية الطاقة المتجددة والاستدامة الخضراء كمسار حتمي لمستقبل أفضل.</p>
                    <p class="en-text" style="display: none;">"Unlimited Energy" is a youth initiative founded by Farhan and Hossam from the Hashemite Kingdom of Jordan, after their involvement with the Crown Prince Foundation. The idea came from their deep belief in the importance of renewable energy and green sustainability as an inevitable path to a better future.</p>
                    
                    <p class="ar-text">تهدف المبادرة إلى زيادة الوعي بالاقتصاد الأخضر، وأهمية الطاقة المتجددة، وآثار التغير المناخي، من خلال العمل الميداني والتدريب العملي وبناء القدرات الشبابية.</p>
                    <p class="en-text" style="display: none;">The initiative aims to raise awareness about the green economy, the importance of renewable energy, and the effects of climate change, through fieldwork, practical training, and youth capacity building.</p>
                </div>
                
                <div class="about-image">
                    <img src="https://assets.onecompiler.app/42r523uca/434p59yys/4.jpg" alt="من نحن">
                </div>
            </div>
            
            <div class="about-content" style="margin-top: 50px;">
                <div class="about-image">
                    <img src="https://assets.onecompiler.app/42r523uca/434p59yys/2.jpg" alt="أصل المبادرة">
                </div>
                
                <div class="about-text">
                    <h3 class="ar-text">🌱 أصل المبادرة</h3>
                    <h3 class="en-text" style="display: none;">🌱 Origin of the Initiative</h3>
                    <p class="ar-text">تم إنشاء "طاقة بلا حدود" استجابةً للحاجة الملحة لزيادة الوعي بأهمية الطاقة المستدامة في مواجهة التحديات البيئية.</p>
                    <p class="en-text" style="display: none;">"Unlimited Energy" was created in response to the urgent need to raise awareness about the importance of sustainable energy in facing environmental challenges.</p>
                    
                    <p class="ar-text">تؤمن المبادرة بأن الشباب هم القوة الدافعة للتغيير، وتسعى إلى تمكينهم وتعزيز مشاركتهم في مشاريع الطاقة المتجددة لتحقيق مستقبل أخضر وآمن.</p>
                    <p class="en-text" style="display: none;">The initiative believes that youth are the driving force for change, and seeks to empower them and enhance their participation in renewable energy projects to achieve a green and secure future.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Partners Section -->
    <section class="section partners" id="partners">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">🤝 شركاؤنا</h2>
                <h2 class="en-text" style="display: none;">🤝 Our Partners</h2>
            </div>
            
            <p class="ar-text" style="text-align: center; margin-bottom: 30px;">نفتخر بشراكاتنا القوية التي ساعدتنا على تحقيق التأثير</p>
            <p class="en-text" style="text-align: center; margin-bottom: 30px; display: none;">We are proud of our strong partnerships that have helped us make an impact</p>
            
            <div class="partners-grid">
                <div class="partner-card">
                    <img src="data:image/jpeg;base64,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" alt="مؤسسة ولي العهد">
                    <h3 class="ar-text">مؤسسة ولي العهد</h3>
                    <h3 class="en-text" style="display: none;">Crown Prince Foundation</h3>
                </div>
                
                <div class="partner-card">
                    <img src="https://taqaspace.com/wp-content/uploads/2024/11/Taqa-5000-x-5000-px-e1732360498333.png" alt="TAQA SPEC">
                    <h3>TAQA SPACE</h3>
                </div>
                
                <div class="partner-card">
                    <img src="https://www.photoeast-academy.com/store/1/Untitled-1.png" alt="Photoeste">
                    <h3>Photoeast</h3>
                </div>
                
                <div class="partner-card">
                    <img src="https://www.jea.org.jo/ebv4.0/root_storage/ar/eb_homepage/asset_1.png" alt="نقابة المهندسين الأردنيين">
                    <h3 class="ar-text">نقابة المهندسين الأردنيين</h3>
                    <h3 class="en-text" style="display: none;">Jordan Engineers Association</h3>
                </div>
                
                <div class="partner-card">
                    <img src="https://www.aabu.edu.jo/_layouts/15/AABUResp/EN/img/arabic.png" alt="جامعة آل البيت">
                    <h3 class="ar-text">جامعة آل البيت</h3>
                    <h3 class="en-text" style="display: none;">Al al-Bayt University</h3>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Team Section -->
    <section class="section" id="team">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">👨‍👩‍👧‍👦 فريق العمل</h2>
                <h2 class="en-text" style="display: none;">👨‍👩‍👧‍👦 Our Team</h2>
            </div>
            
            <p class="ar-text" style="text-align: center; margin-bottom: 30px;">قادة المبادرة الذين يقودون التغيير</p>
            <p class="en-text" style="text-align: center; margin-bottom: 30px; display: none;">The initiative leaders who are driving change</p>
            
            <div class="team-grid">
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Farhan" alt="فرحان">
                    </div>
                    <div class="member-info">
                        <h3>فرحان</h3>
                        <h3 style="display: none;">Farhan</h3>
                        <p class="ar-text">المؤسس المشارك</p>
                        <p class="en-text" style="display: none;">Co-Founder</p>
                    </div>
                </div>
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Hossam" alt="حسام">
                    </div>
                    <div class="member-info">
                        <h3>حسام</h3>
                        <h3 style="display: none;">Hossam</h3>
                        <p class="ar-text">المؤسس المشارك</p>
                        <p class="en-text" style="display: none;">Co-Founder</p>
                    </div>
                </div>
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Rand" alt="رند">
                    </div>
                    <div class="member-info">
                        <h3>رند</h3>
                        <h3 style="display: none;">Rand</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                </div>
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Sulaiman" alt="سليمان">
                    </div>
                    <div class="member-info">
                        <h3>سليمان</h3>
                        <h3 style="display: none;">Sulaiman</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                     </div>
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Sulaiman" alt="سليمان">
                    </div>
                    <div class="member-info">
                        <h3>محمود </h3>
                        <h3 style="display: none;">Mahmood</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                     </div>
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Sulaiman" alt="ماجد">
                    </div>
                    <div class="member-info">
                        <h3>ماجد</h3>
                        <h3 style="display: none;">Majed</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                     </div>
                      <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Sulaiman" alt="سليمان">
                    </div>
                    <div class="member-info">
                        <h3>حلا</h3>
                        <h3 style="display: none;">hala</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                    
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Sulaiman" alt="رواء">
                    </div>
                    <div class="member-info">
                        <h3>رواء</h3>
                        <h3 style="display: none;">Ruwa</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                     </div>
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Sulaiman" alt="هتون">
                    </div>
                    <div class="member-info">
                        <h3>هتون</h3>
                        <h3 style="display: none;">hatoon</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                     </div>
                
                <div class="team-member">
                    <div class="member-image">
                        <img src="https://via.placeholder.com/300x300?text=Sulaiman" alt="noor">
                    </div>
                    <div class="member-info">
                        <h3>نور</h3>
                        <h3 style="display: none;">Noor</h3>
                        <p class="ar-text">عضو الفريق</p>
                        <p class="en-text" style="display: none;">Team Member</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Achievements Section -->
    <section class="section achievements" id="achievements">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">📊 ماذا أنجزنا حتى الآن؟</h2>
                <h2 class="en-text" style="display: none;">📊 What Have We Achieved So Far?</h2>
            </div>
            
            <div class="stats-grid">
                <div class="stat-item">
                    <i class="fas fa-chalkboard-teacher"></i>
                    <h3>30+</h3>
                    <p class="ar-text">ورشة تدريبية</p>
                    <p class="en-text" style="display: none;">Training workshops</p>
                </div>
                
                <div class="stat-item">
                    <i class="fas fa-graduation-cap"></i>
                    <h3>7</h3>
                    <p class="ar-text">دورات تدريبية متخصصة</p>
                    <p class="en-text" style="display: none;">Specialized training courses</p>
                </div>
                
                <div class="stat-item">
                    <i class="fas fa-map-marked-alt"></i>
                    <h3>10</h3>
                    <p class="ar-text">زيارات ميدانية</p>
                    <p class="en-text" style="display: none;">Field visits</p>
                </div>
                
                <div class="stat-item">
                    <i class="fas fa-users"></i>
                    <h3>2000</h3>
                    <p class="ar-text">شاب وشابة على مستوى الوطن العربي</p>
                    <p class="en-text" style="display: none;">Youth trained across the Arab world</p>
                </div>
                
                <div class="stat-item">
                    <i class="fas fa-user-graduate"></i>
                    <h3>3000</h3>
                    <p class="ar-text">شاب وشابة من الأردن</p>
                    <p class="en-text" style="display: none;">Youth trained in Jordan</p>
                </div>
                
                <div class="stat-item">
                    <i class="fas fa-clock"></i>
                    <h3>2000</h3>
                    <p class="ar-text">ساعة تدريبية</p>
                    <p class="en-text" style="display: none;">Training hours</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Why Green Energy Section -->
    <section class="section">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">🌿 لماذا الطاقة الخضراء؟</h2>
                <h2 class="en-text" style="display: none;">🌿 Why Green Energy?</h2>
            </div>
            
            <p class="ar-text" style="text-align: center; margin-bottom: 30px;">الطاقة الخضراء تمثل السبيل الأمثل لتحقيق الاستدامة البيئية والنمو الاقتصادي</p>
            <p class="en-text" style="text-align: center; margin-bottom: 30px; display: none;">Green energy represents the optimal way to achieve environmental sustainability and economic growth</p>
            
            <div class="features-grid">
                <div class="feature-card">
                    <i class="fas fa-leaf"></i>
                    <h3 class="ar-text">تقليل الاعتماد على الوقود الأحفوري</h3>
                    <h3 class="en-text" style="display: none;">Reduce dependence on fossil fuels</h3>
                    <p class="ar-text">نستخدم مصادر الطاقة المتجددة مثل الشمس والرياح لتقليل الانبعاثات الضارة</p>
                    <p class="en-text" style="display: none;">We use renewable energy sources like sun and wind to reduce harmful emissions</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-globe-europe"></i>
                    <h3 class="ar-text">التخفيف من التغير المناخي</h3>
                    <h3 class="en-text" style="display: none;">Mitigate climate change</h3>
                    <p class="ar-text">الطاقة النظيفة تساعد في الحد من ظاهرة الاحتباس الحراري وتأثيراتها</p>
                    <p class="en-text" style="display: none;">Clean energy helps limit global warming and its effects</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-briefcase"></i>
                    <h3 class="ar-text">خلق فرص اقتصادية جديدة</h3>
                    <h3 class="en-text" style="display: none;">Create new economic opportunities</h3>
                    <p class="ar-text">قطاع الطاقة المتجددة يوفر وظائف جديدة ويدعم النمو الاقتصادي</p>
                    <p class="en-text" style="display: none;">The renewable energy sector provides new jobs and supports economic growth</p>
                </div>
                
                <div class="feature-card">
                    <i class="fas fa-hands-helping"></i>
                    <h3 class="ar-text">إشراك الشباب</h3>
                    <h3 class="en-text" style="display: none;">Youth engagement</h3>
                    <p class="ar-text">تمكين الشباب للمشاركة في بناء مستقبل مستدام لأوطانهم</p>
                    <p class="en-text" style="display: none;">Empowering youth to participate in building a sustainable future for their countries</p>
                </div>
            </div>
        </div>
        <!-- قسم المدونة -->
<section class="section blog" id="blog">
    <div class="container">
        <div class="section-title">
            <h2 class="ar-text">📰 المدونة</h2>
            <h2 class="en-text" style="display: none;">📰 Blog</h2>
        </div>
        
        <div class="blog-grid" id="blog-posts">
            <!-- سيتم عرض المقالات هنا تلقائيًا -->
        </div>
        
        <!-- زر لإظهار واجهة الإدارة (للمسؤولين فقط) -->
        <button id="show-admin-btn" class="btn" style="margin: 30px auto; display: block;">
            <span class="ar-text">إدارة المدونة</span>
            <span class="en-text" style="display: none;">Manage Blog</span>
        </button>
        
        <!-- واجهة إضافة مقال جديد (مخفية في البداية) -->
        <div class="blog-admin" style="display: none;" id="blog-admin">
            <h3 class="ar-text">إضافة مقال جديد</h3>
            <h3 class="en-text" style="display: none;">Add New Post</h3>
            
            <form id="blog-form">
                <div class="form-group">
                    <label for="blog-title" class="ar-text">عنوان المقال</label>
                    <label for="blog-title" class="en-text" style="display: none;">Post Title</label>
                    <input type="text" id="blog-title" required>
                </div>
                
                <div class="form-group">
                    <label for="blog-content" class="ar-text">المحتوى</label>
                    <label for="blog-content" class="en-text" style="display: none;">Content</label>
                    <textarea id="blog-content" rows="6" required></textarea>
                </div>
                
                <div class="form-group">
                    <label for="blog-image" class="ar-text">رابط الصورة (اختياري)</label>
                    <label for="blog-image" class="en-text" style="display: none;">Image URL (Optional)</label>
                    <input type="url" id="blog-image" placeholder="https://example.com/image.jpg">
                </div>
                
                <button type="submit" class="btn">
                    <span class="ar-text">نشر</span>
                    <span class="en-text" style="display: none;">Publish</span>
                </button>
            </form>
        </div>
        
    </div>
    </section>
    
    <!-- Volunteer Section -->
    <section class="section" style="background-color: #f5f5f5;">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">👥 دور التطوع ومشاركة الشباب</h2>
                <h2 class="en-text" style="display: none;">👥 Volunteering and Youth Participation</h2>
            </div>
            
            <div class="about-content">
                <div class="about-text">
                    <p class="ar-text">نؤمن أن الشباب هم قلب التغيير، ومن خلال التطوع نمنحهم:</p>
                    <p class="en-text" style="display: none;">We believe that youth are the heart of change, and through volunteering we give them:</p>
                    
                    <ul class="ar-text" style="margin-top: 20px; list-style-type: none;">
                        <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> فرصًا لتطوير مهاراتهم</li>
                        <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> انخراطًا مباشرًا في مشاريع الطاقة</li>
                        <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> بناء روح القيادة والمسؤولية</li>
                        <li><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> مساهمة فعالة في مجتمعاتهم</li>
                    </ul>
                    
                    <ul class="en-text" style="margin-top: 20px; list-style-type: none; display: none;">
                        <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> Opportunities to develop their skills</li>
                        <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> Direct involvement in energy projects</li>
                        <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> Building leadership and responsibility</li>
                        <li><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> Effective contribution to their communities</li>
                    </ul>
                </div>
                
                <div class="about-image">
                    <img src="https://assets.onecompiler.app/42r523uca/434p59yys/3.jpg" alt="التطوع">
                </div>
            </div>
        </div>
    </section>
    
    <!-- Nahno Platform Section -->
    <section class="section">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">💡 منصة "نحن"</h2>
                <h2 class="en-text" style="display: none;">💡 "Nahno" Platform</h2>
            </div>
            
            <div class="about-content">
                <div class="about-image">
                    <img src="https://www.nahno.org/images/logo.png" alt="منصة نحن">
                </div>
                
                <div class="about-text">
                    <p class="ar-text">نحن فخورون بوجودنا على منصة "نحن" التطوعية – أحد برامج مؤسسة ولي العهد</p>
                    <p class="en-text" style="display: none;">We are proud to be on the "Nahno" volunteer platform - one of the Crown Prince Foundation's programs</p>
                    
                    <a href="https://test.nahno.org/ngo/%D8%B7%D8%A7%D9%82%D9%87-%D8%A8%D9%84%D8%A7-%D8%AD%D8%AF%D9%88%D8%AF-Unlimited%E2%80%8F-%E2%80%8Fenergy%E2%80%8F-73659" class="btn" style="margin-top: 20px;" target="_blank">
                        <span class="ar-text">زيارة المنصة</span>
                        <span class="en-text" style="display: none;">Visit Platform</span>
                    </a>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section class="section contact" id="contact">
        <div class="container">
            <div class="section-title">
                <h2 class="ar-text">💬 تواصل معنا</h2>
                <h2 class="en-text" style="display: none;">💬 Contact Us</h2>
            </div>
            
            <div class="contact-container">
                <div class="contact-info">
                    <h3 class="ar-text">ابقى على تواصل</h3>
                    <h3 class="en-text" style="display: none;">Get in Touch</h3>
                    
                    <div class="contact-details">
                        <div class="contact-item">
                            <i class="fas fa-envelope"></i>
                            <span>energyunlimitedfh@gmail.com</span>
                        </div>
                        
                        <div class="contact-item">
                            <i class="fas fa-phone"></i>
                            <span>07 8133 9210</span>
                        </div>
                    </div>
                    
                    <h4 class="ar-text" style="margin-bottom: 15px;">وسائل التواصل الاجتماعي</h4>
                    <h4 class="en-text" style="margin-bottom: 15px; display: none;">Social Media</h4>
                    
                    <div class="social-links">
                        <a href="https://www.facebook.com/61554518817712/about/?_rdr" target="_blank"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://www.instagram.com/unlim.itedenergy" target="_blank"><i class="fab fa-instagram"></i></a>
                        <a href="https://www.linkedin.com/in/Energy%20Unlimited%20FH" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                    
                    <div class="support-section" style="margin-top: 40px;">
                        <h3 class="ar-text">🎁 الدعم والرعاية</h3>
                        <h3 class="en-text" style="display: none;">🎁 Support and Sponsorship</h3>
                        
                        <p class="ar-text" style="margin: 15px 0;">هل تؤمن بأهمية الطاقة المتجددة؟ هل ترغب في تمكين الشباب من قيادة التغيير؟ نرحب بـ:</p>
                        <p class="en-text" style="margin: 15px 0; display: none;">Do you believe in the importance of renewable energy? Do you want to empower youth to lead change? We welcome:</p>
                        
                        <ul class="ar-text" style="list-style-type: none;">
                            <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> الدعم المالي واللوجستي</li>
                            <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> الشراكات المؤسسية</li>
                            <li><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> الرعاة الرسميين</li>
                        </ul>
                        
                        <ul class="en-text" style="list-style-type: none; display: none;">
                            <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> Financial and logistical support</li>
                            <li style="margin-bottom: 10px;"><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> Institutional partnerships</li>
                            <li><i class="fas fa-check" style="color: var(--primary-color); margin-inline-end: 10px;"></i> Official sponsors</li>
                        </ul>
                    </div>
                </div>
                
                <div class="contact-form">
                    <form id="contactForm">
                        <div class="form-group">
                            <label for="name" class="ar-text">الاسم</label>
                            <label for="name" class="en-text" style="display: none;">Name</label>
                            <input type="text" id="name" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="email" class="ar-text">البريد الإلكتروني</label>
                            <label for="email" class="en-text" style="display: none;">Email</label>
                            <input type="email" id="email" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="subject" class="ar-text">الموضوع</label>
                            <label for="subject" class="en-text" style="display: none;">Subject</label>
                            <input type="text" id="subject" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="message" class="ar-text">الرسالة</label>
                            <label for="message" class="en-text" style="display: none;">Message</label>
                            <textarea id="message" required></textarea>
                        </div>
                        
                        <button type="submit" class="btn">
                            <span class="ar-text">إرسال الرسالة</span>
                            <span class="en-text" style="display: none;">Send Message</span>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div class="footer-col">
                    <h3 class="ar-text">طاقة بلا حدود</h3>
                    <h3 class="en-text" style="display: none;">Unlimited Energy</h3>
                    <p class="ar-text">مبادرة شبابية لتطوير الطاقة المتجددة وبناء مستقبل مستدام</p>
                    <p class="en-text" style="display: none;">A youth initiative to develop renewable energy and build a sustainable future</p>
                </div>
                
                <div class="footer-col">
                    <h3 class="ar-text">روابط سريعة</h3>
                    <h3 class="en-text" style="display: none;">Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#about" class="ar-text">من نحن</a><a href="#about" class="en-text" style="display: none;">About Us</a></li>
                        <li><a href="#partners" class="ar-text">شركاؤنا</a><a href="#partners" class="en-text" style="display: none;">Our Partners</a></li>
                        <li><a href="#team" class="ar-text">فريق العمل</a><a href="#team" class="en-text" style="display: none;">Our Team</a></li>
                        <li><a href="#achievements" class="ar-text">إنجازاتنا</a><a href="#achievements" class="en-text" style="display: none;">Achievements</a></li>
                        <li><a href="#contact" class="ar-text">تواصل معنا</a><a href="#contact" class="en-text" style="display: none;">Contact Us</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3 class="ar-text">تواصل معنا</h3>
                    <h3 class="en-text" style="display: none;">Contact Us</h3>
                    <div class="contact-item">
                        <i class="fas fa-envelope" style="color: var(--primary-color);"></i>
                        <span>energyunlimitedfh@gmail.com</span>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone" style="color: var(--primary-color);"></i>
                        <span>07 8133 9210</span>
                    </div>
                </div>
            </div>
            
            <div class="copyright">
                <p class="ar-text">© 2023 طاقة بلا حدود. جميع الحقوق محفوظة.</p>
                <p class="en-text" style="display: none;">© 2023 Unlimited Energy. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
    
    <script>
        // Language Switcher
        const arBtn = document.getElementById('ar-btn');
        const enBtn = document.getElementById('en-btn');
        const arTexts = document.querySelectorAll('.ar-text');
        const enTexts = document.querySelectorAll('.en-text');
        
        arBtn.addEventListener('click', () => {
            document.documentElement.lang = 'ar';
            document.documentElement.dir = 'rtl';
            
            arTexts.forEach(el => el.style.display = 'block');
            enTexts.forEach(el => el.style.display = 'none');
            
            arBtn.classList.add('active');
            enBtn.classList.remove('active');
        });
        
        enBtn.addEventListener('click', () => {
            document.documentElement.lang = 'en';
            document.documentElement.dir = 'ltr';
            
            arTexts.forEach(el => el.style.display = 'none');
            enTexts.forEach(el => el.style.display = 'block');
            
            enBtn.classList.add('active');
            arBtn.classList.remove('active');
        });
        
        // Mobile Menu Toggle
        const hamburger = document.getElementById('hamburger');
        const nav = document.getElementById('nav');
        
        hamburger.addEventListener('click', () => {
            nav.classList.toggle('active');
            hamburger.innerHTML = nav.classList.contains('active') ? '<i class="fas fa-times"></i>' : '<i class="fas fa-bars"></i>';
        });
        
        // Smooth Scrolling for Anchor Links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    if (nav.classList.contains('active')) {
                        nav.classList.remove('active');
                        hamburger.innerHTML = '<i class="fas fa-bars"></i>';
                    }
                }
            });
        });
        
        // Header Scroll Effect
        const header = document.getElementById('header');
        
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
        });
        
        // Form Submission
        const contactForm = document.getElementById('contactForm');
        
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const subject = document.getElementById('subject').value;
            const message = document.getElementById('message').value;
            
            // Here you would typically send the form data to a server
            // For this example, we'll just show an alert
            alert(document.documentElement.lang === 'ar' ? 
                 `شكراً ${name}، تم استلام رسالتك وسنتواصل معك قريباً!` : 
                 `Thank you ${name}, your message has been received and we'll contact you soon!`);
            
            contactForm.reset();
        });
        
        // Animation on Scroll
        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.about-image, .partner-card, .team-member, .stat-item, .feature-card');
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.3;
                
                if (elementPosition < screenPosition) {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                }
            });
        };
        
        // Set initial state for animated elements
        document.querySelectorAll('.about-image, .partner-card, .team-member, .stat-item, .feature-card').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
        });
        
        window.addEventListener('scroll', animateOnScroll);
        window.addEventListener('load', animateOnScroll);
        // ============ إدارة المدونة ============
// 1. تخزين المقالات في localStorage
let blogPosts = JSON.parse(localStorage.getItem('blogPosts')) || [];

// 2. عرض المقالات عند تحميل الصفحة
function displayBlogPosts() {
    const blogGrid = document.getElementById('blog-posts');
    blogGrid.innerHTML = '';
    
    blogPosts.forEach((post, index) => {
        const postElement = document.createElement('div');
        postElement.className = 'blog-post';
        postElement.innerHTML = `
            <div class="blog-image">
                <img src="${post.image || 'https://via.placeholder.com/600x400?text=No+Image'}" alt="${post.title}">
            </div>
            <div class="blog-content">
                <h3>${post.title}</h3>
                <p>${post.content.substring(0, 100)}...</p>
                <div class="blog-date">${new Date(post.date).toLocaleDateString('ar-EG')}</div>
                <button onclick="deletePost(${index})" class="btn" style="margin-top: 10px; background-color: #e74c3c;">
                    <span class="ar-text">حذف</span>
                    <span class="en-text" style="display: none;">Delete</span>
                </button>
            </div>
        `;
        blogGrid.appendChild(postElement);
    });
}

// 3. إضافة مقال جديد
document.getElementById('blog-form').addEventListener('submit', (e) => {
    e.preventDefault();
    
    const newPost = {
        title: document.getElementById('blog-title').value,
        content: document.getElementById('blog-content').value,
        image: document.getElementById('blog-image').value || null,
        date: new Date().toISOString()
    };
    
    blogPosts.unshift(newPost);
    localStorage.setItem('blogPosts', JSON.stringify(blogPosts));
    
    displayBlogPosts();
    document.getElementById('blog-form').reset();
    alert('تم نشر المقال بنجاح!');
});

// 4. حذف مقال
function deletePost(index) {
    if (confirm('هل أنت متأكد من حذف هذا المقال؟')) {
        blogPosts.splice(index, 1);
        localStorage.setItem('blogPosts', JSON.stringify(blogPosts));
        displayBlogPosts();
    }
}

// 5. إظهار/إخفاء واجهة الإدارة
document.getElementById('show-admin-btn').addEventListener('click', () => {
    const password = prompt('أدخل كلمة المرور للإدارة:');
    if (password === 'unlimited123') { // يمكنك تغيير كلمة المرور
        document.getElementById('blog-admin').style.display = 'block';
    } else {
        alert('كلمة المرور غير صحيحة');
    }
});

// 6. عرض المقالات عند تحميل الصفحة
displayBlogPosts();
    </script>
</body>
</html>
