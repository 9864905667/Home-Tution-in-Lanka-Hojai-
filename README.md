# Home-Tution-in-Lanka-Hojai-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Success Tuition - Lanka, Hojai</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f0f4f8;
        }
        header {
            background: linear-gradient(135deg, #0288d1, #4caf50);
            color: white;
            text-align: center;
            padding: 3rem 1rem;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        nav {
            background: #ffffff;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        nav a {
            margin: 0 1.5rem;
            text-decoration: none;
            color: #0288d1;
            font-weight: 600;
            font-size: 1.1rem;
        }
        nav a:hover {
            color: #01579b;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x500/4caf50/ffffff?text=Classroom+with+Assamese+Culture') no-repeat center/cover;
            padding: 4rem 1rem;
            text-align: center;
            color: white;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.8);
        }
        .hero h2 {
            font-size: 2.2rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 2rem 1rem;
        }
        .section {
            background: white;
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }
        .section h2 {
            color: #0288d1;
            margin-bottom: 1rem;
            font-size: 1.8rem;
        }
        .section p, .section ul {
            font-size: 1.1rem;
            color: #444;
        }
        .section ul {
            list-style: square;
            margin-left: 1.5rem;
        }
        .subjects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }
        .subject-card {
            background: #e3f2fd;
            padding: 1rem;
            border-radius: 8px;
            text-align: center;
            transition: transform 0.3s;
        }
        .subject-card:hover {
            transform: translateY(-5px);
        }
        .contact form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            max-width: 600px;
            margin: auto;
        }
        .contact input, .contact textarea {
            padding: 0.75rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
            width: 100%;
        }
        .contact button {
            background: #0288d1;
            color: white;
            border: none;
            padding: 0.75rem;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: background 0.3s;
        }
        .contact button:hover {
            background: #01579b;
        }
        footer {
            background: linear-gradient(135deg, #0288d1, #4caf50);
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        footer p {
            font-size: 0.9rem;
        }
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8rem;
            }
            .hero h2 {
                font-size: 1.6rem;
            }
            nav a {
                margin: 0 0.5rem;
                font-size: 0.9rem;
            }
            .section h2 {
                font-size: 1.5rem;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>Success Tuition</h1>
        <p>Expert Home Tuition for Classes 5–10 in Lanka, Hojai, Assam</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#subjects">Subjects</a>
        <a href="#fees">Fees</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h2>Empowering Young Minds with Knowledge</h2>
        <p>Personalized tuition in Social Science, English, and Maths for Classes 5–10<br>শিক্ষাৰে জীৱন গঢ়ক (Shape your life with education)</p>
    </section>
    <div class="container">
        <section class="section about" id="about">
            <h2>About Your Tutor</h2>
            <p>With a Master’s in Economics and a B.Ed., I bring expertise and dedication to teaching students in Lanka, Hojai, Assam (PIN: 782446). My goal is to make learning engaging and effective, helping students excel in their studies.</p>
        </section>
        <section class="section services" id="services">
            <h2>Our Services</h2>
            <ul>
                <li>One-on-one home tuition for Classes 5–10.</li>
                <li>Personalized lessons in Social Science, English, and Maths.</li>
                <li>Exam preparation, homework help, and concept clarity.</li>
                <li>Flexible schedules to suit your child’s needs.</li>
            </ul>
        </section>
        <section class="section subjects" id="subjects">
            <h2>Subjects Offered</h2>
            <div class="subjects-grid">
                <div class="subject-card">
                    <h3>Social Science</h3>
                    <p>Explore history, geography, and civics with engaging lessons.</p>
                </div>
                <div class="subject-card">
                    <h3>English</h3>
                    <p>Master grammar, writing, and literature with confidence.</p>
                </div>
                <div class="subject-card">
                    <h3>Maths</h3>
                    <p>Build problem-solving skills with clear, step-by-step guidance.</p>
                </div>
            </div>
        </section>
        <section class="section fees" id="fees">
            <h2>Fees</h2>
            <p>₹2,000 for 14 days of personalized home tuition.</p>
            <p>Affordable, high-quality education tailored for Classes 5–10. Contact me to discuss schedules!</p>
        </section>
        <section class="section contact" id="contact">
            <h2>Contact Me</h2>
            <p>Enroll today or ask questions using the form below!</p>
            <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
                <input type="text" name="name" placeholder="Parent/Student Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Your Phone Number" required>
                <textarea name="message" placeholder="Your Message (e.g., Class, Subject, Schedule)" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
            <p>Location: Lanka, Hojai, Assam, PIN: 782446</p>
        </section>
    </div>
    <footer>
        <p>© 2025 Success Tuition, Lanka, Hojai, Assam. All rights reserved.</p>
    </footer>
</body>
</html>
