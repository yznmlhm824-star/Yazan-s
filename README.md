<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مشروع أفق | المخطط التشغيلي الكامل</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #1e3d2c; /* أخضر غابوي عميق */
            --secondary: #b58947; /* ذهبي عتيق */
            --bg: #f9fbf9;
            --white: #ffffff;
            --text: #333333;
        }

        body { font-family: 'Cairo', sans-serif; margin: 0; background-color: var(--bg); color: var(--text); line-height: 1.8; }
        
        /* Header Section */
        header { 
            background: linear-gradient(rgba(30, 61, 44, 0.85), rgba(30, 61, 44, 0.85)), 
            url('https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?q=80&w=2000');
            height: 50vh; background-size: cover; background-position: center;
            display: flex; flex-direction: column; justify-content: center; align-items: center; 
            color: var(--white); text-align: center; border-bottom: 5px solid var(--secondary);
        }

        header h1 { font-size: 3.5rem; margin: 0; font-weight: 900; letter-spacing: 2px; }
        header p { font-size: 1.3rem; margin-top: 10px; font-weight: 300; }

        .container { max-width: 1000px; margin: -60px auto 50px; background: var(--white); border-radius: 15px; padding: 40px; box-shadow: 0 15px 35px rgba(0,0,0,0.1); }

        /* Typography */
        h2.section-title { color: var(--primary); border-bottom: 2px solid var(--secondary); display: inline-block; padding-bottom: 5px; margin-bottom: 30px; }

        /* Timeline Style */
        .day-container { margin-bottom: 50px; }
        .day-title { background: var(--primary); color: var(--white); padding: 10px 25px; border-radius: 50px; display: inline-block; margin-bottom: 20px; font-weight: 700; }
        
        .event-row { display: grid; grid-template-columns: 120px 1fr; margin-bottom: 15px; padding-bottom: 10px; border-bottom: 1px solid #eee; }
        .time { color: var(--secondary); font-weight: 900; font-size: 1.1rem; }
        .activity { font-weight: 400; }
        .highlight-event { color: var(--primary); font-weight: 700; background: #f0f4f1; padding: 2px 8px; border-radius: 4px; }

        /* Logistics & Price Boxes */
        .grid-box { display: grid; grid-template-columns: 1fr 1fr; gap: 25px; margin-top: 40px; }
        .card { background: #fdfdfd; border: 1px solid #e1e8e1; padding: 25px; border-radius: 12px; }
        .card h3 { color: var(--primary); margin-top: 0; }
        .price-value { font-size: 2.2rem; color: var(--secondary); font-weight: 900; }

        /* Images */
        .gallery { display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; margin-top: 30px; }
        .gallery img { width: 100%; height: 180px; object-fit: cover; border-radius: 10px; border: 2px solid #eee; }

        footer { background: var(--primary); color: var(--white); text-align: center; padding: 40px; margin-top: 50px; }
    </style>
</head>
<body>

    <header>
        <h1>أُفق | HORIZON</h1>
        <p>المخطط التشغيلي لرحلة الدراجات الكهربائية (E-Bikes)</p>
    </header>

    <div class="container">
        
        <h2 class="section-title">برنامج الرحلة التفصيلي (5 أيام)</h2>

        <div class="day-container">
            <div class="day-title">اليوم الأول: الناصرة - سد المزينة</div>
            <div class="event-row"><div class="time">10:00 صباحاً</div><div class="activity">التجمع في الناصرة، فحص الدراجات، وتوزيع معدات السلامة.</div></div>
            <div class="event-row"><div class="time">11:30 صباحاً</div><div class="activity">صعود قلعة الحصن (اختبار كفاءة المحرك الكهربائي).</div></div>
            <div class="event-row"><div class="time">02:00 ظهراً</div><div class="activity">غداء ريفي في مطعم إطلالة القلعة.</div></div>
            <div class="event-row"><div class="time">04:30 عصراً</div><div class="activity">التوجه نحو سد المزينة (مسار منحدرات).</div></div>
            <div class="event-row"><div class="time">06:00 مساءً</div><div class="activity"><span class="highlight-event">فعالية الصيد:</span> صيد السمك في بحيرة السد ونصب الخيام.</div></div>
            <div class="event-row"><div class="time">08:30 مساءً</div><div class="activity">عشاء "مشاوي سورية" على الحطب ورصد النجوم.</div></div>
        </div>

        <div class="day-container">
            <div class="day-title">اليوم الثاني: الحواش - تمثال السيدة مريم</div>
            <div class="event-row"><div class="time">09:00 صباحاً</div><div class="activity">إفطار قروي (زيتوزعتر ومكدوس) من إنتاج المنطقة.</div></div>
            <div class="event-row"><div class="time">11:30 صباحاً</div><div class="activity">تحدي صعود قمة جبل السايح (تمثال السيدة مريم).</div></div>
            <div class="event-row"><div class="time">02:00 ظهراً</div><div class="activity">غداء "صفيحة أرمنية" في سوق الحواش القديم.</div></div>
            <div class="event-row"><div class="time">05:00 عصراً</div><div class="activity"><span class="highlight-event">فعالية الأصالة:</span> ضيافة البيوت الحجرية (Home-stay) مع العائلات المحلية.</div></div>
            <div class="event-row"><div class="time">08:00 مساءً</div><div class="activity">عشاء منزلي مطبوخ بضيافة الأهالي وتجربة الحياة الريفية.</div></div>
        </div>

        <div class="day-container">
            <div class="day-title">اليوم الخامس: الاستشفاء والنزول الذهبي</div>
            <div class="event-row"><div class="time">10:00 صباحاً</div><div class="activity">وقت حر للاسترخاء في طبيعة مشتى الحلو.</div></div>
            <div class="event-row"><div class="time">01:00 ظهراً</div><div class="activity"><span class="highlight-event">حمام واصل:</span> جلسة استشفاء وتدليك مائي في الينابيع الكبريتية.</div></div>
            <div class="event-row"><div class="time">04:30 عصراً</div><div class="activity">انطلاق "النزول الذهبي" نحو طرطوس مع انكسار الشمس والتمتع بمشهد الغروب.</div></div>
            <div class="event-row"><div class="time">06:30 مساءً</div><div class="activity">الوصول لشاطئ طرطوس والسباحة الختامية.</div></div>
            <div class="event-row"><div class="time">08:30 مساءً</div><div class="activity">عشاء بحري ختامي وتسليم الصور والذكريات الرقمية.</div></div>
        </div>

        <div class="grid-box">
            <div class="card">
                <h3>💰 التكلفة والأسعار</h3>
                <div class="price-value">1,250,000 ل.س</div>
                <p>تشمل الرحلة: (الدراجة الكهربائية، سيارة الدعم، 3 وجبات يومياً، المبيت، والتأمين).</p>
            </div>
            <div class="card">
                <h3>⚙️ المواصفات اللوجستية</h3>
                <p>• دراجات محرك 500W Mid-drive.</p>
                <p>• سيارة دعم تقني لنقل الحقائب والخيام.</p>
                <p>• نقاط شحن يومية في محطات المبيت.</p>
            </div>
        </div>

        <div class="gallery">
            <img src="https://images.unsplash.com/photo-1544013584-5562fedecfdf?q=80&w=600" alt="قلعة الحصن">
            <img src="https://images.unsplash.com/photo-1519046904884-53103b34b206?q=80&w=600" alt="البحر">
            <img src="https://images.unsplash.com/photo-1473448912268-2022ce9509d8?q=80&w=600" alt="الغابة">
        </div>

    </div>

    <footer>
        <p>إعداد الطالب: <b>يزن ملحم</b> | إشراف الدكتور: <b>مرهف الحمود</b></p>
        <p>كلية السياحة - جامعة حمص - 2026</p>
        <p>للتواصل والاستفسار: 963993491044+</p>
    </footer>

</body>
</html>
