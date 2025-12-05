<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Download BanM</title>
    <!-- Added favicon -->
    <link rel="icon" type="image/webp" href="https://cdn.discordapp.com/avatars/1444379009457848432/7b04d8aeceb8520ea1bb1ee7af96c02a.webp?size=1024">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            background: #000;
            min-height: 100vh;
            color: white;
        }
        
        header {
            background: #000;
            padding: 1.5rem 2rem;
            border-bottom: 2px solid #333;
        }
        
        header h1 {
            font-size: 1.5rem;
            font-weight: bold;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }
        
        .content {
            background: #111;
            padding: 3rem;
            border: 1px solid #333;
            margin-bottom: 2rem;
        }
        
        .content h2 {
            color: white;
            margin-bottom: 1rem;
            font-size: 2rem;
        }
        
        .content p {
            color: #ccc;
            margin-bottom: 2rem;
            line-height: 1.6;
        }
        
        .download-btn {
            display: inline-block;
            background: white;
            color: black;
            padding: 1rem 3rem;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
            transition: background 0.2s, color 0.2s;
            border: 2px solid white;
        }
        
        .download-btn:hover {
            background: black;
            color: white;
        }
        
        .info-box {
            background: #111;
            padding: 2rem;
            border: 1px solid #333;
        }
        
        .info-box h3 {
            color: white;
            margin-bottom: 1rem;
            font-size: 1.3rem;
        }
        
        .info-item {
            display: flex;
            justify-content: space-between;
            padding: 0.75rem 0;
            border-bottom: 1px solid #222;
        }
        
        .info-item:last-child {
            border-bottom: none;
        }
        
        .info-label {
            color: #888;
            font-weight: bold;
        }
        
        .info-value {
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>BanM Download</h1>
    </header>
    
    <div class="container">
        <div class="content">
            <h2>BanM Download</h2>
            <p>Get the easiest ban/kick system with a discord bot for your FiveM server!</p>
            
            <a href="BanM.zip" download="BanM.zip" class="download-btn">
                Download
            </a>
        </div>
        
        <div class="info-box">
            <h3>Tutorial</h3>
            <div class="info-item">
                <span class="info-label">Instalation</span>
                <span class="info-value">Put the "[BanM]" folder into your resources folder!</span>
            </div>
            <div class="info-item">
                <span class="info-label">Ensure</span>
                <span class="info-value">Put in your server.cfg "ensure [BanM]" or start the resource by yourself!</span>
            </div>
        </div>
    </div>
</body>
</html>
