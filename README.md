
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Romantic Photo Grid</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
        }
        h1 {
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
        .photo-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            max-width: 600px;
            position: relative;
        }
        .photo-item {
            position: relative;
        }
        .photo-item img {
            width: 100%;
            border-radius: 8px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }
        .photo-item img:hover {
            transform: scale(1.05);
        }
        .heart-icon {
            position: absolute;
            top: 10px;
            right: 10px;
            color: #ff6b6b;
            font-size: 1.5rem;
            opacity: 0.8;
            transition: transform 0.3s ease, opacity 0.3s ease;
        }
        .photo-item:hover .heart-icon {
            transform: scale(1.2);
            opacity: 1;
        }
    </style>
</head>
<body>
    <h1>Photo Memories</h1>
    <div class="photo-grid">
        <div class="photo-item">
            <img src="i.jpg" alt="Photo 1">
            <div class="heart-icon">❤️</div>
        </div>
        <div class="photo-item">
            <img src="o.jpg" alt="Photo 2">
            <div class="heart-icon">❤️</div>
        </div>
        <div class="photo-item">
            <img src="e.jpg" alt="Photo 3">
            <div class="heart-icon">❤️</div>
        </div>
        <div class="photo-item">
            <img src="h.jpg" alt="Photo 4">
            <div class="heart-icon">❤️</div>
        </div>
        <div class="photo-item">
            <img src="m.jpg" alt="Photo 5">
            <div class="heart-icon">❤️</div>
        </div>
        <div class="photo-item">
            <img src="t.jpg" alt="Photo 6">
            <div class="heart-icon">❤️</div>
        </div>
    </div>
</body>
</html>
