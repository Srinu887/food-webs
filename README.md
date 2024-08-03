<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Eats</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #ff6f61;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
        }
        .featured-dishes {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .dish {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            flex: 1 1 calc(33% - 1rem);
            margin: 0.5rem;
            text-align: center;
        }
        .dish img {
            width: 100%;
            height: auto;
            object-fit: cover;
        }
        .dish h3 {
            margin: 0.5rem 0;
            font-size: 1.5rem;
        }
        .dish p {
            padding: 0 1rem;
            color: #555;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Delicious Eats</h1>
        </div>
    </header>

    <main class="container">
        <section class="featured-dishes">
            <div class="dish">
                <img src="https://via.placeholder.com/400x300" alt="Dish 1">
                <h3>Spaghetti Carbonara</h3>
                <p>A classic Italian pasta dish with creamy sauce and pancetta.</p>
            </div>
            <div class="dish">
                <img src="https://via.placeholder.com/400x300" alt="Dish 2">
                <h3>Chicken Tacos</h3>
                <p>Delicious chicken tacos topped with fresh salsa and avocado.</p>
            </div>
            <div class="dish">
                <img src="https://via.placeholder.com/400x300" alt="Dish 3">
                <h3>Vegetarian Pizza</h3>
                <p>Loaded with fresh vegetables and a rich tomato sauce.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Delicious Eats. All rights reserved.</p>
    </footer>
</body>
</html>
