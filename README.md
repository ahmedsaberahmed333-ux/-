# -
شركة مقاولات 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مؤسسة الرمضاء للمقاولات العامة</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #e6e6e6 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 40px;
            padding: 30px;
            background: linear-gradient(120deg, #8B4513, #A0522D);
            color: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        h1 {
            color: #fff;
            margin-bottom: 10px;
            font-size: 2.5rem;
        }
        
        .header-p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .logo {
            font-size: 50px;
            margin-bottom: 15px;
            color: #F4A460;
        }
        
        .contact-section {
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            text-align: center;
        }
        
        .phone-number {
            font-size: 32px;
            font-weight: bold;
            color: #8B4513;
            margin: 20px 0;
            direction: ltr;
            display: inline-block;
            padding: 10px 20px;
            background: #f8f9fa;
            border-radius: 8px;
            border: 2px dashed #8B4513;
        }
        
        .call-button {
            display: inline-block;
            background-color: #CD853F;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            margin-top: 15px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .call-button:hover {
            background-color: #A0522D;
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        
        .call-button i {
            margin-left: 8px;
        }
        
        .files-section {
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .section-title {
            color: #8B4513;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid #eee;
            font-size: 1.8rem;
        }
        
        .section-title i {
            margin-left: 10px;
            color: #CD853F;
        }
        
        .file-list {
            list-style-type: none;
        }
        
        .file-item {
            padding: 20px;
            margin-bottom: 20px;
            background-color: #f8f9fa;
            border-radius: 8px;
            border-left: 5px solid #CD853F;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: transform 0.3s ease;
        }
        
        .file-item:hover {
            transform: translateX(5px);
            background-color: #FAF0E6;
        }
        
        .file-info {
            flex-grow: 1;
        }
        
        .file-name {
            font-weight: bold;
            color: #8B4513;
            font-size: 1.2rem;
        }
        
        .file-desc {
            color: #7f8c8d;
            margin-top: 5px;
        }
        
        .download-button {
            background-color: #CD853F;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            transition: all 0.3s ease;
            white-space: nowrap;
            margin-left: 15px;
        }
        
        .download-button:hover {
            background-color: #8B4513;
        }
        
        .download-button i {
            margin-left: 8px;
        }
        
        .services {
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .service-item {
            background: #FAF0E6;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            border-bottom: 3px solid #CD853F;
        }
        
        .service-item i {
            font-size: 2rem;
            color: #8B4513;
            margin-bottom: 15px;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #7f8c8d;
            font-size: 16px;
            border-top: 1px solid #ddd;
        }
        
        @media (max-width: 768px) {
            .phone-number {
                font-size: 24px;
            }
            
            .file-item {
                flex-direction: column;
                align-items: flex-start;
            }
            
            .download-button {
                margin-top: 15px;
                align-self: flex-end;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <i class="fas fa-building"></i>
            </div>
            <h1>مؤسسة الرمضاء للمقاولات العامة</h1>
            <p class="header-p">البناء بمعايير الجودة والتميز</p>
        </header>
        
        <section class="contact-section">
            <h2 class="section-title"><i class="fas fa-phone"></i>اتصل بنا</h2>
            <p>يمكنك التواصل معنا عبر الرقم التالي:</p>
            <div class="phone-number">+966 55 123 8320</div>
            <br>
            <a href="tel:+966551238320" class="call-button"><i class="fas fa-phone"></i>اتصال فوري</a>
        </section>
        
        <section class="services">
            <h2 class="section-title"><i class="fas fa-hammer"></i>خدماتنا</h2>
            <div class="services-grid">
                <div class="service-item">
                    <i class="fas fa-home"></i>
                    <h3>تشييد المباني</h3>
                    <p>تشييد المباني السكنية والتجارية بجودة عالية</p>
                </div>
                <div class="service-item">
                    <i class="fas fa-tools"></i>
                    <h3>التشييد والبناء</h3>
                    <p>تنفيذ مشاريع البناء والتشييد بمختلف أحجامها</p>
                </div>
                <div class="service-item">
                    <i class="fas fa-paint-roller"></i>
                    <h3>تشطيب وتزيين</h3>
                    <p>أعمال التشطيب الداخلي والخارجي للمباني</p>
                </div>
                <div class="service-item">
                    <i class="fas fa-wrench"></i>
                    <h3>الصيانة والإصلاح</h3>
                    <p>خدمات الصيانة الشاملة للمباني والمنشآت</p>
                </div>
            </div>
        </section>
        
        <section class="files-section">
            <h2 class="section-title"><i class="fas fa-file-download"></i>ملفات العمل الخاصة بالمؤسسة</h2>
            <ul class="file-list">
                <li class="file-item">
                    <div class="file-info">
                        <div class="file-name">ملف العمل الرئيسي</div>
                        <div class="file-desc">الملف الذي يحتوي على جميع معلومات العمل الخاصة بالمؤسسة</div>
                    </div>
                    <a href="https://drive.google.com/file/d/1Qr_FXSP4Z8oLayXfEdQvYrDqfYbhzFlk/view?usp=drivesdk" class="download-button" target="_blank">
                        <i class="fas fa-download"></i>تحميل الملف
                    </a>
                </li>
                <li class="file-item">
                    <div class="file-info">
                        <div class="file-name">عروض الأسعار.pdf</div>
                        <div class="file-desc">عروض الأسعار الحالية لخدمات المقاولات</div>
                    </div>
                    <a href="#" class="download-button"><i class="fas fa-download"></i>تحميل</a>
                </li>
                <li class="file-item">
                    <div class="file-info">
                        <div class="file-name">نماذج الأعمال السابقة.pptx</div>
                        <div class="file-desc">معرض لأهم المشاريع التي تم تنفيذها</div>
                    </div>
                    <a href="#" class="download-button"><i class="fas fa-download"></i>تحميل</a>
                </li>
                <li class="file-item">
                    <div class="file-info">
                        <div class="file-name">شروط وأحكام التعاقد.docx</div>
                        <div class="file-desc">شروط وأحكام التعاقد مع المؤسسة</div>
                    </div>
                    <a href="#" class="download-button"><i class="fas fa-download"></i>تحميل</a>
                </li>
            </ul>
        </section>
        
        <footer>
            <p>© 2023 مؤسسة الرمضاء للمقاولات العامة. جميع الحقوق محفوظة.</p>
        </footer>
    </div>
</body>
</html>
