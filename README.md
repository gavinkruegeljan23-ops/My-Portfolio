# My-Portfolio
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, serif;
            width: 1024px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 64pt;
            margin-bottom: 20px;
            text-shadow:
                0 0 6px #E033FF,
                0 0 12px #E033FF,
                0 0 24px #E033FF;
        }
        .portfolio-box {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        figure {
            width: 200px;
            text-align: center;
        }
        figure img {
            width: 200px;
            height: auto;
            border: 1px solid #ccc;
            box-shadow: 2px 2px 6px rgba(0,0,0,0.2);
        }
        figcaption {
            font-size: 12pt;
            margin-top: 8px;
        }
    </style>
</head>

<body>

<h1>My Portfolio</h1>

<div class="portfolio-box">
    <!-- Drawing 1 -->
    <figure>
        <a href="images/alley-poster-full.png" target="_blank">
            <img src="images/alley-poster-thumb.png" alt="The Alley Movie Poster">
        </a>
        <figcaption>The Alley Movie Poster</figcaption>
    </figure>
    <!-- Drawing 2 -->
    <figure>
        <a href="images/springers-tour-full.png" target="_blank">
            <img src="images/springers-tour-thumb.png" alt="Springers World Tour Poster">
        </a>
        <figcaption>The Springers World Tour Poster</figcaption>
    </figure>
    <!-- Drawing 3 -->
    <figure>
        <a href="images/self-portrait-full.jpg" target="_blank">
            <img src="images/self-portrait-thumb.jpg" alt="Self Portrait Illustrator">
        </a>
        <figcaption>Self Drawing on Illustrator</figcaption>
    </figure>\
    
</div>

</body>
</html>
