
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TOPSTRAT DIGITAL</title>
    <style>
        /* Your existing styles remain unchanged */

        /* Additional Styles for Enhanced Design */
        .landing-page {
            background-image: url('landing-bg.jpg'); /* Replace with your image */
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }

        .landing-page h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        .landing-page p {
            font-size: 1.5rem;
            margin-bottom: 30px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
        }

        .landing-page a {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .landing-page a:hover {
            background-color: #45a049;
        }

        .statistics-section {
            background-color: #f4f4f4;
            padding: 2rem;
        }

        .company-info-section {
            background-color: #fff;
            padding: 2rem;
        }

        .appointment-section {
            background-color: #f4f4f4;
            padding: 2rem;
        }

        .services-section {
            background-color: #fff; /* Add your preferred background color */
            padding: 2rem;
        }

        .services-section ul {
            list-style-type: none;
            padding: 0;
        }

        .services-section li {
            margin-bottom: 10px;
        }

        .services-section li:hover {
            color: #4CAF50;
            cursor: pointer;
        }

        .service-details {
            display: none;
        }

        .service-details.active {
            display: block;
        }

        .chatbot-section {
            background-color: #f4f4f4; /* Add your preferred background color */
            padding: 2rem;
        }

        .upload-logos-section {
            background-color: #fff; /* Add your preferred background color */
            padding: 2rem;
        }

        .testimonial-section {
            background-color: #f4f4f4; /* Add your preferred background color */
            padding: 2rem;
        }

        .social-media-handles {
            background-color: #333; /* Add your preferred background color */
            color: #fff;
            text-align: center;
            padding: 1rem;
        }

        /* Add more styles for other sections, forms, animations, etc. */
    </style>
</head>

<body>

    <div class="landing-page">
        <h1>Your Digital Marketing Partner</h1>
        <p>Transforming businesses through innovative strategies</p>
        <a href="#appointment-form">Book an Appointment</a>
    </div>

    <section class="statistics-section" id="statistics">
        <h2>Statistics</h2>
        <p>According to Hootsuite (2021):</p>
        <ul>
            <li>Total people using Social Media Globally: 4.33 billion</li>
            <li>97% don't go beyond the second page</li>
            <li>68% of all online experiences begin with Google search engine</li>
        </ul>
    </section>

    <section class="company-info-section" id="company-info">
        <h2>Company Info</h2>
        <h3>Vision:</h3>
        <p>To emerge as the leading and reputable force in the digital marketing landscape, pioneering innovative strategies that transcend industry norms.</p>
        <h3>Mission:</h3>
        <p>Empowering businesses globally with impactful digital campaigns, fostering lasting connections, and driving unparalleled growth.</p>
        <h3>Aim:</h3>
        <ul>
            <li>Global Impact</li>
            <li>Client Empowerment</li>
            <li>Innovative Marketing Strategies</li>
            <li>Industry Recognition</li>
            <li>Strategic Partnership</li>
        </ul>
    </section>

    <section class="appointment-section" id="appointment-form">
        <h2>Book an Appointment</h2>
        <!-- Your appointment form goes here -->
    </section>

    <section class="services-section" id="services">
        <h2>Our Services</h2>
        <ul>
            <li onclick="showServiceDetails('digital-marketing')">Digital Marketing</li>
            <li onclick="showServiceDetails('social-media-marketing')">Social Media Marketing</li>
            <li onclick="showServiceDetails('paid-per-click')">Paid Per Click</li>
            <li onclick="showServiceDetails('data-analytics')">Data Analytics</li>
            <li onclick="showServiceDetails('market-research')">Market Research</li>
            <li onclick="showServiceDetails('influencer-marketing')">Influencer Marketing</li>
            <li onclick="showServiceDetails('email-marketing')">Email Marketing</li>
            <li onclick="showServiceDetails('seo')">Search Engine Optimization</li>
            <li onclick="showServiceDetails('graphics-branding')">Graphics and Branding</li>
            <li onclick="showServiceDetails('podcast-marketing')">Podcast Marketing</li>
            <!-- Add more services as needed -->
        </ul>

        <div id="digital-marketing-details" class="service-details">
            <h3>Digital Marketing</h3>
            <p>Our digital marketing services encompass a wide range of strategies...</p>
        </div>

        <div id="social-media-marketing-details" class="service-details">
            <h3>Social Media Marketing</h3>
            <p>With our social media marketing expertise, we elevate your brand presence...</p>
        </div>

        <!-- Add details for other services -->

    </section>

    <section class="chatbot-section" id="chatbot">
        <h2>Online Chatbot</h2>
        <!-- Add your chatbot integration code here -->
    </section>

    <section class="upload-logos-section" id="upload-logos">
        <h2>Our Sponsors</h2>
        <!-- Add a form or way to upload sponsor logos -->
    </section>

    <section class="testimonial-section" id="testimonials">

```html
    <section class="testimonial-section" id="testimonials">
        <h2>Customer Testimonials</h2>
        <!-- Add a form or a way to display customer testimonials -->
    </section>

    <footer class="social-media-handles">
        <h3>Connect with Us</h3>
        <ul>
            <li><a href="your_instagram_link">Instagram</a></li>
            <li><a href="your_facebook_link">Facebook</a></li>
            <li><a href="your_whatsapp_link">WhatsApp</a></li>
            <li><a href="your_gmail_link">Gmail</a></li>
            <li><a href="your_pinterest_link">Pinterest</a></li>
            <li><a href="your_ticktok_link">TickTok</a></li>
            <li><a href="your_twitter_link">Twitter</a></li>
        </ul>
    </footer>

    <!-- Additional JavaScript for Interactivity -->
    <script>
        // Add your JavaScript for enhanced interactivity

        // Function to show/hide service details
        function showServiceDetails(serviceId) {
            // Hide all service details
            const serviceDetails = document.querySelectorAll('.service-details');
            serviceDetails.forEach(detail => {
                detail.classList.remove('active');
            });

            // Show the selected service detail
            const selectedDetail = document.getElementById(serviceId + '-details');
            selectedDetail.classList.add('active');
        }
    </script>

</body>

</html>
```
