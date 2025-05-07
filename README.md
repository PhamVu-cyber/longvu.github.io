<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Cửa hàng Mini</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Cửa hàng Mini</h1>
    <nav>
      <a href="#">Trang chủ</a>
      <a href="#">Sản phẩm</a>
      <a href="#">Liên hệ</a>
    </nav>
  </header>

  <section class="products">
    <div class="product">
      <img src="img/sp1.jpg" alt="Sản phẩm 1">
      <h2>Sản phẩm 1</h2>
      <p>Giá: 150.000₫</p>
      <button>Mua ngay</button>
    </div>
    <div class="product">
      <img src="img/sp2.jpg" alt="Sản phẩm 2">
      <h2>Sản phẩm 2</h2>
      <p>Giá: 230.000₫</p>
      <button>Mua ngay</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Cửa hàng Mini</p>
  </footer>
</body>
</html>
 body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background: #0077cc;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  margin: 0 10px;
  color: white;
  text-decoration: none;
}

.products {
  display: flex;
  justify-content: center;
  padding: 20px;
  gap: 20px;
  flex-wrap: wrap;
}

.product {
  border: 1px solid #ccc;
  padding: 10px;
  width: 200px;
  text-align: center;
}

.product img {
  width: 100%;
  height: auto;
}

button {
  background: green;
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 10px;
  background: #f1f1f1;
}   
  
