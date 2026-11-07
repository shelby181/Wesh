Pour toi mon Cœur ❤🫂
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Juste pour toi ❤️</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 30px 18px;
    min-height: 100vh;
    background: #0d0b12;
    color: white;
    font-family: Georgia, serif;
    text-align: center;
}

.container {
    max-width: 460px;
    margin: auto;
}

h1 {
    color: #e6c477;
    font-size: 30px;
    margin-top: 35px;
}

.subtitle {
    color: #ffb6c9;
    line-height: 1.8;
    margin-bottom: 30px;
}

.heart {
    color: #ff6b91;
    font-size: 35px;
    animation: beat 1.3s infinite;
}

.card {
    background: #17131d;
    border: 1px solid #806536;
    border-radius: 20px;
    padding: 20px;
    margin: 22px 0;
    box-shadow: 0 5px 20px #00000055;
}

/* ANVELOP */

.envelope {
    margin: 18px 0;
    border: 1px solid #b89555;
    border-radius: 15px;
    background: linear-gradient(145deg, #211724, #151019);
    overflow: hidden;
}

.envelope summary {
    list-style: none;
    cursor: pointer;
    padding: 23px 15px;
    color: #e6c477;
    font-size: 18px;
    transition: 0.3s;
}

.envelope summary::-webkit-details-marker {
    display: none;
}

.envelope summary:hover {
    background: #30202e;
}

.icon {
    display: block;
    font-size: 30px;
    margin-bottom: 10px;
}

.arrow {
    display: block;
    color: #ff9ab6;
    margin-top: 10px;
    font-size: 13px;
}

.message {
    display: grid;
    grid-template-rows: 0fr;
    transition: grid-template-rows 0.6s ease;
}

.message > div {
    overflow: hidden;
}

.envelope[open] .message {
    grid-template-rows: 1fr;
}

.message p {
    padding: 20px;
    margin: 0;
    color: #f5e9ed;
    line-height: 1.9;
    border-top: 1px solid #806536;
    animation: appear 0.8s ease;
}

.envelope[open] .arrow {
    display: none;
}

.signature {
    color: #ff9ab6;
    margin-top: 25px;
    font-size: 19px;
}

footer {
    margin-top: 45px;
    padding: 25px 10px;
    color: #c6a968;
    font-size: 13px;
    letter-spacing: 2px;
    line-height: 2;
}

@keyframes beat {
    50% {
        transform: scale(1.25);
    }
}

@keyframes appear {
    from {
        opacity: 0;
        transform: translateY(15px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
</style>
</head>

<body>

<div class="container">

    <div class="heart">♥</div>

    <h1>Juste pour toi</h1>

    <p class="subtitle">
        J'ai quelques petites choses à te dire...
        <br>
        Prends ton temps et ouvre chaque enveloppe. 💌
    </p>

    <div class="card">

        <details class="envelope">
            <summary>
                <span class="icon">💌</span>
                Un sentiment unique ❤️
                <span class="arrow">Toucher pour ouvrir ↓</span>
            </summary>

            <div class="message">
                <div>
                    <p>
                        Depuis que tu fais partie de ma vie,
                        j'ai découvert une façon d'aimer
                        que je ne connaissais pas.
                        Tu es devenue une belle partie
                        de mon quotidien.
                    </p>
                </div>
            </div>
        </details>


        <details class="envelope">
            <summary>
                <span class="icon">🎀</span>
                Ce que tu représentes pour moi 💗
                <span class="arrow">Toucher pour ouvrir ↓</span>
            </summary>

            <div class="message">
                <div>
                    <p>
                        Tu n'es pas seulement une personne
                        que j'aime. Tu es celle dont la présence
                        peut rendre une journée ordinaire
                        beaucoup plus belle.
                    </p>
                </div>
            </div>
        </details>


        <details class="envelope">
            <summary>
                <span class="icon">❤️</span>
                Une promesse du cœur 💌
                <span class="arrow">Toucher pour ouvrir ↓</span>
            </summary>

            <div class="message">
                <div>
                    <p>
                        Je ne sais pas tout ce que l'avenir
                        nous réserve, mais je sais une chose :
                        j'ai envie de continuer à construire
                        quelque chose de beau avec toi.

                        Apprendre, grandir et avancer ensemble,
                        même lorsque les choses deviennent difficiles.

                        <br><br>
                        Je t'aime. ❤️

                        <br><br>
                        <span class="signature">
                            Avec tout mon amour, Papi ❤️
                        </span>
                    </p>
                </div>
            </div>
        </details>

    </div>

    <footer>
        FAIT AVEC AMOUR ♥
        <br>
        07 NOVEMBRE 2026
    </footer>

</div>

</body>
</html>
