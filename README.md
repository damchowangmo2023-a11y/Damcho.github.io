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
            background: #ffe6ee;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: #1a0008 ;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            color:#1a0008 ;
            text-decoration: none;
            font-weight: 500;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        /* GENERAL SECTIONS */
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

        /* IMAGE STYLING */
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

        /* BIODATA TABLE */
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

        /* SKILLS / HOBBIES */
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

        /* FOOTER */
        footer {
            margin-top: 40px;
            background: #3a6cf4;
            text-align: center;
            color: white;
            padding: 20px;
        }

        /* RESPONSIVE */
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
        <h1>Damchoe Wangmo</h1>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#biodata">Biodata</a></li>
            <li><a href="#skills">Hobbies</a></li>
            <li><a href="#school life">School Life </a></li>
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
            <img src="https://drive.google.com/file/d/1IsFcqt-YqFKNoZ6lidrTKJG7C1wDwRsB/view">
            <img src="https://drive.google.com/drive/folders/1sEVN726VqSnnbzJXxLczqa3wpOHFJ7MF">
            <img src="https://photos.google.com/share/AF1QipNjzjyuHPl01DOCHypTPWUWmz8h2oN55qzMFlgb8msvdLrcbzz7m8DVs_CkgTHlfQ/photo/AF1QipNesAtLJmJ_kJ-1KUFNszdUWKR40RsTXicEEbQQ?key=R0Y4TjRvMkNGbkN1MmhuaEthRE1UTVdELXJUWElB">
        </div>
    </section>

    <!-- School Life-->
    <section id="school life">
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
            <img src="https://images.unsplash.com/photo-1503457574464-0ec2a0396a6c" alt="Trip">
            <img src="https://images.unsplash.com/photo-1525648199074-cee30ba79a56" alt="Dances">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" 
alt="As a grade">
            <img src="https://images.unsplash.com/photo-1504198458649-3128b932f49b" alt="Imagination">
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
    <section id="Hobbies">
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
            <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="school">
            <img src="https://images.unsplash.com/photo-1485988412941-77a35537dae4" alt="hobbies">
            <img src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2" alt="Travel">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" alt="dancing">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" 

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

