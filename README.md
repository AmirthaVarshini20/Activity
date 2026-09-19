# Activity

# PROGRAM:
```
<html>
<head>
    <title>Product Cards</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3e8ff;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 30px;
            min-height: 85vh;
        }

        .product-card {
            width: 300px;
            background-color: #ffffff;
            text-align: center;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 4px 10px #b39ddb;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 25px #7e57c2;
        }

        .product-card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .product-card:hover img {
            transform: scale(1.05);
        }

        .product-card h2 {
            margin: 15px 0 10px;
            color: #512da8;
        }

        .product-card p {
            color: #555;
            line-height: 1.5;
        }

        .price {
            font-size: 22px;
            font-weight: bold;
            color: #00897b;
            margin: 15px 0;
        }

        .cart-btn {
            background-color: #6a1b9a;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 6px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .product-card:hover .cart-btn {
            background-color: #00897b;
        }

        footer {
            background-color: #4527a0;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>

<body>

    <div class="container">

        <!-- Running Shoes -->
        <div class="product-card">

            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?auto=format&fit=crop&w=600&q=80"
                 alt="Running Shoes">

            <h2>Running Shoes</h2>

            <p>
                Comfortable and stylish running shoes
                designed for daily workouts and sports.
            </p>

            <div class="price">
                ₹2,799
            </div>

            <button class="cart-btn">
                Add to Cart
            </button>

        </div>


        <!-- Travel Backpack -->
        <div class="product-card">

            <img src="https://images.unsplash.com/photo-1553062407-98eeb64c6a62?auto=format&fit=crop&w=600&q=80"
                 alt="Travel Backpack">

            <h2>Travel Backpack</h2>

            <p>
                Spacious and durable backpack perfect for
                travel, college, and everyday use.
            </p>

            <div class="price">
                ₹1,499
            </div>

            <button class="cart-btn">
                Add to Cart
            </button>

        </div>

    </div>

    <footer>
        Learner Name: Amirtha Varshini V<br>
        Register Number: 212224040021
    </footer>

</body>
</html>
```
# OUTPUT:

<img width="1917" height="1082" alt="image" src="https://github.com/user-attachments/assets/5b0b060b-a998-4c07-be21-56fe6555d03a" />
