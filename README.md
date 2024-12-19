<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modelo BI</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* Reset general */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to bottom, #f0f8ff, #e7ffe6);
            color: #333;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(to right, #2e8b57, #3cb371);
            color: #fff;
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        header nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
        }

        header nav ul li {
            display: inline;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s, transform 0.2s;
        }

        header nav ul li a:hover {
            color: #ffd700;
            transform: scale(1.1);
        }

        main {
            padding: 2rem;
            display: flex;
            flex-direction: column;
            gap: 3rem;
        }

        section {
            background: #fff;
            border: 2px solid #3cb371;
            border-radius: 10px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
            text-align: center;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        section h2 {
            margin-bottom: 1.5rem;
            font-size: 1.7rem;
            color: #2e8b57;
        }

        iframe {
            width: 100%;
            height: 500px;
            border: 3px solid #ffd700;
            border-radius: 8px;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background: linear-gradient(to right, #2e8b57, #3cb371);
            color: #fff;
            font-size: 0.9rem;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.2);
        }

        footer p {
            margin: 0;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.6rem;
            }

            header nav ul {
                flex-direction: column;
                gap: 0.5rem;
            }

            iframe {
                height: 400px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Modelo BI para los Ingresos Tributarios de San Juan de Miraflores del 2019</h1>
        <nav>
            <ul>
                <li><a href="#dashboard1">Impuesto Predial</a></li>
                <li><a href="#dashboard2">Limpieza Pública</a></li>
                <li><a href="#dashboard3">Parques y Jardines</a></li>
                <li><a href="#dashboard4">Serenazgo</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="dashboard1">
            <h2>Ingresos Tributarios del concepto "Impuesto Predial"</h2>
            <iframe src="https://app.powerbi.com/view?r=eyJrIjoiYTk3ZWQ5MTgtN2M1OC00NWRmLWEwMGEtYWRkZDdiMWFmYzQ1IiwidCI6IjE1NGQ5NDY2LTVmZDQtNDQyYS1iYjZkLWY2ODNiYmY1MjMxZiIsImMiOjR9" 
                title="Ingresos Tributarios del concepto 'Impuesto Predial'"></iframe>
        </section>
        <section id="dashboard2">
            <h2>Ingresos Tributarios del concepto "Limpieza Pública"</h2>
            <iframe src="https://app.powerbi.com/view?r=eyJrIjoiMGUzMGM3YzgtNDg0My00ZjhiLTkxMDItOWU3NDFhOWJlNmMzIiwidCI6IjE1NGQ5NDY2LTVmZDQtNDQyYS1iYjZkLWY2ODNiYmY1MjMxZiIsImMiOjR9" 
                title="Ingresos Tributarios del concepto 'Limpieza Pública'"></iframe>
        </section>
        <section id="dashboard3">
            <h2>Ingresos Tributarios del concepto "Parques y Jardines"</h2>
            <iframe src="https://app.powerbi.com/view?r=eyJrIjoiYTE0MmYxMTctNDAyOS00OThhLWFmYWUtNzVjODQ1Zjg1NjgzIiwidCI6IjE1NGQ5NDY2LTVmZDQtNDQyYS1iYjZkLWY2ODNiYmY1MjMxZiIsImMiOjR9" 
                title="Ingresos Tributarios del concepto 'Parques y Jardines'"></iframe>
        </section>
        <section id="dashboard4">
            <h2>Ingresos Tributarios del concepto "Serenazgo"</h2>
            <iframe src="https://app.powerbi.com/view?r=eyJrIjoiNzg4ZmQ0MTctN2Y5My00ODc2LWEwMjMtYTU2MTViNjVmMzljIiwidCI6IjE1NGQ5NDY2LTVmZDQtNDQyYS1iYjZkLWY2ODNiYmY1MjMxZiIsImMiOjR9" 
                title="Ingresos Tributarios del concepto 'Serenazgo'"></iframe>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Modelo BI - San Juan de Miraflores</p>
    </footer>
</body>
</html>
