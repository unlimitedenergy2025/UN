<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unlimited Energy</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        body {
            color:#000000;
        }
    </style>
</head>
<body class="bg-black text-gray-200">

<!-- Top Navigation Bar -->
<nav class="fixed top-0 left-0 w-full bg-white text-black flex justify-between items-center p-4 z-50">
    <img src="https://assets.onecompiler.app/42r523uca/42tzejh5t/profile-240701193019IU18T.png" alt="Unlimited Energy Logo" class="h-10">
    <div class="hidden md:flex space-x-4">
        <div class="relative group">
            <a href="#foundation-section" class="hover:bg-gray-200 p-2 rounded scroll-link">Foundation</a>
            <div class="absolute hidden group-hover:block bg-white text-black mt-2 rounded shadow-lg">
                <a href="#foundation-section" class="block px-4 py-2 hover:bg-gray-200">Foundation Overview</a>
                <a href="#foundation-activities" class="block px-4 py-2 hover:bg-gray-200">Activities</a>
            </div>
        </div>
        <a href="#origin-section" class="hover:bg-gray-200 p-2 rounded scroll-link">The Origin</a>
        <a href="#youth-participation" class="hover:bg-gray-200 p-2 rounded scroll-link">Youth Participation</a>
        <a href="#green-energy" class="hover:bg-gray-200 p-2 rounded scroll-link">Why Green Energy?</a>
        <a href="#volunteer-plan" class="hover:bg-gray-200 p-2 rounded scroll-link">Volunteer Plan</a>
        <a href="#contact" class="hover:bg-gray-200 p-2 rounded scroll-link">Contact</a>
        <button id="language-toggle" class="hover:bg-gray-200 p-2 rounded flex items-center">
            <img src="https://assets.onecompiler.app/42wttk5ev/434w35dzt/Flag_of_Jordan.svg.png" alt="Jordan Flag" class="h-5 w-5 mr-2">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_the_United_States.svg/32px-Flag_of_the_United_States.svg.png" alt="USA Flag" class="h-5 w-5">
        </button>
    </div>
    <div class="md:hidden">
        <button id="menu-button" class="text-black focus:outline-none">
            <i class="fas fa-bars"></i>
        </button>
    </div>
</nav>

<!-- Mobile Menu -->
<div id="mobile-menu" class="fixed top-0 left-0 w-full h-full bg-white text-black flex flex-col items-center justify-center space-y-4 hidden z-40">
    <a href="#foundation-section" class="hover:bg-gray-200 p-2 rounded scroll-link">Foundation</a>
    <a href="#origin-section" class="hover:bg-gray-200 p-2 rounded scroll-link">The Origin</a>
    <a href="#youth-participation" class="hover:bg-gray-200 p-2 rounded scroll-link">Youth Participation</a>
    <a href="#green-energy" class="hover:bg-gray-200 p-2 rounded scroll-link">Why Green Energy?</a>
    <a href="#volunteer-plan" class="hover:bg-gray-200 p-2 rounded scroll-link">Volunteer Plan</a>
    <a href="#contact" class="hover:bg-gray-200 p-2 rounded scroll-link">Contact</a>
    <button id="close-menu-button" class="text-black focus:outline-none">
        <i class="fas fa-times"></i>
    </button>
    <button id="mobile-language-toggle" class="hover:bg-gray-200 p-2 rounded flex items-center">
        <img src="https://assets.onecompiler.app/42wttk5ev/434w35dzt/Flag_of_Jordan.svg.png" alt="Jordan Flag" class="h-5 w-5 mr-2">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_the_United_States.svg/32px-Flag_of_the_United_States.svg.png" alt="USA Flag" class="h-5 w-5">
    </button>
</div>

<!-- Header Section with Background Image -->
<header class="relative w-full h-screen bg-cover bg-center">
    <img src="https://assets.onecompiler.app/42wttk5ev/434phag8s/UNLIMITED%20ENERGY.jpg" alt="Background image of renewable energy sources" class="absolute inset-0 w-full h-full object-cover">
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="absolute inset-0 flex flex-col justify-center items-center text-center text-white z-10">
        <h1 class="text-4xl md:text-6xl font-bold" data-en="Unlimited Energy Initiative" data-ar="مبادرة طاقة بلا حدود">Unlimited Energy Initiative</h1>
        <p class="mt-4 text-lg md:text-2xl" data-en="Empowering Youth and Promoting Sustainability" data-ar="تمكين الشباب وتعزيز الاستدامة">Empowering Youth and Promoting Sustainability</p>
    </div>
