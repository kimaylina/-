# 
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adopción de Mascotas - Little pet's</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
        }
        header {
            background-color: #ff6f61;
            color: white;
            text-align: center;
            padding: 25px;
        }
        .container {
            width: 90%;
            margin: auto;
        }
        .pet-card {
            background-color: white;
            width: 250px;
            margin: 15px;
            float: left;
            border-radius: 8px;
            overflow: hidden;
            border: 1px solid #ccc;
        }
        .pet-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .pet-info {
            padding: 15px;
            text-align: center;
        }
        .adopt-btn {
            background-color: #28a745;
            color: white;
            padding: 10px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
        }

        /* FORMULARIO */
        .form-section {
            clear: both;
            background-color: white;
            padding: 25px;
            margin-top: 40px;
            border-radius: 8px;
        }
        .form-section h2 {
            text-align: center;
            color: #333;
        }
        form {
            max-width: 500px;
            margin: auto;
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }
        .submit-btn {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 12px;
            width: 100%;
            border-radius: 5px;
            cursor: pointer;
        }

        /* CUPÓN */
        .coupon-section {
            text-align: center;
            background-color: #fff3cd;
            padding: 30px;
            margin-top: 30px;
        }
        .coupon-btn {
            background-color: #dc3545;
            color: white;
            border: none;
            padding: 15px 25px;
            font-size: 18px;
            border-radius: 8px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>¡Adopta una Mascota!</h1>
    <p>Adopto una mascota y dale una familia❤️</p>
</header>

<div class="container">

    
    <div class="PERRRO SALCHICHA">
        <img src="https://estaticos-cdn.prensaiberica.es/clip/92ffe9bd-c6b3-4908-97c6-cff3dca8eb99_16-9-aspect-ratio_default_1238471.jpg" alt="Perrito">
        <div class="pet-info">
            <h3>Max</h3>
            <p>2 años</p>
            <a href="#" class="adopt-btn">Adoptar</a>
        </div>
    </div>

    <!-- MASCOTA 2 -->
    <div class="GATO EGIPCIO">https
        <img src="https://blog.vetjg.com/wp-content/uploads/2020/03/sp-768x1024.jpg" alt="Gato">
        <div class="pet-info">
            <h3>Luna</h3>
            <p>9 MESES </p>
            <a href="#" class="adopt-btn">Adoptar</a>
        </div>
    </div>

    <!-- MASCOTA 3 -->
    <div class="PERIQUITOS">
        <img src="https://thumbs.dreamstime.com/b/dos-aves-amorosas-en-una-jaula-185829749.jpg" alt="periquitos">
        <div class="pet-info">
            <h3>CHARLY Y NIKI</h3>
            <p>1 año</p>
            <a href="#" class="adopt-btn">Adoptar</a>
        </div>
    </div>

    
    <div class="PERRO CHIHUAWAWA">
        <img src="https://www.shutterstock.com/image-photo/deer-head-chihuahua-outdoors-during-600nw-1478121212.jpg" alt="perro">
        <div class="pet-info">
            <h3>MARLEY</h3>
            <p>1 año</p>
            <a href="#" class="adopt-btn">Adoptar</a>
        </div>
    </div>

</div>


<div class="form-section">
    <h2>Formulario de Adopción</h2>
    <form>
        <input type="text" placeholder="Nombre de la mascota a adoptar" required>
        <input type="text" placeholder="Tu nombre completo" required>
        <input type="number" placeholder="Tu edad" required>
        <input type="text" placeholder="¿Dónde vives?" required>
        <input type="tel" placeholder="Número de teléfono" required>
        <button type="submit" class="submit-btn">Enviar solicitud</button>
    </form>
</div>


<div class="coupon-section">
    <p>Promoción especial por Navidad</p>
    <button class="coupon-btn">🎁🎄20% de descuento🎄🎁</button>
</div>

<footer>
    <p>&copy; 2025 segurity pet</p>
</footer>

</body>
</html>
