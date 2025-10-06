
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VolunteerConnect - Make a Difference</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #4CAF50;
            --secondary: #2E7D32;
            --accent: #8BC34A;
            --light: #F1F8E9;
            --dark: #1B5E20;
            --text: #333;
            --white: #fff;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {

                <div class="testimonial">
                    <i class="fas fa-quote-left"></i>
                    <p>Volunteering at the food bank opened my eyes to the needs in our community. The gratitude from those we serve makes every hour spent completely worth it.</p>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/men/22.jpg" alt="Rajesh Kumar">
                        <div class="author-info">
                            <h4>Rajesh Kumar</h4>
                            <p>Food Bank Volunteer</p>
                        </div>
                    </div>
                </div>

                <div class="testimonial">
                    <i class="fas fa-quote-left"></i>
                    <p>I joined VolunteerConnect to meet new people and give back. What I didn't expect was how much I would learn about myself and my community through this experience.</p>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/women/45.jpg" alt="Priya Sharma">
                        <div class="author-info">
                            <h4>Priya Sharma</h4>
                            <p>Community Volunteer</p>
                        </div>
                    </div>
                </div>
            color: var(--text);
            line-height: 1.6;
            background-color: var(--light);
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--dark));
            color: var(--white);
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            display: flex;
            align-items: center;
        }
        
        .logo i {
            margin-right: 10px;
            color: var(--accent);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin-left: 2rem;
        }
        
        .nav-links a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: var(--accent);
        }
        
        .btn {
            display: inline-block;
            background: var(--accent);
            color: var(--white);
            padding: 0.6rem 1.5rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
        }
        
        .btn:hover {
            background: var(--secondary);
            transform: translateY(-2px);
        }
        
        .hero {
            height: 100vh;
            background: url('https://images.unsplash.com/photo-1521791136064-7986c2920216?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2069&q=80') no-repeat center center/cover;
            display: flex;
            align-items: center;
            text-align: center;
            color: var(--white);
            position: relative;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.6);
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
            padding: 0 1rem;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }
        
        section {
            padding: 5rem 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            color: var(--dark);
            position: relative;
        }
        
        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: var(--accent);
            margin: 1rem auto;
        }
        
        .opportunities {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .opportunity-card {
            background: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .opportunity-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.2);
        }
        
        .card-img {
            height: 200px;
            overflow: hidden;
        }
        
        .card-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .opportunity-card:hover .card-img img {
            transform: scale(1.1);
        }
        
        .card-content {
            padding: 1.5rem;
        }
        
        .card-content h3 {
            margin-bottom: 0.5rem;
            color: var(--dark);
        }
        
        .card-content p {
            margin-bottom: 1rem;
            color: #666;
        }
        
        .testimonials {
            background: var(--primary);
            color: var(--white);
        }
        
        .testimonial-container {
            display: flex;
            overflow-x: auto;
            scroll-snap-type: x mandatory;
            gap: 2rem;
            padding: 1rem 0;
            scrollbar-width: none; /* Firefox */
        }
        
        .testimonial-container::-webkit-scrollbar {
            display: none; /* Chrome, Safari, Opera */
        }
        
        .testimonial {
            min-width: 100%;
            scroll-snap-align: start;
            background: rgba(255,255,255,0.1);
            padding: 2rem;
            border-radius: 8px;
            position: relative;
        }
        
        .testimonial i {
            font-size: 2rem;
            color: var(--accent);
            margin-bottom: 1rem;
        }
        
        .testimonial p {
            font-style: italic;
            margin-bottom: 1.5rem;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
        }
        
        .testimonial-author img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 1rem;
            object-fit: cover;
        }
        
        .author-info h4 {
            margin-bottom: 0.2rem;
        }
        
        .author-info p {
            font-style: normal;
            font-size: 0.9rem;
            opacity: 0.8;
            margin: 0;
        }
        
        .signup-form {
            max-width: 600px;
            margin: 0 auto;
            background: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--dark);
        }
        
        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }
        
        .form-group textarea {
            height: 120px;
            resize: vertical;
        }
        
        footer {
            background: var(--dark);
            color: var(--white);
            padding: 3rem 0 1rem;
            text-align: center;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
            text-align: left;
        }
        
        .footer-column h3 {
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 0.5rem;
        }
        
        .footer-column h3::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50px;
            height: 2px;
            background: var(--accent);
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column ul li {
            margin-bottom: 0.8rem;
        }
        
        .footer-column ul li a {
            color: #ccc;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-column ul li a:hover {
            color: var(--accent);
        }
        
        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .social-links a {
            color: var(--white);
            background: rgba(255,255,255,0.1);
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
        }
        
        .social-links a:hover {
            background: var(--accent);
            transform: translateY(-3px);
        }
        
        .copyright {
            padding-top: 1.5rem;
            border-top: 1px solid rgba(255,255,255,0.1);
            font-size: 0.9rem;
            color: #ccc;
        }
        
        /* Mobile menu */
        .menu-toggle {
            display: none;
            cursor: pointer;
            font-size: 1.5rem;
        }
        
        @media (max-width: 768px) {
            .menu-toggle {
                display: block;
            }
            
            .nav-links {
                position: fixed;
                top: 70px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 70px);
                background: var(--dark);
                flex-direction: column;
                align-items: center;
                padding: 2rem 0;
                transition: left 0.3s;
            }
            
            .nav-links.active {
                left: 0;
            }
            
            .nav-links li {
                margin: 1rem 0;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">
                    <i class="fas fa-hands-helping"></i>
                    <span>VolunteerConnect</span>
                </div>
                <div class="menu-toggle">
                    <i class="fas fa-bars"></i>
                </div>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#opportunities">Opportunities</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#signup">Sign Up</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Make a Difference Today</h1>
            <p>Join our community of volunteers and help create positive change in your community. Whether you have a few hours or want to make a long-term commitment, your time and skills can make a real impact.</p>
            <a href="#signup" class="btn">Become a Volunteer</a>
        </div>
    </section>

    <section id="opportunities">
        <div class="container">
            <h2 class="section-title">Volunteer Opportunities</h2>
            <div class="opportunities">
                <div class="opportunity-card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Community Service">
                    </div>
                    <div class="card-content">
                        <h3>Community Cleanup</h3>
                        <p>Help keep our neighborhoods clean and beautiful by participating in our monthly cleanup events.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                
                <div class="opportunity-card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1573497491765-dccce02b29df?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Food Bank">
                    </div>
                    <div class="card-content">
                        <h3>Food Bank Assistance</h3>
                        <p>Sort, pack, and distribute food to those in need at our local food bank.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                
                <div class="opportunity-card">
                    <div class="card-img">
                        <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2071&q=80" alt="Youth Mentoring">
                    </div>
                    <div class="card-content">
                        <h3>Youth Mentoring</h3>
                        <p>Become a mentor and help guide young people toward a brighter future.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="testimonials" id="testimonials">
        <div class="container">
            <h2 class="section-title">What Our Volunteers Say</h2>
            <div class="testimonial-container">
                <div class="testimonial">
                    <i class="fas fa-quote-left"></i>
                    <p>Volunteering with VolunteerConnect has been one of the most rewarding experiences of my life. The team is supportive and the work we do truly makes a difference in people's lives.</p>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="Sarah Johnson">
                        <div class="author-info">
                            <h4>Sarah Johnson</h4>
                            <p>Volunteer since 2019</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial">
                    <i class="fas fa-quote-left"></i>
                    <p>I started volunteering to give back to my community, but I never expected how much I would get in return. The connections I've made and the skills I've developed are invaluable.</p>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Michael Chen">
                        <div class="author-info">
                            <h4>Michael Chen</h4>
                            <p>Food Bank Volunteer</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial">
                    <i class="fas fa-quote-left"></i>
                    <p>As a retired teacher, mentoring young people through VolunteerConnect has given me a new sense of purpose. Seeing my mentees grow and succeed is incredibly fulfilling.</p>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Patricia Williams">
                        <div class="author-info">
                            <h4>Patricia Williams</h4>
                            <p>Youth Mentor</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="signup">
        <div class="container">
            <h2 class="section-title">Join Our Volunteer Team</h2>
            <div class="signup-form">
                <form id="volunteerForm">
                    <div class="form-group">
                        <label for="name">Full Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="email">Email Address</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="phone">Phone Number</label>
                        <input type="tel" id="phone" name="phone">
                    </div>
                    
                    <div class="form-group">
                        <label for="interest">Area of Interest</label>
                        <select id="interest" name="interest" required>
                            <option value="">Select an option</option>
                            <option value="community">Community Cleanup</option>
                            <option value="food">Food Bank Assistance</option>
                            <option value="youth">Youth Mentoring</option>
                            <option value="other">Other</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="availability">Availability</label>
                        <select id="availability" name="availability" required>
                            <option value="">Select an option</option>
                            <option value="weekdays">Weekdays</option>
                            <option value="weekends">Weekends</option>
                            <option value="both">Both</option>
                            <option value="flexible">Flexible</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="message">Why do you want to volunteer with us?</label>
                        <textarea id="message" name="message"></textarea>
                    </div>
                    
                    <button type="submit" class="btn">Submit Application</button>
                </form>
            </div>
        </div>
    </section>

    <footer id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>VolunteerConnect</h3>
                    <p>Making a difference in communities through the power of volunteering.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#opportunities">Opportunities</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#signup">Sign Up</a></li>
                    </ul>
                </div>
                
                <div class="footer-column">
                    <h3>Contact Us</h3>
                    <ul>
                        <li><i class="fas fa-phone"></i> (+91) 84380-38249</li>
                        <li><i class="fas fa-envelope"></i> krithiknirhanjan@gmail.com</li>
                        <li><i class="fas fa-map-marker-alt"></i> Tamil Nadu, India</li>
                    </ul>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 VolunteerConnect. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const menuToggle = document.querySelector('.menu-toggle');
        const navLinks = document.querySelector('.nav-links');
        
        menuToggle.addEventListener('click', () => {
            navLinks.classList.toggle('active');
        });
        
        // Close mobile menu when clicking on a link
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                navLinks.classList.remove('active');
            });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop - 70,
                    behavior: 'smooth'
                });
            });
        });
        
        // Form submission
        const volunteerForm = document.getElementById('volunteerForm');
        
        volunteerForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form values
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            
            // In a real application, you would send this data to a server
            // For this demo, we'll just show an alert
            alert(`Thank you, ${name}! We've received your volunteer application and will contact you at ${email} soon.`);
            
            // Reset the form
            volunteerForm.reset();
        });
        
        // Auto-scrolling testimonials
        let currentTestimonial = 0;
        const testimonials = document.querySelectorAll('.testimonial');
        const testimonialContainer = document.querySelector('.testimonial-container');
        
        function scrollTestimonials() {
            currentTestimonial = (currentTestimonial + 1) % testimonials.length;
            testimonialContainer.scrollTo({
                left: currentTestimonial * testimonialContainer.offsetWidth,
                behavior: 'smooth'
            });
        }
        
        // Change testimonial every 5 seconds
        setInterval(scrollTestimonials, 5000);
    </script>
</body>
</html>
