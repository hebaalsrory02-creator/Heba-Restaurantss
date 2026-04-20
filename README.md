# Heba-Restaurantss
Foods 
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Food Store</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fff8f0;
        }

        header {
            background-color: #ff7043;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background-color: #ffab91;
            padding: 10px;
            text-align: center;
        }

        nav a {
            margin: 10px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        .container {
            padding: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        .card h3 {
            margin: 10px 0;
        }

        .price {
            color: #ff7043;
            font-weight: bold;
        }

        button {
            background-color: #ff7043;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #e64a19;
        }

        footer {
            background-color: #ff7043;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1> Heba restaurant🍔</h1>
    <p>أفضل الأطعمة الطازجة</p>
</header>

<nav>
    <a href="#">الرئيسية</a>
    <a href="#">المنتجات</a>
</nav>

<div class="container">
    <h2>المنتجات</h2>

    <div class="products">

        <div class="card">

            <img src="<"https://images.unsplash.com/photo-1568901346375-23c9450c58cd">
            <h3>برجر لحم</h3>
            <p class="price">25 ريال</p>
            <button>اطلب الآن</button>
        </div>

        <div class="card">
            <img src="images/pizza.jpg" alt="بيتزا" >
            <h3>بيتزا</h3>
            <p class="price">30 ريال</p>
            <button>اطلب الآن</button>
        </div>

        <div class="card">
            <img src="images/fries.jpg" alt="بطاطس مقلية" >
            <h3>بطاطس مقلية</h3>
            <p class="price">10 ريال</p>
            <button>اطلب الآن</button>
        </div>

        <div class="card">
            <img src="images/juice.jpg" alt="عصير برتقال" >
            <h3>عصير برتقال</h3>
            <p class="price">12 ريال</p>
            <button>اطلب الآن</button>
        </div>

    </div>
</div>

<footer>
    <p> للتواصل معنا :0538629411   </p>
</footer>

</body>
</html>
