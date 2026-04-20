# Heba-Restaurantss
Foods 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>Heba Restaurant</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background-color: #fff8f0;
}

header {
    background-color: #ff7043;
    color: white;
    text-align: center;
    padding: 20px;
}

h1 {
    margin: 0;
}

.container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 20px;
}

.card {
    background: white;
    width: 220px;
    margin: 15px;
    border-radius: 10px;
    box-shadow: 0 0 10px #ccc;
    text-align: center;
    padding: 10px;
}

.card img {
    width: 100%;
    border-radius: 10px;
}

button {
    background-color: #ff7043;
    color: white;
    border: none;
    padding: 10px;
    margin-top: 10px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #e64a19;
}

footer {
    text-align: center;
    background: #333;
    color: white;
    padding: 10px;
}
</style>
</head>

<body>

<header>
    <h1>🍔 Heba Restaurant</h1>
    <p>أشهى الوجبات السريعة</p>
</header>

<div class="container">

    <!-- برجر -->
    <div class="card">
        <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd">
        <h3>برجر لحم</h3>
        <p>طازج ولذيذ</p>
        <button>اطلب الآن</button>
    </div>

    <!-- بيتزا -->
    <div class="card">
        <img src="https://images.unsplash.com/photo-1548365328-9f547fb0953a">
        <h3>بيتزا</h3>
        <p>جبن ذايب وشهي</p>
        <button>اطلب الآن</button>
    </div>

    <!-- بطاطس -->
    <div class="card">
        <img src="https://images.unsplash.com/photo-1541592106381-b31e9677c0e5">
        <h3>بطاطس مقلية</h3>
        <p>مقرمشة</p>
        <button>اطلب الآن</button>
    </div>

    <!-- عصير -->
    <div class="card">
        <img src="https://images.unsplash.com/photo-1571689936114-b16146f0c4c2">
        <h3>عصير برتقال</h3>
        <p>طازج ومنعش</p>
        <button>اطلب الآن</button>
    </div>

</div>

<footer>
    <p>© 2026 Heba Restaurant</p>
</footer>

</body>
</html>
