<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Personal Website</title>

    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: #f2f5f9;
            color: #333;
        }

        /* NAVBAR */
        nav {
            background: #3a6cf4;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: white;
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
            color: white;
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
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }

        h2 {
            color: #3a6cf4;
            font-size: 28px;
        }

        p {
            line-height: 1.8;
            margin-bottom: 15px;
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
            <li><a href="#values">Values</a></li>
        </ul>
    </nav>

    <!-- ABOUT ME -->
    <section id="about">
        <h2>Who I Am</h2>
        <p>
            Welcome to my personal page! I am someone who believes in learning endlessly, growing 
            intentionally, and living with purpose. My journey has been shaped by curiosity, creativity, 
            and the desire to create meaningful impact in everything I do.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e" alt="Portrait">
            <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9" alt="Lifestyle">
        </div>
    </section>

    <!-- CHILDHOOD -->
    <section id="childhood">
        <h2>My Childhood Story</h2>
        <p>
            I grew up with a mind full of imagination—always asking “why,” “how,” and “what if.”  
            Whether it was taking apart toys to see how they worked or creating little inventions out of 
            paper, tape, and sheer determination, my childhood was defined by exploration.
        </p>
        <p>
            I loved stories, colors, notebooks, and anything that let me create my own world. My early years shaped the core of who I am today:  
            someone who builds, imagines, and expresses.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1503457574464-0ec2a0396a6c" alt="Childhood Memories">
            <img src="https://images.unsplash.com/photo-1525648199074-cee30ba79a56" alt="Child Playing">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Childhood Creativity">
        </div>
    </section>

    <!-- CAREER -->
    <section id="career">
        <h2>Professional & Career Focus</h2>
        <p>
            Today, my work revolves around creativity, problem-solving, and helping others access 
            knowledge. I focus on building meaningful ideas, projects, and solutions that make life 
            easier, smarter, and more inspired.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1484417894907-623942c8ee29" alt="Work Desk">
            <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c" alt="Career Work">
        </div>
    </section>

    <!-- BIODATA -->
    <section id="biodata">
        <h2>My Biodata</h2>
        <table>
            <tr>
                <th>Full Name</th>
                <td>Your Name</td>
            </tr>
            <tr>
                <th>Date of Birth</th>
                <td>January 1, 2000</td>
            </tr>
            <tr>
                <th>Age</th>
                <td>25</td>
            </tr>
            <tr>
                <th>Nationality</th>
                <td>Your Country</td>
            </tr>
            <tr>
                <th>Education</th>
                <td>Example: B.Sc. in Computer Science</td>
            </tr>
            <tr>
                <th>Languages</th>
                <td>English, Spanish, Hindi (example)</td>
            </tr>
            <tr>
                <th>Hobbies</th>
                <td>Reading, Coding, Traveling, Photography</td>
            </tr>
            <tr>
                <th>Skills</th>
                <td>Web Development, Graphic Design, Writing</td>
            </tr>
        </table>
    </section>

    <!-- VALUES -->
    <section id="values">
        <h2>Personal Identity & Values</h2>
        <p>
            At the heart of who I am are values that guide every choice I make: authenticity, empathy, 
            growth, and creativity. I believe in doing things with intention, being kind even when no one 
            is watching, and never stopping the pursuit of self-improvement.
        </p>

        <div class="image-container">
            <img src="https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05" alt="Nature Values">
        </div>
    </section>

    <footer>
        © 2025 Your Name — All Rights Reserved
    </footer>

</body>
</html>
