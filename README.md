# username.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhammad Khan - Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Muhammad Khan</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#publications">Publications</a></li>
                    <li class="nav-item"><a class="nav-link" href="#certificates">Certificates</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-section">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8 mx-auto text-center">
                    <h1>Muhammad Khan</h1>
                    <p class="lead">English Language & Literature Graduate | Python Developer | Researcher</p>
                    <div class="hero-buttons mt-4">
                        <a href="#contact" class="btn btn-primary me-2">Contact Me</a>
                        <a href="#projects" class="btn btn-outline-light">View Projects</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="row">
                <div class="col-lg-6">
                    <p>A dynamic English Language and Literature graduate (BS, 3.4/4.0) with expertise in literary analysis, linguistics, and Python-driven data solutions. I fuse a passion for postcolonial narratives and creative writing with advanced skills in sentiment analysis and data visualization.</p>
                    <p>My research focuses on the intersection of technology and literature, particularly in analyzing linguistic patterns in postcolonial texts using computational methods.</p>
                </div>
                <div class="col-lg-6">
                    <div class="skills-container">
                        <h3>Skills</h3>
                        <div class="skill-item">
                            <span>Literary Analysis</span>
                            <div class="progress">
                                <div class="progress-bar" role="progressbar" style="width: 95%" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Python Development</span>
                            <div class="progress">
                                <div class="progress-bar" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Data Analysis</span>
                            <div class="progress">
                                <div class="progress-bar" role="progressbar" style="width: 85%" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span>Research & Writing</span>
                            <div class="progress">
                                <div class="progress-bar" role="progressbar" style="width: 95%" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="section bg-light">
        <div class="container">
            <h2 class="section-title">Academic Background</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>BS English Language & Literature</h3>
                        <p>University of Peshawar, Pakistan</p>
                        <p>CGPA: 3.4/4.0</p>
                        <p>2020 - 2024</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <div class="container">
            <h2 class="section-title">Technical Projects</h2>
            <div class="row">
                <div class="col-md-6 mb-4">
                    <div class="project-card">
                        <h3>Multilingual Stylometric Analysis Tool</h3>
                        <p>A Python-based tool for stylistic analysis in English, Urdu & Pashto postcolonial texts with 85% accuracy in authorship attribution.</p>
                        <div class="tech-stack">Python | NLTK | spaCy | scikit-learn | Pandas | Plotly</div>
                    </div>
                </div>
                <div class="col-md-6 mb-4">
                    <div class="project-card">
                        <h3>AI-Driven Translation Tool</h3>
                        <p>An AI tool for translating texts between English, Urdu & Pashto using fine-tuned mBART with 90% sentiment preservation.</p>
                        <div class="tech-stack">Python | Hugging Face | TextBlob | Streamlit</div>
                    </div>
                </div>
                <div class="col-md-6 mb-4">
                    <div class="project-card">
                        <h3>Postcolonial Text Corpus</h3>
                        <p>Created a digital corpus of 500+ postcolonial texts with metadata for computational analysis.</p>
                        <div class="tech-stack">Python | MongoDB | BeautifulSoup | Pandas</div>
                    </div>
                </div>
                <div class="col-md-6 mb-4">
                    <div class="project-card">
                        <h3>Literary Theme Visualization Dashboard</h3>
                        <p>Interactive dashboard for visualizing thematic elements across postcolonial literature.</p>
                        <div class="tech-stack">Python | Dash | Plotly | Flask</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Publications Section -->
    <section id="publications" class="section bg-light">
        <div class="container">
            <h2 class="section-title">Publications</h2>
            <div class="publication-list">
                <div class="publication-item">
                    <h3>The Burden of Honor</h3>
                    <p>Journal of Research Review, 2024</p>
                    <p>An analysis of honor as a thematic element in postcolonial Pakistani literature.</p>
                </div>
                <div class="publication-item">
                    <h3>Hope Amidst Struggle</h3>
                    <p>Sociology & Cultural Research Review, 2025 (Forthcoming)</p>
                    <p>Examining narratives of resilience in contemporary Pashto literature.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Certificates Section -->
    <section id="certificates" class="section">
        <div class="container">
            <h2 class="section-title">Certifications</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="certificate-card">
                        <div class="certificate-icon">
                            <i class="fas fa-certificate"></i>
                        </div>
                        <h3>Teaching English</h3>
                        <p>Arizona State University</p>
                        <span class="year">2024</span>
                        <a href="#" class="btn btn-sm btn-outline-primary mt-2">View Certificate</a>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="certificate-card">
                        <div class="certificate-icon">
                            <i class="fas fa-code"></i>
                        </div>
                        <h3>Certified Python Developer</h3>
                        <p>Ford and Lord Institute, Australia</p>
                        <span class="year">2024</span>
                        <a href="#" class="btn btn-sm btn-outline-primary mt-2">View Certificate</a>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="certificate-card">
                        <div class="certificate-icon">
                            <i class="fas fa-robot"></i>
                        </div>
                        <h3>Prompt Engineering for AI</h3>
                        <p>Vanderbilt University</p>
                        <span class="year">2025</span>
                        <a href="#" class="btn btn-sm btn-outline-primary mt-2">View Certificate</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section bg-light">
        <div class="container">
            <h2 class="section-title">Contact Me</h2>
            <div class="row">
                <div class="col-lg-6 mx-auto">
                    <div class="contact-info text-center mb-4">
                        <p><i class="fas fa-envelope me-2"></i> mkhanu33@gmail.com</p>
                        <p><i class="fas fa-phone me-2"></i> +923226164371</p>
                        <p><i class="fas fa-map-marker-alt me-2"></i> Khyber Pakhtunkhwa (KPK), Pakistan</p>
                    </div>
                    <form id="contact-form">
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Your Name" required>
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Your Email" required>
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="5" placeholder="Your Message" required></textarea>
                        </div>
                        <div class="text-center">
                            <button type="submit" class="btn btn-primary">Send Message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 Muhammad Khan. All Rights Reserved.</p>
            <div class="social-links">
                <a href="#" class="social-link"><i class="fab fa-linkedin"></i></a>
                <a href="#" class="social-link"><i class="fab fa-github"></i></a>
                <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        const targetElement = document.querySelector(targetId);
        
        if (targetElement) {
            window.scrollTo({
                top: targetElement.offsetTop - 70,
                behavior: 'smooth'
            });
        }
    });
});

