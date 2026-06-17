[index.html.txt](https://github.com/user-attachments/files/29061586/index.html.txt)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دعوة زفاف: صلاح & مي</title>
    <!-- استيراد خطوط عربية أنيقة من جوجل -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amiri:ital@0;1&family=Cairo:wght@300;400;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --bg-color: #faf7f2;
            --primary-color: #2c3e2b; /* أخضر ملكي هادئ */
            --gold-color: #c5a059; /* ذهبي دافئ */
            --text-color: #4a4a4a;
        }

        body {
            font-family: 'Cairo', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .card-container {
            background: #ffffff;
            max-width: 480px;
            width: 90%;
            margin: 20px auto;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            border: 1px solid rgba(197, 160, 89, 0.2);
            padding: 40px 25px;
            text-align: center;
            box-sizing: border-box;
            position: relative;
            overflow: hidden;
        }

        /* إطار زخرفي ناعم */
        .card-container::before {
            content: '';
            position: absolute;
            top: 15px; right: 15px; bottom: 15px; left: 15px;
            border: 1px solid var(--gold-color);
            opacity: 0.3;
            border-radius: 15px;
            pointer-events: none;
        }

        .header-flower {
            font-size: 24px;
            color: var(--gold-color);
            margin-bottom: 15px;
        }

        h1 {
            font-family: 'Amiri', serif;
            color: var(--primary-color);
            font-size: 2.5rem;
            margin: 10px 0;
            font-weight: normal;
        }

        .and-sign {
            font-size: 1.8rem;
            color: var(--gold-color);
            display: block;
            margin: 5px 0;
        }

        .invitation-text {
            font-family: 'Amiri', serif;
            font-size: 1.35rem;
            line-height: 1.8;
            color: var(--text-color);
            margin: 25px 0;
            padding: 0 10px;
        }

        .details-section {
            background: rgba(197, 160, 89, 0.05);
            border-radius: 12px;
            padding: 20px;
            margin: 25px 0;
        }

        .date-title {
            color: var(--primary-color);
            font-weight: 700;
            font-size: 1.2rem;
            margin-bottom: 5px;
        }

        .venue-title {
            color: var(--gold-color);
            font-weight: 700;
            font-size: 1.1rem;
            margin-top: 15px;
            margin-bottom: 5px;
        }

        /* العداد التنازلي */
        .countdown-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 25px 0;
        }

        .countdown-box {
            background: var(--primary-color);
            color: #ffffff;
            padding: 10px;
            border-radius: 8px;
            min-width: 65px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .countdown-num {
            font-size: 1.4rem;
            font-weight: 700;
            display: block;
        }

        .countdown-label {
            font-size: 0.75rem;
            opacity: 0.8;
        }

        /* الأزرار */
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: var(--gold-color);
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: bold;
            margin: 10px 5px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            width: 85%;
            font-size: 0.95rem;
            box-shadow: 0 4px 12px rgba(197, 160, 89, 0.25);
        }

        .btn:hover {
            background-color: var(--primary-color);
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(44, 62, 43, 0.25);
        }

        /* نموذج RSVP */
        .rsvp-section {
            margin-top: 30px;
            border-top: 1px dashed rgba(197, 160, 89, 0.4);
            padding-top: 20px;
        }

        .rsvp-title {
            color: var(--primary-color);
            font-size: 1.1rem;
            margin-bottom: 15px;
            font-weight: bold;
        }

        .input-field {
            width: 85%;
            padding: 10px 15px;
            margin-bottom: 12px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-family: 'Cairo', sans-serif;
            font-size: 0.9rem;
            outline: none;
            box-sizing: border-box;
        }

        .input-field:focus {
            border-color: var(--gold-color);
        }

        .footer-note {
            font-size: 0.8rem;
            color: #888;
            margin-top: 25px;
        }
    </style>
