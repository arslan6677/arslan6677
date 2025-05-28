<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>I.S STRONG GROUT AND TILE BOND</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 20px; background-color: #f9f9f9; }
    header { text-align: center; }
    img.logo { width: 150px; }
    img.product { width: 250px; display: block; margin: 20px auto; border: 1px solid #ccc; border-radius: 8px; }
    h1, h2 { color: #800000; }
    .section { margin-top: 30px; }
    form { background: #fff; padding: 20px; border-radius: 10px; max-width: 400px; margin: auto; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    label, select, button { display: block; width: 100%; margin-top: 10px; }
    button { padding: 10px; background: #800000; color: #fff; border: none; border-radius: 5px; cursor: pointer; }
    button:hover { background: #a00000; }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="I.S STRONG Logo" class="logo">
    <h1>I.S STRONG GROUT AND TILE BOND</h1>
    <p>Premium Grade Tile Adhesive - Strong, Durable, Trusted</p>
  </header>  <section class="section">
    <h2>Product Overview</h2>
    <ul>
      <li>✔️ Strong Bond</li>
      <li>✔️ Long-lasting Grip</li>
      <li>✔️ Trusted by Professionals</li>
      <li>✔️ Ideal for Residential & Commercial Projects</li>
    </ul>
    <img src="bag.jpg" alt="Product Bag" class="product">
  </section>  <section class="section">
    <h2>Available Packaging & Price</h2>
    <ul>
      <li>20 KG — Rs. 550</li>
      <li>40 KG — Rs. 1050</li>
    </ul>
    <p>Nationwide delivery available across Pakistan!</p>
  </section>  <section class="section">
    <h2>Place Your Order</h2>
    <form id="orderForm">
      <label for="product">Choose Product:</label>
      <select id="product">
        <option value="20kg">20 KG - Rs. 550</option>
        <option value="40kg">40 KG - Rs. 1050</option>
      </select><label for="quantity">Quantity:</label>
  <select id="quantity">
    <option value="1">1</option>
    <option value="2">2</option>
    <option value="3">3</option>
    <option value="4">4</option>
    <option value="5">5</option>
    <option value="6">6</option>
    <option value="7">7</option>
    <option value="8">8</option>
    <option value="9">9</option>
    <option value="10">10</option>
  </select>

  <button type="button" onclick="sendWhatsApp()">Order Now on WhatsApp</button>
</form>

  </section>  <section class="section">
    <h2>Contact Information</h2>
    <p>📱 0300 0253838</p>
    <p>📧 muhmmedarslan204@gmail.com</p>
    <p>📍 Faisalabad, Pakistan</p>
  </section>  <script>
    function sendWhatsApp() {
      const product = document.getElementById("product").value;
      const quantity = document.getElementById("quantity").value;
      const message = `Hello! I want to order ${quantity} bag(s) of ${product} tile bond.`;
      const phoneNumber = "923000253838";
      window.open(`https://wa.me/${phoneNumber}?text=${encodeURIComponent(message)}`);
    }
  </script></body>
</html>