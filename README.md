<!DOCTYPE html>
<html lang="sk">
<head>
    <meta charset="UTF-8">
    <title>SPC of Shear-Force</title>
    <style>
        body {
            /* Definícia pozadia podľa vašej požiadavky */
            background-image: url('pozadie_SPC.jpg');
            background-size: cover;
            background-attachment: fixed;
            font-family: sans-serif;
            padding: 20px;
            line-height: 1.6;
        }
        .content {
            background-color: rgba(255, 255, 255, 0.8); /* Biely závoj pre čitateľnosť textu */
            padding: 20px;
            border-radius: 8px;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px 0;
        }
    </style>
</head>
<body>

<div class="content">
    <h1>Statistical Process Control (SPC) of Shear-Force</h1>
    <p>====================================================</p>

    <p>To control quality of wire bonding process, the shear force data is processed as follows:</p>
    <ul>
        <li>daily data collection by production device (raw txt data) and export to metadata file</li>
        <li>metadata transformation to Q-DAS dedicated format (by Access VBA code)</li>
        <li>data evaluation by defined evaluation strategy (Q-DAS statistical software) to Control Chart</li>
    </ul>

    <h3>Meta data definition</h3>
    <img src="https://githubusercontent.com" alt="Meta data definition">

    <h3>Control Chart</h3>
    <img src="https://githubusercontent.com" alt="Control Chart">
</div>

</body>
</html>
