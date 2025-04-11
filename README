<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ecolife | متجر البلوفرات والتيشيرتات</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background-color: #fff;
      color: #000;
      direction: rtl;
    }

    header {
      background-color: #000;
      color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: bold;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 15px;
    }

    nav a {
      color: white;
      text-decoration: none;
    }

    .hero {
      padding: 60px 20px;
      text-align: center;
      background-color: #f4f4f4;
    }

    .products {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
      padding: 40px;
    }

    .product {
      border: 1px solid #ccc;
      padding: 15px;
      width: 250px;
      text-align: center;
      background-color: white;
      transition: transform 0.2s;
    }

    .product:hover {
      transform: scale(1.03);
    }

    .product img {
      width: 100%;
      height: auto;
    }

    button {
      background-color: black;
      color: white;
      border: none;
      padding: 10px;
      cursor: pointer;
      margin-top: 10px;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #444;
    }

    .cart {
      position: fixed;
      bottom: 20px;
      left: 20px;
      background: #000;
      color: #fff;
      padding: 15px;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #000;
      color: #fff;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <h1 class="logo">Ecolife</h1>
    <nav>
      <ul>
        <li><a href="#">الرئيسية</a></li>
        <li><a href="#">المنتجات</a></li>
        <li><a href="#">من نحن</a></li>
        <li><a href="#">تواصل معنا</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>اكتشف تشكيلتنا الجديدة</h2>
    <p>بلوفرات وتيشيرتات بتصميم أبيض وأسود أنيق</p>
  </section>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x250?text=بلوفر" alt="بلوفر Ecolife">
      <h3>بلوفر Ecolife كلاسيكي</h3>
      <p>150 ر.س</p>
      <button onclick="addToCart('بلوفر Ecolife', 150)">أضف للسلة</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x250?text=تيشيرت" alt="تيشيرت Ecolife">
      <h3>تيشيرت Ecolife أبيض</h3>
      <p>90 ر.س</p>
      <button onclick="addToCart('تيشيرت Ecolife', 90)">أضف للسلة</button>
    </div>
  </section>

  <div class="cart" id="cart">
    السلة: 0 منتج | المجموع: 0 ر.س
  </div>

  <footer>
    <p>&copy; 2025 Ecolife - جميع الحقوق محفوظة</p>
  </footer>

  <script>
    let cartCount = 0;
    let total = 0;

    function addToCart(productName, price) {
      cartCount++;
      total += price;
      document.getElementById('cart').innerText =
        `السلة: ${cartCount} منتج | المجموع: ${total} ر.س`;
      alert(`تمت إضافة "${productName}" إلى السلة!`);
    }
  </script>

</body>
</html>
