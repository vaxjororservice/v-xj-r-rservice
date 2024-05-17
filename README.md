<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Växjö Rörservice AB</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4; /* Ljusgrå bakgrund för en ren look */
        }
        header {
            background-color: #fffefe; /* Blå färg för header och logotyp */
            color: rgb(9, 150, 33);
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #055719; /* Mörkgrå färg för navigering */
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #0c6319;
            color: white;
        }
        .container {
            padding: 20px;
        }
        .container cont {
            color: #0ab12b; /* Blå färg för titlar */
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        form {
            display: flex;
            flex-direction: column;
            max-width: 600px;
            margin: auto;
        }
        input, textarea {
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            padding: 10px;
            background-color: #0099cc;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #007399;
        }
    </style>
</head>
<body>
    <header>
        <h1>Växjö Rörservice AB</h1>
    </header>
    <nav>
        <a href="#home">Hem</a>
        <a href="#services">Tjänster</a>
        <a href="#about">Om Oss</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <div class="container" id="home">
        <h2 class="cont">Välkommen till Växjö Rörservice AB</h2>
        <p>Vi erbjuder professionella VVS-tjänster för både privatpersoner och företag i Kronoberg med omnejd. Snabb, pålitlig och prisvärd service.</p>
    </div>
    <div class="container" id="services">
        <h2>Våra Tjänster</h2>
        <ul>
            <li><strong>Installation och reparation:</strong> Vi installerar och reparerar alla typer av VVS-system.</li>
            <li><strong>Akut VVS-hjälp:</strong> Tillgängliga dygnet runt för akuta problem.</li>
            <li><strong>Underhåll:</strong> Regelbundet underhåll för att förhindra framtida problem.</li>
            <li><strong>Energieffektiva lösningar:</strong> Modernisering och installation av energieffektiva system.</li>
        </ul>
    </div>
    <div class="container" id="about">
        <h2>Om Växjö Rörservice AB</h2>
        <p>Med lång erfarenhet inom VVS-branschen erbjuder vi högkvalitativa tjänster med fokus på nöjda kunder. Våra certifierade rörmokare är redo att hjälpa dig med allt som krävs inom VVS-branschen.</p>
    </div>
    <div class="container" id="contact">
        <h2>Kontakta Oss</h2>
        <p>Mobil: 0046707469501</p>
        <p>E-post: vaxjororserviceab@gmail.com</p>
        <p>Adress: Vintervägen 7E, 352 32 Växjö</p>
        <form action="mailto:vaxjororserviceab@gmail.com" method="post" enctype="text/plain">
            <label for="name">Namn:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">E-post:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Meddelande:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Skicka</button>
        </form>
    </div>
    <div class="footer">
        <p>© 2024 Växjö Rörservice AB. Alla rättigheter förbehållna.</p>
    </div>
</body>
</html>
