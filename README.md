# Nexon
Its the I wanna build ..
<html>
    <head>
        <base href="https://nexon.tech/"><title>Nexon - Innovating the Future</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
    :root {
        --primary-color: #3498db;
        --secondary-color: #2c3e50;
        --accent-color: #e74c3c;
        --text-color: #333;
        --light-bg: #ecf0f1;
    }
    
    body, html {
        margin: 0;
        padding: 0;
        font-family: 'Roboto', sans-serif;
        line-height: 1.6;
        color: var(--text-color);
        scroll-behavior: smooth;
    }
    
    .container {
        width: 80%;
        margin: auto;
        overflow: hidden;
    }
    
    header {
        background: var(--secondary-color);
        color: white;
        padding: 1rem 0;
        position: fixed;
        width: 100%;
        top: 0;
        z-index: 1000;
    }
    
    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    
    .logo {
        font-size: 1.8rem;
        font-weight: bold;
        display: flex;
        align-items: center;
    }
    
    .logo span {
        color: var(--primary-color);
    }
    
    .logo img {
        margin-right: 10px;
        width: 40px;
        height: 40px;
    }
    
    nav ul {
        display: flex;
        list-style: none;
    }
    
    nav ul li {
        margin-left: 1.5rem;
    }
    
    nav a {
        color: white;
        text-decoration: none;
        font-size: 1rem;
        transition: 0.3s;
    }
    
    nav a:hover {
        color: var(--primary-color);
    }
    
    #hero {
        background: linear-gradient(rgba(44, 62, 80, 0.7), rgba(44, 62, 80, 0.7)), url('https://nexon.tech/images/hero-bg.jpg') no-repeat center center/cover;
        height: 100vh;
        color: white;
        display: flex;
        align-items: center;
        text-align: center;
    }
    
    .hero-content {
        max-width: 800px;
        margin: auto;
    }
    
    .hero-content h1 {
        font-size: 3.5rem;
        margin-bottom: 1rem;
    }
    
    .hero-content p {
        font-size: 1.2rem;
        margin-bottom: 2rem;
    }
    
    .btn {
        display: inline-block;
        background: var(--primary-color);
        color: white;
        padding: 0.8rem 1.8rem;
        border: none;
        cursor: pointer;
        font-size: 1rem;
        border-radius: 5px;
        transition: 0.3s;
        text-decoration: none;
    }
    
    .btn:hover {
        background: #2980b9;
    }
    
    #services {
        padding: 5rem 0;
        background: var(--light-bg);
    }
    
    .services-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 2rem;
    }
    
    .service-card {
        background: white;
        padding: 2rem;
        border-radius: 5px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        transition: 0.3s;
    }
    
    .service-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 20px rgba(0,0,0,0.2);
    }
    
    .service-card h3 {
        color: var(--primary-color);
    }
    
    #about {
        padding: 5rem 0;
    }
    
    .about-content {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    
    .about-text {
        flex: 1;
        padding-right: 2rem;
    }
    
    .about-image {
        flex: 1;
    }
    
    .about-image img {
        width: 100%;
        border-radius: 5px;
    }
    
    #team {
        padding: 5rem 0;
        background: var(--light-bg);
    }
    
    .team-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 2rem;
    }
    
    .team-member {
        background: rgb(253, 251, 251);
        padding: 2rem;
        border-radius: 5px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        text-align: center;
        transition: 0.3s;
    }
    
    .team-member:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 20px rgba(0,0,0,0.2);
    }
    
    .team-member img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        margin-bottom: 1rem;
    }
    
    footer {
        background: var(--secondary-color);
        color: white;
        text-align: center;
        padding: 4rem 0;
    }
    
    .contact-form {
        max-width: 500px;
        margin: 2rem auto;
        padding: 2rem;
        background: white;
        border-radius: 5px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    
    .contact-form h3 {
        margin-bottom: 1rem;
        color: var(--primary-color);
    }
    
    .form-group {
        margin-bottom: 1rem;
    }
    
    .form-group label {
        display: block;
        margin-bottom: 0.5rem;
        color: var(--text-color);
    }
    
    .form-group input,
    .form-group textarea {
        width: 100%;
        padding: 0.5rem;
        border: 1px solid #ddd;
        border-radius: 4px;
    }
    
    .form-group textarea {
        height: 100px;
    }
    
    #prices {
        padding: 5rem 0;
        background: var(--light-bg);
    }

    .prices-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 2rem;
        margin-top: 2rem;
    }

    .price-card {
        background: white;
        padding: 2rem;
        border-radius: 5px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        text-align: center;
        transition: 0.3s;
    }

    .price-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 20px rgba(0,0,0,0.2);
    }

    .price-card h3 {
        color: var(--primary-color);
        font-size: 1.5rem;
        margin-bottom: 1rem;
    }

    .price-card .price {
        font-size: 2.5rem;
        font-weight: bold;
        margin-bottom: 1rem;
    }

    .price-card .price span {
        font-size: 1rem;
        font-weight: normal;
    }

    .price-card ul {
        list-style: none;
        padding: 0;
        margin: 1rem 0;
    }

    .price-card ul li {
        margin-bottom: 0.5rem;
    }

    .price-card .btn {
        display: inline-block;
        margin-top: 1rem;
    }

    .custom-card {
        display: flex;
        flex-direction: column;
    }

    .custom-card form {
        flex-grow: 1;
        display: flex;
        flex-direction: column;
    }

    .custom-card .form-group {
        margin-bottom: 1rem;
        flex-grow: 1;
        display: flex;
        flex-direction: column;
    }

    .custom-card textarea {
        flex-grow: 1;
        min-height: 100px;
    }

    .custom-card .btn {
        align-self: center;
    }

    @keyframes slideInFromLeft {
        0% {
            transform: translateX(-100%);
            opacity: 0;
        }
        100% {
            transform: translateX(0);
            opacity: 1;
        }
    }

    .slide-in {
        opacity: 0;
        transition: opacity 0.8s ease-out, transform 0.8s ease-out;
    }

    .slide-in.active {
        animation: slideInFromLeft 0.8s forwards;
    }

    @media (max-width: 768px) {
        .container {
            width: 90%;
        }
        
        nav ul {
            display: none;
        }
        
        .about-content {
            flex-direction: column;
        }
        
        .about-text, .about-image {
            width: 100%;
            padding: 1rem 0;
        }
    }
