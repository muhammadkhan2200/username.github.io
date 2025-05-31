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
/* General Styles */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    scroll-behavior: smooth;
}

/* Navigation */
.navbar {
    padding: 1rem 0;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
}

.navbar-brand {
    font-weight: 700;
    font-size: 1.5rem;
}

.nav-link {
    font-weight: 500;
    margin: 0 5px;
    transition: color 0.3s ease;
}

/* Hero Section */
.hero-section {
    padding: 150px 0 100px;
    background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
    color: white;
    text-align: center;
}

.hero-section h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    font-weight: 700;
}

.hero-section .lead {
    font-size: 1.25rem;
    margin-bottom: 2rem;
}

.hero-buttons .btn {
    padding: 0.6rem 1.5rem;
    border-radius: 30px;
    font-weight: 500;
    transition: all 0.3s ease;
}

.btn-primary {
    background-color: #2a5298;
    border-color: #2a5298;
}

.btn-primary:hover {
    background-color: #1e3c72;
    border-color: #1e3c72;
}

/* Section Styles */
.section {
    padding: 100px 0;
}

.section-title {
    text-align: center;
    margin-bottom: 60px;
    color: #1e3c72;
    font-weight: 700;
    position: relative;
}

.section-title:after {
    content: '';
    display: block;
    width: 50px;
    height: 3px;
    background: #2a5298;
    margin: 15px auto 0;
}

/* About Section */
.skills-container {
    background: #f8f9fa;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0,0,0,0.05);
}

.skills-container h3 {
    margin-bottom: 20px;
    color: #1e3c72;
}

.skill-item {
    margin-bottom: 15px;
}

.skill-item span {
    display: block;
    margin-bottom: 5px;
    font-weight: 500;
}

.progress {
    height: 10px;
    border-radius: 5px;
}

.progress-bar {
    background-color: #2a5298;
}

/* Education Section */
.timeline {
    position: relative;
    max-width: 800px;
    margin: 0 auto;
}

.timeline-item {
    padding: 20px 30px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0,0,0,0.05);
    margin-bottom: 20px;
}

.timeline-content h3 {
    color: #1e3c72;
    margin-bottom: 10px;
}

/* Project Cards */
.project-card {
    background: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0,0,0,0.1);
    height: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 20px rgba(0,0,0,0.15);
}

.project-card h3 {
    color: #1e3c72;
    margin-bottom: 15px;
}

.tech-stack {
    margin-top: 20px;
    color: #666;
    font-size: 0.9rem;
    font-style: italic;
}

/* Publication Items */
.publication-item {
    margin-bottom: 30px;
    padding: 25px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0,0,0,0.05);
    transition: transform 0.3s ease;
}

.publication-item:hover {
    transform: translateY(-5px);
}

.publication-item h3 {
    color: #1e3c72;
    margin-bottom: 10px;
}

/* Certificate Cards */
.certificate-card {
    background: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 2px 15px rgba(0,0,0,0.05);
    text-align: center;
    height: 100%;
    transition: transform 0.3s ease;
}

.certificate-card:hover {
    transform: translateY(-5px);
}

.certificate-icon {
    font-size: 2.5rem;
    color: #2a5298;
    margin-bottom: 15px;
}

.certificate-card h3 {
    color: #1e3c72;
    font-size: 1.2rem;
    margin-bottom: 10px;
}

.year {
    display: block;
    color: #666;
    font-size: 0.9rem;
    margin-bottom: 10px;
}

/* Contact Section */
.contact-info {
    margin-bottom: 30px;
}

.contact-info p {
    margin-bottom: 10px;
    font-size: 1.1rem;
}

.form-control {
    padding: 12px;
    border-radius: 5px;
    margin-bottom: 20px;
}

/* Footer */
.footer {
    background-color: #1e3c72;
}

.social-links {
    margin-top: 15px;
}

.social-link {
    display: inline-block;
    width: 40px;
    height: 40px;
    line-height: 40px;
    border-radius: 50%;
    background-color: rgba(255,255,255,0.1);
    color: white;
    margin: 0 5px;
    transition: all 0.3s ease;
}

.social-link:hover {
    background-color: rgba(255,255,255,0.2);
    color: white;
}

/* Responsive Design */
@media (max-width: 992px) {
    .hero-section h1 {
        font-size: 3rem;
    }
    
    .section {
        padding: 80px 0;
    }
}

@media (max-width: 768px) {
    .hero-section h1 {
        font-size: 2.5rem;
    }
    
    .hero-section {
        padding: 120px 0 80px;
    }
    
    .section {
        padding: 60px 0;
    }
    
    .section-title {
        margin-bottom: 40px;
    }
}

@media (max-width: 576px) {
    .hero-section h1 {
        font-size: 2rem;
    }
    
    .hero-section .lead {
        font-size: 1rem;
    }
    
    .hero-buttons .btn {
        display: block;
        width: 100%;
        margin-bottom: 10px;
    }
    
    .hero-buttons .btn:last-child {
        margin-bottom: 0;
    }
}
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
