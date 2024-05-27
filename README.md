<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Criterios de la Primera Derivada</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h1, h2, h3 {
            color: #333;
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        ul {
            list-style: disc inside;
            margin: 10px 0 10px 20px;
            padding: 0;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            border-left: 4px solid #ccc;
            overflow-x: auto;
            white-space: pre-wrap;
            word-wrap: break-word;
        }
        @media (max-width: 768px) {
            .container {
                width: 90%;
                margin-top: 20px;
                padding: 15px;
            }
            pre {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Criterios de la Primera Derivada</h1>

        <div class="section">
            <h2>Conceptos Básicos</h2>
            <p><strong>Función y Derivada:</strong></p>
            <ul>
                <li><strong>Función:</strong> Imagina una función como una máquina que toma un número y lo transforma en otro número. Por ejemplo, f(x) = x<sup>2</sup> toma x y lo convierte en x<sup>2</sup>.</li>
                <li><strong>Primera Derivada:</strong> La primera derivada de una función, f'(x), nos dice cómo cambia la función en cada punto. Es como la velocidad a la que cambia la función.</li>
            </ul>
        </div>

        <div class="section">
            <h2>Criterio de la Primera Derivada para Monotonía</h2>
            <p><strong>¿Cómo saber si una función está subiendo o bajando?</strong></p>
            <ul>
                <li><strong>Función Creciente:</strong> Una función está subiendo (es creciente) si su derivada es positiva, f'(x) &gt; 0. Imagínate una montaña que estás subiendo. Si la pendiente es positiva, estás yendo hacia arriba.</li>
                <li><strong>Función Decreciente:</strong> Una función está bajando (es decreciente) si su derivada es negativa, f'(x) &lt; 0. Imagínate una montaña que estás bajando. Si la pendiente es negativa, estás yendo hacia abajo.</li>
            </ul>
        </div>

        <div class="section">
            <h2>Puntos Críticos y Extremos Locales</h2>
            <p><strong>¿Qué son los puntos críticos?</strong></p>
            <p>Un punto crítico es un punto donde la derivada es cero (f'(x) = 0) o no está definida. Es como un punto en el camino donde la pendiente se aplana.</p>

            <p><strong>¿Cómo saber si es un máximo o un mínimo?</strong></p>
            <ul>
                <li><strong>Máximo Local:</strong> Si antes del punto crítico la función estaba subiendo (f'(x) &gt; 0) y después está bajando (f'(x) &lt; 0), entonces el punto crítico es un máximo local. Es como llegar a la cima de una colina; subiste y ahora empiezas a bajar.</li>
                <li><strong>Mínimo Local:</strong> Si antes del punto crítico la función estaba bajando (f'(x) &lt; 0) y después está subiendo (f'(x) &gt; 0), entonces el punto crítico es un mínimo local. Es como llegar al fondo de un valle; bajaste y ahora empiezas a subir.</li>
            </ul>
        </div>

        <div class="section">
            <h2>Ejemplo Práctico</h2>
            <p><strong>Función:</strong> f(x) = x<sup>3</sup> - 3x<sup>2</sup> + 4</p>

            <p><strong>1. Encontrar la derivada:</strong></p>
            <pre>f'(x) = 3x<sup>2</sup> - 6x</pre>

            <p><strong>2. Encontrar los puntos críticos:</strong></p>
            <pre>
3x<sup>2</sup> - 6x = 0
3x(x - 2) = 0
x = 0 y x = 2
Los puntos críticos son x = 0 y x = 2.
            </pre>

            <p><strong>3. Analizar la derivada alrededor de los puntos críticos:</strong></p>
            <pre>
Para x &lt; 0, prueba con un número como x = -1:
f'(-1) = 3(-1)<sup>2</sup> - 6(-1) = 3 + 6 = 9 (positivo, función creciente)

Para 0 &lt; x &lt; 2, prueba con un número como x = 1:
f'(1) = 3(1)<sup>2</sup> - 6(1) = 3 - 6 = -3 (negativo, función decreciente)

Para x &gt; 2, prueba con un número como x = 3:
f'(3) = 3(3)<sup>2</sup> - 6(3) = 27 - 18 = 9 (positivo, función creciente)
            </pre>

            <p><strong>4. Determinar los extremos locales:</strong></p>
            <ul>
                <li>En x = 0, la función pasa de creciente a decreciente, así que x = 0 es un máximo local.</li>
                <li>En x = 2, la función pasa de decreciente a creciente, así que x = 2 es un mínimo local.</li>
            </ul>
        </div>
    </div>
</body>
</html>
