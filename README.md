<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kad Jemputan Majlis</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #333;
        }
        .card {
            background: #ffffff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            max-width: 450px;
            width: 100%;
            text-align: center;
        }
        h1 {
            color: #b76e79;
            margin-bottom: 10px;
            font-size: 24px;
        }
        .names {
            font-size: 22px;
            font-weight: bold;
            color: #2c3e50;
            margin: 20px 0;
        }
        .details {
            background: #f9f9f9;
            padding: 15px;
            border-radius: 10px;
            margin: 20px 0;
            text-align: left;
            font-size: 15px;
            line-height: 1.6;
        }
        .details strong {
            color: #555;
        }
        .btn {
            display: inline-block;
            background: #27ae60;
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 10px;
            box-shadow: 0 4px 10px rgba(39, 174, 96, 0.3);
            transition: 0.3s;
        }
        .btn:hover {
            background: #219653;
        }
        .map-btn {
            background: #2980b9;
            box-shadow: 0 4px 10px rgba(41, 128, 185, 0.3);
            margin-right: 5px;
        }
        .map-btn:hover {
            background: #1f618d;
        }
        .footer {
            font-size: 12px;
            color: #888;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>Undangan Majlis</h1>
        <p>Dengan segala hormatnya menjemput Dato'/Datin/Tuan/Puan/Encik/Cik hadir ke majlis kami.</p>

        <div class="names">
            Risa Rozrita Rini<br>
            <span style="font-size: 16px; font-weight: normal; color: #7f8c8d;">&amp;</span><br>
            Isaq Albaris
        </div>

        <div class="details">
            <p>📅 <strong>Tarikh:</strong> 16 Mac 2027</p>
            <p>⏰ <strong>Masa:</strong> 10:00 Pagi - 4:00 Petang</p>
            <p>📍 <strong>Tempat:</strong> Cottage Garden Univilla</p>
        </div>

        <!-- Butang arah lokasi Google Maps -->
        <a href="https://www.google.com/maps/search/?api=1&query=Cottage+Garden+Univilla" target="_blank" class="btn map-btn">🗺️ Buka Peta</a>

        <!-- Butang Hubungi WhatsApp -->
        <a href="https://wa.me/60183226973" target="_blank" class="btn">📞 Hubungi (Baby Rini)</a>

        <div class="footer">
            Dihoskan oleh Ayie Nazrie
        </div>
    </div>

    <!-- Lagu asal dikekalkan -->
    <audio autoplay loop>
        <!-- Masukkan link audio asal anda di sini jika ada -->
    </audio>

</body>
</html>
