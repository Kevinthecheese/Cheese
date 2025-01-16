<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>南方豐收餐廳 - Southern Harvest Kitchen</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f5f0;
            color: #333;
        }
        header {
            background-color: #d4a373;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }
        .menu-section {
            padding: 20px;
            margin: 20px auto;
            max-width: 900px;
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .menu-section h2 {
            text-align: center;
            color: #8a5a44;
            margin-bottom: 15px;
        }
        .menu-item {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            border-bottom: 1px solid #ddd;
            padding-bottom: 15px;
        }
        .menu-item img {
            width: 100px;
            height: 100px;
            object-fit: cover;
            margin-right: 20px;
            border-radius: 8px;
        }
        .menu-item .info {
            flex: 1;
        }
        .menu-item .info h3 {
            margin: 0;
            font-size: 1.2em;
            color: #333;
        }
        .menu-item .info p {
            margin: 5px 0;
            color: #666;
        }
        .menu-item .price {
            font-weight: bold;
            color: #8a5a44;
        }
    </style>
</head>
<body>
    <header>
        <h1>南方豐收餐廳</h1>
        <p>Southern Harvest Kitchen</p>
    </header>

    <section class="menu-section">
        <h2>前菜 Appetizers</h2>
        <div class="menu-item">
            <img src="https://source.unsplash.com/100x100/?bread" alt="玉米麵包">
            <div class="info">
                <h3>Rustic Cornbread with Honey Butter</h3>
                <p>鄉村玉米麵包佐蜂蜜奶油</p>
            </div>
            <span class="price">NT$150</span>
        </div>
        <div class="menu-item">
            <img src="https://source.unsplash.com/100x100/?slider" alt="豬肉小漢堡">
            <div class="info">
                <h3>BBQ Pulled Pork Sliders</h3>
                <p>燒烤豬肉小漢堡</p>
            </div>
            <span class="price">NT$200</span>
        </div>
    </section>

    <section class="menu-section">
        <h2>主餐 Main Courses</h2>
        <div class="menu-item">
            <img src="https://source.unsplash.com/100x100/?steak" alt="鹿肉排">
            <div class="info">
                <h3>Herb-Crusted Venison Loin</h3>
                <p>香草脆皮鹿肉排</p>
            </div>
            <span class="price">NT$720</span>
        </div>
    </section>

    <section class="menu-section">
        <h2>飲品 Drinks</h2>
        <div class="menu-item">
            <img src="https://source.unsplash.com/100x100/?martini" alt="馬丁尼">
            <div class="info">
                <h3>Classic Martini (Gin/Vodka)</h3>
                <p>經典馬丁尼（琴酒/伏特加）</p>
            </div>
            <span class="price">NT$260</span>
        </div>
    </section>
</body>
</html>
