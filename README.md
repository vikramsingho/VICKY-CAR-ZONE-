#                VICKY-CAR-ZONE-
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Car Booking</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background: url('https://wallpapercave.com/wp/wp4676584.jpg') no-repeat center center/cover;
      color: white;
      overflow-x: hidden;
    }
    header, footer {
      background: rgba(0, 0, 0, 0.7);
      padding: 10px;
      text-align: center;
      border: 2px solid gold;
      border-radius: 10px;
      margin: 10px;
    }
    .floating-car {
      width: 100%;
      height: 200px;
      background: url('https://pngimg.com/uploads/lamborghini/lamborghini_PNG10607.png') no-repeat center;
      background-size: contain;
      animation: float 4s ease-in-out infinite;
    }
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
      100% { transform: translateY(0); }
    }
    .card {
      background: rgba(0, 0, 0, 0.6);
      margin: 10px;
      padding: 20px;
      border: 2px solid gold;
      border-radius: 15px;
      box-shadow: 0 0 10px gold;
    }
    select, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 8px;
      border: none;
      font-size: 16px;
    }
    .contact {
      position: fixed;
      bottom: 80px;
      right: 10px;
      background: gold;
      padding: 10px;
      border-radius: 10px;
      color: black;
      font-weight: bold;
    }
    .floating-box {
      position: fixed;
      top: 20px;
      left: 20px;
      background: rgba(0, 0, 0, 0.8);
      padding: 10px;
      border: 2px solid gold;
      border-radius: 15px;
      color: white;
    }
    a { color: white; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    ⚠️ WARNING: MERE GHAR SE CAR JITNE KM NIKALEGI USKE HISAB SE KM PE PAISA DENA HOGA. ALL TALLS AAPKO DENE HONGE
  </header>  <div class="floating-car"></div>  <div class="card">
    <h2>Book Your Car</h2>
    <label for="car">Select Car:</label>
    <select id="car">
      <option value="ertiga">Ertiga</option>
    </select><label for="fuel">Select Fuel Type:</label>
<select id="fuel">
  <option value="petrol">Petrol</option>
  <option value="cng">CNG</option>
</select>

<button onclick="window.location.href='https://wa.me/916375961963?text=Hi%2C%20I%20want%20to%20book%20a%20car.'">BOOK NOW</button>

  </div>  <div class="contact">
    <div>WhatsApp</div>
    <div>Instagram</div>
    <div><a href="https://t.me/viicky_rajgarh_007" target="_blank">Telegram</a></div>
  </div>  <div class="floating-box">
    WEBSITE BNWANI H TO BHI CONTACT KRO<br>
    PRICE: 2.5k SE STARTING
  </div>  <footer>
    ⚠️ WARNING: ONLY INSTANT PAYMENT WAALE AANA WARNA MAT AANA
  </footer>
</body>
</html>
