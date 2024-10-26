
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Longganisa Recipe</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f5e4d7;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #d2691e;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        h2 {
            color: #8b4513;
            margin-top: 30px;
            border-bottom: 2px solid #8b4513;
            display: inline-block;
            padding-bottom: 5px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }
        ul {
            margin: 15px 0;
            padding-left: 20px;
        }
        li {
            margin: 5px 0;
        }
        .instructions {
            margin-top: 20px;
        }
        ol {
            counter-reset: step;
        }
        ol li {
            counter-increment: step;
            margin-bottom: 15px;
            font-size: 1.1rem;
            position: relative;
            padding-left: 35px;
        }
        ol li::before {
            content: counter(step) ".";
            position: absolute;
            left: 0;
            top: 0;
            color: #d2691e;
            font-size: 1.5rem;
            font-weight: bold;
        }
        footer {
            margin-top: 30px;
            text-align: center;
            font-size: 0.9rem;
            color: #555;
        }
        .note {
            background-color: #ffe4b5;
            border-left: 6px solid #d2691e;
            padding: 10px;
            margin-top: 10px;
        }
        .emoji {
            font-size: 1.2rem;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>🍖 Longganisa Recipe</h1>
    </header>
    
    <div class="container">
        <section>
            <h2>✨ What is Longganisa?</h2>
            <p>Longganisa is a beloved Filipino sausage, known for its garlicky and sweet flavor. There are many regional variations, but this recipe offers a classic, savory-sweet style that pairs perfectly with garlic fried rice and a fried egg. A breakfast favorite also known as <strong>“Longsilog.”</strong> 🇵🇭</p>
        </section>

        <section>
            <h2>🛒 Ingredients</h2>
            <ul>
                <li>1 kg ground pork (with fat)</li>
                <li>5 cloves garlic, minced 🧄</li>
                <li>1/4 cup brown sugar 🍬</li>
                <li>2 tablespoons soy sauce</li>
                <li>1 tablespoon vinegar</li>
                <li>1 teaspoon salt</li>
                <li>1/2 teaspoon black pepper</li>
                <li>1/2 teaspoon paprika 🌶️</li>
                <li>1/2 teaspoon crushed red pepper (optional)</li>
                <li>2 tablespoons water</li>
                <li>Sausage casings (optional)</li>
            </ul>
        </section>

        <section class="instructions">
            <h2>👩‍🍳 Instructions</h2>
            <ol>
                <li>In a large bowl, mix ground pork, garlic, brown sugar, soy sauce, vinegar, salt, black pepper, paprika, and red pepper (if using).</li>
                <li>Add water to the mixture and stir until well combined and sticky.</li>
                <li>If using casings, soak them in water and stuff with the mixture. Twist into 6-inch links.</li>
                <li>Alternatively, shape the mixture into small patties.</li>
                <li>Cover and refrigerate for at least 4 hours (or overnight) for the flavors to develop.</li>
                <li>Grill or pan-fry over medium heat until golden brown and fully cooked — about 8-10 minutes for links, 4-5 minutes per side for patties.</li>
                <li>Serve hot with garlic rice, a fried egg, and dipping sauces like vinegar with chili. Enjoy! 🍽️</li>
            </ol>
        </section>

        <div class="note">
            <p><strong>Tip:</strong> For a more authentic flavor, use pork with some fat. The fat makes the sausage juicier and more flavorful!</p>
        </div>
    </div>

    <footer>
        <p>Made with ❤️ in the Philippines | © 2024 Longganisa Delights</p>
    </footer>
</body>
</html>
