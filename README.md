# Bricksville-District-website2
welcome


Unban request here  (https://github.com/user-attachments/files/22694300/unban-request_Version3.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brickville District Community Hub</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&family=Oswald:wght@500;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7; /* Light gray/off-white background */
        }
        .hero-background {
            /* A subtle pattern or gradient to evoke a construction/building feel */
            background-color: #1a202c; /* Dark base color */
            background-image: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.6)), url('https://placehold.co/1200x600/1a202c/ffffff?text=BRICK+RIGS+BACKGROUND');
            background-size: cover;
            background-position: center;
            /* Optional: Add a subtle brick pattern overlay for theme */
            /* filter: saturate(1.2); */
        }
        .text-brick-red {
            color: #d9534f; /* A strong, primary red often associated with bricks/construction */
        }
        .shadow-brick {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        /* Style for the modal overlay */
        .modal-overlay {
            background-color: rgba(0, 0, 0, 0.7);
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Navigation Bar -->
    <nav class="bg-gray-900 shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo/Title -->
                <a href="index.html" class="flex-shrink-0 text-white text-2xl font-extrabold tracking-wider font-oswald">
                    BRICKVILLE DISTRICT
                </a>

                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-4">
                    <a href="index.html" class="text-brick-red bg-gray-800 px-3 py-2 rounded-lg font-medium transition duration-150">Home</a>
                    <!-- Links updated to specific file versions -->
                    <a href="brickville-district-admin-application_Version2.html" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-lg font-medium transition duration-150">Staff Application</a>
                    <a href="unban-request_Version3.html" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-lg font-medium transition duration-150">Unban Request</a>
                    <a href="ideas-tab_Version9.1.html" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-lg font-medium transition duration-150">Community Ideas</a>
                    <a href="#about" class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-lg font-medium transition duration-150">Rules & Info</a>
                </div>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" type="button" class="inline-flex items-center justify-center p-2 rounded-lg text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none md:hidden" aria-controls="mobile-menu" aria-expanded="false">
                    <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu (Hidden by default) -->
        <div class="md:hidden hidden" id="mobile-menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="index.html" class="text-brick-red bg-gray-800 block px-3 py-2 rounded-lg font-medium transition duration-150">Home</a>
                <!-- Links updated to specific file versions -->
                <a href="brickville-district-admin-application_Version2.html" class="text-gray-300 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-lg font-medium transition duration-150">Staff Application</a>
                <a href="unban-request_Version3.html" class="text-gray-300 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-lg font-medium transition duration-150">Unban Request</a>
                <a href="ideas-tab_Version9.1.html" class="text-gray-300 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-lg font-medium transition duration-150">Community Ideas</a>
                <a href="#about" class="text-gray-300 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-lg font-medium transition duration-150">Rules & Info</a>
            </div>
        </div>
    </nav>

    <!-- Main Content Area -->
    <main>
        <!-- Hero Section -->
        <div class="hero-background text-white py-20 sm:py-32">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h2 class="text-5xl sm:text-7xl font-oswald font-bold tracking-tight mb-4">
                    <span class="text-brick-red">BUILD</span>. <span class="text-yellow-400">CREATE</span>. <span class="text-blue-400">DOMINATE</span>.
                </h2>
                <p class="text-xl sm:text-2xl font-light max-w-3xl mx-auto mb-8 text-gray-200">
                    Welcome to the Brickville District—the ultimate destination for builders and creators in the Brick Rigs universe.
                </p>
                <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-6">
                    <!-- Call to Action 1: Join Server - Now opens the modal -->
                    <button id="join-server-btn" class="bg-brick-red hover:bg-red-700 text-white font-bold py-3 px-8 rounded-xl shadow-lg transition duration-300 transform hover:scale-105 active:scale-95 text-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 inline-block mr-2 -mt-0.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"/></svg>
                        Connect to the Server
                    </button>
                    <!-- Call to Action 2: Staff Application - Linked to main application file -->
                    <a href="brickville-district-admin-application_Version2.html" class="bg-yellow-400 hover:bg-yellow-500 text-gray-900 font-bold py-3 px-8 rounded-xl shadow-lg transition duration-300 transform hover:scale-105 active:scale-95 text-lg">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 inline-block mr-2 -mt-0.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M22 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
                        Staff Application
                    </a>
                </div>
            </div>
        </div>

        <!-- Features/Info Grid -->
        <section id="features" class="py-16 sm:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h3 class="text-4xl font-extrabold text-gray-800 text-center mb-12 font-oswald">COMMUNITY ACCESS POINTS</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

                <!-- Feature Card 1: Applications - Linked to main application file -->
                <a href="brickville-district-admin-application_Version2.html" class="block bg-white p-6 rounded-2xl shadow-brick hover:shadow-xl transition duration-300 transform hover:-translate-y-1 border-t-4 border-brick-red">
                    <div class="flex items-center text-brick-red mb-4">
                         <!-- Icon for Applications -->
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6M16 13H8M16 17H8M10 9H8"/></svg>
                        <h4 class="text-xl font-bold">Staff Applications</h4>
                    </div>
                    <p class="text-gray-600">Think you have what it takes to moderate the District? Apply here to join our team and help us keep the community running smoothly.</p>
                </a>

                <!-- Feature Card 2: Unban Request - Linked to unban file -->
                <a href="unban-request_Version3.html" class="block bg-white p-6 rounded-2xl shadow-brick hover:shadow-xl transition duration-300 transform hover:-translate-y-1 border-t-4 border-blue-500">
                    <div class="flex items-center text-blue-600 mb-4">
                         <!-- Icon for Unban -->
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/><circle cx="12" cy="12" r="10"/></svg>
                        <h4 class="text-xl font-bold">Unban Requests</h4>
                    </div>
                    <p class="text-gray-600">Made a mistake? File an appeal here. Provide clear details and follow the guidelines to have your ban reviewed by our staff team.</p>
                </a>

                <!-- Feature Card 3: Ideas Tab - Linked to ideas file -->
                <a href="ideas-tab_Version9.1.html" class="block bg-white p-6 rounded-2xl shadow-brick hover:shadow-xl transition duration-300 transform hover:-translate-y-1 border-t-4 border-green-500">
                    <div class="flex items-center text-green-600 mb-4">
                         <!-- Icon for Ideas -->
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
                        <h4 class="text-xl font-bold">Community Ideas</h4>
                    </div>
                    <p class="text-gray-600">Have a suggestion for the server, a new rule, or an event? Share your brilliant ideas and help shape the future of Brickville District.</p>
                </a>
            </div>
        </section>

        <!-- About/Rules Section -->
        <section id="about" class="bg-gray-100 py-16 sm:py-24">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="md:grid md:grid-cols-2 md:gap-12 items-center">
                    <div>
                        <h3 class="text-4xl font-extrabold text-gray-800 mb-6 font-oswald">The Brickville Vibe</h3>
                        <p class="text-gray-600 mb-4 text-lg">
                            We are the premier community for creative building and exciting sandbox physics in Brick Rigs. Our server focuses on quality builds, respectful competition, and a supportive environment for all players, old and new.
                        </p>
                        <p class="text-gray-600 mb-8">
                            We enforce fair play and encourage large-scale projects, realistic scenarios, and spectacular destruction (within the rules, of course!).
                        </p>
                        <!-- Updated View Rules button to also open the modal, as rules are often paired with connection details -->
                        <button id="view-rules-btn" class="bg-gray-800 hover:bg-gray-900 text-white font-bold py-2 px-6 rounded-lg transition duration-300">
                            View Server Rules
                        </button>
                    </div>
                    <div class="mt-10 md:mt-0">
                        <!-- Image placeholder for Brick Rigs theme -->
                        <img src="https://placehold.co/500x350/d9534f/ffffff?text=Epic+Brick+Rigs+Build" alt="Placeholder image of an epic Brick Rigs build" class="rounded-xl shadow-2xl w-full">
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Server Info Modal (Hidden by default) -->
    <div id="server-modal" class="fixed inset-0 z-[100] hidden items-center justify-center modal-overlay">
        <div class="bg-white rounded-xl shadow-2xl p-6 w-full max-w-lg mx-4 transform transition-all duration-300 scale-100">
            <h3 class="text-3xl font-extrabold text-gray-800 mb-4 font-oswald text-center text-brick-red">
                Join Brickville District
            </h3>
            <p class="text-gray-600 text-center mb-6">
                Copy the IP and Port below to join the server in Brick Rigs.
            </p>

            <div class="space-y-4">
                <!-- Server IP Display -->
                <div class="bg-gray-100 p-4 rounded-lg flex items-center justify-between shadow-inner">
                    <span class="text-sm font-medium text-gray-500 mr-4">Server IP:</span>
                    <code id="server-ip" class="text-lg font-mono text-gray-800 select-all">123.45.67.89</code>
                    <button onclick="copyToClipboard('123.45.67.89', 'ip-copy-msg')" class="ml-4 p-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition duration-150 text-sm flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg>
                        Copy IP
                    </button>
                </div>

                <!-- Server Port Display -->
                <div class="bg-gray-100 p-4 rounded-lg flex items-center justify-between shadow-inner">
                    <span class="text-sm font-medium text-gray-500 mr-4">Port:</span>
                    <code id="server-port" class="text-lg font-mono text-gray-800 select-all">27015</code>
                    <button onclick="copyToClipboard('27015', 'port-copy-msg')" class="ml-4 p-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition duration-150 text-sm flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg>
                        Copy Port
                    </button>
                </div>
            </div>

            <!-- Status Message -->
            <div id="ip-copy-msg" class="text-center text-sm text-green-600 mt-2 font-semibold hidden">IP Copied!</div>
            <div id="port-copy-msg" class="text-center text-sm text-green-600 mt-2 font-semibold hidden">Port Copied!</div>
            
            <button id="close-modal-btn" class="mt-6 w-full py-3 bg-gray-700 text-white rounded-xl font-semibold hover:bg-gray-800 transition duration-150">
                Close
            </button>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-sm text-gray-400">&copy; 2025 Brickville District Community. All rights reserved. Not affiliated with Brick Rigs developers.</p>
            <div class="mt-4 space-x-4">
                <a href="#" class="text-gray-400 hover:text-brick-red text-sm">Discord</a>
                <a href="#" class="text-gray-400 hover:text-brick-red text-sm">Steam Group</a>
                <!-- Staff Login/Application - Linked to main application file -->
                <a href="brickville-district-admin-application_Version2.html" class="text-gray-400 hover:text-brick-red text-sm">Staff Login</a>
            </div>
        </div>
    </footer>

    <!-- JavaScript for Functionality -->
    <script>
        // --- Mobile Menu Toggle ---
        document.addEventListener('DOMContentLoaded', () => {
            const button = document.getElementById('mobile-menu-btn');
            const menu = document.getElementById('mobile-menu');
            const modal = document.getElementById('server-modal');
            const joinButton = document.getElementById('join-server-btn');
            const closeButton = document.getElementById('close-modal-btn');
            const rulesButton = document.getElementById('view-rules-btn');

            // Toggle Mobile Menu
            button.addEventListener('click', () => {
                menu.classList.toggle('hidden');
                const isExpanded = button.getAttribute('aria-expanded') === 'true' || false;
                button.setAttribute('aria-expanded', !isExpanded);
            });

            // --- Modal Control ---
            // Open modal when Join Server or View Rules is clicked
            const openModal = () => {
                modal.classList.remove('hidden');
                modal.classList.add('flex');
            };

            joinButton.addEventListener('click', openModal);
            rulesButton.addEventListener('click', openModal);

            // Close modal
            const closeModal = () => {
                modal.classList.add('hidden');
                modal.classList.remove('flex');
            };
            
            closeButton.addEventListener('click', closeModal);
            modal.addEventListener('click', (e) => {
                if (e.target === modal) {
                    closeModal(); // Close if clicked outside the content box
                }
            });
        });

        // --- Copy to Clipboard Function ---
        function copyToClipboard(textToCopy, messageId) {
            // Use execCommand('copy') for compatibility in sandbox environments
            const tempInput = document.createElement('input');
            tempInput.value = textToCopy;
            document.body.appendChild(tempInput);
            tempInput.select();
            document.execCommand('copy');
            document.body.removeChild(tempInput);

            // Show confirmation message
            const msgElement = document.getElementById(messageId);
            if (msgElement) {
                msgElement.classList.remove('hidden');
                setTimeout(() => {
                    msgElement.classList.add('hidden');
                }, 2000);
            }
        }
    </script>

</body>
</html>
