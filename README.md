<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Subhash Chandra Bose Scholarship Foundation</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">SCBSF</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#scholarships">Scholarships</a></li>
                <li><a href="#apply">Apply</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <div class="hero-content">
                <h1 class="animate-fadeIn">Subhash Chandra Bose Scholarship Foundation</h1>
                <p class="tagline animate-fadeIn">Empowering Education, Building Future Leaders</p>
                <a href="#apply" class="cta-button animate-fadeIn">Apply Now</a>
                <div class="stats">
                    <div class="stat-item">
                        <i class="fas fa-graduation-cap"></i>
                        <h3>1000+</h3>
                        <p>Students Supported</p>
                    </div>
                    <div class="stat-item">
                        <i class="fas fa-rupee-sign"></i>
                        <h3>₹5Cr+</h3>
                        <p>Scholarships Awarded</p>
                    </div>
                    <div class="stat-item">
                        <i class="fas fa-university"></i>
                        <h3>50+</h3>
                        <p>Partner Institutions</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="about">
            <div class="about-content">
                <h2>About Us</h2>
                <p class="mission">Continuing the legacy of Netaji Subhash Chandra Bose, we strive to empower young minds through education.</p>
                <div class="about-grid">
                    <div class="about-card">
                        <i class="fas fa-bullseye"></i>
                        <h3>Our Mission</h3>
                        <p>To provide financial support to deserving students and help them achieve their educational goals.</p>
                    </div>
                    <div class="about-card">
                        <i class="fas fa-eye"></i>
                        <h3>Our Vision</h3>
                        <p>Creating a society where quality education is accessible to all, regardless of economic background.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="scholarships">
            <h2>Available Scholarships</h2>
            <div class="scholarship-cards">
                <!-- Scholarship cards will be added dynamically -->
            </div>
        </section>

        <section id="apply">
            <h2>Apply for Scholarship</h2>
            <form action="https://formspree.io/f/your-form-id" method="POST" enctype="multipart/form-data" id="application-form">
                <!-- Add form ID for Formspree -->
                <input type="hidden" name="_cc" value="rmukherjee2003@gmail.com,eden.rsp@gmail.com">
                <input type="hidden" name="_subject" value="New Scholarship Application">
                
                <div class="form-grid">
                    <!-- Personal Information -->
                    <h3 class="form-section-title">Personal Information</h3>
                    <input type="text" placeholder="Full Name" required>
                    <input type="email" placeholder="Email" required>
                    <input type="tel" placeholder="Phone Number" required>
                    <input type="date" placeholder="Date of Birth" required>
                    <input type="text" placeholder="Father's Name" required>
                    <input type="text" placeholder="Mother's Name" required>
                    <textarea placeholder="Permanent Address" required></textarea>
                    
                    <!-- Scholarship Details -->
                    <h3 class="form-section-title">Scholarship Details</h3>
                    <select name="scholarship" required>
                        <option value="">Select Scholarship</option>
                        <option value="aspire">Aspire Scholarship Program</option>
                        <option value="women-stem">Women in STEM Scholarship</option>
                        <option value="rural">Rural Education Excellence</option>
                        <option value="future-leaders">Future Leaders Program</option>
                        <option value="saksham">Saksham Scholarship Program</option>
                        <option value="virchow">Virchow Scholarship Program</option>
                        <option value="legrand">Legrand Empowering Scholarship Program</option>
                        <option value="kotak-kanya">Kotak Kanya Scholarship</option>
                    </select>
                    <textarea placeholder="Why do you deserve this scholarship? (Min. 200 words)" required minlength="200"></textarea>
                    
                    <!-- Documents Upload -->
                    <h3 class="form-section-title">Required Documents</h3>
                    <div class="file-upload">
                        <label>Academic Marksheets</label>
                        <input type="file" accept=".pdf,.jpg,.jpeg,.png" multiple required>
                    </div>
                    <div class="file-upload">
                        <label>Income Certificate</label>
                        <input type="file" accept=".pdf,.jpg,.jpeg,.png" required>
                    </div>
                    <div class="file-upload">
                        <label>ID Proof</label>
                        <input type="file" accept=".pdf,.jpg,.jpeg,.png" required>
                    </div>
                </div>
                <button type="submit" class="submit-btn">Submit Application</button>
            </form>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact-info">
                <p>Email: eden.rsp@gmail.com</p>
                <p>Phone: +91 7595981444</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Subhash Chandra Bose Scholarship Foundation</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
# SUBHASH-CHANDRA-BOSE-SCHOLARSHIP-FOUNDATION
