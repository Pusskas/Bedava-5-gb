<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>İnternet Öldü mü Lan?</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            background: black;
            color: lime;
            font-family: 'Courier New', monospace;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            animation: blink-bg 1s infinite alternate;
        }
        h1 {
            font-size: 5vw;
            text-align: center;
            color: red;
            text-shadow: 0 0 20px red;
            animation: shake 0.5s infinite;
        }
        .emoji {
            font-size: 15vw;
            animation: explode 2s infinite;
        }
        @keyframes blink-bg {
            from { background: #000; }
            to   { background: #200000; }
        }
        @keyframes shake {
            0% { transform: translate(1px, 1px) rotate(0deg); }
            10% { transform: translate(-1px, -2px) rotate(-1deg); }
            20% { transform: translate(-3px, 0px) rotate(1deg); }
            30% { transform: translate(3px, 2px) rotate(0deg); }
            100% { transform: translate