// Navbar scroll effect
window.addEventListener('scroll', function() {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
        navbar.classList.add('navbar-scrolled');
        navbar.classList.add('navbar-dark');
        navbar.classList.remove('navbar-light');
    } else {
        navbar.classList.remove('navbar-scrolled');
    }
});

// Form submission handling
const contactForm = document.getElementById('contact-form');
if (contactForm) {
    contactForm.addEventListener('submit', function(e) {
        e.preventDefault();
        
        // Here you would typically send the form data to a server
        // For now, we'll just show a success message
        const formElements = contactForm.elements;
        let formData = {};
        
        for (let i = 0; i < formElements.length; i++) {
            const element = formElements[i];
            if (element.type !== 'submit') {
                formData[element.name || `field_${i}`] = element.value;
            }
        }
        
        console.log('Form data:', formData);
        
        // Reset form and show success message
        contactForm.reset();
        alert('Thank you for your message! I will get back to you soon.');
    });
}

// Add active class to nav items on scroll
window.addEventListener('scroll', function() {
    const sections = document.querySelectorAll('section');
    const navLinks = document.querySelectorAll('.nav-link');
    
    let current = '';
    
    sections.forEach(section => {
        const sectionTop = section.offsetTop;
        const sectionHeight = section.clientHeight;
        
        if (window.scrollY >= (sectionTop - 100)) {
            current = section.getAttribute('id');
        }
    });
    
    navLinks.forEach(link => {
        link.classList.remove('active');
        if (link.getAttribute('href') === `#${current}`) {
            link.classList.add('active');
        }
    });
});
