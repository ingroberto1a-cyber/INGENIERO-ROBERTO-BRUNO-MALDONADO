# INGENIERO-ROBERTO-BRUNO-MALDONADO
OBRAS DE FAISPIAM Y OBRAS DE LA ESCUELA ES NUESTRA
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Obras FAIS-PIAM – El Fuereño y Plan Ranchito</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #eef2f3;
        }

        header {
            background: linear-gradient(135deg, #003366, #005599);
            color: white;
            padding: 40px;
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
        }

        section {
            background: white;
            margin: 20px;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            opacity: 0;
            transform: translateY(30px);
            animation: slideUp 1s forwards;
        }

        h2 {
            color: #003366;
        }

        .obra {
            border-left: 6px solid #005599;
            padding-left: 15px;
            margin-bottom: 20px;
        }

        .galeria img {
            width: 30%;
            margin: 5px;
            border-radius: 8px;
            transition: transform .3s;
        }

        .galeria img:hover {
            transform: scale(1.05);
        }

        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }

        /* Animaciones */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>

    <script>
        // Animación progresiva de secciones
        document.addEventListener("DOMContentLoaded", () => {
            const sections = document.querySelectorAll("section");
            let delay = 0.3;

            sections.forEach(sec => {
                sec.style.animationDelay = delay + "s";
                delay += 0.3;
            });
        });
    </script>
</head>

<body>

<header>
    <h1>Obras de Infraestructura – FAIS-PIAM</h1>
    <p>Comunidad El Fuereño y Plan Ranchito – Municipio de Acatepec, Guerrero</p>
</header>

<section>
    <h2>1. Construcción del Tanque de Agua Potable – El Fuereño</h2>

    <div class="obra">
        <p>
            La obra consiste en la construcción de un tanque de almacenamiento de agua potable 
            para mejorar el suministro del vital líquido en la comunidad de El Fuereño. 
            El proyecto es financiado con recursos del **FAIS-PIAM**.
        </p>
    </div>

    <h3>Objetivos</h3>
    <ul>
        <li>Garantizar el acceso al agua potable para todas las familias.</li>
        <li>Mejorar la infraestructura hidráulica comunitaria.</li>
        <li>Reducir riesgos sanitarios por falta de agua.</li>
    </ul>

    <h3>Avances</h3>
    <ul>
        <li>Avance físico: 55%</li>
        <li>Avance financiero: 48%</li>
        <li>Etapa actual: Construcción de muros y preparación para la losa.</li>
    </ul>

    <h3>Galería</h3>
    <div class="galeria">
        <img src="tanque1.jpg" alt="Tanque de agua avance 1">
        <img src="tanque2.jpg" alt="Tanque de agua avance 2">
        <img src="tanque3.jpg" alt="Tanque de agua avance 3">
    </div>
</section>

<section>
    <h2>2. Construcción de Calle con Concreto Hidráulico – Plan Ranchito</h2>

    <div class="obra">
        <p>
            La obra contempla la pavimentación con concreto hidráulico de una de las calles 
            principales de la comunidad de Plan Ranchito, mejorando la movilidad y el acceso 
            a servicios básicos. Proyecto financiado con **FAIS-PIAM**.
        </p>
    </div>

    <h3>Objetivos</h3>
    <ul>
        <li>Mejorar la conectividad interna de la comunidad.</li>
        <li>Garantizar una vía segura y resistente a la temporada de lluvias.</li>
        <li>Impulsar el desarrollo social y económico local.</li>
    </ul>

    <h3>Avances</h3>
    <ul>
        <li>Avance físico: 70%</li>
        <li>Avance financiero: 65%</li>
        <li>Etapa actual: Colado de losas y habilitación de cunetas.</li>
    </ul>

    <h3>Galería</h3>
    <div class="galeria">
        <img src="calle1.jpg" alt="Calle concreto avance 1">
        <img src="calle2.jpg" alt="Calle concreto avance 2">
        <img src="calle3.jpg" alt="Calle concreto avance 3">
    </div>
</section>

<section>
    <h2>Contacto</h2>
    <p><strong>Responsable Técnico:</strong> Ing. ___________________</p>
    <p><strong>Teléfono:</strong> ___________________</p>
    <p><strong>Correo:</strong> ___________________</p>
</section>

<footer>
    <p>© 2026 Obras FAIS-PIAM – Municipio de Acatepec, Guerrero</p>
</footer>

</body>
</html>
