# Mobile_wesite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SRI BHAGAWAN MOBILES</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome CDN for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Custom styles for smooth transitions if needed, though Tailwind handles most */
        body {
            font-family: 'Inter', sans-serif; /* Using Inter font as per instructions */
        }
        .page-section {
            display: none; /* Hide all pages by default */
        }
        .page-section.active {
            display: block; /* Show active page */
        }
    </style>
</head>
<body class="min-h-screen bg-gray-100 font-sans flex flex-col">

    <!-- Navigation Bar -->
    <nav class="bg-gradient-to-r from-blue-600 to-blue-800 p-4 shadow-lg">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-white text-3xl font-bold rounded-lg px-3 py-1 bg-blue-700">
                 SRI BHAGAWAN MOBILES
            </h1>
            <ul class="flex space-x-6">
                <li>
                    <button
                        onclick="showPage('home')"
                        id="nav-home"
                        class="text-white text-lg font-medium px-4 py-2 rounded-lg transition duration-300 ease-in-out hover:bg-blue-700"
                    >
                        Home
                    </button>
                </li>
                <li>
                    <button
                        onclick="showPage('about')"
                        id="nav-about"
                        class="text-white text-lg font-medium px-4 py-2 rounded-lg transition duration-300 ease-in-out hover:bg-blue-700"
                    >
                        About Us
                    </button>
                </li>
                <li>
                    <button
                        onclick="showPage('contact')"
                        id="nav-contact"
                        class="text-white text-lg font-medium px-4 py-2 rounded-lg transition duration-300 ease-in-out hover:bg-blue-700"
                    >
                        Contact
                    </button>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Page Content Container -->
    <main class="flex-grow container mx-auto p-6 bg-white shadow-xl rounded-lg my-8">
        <!-- Home Page Section -->
        <section id="home-page" class="page-section text-center">
            <h2 class="text-4xl font-extrabold text-gray-800 mb-6">Welcome to Our Mobile Shop!</h2>
            <div class="mb-8 p-4 bg-blue-50 rounded-lg shadow-inner">
                <img
                    src="image\image1.jpg"
                    alt="Mobile Shop".
                    class="w-150 h-150 rounded-lg shadow-md mx-auto"
                    onerror="this.onerror=null;this.src='https://placehold.co/1200x400/ADD8E6/000000?text=Image+Not+Available';"
                />
                <p class="mt-4 text-lg text-gray-700">
                    Your one-stop destination for all your mobile needs.
                </p>
            </div>

            <section class="mb-8">
                <h3 class="text-3xl font-bold text-gray-800 mb-4">Our Products</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- Product Card 1 -->
                    <div class="bg-white p-6 rounded-lg shadow-lg border border-gray-200 hover:shadow-xl transition-shadow duration-300">
                        <img
                            src="image\image3.jpg"
                            alt="Smartphone 1"
                            class="w-150 h-50 object-cover rounded-md mb-4"
                            onerror="this.onerror=null;this.src='https://placehold.co/300x200/FFD700/000000?text=Image+Not+Available';"
                        />
                        <h4 class="text-xl font-semibold text-gray-900 mb-2">Latest Smartphone</h4>
                        <p class="text-gray-700 mb-3">Brand new model with an amazing camera, powerful processor, and long battery life.</p>
                        <span class="text-blue-600 font-bold text-lg">₹ 25,000</span>
                    </div>

                    <!-- Product Card 2 -->
                    <div class="bg-white p-6 rounded-lg shadow-lg border border-gray-200 hover:shadow-xl transition-shadow duration-300">
                        <img
                            src="image\image4.jpg"
                            alt="Smartphone 2"
                            class="w-150 h-50 object-cover rounded-md mb-4"
                            onerror="this.onerror=null;this.src='https://placehold.co/300x200/C0C0C0/000000?text=Image+Not+Available';"
                        />
                        <h4 class="text-xl font-semibold text-gray-900 mb-2">Budget-Friendly Phone</h4>
                        <p class="text-gray-700 mb-3">An affordable key_pad phones also Available.</p>
                        <span class="text-blue-600 font-bold text-lg">₹ 1,500</span>
                    </div>

                    <!-- Product Card 3 -->
                    <div class="bg-white p-6 rounded-lg shadow-lg border border-gray-200 hover:shadow-xl transition-shadow duration-300">
                        <img
                            src="image\image5.jpg"
                            alt="Mobile Accessories"
                            class="w-150 h-50 object-cover rounded-md mb-4"
                            onerror="this.onerror=null;this.src='https://placehold.co/300x200/ADD8E6/000000?text=Image+Not+Available';"
                        />
                        <h4 class="text-xl font-semibold text-gray-900 mb-2">Mobile Accessories</h4>
                        <p class="text-gray-700 mb-3">Enhance your phone with cases, screen protectors, headphones, and more.</p>
                        <span class="text-blue-600 font-bold text-lg">From ₹ 500</span>
                    </div>
                </div>
            </section>
        </section>

        <!-- About Us Page Section -->
        <section id="about-page" class="page-section text-center">
            <h2 class="text-4xl font-extrabold text-gray-800 mb-6">About Us</h2>
            <div class="bg-blue-50 p-6 rounded-lg shadow-inner mb-8">
                <p class="text-lg text-gray-700 leading-relaxed">
                   Welcome to Sri Bhagawan Mobiles – your trusted destination for the latest mobile phones and accessories.  We are dedicated to providing top-quality products from leading brands at competitive prices. Our experienced team is here to guide you in finding the perfect device that matches your needs and budget.

