# JebesonJr
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .caption {
            font-size: 24px;
            font-weight: bold;
            opacity: 0;
            transition: opacity 2s ease-in-out;
            margin-bottom: 20px;
            color: #555;
        }

        .caption.show {
            opacity: 1;
        }
    </style>
</head>
<body>
    <div class="caption">Hello world</div>

    <h1>Hi there! 👋</h1>
    <p>I'm a <strong>Brazilian</strong> passionate about web development. With experience in <strong>HTML</strong>, I enjoy creating clean, structured, and accessible web pages. My journey in coding continues as I explore more web technologies and improve my skills every day.</p>
    <p>Feel free to connect or reach out to collaborate!</p>

    <script>
        window.onload = function() {
            document.querySelector('.caption').classList.add('show');
        }
    </script>
</body>
</html>