</header>

<!-- Foundation Section with Background Image -->
<section id="foundation-section" class="relative py-20 bg-cover bg-center text-white">
    <img src="https://assets.onecompiler.app/42r523uca/434p59yys/1D1A5517-min-1-e1709019652743.jpg" alt="Background image of a foundation event" class="absolute inset-0 w-full h-full object-cover">
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="relative z-10 text-center max-w-3xl mx-auto">
        <h2 class="text-3xl md:text-4xl font-bold mb-6" data-en="Role of His Royal Highness Foundation" data-ar="دور مؤسسة صاحب السمو الملكي">Role of His Royal Highness Foundation</h2>
        <p class="text-lg md:text-xl mb-4" data-en='"Youth are the backbone of the nation and the foundation of the future. It is essential to empower them and provide opportunities for them to lead change and shape Jordan’s future. At the Crown Prince Foundation, we are working towards achieving this goal by supporting initiatives that enhance their role in various fields."' data-ar='"الشباب هم العمود الفقري للأمة وأساس المستقبل. من الضروري تمكينهم وتوفير الفرص لهم لقيادة التغيير وتشكيل مستقبل الأردن. في مؤسسة ولي العهد، نعمل على تحقيق هذا الهدف من خلال دعم المبادرات التي تعزز دورهم في مختلف المجالات."'>
            "Youth are the backbone of the nation and the foundation of the future. It is essential to empower them and provide opportunities for them to lead change and shape Jordan’s future. At the Crown Prince Foundation, we are working towards achieving this goal by supporting initiatives that enhance their role in various fields."
        </p>
        <p class="italic mb-6" data-en="– His Royal Highness Prince Hussein bin Abdullah II" data-ar="– صاحب السمو الملكي الأمير حسين بن عبد الله الثاني">– His Royal Highness Prince Hussein bin Abdullah II</p>
        <p class="text-lg md:text-xl" data-en="Through its support of the 'Unlimited Energy' initiative, the Foundation focuses on promoting renewable energy and sustainable practices, helping youth become active leaders in the transition to a greener future. The initiative provides youth with hands-on opportunities to engage in renewable energy projects and contribute to the achievement of sustainable development goals. His Royal Highness’s vision is to inspire youth to take part in the green energy sector and contribute to tackling climate change challenges." data-ar="من خلال دعمها لمبادرة 'طاقة بلا حدود'، تركز المؤسسة على تعزيز الطاقة المتجددة والممارسات المستدامة، مما يساعد الشباب على أن يصبحوا قادة نشطين في الانتقال إلى مستقبل أكثر خضرة. توفر المبادرة للشباب فرصًا عملية للمشاركة في مشاريع الطاقة المتجددة والمساهمة في تحقيق أهداف التنمية المستدامة. رؤية صاحب السمو الملكي هي إلهام الشباب للمشاركة في قطاع الطاقة الخضراء والمساهمة في مواجهة تحديات تغير المناخ.">
            Through its support of the "Unlimited Energy" initiative, the Foundation focuses on promoting renewable energy and sustainable practices, helping youth become active leaders in the transition to a greener future. The initiative provides youth with hands-on opportunities to engage in renewable energy projects and contribute to the achievement of sustainable development goals. His Royal Highness’s vision is to inspire youth to take part in the green energy sector and contribute to tackling climate change challenges.
        </p>
    </div>
</section>

