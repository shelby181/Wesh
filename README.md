<!DOCTYPE html>
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
    margin-bottom: 10
