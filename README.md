\\HOME PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahindh Suriyakumar</title>
    <style>
        body {
            background: linear-gradient(to right, #66ccff, #3399ff);
            color: #fff;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding: 50px;
            background-color:white;
            color:black;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(255, 255, 255, 0.3);
            padding: 20px;
        }

        nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 50px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.3);
        }
    </style>
</head>
<body>

    <header>
        <h1> Hello Everyone!! Mahindh Here,Welcome to My Professional Website</h1>
        <p>This Page Contains Brief Overview of My Skills and Projects,Users are free to go through it</p>
    </header>

    <nav>
        <a href="C:\Users\mahin\about.html">About Me</a>
        <a href="C:\Users\mahin\portfolio.html">Portfolio</a>
        <a href="C:\Users\mahin\skills.html">Skills</a>
        <a href="C:\Users\mahin\testimonals.html">Testimonials</a>
        <a href="C:\Users\mahin\resume.html">Resume</a>
        <a href="C:\Users\mahin\contact.html">Contact</a>
    </nav>

</body>
</html>
\\ ABOUT ME
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me - Mahindh Suriyakumar</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(to right, #66ccff, #3399ff);
            color: #fff;
        }

        section {
            padding: 50px;
        }

        .timeline {
            position: relative;
            margin: 40px 0;
        }

        .timeline::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            width: 2px;
            height: 100%;
            background: #ccc;
            transform: translateX(-50%);
        }

        .event {
            position: relative;
            margin-bottom: 40px;
        }

        .event::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 20px;
            height: 20px;
            background: #66ccff;
            border-radius: 50%;
            transform: translate(-50%, -50%);
        }

        .event h3 {
            margin-top: 0;
        }          
        img{
             width:150px;
             border-radius:10px;
             float:left;
             margin-right:10px;
           }
    </style>
</head>
<body>
    <img src="C:\Users\mahin\OneDrive\Pictures\IMG_20210519_125517_072458.jpg"alt="mahindh">

    <header>
        <h1>About Me - Mahindh Suriyakumar</h1>
        <p>Detailed Biography, Career Journey, and More</p>
    </header>

    <section>
        <h2>Biography</h2>
         <p>
            Hello! I'm Mahindh Suriyakumar, a passionate and dedicated software engineer. I hold a B Tech from VIT University and have a strong background in coding. My journey in the professional world began with CTS, where I gained valuable skills in python and c++.
        </p>

        <p>
            Over the years, I have had the privilege of working with top-notch companies, including CTS, where I achieved a lot. This experience has equipped me with in-depth knowledge of Technology, and I thrive on challenges that push me to continually learn and grow.
        </p>

        <p>
            In addition to my professional experience, I have earned certifications in white hat, further enhancing my expertise. My commitment to staying updated with the latest trends and technologies in my field reflects my dedication to delivering high-quality results.
        </p>

        <p>
            Outside of work, I enjoy games and actively contribute to social community. I am excited about the opportunity to further improvement, and I believe that my unique blend of skills and experiences makes me a valuable asset in any professional setting.
        </p>
    </section>

    <section>
        <h2>Career Journey</h2>
        <div class="timeline">
            <div class="event">
                <h3>Year 2022 - Present</h3>
                <p>Team leader at Bosch</p>
            </div>
            <div class="event">
                <h3>Year 2020 - Year 2022</h3>
                <p>Project Manager at CTS</p>
            </div>
    </section>

    <section>
        <h2>LinkedIn Profile</h2>
        <p>Connect with me on LinkedIn: <a href="https://www.linkedin.com/in/mahindh-suriyakumar-aba12724b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">Mahindh Suriyakumar</a></p>
    </section>

