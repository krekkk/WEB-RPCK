<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>FLZZUE INSTALLER</title>

<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;600&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background:
        radial-gradient(circle at 20% 20%, #111 0%, #000 40%, #000 100%),
        radial-gradient(circle at 80% 80%, #0a0a0a 0%, #000 60%);
    font-family: 'Oswald', sans-serif;
    color: white;
}

.container {
    text-align: center;
}

.title {
    color: #1e90ff;
    font-size: 60px;
    font-weight: 600;
    margin-bottom: 30px;
    text-shadow:
        0 0 5px #1e90ff,
        0 0 10px #1e90ff,
        0 0 20px #1e90ff,
        0 0 40px #1e90ff;
}

/* CMD BOX */
.cmd {
    background: #000;
    border: 1px solid #1e90ff;
    width: 700px;
    margin: 15px auto;
    padding: 20px;
    text-align: left;
    font-family: Consolas, monospace;
    color: #00ffcc;
    box-shadow: 0 0 20px #1e90ff;
}

.cmd-title {
    color: #1e90ff;
    margin-bottom: 10px;
}

.line {
    margin: 4px 0;
}

/* BUTTON */
.btn {
    margin-top: 10px;
    padding: 10px 25px;
    font-size: 14px;
    color: #1e90ff;
    background: transparent;
    border: 2px solid #1e90ff;
    border-radius: 8px;
    cursor: pointer;
    box-shadow: 0 0 5px #1e90ff;
    transition: 0.2s;
}

.btn:hover {
    background: #1e90ff;
    color: #000;
    box-shadow: 0 0 15px #1e90ff;
}
</style>
</head>

<body>

<div class="container">

    <div class="title">
        FLZZUE.COM<br>
        GAME AND SOFTWARE
    </div>

    <!-- GTA 3 -->
    <div class="cmd">

        <div class="cmd-title">GTA 3 RPCK INSTALL</div>

        <div class="line">TUTORIAL INSTALL:</div>
        <div class="line">1. Install ke Drive C / D / E</div>
        <div class="line">2. Masuk folder "GAME FLZZUE"</div>
        <div class="line">3. Buka folder "Grand Theft Auto 3"</div>
        <div class="line">4. Run gta3.exe</div>

        <div class="line">--------------------------------</div>

        <button class="btn"
        onclick="window.location.href='https://www.mediafire.com/file/zkonlxo4t5ycz46/GTA+3+RPCK+FLZZUE.rar/file'">
            INSTALL GTA 3
        </button>

    </div>

    <!-- GTA SA -->
    <div class="cmd">

        <div class="cmd-title">GTA SAN ANDREAS RPCK INSTALL</div>

        <div class="line">TUTORIAL INSTALL:</div>
        <div class="line">1. Install ke Drive C / D / E</div>
        <div class="line">2. Masuk folder "GAME FLZZUE"</div>
        <div class="line">3. Buka folder "Grand Theft Auto San Andreas"</div>
        <div class="line">4. Run gta-sa.exe</div>

        <div class="line">--------------------------------</div>

        <button class="btn"
        onclick="window.location.href='https://store.steampowered.com/app/12120/Grand_Theft_Auto_San_Andreas/'">
            INSTALL GTA SA
        </button>

    </div>

</div>

</body>
</html>
