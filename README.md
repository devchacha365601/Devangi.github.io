<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Copywriting Portfolio</title>  
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f5f9;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
            text-align: center;
        }
        h1, h2 {
            color: #503a2c;
        }
        .section {
            margin-bottom: 50px;
            padding: 30px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .profile-img {
            display: block;
            margin: 0 auto 20px;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #2c3e50;
        }
        .work-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            padding: 10px;
        }
        .work-item {
            background-color: #ffffff;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .work-item:hover img:hover {
            transform: scale(1.05);
        }
        .work-item img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        .contact-list a {
            display: inline-block;
            text-decoration: none;
            margin: 10px;
            font-size: 18px;
            color: #0073b1;
            background: #ecf0f1;
            padding: 10px 20px;
            border-radius: 5px;
            transition: 0.3s;
        }
        .contact-list a:hover {
            background: #d5dbdb;
        }

        /* Headlines Section - Properly Aligned */
        .headline-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            flex-wrap: wrap;
            padding: 20px;
        }
        .headline-container a {
            text-decoration: none;
        }
        .headline-container img {
            width: 200px; /* Set image width */
            height: auto;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        .headline-container img:hover {
            transform: scale(1.05);
        }

        /* Responsive Fix */
        @media (max-width: 768px) {
            .headline-container {
                flex-wrap: wrap;
            }
            .headline-container img {
                width: 180px; /* Adjust size for smaller screens */
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <section class="section" id="about">
            <h1>About Me</h1>
            <img src="The photo.jpg" alt="Your Photo" class="profile-img">
            <p><p>🔹 I write words that sell. 
                <br>🔹 I turn ideas into revenue-generating copy.
                <br>🔹 I make people stop, read, and take action.</p>
                <p>From **high-converting sales pages** to **persuasive emails**, I help businesses increase their impact and income.</p></p>
        </section>
        
        <section class="section" id="work">
            <h2>What I Do</h2>
            <div class="work-grid">
                <div class="work-item">
                    <h2>Sales Page</h2>
                    <br>
                    <h3>Sales Page-1</h3>
                    <a href="https://docs.google.com/document/d/15mDAQc3CkalBCNlnN3YNstaHwPeq9QRHkNe3MZzalCE/edit?usp=drive_link"><img src="sale 1.png" alt="Sales Page"></a>
                    <h3>Sales Page-2</h3>
                    <a href="https://docs.google.com/document/d/1tbdTWrmHwIX26vjNJv4o-FPa-f9e5AHXbX5r4RQqfEA/edit?usp=drive_link"><img src="sale 2.png" alt="Sales Page"></a>
                    <h3>Sales Page-3</h3>
                    <a href="https://docs.google.com/document/d/1s_c6EF7Ca9XvGq4Gm8ssJ8Eck5dyUrU060HT2y7WIKU/edit?usp=drive_link"><img src="sale 3.png" alt="Sales Page"></a>
                </div>
                <div class="work-item">
                    <h2>Email Copy</h2>
                    <br>
                    <h3>Email Copy-1</h3>
                    <a href="https://docs.google.com/document/d/1PrFHf673PkxbAacq4R-zS23cFu3QAoftQbSHhY5RmfE/edit?usp=drive_link"><img src="Email 1.png" alt="Email Copy"></a>
                    <h3>Email Copy-2</h3>
                    <a href="https://docs.google.com/document/d/1JruibTzeLBvDs--eC34VHvgeXGWaJRAOwXtjDnLfnzQ/edit?usp=drive_link"><img src="Email 2.png" alt="Email Copy"></a>
                    <h3>Email Copy-3</h3>
                    <a href="https://docs.google.com/document/d/1PepxEXCopCSvS-wIE3mKOmJyYG1GktEL4EHfXuG2MXg/edit?usp=drive_link"><img src="Email 3.png" alt="Email Copy"></a>
                </div>
            </div>
        </section>
        
        <section class="section" id="headlines">
            <h2>Headlines</h2>
            <div class="headline-container">
                <a href="https://drive.google.com/file/d/1Zhn2JflO54A5isgjsw1EvsTZGvsJR7Aj/view?usp=drive_link">
                    <img src="Brown Photo Collage Instagram Post.png" alt="Shopify">
                </a>
                <a href="https://drive.google.com/file/d/1vLpBRPM_28qKiLGuMfjerrJCNNtYiuyH/view?usp=drive_link">
                    <img src="amazone.png" alt="Amazon">
                </a>
                <a href="https://drive.google.com/file/d/1NomT7N-wGFbreY-n1LaidXkq6Umts9du/view?usp=drive_link">
                    <img src="mac.png" alt="McDonald's">
                </a>
            </div>
        </section>

        <section class="section" id="contact">
            <h2>Contact Details</h2>
            <div class="contact-list">
                <a href="https://www.instagram.com/chopra_devangi?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==">Instagram</a>
                <a href="https://www.linkedin.com/in/chopra-devangi-3b1a402a8">LinkedIn</a>
                <a href="mailto:devangichopra2004@gmail.com">Gmail</a>
            </div>
        </section>
    </div>
</body>
</html>

    </div>
</body>
</html>