</body>
</html>
\\PORTFOLIO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Mahindh Suriyakumar</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(to right, #66ccff, #3399ff);
            color: #fff;
        }

        section {
            padding: 50px;
        }

        .project {
            margin-bottom: 40px;
        }

        .project img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .project-info {
            margin-top: 20px;
        }

        .project-info h3 {
            margin-top: 0;
        }

        .project-info p {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Portfolio - Mahindh Suriyakumar</h1>
        <p>Showcasing My Top Projects</p>
    </header>

    <section class="project">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTo5_wazGEYp_pb-8YN7EtdZ9d4OVqNMFCyuw&usqp=CAU" alt="Project 1 Image">
        <div class="project-info">
            <h3>Project 1: Task Manager Web Application</h3>
            <p>Description:Develop a web-based task manager application that allows users to create, update, and delete tasks. Implement features such as task categorization, priority levels, due dates, and user authentication. The application should provide an intuitive user interface and real-time updates for task changes.</p>
            <p>Role:developer.</p>
            <p>Link: <a href="https://example.com/project1" target="_blank">View Project</a></p>
        </div>
    </section>

    <section class="project">
        <img src="C:\Users\mahin\Downloads\recipe.jpeg" alt="Project 2 Image">
        <div class="project-info">
            <h3>Project 2:Online Recipe Book Mobile App:</h3>
            <p>Description:Create a mobile application that serves as a digital recipe book. Users can browse, search, and save recipes based on various categories, cuisines, or dietary preferences. Include features such as a personalized user profile, the ability to share recipes, and a shopping list generator for ingredients needed. .</p>
            <p>Role:Designer</p>
            <p>Link: <a href="https://example.com/project2" target="_blank">View Project</a></p>
        </div>
    </section>

    <section class="project">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLLQx6PRUml8r0I6ZsEiIDFBtYlKDKNUdEbg&usqp=CAU" alt="Project 3 Image">
        <div class="project-info">
            <h3>Project 3:E-commerce Website with Recommendation Engine:</h3>
            <p>Description:Build an e-commerce website with a personalized recommendation engine. The platform should allow users to browse products, add them to the cart, and make purchases. Implement a recommendation system that suggests products based on user preferences, purchase history, and browsing behavior. Integrate secure payment gateways for transactions..</p>
            <p>Role: Project Manager</p>
            <p>Link: <a href="https://example.com/project3" target="_blank">View Project</a></p>
        </div>
    </section>

</body>
</html>
\\SKILLS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Technical Skills - Mahindh Suriyakumar</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(to right, #66ccff, #3399ff);
            color: #fff;
        }

        section {
            padding: 50px;
        }

        .skill-description {
            margin-bottom: 40px;
        }

        .skill-description h2 {
            margin-top: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Technical Skills - 	Mahindh Suriyakumaar</h1>
        <p>Exploring the Depths of My Expertise</p>
    </header>

    <section class="skill-description">
        <h2>Programming Languages: JavaScript</h2>
        <p>
            JavaScript is a versatile programming language that I leverage extensively in web development. It allows me to create dynamic and interactive user interfaces, handle asynchronous operations, and build robust, scalable applications. With expertise in frameworks like React and Node.js, I can deliver seamless, client-server applications.
        </p>
    </section>

    <section class="skill-description">
        <h2>Front-end Development: HTML, CSS, and React</h2>
        <p>
            HTML and CSS are the building blocks of web development, enabling me to structure content and apply styles. Additionally, React.js is a powerful library that I use for building efficient and modular user interfaces. Through the use of components, state management, and virtual DOM, I can create responsive and interactive front-end experiences.
        </p>
    </section>

    <section class="skill-description">
        <h2>Back-end Development: Node.js and Express</h2>
        <p>
            Node.js, coupled with the Express.js framework, forms the backbone of my back-end development. This combination allows me to create scalable and performant server-side applications. I can design RESTful APIs, handle data storage using databases like MongoDB, and implement server-side logic to support various functionalities.
        </p>
    </section>

</body>
</html>
\\TESTIMONALS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Testimonials - Mahindh Suriyakumar</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(to right, #66ccff, #3399ff);
            color: #fff;
        }

        section {
            padding: 50px;
        }

        .testimonial {
            margin-bottom: 40px;
            border-left: 4px solid #66ccff;
            padding-left: 20px;
        }

        .testimonial p {
            margin: 10px 0;
        }

        .achievement-highlight {
            font-weight: bold;
            color: #3399ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Testimonials - Mahindh Suriyakumar</h1>
        <p>What Others Say About My Work</p>
    </header>

    <section class="testimonial">
        <p>
            "Working with Mahindh Suriyakumar has been an incredible experience. Their expertise in <span class="achievement-highlight">front-end development</span> significantly improved our user interface, resulting in a <span class="achievement-highlight">20% increase in user engagement</span>. The attention to detail and commitment to quality make them a valuable asset to any project."
        </p>
    </section>

    <section class="testimonial">
        <p>
            "Mahindh Suriyakumar's <span class="achievement-highlight">problem-solving skills</span> were evident throughout the project. They successfully tackled complex challenges in our backend architecture, leading to a <span class="achievement-highlight">30% reduction in server response time</span>. Their dedication to achieving optimal performance is commendable."
        </p>
    </section>

    <section class="testimonial">
        <p>
            "I appreciate Mahindh Suriyakumar's <span class="achievement-highlight">effective project management</span>. Their ability to meet tight deadlines while maintaining <span class="achievement-highlight">bug-free code</span> is impressive. The seamless deployment of our application resulted in a <span class="achievement-highlight">95% customer satisfaction rate</span>."
        </p>
    </section>

</body>
</html>
\\RESUME
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahindh Suriyakumar - Resume</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(to right, #66ccff, #3399ff);
            color: #fff;
        }

        section {
            padding: 50px;
        }

        .resume {
            max-width: 800px;
            margin: 0 auto;
        }

        .resume a {
            display: block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #66ccff;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        .resume a:hover {
            background-color: #3399ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Mahindh Suriyakumar - Resume</h1>
        <p>Explore My Professional Journey</p>
    </header>

    <section class="resume">
        <h2>Education</h2>
        <p>Bachelor of Science in Computer Science - VIT University</p>
        <p>Graduation Year: 2019</p>

        <h2>Work Experience</h2>
        <p>Software Developer(team leader) - bosch Company</p>
        <p>Duration: april 2022 - Present</p>
        <p>project manager-CTS</p>
        <p>Duration:march 2020-feb 2022</p>
        <h2>Skills</h2>
        <ul>
            <li>Programming Languages: JavaScript, Python</li>
            <li>Front-end Development: HTML, CSS, React</li>
            <li>Back-end Development: Node.js, Express</li>
        </ul>

        <!-- Download link for PDF -->
        <a href="C:\Users\mahin\OneDrive\Documents\myresume.pdf" download>Download PDF</a>
    </section>

</body>
</html>
//CONTACT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Me - Mahindh Suriyakumar</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            text-align: center;
            padding: 50px;
            background: linear-gradient(to right, #66ccff, #3399ff);
            color: #fff;
        }

        section {
            padding: 50px;
        }

        form {
            max-width: 600px;
            margin: 0 auto;
        }

        label {
            display: block;
            margin-bottom: 10px;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            box-sizing: border-box;
        }

        button {
            background-color: #66ccff;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #3399ff;
        }

        .social-links {
            margin-top: 20px;
        }

        .social-links a {
            display: inline-block;
            margin-right: 10px;
            color: #66ccff;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Contact Me - Mahindh Suriyakumar</h1>
        <p>Feel free to get in touch!</p>
    </header>

    <section>
        <form action="#" method="post">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Your Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <section class="social-links">
        <h2>Connect with Me</h2>
        <a href="mailto:mahindhsuriyakumar2004@gmail.com" target="_blank">Email</a>
        <a href="https://www.linkedin.com/in/mahindh-suriyakumar-aba12724b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LinkedIn</a>
        <a href="https://x.com/Mahindh3?t=5qLB2nqE-5Ll-7t9jC1P7Q&s=08">Twitter</a>
    </section>

</body>
</html>
