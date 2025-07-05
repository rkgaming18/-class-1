<!DOCTYPE html>
<html lang="as">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>প্ৰথম শ্ৰেণী | অসীম Library</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #ffffff;
      color: #222;
    }

    /* Header */
    .header {
      display: flex;
      align-items: center;
      padding: 15px 20px;
      background-color: #f8f8f8;
      border-bottom: 1px solid #ddd;
    }

    .logo {
      height: 50px;
      margin-right: 15px;
    }

    .title {
      font-size: 20px;
      font-weight: bold;
      color: #d32f2f;
    }

    /* Class Name */
    .class-title {
      text-align: center;
      margin-top: 30px;
      font-size: 24px;
      color: #2c3e50;
    }

    /* Subject List */
    .subject-section {
      max-width: 500px;
      margin: 40px auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 12px;
      background: #f9f9f9;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
    }

    .subject-section h2 {
      text-align: center;
      color: #4caf50;
      margin-bottom: 20px;
    }

    .subject-list {
      display: flex;
      flex-direction: column;
      gap: 12px;
      align-items: center;
    }

    .subject-list a {
      display: inline-block;
      width: 80%;
      text-align: center;
      padding: 10px 20px;
      background-color: #0077cc;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 18px;
      transition: background-color 0.3s;
    }

    .subject-list a:hover {
      background-color: #005fa3;
    }

    @media (max-width: 500px) {
      .subject-list a {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header class="header">
    <img src="asim-logo.png" alt="অসীম Library Logo" class="logo" />
    <div class="title">অসীম Library</div>
  </header>

  <!-- Class Name -->
  <div class="class-title">📘 প্ৰথম শ্ৰেণী</div>

  <!-- Subject Section -->
  <section class="subject-section">
    <h2>📚 বিষয়</h2>
    <div class="subject-list">
      <a href="assamese.html">অসমীয়া</a>
      <a href="english.html">ইংৰাজী</a>
      <a href="math.html">গণিত</a>
    </div>
  </section>

</body>
</html>
