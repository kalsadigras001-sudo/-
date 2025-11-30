<!DOCTYPE html>
<html lang="mr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ग्रामपंचायत कळसा</title>

    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #eef2f3;
        }

        header {
            background: linear-gradient(90deg, #005f8d, #0083b0);
            padding: 25px;
            text-align: center;
            color: white;
        }

        .logo {
            width: 90px;
            height: 90px;
            background: white;
            border-radius: 50%;
            margin: auto;
            margin-bottom: 15px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 22px;
            font-weight: bold;
            color: #005f8d;
            border: 3px solid #ffffff;
        }

        nav {
            background: #004d6b;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 12px;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            background: white;
            margin: 20px;
            padding: 18px;
            border-radius: 10px;
            box-shadow: 0 2px 6px #ccc;
        }

        h2 {
            color: #005f8d;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 12px;
        }

        table, th, td {
            border: 1px solid #999;
        }

        th, td {
            padding: 10px;
        }

        /* फोटो गॅलरी */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
            gap: 10px;
        }

        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 2px 4px #aaa;
        }

        /* संपर्क फॉर्म */
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 8px;
            border-radius: 6px;
            border: 1px solid #888;
        }

        button {
            padding: 10px 20px;
            background: #005f8d;
            color: white;
            border: none;
            margin-top: 10px;
            border-radius: 6px;
            font-size: 16px;
        }

        footer {
            background: #00344a;
            color: white;
            text-align: center;
            padding: 14px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>
    <div class="logo">GP</div>
    <h1>ग्रामपंचायत कळसा</h1>
    <p>तालुका दिग्रस • जिल्हा यवतमाळ</p>
</header>

<nav>
    <a href="#about">परिचय</a>
    <a href="#members">सदस्य</a>
    <a href="#gallery">गॅलरी</a>
    <a href="#contact">संपर्क</a>
</nav>

<section id="about">
    <h2>ग्रामपंचायत कळसा – परिचय</h2>
    <p><b>लोकसंख्या:</b> 3694</p>
    <p>
        ग्रामपंचायत कळसा ही दिग्रस तालुक्यातील एक प्रगत व शैक्षणिकदृष्ट्या 
        विकसित ग्रामपंचायत आहे. गावाच्या विकासासाठी विविध शासकीय योजना 
        प्रभावीपणे राबविल्या जातात.
    </p>

    <h3>मुख्य पदाधिकारी</h3>
    <ul>
        <li><b>सरपंच:</b> हरिभाऊ दामोदर मनवर</li>
        <li><b>उपसरपंच:</b> सौ. पल्लवी सचिन तायडे</li>
        <li><b>ग्रामसेवक:</b> संतोष सोळंके</li>
    </ul>
</section>

<section id="members">
    <h2>ग्रामपंचायत सदस्य</h2>
    <table>
        <tr>
            <th>क्रमांक</th>
            <th>नाव</th>
            <th>पद</th>
        </tr>

        <tr><td>1</td><td>सौ. पल्लवी सचिन तायडे</td><td>उपसरपंच</td></tr>
        <tr><td>2</td><td>नष्ठू कानिराम जाधव</td><td>सदस्य</td></tr>
        <tr><td>3</td><td>निखिल भारत खुळे</td><td>सदस्य</td></tr>
        <tr><td>4</td><td>रवो पुदलिक वाघ</td><td>सदस्य</td></tr>
        <tr><td>5</td><td>पंचाबाई शेषराव जाधव</td><td>सदस्य</td></tr>
        <tr><td>6</td><td>प्रतिभा श्याम देशमुख</td><td>सदस्य</td></tr>
        <tr><td>7</td><td>दगाबाई श्यामराव शिंदे</td><td>सदस्य</td></tr>
        <tr><td>8</td><td>मंगला कैलास स्वर्ग</td><td>सदस्य</td></tr>
        <tr><td>9</td><td>ललिता रमेश चोरे</td><td>सदस्य</td></tr>
        <tr><td>10</td><td>अजय अशोक गिरो</td><td>सदस्य</td></tr>

    </table>
</section>

<section id="gallery">
    <h2>ग्रामपंचायत फोटो गॅलरी</h2>

    <div class="gallery">
        <img src="https://via.placeholder.com/300x200?text=Office" alt="">
        <img src="https://via.placeholder.com/300x200?text=Gram+Sabha" alt="">
        <img src="https://via.placeholder.com/300x200?text=Development+Work" alt="">
        <img src="https://via.placeholder.com/300x200?text=Village" alt="">
    </div>
</section>

<section id="contact">
    <h2>संपर्क</h2>
    <p><b>पत्ता:</b> ग्रामपंचायत कार्यालय, कळसा, ता. दिग्रस, जि. यवतमाळ</p>

    <form>
        <label>नाव:</label>
        <input type="text" placeholder="आपले नाव">

        <label>मोबाईल नंबर:</label>
        <input type="text" placeholder="मोबाईल नंबर">

        <label>मेसेज:</label>
        <textarea rows="5" placeholder="आपला संदेश"></textarea>

        <button>पाठवा</button>
    </form>
</section>

<footer>
    © 2025 ग्रामपंचायत कळसा | सर्व हक्क राखीव
</footer>

</body>
</html># -
ग्रामपंचायत कार्यालय कळसा ता दिग्रस जि यवतमाळ 
