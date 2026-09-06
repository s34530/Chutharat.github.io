```html
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>

<body>

<!-- ================= MENU ================= -->

<nav class="sidebar">

    <div class="logo">
        PORTFOLIO
    </div>

    <button onclick="showPage('home')">
        หน้าแรก
    </button>

    <button onclick="showPage('preface')">
        คำนำ
    </button>

    <button onclick="showPage('profile')">
        ประวัติส่วนตัว
    </button>

    <button onclick="showPage('activities')">
        ผลงานและกิจกรรม
    </button>

    <button onclick="showPage('contact')">
        ช่องทางการติดต่อ
    </button>

</nav>


<!-- ================= MAIN ================= -->

<main>


<!-- ================= PAGE 1 ================= -->

<section id="home" class="page active">

    <div class="home-content">

        <h1>WELCOME TO<br>MY PORTFOLIO</h1>

        <p class="subtitle">
            แฟ้มสะสมผลงาน
        </p>

        <!-- ใส่รูปของตัวเอง -->
        <img
            src="images/profile.jpg"
            alt="Profile Image"
            class="profile-image"
        >

        <div class="personal-info">

            <h2>ชื่อ-นามสกุล</h2>

            <p>ชื่อเล่น : ใส่ชื่อเล่น</p>

            <p>ชั้น : ม.6 เลขที่ : XX</p>

            <p>โรงเรียน : ใส่ชื่อโรงเรียน</p>

        </div>

    </div>

</section>


<!-- ================= PAGE 2 ================= -->

<section id="preface" class="page">

    <h1 class="page-title">
        คำนำ
    </h1>

    <div class="content-box">

        <h2>แฟ้มสะสมผลงาน (Portfolio)</h2>

        <p>
            แฟ้มสะสมผลงาน (Portfolio) เล่มนี้จัดทำขึ้นเพื่อรวบรวม
            ประวัติส่วนตัว ผลงาน กิจกรรม ประสบการณ์ และความสามารถ
            ที่ข้าพเจ้าได้เรียนรู้และพัฒนาตลอดระยะเวลาที่ผ่านมา
        </p>

        <p>
            ภายในแฟ้มสะสมผลงานเล่มนี้ประกอบด้วยข้อมูลเกี่ยวกับ
            ประวัติส่วนตัว ผลงานที่ภาคภูมิใจ กิจกรรมต่าง ๆ
            รวมถึงเกียรติบัตรและประสบการณ์ที่ได้รับ
        </p>

        <p>
            ข้าพเจ้าหวังเป็นอย่างยิ่งว่าแฟ้มสะสมผลงานเล่มนี้
            จะช่วยแสดงให้เห็นถึงความตั้งใจ ความสามารถ
            และพัฒนาการของข้าพเจ้าได้เป็นอย่างดี
        </p>

    </div>

</section>


<!-- ================= PAGE 3 ================= -->

<section id="profile" class="page">

    <h1 class="page-title">
        ประวัติส่วนตัว
    </h1>

    <div class="content-box">

        <h2>ประวัติส่วนตัว</h2>

        <div class="profile-grid">

            <div>
                <p><strong>ชื่อ-นามสกุล :</strong> ใส่ชื่อของคุณ</p>

                <p><strong>ชื่อเล่น :</strong> ใส่ชื่อเล่น</p>

                <p><strong>วันเกิด :</strong> XX/XX/XXXX</p>

                <p><strong>อายุ :</strong> XX ปี</p>
            </div>

            <div>
                <p><strong>โรงเรียน :</strong> ใส่ชื่อโรงเรียน</p>

                <p><strong>ระดับชั้น :</strong> ม.6</p>

                <p><strong>แผนการเรียน :</strong> ใส่แผนการเรียน</p>

                <p><strong>งานอดิเรก :</strong> วาดรูป ฟังเพลง อ่านหนังสือ</p>
            </div>

        </div>

    </div>


    <div class="content-box">

        <h2>ความสนใจและเป้าหมาย</h2>

        <p>
            ข้าพเจ้ามีความสนใจในด้านวิทยาศาสตร์ เทคโนโลยี
            การวาดภาพ และการเรียนรู้สิ่งใหม่ ๆ
            โดยมีเป้าหมายที่จะพัฒนาตนเองอย่างต่อเนื่อง
            และนำความรู้ที่ได้รับไปต่อยอดในอนาคต
        </p>

    </div>

</section>


<!-- ================= PAGE 4 ================= -->

<section id="activities" class="page">

    <h1 class="page-title">
        ผลงานและกิจกรรม
    </h1>


    <!-- ผลงานที่ 1 -->

    <div class="activity-card">

        <img
            src="images/certificate1.jpg"
            alt="Certificate 1"
        >

        <div>

            <h2>
                ชื่อผลงาน / เกียรติบัตรที่ 1
            </h2>

            <p>
                ได้เข้าร่วมกิจกรรม....................................
                ซึ่งจัดขึ้นเพื่อ........................................
            </p>

            <p>
                จากกิจกรรมนี้ข้าพเจ้าได้รับประสบการณ์
                และได้พัฒนาทักษะด้าน................................
            </p>

        </div>

    </div>


    <!-- ผลงานที่ 2 -->

    <div class="activity-card">

        <img
            src="images/certificate2.jpg"
            alt="Certificate 2"
        >

        <div>

            <h2>
                ชื่อผลงาน / เกียรติบัตรที่ 2
            </h2>

            <p>
                ได้เข้าร่วมกิจกรรม....................................
                เมื่อวันที่.............................................
            </p>

            <p>
                สิ่งที่ได้รับจากกิจกรรมนี้คือ...........................
            </p>

        </div>

    </div>


    <!-- ผลงานที่ 3 -->

    <div class="activity-card">

        <img
            src="images/certificate3.jpg"
            alt="Certificate 3"
        >

        <div>

            <h2>
                ชื่อผลงาน / เกียรติบัตรที่ 3
            </h2>

            <p>
                รายละเอียดเกี่ยวกับผลงานหรือกิจกรรม
                สามารถเขียนเพิ่มเติมตรงนี้ได้เลย
            </p>

            <p>
                ประสบการณ์หรือทักษะที่ได้รับจากกิจกรรมนี้
            </p>

        </div>

    </div>

</section>


<!-- ================= PAGE 5 ================= -->

<section id="contact" class="page">

    <h1 class="page-title">
        ช่องทางการติดต่อ
    </h1>

    <div class="contact-box">

        <div class="contact-item">

            <span>✉️</span>

            <div>
                <h2>Gmail</h2>
                <p>yourname@gmail.com</p>
            </div>

        </div>


        <div class="contact-item">

            <span>📱</span>

            <div>
                <h2>Tel</h2>
                <p>08X-XXX-XXXX</p>
            </div>

        </div>


        <div class="contact-item">

            <span>📷</span>

            <div>
                <h2>Instagram</h2>
                <p>@yourusername</p>
            </div>

        </div>

    </div>

</section>

</main>


<script src="script.js"></script>

</body>
</html>
```
