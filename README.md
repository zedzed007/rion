<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quick Feedback Survey</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif; /* Apply Inter font */
        }
    </style>
</head>
<body class="bg-gray-100 min-h-screen flex items-center justify-center p-4">
    <div class="container bg-white p-6 md:p-8 rounded-xl shadow-lg w-full max-w-md mx-auto">
        <h1 class="text-3xl font-bold text-center text-blue-700 mb-6 md:mb-8">Quick Feedback Survey</h1>
        <form>
            <!-- Question 1 -->
            <div class="mb-5">
                <label for="q1" class="block text-gray-700 text-lg font-medium mb-2">1. What's one thing you're looking forward to this week?</label>
                <input type="text" id="q1" name="answer1"
                       class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent text-gray-800"
                       placeholder="Type your answer here..."
                       aria-label="Answer to question 1">
            </div>

            <!-- Question 2 -->
            <div class="mb-5">
                <label for="q2" class="block text-gray-700 text-lg font-medium mb-2">2. What's a simple pleasure that always brings a smile to your face?</label>
                <input type="text" id="q2" name="answer2"
                       class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent text-gray-800"
                       placeholder="Type your answer here..."
                       aria-label="Answer to question 2">
            </div>

            <!-- Question 3 -->
            <div class="mb-5">
                <label for="q3" class="block text-gray-700 text-lg font-medium mb-2">3. If you could instantly learn any new skill, what would it be?</label>
                <input type="text" id="q3" name="answer3"
                       class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent text-gray-800"
                       placeholder="Type your answer here..."
                       aria-label="Answer to question 3">
            </div>

            <!-- Question 4 -->
            <div class="mb-5">
                <label for="q4" class="block text-gray-700 text-lg font-medium mb-2">4. What's one small change that could significantly improve your day?</label>
                <input type="text" id="q4" name="answer4"
                       class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent text-gray-800"
                       placeholder="Type your answer here..."
                       aria-label="Answer to question 4">
            </div>

            <!-- Question 5 -->
            <div class="mb-6">
                <label for="q5" class="block text-gray-700 text-lg font-medium mb-2">5. What's a piece of advice you'd give your younger self?</label>
                <input type="text" id="q5" name="answer5"
                       class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent text-gray-800"
                       placeholder="Type your answer here..."
                       aria-label="Answer to question 5">
            </div>

            <!-- Submit Button -->
            <button type="submit"
                    class="w-full py-3 bg-blue-600 hover:bg-blue-700 text-white font-semibold text-lg rounded-lg shadow-md transition duration-300 ease-in-out focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50">
                Submit Answers
            </button>
        </form>
    </div>
</body>
</html>
