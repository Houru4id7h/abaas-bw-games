<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hacked Site</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            animation: shake 0.5s infinite alternate;
            background-color: black;
            color: green;
            animation-delay: 3s; /* تأخير ظهور الهز */
        }

        @keyframes shake {
            0% { transform: translate(0, 0); }
            100% { transform: translate(5px, 5px); }
        }

        .hacked-text {
            position: absolute;
            font-size: 36px;
            color: green;
            text-shadow: 2px 2px black, -2px -2px black, 2px -2px black, -2px 2px black, 0px 2px black, 0px -2px black, 2px 0px black, -2px 0px black;
            animation: move 3s linear infinite alternate;
        }

        @keyframes move {
            0% { transform: translate(0, 0); }
            25% { transform: translate(50px, 50px); }
            50% { transform: translate(-50px, -50px); }
            75% { transform: translate(50px, -50px); }
            100% { transform: translate(-50px, 50px); }
        }

        .flash {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            animation: flash 1s infinite alternate;
        }

        @keyframes flash {
            0% { background-color: black; }
            50% { background-color: white; }
        }
    </style>
</head>
<body>
    <!-- كرر كلمة "Hacked" 20 مرة -->
    <div class="hacked-text" style="top: 10%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 20%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 30%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 40%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 50%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 60%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 70%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 80%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 90%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>
    <div class="hacked-text" style="top: 100%;">Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked Hacked</div>

    <!-- شاشة الوميض -->
    <div class="flash"></div>
    <!-- رسالة "مشت عليك؟" -->
    <div class="hacked-text" style="position: fixed; bottom: 20px; color: green;">Moshet Alayek?</div>
</body>
</html>
