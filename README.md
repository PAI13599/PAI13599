<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เกี่ยวกับธาตุ</title>
    <link rel="stylesheet" href="style.css">
    <img src="resize-1.jpg" >
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #000;
            margin: 0;
            padding: 0;
            overflow: hidden;
            position: relative;
        }

        h1 {
            margin-top: 50px;
            font-size: 2rem;
            color: white;
        }

        /* สร้างพื้นหลังที่มีดาว */
        .stars {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: transparent;
            pointer-events: none;
            z-index: -1;
        }

        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background-color: white;
            border-radius: 50%;
            animation: moveStars 50s infinite linear;
        }

        @keyframes moveStars {
            0% { transform: translate(0, 0); }
            100% { transform: translate(-100%, -100%); }
        }

        /* กล่องจดหมาย */
        .mailbox {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
            background-color: #e74c3c;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
            font-size: 30px;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
            text-decoration: none;
        }

        /* เอฟเฟกต์เมื่อ hover */
        .mailbox:hover {
            transform: scale(1.1);
        }

        /* สร้างแสงดาวที่ขยับ */
        .element {
            width: 200px;
            height: 200px;
            background-color: #3498db;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 24px;
            font-weight: bold;
            border-radius: 10px;
            text-decoration: none;
        }

        .element img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .table-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
            gap: 20px;
            padding: 0 20px;
        }

        /* Media query สำหรับหน้าจอขนาดเล็ก */
        @media (max-width: 600px) {
            .mailbox {
                width: 50px;
                height: 50px;
                font-size: 24px;
                top: 15px;
                right: 15px;
            }

            h1 {
                font-size: 1.5rem;
            }

            .element {
                width: 150px;
                height: 150px;
            }
        }
    </style>
</head>
<body>
    <div class="stars">
        <!-- สร้างดาวแบบสุ่ม -->
        <div class="star" style="top: 10%; left: 20%; animation-duration: 60s;"></div>
        <div class="star" style="top: 30%; left: 50%; animation-duration: 45s;"></div>
        <div class="star" style="top: 80%; left: 80%; animation-duration: 30s;"></div>
        <div class="star" style="top: 40%; left: 70%; animation-duration: 55s;"></div>
        <div class="star" style="top: 60%; left: 30%; animation-duration: 50s;"></div>
    </div>

    <!-- กล่องจดหมายเป็นลิงก์ -->
    <a href=" https://docs.google.com/forms/d/e/1FAIpQLSelQtpPCOpG7D6qHUDd_X1GkeGLR_pT77BNBGNzXXwYmwR8eA/viewform?fbclid=IwY2xjawIV5SNleHRuA2FlbQIxMAABHSo9XHcXccpjQaMoLqwqyO3Hl-m4FsyplBbQGJvjD8n8i5gaT0_NlGK3Nw_aem_dCG8CvTyS0tjijgvn_ePeA  " class="mailbox">
        📧
    </a>

    <body>
         <body>
            <h1>ตารางธาตุ</h1>
            <div class="table-container">
                <a href="https://quiz.zep.us/th/play/6PBxjV" class="element">
                    <img src="좀비vs생존자.webp">
                </a>
                <a href="https://quiz.zep.us/th/play/odbWGa" class="element">
                    <img src="images.jpg">
                </a>
                <a href="https://quiz.zep.us/th/play/kP6O9a" class="element">
                    <img src="미술관.webp" >
                </a>
                <a href="https://quiz.zep.us/th/play/7R4awb" class="element">
                    <img src="호수 낚시.webp">
                </a>
        </div>
</body>
</html>
