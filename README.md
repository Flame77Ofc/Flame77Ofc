<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Bio</title>
</head>
<body>
    <div id="bio"></div>

    <script>
        const bioPT = `
            <h1>Olá, meu nome é Gabriel Goulart, tenho 14 anos.</h1>
            <ul>
                <li>🌱 Atualmente aprendendo JavaScript 🟨</li>
                <li>📌 Localização: Brasil, Santa Catarina, Blumenau.</li>
                <li>🎂 Nascimento: 14/06/2010</li>
                <li>⚔ Todos os dias programando! 👨🏻‍💻</li>
                <li>⚡ Gosto de: Astronomia 🪐, Xadrez ♟ e Programação 🖥</li>
            </ul>
            <h2>Histórico de Datas:</h2>
            <ul>
                <li>22/10/2024: Comecei HTML e CSS</li>
                <li>25/12/2024: Terminei HTML e CSS</li>
                <li>05/01/2025: Comecei JavaScript</li>
                <li>01/03/2025: Acabei JavaScript</li>
            </ul>
        `;

        const bioEN = `
            <h1>Hello, my name is Gabriel Goulart, I am 14 years old.</h1>
            <ul>
                <li>🌱 Currently learning JavaScript 🟨</li>
                <li>📌 Location: Brazil, Santa Catarina, Blumenau.</li>
                <li>🎂 Birthdate: 06/14/2010</li>
                <li>⚔ Programming every day! 👨🏻‍💻</li>
                <li>⚡ I like: Astronomy 🪐, Chess ♟, and Programming 🖥</li>
            </ul>
            <h2>Date History:</h2>
            <ul>
                <li>10/22/2024: Started HTML and CSS</li>
                <li>12/25/2024: Finished HTML and CSS</li>
                <li>01/05/2025: Started JavaScript</li>
                <li>03/01/2025: Finished JavaScript</li>
            </ul>
        `;

        const userLang = navigator.language || navigator.userLanguage;
        document.getElementById("bio").innerHTML = userLang.startsWith("pt") ? bioPT : bioEN;
    </script>
</body>
</html>
