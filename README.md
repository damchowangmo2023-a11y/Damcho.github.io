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
        <h1>Your Name</h1>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#childhood">Childhood</a></li>
            <li><a href="#career">Career</a></li>
            <li><a href="#biodata">Biodata</a></li>
            <li><a href="#skills">Hobbies</a></li>
            <li><a href="#achievements">Achievements</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#values">Values</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- ABOUT ME -->
    <section id="about">
        <h2>Who I Am</h2>
        <p>
            Hi! I’m someone passionate about creativity, learning, and making a meaningful impact. 
            I enjoy exploring new ideas, connecting with people, and sharing knowledge. 
        </p>
        <p>
            My journey so far has been a blend of curiosity, challenges, and continuous growth. 
            I like to approach life with intention and creativity, and I value experiences over things.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e" alt="Portrait">
            <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9" alt="Lifestyle">
            <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Thinking">
        </div>
    </section>

    <!-- CHILDHOOD -->
    <section id="childhood">
        <h2>Childhood Memories</h2>
        <p>
            My childhood was full of curiosity and exploration. I spent countless hours imagining new worlds, 
            building small inventions, and experimenting with creative projects. I loved books, colors, and 
            drawing anything that inspired me.
        </p>
        <p>
            I was surrounded by a supportive environment that encouraged learning, and my early years were 
            crucial in shaping my personality and interests. Those small moments—playful experiments, school 
            activities, and simple family moments—built the foundation for the person I am today.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1503457574464-0ec2a0396a6c" alt="Childhood Memories">
            <img src="https://images.unsplash.com/photo-1525648199074-cee30ba79a56" alt="Child Playing">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Childhood Creativity">
            <img src="https://images.unsplash.com/photo-1504198458649-3128b932f49b" alt="Imagination">
        </div>
    </section>

    <!-- CAREER -->
    <section id="career">
        <h2>Career & Professional Journey</h2>
        <p>
             My current career is being a student, and I take pride in learning, growing, and exploring new skills every day.
        As a learner, I enjoy discovering new subjects, challenging myself, and developing knowledge that will help me
        build a bright future.
       
        <p>
            I am passionate about improving myself academically as well as personally. Whether it’s working on school
        projects, participating in activities, or learning new skills, my student journey continues to shape who I am.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1484417894907-623942c8ee29" alt="Work Desk">
            <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c" alt="Career Work">
            <img src="https://images.unsplash.com/photo-1551836022-d5d88e9218df" alt="Professional Skills">
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
            <div class="list-item">Creative Writing</div>
            <div class="list-item">Photography</div>
            <div class="list-item">Traveling</div>
            <div class="list-item">Reading</div>
            <div class="list-item">Problem Solving</div>
        </div>
    </section>

    <!-- ACHIEVEMENTS -->
    <section id="achievements">
        <h2>Achievements</h2>
        <p>
            Over the years, I have worked on several projects that have helped me grow both professionally 
            and personally. Some notable achievements include:
        </p>
        <ul>
            <li>Completed a major web development project for a startup.</li>
            <li>Designed a creative portfolio showcased online.</li>
            <li>Won a school-level innovation award in childhood.</li>
            <li>Contributed to community learning projects and workshops.</li>
        </ul>
    </section>

    <!-- GALLERY -->
    <section id="gallery">
        <h2>Gallery</h2>
        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Inspiration">
            <img src="https://images.unsplash.com/photo-1485988412941-77a35537dae4" alt="Workplace">
            <img src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2" alt="Travel">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" alt="Coding">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Creativity">
        </div>
    </section>

    <!-- VALUES -->
    <section id="values">
        <h2>Personal Identity & Values</h2>
        <p>
            I strongly believe in authenticity, empathy, creativity, and constant growth. These values guide 
            every choice I make and help me maintain balance and purpose in life.
        </p>
        <p>
            Living intentionally and learning continuously are my key principles. I strive to inspire others 
            by example and create meaningful work that reflects my personal philosophy.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05" alt="Nature Values">
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