</head>
<body>

    <div class="card-container">
        <div class="header-flower">✿ ⚜ ✿</div>
        
        <!-- أسماء العروسين -->
        <h1>صلاح</h1>
        <span class="and-sign">&</span>
        <h1>مي</h1>

        <!-- نص الدعوة المختار -->
        <div class="invitation-text">
            "في عمر واحد، وحكاية واحدة، يجمعنا الحب ويُباركنا النصيب.<br>
            يسعدنا ويشرفنا أن تشاركونا فرحتنا بقراننا وإعلان زفافنا.<br>
            حضوركم يكتمل به جوهر فرحتنا، وتُنسج به أجمل ذكريات العمر."
        </div>

        <!-- تفاصيل الموعد والمكان -->
        <div class="details-section">
            <div class="date-title">يوم الأربعاء، 29 أغسطس 2026</div>
            <div class="venue-title">قاعة القصر - سفاجا</div>
        </div>

        <!-- العداد التنازلي -->
        <div class="countdown-container">
            <div class="countdown-box">
                <span class="countdown-num" id="days">00</span>
                <span class="countdown-label">يوم</span>
            </div>
            <div class="countdown-box">
                <span class="countdown-num" id="hours">00</span>
                <span class="countdown-label">ساعة</span>
            </div>
            <div class="countdown-box">
                <span class="countdown-num" id="minutes">00</span>
                <span class="countdown-label">دقيقة</span>
            </div>
        </div>

        <!-- زر موقع القاعة التفاعلي -->
        <a href="https://maps.google.com/?q=26.7495,33.9355" target="_blank" class="btn">
            📍 عرض موقع القاعة على الخريطة
        </a>

        <!-- قسم تأكيد الحضور التفاعلي -->
        <div class="rsvp-section">
            <div class="rsvp-title">تأكيد الحضور</div>
            <form id="rsvpForm" onsubmit="submitRSVP(event)">
                <input type="text" id="guestName" class="input-field" placeholder="اسم الضيف الكريم" required>
                <input type="number" id="guestCount" class="input-field" placeholder="عدد المرافقين" min="0" required>
                <button type="submit" class="btn" style="background-color: var(--primary-color);">✔ إرسال تأكيد الحضور</button>
            </form>
        </div>

        <div class="footer-note">دامت دياركم عامرة بالأفراح والمسرات</div>
    </div>

    <!-- الجزء البرمجي الذكي للعداد وتأكيد الحضور -->
    <script>
        // تحديد تاريخ الزفاف الذكي (29 أغسطس 2026)
        const weddingDate = new Date("August 29, 2026 20:00:00").getTime();

        const timer = setInterval(function() {
            const now = new Date().getTime();
            const distance = weddingDate - now;

            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));

            document.getElementById("days").innerHTML = days < 10 ? "0" + days : days;
            document.getElementById("hours").innerHTML = hours < 10 ? "0" + hours : hours;
            document.getElementById("minutes").innerHTML = minutes < 10 ? "0" + minutes : minutes;

            if (distance < 0) {
                clearInterval(timer);
                document.querySelector(".countdown-container").innerHTML = "<h3>بدأ الحفل الميمون! 🎉</h3>";
            }
        }, 1000);

        // وظيفة تفاعلية لإرسال تأكيد الحضور عبر الواتساب مباشرة
        function submitRSVP(event) {
            event.preventDefault();
            const name = document.getElementById("guestName").value;
            const count = document.getElementById("guestCount").value;
            
            // نص الرسالة التلقائية التي ستصلك
            const message = `مرحباً، أنا أؤكد حضوري لحفل زفاف صلاح ومي.%0Aالاسم: ${name}%0Aعدد المرافقين: ${count}`;
            
            // هنا يمكنك استبدال الرقم برقم واتساب الخاص بك لتلقي الرسائل مباشرة
            window.open(`https://wa.me/?text=${message}`, '_blank');
        }
    </script>
</body>
</html>
