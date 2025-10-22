<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nitish Agrawal – CA Finalist</title>
  <style>
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #f9fafb;
      color: #333;
    }

    .container {
      max-width: 480px;
      margin: 40px auto;
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      padding: 24px;
      animation: fadeInUp 0.8s ease-out both;
    }

    .profile {
      display: flex;
      justify-content: center;
      margin-bottom: 16px;
      animation: fadeInUp 1s ease-out both;
    }

    .profile img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      object-fit: cover;
      box-shadow: 0 3px 8px rgba(0,0,0,0.2);
    }

    h1 {
      text-align: center;
      font-size: 2rem;
      margin: 10px 0 4px;
    }

    p.subtitle {
      text-align: center;
      color: #555;
      margin-top: 0;
      font-weight: 500;
    }

    .section {
      margin-top: 28px;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s ease forwards;
    }

    .section:nth-child(3) { animation-delay: 0.4s; }
    .section:nth-child(4) { animation-delay: 0.8s; }
    .section:nth-child(5) { animation-delay: 1.2s; }
    .section:nth-child(6) { animation-delay: 1.6s; }

    a {
      color: #0073e6;
      text-decoration: none;
    }

    .btn {
      display: inline-block;
      margin: 8px 6px 0 0;
      padding: 10px 18px;
      text-decoration: none;
      color: #fff;
      background: #0073e6;
      border-radius: 6px;
      font-size: 0.95rem;
      transition: background 0.3s ease;
    }

    .btn:hover { background: #005bb5; }
    .btn-whatsapp { background: #25D366; }
    .btn-instagram { background: #E1306C; }
    .btn-instagram:hover { background: #C92D61; }

    ul {
      list-style: none;
      padding: 0;
      margin: 8px 0;
    }

    li::before {
      content: "• ";
      color: #0073e6;
    }

    .qr-section {
      text-align: center;
      margin-top: 28px;
      animation: fadeInUp 2s ease-out both;
    }

    .qr-section img {
      width: 160px;
      border-radius: 12px;
      margin-top: 10px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }

    footer {
      text-align: center;
      color: #777;
      font-size: 0.85rem;
      margin-top: 32px;
      animation: fadeInUp 2.2s ease-out both;
    }
  </style>
</head>
<body>
  <div class="container">

    <div class="profile">
  <img src="profile.jpg" alt="Nitish Agrawal" style="width:200px; height:200px;">
</div>

    <h1>Nitish Agrawal</h1>
    <p class="subtitle">CA Finalist</p>

    <div class="section">
      <h2>Contact</h2>
      <p>
        📞 <a href="tel:+917828780780">+91 78287 80780</a><br>
        ✉️ <a href="mailto:nitishagrawal304@gmail.com">nitishagrawal304@gmail.com</a><br>
        📍 Baloda, Saraipali, Mahasamund, Chhattisgarh 493558
      </p>

      <a href="https://wa.me/917828780780?text=Hello%20Nitish%20Agrawal" class="btn btn-whatsapp">WhatsApp</a>
      <a href="nitishagrawal.vcf" class="btn">Download vCard</a>
      <a href="https://instagram.com/nattu304" class="btn btn-instagram">Instagram</a>
    </div>

    <div class="section">
      <h2>About Me</h2>
      <p>
        I’m a CA Finalist passionate about taxation, auditing, and helping businesses stay compliant while growing confidently.
      </p>
    </div>

    <div class="section">
      <h2>Business Ventures</h2>
      <ul>
        <li>Poonam Kapda Dukan</li>
        <li>Poonam Bartan Dukan</li>
        <li>Poonam Krishi Sewa Kendra</li>
      </ul>
    </div>

    <div class="qr-section">
      <h2>Scan for UPI Payment</h2>
      <img src="PHONEPAYQR.JPG" alt="PhonePe UPI QR Code">
    </div>

    <footer>
      © 2025 Nitish Agrawal
    </footer>
  </div>
</body>
</html>
