# Portfolio.Krisha

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-white shadow-lg p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">My Portfolio</h1>
            <ul class="flex space-x-4">
                <li><a href="#about" class="text-gray-700 hover:text-blue-500">About</a></li>
                <li><a href="#projects" class="text-gray-700 hover:text-blue-500">Projects</a></li>
                <li><a href="#contact" class="text-gray-700 hover:text-blue-500">Contact</a></li>
            </ul>
        </div>
    </nav>
    
    <!-- Hero Section -->
    <section class="text-center py-20 bg-blue-500 text-white">
        <h2 class="text-4xl font-bold">Hello, I'm John Doe</h2>
        <p class="mt-4 text-lg">A Web Developer specializing in Tailwind CSS</p>
    </section>
    
    <!-- About Section -->
    <section id="about" class="container mx-auto py-20 px-6">
        <h2 class="text-3xl font-bold text-center">About Me</h2>
        <p class="text-center mt-4 text-gray-700">I am a passionate web developer with experience in modern web technologies.</p>
    </section>
    
    <!-- Projects Section -->
    <section id="projects" class="bg-gray-200 py-20 px-6">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold text-center">Projects</h2>
            <div class="grid md:grid-cols-3 gap-6 mt-6">
                <div class="bg-white p-4 shadow-md rounded-lg">
                    <h3 class="text-xl font-semibold">Project One</h3>
                    <p class="text-gray-600">Description of project one.</p>
                </div>
                <div class="bg-white p-4 shadow-md rounded-lg">
                    <h3 class="text-xl font-semibold">Project Two</h3>
                    <p class="text-gray-600">Description of project two.</p>
                </div>
                <div class="bg-white p-4 shadow-md rounded-lg">
                    <h3 class="text-xl font-semibold">Project Three</h3>
                    <p class="text-gray-600">Description of project three.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section id="contact" class="container mx-auto py-20 px-6 text-center">
        <h2 class="text-3xl font-bold">Contact Me</h2>
        <p class="mt-4 text-gray-700">Email: johndoe@example.com</p>
    </section>
    
    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center p-4">
        <p>&copy; 2025 John Doe. All rights reserved.</p>
    </footer>
</body>
</html>
