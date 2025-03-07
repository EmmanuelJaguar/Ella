<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valeria</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #6a82fb, #fc5c7d);
            font-family: 'Dancing Script', cursive;
            color: #333;
        }

        .book {
            position: relative;
            width: 350px;
            height: 500px;
            overflow: hidden;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .page {
            width: 100%;
            height: 100%;
            padding: 20px;
            box-sizing: border-box;
            position: absolute;
            top: 0;
            left: 0;
            display: none;
            text-align: center;
            font-style: italic; /* Letra cursiva */
        }

        .page.active {
            display: block;
        }

        .arrow {
            position: fixed;
            top: 50%;
            transform: translateY(-50%);
            font-size: 30px;
            cursor: pointer;
            color: white;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px;
            border-radius: 50%;
            user-select: none;
            transition: background 0.3s;
            z-index: 100;
        }

        .arrow:hover {
            background: rgba(0, 0, 0, 0.8);
        }

        .arrow.left {
            left: 10px;
        }

        .arrow.right {
            right: 10px;
        }

        h1 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #444;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
            color: #555;
        }

        .poem {
            margin-top: 20px;
            font-size: 16px;
            line-height: 1.8;
            color: #666;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
</head>
<body>

    <div class="book">
        <!-- Página 1 -->
        <div class="page active">
            <h1>Valeria</h1>
            <p>Un día la vi y todo cambió...</p>
            <div class="poem">
                Tu risa estalla como un trueno ardiente,<br>
                mi pecho esconde un eco que delira,<br>
                tu voz es llama que en mi piel transpira,<br>
                tu ausencia es frío que me hiela la mente.<br>
                <br>
                Y en este caos de pasiones rotas,<br>
                me encuentro en fiebre y sombra clandestina,<br>
                mi alma es tuya, prisionera y divina,<br>
                en esta guerra donde no hay derrotas.
            </div>
        </div>
        <!-- Página 2 -->
        <div class="page">
            <div class="poem">
                Te miro y tiemblan todos mis cimientos,<br>
                me abrasas con tu luz incandescente,<br>
                y aunque tu sol me queme lentamente,<br>
                prefiero arder que ahogarme en mis tormentos.<br>
                <br>
                Tu voz se esconde entre mis madrugadas,<br>
                resuena en cada espacio de mi mente,<br>
                mi pecho es un latido irreverente,<br>
                perdido entre tus sombras encantadas.
            </div>
        </div>
        <!-- Página 3 -->
        <div class="page">
            <div class="poem">
                Te vi danzando entre mis noches rotas,<br>
                tu risa fue un relámpago en mi pecho,<br>
                y aunque intenté borrar tu amor deshecho,<br>
                tu sombra me arañó con sus derrotas.<br>
                <br>
                Eres mi furia, mi piedad, mi herida,<br>
                un laberinto donde ardo y me pierdo,<br>
                tu amor es fuego, mi verdad, mi miedo,<br>
                la dulce cicatriz de mi caída.
            </div>
        </div>
        <!-- Página 4 -->
        <div class="page">
            <div class="poem">
                El eco de tu risa me tortura,<br>
                mi piel se quiebra al roce de tu aliento,<br>
                me clavas en el alma tu tormento,<br>
                y en esta herida hallé mi sepultura.<br>
                <br>
                Pero me eleva el caos de tu abrazo,<br>
                me atrapa el huracán de tu perfume,<br>
                y aunque mi amor en tu silencio fume,<br>
                me entrego a ti, mi muerte y mi regazo.
            </div>
        </div>
        <!-- Página 5 -->
        <div class="page">
            <div class="poem">
                Si miro el cielo, en cada estrella estallas,<br>
                mis noches llevan rastros de tu fuego,<br>
                tu ausencia es un abismo en que me entrego,<br>
                sin ti no queda más que sombras callas.<br>
                <br>
                Mi alma se deshace en tu oleaje,<br>
                tu amor es mar, corriente desbocada,<br>
                te sigo como un náufrago en la nada,<br>
                tu luz es mi condena y mi pasaje.
            </div>
        </div>
        <!-- Página 6 -->
        <div class="page">
            <div class="poem">
                Tu piel es un conjuro envenenado,<br>
                me hechizas con la sombra de tu danza,<br>
                tu amor es la más cruel extravaganza,<br>
                el dulce precipicio en que he saltado.<br>
                <br>
                Pero te sigo, sediento en tu sombra,<br>
                me quemo en cada rastro de tu esencia,<br>
                y aunque mi alma pierda su conciencia,<br>
                me aferro a la locura que me nombra.
            </div>
        </div>
        <!-- Página 7 -->
        <div class="page">
            <div class="poem">
                Si callas, mi universo se desploma,<br>
                me ahoga la tormenta de tu olvido,<br>
                mi pecho en soledad muere perdido,<br>
                pues sólo en ti mi sombra se desploma.<br>
                <br>
                Mas si me miras, se ilumina el día,<br>
                tu risa es mi batalla y mi victoria,<br>
                quiero perderme en la infinita gloria,<br>
                de un beso que devuelva mi agonía.
            </div>
        </div>
        <!-- Página 8 -->
        <div class="page">
            <div class="poem">
                Mi mente es un incendio en tu memoria,<br>
                tu rastro es un abismo de fulgor,<br>
                y aunque me queme el fuego de tu amor,<br>
                me entrego a ti, mi ruina y mi historia.<br>
                <br>
                Sin ti, la vida es solo un eco frío,<br>
                me habita un hueco que tu luz reclama,<br>
                pues todo lo que soy arde en tu llama,<br>
                y muero cada vez que no te río.
            </div>
        </div>
        <!-- Página 9 -->
        <div class="page">
            <div class="poem">
                Si el viento me susurra tu silueta,<br>
                tiembla mi piel de ansiosa incertidumbre,<br>
                pues eres en mi mente un cielo en cumbre,<br>
                el fuego que mi alma interpreta.<br>
                <br>
                Mas eres vendaval y eres tormenta,<br>
                y huyo del caos que en tus labios quema,<br>
                pero regreso a ti, pues eres lema,<br>
                de un alma que en tu ausencia se fragmenta.
            </div>
        </div>
        <!-- Página 10 -->
        <div class="page">
            <div class="poem">
                Si cierro los ojos, su risa me abraza,<br>
                un eco de luz en la sombra distante,<br>
                me atrapa, me eleva, me ahoga, me arrastra,<br>
                y quedo sin voz, tembloroso y errante.<br>
                <br>
                Pero si calla, el abismo me traga,<br>
                mi mundo es un lienzo pintado en su ausencia,<br>
                y aunque en su amor no me quede clemencia,<br>
                prefiero su guerra a perder su batalla.
            </div>
        </div>
        <!-- Página 11 (Hoja final) -->
        <div class="page">
            <div class="poem">
                Si he de perderte, que el viento me arranque,<br>
                que borre tu sombra de cada latido,<br>
                pues duele más verte partir sin sentido,<br>
                que nunca haber sido quien prenda tu estanque.<br>
                <br>
                Pero si dudas, si en ti se desata<br>
                el eco silente de un sueño dormido,<br>
                no huyas aún, quédate en mi descuido,<br>
                y deja que el tiempo nos marque su pauta.<br>
                <br>
                Y aun si me llamas, mi voz será ausencia,<br>
                porque este es mi último paso hacia ti,<br>
                no porque deje de amarte así,<br>
                sino porque el alma merece clemencia.
            </div>
        </div>
    </div>

    <!-- Flechas de navegación -->
    <div class="arrow left" onclick="changePage('prev')">&#10094;</div>
    <div class="arrow right" onclick="changePage('next')">&#10095;</div>

    <script>
        let currentPage = 0; // Página inicial
        const pages = document.querySelectorAll('.page');

        function changePage(direction) {
            pages[currentPage].classList.remove('active');

            if (direction === 'next') {
                currentPage = (currentPage + 1) % pages.length; // Si llegamos al final, volvemos al principio
            } else {
                currentPage = (currentPage - 1 + pages.length) % pages.length; // Si vamos al inicio, volvemos al final
            }

            pages[currentPage].classList.add('active');
        }
    </script>

</body>
</html>
