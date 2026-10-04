<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bull Brock</title>

<style>
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:#111;
  color:white;
  text-align:center;
}
header{
  background:#d4af37;
  color:#111;
  padding:25px 15px;
}
h1{
  margin:0;
  font-size:36px;
}
.container{
  max-width:600px;
  margin:auto;
  padding:25px 15px;
}
.card{
  background:#1d1d1d;
  border-radius:15px;
  padding:25px;
  margin:20px 0;
  box-shadow:0 4px 15px #000;
}
button{
  width:100%;
  padding:15px;
  border:0;
  border-radius:10px;
  background:#d4af37;
  color:#111;
  font-size:18px;
  font-weight:bold;
  margin-top:15px;
}
button:active{
  transform:scale(.98);
}
footer{
  padding:25px;
  color:#aaa;
}
</style>
</head>

<body>

<header>
  <h1>🐂 BULL BROCK</h1>
  <p>ยินดีต้อนรับสู่ Bull Brock</p>
</header>

<div class="container">

  <div class="card">
    <h2>สินค้า Bull Brock</h2>
    <p>เว็บไซต์อย่างเป็นทางการ</p>
    <button onclick="order()">สั่งซื้อสินค้า</button>
  </div>

  <div class="card">
    <h2>ติดต่อเรา</h2>
    <p>LINE: bull1996z</p>
    <button onclick="contact()">ติดต่อผ่าน LINE</button>
  </div>

</div>

<footer>
  © 2026 Bull Brock
</footer>

<script>
function order(){
  window.open("https://line.me/ti/p/~bull1996z","_blank");
}

function contact(){
  window.open("https://line.me/ti/p/~bull1996z","_blank");
}
</script>

</body>
</html>