We believe in delivering not just technology but also trust and satisfaction. Whether you're looking for the newest smartphone, reliable accessories, or expert advice, we’re here to help.

Visit us today and experience the best in mobile technology!
                </p>
                <p class="mt-4 text-lg text-gray-700 leading-relaxed">
                    Visit our shop and experience the latest in mobile technology!
                </p>
            </div>
            <img
                src="image\image2.jpg"
                alt="Mobile Shop Interior"
                class="w-200 h-200 rounded-lg shadow-md mx-auto mt-6"
                onerror="this.onerror=null;this.src='https://placehold.co/800x400/ADD8E6/000000?text=Image+Not+Available';"
            />
        </section>

        <!-- Contact Page Section -->
        <section id="contact-page" class="page-section text-center">
            <h2 class="text-4xl font-extrabold text-gray-800 mb-6">Contact Us</h2>
            <div class="bg-blue-50 p-6 rounded-lg shadow-inner mb-8">
                <p class="text-lg text-gray-700 mb-4">
                    If you have any questions or inquiries, please feel free to contact us.
                </p>
                <div class="text-left inline-block">
                    <p class="text-xl font-semibold text-gray-800 mb-2">
                        <i class="fas fa-map-marker-alt text-blue-600 mr-2"></i> Address:
                    </p>
                    <p class="text-lg text-gray-700 mb-4">
                      Door No 7A-8-11, Beside Vijaya Watch, Main Bazar, Bazaar-534001 , Eluru , AndhraPradesh
                    </p>

                    <p class="text-xl font-semibold text-gray-800 mb-2">
                        <i class="fas fa-phone-alt text-blue-600 mr-2"></i> Phone:7
                    </p>
                    <p class="text-lg text-gray-700 mb-4">
                       +91 7207227234
                    </p>

                    
                

                    <p class="text-xl font-semibold text-gray-800 mb-2">
                        <i class="fas fa-clock text-blue-600 mr-2"></i> Working Hours:
                    </p>
                    <p class="text-lg text-gray-700">
                        Monday - Saturday: 10:00 AM to 9:00 PM
                    </p>
                    <p class="text-lg text-gray-700">
                        Sunday: Closed
                    </p>
                </div>
            </div>
            
               
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white p-4 text-center mt-auto shadow-inner">
        <div class="container mx-auto">
            <p>&copy; 2025 Mobile World. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Function to show the selected page and update active navigation button
        function showPage(pageId) {
            // Hide all page sections
            document.querySelectorAll('.page-section').forEach(section => {
                section.classList.remove('active');
            });

            // Remove active class from all navigation buttons
            document.querySelectorAll('nav button').forEach(button => {
                button.classList.remove('bg-blue-700', 'shadow-md');
            });

            // Show the selected page
            document.getElementById(pageId + '-page').classList.add('active');

            // Add active class to the corresponding navigation button
            document.getElementById('nav-' + pageId).classList.add('bg-blue-700', 'shadow-md');
        }

        // Show the home page by default when the page loads
        document.addEventListener('DOMContentLoaded', () => {
            showPage('home');
        });
    </script>
</body>
</html>
![image1](https://github.com/user-attachments/assets/99612dd0-08a2-40c0-a370-2ae9f9b8f347)
![image2](https://github.com/user-attachments/assets/ca4cf0b8-52bf-4f69-b634-1a2a38d398ce)
![image3](https://github.com/user-attachments/assets/ba4dffdd-4739-4224-aa16-6aea13c9fc8c)
![image4](https://github.com/user-attachments/assets/44536ed6-794d-406d-afe5-c07fa61947da)
![image5](https://github.com/user-attachments/assets/c31cb0f0-260f-45b1-adfa-6bec64622f07)
![image2](https://github.com/user-attachments/assets/c64724b4-74fe-4c1d-a9b1-d56fbd03f59a)
![image1](https://github.com/user-attachments/assets/3fab0fd0-8315-4221-aa23-55def87da4bc)
![image4](https://github.com/user-attachments/assets/57dff2c6-94e2-41b1-add5-0cf4dfa2c919)
![image5](https://github.com/user-attachments/assets/0ef85144-f41c-45c5-a409-84887dfc18c8)

![image3](https://github.com/user-attachments/assets/58f50ec6-dd31-458d-b12c-d0d30e86eec7)