<!-- Origin Section -->
<section id="origin-section" class="relative py-20 bg-cover bg-center text-white">
    <img src="https://assets.onecompiler.app/42wttk5ev/434phag8s/5.jpg" alt="Background image of the origin of the initiative" class="absolute inset-0 w-full h-full object-cover">
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="relative z-10 text-center max-w-3xl mx-auto">
        <h2 class="text-3xl md:text-4xl font-bold mb-6" data-en="Origin of the Initiative (Unlimited Energy)" data-ar="أصل المبادرة (طاقة بلا حدود)">Origin of the Initiative (Unlimited Energy)</h2>
        <p class="text-lg md:text-xl" data-en="The 'Unlimited Energy' initiative was established in response to the urgent need to raise awareness about the importance of sustainable energy in addressing global environmental challenges. As climate change accelerates, innovative solutions are essential to overcome traditional energy issues. The initiative aims to achieve social and environmental sustainability by empowering youth and enhancing their active participation in this vital field, recognizing that young people are the driving force for change in communities." data-ar="تم إنشاء مبادرة 'طاقة بلا حدود' استجابةً للحاجة الملحة لزيادة الوعي بأهمية الطاقة المستدامة في معالجة التحديات البيئية العالمية. مع تسارع تغير المناخ، تعتبر الحلول المبتكرة ضرورية للتغلب على مشاكل الطاقة التقليدية. تهدف المبادرة إلى تحقيق الاستدامة الاجتماعية والبيئية من خلال تمكين الشباب وتعزيز مشاركتهم الفعالة في هذا المجال الحيوي، مع الاعتراف بأن الشباب هم القوة الدافعة للتغيير في المجتمعات.">
            The "Unlimited Energy" initiative was established in response to the urgent need to raise awareness about the importance of sustainable energy in addressing global environmental challenges. As climate change accelerates, innovative solutions are essential to overcome traditional energy issues. The initiative aims to achieve social and environmental sustainability by empowering youth and enhancing their active participation in this vital field, recognizing that young people are the driving force for change in communities.
        </p>
    </div>
</section>

<!-- Youth Participation Section with Background Image -->
<section id="youth-participation" class="relative py-20 bg-cover bg-center text-white">
    <img src="https://assets.onecompiler.app/42r523uca/434p59yys/4.jpg" alt="Background image of youth participation in renewable energy projects" class="absolute inset-0 w-full h-full object-cover">
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="relative z-10 text-center max-w-3xl mx-auto">
        <h2 class="text-3xl md:text-4xl font-bold mb-6" data-en="The Role of Volunteering and Youth Participation" data-ar="دور التطوع ومشاركة الشباب">The Role of Volunteering and Youth Participation</h2>
        <p class="text-lg md:text-xl mb-4" data-en="This initiative places a strong emphasis on engaging youth in renewable energy projects, recognizing that young people are critical to driving change. It aims to enhance their understanding of environmental issues and provide opportunities for skill development in the green energy sector. By involving them in hands-on projects, workshops, and community outreach programs, the initiative fosters leadership qualities, innovative thinking, and a deep sense of responsibility towards sustainability." data-ar="تركز هذه المبادرة بشكل كبير على إشراك الشباب في مشاريع الطاقة المتجددة، مع الاعتراف بأن الشباب هم العامل الحاسم في دفع التغيير. تهدف إلى تعزيز فهمهم للقضايا البيئية وتوفير فرص لتطوير المهارات في قطاع الطاقة الخضراء. من خلال إشراكهم في مشاريع عملية وورش عمل وبرامج توعية مجتمعية، تعزز المبادرة صفات القيادة والتفكير الابتكاري والشعور العميق بالمسؤولية تجاه الاستدامة.">
            This initiative places a strong emphasis on engaging youth in renewable energy projects, recognizing that young people are critical to driving change. It aims to enhance their understanding of environmental issues and provide opportunities for skill development in the green energy sector. By involving them in hands-on projects, workshops, and community outreach programs, the initiative fosters leadership qualities, innovative thinking, and a deep sense of responsibility towards sustainability.
        </p>
        <p class="text-lg md:text-xl" data-en="Through volunteering, youth gain practical experience in the renewable energy field, empowering them to become change-makers in their communities. The initiative equips them with the tools to advocate for clean energy solutions, while also encouraging them to take on leadership roles in addressing climate change. By supporting youth in their efforts to transition to a greener future, the initiative helps cultivate a generation of environmentally conscious individuals dedicated to building a sustainable world." data-ar="من خلال التطوع، يكتسب الشباب خبرة عملية في مجال الطاقة المتجددة، مما يمكنهم من أن يصبحوا صناع تغيير في مجتمعاتهم. تزودهم المبادرة بالأدوات اللازمة للدفاع عن حلول الطاقة النظيفة، بينما تشجعهم أيضًا على تولي أدوار قيادية في معالجة تغير المناخ. من خلال دعم الشباب في جهودهم للانتقال إلى مستقبل أكثر خضرة، تساعد المبادرة في تنمية جيل من الأفراد الواعيين بيئيًا المكرسين لبناء عالم مستدام.">
            Through volunteering, youth gain practical experience in the renewable energy field, empowering them to become change-makers in their communities. The initiative equips them with the tools to advocate for clean energy solutions, while also encouraging them to take on leadership roles in addressing climate change. By supporting youth in their efforts to transition to a greener future, the initiative helps cultivate a generation of environmentally conscious individuals dedicated to building a sustainable world.
        </p>
    </div>
