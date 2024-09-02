<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video in Endlosschleife</title>
    <style>
        /* Vollbildvideo */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
        }

        video {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 100%;
            height: 100%;
            transform: translate(-50%, -50%);
            object-fit: contain; /* Wichtige Eigenschaft, damit das gesamte Video sichtbar ist */
        }
    </style>
</head>
<body>
    <video src="SaveTube.App-Schneller und entspannter durch die Sicherheitskontrolle (1).mp4" autoplay loop muted></video>
</body>
</html>
