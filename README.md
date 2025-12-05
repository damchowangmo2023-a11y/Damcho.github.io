<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Personal Website</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background: pink;
            color: #333;
        }

        /* NAVBAR */
        nav {
            background: rgba(255, 230, 238, 0.55);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            padding: 18px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: #4a0033;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 1.5px solid rgba(255, 192, 203, 0.35);
            box-shadow: 0 4px 18px rgba(0, 0, 0, 0.1);
        }

        nav h1 {
            margin: 0;
            font-size: 26px;
            font-weight: 700;
            letter-spacing: 1px;
            color: #4a0033;
            transition: 0.3s ease-in-out;
            cursor: pointer;
        }

        nav h1:hover {
            color: #ff5fa2;
            transform: scale(1.05);
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
            margin: 0;
            padding: 0;
        }

        nav ul li a {
            color: #4a0033;
            text-decoration: none;
            font-weight: 500;
            padding: 8px 14px;
            font-size: 16px;
            border-radius: 8px;
            transition: 0.3s ease;
        }

        nav ul li a:hover {
            background: #ffd3e6;
            color: #8a004f;
            box-shadow: 0 4px 10px rgba(255, 182, 203, 0.5);
            transform: translateY(-2px);
        }

        nav ul li a.active {
            background: #ff99c8;
            color: white;
            box-shadow: 0 3px 8px rgba(255, 153, 200, 0.6);
        }

        /* GENERAL SECTION DESIGN */
        section {
            max-width: 1000px;
            margin: 40px auto;
            background: white;
            padding: 40px 30px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }

        h2 {
            color: #3a6cf4;
            font-size: 32px;
            margin-bottom: 15px;
        }

        p {
            line-height: 1.8;
            margin-bottom: 15px;
            font-size: 16px;
        }

        .image-container {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .image-container img {
            width: 300px;
            border-radius: 10px;
            box-shadow: 0 0 12px rgba(0,0,0,0.15);
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table th, table td {
            text-align: left;
            padding: 12px 10px;
            border-bottom: 1px solid #ddd;
        }

        table th {
            background-color: #3a6cf4;
            color: white;
            width: 30%;
        }

        table td {
            background: #f9f9f9;
        }

        .list-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .list-item {
            background: #e6edff;
            color: #333;
            padding: 15px 20px;
            border-radius: 10px;
            font-weight: 500;
        }

        footer {
            margin-top: 40px;
            background: #3a6cf4;
            text-align: center;
            color: white;
            padding: 20px;
        }

        @media(max-width: 768px){
            .image-container img {
                width: 100%;
            }
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>

    <!-- NAVIGATION BAR -->
    <nav>
      <ul>
        <li><a href="#home" class="active">Home</a></li>
        <li><a href="#biodata">Biodata</a></li>
        <li><a href="#memories">Memories</a></li>
        <li><a href="#hobbies">Hobbies</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

  

    <!-- Home-->
    <section id="home">
        <h2>Who I Am</h2>
        <p>
            Hello everyone! My name is Damchoe Wangmo, and I am currently a Grade 9 student at The Royal Academy. Before joining this school, I studied at Thangrong Primary School in Mongar Dzongkhag, where I built many wonderful memories and learned important values that still guide me today.
                    
       </p>
        <p>
            I’m someone who enjoys staying active and trying new things. I love playing sports such as basketball, football, and volleyball in fact, I enjoy almost all kinds of sports because they help me stay healthy, energetic, and connected with my friends. Sports teach me teamwork, discipline, and confidence, which I try to carry into my daily life.
        </p>
        <p>
            Besides sports, I also have a deep passion for dancing and sketching. These two hobbies are very close to my heart because they allow me to express myself freely. Whenever I feel stressed, sad, or unmotivated, dancing and drawing help lift my mood and remind me to stay positive. They give me a sense of peace, creativity, and joy, and they always inspire me to keep going, no matter the challenge.

        </p>
         <p>
            Overall, I am someone who loves to learn, explore new activities, and grow as a person. I believe that staying positive, being active, and expressing myself creatively helps me become a better version of myself every day.

        </p>

      <div class="image-container">
            <iframe src="https://drive.google.com/file/d/14WE5kJGr6YUZ6zEBupK9pBFLhDSwMAcH/preview" width="640" height="480" allow="autoplay"></iframe>
            <iframe src="https://drive.google.com/file/d/1_1E0_jvbpM8Z8SAwTkv9dUBA6G7MXcsx/preview" width="640" height="480" allow="autoplay"></iframe>
        </div>
    </section>

    <!-- School Life-->
    <section id="memories">
        <h2> Memories</h2>
        <p>
            I have created so many unforgettable memories at my new school. When I first arrived, everything felt strange and new, and I used to cry almost every day. But my friends were always there to comfort me. They made sure I never felt alone we would sing, dance, and talk for hours in our rooms. And of course, we would gossip and laugh about the funniest little things. Their support helped me adjust and made the school feel like a second home.
        </p>
        <p>
           Our batch of 2028 has already been on several amazing trips together. One of the most memorable ones was our visit to Tiger’s Nest (Taktsang). It was our third trip, and the experience of hiking together, helping each other, and reaching the top felt incredibly special. Before that, our first trip was to Sangchokhor and our second to Dhopji Dzong. Each trip brought us closer and filled our hearts with fun, laughter, and memories that we will cherish forever.
        </p>
         <p>
           We also created countless funny and interesting moments during school events. Whenever we had to prepare dance performances, the boys and girls would always argue over the steps it was chaotic but in the funniest way. Even simple moments like sharing snacks, teasing each other, or sitting together during breaks made our days brighter. We were friendly, supportive, and always there for one another.

        </p>
        <p>
           These memories,big and small, are truly beautiful to me. They remind me of how far I’ve come, the friendships I’ve built, and the joy I’ve found in this new chapter of my life.

        </p>

        <div class="image-container">
            <iframe src="https://drive.google.com/file/d/1VirceMJ90cCAu240LXaP9qtua2YzbRkG/preview" width="640" height="480" allow="autoplay"></iframe>" 
           "<iframe src="https://drive.google.com/file/d/1vbu-uPJutgt6P-oISqrfTbgQu4g7CVJr/preview" width="640" height="480" allow="autoplay"></iframe>" 
            <iframe src="https://drive.google.com/file/d/1bEP_3UUhZublayVlCCd-KQti8Kc48IRB/preview" width="640" height="480" allow="autoplay"></iframe>
            <iframe src="https://drive.google.com/file/d/19g0UYnyiW2k0G2hseaxicaIVISO0dWvm/preview" width="640" height="480" allow="autoplay"></iframe>
        </div>
    </section>

   
    <!-- BIODATA -->
    <section id="biodata">
        <h2>Biodata</h2>
        <table>
            <tr><th>Full Name</th><td>Damchoe Wangmo</td></tr>
            <tr><th>Date of Birth</th><td>March 1, 2010</td></tr>
            <tr><th>Age</th><td>15</td></tr>
            <tr><th>Nationality</th><td>Bhutan</td></tr>
            <tr><th>Education</th><td>The Royal Academy</td></tr>
            <tr><th>Languages</th><td>English, Dzongkha, Hindi, French</td></tr>
            <tr><th>Hobbies</th><td>Reading, dancing,listening to music, Traveling, Photography</td></tr>
            <tr><th>Email</th><td>damcho.wangmo2023@academy.bt</td></tr>
            <tr><th>Phone</th><td>+975 77265130</td></tr>
        </table>
    </section>

    <!--  HOBBIES -->
    <section id="hobbies">
        <h2>Hobbies</h2>
        <p>Here are some of my core  hobbies that define my personal  life:</p>
        <div class="list-container">
            <div class="list-item">Dancing </div>
            <div class="list-item">sports</div>
            <div class="list-item">Photography</div>
            <div class="list-item">Traveling</div>
            <div class="list-item">Reading</div>
        </div>

    </section>

    <!-- GALLERY -->
    <section id="gallery">
        <h2>Gallery</h2>
        <div class="image-container">
            <img src="https://lh3.googleusercontent.com/pw/AP1GczM6-R9xSUvc9YKWrA39BaEDeBKvP4puteNw3lVOEtdwG78BLcYocVMqSD9-0XsQ4psbv_5t1loBYBmq7XVJCgtSABMt5cjItvOCTQr8b9SBzOxq9uJYATkQcX7iFN3KRy4h7LJRDTvD8IoU8O9UCpL4hw=w1420-h1894-s-no-gm?authuser=0" alt="school">
            <img src="https://lh3.googleusercontent.com/pw/AP1GczNjwFUkITS1DTWiwzLSxDhIqr_dO3jxFSSGAj6VoTJJp3-R5__nN4LqIQQhqO524sYGp6vn5PDkeOaeLXtwO9r5w1cwauWktHObcaa1vRQL30dEHZnJ_ETdWCXbXnTh17zNw5O-fUW5m1tC-q2qIwQXWg=w1420-h1894-s-no-gm?authuser=0" alt="hobbies">
            <img src="https://chat.google.com/u/0/api/get_attachment_url?url_type=FIFE_URL&content_type=image%2Fheic&attachment_token=AOo0EEVkCmNJTBZGJgDL2JwnFcga7gWelz4xIJyP89182JRzlpvFqik0OBODxwTOVcx%2FUX7%2BqAc2wpcZLBMyMTx2GSWJRVN9Mo1IDQKNgNrRFnN7k%2B2ctjB5UiGm9rmolBYI8%2BKpR8Dkz3XP%2F%2FTdwi1OZ5rFPjU9v0Kal2ruVdrz2F%2BTgpkUVQvZ07Kt3m50WwI54TJ1gh7YNBybovWJZZehcb3LRDtkuHSKNy4oXjEXe%2BddmuNqj8jfmYmV5JQAf30IWbYlO%2BQUxCw4fAuTdtApqwqfxxV%2BvNwEotUoVYG9gAfSPSQmJuYRo2QIomM%2F9t2eOFhDtP%2FmagJGnsBIZzO3USHhWL8g1xHwo6K7fzoPW0koVXo4%2FK2fQ1vMCQ6QYYqGenhR6JMTr2y5Sn6rWSzp%2F%2F0ZHAyDk5PYvWdz2mPeyEr%2Fo%2BgCz4J4YKfyog2lijN8Pmeal37HPh%2B95tb080DUunvas3ZG%2Bn4qsIu4ab4fZOYpuUq6uqnbnwZcYmmj93f7kda4pUR8cFOfqBT%2F55DXz7LJHPkUadum50V04H96wxwOam69XYACH1W5R1%2Bt4xPwLPbDzPhP7IiXBWuGj7gtRk1a7Q%3D%3D&allow_caching=true&sz=w512" alt="Travel">
            <img src="https://chat.google.com/u/0/api/get_attachment_url?url_type=FIFE_URL&content_type=image%2Fheic&attachment_token=AOo0EEVloBrg%2BFsWQx9y3AHzAAVUm7mRlo6zxomPgK3hTBoyfcGcQs5EIfnuZaZHEOome24mfdPq5PjISUG%2FVbL0x4B4Jc6tNKwYdx0tlcOT8VeJxvGQHzzcXxFlFEVL7aqkmG0BPoTcCSNO3yiIkFDRZhwJQ7itdThNV3AJw1cNnaGt767O85OOtmDa9ddhwyVG6jx%2FEkFni%2B3AtSbrDgUfJmNCjMP%2B6MJL48ZvXyLoQF36MLQnY%2F7aVZmst%2Fn%2FiQqSTuRPrM%2B3s1HkF1SXY2cudGFBnnMvifEbu2%2BM4%2FequGJEefHMdz5ZTrUUgMR3W2hM9BIOYkT0N7laFchEa1BYfSGMdJUQjE3jABWZndQ54aaA0q15Y%2FpDMdwi5sPG5j6U8ifNb3vA4yeZ5%2BCfV6%2BokxFZz9AT%2FdHbFTCW%2B9d5q24%2FUyF5NX0F3n6NunPrfBDPy2mFdVQFG0vHkYsVCTElBnr%2BIc28YcDywIhuaSOlMwyOv4LWtlF4TdQIJptw6xUXqXds%2BxYEXcRn1NzhnBqKljqGopRnfI9Dj59Jz%2FQtY9KRmzs1%2F67OrPIU%2FIwD5q7CrQ1UF2WeuBHL%2Bfi8rUOL6BvuiA%3D%3D&allow_caching=true&sz=w512" alt="dancing">


        </div>
    </section>

 
    <!-- CONTACT -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you want to get in touch, feel free to reach out via email or phone:</p>
        <ul>
            <li>Email: damcho.wangmo2023@academy.bt</li>

        </ul>
        <p>I would love to collaborate, share ideas, or simply connect!</p>
    </section>

    <!-- FOOTER -->
    <footer>
        © 2025 damchoe wangmo — All Rights Reserved
    </footer>

</body>
</html>

