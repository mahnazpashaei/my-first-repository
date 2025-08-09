<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>باکس آیتم‌ها</title>
<style>
  body {
    font-family: sans-serif;
    direction: rtl;
    background-color: #f7f7f7;
  }
  .container {
    display: flex;
    gap: 10px;
    padding: 15px;
    border: 2px solid #ccc;
    border-radius: 10px;
    background-color: white;
    max-width: fit-content;
    margin: 20px auto;
  }
  .item {
    padding: 10px 15px;
    border-radius: 5px;
    background-color: #4CAF50;
    color: white;
    text-align: center;
    cursor: pointer;
    transition: background 0.3s;
  }
  .item:hover {
    background-color: #45a049;
  }
</style>
</head>
<body>

<div class="container">
  <div class="item">کار ۱</div>
  <div class="item">کار ۲</div>
  <div class="item">کار ۳</div>
</div>

</body>
</html>
