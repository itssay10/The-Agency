<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galería de Bots - JanitorAI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 16px;
            width: 80%;
            margin: 20px;
        }
        .gallery-item {
            position: relative;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .gallery-item img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease;
        }
        .gallery-item img:hover {
            transform: scale(1.1);
        }
        .gallery-item a {
            display: block;
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
            color: white;
            text-align: center;
            line-height: 100%;
            text-decoration: none;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        .gallery-item:hover a {
            opacity: 1;
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div class="gallery-item">
            <img src="image1.jpg" alt="Bot 1">
            <a href="https://enlace1.com" target="_blank">Ver más</a>
        </div>
        <div class="gallery-item">
            <img src="image2.jpg" alt="Bot 2">
            <a href="https://enlace2.com" target="_blank">Ver más</a>
        </div>
        <!-- Agrega más imágenes aquí -->
    </div>
</body>
</html>
