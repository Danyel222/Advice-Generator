<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advice Generator</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Manrope:wght@800&display=swap" rel="stylesheet">
</head>
<body class="flex items-center justify-center min-h-screen bg-[#1F2632] p-6">
    <div class="bg-[#313A49] text-[#CEE3E9] p-8 rounded-xl shadow-lg w-[375px] sm:w-[440px] text-center relative">
        <p class="text-[#52FFA8] text-sm uppercase tracking-[0.3em]">
            Advice #<span id="adviceID">117</span>
        </p>
        <h1 id="adviceText" class="text-2xl font-extrabold mt-4 leading-relaxed">
            "It is easy to sit up and take notice, what's difficult is getting up and taking action."
        </h1>
        <div class="flex justify-center my-6">
            <img src="divider.png" alt="Divider" class="w-40">
        </div>
        <button id="diceBtn" class="absolute left-1/2 -bottom-6 transform -translate-x-1/2 bg-[#52FFA8] p-5 rounded-full shadow-md hover:bg-green-400 transition cursor-pointer">
            <img src="dice.png" alt="Dice" class="w-10">
        </button>
    </div>
    <script src="app.js"></script>
</body>
</html>
