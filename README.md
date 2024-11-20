# portfolio_website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professor Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">


</head>

<body>

    <!-- nav bar -->
    <nav>
        <ul class="sidebar">
            <li onclick="hidesidebar()"><a href="#"><svg xmlns="http://www.w3.org/2000/svg" height="24px"
                        viewBox="0 -960 960 960" width="24px" fill="#e8eaed">
                        <path
                            d="m256-200-56-56 224-224-224-224 56-56 224 224 224-224 56 56-224 224 224 224-56 56-224-224-224 224Z" />
                    </svg></a></li>
            <li><a href="#">Breif Profile</a></li>
            <li><a href="#">Experience</a></li>
            <li><a href="awards.html">Award & Membership</a></li>
            <li><a href="#">Publications</a></li>
            <li><a href="#">Workshp</a></li>
            <li><a href="#">Administrative </a></li>
            <li><a href="research.html">Research </a></li>
            <li><a href="#">Guest Lecture</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
        <ul>
            <li class="hideOnMoblie"><a href="#">home</a></li>
            <li><a href="#">Breif Profile</a></li>
            <li><a href="#">Experience</a></li>
            <li><a href="awards.html">Award & Membership</a></li>
            <li><a href="#">Publications</a></li>
            <li><a href="#">Workshp</a></li>
            <li><a href="#">Administrative</a></li>
            <li><a href="research.html">Research</a></li>
            <li><a href="#">Guest Lecture</a></li>
            <li><a href="#">Contact</a></li>
            <li onclick="showSidebar()"><a href="#"><svg xmlns="http://www.w3.org/2000/svg" height="26"
                        viewBox="0 -960 960 960" width="26" fill="#e8eaed">
                        <path d="M120-240v-80h720v80H120Zm0-200v-80h720v80H120Zm0-200v-80h720v80H120Z" />
                    </svg></a></li>
        </ul>
    </nav>
    <script>
        function showSidebar() {
            const sidebar = document.querySelector('.sidebar')
            sidebar.style.display = 'flex'
        }
        function hidesidebar() {
            const sidebar = document.querySelector('.sidebar')
            sidebar.style.display = 'none'
        }   
    </script>
    <!-- Header Section -->
    <header id="home" class="hero-section">
        <div class="container">
            <div class="profile-image">
                <img src="professor.jpg" alt="Professor's Photo">
            </div>
            <h1 class="name">Dr. Suneetha Eluri</h1>
            <h4>Assistant Professor</h4>
            <p class="tagline">Professor | Researcher | Innovator</p>
            <p class="description">
                Welcome to my professional portfolio. Explore my academic journey, research contributions, and teaching
                experience.
            </p>
            <a href="#contact" class="btn">Contact Me</a>
            <a href="#contact" class="btn">Linked in</a>
            <a href="#contact" class="btn">Mail</a>
        </div>
    </header>


    <!-- Experiences Section -->
    <section id="experiences" class="experiences-section">
        <div class="container">
            <h2 class="section-title">Professional Experiences</h2>
            <div class="experience-list">
                <!-- Experience Item 1 -->
                <div class="experience-item">
                    <h3>Professor of Computer Science</h3>
                    <p class="experience-duration">JNTUK University (2013 - Present)</p>
                    <p class="experience-description">
                        Responsible for teaching advanced courses in Artificial Intelligence, guiding PhD research, and
                        publishing groundbreaking research in machine learning.
                    </p>
                </div>

                <!-- Experience Item 2 -->
                <div class="experience-item">
                    <h3>Assistant Professor</h3>
                    <p class="experience-duration"> Institute of Technology (2010 - 2015)</p>
                    <p class="experience-description">
                        Taught undergraduate courses in Data Structures and Algorithms, mentored students for national
                        coding competitions, and led departmental research initiatives.
                    </p>
                </div>

                <!-- Experience Item 3 -->
                <div class="experience-item">
                    <h3>Research Fellow</h3>
                    <p class="experience-duration">DEF Research Labs (2008 - 2010)</p>
                    <p class="experience-description">
                        Conducted pioneering research in cloud computing security and published multiple papers in
                        reputed international journals.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Awards and Honors Section -->
    <!-- Awards and Honors Section -->
    <section id="awards" class="awards-section">
        <div class="container">
            <h2 class="section-title">Awards, Honors, & Certifications</h2>
            <div class="awards-list">
                <!-- Award Item 1 -->
                <div class="award-item">
                    <i class="fa fa-trophy award-icon"></i>
                    <div class="award-details">
                        <h3>Best Student/College First in M.Tech (CSE)</h3>
                        <p class="award-description">
                            Awarded in 2010 at CVR College of Engineering, Hyderabad.
                        </p>
                    </div>
                </div>

                <!-- Award Item 2 -->
                <div class="award-item">
                    <i class="fa fa-trophy award-icon"></i>
                    <div class="award-details">
                        <h3>Best Student/College First in Intermediate</h3>
                        <p class="award-description">
                            Awarded in 2000 at APSWR Jr. College (Girls), Polasanipalli.
                        </p>
                    </div>
                </div>

                <!-- Award Item 3 -->
                <div class="award-item">
                    <i class="fa fa-trophy award-icon"></i>
                    <div class="award-details">
                        <h3>Best Student/School First in SSC Board Exams</h3>
                        <p class="award-description">
                            Awarded in 1998 at APSWR Girls High School, Jangareddygudem.
                        </p>
                    </div>
                </div>

                <!-- Award Item 4 -->
                <div class="award-item">
                    <i class="fa fa-medal award-icon"></i>
                    <div class="award-details">
                        <h3>Winner in Bhagavad Gita Slokas Zonal Competition</h3>
                        <p class="award-description">
                            Awarded in 1997 (IX Class) at APSWR Girls High School, Jangareddygudem.
                        </p>
                    </div>
                </div>

                <!-- more..-->
                <div class="award-item">
                    <div class="award-details">
                        <a href="awards.html">
                            <h3>More..</h3>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <div class="container">
            <div class="contact-content">
                <!-- Contact Form -->
                <div class="contact-form">
                    <h2>Contact Me</h2>
                    <form action="submit_form.php" method="POST">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>

                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>

                        <label for="subject">Subject</label>
                        <input type="text" id="subject" name="subject" required>

                        <label for="message">Message</label>
                        <textarea id="message" name="message" rows="5" required></textarea>

                        <button type="submit" class="btn">Send Message</button>

                    </form>
                </div>

                <!-- Professor's Details -->
                <div class="professor-details">
                    <h2>Professor Details</h2>
                    <p><strong>Professor</strong><br>
                        Department of Computer Science & Engineering, University College of Engineering Kakinada<br>
                        Jawaharlal Nehru Technological University Kakinada (JNTUK)
                    </p>

                    <p><strong>Email:</strong> <a
                            href="mailto:suneethaeluri83@jntucek.ac.in">suneethaeluri83@jntucek.ac.in</a></p>
                    <p><strong>Call:</strong> +91 9491141160 (Phone Office: 0884-2300866)</p>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <div class="footer-container">
            <div class="footer-right">
                <h3>Dr. Suneetha Eluri</h3>
                <p>&copy; 2024 All Rights Reserved</p>
            </div>
            <div class="footer-left">
                <ul class="footer-links">
                    <li><a href="#about">About</a></li>
                    <li><a href="#courses">Courses</a></li>
                    <li><a href="#research">Research</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>

        </div>
    </footer>



</body>



</html>
