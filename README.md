# curhatyuk-.io

  <meta charset="UTF-8">
<head>
  
      font-family: 'Segoe UI', sans-serif;
      background: url('Bg.web.jpg') no-repeat center center fixed;
      background-size: cover;
      padding: 30px;
      color: #333;
    }

    .container {
      max-width: 600px;
      margin: auto;
      background: rgba(255, 246, 246, 0.92); /* semi-transparan */
      padding: 25px;
      border-radius: 16px;
      box-shadow: 0 0 25px rgba(0,0,0,0.15);
    }

    h1 {
      color: #d6336c;
      text-align: center;
    }

    p {
      line-height: 1.7;
      font-size: 16px;
    }

    .prompt {
      margin-top: 30px;
      font-weight: bold;
      font-size: 17px;
      color: #444;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 15px;
      background-color: #fff;
    }

    button {
      padding: 12px 20px;
      background-color: #ff6f91;
      color: white;
      font-weight: bold;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    button:hover {
      background-color: #e85974;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Curhat Yuk 💬</h1>
    
    <p>Hai,</p>

    <p>Aku cuma mau bilang... kadang hidup tuh nggak gampang. Kita sering tahan semuanya sendiri, sambil pura-pura kuat. Tapi kamu nggak harus gitu terus. Kamu boleh banget cerita.</p>

    <p>Aku di sini, dan aku dengerin.</p>

    <p class="prompt">Kalau kamu nyaman, boleh isi ini ya:</p>

    <form action="https://formspree.io/f/xldjkbee" method="POST">
      <label for="name">Namamu (boleh anonim):</label>
      <input type="text" name="name" placeholder="Misal: Temanmu / Anonim">

      <label for="message">Apa yang sedang kamu rasakan akhir-akhir ini?</label>
      <textarea name="message" placeholder="Tulis sejujurnya, nggak akan dihakimi..." required></textarea>

      <button type="submit">Kirim Cerita 💌</button>
    </form>
  </div>

</body>
</html>
