<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estado de Autorización - Crédito</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 900px;
            width: 100%;
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .company-name {
            font-size: 36px;
            font-weight: 700;
            letter-spacing: 1px;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 3px solid #FFD700;
            display: inline-block;
        }

        .header h1 {
            font-size: 28px;
            margin-bottom: 10px;
            margin-top: 20px;
        }

        .header p {
            opacity: 0.9;
            font-size: 14px;
        }

        .content {
            padding: 40px;
        }

        .form-section {
            display: block;
        }

        .details-section {
            display: none;
        }

        .form-group {
            margin-bottom: 25px;
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: 600;
            font-size: 14px;
        }

        input {
            width: 100%;
            padding: 12px 15px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 16px;
            transition: all 0.3s;
        }

        input:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }

        .btn {
            width: 100%;
            padding: 14px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: transform 0.2s;
        }

        .btn:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(102, 126, 234, 0.4);
        }

        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
        }

        .btn-secondary {
            background: #6c757d;
            margin-top: 10px;
        }

        .error {
            background: #fee;
            border-left: 4px solid #f44;
            padding: 12px;
            border-radius: 4px;
            color: #c33;
            margin-bottom: 20px;
            display: none;
        }

        .loading {
            background: #e7f3ff;
            border-left: 4px solid #2196F3;
            padding: 12px;
            border-radius: 4px;
            color: #0d47a1;
            margin-bottom: 20px;
            display: none;
            text-align: center;
        }

        .status-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
        }

        .status-card.approved {
            background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);
        }

        .status-card.denied {
            background: linear-gradient(135deg, #eb3349 0%, #f45c43 100%);
        }

        .status-icon {
            font-size: 64px;
            margin-bottom: 15px;
        }

        .status-card h2 {
            font-size: 32px;
            margin-bottom: 10px;
        }

        .status-card p {
            opacity: 0.9;
            font-size: 16px;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .info-box {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #667eea;
        }

        .info-box label {
            font-size: 12px;
            color: #666;
            margin-bottom: 5px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .info-box .value {
            font-size: 20px;
            font-weight: 600;
            color: #333;
            margin-top: 5px;
        }

        .info-box.highlight {
            background: linear-gradient(135deg, #667eea15 0%, #764ba215 100%);
            border-left-color: #764ba2;
        }

        .section-title {
            font-size: 20px;
            font-weight: 600;
            color: #333;
            margin: 30px 0 15px 0;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .timeline {
            position: relative;
            padding-left: 40px;
            margin-top: 20px;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 15px;
            top: 0;
            bottom: 0;
            width: 2px;
            background: #e0e0e0;
        }

        .timeline-item {
            position: relative;
            padding-bottom: 30px;
        }

        .timeline-item::before {
            content: '';
            position: absolute;
            left: -29px;
            top: 5px;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #667eea;
            border: 3px solid white;
            box-shadow: 0 0 0 2px #667eea;
        }

        .timeline-item.completed::before {
            background: #28a745;
            box-shadow: 0 0 0 2px #28a745;
        }

        .timeline-content {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
        }

        .timeline-date {
            font-size: 12px;
            color: #666;
            font-weight: 600;
        }

        .timeline-title {
            font-size: 16px;
            font-weight: 600;
            color: #333;
            margin: 5px 0;
        }

        .timeline-desc {
            font-size: 14px;
            color: #666;
        }

        .costs-breakdown {
            background: #fff9e6;
            border: 2px solid #ffd700;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
        }

        .cost-row {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #f0e5b8;
        }

        .cost-row:last-child {
            border-bottom: none;
            font-weight: 600;
            font-size: 18px;
            color: #333;
            padding-top: 15px;
            border-top: 2px solid #ffd700;
        }

        .cost-label {
            color: #666;
        }

        .cost-value {
            color: #333;
            font-weight: 600;
        }

        .alert-box {
            background: #e7f3ff;
            border-left: 4px solid #2196F3;
            padding: 15px;
            border-radius: 8px;
            margin: 20px 0;
        }

        .alert-box.warning {
            background: #fff3cd;
            border-left-color: #ffc107;
        }

        .alert-box.success {
            background: #d4edda;
            border-left-color: #28a745;
        }

        .alert-box.danger {
            background: #f8d7da;
            border-left-color: #dc3545;
        }

        .alert-title {
            font-weight: 600;
            margin-bottom: 5px;
            color: #333;
        }

        .next-steps {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }

        .step-item {
            display: flex;
            align-items: start;
            gap: 15px;
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px solid #e0e0e0;
        }

        .step-item:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }

        .step-number {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 600;
            flex-shrink: 0;
        }

        .step-content {
            flex: 1;
        }

        .step-title {
            font-weight: 600;
            color: #333;
            margin-bottom: 3px;
        }

        .step-desc {
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="company-name">FINANCIERA MEXICANA</div>
            <h1>📋 Estado de Autorización</h1>
            <p>Consulta el estado de tu solicitud de crédito</p>
        </div>

        <div class="content">
            <!-- Formulario de Consulta -->
            <div class="form-section" id="loginForm">
                <div class="loading" id="loadingMsg">⏳ Consultando información...</div>
                <div class="error" id="errorMsg"></div>
                
                <div class="form-group">
                    <label for="clientNumber">Número de Cliente</label>
                    <input type="text" id="clientNumber" placeholder="Ej: 12345" required>
                </div>

                <div class="form-group">
                    <label for="solicitudNumber">Número de Solicitud</label>
                    <input type="text" id="solicitudNumber" placeholder="Ej: SOL-2024-001" required>
                </div>

                <button class="btn" id="consultarBtn" onclick="consultarSolicitud()">Consultar Estado</button>
            </div>

            <!-- Sección de Detalles -->
            <div class="details-section" id="detailsSection">
                <!-- Estado de Autorización -->
                <div class="status-card" id="statusCard">
                    <div class="status-icon" id="statusIcon"></div>
                    <h2 id="statusTitle"></h2>
                    <p id="statusMessage"></p>
                </div>

                <!-- Información de la Solicitud -->
                <div class="section-title">📄 Información de la Solicitud</div>
                <div class="info-grid">
                    <div class="info-box">
                        <label>Número de Solicitud</label>
                        <div class="value" id="numSolicitud"></div>
                    </div>
                    <div class="info-box">
                        <label>Cliente</label>
                        <div class="value" id="nombreCliente"></div>
                    </div>
                    <div class="info-box highlight">
                        <label>Monto Solicitado</label>
                        <div class="value" id="montoSolicitado"></div>
                    </div>
                    <div class="info-box">
                        <label>Propósito del Crédito</label>
                        <div class="value" id="proposito"></div>
                    </div>
                    <div class="info-box">
                        <label>Plazo</label>
                        <div class="value" id="plazo"></div>
                    </div>
                    <div class="info-box">
                        <label>Fecha de Solicitud</label>
                        <div class="value" id="fechaSolicitud"></div>
                    </div>
                </div>

                <!-- Sección de Aprobación -->
                <div id="approvedSection" style="display: none;">
                    <div class="alert-box success">
                        <div class="alert-title">🎉 ¡Felicidades!</div>
                        Tu crédito ha sido aprobado. A continuación encontrarás los detalles de los costos y próximos pasos.
                    </div>

                    <div class="section-title">💰 Desglose de Costos</div>
                    <div class="costs-breakdown">
                        <div class="cost-row">
                            <span class="cost-label">Monto Aprobado:</span>
                            <span class="cost-value" id="montoAprobado"></span>
                        </div>
                        <div class="cost-row">
                            <span class="cost-label">Comisión por Apertura (<span id="comisionPorcentaje"></span>):</span>
                            <span class="cost-value" id="comisionApertura"></span>
                        </div>
                    </div>

                    <div class="info-grid">
                        <div class="info-box highlight">
                            <label>Tasa de Interés Anual</label>
                            <div class="value" id="tasaInteres"></div>
                        </div>
                        <div class="info-box highlight">
                            <label>Pago Mensual</label>
                            <div class="value" id="pagoMensual"></div>
                        </div>
                        <div class="info-box">
                            <label>Fecha de Primer Pago</label>
                            <div class="value" id="primerPago"></div>
                        </div>
                        <div class="info-box">
                            <label>Ejecutivo Asignado</label>
                            <div class="value" id="ejecutivo"></div>
                        </div>
                    </div>

                    <div class="section-title">✅ Próximos Pasos</div>
                    <div class="next-steps">
                        <div class="step-item">
                            <div class="step-number">1</div>
                            <div class="step-content">
                                <div class="step-title">Firma del Contrato</div>
                                <div class="step-desc">Recibirás el contrato vía correo electrónico. Puedes firmarlo digitalmente o acudir directamente a sucursal para firma presencial.</div>
                            </div>
                        </div>
                        <div class="step-item">
                            <div class="step-number">2</div>
                            <div class="step-content">
                                <div class="step-title">Documentación Adicional</div>
                                <div class="step-desc">Presenta los documentos originales: identificación oficial, comprobante de domicilio y estado de cuenta.</div>
                            </div>
                        </div>
                        <div class="step-item">
                            <div class="step-number">3</div>
                            <div class="step-content">
                                <div class="step-title">Pago de Comisión por Apertura</div>
                                <div class="step-desc">Realiza el pago de la comisión por apertura a través de los medios disponibles.</div>
                            </div>
                        </div>
                        <div class="step-item">
                            <div class="step-number">4</div>
                            <div class="step-content">
                                <div class="step-title">Dispersión del Crédito</div>
                                <div class="step-desc">El monto será depositado en tu cuenta dentro de 48 a 72 horas después del pago de comisión y firma del contrato.</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Sección de Denegación -->
                <div id="deniedSection" style="display: none;">
                    <div class="alert-box danger">
                        <div class="alert-title">Solicitud No Aprobada</div>
                        Lamentablemente, tu solicitud de crédito no fue aprobada en este momento. Esto puede deberse a diversos factores en tu perfil crediticio.
                    </div>

                    <div class="section-title">📋 Motivos de Denegación</div>
                    <div class="info-box">
                        <label>Razones</label>
                        <div class="value" style="font-size: 16px; line-height: 1.6; white-space: pre-line;" id="motivosDenegacion"></div>
                    </div>

                    <div class="alert-box warning">
                        <div class="alert-title">💡 ¿Qué puedes hacer?</div>
                        Puedes volver a solicitar un crédito después de 90 días. Te recomendamos mejorar tu historial crediticio y capacidad de pago antes de hacer una nueva solicitud.
                    </div>
                </div>

                <!-- Timeline de Proceso -->
                <div class="section-title">📅 Línea de Tiempo del Proceso</div>
                <div class="timeline" id="timeline"></div>

                <button class="btn btn-secondary" onclick="volverAlInicio()">Consultar Otra Solicitud</button>
            </div>
        </div>
    </div>

    <script>
        // URL configurada de Google Apps Script
        const GOOGLE_SCRIPT_URL = 'https://script.google.com/macros/s/AKfycbxsZYckLgRNazxDIpWKLN3svBwfuceO0iRzgimPbbTxeNE37pP3yytQcDK8icmdFt0W1A/exec';

        async function consultarSolicitud() {
            const clientNumber = document.getElementById('clientNumber').value.trim();
            const solicitudNumber = document.getElementById('solicitudNumber').value.trim();
            const errorMsg = document.getElementById('errorMsg');
            const loadingMsg = document.getElementById('loadingMsg');
            const consultarBtn = document.getElementById('consultarBtn');

            if (!clientNumber || !solicitudNumber) {
                errorMsg.textContent = '⚠️ Por favor ingresa todos los datos';
                errorMsg.style.display = 'block';
                loadingMsg.style.display = 'none';
                return;
            }

            // Mostrar loading
            errorMsg.style.display = 'none';
            loadingMsg.style.display = 'block';
            consultarBtn.disabled = true;

            try {
                const url = `${GOOGLE_SCRIPT_URL}?clientNumber=${encodeURIComponent(clientNumber)}&solicitudNumber=${encodeURIComponent(solicitudNumber)}`;
                
                const response = await fetch(url);
                const data = await response.json();

                loadingMsg.style.display = 'none';
                consultarBtn.disabled = false;

                if (data.error) {
                    errorMsg.textContent = '❌ ' + data.error;
                    errorMsg.style.display = 'block';
                    return;
                }

                mostrarDetalles(data);

            } catch (error) {
                loadingMsg.style.display = 'none';
                consultarBtn.disabled = false;
                errorMsg.textContent = '❌ Error al consultar. Verifica tu conexión o la configuración del script.';
                errorMsg.style.display = 'block';
                console.error('Error:', error);
            }
        }

        function mostrarDetalles(solicitud) {
            document.getElementById('loginForm').style.display = 'none';
            document.getElementById('detailsSection').style.display = 'block';

            // Configurar tarjeta de estado
            const statusCard = document.getElementById('statusCard');
            const statusIcon = document.getElementById('statusIcon');
            const statusTitle = document.getElementById('statusTitle');
            const statusMessage = document.getElementById('statusMessage');

            if (solicitud.estado === 'aprobado') {
                statusCard.className = 'status-card approved';
                statusIcon.textContent = '✅';
                statusTitle.textContent = '¡Crédito Aprobado!';
                statusMessage.textContent = 'Tu solicitud ha sido aprobada exitosamente';
                document.getElementById('approvedSection').style.display = 'block';
                document.getElementById('deniedSection').style.display = 'none';
            } else {
                statusCard.className = 'status-card denied';
                statusIcon.textContent = '❌';
                statusTitle.textContent = 'Solicitud Denegada';
                statusMessage.textContent = 'Lo sentimos, tu solicitud no fue aprobada';
                document.getElementById('approvedSection').style.display = 'none';
                document.getElementById('deniedSection').style.display = 'block';
            }

            // Información básica
            document.getElementById('numSolicitud').textContent = solicitud.numeroSolicitud;
            document.getElementById('nombreCliente').textContent = solicitud.nombreCliente;
            document.getElementById('montoSolicitado').textContent = formatMoney(solicitud.montoSolicitado);
            document.getElementById('proposito').textContent = solicitud.proposito;
            document.getElementById('plazo').textContent = solicitud.plazo + ' meses';
            document.getElementById('fechaSolicitud').textContent = solicitud.fechaSolicitud;

            // Datos de aprobación
            if (solicitud.estado === 'aprobado') {
                document.getElementById('montoAprobado').textContent = formatMoney(solicitud.montoAprobado);
                document.getElementById('comisionPorcentaje').textContent = solicitud.porcentajeComision + '%';
                document.getElementById('comisionApertura').textContent = formatMoney(solicitud.comisionApertura);
                document.getElementById('tasaInteres').textContent = solicitud.tasaInteres + '%';
                document.getElementById('pagoMensual').textContent = formatMoney(solicitud.pagoMensual);
                document.getElementById('primerPago').textContent = solicitud.fechaPrimerPago;
                document.getElementById('ejecutivo').textContent = solicitud.ejecutivo;
            }

            // Datos de denegación
            if (solicitud.estado === 'denegado') {
                document.getElementById('motivosDenegacion').textContent = solicitud.motivosDenegacion || 'No especificado';
            }

            // Timeline
            const timeline = document.getElementById('timeline');
            timeline.innerHTML = '';
            if (solicitud.timeline && solicitud.timeline.length > 0) {
                solicitud.timeline.forEach(item => {
                    const div = document.createElement('div');
                    div.className = `timeline-item ${item.completado ? 'completed' : ''}`;
                    div.innerHTML = `
                        <div class="timeline-content">
                            <div class="timeline-date">${item.fecha}</div>
                            <div class="timeline-title">${item.titulo}</div>
                            <div class="timeline-desc">${item.desc}</div>
                        </div>
                    `;
                    timeline.appendChild(div);
                });
            }
        }

        function volverAlInicio() {
            document.getElementById('loginForm').style.display = 'block';
            document.getElementById('detailsSection').style.display = 'none';
            document.getElementById('clientNumber').value = '';
            document.getElementById('solicitudNumber').value = '';
        }

        function formatMoney(amount) {
            return '$' + amount.toLocaleString('es-MX', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
        }

        // Enter para consultar
        document.getElementById('solicitudNumber').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                consultarSolicitud();
            }
        });
    </script>
</body>
</html>
