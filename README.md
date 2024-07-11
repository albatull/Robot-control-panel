<!DOCTYPE html>
<html>
<head>
    <title>Robot Movement Control</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        h1 {
            color: #333;
            text-align: center;
        }
        .container {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        button {
            background: #007bff;
            color: #fff;
            border: none;
            padding: 10px 20px;
            margin: 5px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Control the Robot's Movement</h1>
        <form method="post" action="send.php">
            <button type="move" name="move" value="forward">Forward</button>
            <button type="move" name="move" value="backward">Backward</button>
            <button type="move" name="move" value="stop">Stop</button>
            <button type="move" name="move" value="right">Right</button>
            <button type="move" name="move" value="left">Left</button>
        </form>
    </div>
</body>
</html>
