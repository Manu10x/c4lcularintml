<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Pagos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h2 {
            text-align: center;
            color: #444;
            margin-top: 20px;
        }

        .container {
            width: 90%;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        label {
            font-size: 14px;
            font-weight: bold;
            margin-top: 10px;
            display: block;
        }

        input[type="text"], input[type="number"], input[type="date"] {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }

        input[type="text"]:focus, input[type="number"]:focus, input[type="date"]:focus {
            border-color: #0056b3;
            outline: none;
        }

        input[type="submit"], button {
            padding: 10px 20px;
            border: none;
            background-color: #28a745;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            margin: 5px;
        }

        input[type="submit"]:hover, button:hover {
            background-color: #218838;
        }

        .result-table {
            width: 100%;
            margin-top: 20px;
            border-collapse: collapse;
        }

        .result-table th, .result-table td {
            padding: 10px;
            text-align: center;
            border: 1px solid #ddd;
        }

        .result-table th {
            background-color: #f8f9fa;
            font-weight: bold;
        }

        .result-table tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        .result-table td {
            background-color: #f1f1f1;
        }

        .btn-container {
            text-align: center;
            margin-top: 20px;
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .btn-container a {
            text-decoration: none;
        }

        #enviarWhatsApp {
            display: inline-block;
        }

        .form-container {
            margin-bottom: 20px;
        }

        .clear-btn {
            background-color: #dc3545;
        }

        .clear-btn:hover {
            background-color: #c82333;
        }

        .footer {
            text-align: center;
            margin-top: 50px;
            font-size: 12px;
            color: #888;
        }

        .footer a {
            color: #007bff;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                width: 95%;
            }

            h2 {
                font-size: 24px;
            }

            input[type="submit"], button {
                width: 100%;
                font-size: 18px;
            }

            .result-table {
                font-size: 14px;
            }

            .footer {
                font-size: 10px;
            }

            .btn-container {
                display: flex;
                flex-direction: column;
                align-items: center;
            }

            .btn-container a {
                width: 100%;
                margin-top: 10px;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 10px;
            }

            input[type="submit"], button {
                font-size: 16px;
                padding: 12px 25px;
            }

            .result-table {
                font-size: 12px;
            }

            .footer {
                font-size: 10px;
            }
        }
    </style>
    <script>
        // Función para formatear el valor con puntos como separador de miles
        function formatearValor(input) {
            let valor = input.value.replace(/\D/g, '');
            valor = valor.replace(/\B(?=(\d{3})+(?!\d))/g, ".");
            input.value = valor;
        }

        // Función para limpiar los resultados
        function limpiarResultados() {
            document.getElementById("resultadoCompra").innerHTML = "";
            document.getElementById("resultadoCálculos").innerHTML = "";
            document.getElementById("resultadoFechas").innerHTML = "";
            document.getElementById("valor_compra").value = "";
            document.getElementById("cuotas").value = "";
            document.getElementById("fecha_compra").value = "";
            document.getElementById("numero_whatsapp").value = "";
            document.getElementById("enviarWhatsApp").style.display = "none"; // Ocultar el botón de WhatsApp
        }

        // Función para calcular los pagos
        function calcularPagos() {
            let valorCompra = document.getElementById("valor_compra").value.replace(/\./g, '');
            let cuotas = document.getElementById("cuotas").value;
            let fechaCompraInput = document.getElementById("fecha_compra").value;

            if (!valorCompra || !cuotas) {
                alert("Por favor, ingrese el valor de la compra y las cuotas.");
                return;
            }

            valorCompra = parseInt(valorCompra);
            cuotas = parseInt(cuotas);

            let fechaCompra = fechaCompraInput ? new Date(fechaCompraInput) : new Date();

            let interes = 2;
            let interesTotal = valorCompra * (interes / 100);
            let montoTotal = valorCompra + interesTotal;
            let cuotaMensual = montoTotal / cuotas;

            let resultadoCompra = `
                <h3>Fecha de la compra:</h3>
                <table class="result-table">
                    <tr><th>Fecha de la compra</th><td>${fechaCompra.toLocaleDateString()}</td></tr>
                </table><br><br>
            `;

            document.getElementById("resultadoCompra").innerHTML = resultadoCompra;

            let resultadoCalculos = `
                <h3>Resumen del cálculo:</h3>
                <table class="result-table">
                    <tr><th>Concepto</th><th>Valor</th></tr>
                    <tr><td>Valor de la compra</td><td>$ ${valorCompra.toLocaleString()}</td></tr>
                    <tr><td>Interés (2%)</td><td>$ ${interesTotal.toLocaleString()}</td></tr>
                    <tr><td>Monto total a pagar</td><td>$ ${montoTotal.toLocaleString()}</td></tr>
                    <tr><td>Cuota mensual</td><td>$ ${cuotaMensual.toLocaleString()}</td></tr>
                </table><br><br>
            `;
            document.getElementById("resultadoCálculos").innerHTML = resultadoCalculos;

            let resultadoFechas = `<h4>Fechas de pago:</h4>
                <table class="result-table">
                    <tr><th>Cuota</th><th>Fecha de pago</th><th>Días restantes</th></tr>`;

            let mensajeWhatsApp = `Fecha de la compra: ${fechaCompra.toLocaleDateString()}\n\n`;
            mensajeWhatsApp += `Resumen del cálculo:\n`;
            mensajeWhatsApp += `Valor de la compra: $ ${valorCompra.toLocaleString()}\n`;
            mensajeWhatsApp += `Interés (2%): $ ${interesTotal.toLocaleString()}\n`;
            mensajeWhatsApp += `Monto total a pagar: $ ${montoTotal.toLocaleString()}\n`;
            mensajeWhatsApp += `Cuota mensual: $ ${cuotaMensual.toLocaleString()}\n\n`;
            mensajeWhatsApp += `Fechas de pago:\n`;

            for (let i = 1; i <= cuotas; i++) {
                let fechaPago = new Date(fechaCompra);
                let mes = fechaPago.getMonth() + 1 + i - 1;
                if (mes > 12) {
                    mes = mes - 12;
                    fechaPago.setFullYear(fechaPago.getFullYear() + 1);
                }
                fechaPago.setMonth(mes - 1);
                fechaPago.setDate(15);

                let diasRestantes = Math.max(0, Math.ceil((fechaPago - new Date()) / (1000 * 3600 * 24)));

                resultadoFechas += `
                    <tr>
                        <td>Cuota ${i}</td>
                        <td>${fechaPago.toLocaleDateString()}</td>
                        <td>${diasRestantes} días</td>
                    </tr>`;
                mensajeWhatsApp += `Cuota ${i}: ${fechaPago.toLocaleDateString()} - ${diasRestantes} días restantes\n`;
            }

            resultadoFechas += `</table><br><br>`;
            document.getElementById("resultadoFechas").innerHTML = resultadoFechas;

            // Enlace para WhatsApp con todos los resultados
            let mensajeFinal = encodeURIComponent(mensajeWhatsApp);
            let numeroWhatsApp = document.getElementById("numero_whatsapp").value || "573022850991"; // Usar el número ingresado o el predeterminado

            let enlaceWhatsApp = `https://wa.me/${numeroWhatsApp}?text=${mensajeFinal}`;
            document.getElementById("enviarWhatsApp").href = enlaceWhatsApp;
            document.getElementById("enviarWhatsApp").style.display = "inline"; // Hacer visible el botón de WhatsApp
        }
    </script>
