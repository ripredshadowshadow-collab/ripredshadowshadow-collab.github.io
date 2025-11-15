<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Racer</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind to use Inter font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                },
            },
        }
    </script>
    <style>
        /* Basic body styling */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 min-h-screen flex items-center justify-center">

    <div class="w-full max-w-sm">
        <h1 class="text-2xl font-bold text-center text-gray-800 mb-6">Main Menu</h1>
        
        <!-- Navigation Menu -->
        <nav class="bg-white rounded-lg shadow-lg">
            <ul class="flex flex-col">
                <!-- Play Option -->
                <li>
                    <!-- The link now has fully rounded corners (rounded-lg) -->
                    <a href="#" 
                       class="flex items-center justify-center w-full px-6 py-4 text-lg font-medium text-gray-700 rounded-lg hover:bg-gray-50 transition-colors duration-200">
                        <!-- Simple Play Icon -->
                        <svg class="w-5 h-5 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3l14 9-14 9V3z"></path></svg>
                        Play
                    </a>
                </li>
                <!-- "Send Picture" option and separator removed -->
            </ul>
        </nav>
    </div>

</body>
</html>
