<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เกี่ยวกับธาตุ</title>
    <link rel="stylesheet" href="style.css">
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
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSelQtpPCOpG7D6qHUDd_X1GkeGLR_pT77BNBGNzXXwYmwR8eA/viewform?fbclid=IwY2xjawIV5SNleHRuA2FlbQIxMAABHSo9XHcXccpjQaMoLqwqyO3Hl-m4FsyplBbQGJvjD8n8i5gaT0_NlGK3Nw_aem_dCG8CvTyS0tjijgvn_ePeA" class="mailbox">
        📧
    </a>

    <h1>เกมเกี่ยวกับธาตุ</h1>
    <!-- แก้ไขที่นี่เป็นเส้นทางที่ถูกต้อง -->
    <img src="https://pbs.twimg.com/media/FTMkuQoagAAdJYi.jpg:large" style="max-width: 25%; height: auto; display: block; margin: auto;">

    
    <div class="table-container">
        <a href="https://quiz.zep.us/th/play/qnMkMA?fbclid=IwZXh0bgNhZW0CMTAAAR27pyMgU_0IrWJO7xNeRBd-m878ddCSzpx8YG5cgM1z5Q-yTRiKcUPr9W0_aem_R9IrUzRvm0K_pHyEgo5K8w" class="element">
            <img src="https://quiz.zep.us/_next/image?url=https%3A%2F%2Fasset-zepetoful.zepeto.io%2FlZS2as4ZxDWZ%2F5eUfp3wK87cuncBUl0aSFc9%2FLeKMw3wK87he5f71eaaee695c40753ba1c365aefb3buncBW5b5KL7C%2F%25EC%25A2%2580%25EB%25B9%2584vs%25EC%2583%259D%25EC%25A1%25B4%25EC%259E%2590.png&w=1080&q=75">
        </a>
        <a href="https://quiz.zep.us/th/play/odbWGa?fbclid=IwZXh0bgNhZW0CMTAAAR3tfFvZRKYHI8fTrW1YFUQ9XJkfpYMKpWV-Me_2TEtxxI-4QVKssq8-jAw_aem_CSRPhrBWFEeWUixz7YC3Yw" class="element">
            <img src="https://quiz.zep.us/_next/image?url=https%3A%2F%2Fasset-zepetoful.zepeto.io%2FlZS2as4ZxDWZ%2FI3MCI3wK87cuncAUe4Z6ePj%2FIRUeB3wK87h60a0c41dabe5b42ea805b27af44384cauncB0jNnfaUC%2F%25EA%25B3%25B5%25ED%258F%25AC%2520%25ED%258F%2590%25EA%25B5%2590.png&w=1080&q=75">
        </a>
        <a href="https://quiz.zep.us/th/play/xEYm7O?fbclid=IwZXh0bgNhZW0CMTAAAR1eqXOylxWr54-CTxitVAlfiZFjzESlv_KFUHr1dr35EdIskbPR7T6DOkY_aem_3Iw7Oewr5zT_YPVtxsl9vg " class="element">
            <img src="https://quiz.zep.us/_next/image?url=https%3A%2F%2Fasset-zepetoful.zepeto.io%2FlZS2as4ZxDWZ%2FFOg173wK87duvSnnPRUQjFf%2FzcprL3wK87hbd4c14d14a5d6419cbb00bf645931926uvSnreMmQGEA%2F%25EC%258A%25A4%25EC%258B%259C_%25EC%258D%25B8%25EB%2584%25A4%25EC%259D%25BC%2520%25EB%25B3%25B5%25EC%2582%25AC.webp&w=1080&q=75">
        </a>
        <a href="https://quiz.zep.us/th/play/7R4awb?fbclid=IwZXh0bgNhZW0CMTAAAR03UgHLtp5hEN5Yr-3fsKa7c3d5KOvD3QeVfmCdKxbBcv-hjA8IvIPDRaU_aem_CESnfdPFtM6nDrT3-jjCZQ" class="element">
            <img src="https://quiz.zep.us/_next/image?url=https%3A%2F%2Fasset-zepetoful.zepeto.io%2FlZS2as4ZxDWZ%2FEkP5r3wK87duncC9f9hEzrY%2FsHJTO3wK87h288351d266eca251e281e4e93579df7auncCaBhRL6fQ%2F%25ED%2598%25B8%25EC%2588%2598%2520%25EB%2582%259A%25EC%258B%259C.png&w=1080&q=75">
        </a>
        <a href="https://quiz.zep.us/th/play/Bj9Q9k?fbclid=IwZXh0bgNhZW0CMTAAAR0EpY39bwCSwtie5cZRcNr05qGoyK_DSzTMvNCuj_eY8ysCBFu_CxOaTtA_aem_mP5xOW9fZHI4K-8pb5e2lQ" class="element">
            <img src="https://quiz.zep.us/_next/image?url=https%3A%2F%2Fasset-zepetoful.zepeto.io%2FlZS2as4ZxDWZ%2FZE7Hl3wK87curURLeonYEde%2FkAWeP3wK87h4d619a1c2a29bfe54bef9f702086f973urURONTWzCbK%2F%25EC%25B2%259C%25EC%2582%25ACvs%25EC%2595%2585%25EB%25A7%2588.webp&w=1080&q=75">
        </a>
    </div>
</body>
</html>