</head>
<body>
    <div class="container">
        <h2>Calculadora de Pagos con Interés</h2>
        <div class="form-container">
            <form method="POST" onsubmit="event.preventDefault(); calcularPagos();">
                <label for="valor_compra">Valor de la compra (en pesos colombianos): </label>
                <input type="text" name="valor_compra" id="valor_compra" oninput="formatearValor(this)" required><br>

                <label for="cuotas">Número de cuotas: </label>
                <input type="number" name="cuotas" id="cuotas" min="1" required><br>

                <label for="fecha_compra">Fecha de la compra (opcional, si no se selecciona se usa la fecha actual): </label>
                <input type="date" name="fecha_compra" id="fecha_compra"><br>

                <label for="numero_whatsapp">Número de WhatsApp para enviar los resultados: </label>
                <input type="text" name="numero_whatsapp" id="numero_whatsapp" placeholder="Ej: 3022850991"><br><br>

                <input type="submit" value="Calcular">
                <button type="button" class="clear-btn" onclick="limpiarResultados()">Limpiar resultados</button>
            </form>
        </div>

        <div id="resultadoCompra"></div>
        <div id="resultadoCálculos"></div>
        <div id="resultadoFechas"></div>

        <div class="btn-container">
            <a id="enviarWhatsApp" href="#" target="_blank">
                <button type="button">Enviar resultados por WhatsApp</button>
            </a>
        </div>
    </div>

    <div class="footer">
        <p>Diseñado por <a href="#">Manu10</a></p>
    </div>
</body>
</html>
