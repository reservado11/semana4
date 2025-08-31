<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estructura Flexbox</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background-color: rgb(255, 238, 0);  
            color: rgb(25, 20, 20);
            text-align: center;
            padding: 20px;
            flex: 0 0 60px;
        }

        .container {
            flex: 1;
            display: flex;
        }

        nav {
            background-color: rgb(169, 3, 169);   /* Morado */
            padding: 20px;
            flex: 0 0 200px;
        }

        main {
            background-color: rgb(0, 253, 0); /* Verde */
            padding: 20px;
            flex: 1;
        }

        footer {
            background-color: rgb(5, 64, 88); /* Azul */
            color: black;
            text-align: center;
            padding: 15px;
            flex: 0 0 50px;
        }

        /* Estilo para las cajas de ejemplo */
        .items {
            background: rgba(0,0,0,0.1);
            margin: 10px;
            padding: 15px;
            border-radius: 8px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Header</h1>
    </header>

    <div class="container">
        <nav>
            <h2>Navbar</h2>
            
        </nav>

        <main>
            <h2>Body</h2>
            <p></p>
        </main>
    </div>

    <footer>
        <h2>Footer</h2>
    </footer>
 </body>
</html>

</body>
</html>
