<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ร้านอาหารของเรา</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header>
        <h1>ร้านอาหารของเรา</h1>
        <nav>
            <a href="#home">หน้าแรก</a>
            <a href="#menu">เมนู</a>
            <a href="#contact">ติดต่อเรา</a>
        </nav>
    </header>

    <!-- หน้าแรก -->
    <section id="home">
        <h2>ยินดีต้อนรับสู่ร้านอาหารของเรา</h2>
        <p>สัมผัสรสชาติอาหารที่อร่อยที่สุดที่คุณไม่เคยสัมผัสมาก่อน</p>
        <img src="your-image.jpg" alt="ภาพร้านอาหาร">
    </section>

    <!-- เมนู -->
    <section id="menu">
        <h2>เมนูของเรา</h2>
        <div class="menu-item">
            <h3>ผัดไทยกุ้งสด</h3>
            <p>ราคา: 150 บาท</p>
        </div>
        <div class="menu-item">
            <h3>ต้มยำกุ้ง</h3>
            <p>ราคา: 180 บาท</p>
        </div>
        <div class="menu-item">
            <h3>แกงเขียวหวานไก่</h3>
            <p>ราคา: 130 บาท</p>
        </div>
    </section>

    <!-- ติดต่อเรา -->
    <section id="contact">
        <h2>ติดต่อเรา</h2>
        <form id="contactForm">
            <label for="name">ชื่อ:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">อีเมล:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">ข้อความ:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">ส่งข้อความ</button>
        </form>
    </section>

    <script src="script.js"></script>
</body>
</html>