</section>

<!-- Green Energy Section with Background Image -->
<section id="green-energy" class="relative py-20 bg-cover bg-center text-white">
    <img src="https://assets.onecompiler.app/42r523uca/434p59yys/2.jpg" alt="Background image of green energy sources" class="absolute inset-0 w-full h-full object-cover">
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="relative z-10 text-center max-w-3xl mx-auto">
        <h2 class="text-3xl md:text-4xl font-bold mb-6" data-en="Why Green Energy?" data-ar="لماذا الطاقة الخضراء؟">Why Green Energy?</h2>
        <p class="text-lg md:text-xl mb-4" data-en="Green energy is crucial for environmental sustainability and economic growth. This initiative encourages youth to actively participate in the global shift to cleaner, renewable energy solutions. By promoting renewable energy sources like solar, wind, and hydropower, it aims to reduce reliance on fossil fuels and combat climate change." data-ar="الطاقة الخضراء ضرورية للاستدامة البيئية والنمو الاقتصادي. تشجع هذه المبادرة الشباب على المشاركة الفعالة في التحول العالمي نحو حلول الطاقة المتجددة الأنظف. من خلال الترويج لمصادر الطاقة المتجددة مثل الطاقة الشمسية والرياح والطاقة المائية، تهدف إلى تقليل الاعتماد على الوقود الأحفوري ومكافحة تغير المناخ.">
            Green energy is crucial for environmental sustainability and economic growth. This initiative encourages youth to actively participate in the global shift to cleaner, renewable energy solutions. By promoting renewable energy sources like solar, wind, and hydropower, it aims to reduce reliance on fossil fuels and combat climate change.
        </p>
        <p class="text-lg md:text-xl" data-en="Through workshops, projects, and campaigns, the initiative empowers young people to lead the way in creating a greener future. It provides them with the skills and knowledge necessary to contribute to a sustainable world and helps foster innovation in the green energy sector." data-ar="من خلال ورش العمل والمشاريع والحملات، تمكّن المبادرة الشباب من قيادة الطريق نحو مستقبل أكثر خضرة. تزودهم بالمهارات والمعرفة اللازمة للمساهمة في عالم مستدام وتساعد في تعزيز الابتكار في قطاع الطاقة الخضراء.">
            Through workshops, projects, and campaigns, the initiative empowers young people to lead the way in creating a greener future. It provides them with the skills and knowledge necessary to contribute to a sustainable world and helps foster innovation in the green energy sector.
        </p>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-20 bg-white text-center">
    <h2 class="text-3xl md:text-4xl font-bold text-blue-800 mb-6" data-en="Contact Us" data-ar="اتصل بنا">Contact Us</h2>
    <a href="mailto:energyunlimitedfh@gmail.com" class="bg-blue-800 text-white py-3 px-6 rounded hover:bg-blue-700 transition duration-300" data-en="Send Email" data-ar="إرسال بريد إلكتروني">Send Email</a>
</section>

<!-- Footer Section -->
<footer class="bg-blue-800 text-white py-4 text-center">
    <p data-en="All rights reserved © 2024 - Unlimited Energy Initiative" data-ar="جميع الحقوق محفوظة © 2024 - مبادرة طاقة بلا حدود">All rights reserved © 2024 - Unlimited Energy Initiative</p>
</footer>

<script>
    const menuButton = document.getElementById('menu-button');
    const closeMenuButton = document.getElementById('close-menu-button');
    const mobileMenu = document.getElementById('mobile-menu');

    menuButton.addEventListener('click', () => {
        mobileMenu.classList.remove('hidden');
    });

    closeMenuButton.addEventListener('click', () => {
        mobileMenu.classList.add('hidden');
    });

    // Close mobile menu when a link is clicked
    document.querySelector
