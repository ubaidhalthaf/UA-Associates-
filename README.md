<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UA Associate - Logistics & Supply Chain Consulting</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles to complement Tailwind */
        .navbar {
            transition: background-color 0.3s ease;
        }

        .navbar.scrolled {
            background-color: rgba(0, 0, 0, 0.8);
        }

        section {
            scroll-margin-top: 80px; /* Adjust for fixed navbar */
        }
    </style>
</head>
<body class="font-sans bg-gray-100">
    <!-- Navbar -->
    <nav class="fixed top-0 left-0 w-full bg-transparent backdrop-blur-md z-50 transition-all duration-300" id="navbar">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-white" style="font-family: 'Montserrat', sans-serif;">
                <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-600 to-teal-400">UA Associate</span>
            </a>
            <ul class="flex space-x-6">
                <li><a href="#home" class="text-white hover:text-teal-300 transition">Home</a></li>
                <li><a href="#services" class="text-white hover:text-teal-300 transition">Services</a></li>
                <li><a href="#about" class="text-white hover:text-teal-300 transition">About</a></li>
                <li><a href="#blog" class="text-white hover:text-teal-300 transition">Blog</a></li>
                <li><a href="#contact" class="text-white hover:text-teal-300 transition">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-center bg-cover bg-center" style="background-image: url('https://source.unsplash.com/1600x900/?logistics,warehouse');">
        <div class="container mx-auto px-4 text-center text-white">
            <h1 class="text-5xl md:text-6xl font-bold mb-4" style="font-family: 'Montserrat', sans-serif;">Welcome to UA Associate</h1>
            <p class="text-lg md:text-xl mb-6">Your trusted partner for innovative logistics and supply chain solutions. We empower businesses with expert guidance for operational excellence.</p>
            <a href="#services" class="inline-block bg-gradient-to-r from-blue-600 to-teal-400 text-white px-6 py-3 rounded-full hover:scale-105 transition-transform">Explore Services</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Our Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-6 bg-gray-50 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold mb-2">Operational Consulting</h3>
                    <p class="text-gray-600">Streamline processes, reduce costs, and boost efficiency with our strategic expertise.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold mb-2">Inventory Key Actions</h3>
                    <p class="text-gray-600">Optimize inventory with advanced forecasting and stock management strategies.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold mb-2">Audit Planning</h3>
                    <p class="text-gray-600">Comprehensive audits to enhance workflows and ensure compliance.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold mb-2">Supervision Methodology</h3>
                    <p class="text-gray-600">Data-driven frameworks to monitor and improve operational performance.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold mb-2">Training Programs</h3>
                    <p class="text-gray-600">Tailored workshops on best practices and emerging industry trends.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-6 md:mb-0">
                    <img src="https://source.unsplash.com/600x400/?team,office" alt="UA Associate team collaborating in a modern office" class="rounded-lg shadow-lg">
                </div>
                <div class="md:w-1/2 md:pl-8">
                    <h2 class="text-4xl font-bold mb-4 text-gray-800">About UA Associate</h2>
                    <p class="text-gray-600 mb-4">UA Associate is a premier consultancy in logistics and supply chain management, focused on strategic guidance for operational excellence. We help professionals and businesses navigate complex challenges without engaging in transportation or distribution.</p>
                    <h4 class="text-xl font-semibold mb-2">Our Mission</h4>
                    <p class="text-gray-600 mb-4">To deliver innovative, practical solutions that drive efficiency and sustainability in logistics.</p>
                    <h4 class="text-xl font-semibold mb-2">Our Vision</h4>
                    <p class="text-gray-600 mb-4">To set the global standard for logistics and supply chain consulting.</p>
                    <h4 class="text-xl font-semibold mb-2">Our Team</h4>
                    <p class="text-gray-600">Led by fictional experts like Dr. Emma Torres, a supply chain strategist, and Raj Patel, a process optimization specialist, our team brings decades of industry insights.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Insights & Blog</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-gray-50 rounded-lg shadow-lg overflow-hidden">
                    <img src="https://source.unsplash.com/600x400/?inventory,warehouse" alt="Materials management in a warehouse" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Optimizing Materials Management</h3>
                        <p class="text-gray-600">Discover strategies to reduce waste and enhance efficiency in material flows.</p>
                    </div>
                </div>
                <div class="bg-gray-50 rounded-lg shadow-lg overflow-hidden">
                    <img src="https://source.unsplash.com/600x400/?dashboard,technology" alt="Systematical literacy dashboard" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Systematical Literacy in Supply Chains</h3>
                        <p class="text-gray-600">Explore how data-driven systems transform modern logistics.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Contact Us</h2>
            <div class="flex flex-col md:flex-row gap-8">
                <div class="md:w-1/2">
                    <form id="contactForm" class="space-y-4">
                        <div>
                            <label for="name" class="block text-gray-700">Name</label>
                            <input type="text" id="name" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-teal-400" required>
                        </div>
                        <div>
                            <label for="email" class="block text-gray-700">Email</label>
                            <input type="email" id="email" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-teal-400" required>
                        </div>
                        <div>
                            <label for="message" class="block text-gray-700">Message</label>
                            <textarea id="message" rows="4" class="w-full p-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-teal-400" required></textarea>
                        </div>
                        <button type="submit" class="bg-gradient-to-r from-blue-600 to-teal-400 text-white px-6 py-3 rounded-full hover:scale-105 transition-transform">Send</button>
                    </form>
                </div>
                <div class="md:w-1/2">
                    <img src="https://source.unsplash.com/600x400/?office,building" alt="UA Associate office exterior" class="rounded-lg shadow-lg w-full h-full object-cover">
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-6 bg-gray-800 text-white text-center">
        <div class="container mx-auto px-4">
            <p>&copy; 2025 UA Associate. All rights reserved.</p>
            <div class="mt-2">
                <a href="#" class="text-teal-300 hover:text-teal-100 mx-2">LinkedIn</a>
                <a href="#" class="text-teal-300 hover:text-teal-100 mx-2">Twitter</a>
                <a href="#" class="text-teal-300 hover:text-teal-100 mx-2">Email: info@uaassociate.com</a>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Smooth scroll for nav links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });

            // Navbar background on scroll
            const navbar = document.getElementById('navbar');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 50) {
                    navbar.classList.add('scrolled');
                } else {
                    navbar.classList.remove('scrolled');
                }
            });

            // Form handling
            document.getElementById('contactForm').addEventListener('submit', (e) => {
                e.preventDefault();
                alert('Thank you for your inquiry! (Demo - use EmailJS or Formspree for live forms.)');
            });
        });
    </script>
</body>
</html># my-website
Website for knowledge spreading 