</style>
</head>
<body>
    <header>
    <nav class="container">
        <div class="logo">
            <img src="https://media.discordapp.net/attachments/1285191939360292894/1286521129359507567/baka.jpg?ex=66ee35ab&is=66ece42b&hm=5cd4fca5f4cc48f93692fd29fda710d90ec6fbdf8b408a72e83b7c3625e1e04e&=&format=webp&width=383&height=417" alt="Nexon logo" width="40" height="40">
            Nex<span>on</span>
        </div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="#prices">Prices</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

    <section id="hero">
        <div class="hero-content">
            <h1>Innovating the Future</h1>
            <p>At Nexon, we're passionate about pushing the boundaries of technology to create a better tomorrow.</p>
            <a href="#services" class="btn">Get Started</a>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services-grid">
                <div class="service-card slide-in">
                    <h3>Web Design</h3>
                    <p>Create stunning, responsive websites that captivate your audience and drive engagement.</p>
                </div>
                <div class="service-card slide-in">
                    <h3>3D Modeling</h3>
                    <p>Transform your ideas into stunning 3D visualizations with our expert modeling services.</p>
                </div>
                <div class="service-card slide-in">
                    <h3>Cybersecurity</h3>
                    <p>Protect your digital assets with our state-of-the-art security solutions.</p>
                </div>
                <div class="service-card slide-in">
                    <h3>Video Editing</h3>
                    <p>Transform your raw footage into compelling visual stories with our professional video editing services.</p>
                </div>
            </div>
        </div>
    </section>


    <section id="about">
        <div class="container about-content">
            <div class="about-text">
                <h2>About Nexon</h2>
                <p>Founded in 2024, Nexon has quickly established itself as a pioneer in technological innovation. Despite our young age, our team of expert engineers and visionary leaders work tirelessly to develop cutting-edge solutions that address the world's most pressing challenges.</p>
                <p>We believe in the power of technology to create positive change and are committed to ethical innovation that benefits society as a whole.</p>
            </div>
            <div class="about-image">
                <img alt="photo" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8MRQn6xaFRsT_GnOzByo-C9vOud3EZlPWNQ&s" width="500" height="300">
            </div>
        </div>
    </section>

    <section id="team">
        <div class="container">
            <h2>Our Team</h2>
            <div class="team-grid">
                <div class="team-member">
                    <img src="https://scontent.fktm17-1.fna.fbcdn.net/v/t39.30808-6/460878535_1030047135489551_5380631847927136064_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=127cfc&_nc_ohc=eq4NwjkBMXEQ7kNvgHnVWBW&_nc_ht=scontent.fktm17-1.fna&oh=00_AYC7hdRaV7L-IPv0oCcedCj1jKl_GyqdmYCVwl9QjE-_Sg&oe=66F2A06B" alt="Photo" width="150" height="150">
                    <h3>Abhisek panthi</h3>
                    <p>CEO</p>
                </div>
                <div class="team-member">
                    <img src="https://nexon.tech/images/team-member-2.jpg" alt="Photo" width="150" height="150">
                    <h3>Prajwal bagale</h3>
                    <p>App developer</p>
                </div>
                <div class="team-member">
                    <img src="https://nexon.tech/images/team-member-3.jpg" alt="Photo" width="150" height="150">
                    <h3>Snaskar adhikari</h3>
                    <p>Cyber security</p>
                </div>
                <div class="team-member">
                    <img src="https://media.discordapp.net/attachments/1286354619940864153/1286354681790074911/IMG_20240919_202230.jpg?ex=66ed9aa7&is=66ec4927&hm=c89baf8b9e6e9c5bf1c5f9b7038296c426f860da714d00b0d878afe0fd288800&=&format=webp&width=199&height=416" alt="Photo" width="150" height="150">
                    <h3>Monk Thapa</h3>
                    <p>Video editor</p>
                </div>
                <div class="team-member">
                    <img src="https://scontent.fktm17-1.fna.fbcdn.net/v/t39.30808-6/379990529_348998724126762_8762271610410610732_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=833d8c&_nc_ohc=EOvNd2YhMbYQ7kNvgEHj9o8&_nc_ht=scontent.fktm17-1.fna&_nc_gid=AsZMHhL3KDqcPTW322pdQMD&oh=00_AYCmjvtbcvO560aUJKgXAe72fKVGgZw9v5yngyTTgDWHJA&oe=66F2B06F" alt="Photo" width="100" height="100">
                    <h3>Sujal Dhunga</h3>
                    <p>Game developer</p>
                </div>
                <div class="team-member">
                    <img src="https://scontent.fktm17-1.fna.fbcdn.net/v/t39.30808-1/455926815_519179073957433_4195503956021362700_n.jpg?stp=c0.252.1536.1536a_dst-jpg_s200x200&_nc_cat=110&ccb=1-7&_nc_sid=0ecb9b&_nc_ohc=ocUiLPpuwPUQ7kNvgGUp5Gz&_nc_ht=scontent.fktm17-1.fna&_nc_gid=AKjL6o0f92xPFYi_20vzEMp&oh=00_AYC9m8MTVIdKgzhuQlKlXaHz0revCVrhYc5qP4VJRDCadw&oe=66F2A6D9" alt="Photo" width="150" height="150">
                    <h3>Sushant Barma</h3>
                    <p>Programmer</p>
                </div>
                <div class="team-member">
                    <img src="https://scontent.fktm17-1.fna.fbcdn.net/v/t39.30808-6/399273073_3256688651144697_4371581298747895938_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=94e2a3&_nc_ohc=8ZSD89kz5OIQ7kNvgGq0dIn&_nc_ht=scontent.fktm17-1.fna&_nc_gid=A0h8jxkJ0YbFXQvV33uQwTT&oh=00_AYBSIFO2B1siUMlzAgE8GNI8LYT_DOcYlxmejrCc7mE8GA&oe=66F2CC8A" alt="Photo" width="150" height="150">
                    <h3>Pratik aryal</h3>
                    <p>Java script</p>
                </div>
            </div>
        </div>
    </section>


    <section id="prices">
        <div class="container">
            <h2>Our Pricing Plans</h2>
            <div class="prices-grid">
                <div class="price-card slide-in">
                    <h3>Basic</h3>
                    <p class="price">$10<span>/month</span></p>
                    <ul>
                        <li>Web Design</li>
                        <li>5 Pages</li>
                        <li>Basic SEO</li>
                        <li>1 Revision</li>
                    </ul>
                    <a href="#contact" class="btn">Choose Plan</a>
                </div>
                <div class="price-card slide-in">
                    <h3>Pro</h3>
                    <p class="price">$20<span>/month</span></p>
                    <ul>
                        <li>Web Design</li>
                        <li>10 Pages</li>
                        <li>Advanced SEO</li>
                        <li>3 Revisions</li>
                        <li>Basic 3D Modeling</li>
                    </ul>
                    <a href="#contact" class="btn">Choose Plan</a>
                </div>
                <div class="price-card slide-in">
                    <h3>Enterprise</h3>
                    <p class="price">$30<span>/month</span></p>
                    <ul>
                        <li>Custom Web Design</li>
                        <li>Unlimited Pages</li>
                        <li>Premium SEO</li>
                        <li>Unlimited Revisions</li>
                        <li>Advanced 3D Modeling</li>
                        <li>Video Editing</li>
                    </ul>
                    <a href="#contact" class="btn">Choose Plan</a>
                </div>
                <div class="price-card custom-card slide-in">
                    <h3>Custom Project</h3>
                    <p class="price">$50<span>/project</span></p>
                    <p>Tell us how you want your project built:</p>
                    <form id="custom-project-form">
                        <div class="form-group">
                            <label for="custom-instructions">Your Instructions:</label>
                            <textarea id="custom-instructions" name="custom-instructions" required></textarea>
                        </div>
                        <button type="submit" class="btn">Submit Project</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact">
        <div class="container slide-in">
            <h2>Contact Us</h2>
            <p>Ready to innovate? Get in touch with us today.</p>
            
            <div class="contact-form slide-in">
                <h3>Send us a message</h3>
                <form id="contact-form">
                    <div class="form-group">
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" required="">
                    </div>
                    <div class="form-group">
                        <label for="message">Message:</label>
                        <textarea id="message" name="message" required=""></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
            
            <p>Email: info@nexon.tech | Phone: (555) 699-69-911</p>
            <p>© 2024 Nexon. All rights reserved.</p>
            <p>Created by: Abhisek panthi</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => 
        {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({
                        behavior: 'smooth'
                    });
                } else if (targetId === 'home') {
                    window.scrollTo({
                        top: 0,
                        behavior: 'smooth'
                    });
                }
            });
        });
    
        // Header hide on scroll
        let lastScrollTop = 0;
        const header = document.querySelector('header');
        const scrollThreshold = 50; // Adjust this value to change when the header hides
    
        window.addEventListener('scroll', () => {
            let scrollTop = window.pageYOffset || document.documentElement.scrollTop;
            
            if (scrollTop > lastScrollTop && scrollTop > scrollThreshold) {
                // Scrolling down
                header.classList.add('hide');
            } else {
                // Scrolling up
                header.classList.remove('hide');
            }
            
            lastScrollTop = scrollTop <= 0 ? 0 : scrollTop;
        }, false);
    
        // Contact form validation and submission
        const form = document.getElementById('contact-form');
        if (form) {
            form.addEventListener('submit', (e) => {
                e.preventDefault();
                
                // Simple form validation
                const email = document.getElementById('email').value.trim();
                const message = document.getElementById('message').value.trim();
                
                if (!email || !message) {
                    alert('Please fill in all fields');
                    return;
                }
                
                if (!isValidEmail(email)) {
                    alert('Please enter a valid email address');
                    return;
                }
                
                // Here you would typically send the form data to a server
                console.log('Form submitted:', { email, message });
                alert('Thank you for your message. We will get back to you soon!');
                
                // Clear the form
                form.reset();
            });
        }
    
        // Simple email validation function
        function isValidEmail(email) {
            const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            return re.test(email);
        }
    
        // Custom project form submission handling
        const customProjectForm = document.getElementById('custom-project-form');
        if (customProjectForm) {
            customProjectForm.addEventListener('submit', (e) => {
                e.preventDefault();
                
                const instructions = document.getElementById('custom-instructions').value.trim();
                
                if (!instructions) {
                    alert('Please provide instructions for your custom project');
                    return;
                }
                
                // Here you would typically send the form data to a server
                console.log('Custom project submitted:', { instructions });
                alert('Thank you for your custom project request. We will review your instructions and get back to you soon!');
                
                // Clear the form
                customProjectForm.reset();
            });
        }
    
        // Intersection Observer for fade-in animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, {threshold: 0.1});
    
        document.querySelectorAll('.slide-in').forEach((el) => observer.observe(el));
    </script>
    
    </body></html>
