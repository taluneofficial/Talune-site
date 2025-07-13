# Re-create the HTML file after code execution environment reset.

html_code = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Talune | Ethereal Pop</title>
    <style>
        body {
            margin: 0;
            font-family: 'Georgia', serif;
            background: linear-gradient(to bottom, #f6f6f6, #d6cfe6);
            color: #2d2d2d;
        }

        header {
            background: #a487a9;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
            font-style: italic;
        }

        .section {
            padding: 40px 20px;
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        .section h2 {
            margin-bottom: 20px;
            font-size: 1.8em;
        }

        .links a {
            display: inline-block;
            margin: 10px 15px;
            padding: 10px 20px;
            background-color: #a487a9;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .newsletter input[type="email"] {
            padding: 10px;
            width: 60%;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .newsletter button {
            padding: 10px 20px;
            background-color: #2d2d2d;
            color: white;
            border: none;
            border-radius: 5px;
            margin-left: 10px;
        }

        footer {
            background-color: #2d2d2d;
            color: white;
            text-align: center;
            padding: 20px 10px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

<header>
    <h1>TALUNE</h1>
    <p>ethereal pop from the other side</p>
    <p>⋆ healing through sound ⋆ new music soon ⋆</p>
</header>

<div class="section">
    <h2>About</h2>
    <p>
        Talune crafts soft, celestial pop infused with spiritual energy and feminine healing.<br>
        Her sound lives between worlds: dreamlike melodies, intimate lyrics, and sonic moonlight.<br><br>
        New music coming soon — follow the journey.
    </p>
</div>

<div class="section links">
    <h2>Listen & Connect</h2>
    <a href="#" target="_blank">Spotify</a>
    <a href="#" target="_blank">YouTube</a>
    <a href="#" target="_blank">Instagram</a>
    <a href="#" target="_blank">TikTok</a>
</div>

<div class="section newsletter">
    <h2>Stay in the Loop</h2>
    <p>Want updates from the other side? Drop your email below ✨</p>
    <input type="email" placeholder="Your email">
    <button>Subscribe</button>
</div>

<footer>
    © 2025 Talune. All rights reserved. <br>
    designed with love + moonlight
</footer>

</body>
</html>
"""

# Save the HTML content to a file
file_path = "/mnt/data/talune_landing_page.html"
with open(file_path, "w") as f:
    f.write(html_code)

file_path
