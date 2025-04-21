<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DripHaven - Kup Teraz</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #111;
      color: white;
    }
    header {
      padding: 40px;
    }
    h1 {
      color: #00ffff;
    }
    .products {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 40px;
    }
    .product {
      background: #222;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      text-align: left;
    }
    .price {
      font-size: 1.2em;
      color: #ff0;
      font-weight: bold;
    }
    .paypal-btn {
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>DripHaven</h1>
    <p>Click to purchase the products below, and you will receive links via email!</p>
  </header>

  <div class="products">
    <!-- AirPods Max -->
    <div class="product">
      <h3>AirPods Max</h3>
      <p class="price">Cena: 10$</p>
      <!-- PayPal button -->
      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
        <input type="hidden" name="cmd" value="_s-xclick" />
        <input type="hidden" name="hosted_button_id" value="TWOJ_ID_PRZYCISKU_AIRPODS" />
        <input type="submit" value="Kup teraz z PayPal" class="paypal-btn" />
      </form>
    </div>

    <!-- AirPods 3 -->
    <div class="product">
      <h3>AirPods 3</h3>
      <p class="price">Cena: 10$</p>
      <!-- PayPal button -->
      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
        <input type="hidden" name="cmd" value="_s-xclick" />
        <input type="hidden" name="hosted_button_id" value="TWOJ_ID_PRZYCISKU_AIRPODS_3" />
        <input type="submit" value="Kup teraz z PayPal" class="paypal-btn" />
      </form>
    </div>

    <!-- Yeezy Slide -->
    <div class="product">
      <h3>Yeezy Slide</h3>
      <p class="price">Cena: 10$</p>
      <!-- PayPal button -->
      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
        <input type="hidden" name="cmd" value="_s-xclick" />
        <input type="hidden" name="hosted_button_id" value="TWOJ_ID_PRZYCISKU_YEEZY" />
        <input type="submit" value="Kup teraz z PayPal" class="paypal-btn" />
      </form>
    </div>
  </div>

  <!-- Link wysłany po zakupie -->
  <script type="text/javascript">
    // Po dokonaniu płatności PayPal, użytkownik może otrzymać e-mail
    // z linkami, które Ty przygotujesz (używając np. EmailJS lub innego systemu do wysyłki).
    // Implementacja wysyłania emaila po zakończeniu transakcji będzie wymagała backendu
    // lub użycia narzędzi takich jak EmailJS (do konfiguracji API).

    // Możesz zintegrować to z EmailJS, aby wysłać e-mail z linkami po zakończeniu płatności.
  </script>

</body>
</html>

