<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel FFH4X</title>
    <style>
        :root {
            --primary: #00ff41;
            --bg-dark: #0a0a0a;
            --card-bg: #1a1a1a;
            --text: #ffffff;
        }

        body {
            background-color: #000;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: var(--text);
            overflow: hidden;
        }

        /* Container Principal */
        #painel {
            width: 320px;
            background: var(--card-bg);
            border: 2px solid var(--primary);
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 0 20px rgba(0, 255, 65, 0.2);
            position: relative;
