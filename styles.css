<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة التثقيف الأمني السيبراني</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #1a365d;
            --secondary: #2c5282;
            --accent: #e53e3e;
            --light: #ebf8ff;
            --dark: #1a202c;
            --success: #38a169;
            --warning: #dd6b20;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, var(--dark), var(--primary));
            color: var(--light);
            line-height: 1.8;
            min-height: 100vh;
            background-attachment: fixed;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* الشريط العلوي */
        header {
            background: rgba(26, 32, 44, 0.95);
            padding: 15px 0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .logo i {
            font-size: 2rem;
            color: var(--accent);
        }
        
        .logo h1 {
            font-size: 1.6rem;
            color: var(--light);
        }
        
        .nav-links {
            display: flex;
            gap: 20px;
        }
        
        .nav-links a {
            color: var(--light);
            text-decoration: none;
            padding: 8px 15px;
            border-radius: 20px;
            transition: all 0.3s ease;
        }
        
        .nav-links a:hover, .nav-links a.active {
            background: var(--secondary);
        }
        
        /* القسم الرئيسي */
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: url('https://images.unsplash.com/photo-1563089145-599997674d42?q=80&w=1470') no-repeat center center;
            background-size: cover;
            position: relative;
            margin-top: 20px;
            border-radius: 15px;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 15px;
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h2 {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--light);
        }
        
        .hero p {
            font-size: 1.3rem;
            margin-bottom: 30px;
            color: #cbd5e0;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: var(--accent);
            color: white;
            border: none;
            border-radius: 30px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            margin: 10px;
        }
        
        .btn:hover {
            background: #c53030;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .btn-secondary {
            background: transparent;
            border: 2px solid var(--accent);
        }
        
        .btn-secondary:hover {
            background: rgba(229, 62, 62, 0.1);
        }
        
        /* أقسام المحتوى */
        section {
            margin: 70px 0;
            padding: 30px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            position: relative;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            color: var(--light);
            display: inline-block;
            padding-bottom: 15px;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 4px;
            background: var(--accent);
            border-radius: 2px;
        }
        
        /* معجم المصطلحات */
        .terms-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 30px;
        }
        
        .term-card {
            background: rgba(44, 82, 130, 0.6);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
            opacity: 0;
            transform: translateY(20px);
        }
        
        .term-card.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        .term-card:hover {
            transform: translateY(-10px);
            border-color: var(--accent);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
        }
        
        .term-header {
            padding: 20px;
            background: rgba(26, 32, 44, 0.7);
            border-bottom: 2px solid var(--accent);
        }
        
        .term-header h3 {
            font-size: 1.6rem;
            margin-bottom: 10px;
            color: var(--light);
        }
        
        .term-header .category {
            display: inline-block;
            background: var(--accent);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .term-body {
            padding: 20px;
        }
        
        .term-body p {
            margin-bottom: 15px;
            font-size: 1.1rem;
            color: #e2e8f0;
        }
        
        .term-body .example {
            background: rgba(52, 152, 219, 0.1);
            padding: 15px;
            border-radius: 10px;
            border-left: 3px solid var(--accent);
            margin-top: 15px;
            font-style: italic;
        }
        
        /* وحدات التعلم */
        .modules-container {
            display: flex;
            flex-direction: column;
            gap: 25px;
        }
        
        .module {
            background: rgba(44, 82, 130, 0.6);
            border-radius: 15px;
            overflow: hidden;
            display: flex;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            opacity: 0;
            transform: translateY(20px);
        }
        
        .module.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        .module-image {
            flex: 0 0 40%;
            background-size: cover;
            background-position: center;
        }
        
        .module-content {
            flex: 1;
            padding: 30px;
        }
        
        .module-content h3 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: var(--light);
        }
        
        .module-stats {
            display: flex;
            justify-content: space-between;
            margin: 20px 0;
            color: #cbd5e0;
            font-size: 0.9rem;
        }
        
        .module-progress {
            height: 10px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 5px;
            margin: 15px 0;
            overflow: hidden;
        }
        
        .progress-bar {
            height: 100%;
            background: var(--success);
            border-radius: 5px;
            transition: width 1s ease;
        }
        
        /* اختبارات */
        .quiz-container {
            background: rgba(44, 82, 130, 0.6);
            border-radius: 15px;
            padding: 40px;
            max-width: 800px;
            margin: 0 auto;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
        }
        
        .quiz-question {
            font-size: 1.4rem;
            margin-bottom: 30px;
            line-height: 1.8;
            color: var(--light);
        }
        
        .quiz-options {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
            margin-bottom: 30px;
        }
        
        .quiz-option {
            background: rgba(26, 32, 44, 0.6);
            border: 1px solid var(--secondary);
            padding: 15px 20px;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 1.1rem;
        }
        
        .quiz-option:hover {
            background: var(--secondary);
            transform: translateY(-3px);
        }
        
        .quiz-option.selected {
            background: var(--secondary);
            border-color: var(--accent);
            box-shadow: 0 0 0 2px var(--accent);
        }
        
        .quiz-navigation {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
        }
        
        /* أدوات الأمان */
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
        }
        
        .tool-card {
            background: rgba(44, 82, 130, 0.6);
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            opacity: 0;
            transform: translateY(20px);
        }
        
        .tool-card.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        .tool-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
            border: 1px solid var(--accent);
        }
        
        .tool-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--accent);
        }
        
        .tool-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--light);
        }
        
        /* القسم السفلي */
        footer {
            text-align: center;
            padding: 50px 0 30px;
            margin-top: 50px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #a0aec0;
            background: rgba(26, 32, 44, 0.8);
        }
        
        .footer-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
            margin: 30px 0;
        }
        
        .footer-links a {
            color: #cbd5e0;
            text-decoration: none;
            transition: color 0.3s ease;
            font-size: 1.1rem;
        }
        
        .footer-links a:hover {
            color: var(--accent);
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        
        .social-links a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: var(--secondary);
            color: white;
            font-size: 1.5rem;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--accent);
            transform: translateY(-5px);
        }
        
        /* التكيف مع الجوال */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 15px;
            }
            
            .nav-links {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .hero h2 {
                font-size: 2.2rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
            
            .module {
                flex-direction: column;
            }
            
            .module-image {
                height: 200px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <div class="logo">
                <i class="fas fa-shield-alt"></i>
                <h1>منصة التثقيف الأمني السيبراني</h1>
            </div>
            <div class="nav-links">
                <a href="#" class="active">الرئيسية</a>
                <a href="#glossary">المعجم</a>
                <a href="#learning">التعلم</a>
                <a href="#quizzes">الاختبارات</a>
                <a href="#tools">الأدوات</a>
            </div>
        </div>
    </header>
    
    <div class="container">
        <section class="hero">
            <div class="hero-content">
                <h2>أهلاً بك في عالم الأمن السيبراني</h2>
                <p>منصة متكاملة لتثقيف وتدريب الأفراد والمؤسسات في مجال الأمن السيبراني وعلوم الحاسب. تعلم المصطلحات الحديثة، تابع الدورات، اختبر معلوماتك، واستخدم أدوات الأمان لحماية نفسك ومؤسستك.</p>
                <div>
                    <a href="#glossary" class="btn">ابدأ الرحلة</a>
                    <a href="#learning" class="btn btn-secondary">استكشف الدورات</a>
                </div>
            </div>
        </section>
        
        <!-- معجم المصطلحات -->
        <section id="glossary">
            <div class="section-title">
                <h2>معجم المصطلحات الأمنية</h2>
            </div>
            
            <div class="terms-grid">
                <!-- سيتم ملئها بالجافاسكريبت -->
            </div>
            
            <div style="text-align: center; margin-top: 40px;">
                <button id="loadMoreTerms" class="btn">تحميل المزيد من المصطلحات</button>
            </div>
        </section>
        
        <!-- وحدات التعلم -->
        <section id="learning">
            <div class="section-title">
                <h2>وحدات التعلم التفاعلية</h2>
            </div>
            
            <div class="modules-container">
                <!-- سيتم ملئها بالجافاسكريبت -->
            </div>
        </section>
        
        <!-- اختبارات -->
        <section id="quizzes">
            <div class="section-title">
                <h2>اختبارات معرفتك الأمنية</h2>
            </div>
            
            <div class="quiz-container">
                <div class="quiz-question" id="questionText">
                    ما هو الهجوم الذي يستخدم رسائل بريد إلكتروني مزيفة لخداع الضحايا؟
                </div>
                
                <div class="quiz-options" id="quizOptions">
                    <!-- سيتم ملئها بالجافاسكريبت -->
                </div>
                
                <div class="quiz-navigation">
                    <button id="prevQuestion" class="btn btn-secondary">السؤال السابق</button>
                    <button id="nextQuestion" class="btn">السؤال التالي</button>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 40px;">
                <button id="startQuiz" class="btn">بدء اختبار جديد</button>
            </div>
        </section>
        
        <!-- أدوات الأمان -->
        <section id="tools">
            <div class="section-title">
                <h2>أدوات الأمان والتقييم</h2>
            </div>
            
            <div class="tools-grid">
                <!-- سيتم ملئها بالجافاسكريبت -->
            </div>
        </section>
    </div>
    
    <footer>
        <div class="container">
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
            </div>
            
            <div class="footer-links">
                <a href="#">الرئيسية</a>
                <a href="#glossary">المعجم</a>
                <a href="#learning">التعلم</a>
                <a href="#quizzes">الاختبارات</a>
                <a href="#tools">الأدوات</a>
                <a href="#">عن المنصة</a>
                <a href="#">اتصل بنا</a>
                <a href="#">سياسة الخصوصية</a>
            </div>
            
            <p>منصة التثقيف الأمني السيبراني - تم تطويرها لتعزيز الوعي الأمني في العالم العربي</p>
            <p>© 2023 جميع الحقوق محفوظة</p>
        </div>
    </footer>
    
    <script>
        // بيانات التطبيق
        const terms = [
            {
                term: "التصيد الإلكتروني (Phishing)",
                definition: "هو هجوم إلكتروني يستخدم فيه المهاجمون رسائل بريد إلكتروني أو مواقع ويب مزيفة لخداع الضحايا وإغرائهم بتقديم معلومات حساسة مثل كلمات المرور أو أرقام البطاقات الائتمانية.",
                category: "الاختراق",
                example: "رسالة بريد إلكتروني تبدو وكأنها من البنك تطلب تحديث معلومات الحساب."
            },
            {
                term: "برمجيات الفدية (Ransomware)",
                definition: "هو نوع من البرمجيات الخبيثة التي تقوم بتشفير ملفات الضحية وطلب فدية مالية مقابل فك التشفير.",
                category: "البرمجيات الخبيثة",
                example: "برنامج WannaCry الذي أصاب مئات الآلاف من الأجهزة حول العالم في 2017."
            },
            {
                term: "الهندسة الاجتماعية (Social Engineering)",
                definition: "هو تكتيك يستخدمه المهاجمون لخداع الأشخاص لكشف معلومات سرية أو القيام بأفعال معينة.",
                category: "الاختراق",
                example: "الاتصال بالضحية وادعاء أن المتصل من قسم الدعم الفني ويطلب كلمة المرور."
            },
            {
                term: "التصيد المستهدف (Spear Phishing)",
                definition: "هو هجوم تصيد يركز على هدف معين (فرد أو منظمة) ويستخدم معلومات شخصية لزيادة فرص النجاح.",
                category: "الاختراق",
                example: "رسالة بريد إلكتروني موجهة لمدير مالي تبدو وكأنها من الرئيس التنفيذي تطلب تحويل أموال."
            },
            {
                term: "هجوم رفض الخدمة الموزع (DDoS)",
                definition: "هو هجوم يهدف إلى جعل خدمة أو مورد غير متاح للمستخدمين المقصودين عن طريق إغراقه بحركة مرور زائفة من مصادر متعددة.",
                category: "أمن الشبكات",
                example: "هجوم على موقع حكومي باستخدام آلاف الأجهزة المخترقة حول العالم."
            },
            {
                term: "التشفير من طرف إلى طرف (End-to-End Encryption)",
                definition: "نظام اتصالات حيث يتم تشفير البيانات بشكل لا يمكن قراءته إلا من قبل الأطراف المتواصلة، ولا يمكن فك تشفيرها من قبل مزود الخدمة.",
                category: "التشفير",
                example: "تطبيقات المراسلة مثل Signal وWhatsApp تستخدم هذا النوع من التشفير."
            }
        ];

        const courses = [
            {
                title: "أساسيات الأمن السيبراني",
                description: "مقدمة شاملة لمفاهيم الأمن السيبراني وأهميته في العصر الرقمي. تعرف على أنواع التهديدات الإلكترونية وأساليب الحماية الأساسية.",
                duration: "4 ساعات",
                lessons: "5 دروس",
                level: "للمبتدئين",
                progress: 100,
                image: "https://images.unsplash.com/photo-1550751827-4bd374c3f58b?q=80&w=1470"
            },
            {
                title: "أمن الشبكات والتطبيقات",
                description: "تعلم كيفية تأمين البنية التحتية للشبكات والأنظمة والتطبيقات. اكتشف تقنيات الكشف عن التسلل وأساليب منع الاختراقات.",
                duration: "6 ساعات",
                lessons: "7 دروس",
                level: "للمتوسطين",
                progress: 65,
                image: "https://images.unsplash.com/photo-1563206767-5b18f218e8de?q=80&w=1469"
            },
            {
                title: "أمن البيانات والتشفير",
                description: "اكتشف تقنيات التشفير الحديثة وأساليب حماية البيانات الحساسة. تعرف على بروتوكولات الأمان ومبادئ إدارة الهوية والوصول.",
                duration: "8 ساعات",
                lessons: "8 دروس",
                level: "للمتقدمين",
                progress: 0,
                image: "https://images.unsplash.com/photo-1563014959-7aaa83350992?q=80&w=1476"
            }
        ];

        const tools = [
            {
                icon: "fas fa-key",
                title: "مدير كلمات المرور",
                description: "أداة لإنشاء وتخزين وإدارة كلمات مرور قوية وفريدة لكل حساب من حساباتك"
            },
            {
                icon: "fas fa-shield-alt",
                title: "مختبر التصيد الإلكتروني",
                description: "اختبار قدرة موظفيك على التعرف على رسائل التصيد الإلكتروني المزيفة"
            },
            {
                icon: "fas fa-search",
                title: "ماسح الثغرات الأمنية",
                description: "اكتشف الثغرات الأمنية في أنظمتك قبل أن يستغلها المهاجمون"
            }
        ];

        const quizQuestions = [
            {
                question: "ما هو الهجوم الذي يستخدم رسائل بريد إلكتروني مزيفة لخداع الضحايا؟",
                options: [
                    "برمجيات الفدية (Ransomware)",
                    "التصيد الإلكتروني (Phishing)",
                    "هجوم رفض الخدمة (DDoS)",
                    "حصان طروادة (Trojan Horse)"
                ],
                correctAnswer: 1
            },
            {
                question: "أي من هذه الأنواع يصنف كبرمجية خبيثة؟",
                options: [
                    "جدار الحماية",
                    "VPN",
                    "برمجيات الفدية",
                    "التشفير"
                ],
                correctAnswer: 2
            },
            {
                question: "ما هو الغرض من جدار الحماية؟",
                options: [
                    "تشفير البيانات",
                    "منع الوصول غير المصرح به للشبكة",
                    "خداع المستخدمين لكشف معلومات",
                    "طلب فدية مالية"
                ],
                correctAnswer: 1
            }
        ];

        // المتغيرات العامة
        let currentQuestion = 0;
        let selectedOption = null;
        let loadedTerms = 3; // عدد المصطلحات المعروضة مبدئياً

        // تهيئة التطبيق عند تحميل الصفحة
        document.addEventListener('DOMContentLoaded', function() {
            // تهيئة الروابط
            initNavigation();
            
            // تحميل المحتوى
            loadTerms();
            loadCourses();
            loadTools();
            loadQuiz();
            
            // إعداد الأحداث
            setupEvents();
            
            // إعداد تأثيرات الظهور
            setupAnimations();
        });

        // تهيئة التنقل
        function initNavigation() {
            // التنقل السلس
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    
                    const target = document.querySelector(this.getAttribute('href'));
                    if (target) {
                        window.scrollTo({
                            top: target.offsetTop - 80,
                            behavior: 'smooth'
                        });
                        
                        // تحديث الروابط النشطة
                        document.querySelectorAll('.nav-links a').forEach(link => {
                            link.classList.remove('active');
                        });
                        this.classList.add('active');
                    }
                });
            });
        }

        // تحميل المصطلحات
        function loadTerms() {
            const container = document.querySelector('.terms-grid');
            container.innerHTML = '';
            
            terms.slice(0, loadedTerms).forEach((term, index) => {
                const termCard = document.createElement('div');
                termCard.className = `term-card ${index < 3 ? 'visible' : ''}`;
                termCard.innerHTML = `
                    <div class="term-header">
                        <h3>${term.term}</h3>
                        <span class="category">${term.category}</span>
                    </div>
                    <div class="term-body">
                        <p>${term.definition}</p>
                        <div class="example">
                            <strong>مثال:</strong> ${term.example}
                        </div>
                    </div>
                `;
                container.appendChild(termCard);
            });
        }

        // تحميل الدورات
        function loadCourses() {
            const container = document.querySelector('.modules-container');
            container.innerHTML = '';
            
            courses.forEach((course, index) => {
                const module = document.createElement('div');
                module.className = `module ${index < 3 ? 'visible' : ''}`;
                module.innerHTML = `
                    <div class="module-image" style="background-image: url('${course.image}');"></div>
                    <div class="module-content">
                        <h3>${course.title}</h3>
                        <p>${course.description}</p>
                        <div class="module-stats">
                            <span><i class="fas fa-clock"></i> ${course.duration}</span>
                            <span><i class="fas fa-check-circle"></i> ${course.lessons}</span>
                            <span><i class="fas fa-star"></i> ${course.level}</span>
                        </div>
                        <div class="module-progress">
                            <div class="progress-bar" style="width: ${course.progress}%"></div>
                        </div>
                        <div style="margin-top: 20px;">
                            <button class="btn start-course" data-id="${index}">بدء التعلم</button>
                        </div>
                    </div>
                `;
                container.appendChild(module);
            });
        }

        // تحميل أدوات الأمان
        function loadTools() {
            const container = document.querySelector('.tools-grid');
            container.innerHTML = '';
            
            tools.forEach((tool, index) => {
                const toolCard = document.createElement('div');
                toolCard.className = `tool-card ${index < 3 ? 'visible' : ''}`;
                toolCard.innerHTML = `
                    <div class="tool-icon">
                        <i class="${tool.icon}"></i>
                    </div>
                    <h3>${tool.title}</h3>
                    <p>${tool.description}</p>
                    <div style="margin-top: 20px;">
                        <button class="btn use-tool" data-id="${index}">استخدم الأداة</button>
                    </div>
                `;
                container.appendChild(toolCard);
            });
        }

        // تحميل الاختبار
        function loadQuiz() {
            if (currentQuestion >= quizQuestions.length) {
                currentQuestion = 0;
            }
            
            const question = quizQuestions[currentQuestion];
            document.getElementById('questionText').textContent = question.question;
            
            const optionsContainer = document.getElementById('quizOptions');
            optionsContainer.innerHTML = '';
            
            question.options.forEach((option, index) => {
                const optionElement = document.createElement('div');
                optionElement.className = 'quiz-option';
                if (selectedOption === index) {
                    optionElement.classList.add('selected');
                }
                optionElement.textContent = option;
                optionElement.dataset.index = index;
                optionElement.addEventListener('click', function() {
                    document.querySelectorAll('.quiz-option').forEach(opt => {
                        opt.classList.remove('selected');
                    });
                    this.classList.add('selected');
                    selectedOption = parseInt(this.dataset.index);
                });
                optionsContainer.appendChild(optionElement);
            });
        }

        // إعداد الأحداث
        function setupEvents() {
            // تحميل المزيد من المصطلحات
            document.getElementById('loadMoreTerms').addEventListener('click', function() {
                loadedTerms += 3;
                if (loadedTerms > terms.length) {
                    loadedTerms = terms.length;
                    this.disabled = true;
                    this.textContent = 'تم تحميل جميع المصطلحات';
                }
                loadTerms();
            });
            
            // بدء دورة تدريبية
            document.querySelectorAll('.start-course').forEach(btn => {
                btn.addEventListener('click', function() {
                    const courseId = this.dataset.id;
                    const course = courses[courseId];
                    alert(`بدأت دورة "${course.title}" بنجاح!`);
                });
            });
            
            // استخدام أداة
            document.querySelectorAll('.use-tool').forEach(btn => {
                btn.addEventListener('click', function() {
                    const toolId = this.dataset.id;
                    const tool = tools[toolId];
                    alert(`فتحت أداة "${tool.title}" بنجاح!`);
                });
            });
            
            // التنقل بين أسئلة الاختبار
            document.getElementById('prevQuestion').addEventListener('click', function() {
                if (currentQuestion > 0) {
                    currentQuestion--;
                    selectedOption = null;
                    loadQuiz();
                }
            });
            
            document.getElementById('nextQuestion').addEventListener('click', function() {
                if (selectedOption === null) {
                    alert('الرجاء اختيار إجابة قبل المتابعة');
                    return;
                }
                
                if (selectedOption === quizQuestions[currentQuestion].correctAnswer) {
                    alert('إجابة صحيحة! ✓');
                } else {
                    alert('إجابة خاطئة! ✗');
                }
                
                if (currentQuestion < quizQuestions.length - 1) {
                    currentQuestion++;
                    selectedOption = null;
                    loadQuiz();
                } else {
                    alert('لقد أكملت الاختبار بنجاح! شكراً لمشاركتك.');
                    document.getElementById('startQuiz').click();
                }
            });
            
            // بدء اختبار جديد
            document.getElementById('startQuiz').addEventListener('click', function() {
                currentQuestion = 0;
                selectedOption = null;
                loadQuiz();
                alert('بدأ اختبار جديد. حظاً موفقاً!');
            });
        }

        // إعداد تأثيرات الظهور
        function setupAnimations() {
            // عند التمرير، عرض العناصر
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, { threshold: 0.1 });
            
            // مراقبة جميع العناصر التي لها تأثير الظهور
            document.querySelectorAll('.term-card, .module, .tool-card').forEach(card => {
                observer.observe(card);
            });
        }
    </script>
</body>
</html>
