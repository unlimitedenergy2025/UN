
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unlimited Energy Initiative</title>
    <meta name="description" content="A youth-led initiative promoting renewable energy and sustainability">
    <meta name="keywords" content="renewable energy, sustainability, youth empowerment, green energy, NGO">
    <meta name="author" content="Unlimited Energy Initiative">
    
    <!-- Favicon -->
    <link rel="icon" href="https://assets.onecompiler.app/42r523uca/42tzejh5t/profile-240701193019IU18T.png" type="image/png">
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:title" content="Unlimited Energy Initiative">
    <meta property="og:description" content="Empowering Youth and Promoting Sustainability">
    <meta property="og:image" content="https://assets.onecompiler.app/42wttk5ev/434phag8s/UNLIMITED%20ENERGY.jpg">
    <meta property="og:url" content="https://unlimitedenergy.org">
    <meta property="og:type" content="website">
    
    <!-- CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary-color: #1e3a8a; /* blue-900 */
            --secondary-color: #3b82f6; /* blue-500 */
            --accent-color: #10b981; /* emerald-500 */
        }
        
        body {
            color: #333;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            scroll-behavior: smooth;
        }
        
        .rtl {
            direction: rtl;
        }
        
        .dropdown:hover .dropdown-menu {
            display: block;
        }
        
        .section-padding {
            padding: 5rem 0;
        }
        
        .hero-overlay {
            background: linear-gradient(to bottom, rgba(0,0,0,0.3), rgba(0,0,0,0.7));
        }
        
        .content-overlay {
            background: rgba(0,0,0,0.5);
        }
        
        .btn-primary {
            background-color: var(--primary-color);
            transition: all 0.3s ease;
        }
        
        .btn-primary:hover {
            background-color: var(--secondary-color);
            transform: translateY(-2px);
        }
        
        .language-selector {
            transition: all 0.3s ease;
        }
        
        .language-selector:hover {
            transform: scale(1.05);
        }
        
        .nav-link {
            position: relative;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: 0;
            left: 0;
            background-color: var(--primary-color);
            transition: width 0.3s ease;
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        .stat-card {
            transition: transform 0.3s ease;
        }
        
        .stat-card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="bg-gray-50">

<!-- Top Navigation Bar -->
<nav class="fixed top-0 left-0 w-full bg-white shadow-md z-50">
    <div class="container mx-auto px-4">
        <div class="flex justify-between items-center py-4">
            <!-- Logo -->
            <a href="#" class="flex items-center">
                <img src="https://assets.onecompiler.app/42r523uca/42tzejh5t/profile-240701193019IU18T.png" 
                     alt="Unlimited Energy Logo" 
                     class="h-10">
                <span class="ml-3 text-xl font-bold text-gray-800 hidden md:block" data-en="Unlimited Energy" data-ar="طاقة بلا حدود">Unlimited Energy</span>
            </a>

            <!-- Desktop Navigation -->
            <div class="hidden md:flex items-center space-x-1">
                <div class="dropdown relative group">
                    <a href="#foundation-section" class="nav-link px-4 py-2 text-gray-700 hover:text-blue-900 scroll-link" 
                       data-en="Foundation" data-ar="المؤسسة">Foundation</a>
                    <div class="dropdown-menu absolute hidden group-hover:block bg-white shadow-lg rounded-md mt-1 w-48 z-50">
                        <a href="#foundation-section" class="block px-4 py-2 text-gray-700 hover:bg-blue-50" 
                           data-en="Overview" data-ar="نظرة عامة">Overview</a>
                        <a href="#foundation-activities" class="block px-4 py-2 text-gray-700 hover:bg-blue-50" 
                           data-en="Activities" data-ar="الأنشطة">Activities</a>
                    </div>
                </div>
                
                <a href="#origin-section" class="nav-link px-4 py-2 text-gray-700 hover:text-blue-900 scroll-link" 
                   data-en="The Origin" data-ar="الأصل">The Origin</a>
                
                <a href="#youth-participation" class="nav-link px-4 py-2 text-gray-700 hover:text-blue-900 scroll-link" 
                   data-en="Youth" data-ar="الشباب">Youth</a>
                
                <a href="#green-energy" class="nav-link px-4 py-2 text-gray-700 hover:text-blue-900 scroll-link" 
                   data-en="Green Energy" data-ar="الطاقة الخضراء">Green Energy</a>
                
                <a href="#volunteer-plan" class="nav-link px-4 py-2 text-gray-700 hover:text-blue-900 scroll-link" 
                   data-en="Volunteer" data-ar="تطوع">Volunteer</a>
                
                <a href="#contact" class="nav-link px-4 py-2 text-gray-700 hover:text-blue-900 scroll-link" 
                   data-en="Contact" data-ar="اتصل بنا">Contact</a>
                
                <a href="#donate" class="ml-4 px-4 py-2 bg-blue-900 text-white rounded-md hover:bg-blue-800 transition" 
                   data-en="Donate" data-ar="تبرع">Donate</a>
                
                <button id="language-toggle" class="language-selector ml-4 p-2 rounded-full hover:bg-gray-100 flex items-center">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_the_United_States.svg/32px-Flag_of_the_United_States.svg.png" 
                         alt="English" 
                         class="h-5 w-5">
                    <span class="ml-2 text-sm" data-en="EN" data-ar="EN">EN</span>
                </button>
            </div>

            <!-- Mobile menu button -->
            <div class="md:hidden flex items-center">
                <button id="language-toggle-mobile" class="language-selector p-2 rounded-full hover:bg-gray-100 flex items-center mr-2">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_the_United_States.svg/32px-Flag_of_the_United_States.svg.png" 
                         alt="English" 
                         class="h-5 w-5">
                </button>
                
                <button id="menu-button" class="text-gray-700 focus:outline-none">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
    </div>
</nav>

<!-- Mobile Menu -->
<div id="mobile-menu" class="fixed top-0 left-0 w-full h-full bg-white z-40 flex flex-col items-center justify-center hidden">
    <button id="close-menu-button" class="absolute top-4 right-4 text-gray-700 focus:outline-none">
        <i class="fas fa-times text-2xl"></i>
    </button>
    
    <div class="flex flex-col items-center space-y-6">
        <a href="#foundation-section" class="text-xl text-gray-700 hover:text-blue-900 scroll-link" 
           data-en="Foundation" data-ar="المؤسسة">Foundation</a>
        <a href="#origin-section" class="text-xl text-gray-700 hover:text-blue-900 scroll-link" 
           data-en="The Origin" data-ar="الأصل">The Origin</a>
        <a href="#youth-participation" class="text-xl text-gray-700 hover:text-blue-900 scroll-link" 
           data-en="Youth" data-ar="الشباب">Youth</a>
        <a href="#green-energy" class="text-xl text-gray-700 hover:text-blue-900 scroll-link" 
           data-en="Green Energy" data-ar="الطاقة الخضراء">Green Energy</a>
        <a href="#volunteer-plan" class="text-xl text-gray-700 hover:text-blue-900 scroll-link" 
           data-en="Volunteer" data-ar="تطوع">Volunteer</a>
        <a href="#contact" class="text-xl text-gray-700 hover:text-blue-900 scroll-link" 
           data-en="Contact" data-ar="اتصل بنا">Contact</a>
        <a href="#donate" class="px-6 py-3 bg-blue-900 text-white rounded-md hover:bg-blue-800 transition text-xl" 
           data-en="Donate" data-ar="تبرع">Donate</a>
    </div>
</div>

<!-- Header Section with Background Image -->
<header class="relative w-full h-screen mt-16">
    <div class="absolute inset-0 w-full h-full overflow-hidden">
        <img src="https://assets.onecompiler.app/42wttk5ev/434phag8s/UNLIMITED%20ENERGY.jpg" 
             alt="Renewable energy sources including solar panels and wind turbines" 
             class="w-full h-full object-cover">
        <div class="absolute inset-0 hero-overlay"></div>
    </div>
    
    <div class="absolute inset-0 flex flex-col justify-center items-center text-center text-white px-4 z-10">
        <h1 class="text-4xl md:text-6xl font-bold mb-6" 
            data-en="Unlimited Energy Initiative" 
            data-ar="مبادرة طاقة بلا حدود">Unlimited Energy Initiative</h1>
        
        <p class="text-xl md:text-3xl mb-8 max-w-3xl" 
           data-en="Empowering Youth and Promoting Sustainability" 
           data-ar="تمكين الشباب وتعزيز الاستدامة">Empowering Youth and Promoting Sustainability</p>
        
        <div class="flex flex-col sm:flex-row gap-4">
            <a href="#volunteer-plan" class="btn-primary px-8 py-3 rounded-md text-lg font-medium scroll-link" 
               data-en="Join Us" 
               data-ar="انضم إلينا">Join Us</a>
            
            <a href="#about" class="bg-white text-blue-900 px-8 py-3 rounded-md text-lg font-medium hover:bg-gray-100 scroll-link" 
               data-en="Learn More" 
               data-ar="تعرف أكثر">Learn More</a>
        </div>
    </div>
    
    <a href="#about" class="absolute bottom-10 left-1/2 transform -translate-x-1/2 text-white animate-bounce z-10">
        <i class="fas fa-chevron-down text-3xl"></i>
    </a>
</header>

<!-- Stats Section -->
<section class="bg-blue-900 text-white py-12">
    <div class="container mx-auto px-4">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="stat-card bg-white bg-opacity-10 p-6 rounded-lg text-center backdrop-blur-sm">
                <h3 class="text-4xl font-bold mb-2" id="projects-count">0</h3>
                <p class="text-xl" data-en="Projects Completed" data-ar="مشاريع مكتملة">Projects Completed</p>
            </div>
            
            <div class="stat-card bg-white bg-opacity-10 p-6 rounded-lg text-center backdrop-blur-sm">
                <h3 class="text-4xl font-bold mb-2" id="volunteers-count">0</h3>
                <p class="text-xl" data-en="Active Volunteers" data-ar="متطوعين نشطين">Active Volunteers</p>
            </div>
            
            <div class="stat-card bg-white bg-opacity-10 p-6 rounded-lg text-center backdrop-blur-sm">
                <h3 class="text-4xl font-bold mb-2" id="communities-count">0</h3>
                <p class="text-xl" data-en="Communities Impacted" data-ar="مجتمعات متأثرة">Communities Impacted</p>
            </div>
        </div>
    </div>
</section>

<!-- About Section -->
<section id="about" class="section-padding bg-white">
    <div class="container mx-auto px-4">
        <div class="flex flex-col lg:flex-row items-center gap-12">
            <div class="lg:w-1/2">
                <img src="https://assets.onecompiler.app/42r523uca/434p59yys/1D1A5517-min-1-e1709019652743.jpg" 
                     alt="Youth working on renewable energy project" 
                     class="rounded-lg shadow-xl w-full h-auto">
            </div>
            
            <div class="lg:w-1/2">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-6" 
                    data-en="About Our Initiative" 
                    data-ar="حول مبادرتنا">About Our Initiative</h2>
                
                <p class="text-lg text-gray-600 mb-4" 
                   data-en="The Unlimited Energy Initiative is a youth-led movement dedicated to promoting renewable energy and sustainable practices. We believe in the power of young people to drive change and create a greener future for all." 
                   data-ar="مبادرة طاقة بلا حدود هي حركة يقودها الشباب مكرسة لتعزيز الطاقة المتجددة والممارسات المستدامة. نحن نؤمن بقوة الشباب لدفع التغيير وخلق مستقبل أكثر اخضرارًا للجميع.">
                    The Unlimited Energy Initiative is a youth-led movement dedicated to promoting renewable energy and sustainable practices. We believe in the power of young people to drive change and create a greener future for all.
                </p>
                
                <p class="text-lg text-gray-600 mb-6" 
                   data-en="Through education, hands-on projects, and community engagement, we empower youth to become leaders in the transition to sustainable energy solutions." 
                   data-ar="من خلال التعليم والمشاريع العملية والمشاركة المجتمعية، نمكن الشباب من أن يصبحوا قادة في التحول إلى حلول الطاقة المستدامة.">
                    Through education, hands-on projects, and community engagement, we empower youth to become leaders in the transition to sustainable energy solutions.
                </p>
                
                <a href="#mission" class="inline-block btn-primary px-6 py-3 rounded-md text-lg font-medium scroll-link" 
                   data-en="Our Mission" 
                   data-ar="مهمتنا">Our Mission</a>
            </div>
        </div>
    </div>
</section>

<!-- Foundation Section -->
<section id="foundation-section" class="section-padding bg-gray-100">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4" 
                data-en="Supported by the Crown Prince Foundation" 
                data-ar="بدعم من مؤسسة ولي العهد">Supported by the Crown Prince Foundation</h2>
            
            <div class="w-24 h-1 bg-blue-900 mx-auto mb-6"></div>
            
            <p class="text-xl text-gray-600 max-w-3xl mx-auto" 
               data-en="Our initiative is proud to be supported by the Crown Prince Foundation, sharing their vision for youth empowerment and sustainable development." 
               data-ar="تفخر مبادرتنا بدعم مؤسسة ولي العهد، وتشاركها رؤية تمكين الشباب والتنمية المستدامة.">
                Our initiative is proud to be supported by the Crown Prince Foundation, sharing their vision for youth empowerment and sustainable development.
            </p>
        </div>
        
        <div class="flex flex-col lg:flex-row gap-8 items-center">
            <div class="lg:w-1/2">
                <blockquote class="bg-white p-8 rounded-lg shadow-md mb-8">
                    <p class="text-xl italic text-gray-700 mb-4" 
                       data-en="&ldquo;Youth are the backbone of the nation and the foundation of the future. It is essential to empower them and provide opportunities for them to lead change and shape Jordan's future.&rdquo;" 
                       data-ar="&ldquo;الشباب هم العمود الفقري للأمة وأساس المستقبل. من الضروري تمكينهم وتوفير الفرص لهم لقيادة التغيير وتشكيل مستقبل الأردن.&rdquo;">
                        &ldquo;Youth are the backbone of the nation and the foundation of the future. It is essential to empower them and provide opportunities for them to lead change and shape Jordan's future.&rdquo;
                    </p>
                    
                    <p class="font-semibold text-blue-900" 
                       data-en="— HRH Prince Hussein bin Abdullah II" 
                       data-ar="— صاحب السمو الملكي الأمير حسين بن عبد الله الثاني">
                        — HRH Prince Hussein bin Abdullah II
                    </p>
                </blockquote>
            </div>
            
            <div class="lg:w-1/2">
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4" 
                        data-en="Partnership Impact" 
                        data-ar="أثر الشراكة">Partnership Impact</h3>
                    
                    <p class="text-gray-600 mb-4" 
                       data-en="Through this partnership, we have been able to:" 
                       data-ar="من خلال هذه الشراكة، تمكنا من:">
                        Through this partnership, we have been able to:
                    </p>
                    
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-3"></i>
                            <span data-en="Expand our renewable energy projects to 15 new communities" 
                                  data-ar="توسيع مشاريعنا للطاقة المتجددة إلى 15 مجتمعًا جديدًا">Expand our renewable energy projects to 15 new communities</span>
                        </li>
                        
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-3"></i>
                            <span data-en="Train over 500 youth in green energy technologies" 
                                  data-ar="تدريب أكثر من 500 شاب على تقنيات الطاقة الخضراء">Train over 500 youth in green energy technologies</span>
                        </li>
                        
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 mt-1 mr-3"></i>
                            <span data-en="Establish 3 innovation hubs for sustainable solutions" 
                                  data-ar="إنشاء 3 مراكز ابتكار للحلول المستدامة">Establish 3 innovation hubs for sustainable solutions</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Mission Section -->
<section id="mission" class="section-padding bg-blue-900 text-white">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" 
                data-en="Our Mission & Vision" 
                data-ar="مهمتنا ورؤيتنا">Our Mission & Vision</h2>
            
            <div class="w-24 h-1 bg-white mx-auto mb-6"></div>
        </div>
        
        <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-white bg-opacity-10 p-8 rounded-lg backdrop-blur-sm">
                <div class="text-5xl text-blue-300 mb-4">
                    <i class="fas fa-bullseye"></i>
                </div>
                
                <h3 class="text-2xl font-bold mb-4" 
                    data-en="Our Mission" 
                    data-ar="مهمتنا">Our Mission</h3>
                
                <p class="text-lg" 
                   data-en="To empower youth through renewable energy education and hands-on experience, fostering the next generation of sustainability leaders who will drive the transition to a green economy." 
                   data-ar="تمكين الشباب من خلال تعليم الطاقة المتجددة والخبرة العملية، وتنشئة الجيل القادم من قادة الاستدامة الذين سيدفعون التحول نحو الاقتصاد الأخضر.">
                    To empower youth through renewable energy education and hands-on experience, fostering the next generation of sustainability leaders who will drive the transition to a green economy.
                </p>
            </div>
            
            <div class="bg-white bg-opacity-10 p-8 rounded-lg backdrop-blur-sm">
                <div class="text-5xl text-blue-300 mb-4">
                    <i class="fas fa-eye"></i>
                </div>
                
                <h3 class="text-2xl font-bold mb-4" 
                    data-en="Our Vision" 
                    data-ar="رؤيتنا">Our Vision</h3>
                
                <p class="text-lg" 
                   data-en="A world where sustainable energy is accessible to all, and young people are at the forefront of innovative solutions to global environmental challenges." 
                   data-ar="عالم تكون فيه الطاقة المستدامة في متناول الجميع، ويكون الشباب في طليعة الحلول المبتكرة للتحديات البيئية العالمية.">
                    A world where sustainable energy is accessible to all, and young people are at the forefront of innovative solutions to global environmental challenges.
                </p>
            </div>
        </div>
    </div>
</section>

<!-- Origin Section -->
<section id="origin-section" class="section-padding bg-white">
    <div class="container mx-auto px-4">
        <div class="flex flex-col lg:flex-row-reverse items-center gap-12">
            <div class="lg:w-1/2">
                <img src="https://assets.onecompiler.app/42wttk5ev/434phag8s/5.jpg" 
                     alt="Team meeting to discuss renewable energy projects" 
                     class="rounded-lg shadow-xl w-full h-auto">
            </div>
            
            <div class="lg:w-1/2">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-6" 
                    data-en="How It All Began" 
                    data-ar="كيف بدأ كل شيء">How It All Began</h2>
                
                <p class="text-lg text-gray-600 mb-4" 
                   data-en="The Unlimited Energy Initiative was founded in 2020 by a group of young environmental activists who recognized the urgent need for sustainable energy solutions in their communities." 
                   data-ar="تأسست مبادرة طاقة بلا حدود في عام 2020 من قبل مجموعة من الناشطين البيئيين الشباب الذين أدركوا الحاجة الملحة لحلول الطاقة المستدامة في مجتمعاتهم.">
                    The Unlimited Energy Initiative was founded in 2020 by a group of young environmental activists who recognized the urgent need for sustainable energy solutions in their communities.
                </p>
                
                <p class="text-lg text-gray-600 mb-6" 
                   data-en="What started as a small community project installing solar panels in local schools has grown into a nationwide movement, empowering thousands of young people to become agents of change in the green energy transition." 
                   data-ar="ما بدأ كمشروع مجتمعي صغير لتركيب الألواح الشمسية في المدارس المحلية تحول إلى حركة وطنية، تمكن آلاف الشباب ليصبحوا عوامل تغيير في التحول نحو الطاقة الخضراء.">
                    What started as a small community project installing solar panels in local schools has grown into a nationwide movement, empowering thousands of young people to become agents of change in the green energy transition.
                </p>
                
                <a href="#youth-participation" class="inline-block btn-primary px-6 py-3 rounded-md text-lg font-medium scroll-link" 
                   data-en="Our Impact" 
                   data-ar="أثرنا">Our Impact</a>
            </div>
        </div>
    </div>
</section>

<!-- Youth Participation Section -->
<section id="youth-participation" class="section-padding bg-gray-100">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4" 
                data-en="Youth at the Heart of Our Work" 
                data-ar="الشباب في قلب عملنا">Youth at the Heart of Our Work</h2>
            
            <div class="w-24 h-1 bg-blue-900 mx-auto mb-6"></div>
            
            <p class="text-xl text-gray-600 max-w-3xl mx-auto" 
               data-en="We believe young people are not just beneficiaries of our programs, but essential partners in designing and implementing solutions." 
               data-ar="نحن نؤمن بأن الشباب ليسوا مجرد مستفيدين من برامجنا، ولكنهم شركاء أساسيون في تصميم وتنفيذ الحلول.">
                We believe young people are not just beneficiaries of our programs, but essential partners in designing and implementing solutions.
            </p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
                <div class="text-blue-900 text-4xl mb-4">
                    <i class="fas fa-hands-helping"></i>
                </div>
                
                <h3 class="text-xl font-bold mb-3" 
                    data-en="Leadership Development" 
                    data-ar="تنمية القيادة">Leadership Development</h3>
                
                <p class="text-gray-600" 
                   data-en="Our programs cultivate leadership skills, preparing youth to advocate for sustainable energy policies in their communities." 
                   data-ar="تطور برامجنا مهارات القيادة، وتعد الشباب للدفاع عن سياسات الطاقة المستدامة في مجتمعاتهم.">
                    Our programs cultivate leadership skills, preparing youth to advocate for sustainable energy policies in their communities.
                </p>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
                <div class="text-blue-900 text-4xl mb-4">
                    <i class="fas fa-lightbulb"></i>
                </div>
                
                <h3 class="text-xl font-bold mb-3" 
                    data-en="Innovation Labs" 
                    data-ar="معامل الابتكار">Innovation Labs</h3>
                
                <p class="text-gray-600" 
                   data-en="We provide spaces for youth to develop and test innovative solutions to local energy challenges." 
                   data-ar="نوفر مساحات للشباب لتطوير واختبار حلول مبتكرة للتحديات المحلية في مجال الطاقة.">
                    We provide spaces for youth to develop and test innovative solutions to local energy challenges.
                </p>
            </div>
            
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition">
                <div class="text-blue-900 text-4xl mb-4">
                    <i class="fas fa-graduation-cap"></i>
                </div>
                
                <h3 class="text-xl font-bold mb-3" 
                    data-en="Education & Training" 
                    data-ar="التعليم والتدريب">Education & Training</h3>
                
                <p class="text-gray-600" 
                   data-en="Comprehensive training programs in renewable energy technologies and sustainable practices." 
                   data-ar="برامج تدريبية شاملة في تقنيات الطاقة المتجددة والممارسات المستدامة.">
                    Comprehensive training programs in renewable energy technologies and sustainable practices.
                </p>
            </div>
        </div>
    </div>
</section>

<!-- Green Energy Section -->
<section id="green-energy" class="section-padding bg-white">
    <div class="container mx-auto px-4">
        <div class="flex flex-col lg:flex-row items-center gap-12">
            <div class="lg:w-1/2">
                <img src="https://assets.onecompiler.app/42r523uca/434p59yys/2.jpg" 
                     alt="Solar panels and wind turbines generating clean energy" 
                     class="rounded-lg shadow-xl w-full h-auto">
            </div>
            
            <div class="lg:w-1/2">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-6" 
                    data-en="The Power of Green Energy" 
                    data-ar="قوة الطاقة الخضراء">The Power of Green Energy</h2>
                
                <p class="text-lg text-gray-600 mb-4" 
                   data-en="Renewable energy is not just about protecting the environment—it's about creating sustainable economies, empowering communities, and building resilient futures." 
                   data-ar="الطاقة المتجددة لا تتعلق فقط بحماية البيئة - بل تتعلق بخلق اقتصادات مستدامة وتمكين المجتمعات وبناء مستقبل مرن.">
                    Renewable energy is not just about protecting the environment—it's about creating sustainable economies, empowering communities, and building resilient futures.
                </p>
                
                <div class="space-y-4 mb-6">
                    <div class="flex items-start">
                        <div class="flex-shrink-0 mt-1">
                            <div class="h-5 w-5 bg-green-500 rounded-full"></div>
                        </div>
                        <p class="ml-3 text-gray-600" 
                           data-en="Reduces greenhouse gas emissions and combats climate change" 
                           data-ar="يقلل من انبعاثات غازات الاحتباس الحراري ويحارب تغير المناخ">
                            Reduces greenhouse gas emissions and combats climate change
                        </p>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="flex-shrink-0 mt-1">
                            <div class="h-5 w-5 bg-green-500 rounded-full"></div>
                        </div>
                        <p class="ml-3 text-gray-600" 
                           data-en="Creates local jobs and stimulates economic growth" 
                           data-ar="يخلق فرص عمل محلية ويحفز النمو الاقتصادي">
                            Creates local jobs and stimulates economic growth
                        </p>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="flex-shrink-0 mt-1">
                            <div class="h-5 w-5 bg-green-500 rounded-full"></div>
                        </div>
                        <p class="ml-3 text-gray-600" 
                           data-en="Improves energy security and independence" 
                           data-ar="يحسن أمن الطاقة والاستقلال">
                            Improves energy security and independence
                        </p>
                    </div>
                </div>
                
                <a href="#volunteer-plan" class="inline-block btn-primary px-6 py-3 rounded-md text-lg font-medium scroll-link" 
                   data-en="Get Involved" 
                   data-ar="شارك معنا">Get Involved</a>
            </div>
        </div>
    </div>
</section>

<!-- Volunteer Plan Section -->
<section id="volunteer-plan" class="section-padding bg-blue-900 text-white">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" 
                data-en="Join Our Volunteer Program" 
                data-ar="انضم إلى برنامج التطوع لدينا">Join Our Volunteer Program</h2>
            
            <div class="w-24 h-1 bg-white mx-auto mb-6"></div>
            
            <p class="text-xl max-w-3xl mx-auto" 
               data-en="Become part of our movement and help drive the transition to sustainable energy in your community." 
               data-ar="كن جزءًا من حركتنا وساعد في دفع التحول نحو الطاقة المستدامة في مجتمعك.">
                Become part of our movement and help drive the transition to sustainable energy in your community.
            </p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-white bg-opacity-10 p-8 rounded-lg backdrop-blur-sm">
                <div class="text-4xl text-blue-300 mb-4">
                    <i class="fas fa-user-plus"></i>
                </div>
                
                <h3 class="text-2xl font-bold mb-4" 
                    data-en="Who Can Volunteer?" 
                    data-ar="من يمكنه التطوع؟">Who Can Volunteer?</h3>
                
                <p class="mb-4" 
                   data-en="Our volunteer program is open to anyone aged 16-35 who is passionate about sustainability and eager to make a difference." 
                   data-ar="برنامج التطوع لدينا مفتوح لأي شخص تتراوح أعماره بين 16 و35 عامًا شغوف بالاستدامة ومتحمس لإحداث فرق.">
                    Our volunteer program is open to anyone aged 16-35 who is passionate about sustainability and eager to make a difference.
                </p>
                
                <ul class="space-y-2">
                    <li class="flex items-start">
                        <i class="fas fa-check text-blue-300 mt-1 mr-2"></i>
                        <span data-en="No prior experience required" 
                              data-ar="لا يلزم خبرة مسبقة">No prior experience required</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-check text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Training provided" 
                              data-ar="يتم تقديم التدريب">Training provided</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-check text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Flexible time commitments" 
                              data-ar="التزامات زمنية مرنة">Flexible time commitments</span>
                    </li>
                </ul>
            </div>
            
            <div class="bg-white bg-opacity-10 p-8 rounded-lg backdrop-blur-sm">
                <div class="text-4xl text-blue-300 mb-4">
                    <i class="fas fa-tasks"></i>
                </div>
                
                <h3 class="text-2xl font-bold mb-4" 
                    data-en="Volunteer Roles" 
                    data-ar="أدوار المتطوعين">Volunteer Roles</h3>
                
                <p class="mb-4" 
                   data-en="We offer diverse opportunities to match different skills and interests:" 
                   data-ar="نقدم فرصًا متنوعة لتتناسب مع المهارات والاهتمامات المختلفة:">
                    We offer diverse opportunities to match different skills and interests:
                </p>
                
                <ul class="space-y-2">
                    <li class="flex items-start">
                        <i class="fas fa-solar-panel text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Renewable energy projects" 
                              data-ar="مشاريع الطاقة المتجددة">Renewable energy projects</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-chalkboard-teacher text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Community education" 
                              data-ar="التعليم المجتمعي">Community education</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-laptop-code text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Digital content creation" 
                              data-ar="إنشاء المحتوى الرقمي">Digital content creation</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-hands-helping text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Event coordination" 
                              data-ar="تنسيق الفعاليات">Event coordination</span>
                    </li>
                </ul>
            </div>
            
            <div class="bg-white bg-opacity-10 p-8 rounded-lg backdrop-blur-sm">
                <div class="text-4xl text-blue-300 mb-4">
                    <i class="fas fa-award"></i>
                </div>
                
                <h3 class="text-2xl font-bold mb-4" 
                    data-en="Benefits" 
                    data-ar="فوائد">Benefits</h3>
                
                <p class="mb-4" 
                   data-en="Volunteering with us provides valuable experience and opportunities:" 
                   data-ar="التطوع معنا يوفر خبرة وفرصًا قيمة:">
                    Volunteering with us provides valuable experience and opportunities:
                </p>
                
                <ul class="space-y-2">
                    <li class="flex items-start">
                        <i class="fas fa-certificate text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Professional training certificates" 
                              data-ar="شهادات تدريب مهنية">Professional training certificates</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-network-wired text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Networking opportunities" 
                              data-ar="فرص التواصل">Networking opportunities</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-briefcase text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Career development" 
                              data-ar="التطور المهني">Career development</span>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-heart text-blue-300 mt-1 mr-2"></i>
                        <span data-en="Make a real impact" 
                              data-ar="إحداث تأثير حقيقي">Make a real impact</span>
                    </li>
                </ul>
            </div>
        </div>
        
        <div class="text-center mt-12">
            <a href="#contact" class="inline-block bg-white text-blue-900 px-8 py-3 rounded-md text-lg font-medium hover:bg-gray-100 scroll-link" 
               data-en="Apply Now" 
               data-ar="قدم الآن">Apply Now</a>
        </div>
    </div>
</section>

<!-- Donate Section -->
<section id="donate" class="section-padding bg-gray-100">
    <div class="container mx-auto px-4">
        <div class="flex flex-col lg:flex-row items-center gap-12">
            <div class="lg:w-1/2">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-6" 
                    data-en="Support Our Work" 
                    data-ar="ادعم عملنا">Support Our Work</h2>
                
                <p class="text-lg text-gray-600 mb-4" 
                   data-en="Your donation helps us empower more youth, implement more renewable energy projects, and create greater impact in communities across the region." 
                   data-ar="تبرعك يساعدنا في تمكين المزيد من الشباب، وتنفيذ المزيد من مشاريع الطاقة المتجددة، وإحداث تأثير أكبر في المجتمعات في جميع أنحاء المنطقة.">
                    Your donation helps us empower more youth, implement more renewable energy projects, and create greater impact in communities across the region.
                </p>
                
                <div class="bg-white p-6 rounded-lg shadow-md mb-6">
                    <h3 class="text-xl font-bold text-gray-800 mb-4" 
                        data-en="Ways to Give" 
                        data-ar="طرق التبرع">Ways to Give</h3>
                    
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fas fa-money-bill-wave text-green-500 mt-1 mr-3"></i>
                            <span data-en="One-time donation" 
                                  data-ar="تبرع لمرة واحدة">One-time donation</span>
                        </li>
                        
                        <li class="flex items-start">
                            <i class="fas fa-calendar-check text-green-500 mt-1 mr-3"></i>
                            <span data-en="Monthly giving" 
                                  data-ar="تبرع شهري">Monthly giving</span>
                        </li>
                        
                        <li class="flex items-start">
                            <i class="fas fa-briefcase text-green-500 mt-1 mr-3"></i>
                            <span data-en="Corporate sponsorship" 
                                  data-ar="رعاية شركات">Corporate sponsorship</span>
                        </li>
                        
                        <li class="flex items-start">
                            <i class="fas fa-lightbulb text-green-500 mt-1 mr-3"></i>
                            <span data-en="Project-specific funding" 
                                  data-ar="تمويل مشاريع محددة">Project-specific funding</span>
                        </li>
                    </ul>
                </div>
                
                <a href="#contact" class="inline-block btn-primary px-6 py-3 rounded-md text-lg font-medium scroll-link" 
                   data-en="Donate Now" 
                   data-ar="تبرع الآن">Donate Now</a>
            </div>
            
            <div class="lg:w-1/2">
                <div class="bg-white p-8 rounded-lg shadow-xl">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center" 
                        data-en="Your Impact" 
                        data-ar="تأثيرك">Your Impact</h3>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-solar-panel text-blue-900 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="$50" 
                                    data-ar="٥٠$">$50</h4>
                                <p class="text-gray-600" 
                                   data-en="Provides materials for a solar lamp workshop" 
                                   data-ar="يوفر مواد لورشة عمل مصباح شمسي">
                                    Provides materials for a solar lamp workshop
                                </p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-book text-blue-900 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="$100" 
                                    data-ar="١٠٠$">$100</h4>
                                <p class="text-gray-600" 
                                   data-en="Sponsors educational materials for 5 students" 
                                   data-ar="يرعى المواد التعليمية لـ 5 طلاب">
                                    Sponsors educational materials for 5 students
                                </p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-home text-blue-900 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="$500" 
                                    data-ar="٥٠٠$">$500</h4>
                                <p class="text-gray-600" 
                                   data-en="Supports a family with solar home installation" 
                                   data-ar="يدعم عائلة بتركيب نظام شمسي منزلي">
                                    Supports a family with solar home installation
                                </p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-school text-blue-900 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="$1,000+" 
                                    data-ar="١٠٠٠$+">$1,000+</h4>
                                <p class="text-gray-600" 
                                   data-en="Funds renewable energy systems for schools" 
                                   data-ar="يمول أنظمة الطاقة المتجددة للمدارس">
                                    Funds renewable energy systems for schools
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="section-padding bg-white">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4" 
                data-en="Get In Touch" 
                data-ar="تواصل معنا">Get In Touch</h2>
            
            <div class="w-24 h-1 bg-blue-900 mx-auto mb-6"></div>
            
            <p class="text-xl text-gray-600 max-w-3xl mx-auto" 
               data-en="We'd love to hear from you! Whether you're interested in volunteering, partnering, or just learning more, reach out to us." 
               data-ar="نود أن نسمع منك! سواء كنت مهتمًا بالتطوع أو الشراكة أو مجرد معرفة المزيد، تواصل معنا.">
                We'd love to hear from you! Whether you're interested in volunteering, partnering, or just learning more, reach out to us.
            </p>
        </div>
        
        <div class="flex flex-col lg:flex-row gap-12">
            <div class="lg:w-1/2">
                <form class="space-y-6">
                    <div>
                        <label for="name" class="block text-gray-700 mb-2" 
                               data-en="Your Name" 
                               data-ar="اسمك">Your Name</label>
                        <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-900">
                    </div>
                    
                    <div>
                        <label for="email" class="block text-gray-700 mb-2" 
                               data-en="Email Address" 
                               data-ar="البريد الإلكتروني">Email Address</label>
                        <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-900">
                    </div>
                    
                    <div>
                        <label for="subject" class="block text-gray-700 mb-2" 
                               data-en="Subject" 
                               data-ar="الموضوع">Subject</label>
                        <select id="subject" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-900">
                            <option value="" data-en="Select a subject" data-ar="اختر موضوعًا">Select a subject</option>
                            <option value="volunteer" data-en="Volunteering" data-ar="التطوع">Volunteering</option>
                            <option value="donation" data-en="Donation" data-ar="التبرع">Donation</option>
                            <option value="partnership" data-en="Partnership" data-ar="الشراكة">Partnership</option>
                            <option value="information" data-en="General Information" data-ar="معلومات عامة">General Information</option>
                        </select>
                    </div>
                    
                    <div>
                        <label for="message" class="block text-gray-700 mb-2" 
                               data-en="Your Message" 
                               data-ar="رسالتك">Your Message</label>
                        <textarea id="message" rows="5" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-900"></textarea>
                    </div>
                    
                    <button type="submit" class="btn-primary px-6 py-3 rounded-md text-lg font-medium w-full" 
                            data-en="Send Message" 
                            data-ar="إرسال الرسالة">Send Message</button>
                </form>
            </div>
            
            <div class="lg:w-1/2">
                <div class="bg-gray-100 p-8 rounded-lg h-full">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6" 
                        data-en="Contact Information" 
                        data-ar="معلومات الاتصال">Contact Information</h3>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-envelope text-blue-900"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="Email" 
                                    data-ar="البريد الإلكتروني">Email</h4>
                                <a href="mailto:energyunlimitedfh@gmail.com" class="text-blue-900 hover:underline">energyunlimitedfh@gmail.com</a>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-phone-alt text-blue-900"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="Phone" 
                                    data-ar="الهاتف">Phone</h4>
                                <p class="text-gray-600" 
                                   data-en="+962 6 123 4567" 
                                   data-ar="٩٦٢ ٦ ١٢٣ ٤٥٦٧+">+962 6 123 4567</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-map-marker-alt text-blue-900"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="Address" 
                                    data-ar="العنوان">Address</h4>
                                <p class="text-gray-600" 
                                   data-en="123 Green Energy Street, Amman, Jordan" 
                                   data-ar="١٢٣ شارع الطاقة الخضراء، عمان، الأردن">
                                    123 Green Energy Street, Amman, Jordan
                                </p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-clock text-blue-900"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-gray-800" 
                                    data-en="Office Hours" 
                                    data-ar="ساعات العمل">Office Hours</h4>
                                <p class="text-gray-600" 
                                   data-en="Sunday-Thursday: 9AM - 5PM" 
                                   data-ar="الأحد-الخميس: ٩ صباحًا - ٥ مساءً">
                                    Sunday-Thursday: 9AM - 5PM
                                </p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="mt-8">
                        <h4 class="font-bold text-gray-800 mb-4" 
                            data-en="Follow Us" 
                            data-ar="تابعنا">Follow Us</h4>
                        
                        <div class="flex space-x-4">
                            <a href="#" class="bg-blue-900 text-white p-3 rounded-full hover:bg-blue-800 transition">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                            <a href="#" class="bg-blue-900 text-white p-3 rounded-full hover:bg-blue-800 transition">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="bg-blue-900 text-white p-3 rounded-full hover:bg-blue-800 transition">
                                <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#" class="bg-blue-900 text-white p-3 rounded-full hover:bg-blue-800 transition">
                                <i class="fab fa-linkedin-in"></i>
                            </a>
                            <a href="#" class="bg-blue-900 text-white p-3 rounded-full hover:bg-blue-800 transition">
                                <i class="fab fa-youtube"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Newsletter Section -->
<section class="bg-blue-900 text-white py-16">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl md:text-4xl font-bold mb-4" 
            data-en="Stay Updated" 
            data-ar="ابق على اطلاع">Stay Updated</h2>
        
        <p class="text-xl mb-8 max-w-2xl mx-auto" 
           data-en="Subscribe to our newsletter for the latest news, events, and opportunities from Unlimited Energy." 
           data-ar="اشترك في نشرتنا الإخبارية للحصول على آخر الأخبار والفعاليات والفرص من طاقة بلا حدود.">
            Subscribe to our newsletter for the latest news, events, and opportunities from Unlimited Energy.
        </p>
        
        <form class="max-w-md mx-auto flex">
            <input type="email" placeholder="Your email address" 
                   class="px-4 py-3 w-full rounded-l-md focus:outline-none text-gray-800" 
                   data-en-placeholder="Your email address" 
                   data-ar-placeholder="عنوان بريدك الإلكتروني">
            <button type="submit" class="bg-green-500 hover:bg-green-600 px-6 py-3 rounded-r-md font-medium" 
                    data-en="Subscribe" 
                    data-ar="اشتراك">Subscribe</button>
        </form>
    </div>
</section>

<!-- Footer -->
<footer class="bg-gray-900 text-white pt-12 pb-6">
    <div class="container mx-auto px-4">
        <div class="grid md:grid-cols-4 gap-8 mb-8">
            <div>
                <h3 class="text-xl font-bold mb-4" 
                    data-en="About Us" 
                    data-ar="عنّا">About Us</h3>
                <p class="text-gray-400 mb-4" 
                   data-en="Unlimited Energy is a youth-led initiative promoting renewable energy and sustainability through education, innovation, and community engagement." 
                   data-ar="طاقة بلا حدود هي مبادرة يقودها الشباب لتعزيز الطاقة المتجددة والاستدامة من خلال التعليم والابتكار والمشاركة المجتمعية.">
                    Unlimited Energy is a youth-led initiative promoting renewable energy and sustainability through education, innovation, and community engagement.
                </p>
            </div>
            
            <div>
                <h3 class="text-xl font-bold mb-4" 
                    data-en="Quick Links" 
                    data-ar="روابط سريعة">Quick Links</h3>
                <ul class="space-y-2">
                    <li><a href="#about" class="text-gray-400 hover:text-white transition scroll-link" 
                           data-en="About" 
                           data-ar="عنّا">About</a></li>
                    <li><a href="#mission" class="text-gray-400 hover:text-white transition scroll-link" 
                           data-en="Mission" 
                           data-ar="المهمة">Mission</a></li>
                    <li><a href="#youth-participation" class="text-gray-400 hover:text-white transition scroll-link" 
                           data-en="Youth Programs" 
                           data-ar="برامج الشباب">Youth Programs</a></li>
                    <li><a href="#volunteer-plan" class="text-gray-400 hover:text-white transition scroll-link" 
                           data-en="Volunteer" 
                           data-ar="تطوع">Volunteer</a></li>
                    <li><a href="#donate" class="text-gray-400 hover:text-white transition scroll-link" 
                           data-en="Donate" 
                           data-ar="تبرع">Donate</a></li>
                </ul>
            </div>
            
            <div>
                <h3 class="text-xl font-bold mb-4" 
                    data-en="Our Programs" 
                    data-ar="برامجنا">Our Programs</h3>
                <ul class="space-y-2">
                    <li><a href="#" class="text-gray-400 hover:text-white transition" 
                           data-en="Renewable Energy Training" 
                           data-ar="تدريب الطاقة المتجددة">Renewable Energy Training</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white transition" 
                           data-en="Community Solar Projects" 
                           data-ar="مشاريع الطاقة الشمسية المجتمعية">Community Solar Projects</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white transition" 
                           data-en="Youth Innovation Labs" 
                           data-ar="معامل ابتكار الشباب">Youth Innovation Labs</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white transition" 
                           data-en="Sustainability Workshops" 
                           data-ar="ورش عمل الاستدامة">Sustainability Workshops</a></li>
                    <li><a href="#" class="text-gray-400 hover:text-white transition" 
                           data-en="School Outreach" 
                           data-ar="التوعية المدرسية">School Outreach</a></li>
                </ul>
            </div>
            
            <div>
                <h3 class="text-xl font-bold mb-4" 
                    data-en="Contact" 
                    data-ar="اتصل بنا">Contact</h3>
                <address class="not-italic text-gray-400 space-y-2">
                    <p>123 Green Energy Street</p>
                    <p data-en="Amman, Jordan" 
                       data-ar="عمان، الأردن">Amman, Jordan</p>
                    <p>+962 6 123 4567</p>
                    <p><a href="mailto:energyunlimitedfh@gmail.com" class="hover:text-white transition">energyunlimitedfh@gmail.com</a></p>
                </address>
            </div>
        </div>
        
        <div class="border-t border-gray-800 pt-6 flex flex-col md:flex-row justify-between items-center">
            <p class="text-gray-400 mb-4 md:mb-0" 
               data-en="&copy; 2024 Unlimited Energy Initiative. All rights reserved." 
               data-ar="&copy; 2024 مبادرة طاقة بلا حدود. جميع الحقوق محفوظة.">
                &copy; 2024 Unlimited Energy Initiative. All rights reserved.
            </p>
            
            <div class="flex space-x-6">
                <a href="#" class="text-gray-400 hover:text-white transition" 
                   data-en="Privacy Policy" 
                   data-ar="سياسة الخصوصية">Privacy Policy</a>
                <a href="#" class="text-gray-400 hover:text-white transition" 
                   data-en="Terms of Service" 
                   data-ar="شروط الخدمة">Terms of Service</a>
                <a href="#" class="text-gray-400 hover:text-white transition" 
                   data-en="Sitemap" 
                   data-ar="خريطة الموقع">Sitemap</a>
            </div>
        </div>
    </div>
</footer>

<!-- Back to Top Button -->
<button id="back-to-top" class="fixed bottom-8 right-8 bg-blue-900 text-white p-3 rounded-full shadow-lg opacity-0 invisible transition-all duration-300 z-50">
    <i class="fas fa-arrow-up"></i>
</button>

<script>
    // Mobile menu toggle
    const menuButton = document.getElementById('menu-button');
    const closeMenuButton = document.getElementById('close-menu-button');
    const mobileMenu = document.getElementById('mobile-menu');
    
    menuButton.addEventListener('click', () => {
        mobileMenu.classList.remove('hidden');
        document.body.style.overflow = 'hidden';
    });
    
    closeMenuButton.addEventListener('click', () => {
        mobileMenu.classList.add('hidden');
        document.body.style.overflow = 'auto';
    });
    
    // Language toggle
    let currentLanguage = 'en';
    const languageToggle = document.getElementById('language-toggle');
    const mobileLanguageToggle = document.getElementById('language-toggle-mobile');
    
    function toggleLanguage() {
        currentLanguage = currentLanguage === 'en' ? 'ar' : 'en';
        updateLanguage();
    }
    
    function updateLanguage() {
        // Update all elements with data-en and data-ar attributes
        document.querySelectorAll('[data-en], [data-ar]').forEach(element => {
            if (currentLanguage === 'en') {
                if (element.tagName === 'INPUT' && element.hasAttribute('placeholder')) {
                    element.placeholder = element.getAttribute('data-en-placeholder') || '';
                } else {
                    element.textContent = element.getAttribute('data-en');
                }
            } else {
                if (element.tagName === 'INPUT' && element.hasAttribute('placeholder')) {
                    element.placeholder = element.getAttribute('data-ar-placeholder') || '';
                } else {
                    element.textContent = element.getAttribute('data-ar');
                }
            }
        });
        
        // Update HTML direction
        document.documentElement.dir = currentLanguage === 'ar' ? 'rtl' : 'ltr';
        
        // Update language toggle button
        if (languageToggle) {
            if (currentLanguage === 'en') {
                languageToggle.innerHTML = `
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_the_United_States.svg/32px-Flag_of_the_United_States.svg.png" 
                         alt="English" 
                         class="h-5 w-5">
                    <span class="ml-2 text-sm">EN</span>
                `;
            } else {
                languageToggle.innerHTML = `
                    <img src="https://assets.onecompiler.app/42wttk5ev/434w35dzt/Flag_of_Jordan.svg.png" 
                         alt="Arabic" 
                         class="h-5 w-5">
                    <span class="ml-2 text-sm">AR</span>
                `;
            }
        }
        
        if (mobileLanguageToggle) {
            if (currentLanguage === 'en') {
                mobileLanguageToggle.innerHTML = `
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_the_United_States.svg/32px-Flag_of_the_United_States.svg.png" 
                         alt="English" 
                         class="h-5 w-5">
                `;
            } else {
                mobileLanguageToggle.innerHTML = `
                    <img src="https://assets.onecompiler.app/42wttk5ev/434w35dzt/Flag_of_Jordan.svg.png" 
                         alt="Arabic" 
                         class="h-5 w-5">
                `;
            }
        }
    }
    
    if (languageToggle) {
        languageToggle.addEventListener('click', toggleLanguage);
    }
    
    if (mobileLanguageToggle) {
        mobileLanguageToggle.addEventListener('click', toggleLanguage);
    }
    
    // Smooth scrolling for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            
            const targetId = this.getAttribute('href');
            if (targetId === '#') return;
            
            const targetElement = document.querySelector(targetId);
            if (targetElement) {
                // Close mobile menu if open
                mobileMenu.classList.add('hidden');
                document.body.style.overflow = 'auto';
                
                // Scroll to target
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
            }
        });
    });
    
    // Back to top button
    const backToTopButton = document.getElementById('back-to-top');
    
    window.addEventListener('scroll', () => {
        if (window.pageYOffset > 300) {
            backToTopButton.classList.remove('opacity-0', 'invisible');
            backToTopButton.classList.add('opacity-100', 'visible');
        } else {
            backToTopButton.classList.remove('opacity-100', 'visible');
            backToTopButton.classList.add('opacity-0', 'invisible');
        }
    });
    
    backToTopButton.addEventListener('click', () => {
        window.scrollTo({
            top: 0,
            behavior: 'smooth'
        });
    });
    
    // Animate stats counters
    function animateValue(id, start, end, duration) {
        const obj = document.getElementById(id);
        let startTimestamp = null;
        const step = (timestamp) => {
            if (!startTimestamp) startTimestamp = timestamp;
            const progress = Math.min((timestamp - startTimestamp) / duration, 1);
            const value = Math.floor(progress * (end - start) + start);
            obj.innerHTML = value.toLocaleString();
            if (progress < 1) {
                window.requestAnimationFrame(step);
            }
        };
        window.requestAnimationFrame(step);
    }
    
    // Intersection Observer for stats animation
    const statsSection = document.querySelector('section.bg-blue-900.text-white');
    
    const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                animateValue('projects-count', 0, 42, 2000);
                animateValue('volunteers-count', 0, 350, 2000);
                animateValue('communities-count', 0, 18, 2000);
                observer.unobserve(entry.target);
            }
        });
    }, { threshold: 0.5 });
    
    if (statsSection) {
        observer.observe(statsSection);
    }
    
    // Initialize language
    updateLanguage();
</script>
</body>
</html>
