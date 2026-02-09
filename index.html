<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Árbol de Decisión - Optimización de Producción</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        
        header {
            background: linear-gradient(to right, #2c3e50, #4a6491);
            color: white;
            padding: 30px;
            border-radius: 15px 15px 0 0;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        header h1 i {
            color: #3498db;
        }
        
        header p {
            font-size: 1.1rem;
            opacity: 0.9;
            max-width: 800px;
            line-height: 1.6;
        }
        
        .main-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-bottom: 30px;
        }
        
        @media (max-width: 1100px) {
            .main-content {
                grid-template-columns: 1fr;
            }
        }
        
        .input-section {
            background-color: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
        }
        
        .input-section h2 {
            color: #2c3e50;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid #ecf0f1;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .input-section h2 i {
            color: #3498db;
        }
        
        .factor-group {
            margin-bottom: 25px;
        }
        
        .factor-group h3 {
            color: #34495e;
            margin-bottom: 15px;
            font-size: 1.2rem;
        }
        
        .slider-container {
            margin-bottom: 20px;
        }
        
        .slider-label {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
        }
        
        .slider-label span {
            font-weight: 600;
            color: #2c3e50;
        }
        
        .slider-value {
            color: #3498db;
            font-weight: bold;
        }
        
        .slider {
            width: 100%;
            height: 10px;
            -webkit-appearance: none;
            appearance: none;
            background: #ecf0f1;
            border-radius: 5px;
            outline: none;
        }
        
        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 22px;
            height: 22px;
            border-radius: 50%;
            background: #3498db;
            cursor: pointer;
            border: 3px solid white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        
        .slider::-moz-range-thumb {
            width: 22px;
            height: 22px;
            border-radius: 50%;
            background: #3498db;
            cursor: pointer;
            border: 3px solid white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        
        .radio-group {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 10px;
        }
        
        .radio-option {
            display: flex;
            align-items: center;
            background: #f8f9fa;
            padding: 12px 15px;
            border-radius: 8px;
            border: 2px solid #e9ecef;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .radio-option:hover {
            border-color: #3498db;
            background: #e8f4fc;
        }
        
        .radio-option.selected {
            border-color: #3498db;
            background: #d4eaf7;
        }
        
        .radio-option input {
            margin-right: 10px;
            cursor: pointer;
        }
        
        .radio-option label {
            cursor: pointer;
            font-weight: 500;
        }
        
        .buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
        }
        
        .btn {
            padding: 15px 25px;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            flex: 1;
        }
        
        .btn-primary {
            background: linear-gradient(to right, #3498db, #2c80b9);
            color: white;
        }
        
        .btn-primary:hover {
            background: linear-gradient(to right, #2c80b9, #1f6390);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(52, 152, 219, 0.3);
        }
        
        .btn-secondary {
            background: #ecf0f1;
            color: #2c3e50;
        }
        
        .btn-secondary:hover {
            background: #dde4e6;
            transform: translateY(-2px);
        }
        
        .result-section {
            background-color: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
        }
        
        .result-section h2 {
            color: #2c3e50;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid #ecf0f1;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .result-section h2 i {
            color: #e74c3c;
        }
        
        .production-result {
            text-align: center;
            padding: 30px;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 10px;
            margin-bottom: 30px;
        }
        
        .production-value {
            font-size: 4.5rem;
            font-weight: 800;
            color: #2c3e50;
            margin: 15px 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        
        .production-label {
            font-size: 1.5rem;
            color: #7f8c8d;
            margin-bottom: 20px;
        }
        
        .recommendation-box {
            background-color: #fff;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            border-left: 5px solid #3498db;
            margin-bottom: 25px;
        }
        
        .recommendation-box h3 {
            color: #2c3e50;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .recommendation-box p {
            line-height: 1.6;
            color: #555;
        }
        
        .factors-impact {
            background-color: #fff;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .factors-impact h3 {
            color: #2c3e50;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .factor-impact-item {
            display: flex;
            justify-content: space-between;
            padding: 12px 0;
            border-bottom: 1px solid #f1f1f1;
        }
        
        .factor-impact-item:last-child {
            border-bottom: none;
        }
        
        .factor-name {
            font-weight: 500;
            color: #555;
        }
        
        .impact-level {
            font-weight: 600;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .high {
            background-color: #d4edda;
            color: #155724;
        }
        
        .medium {
            background-color: #fff3cd;
            color: #856404;
        }
        
        .low {
            background-color: #f8d7da;
            color: #721c24;
        }
        
        .tree-visualization {
            background-color: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            margin-top: 30px;
            overflow: auto;
        }
        
        .tree-visualization h2 {
            color: #2c3e50;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid #ecf0f1;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .tree-visualization h2 i {
            color: #27ae60;
        }
        
        .tree-container {
            display: flex;
            justify-content: center;
            padding: 20px;
            min-height: 400px;
            background: #f8f9fa;
            border-radius: 10px;
            overflow: auto;
        }
        
        .tree-node {
            padding: 15px 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            border: 2px solid #3498db;
            text-align: center;
            min-width: 180px;
            margin: 10px;
            position: relative;
            transition: all 0.3s;
        }
        
        .tree-node.active {
            background: #e8f4fc;
            border-color: #e74c3c;
            transform: scale(1.05);
            z-index: 10;
        }
        
        .tree-node.decision {
            background: #d4edda;
            border-color: #27ae60;
        }
        
        .node-title {
            font-weight: 700;
            color: #2c3e50;
            margin-bottom: 5px;
            font-size: 1rem;
        }
        
        .node-value {
            font-weight: 600;
            color: #3498db;
            font-size: 1.2rem;
        }
        
        .tree-connection {
            position: absolute;
            background: #3498db;
            height: 2px;
        }
        
        .tree-connection.vertical {
            width: 2px;
            height: 40px;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 25px;
            color: #7f8c8d;
            font-size: 0.9rem;
            border-top: 1px solid #ecf0f1;
        }
        
        .info-note {
            background-color: #e8f4fc;
            border-radius: 10px;
            padding: 20px;
            margin-top: 20px;
            border-left: 5px solid #3498db;
        }
        
        .info-note h4 {
            color: #2c3e50;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .info-note p {
            line-height: 1.6;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-industry"></i> Árbol de Decisión para Optimización de Producción</h1>
            <p>Esta herramienta utiliza un árbol de decisión para ayudarte a determinar el nivel óptimo de producción de tu empresa basándose en factores clave del mercado y de tu operación.</p>
        </header>
        
        <div class="main-content">
            <div class="input-section">
                <h2><i class="fas fa-sliders-h"></i> Factores de Decisión</h2>
                
                <div class="factor-group">
                    <h3>1. Demanda del Mercado</h3>
                    <div class="slider-container">
                        <div class="slider-label">
                            <span>Nivel de Demanda</span>
                            <span class="slider-value" id="demandValue">Media</span>
                        </div>
                        <input type="range" min="1" max="5" value="3" class="slider" id="demandSlider">
                        <div style="display: flex; justify-content: space-between; font-size: 0.85rem; color: #7f8c8d; margin-top: 5px;">
                            <span>Muy Baja</span>
                            <span>Baja</span>
                            <span>Media</span>
                            <span>Alta</span>
                            <span>Muy Alta</span>
                        </div>
                    </div>
                </div>
                
                <div class="factor-group">
                    <h3>2. Estacionalidad del Producto</h3>
                    <div class="radio-group" id="seasonalityGroup">
                        <div class="radio-option">
                            <input type="radio" id="seasonHigh" name="seasonality" value="high">
                            <label for="seasonHigh">Alta Estacionalidad</label>
                        </div>
                        <div class="radio-option">
                            <input type="radio" id="seasonMedium" name="seasonality" value="medium" checked>
                            <label for="seasonMedium">Estacionalidad Media</label>
                        </div>
                        <div class="radio-option">
                            <input type="radio" id="seasonLow" name="seasonality" value="low">
                            <label for="seasonLow">Baja Estacionalidad</label>
                        </div>
                    </div>
                </div>
                
                <div class="factor-group">
                    <h3>3. Capacidad de Producción Actual</h3>
                    <div class="slider-container">
                        <div class="slider-label">
                            <span>% de Capacidad Utilizada</span>
                            <span class="slider-value" id="capacityValue">65%</span>
                        </div>
                        <input type="range" min="0" max="100" value="65" class="slider" id="capacitySlider">
                    </div>
                </div>
                
                <div class="factor-group">
                    <h3>4. Nivel de Inventario</h3>
                    <div class="radio-group" id="inventoryGroup">
                        <div class="radio-option">
                            <input type="radio" id="inventoryLow" name="inventory" value="low">
                            <label for="inventoryLow">Bajo</label>
                        </div>
                        <div class="radio-option">
                            <input type="radio" id="inventoryMedium" name="inventory" value="medium" checked>
                            <label for="inventoryMedium">Medio</label>
                        </div>
                        <div class="radio-option">
                            <input type="radio" id="inventoryHigh" name="inventory" value="high">
                            <label for="inventoryHigh">Alto</label>
                        </div>
                    </div>
                </div>
                
                <div class="factor-group">
                    <h3>5. Costos de Producción</h3>
                    <div class="slider-container">
                        <div class="slider-label">
                            <span>Nivel de Costos</span>
                            <span class="slider-value" id="costValue">Medio</span>
                        </div>
                        <input type="range" min="1" max="5" value="3" class="slider" id="costSlider">
                        <div style="display: flex; justify-content: space-between; font-size: 0.85rem; color: #7f8c8d; margin-top: 5px;">
                            <span>Muy Bajos</span>
                            <span>Bajos</span>
                            <span>Medios</span>
                            <span>Altos</span>
                            <span>Muy Altos</span>
                        </div>
                    </div>
                </div>
                
                <div class="factor-group">
                    <h3>6. Competencia en el Mercado</h3>
                    <div class="radio-group" id="competitionGroup">
                        <div class="radio-option">
                            <input type="radio" id="competitionLow" name="competition" value="low">
                            <label for="competitionLow">Baja Competencia</label>
                        </div>
                        <div class="radio-option">
                            <input type="radio" id="competitionMedium" name="competition" value="medium" checked>
                            <label for="competitionMedium">Competencia Media</label>
                        </div>
                        <div class="radio-option">
                            <input type="radio" id="competitionHigh" name="competition" value="high">
                            <label for="competitionHigh">Alta Competencia</label>
                        </div>
                    </div>
                </div>
                
                <div class="buttons">
                    <button class="btn btn-primary" id="calculateBtn">
                        <i class="fas fa-calculator"></i> Calcular Producción Óptima
                    </button>
                    <button class="btn btn-secondary" id="resetBtn">
                        <i class="fas fa-redo"></i> Restablecer Valores
                    </button>
                </div>
                
                <div class="info-note">
                    <h4><i class="fas fa-info-circle"></i> Cómo funciona el árbol de decisión</h4>
                    <p>El sistema evalúa cada factor utilizando un algoritmo de árbol de decisión. Comienza con la demanda del mercado, luego considera la capacidad de producción, costos, inventario y competencia para determinar el nivel de producción recomendado.</p>
                </div>
            </div>
            
            <div class="result-section">
                <h2><i class="fas fa-chart-line"></i> Recomendación de Producción</h2>
                
                <div class="production-result">
                    <div class="production-label">NIVEL DE PRODUCCIÓN RECOMENDADO</div>
                    <div class="production-value" id="productionResult">--</div>
                    <div class="production-label" id="productionLabel">Introduce los datos y haz clic en Calcular</div>
                </div>
                
                <div class="recommendation-box">
                    <h3><i class="fas fa-lightbulb"></i> Recomendación Estratégica</h3>
                    <p id="strategyText">El sistema analizará los factores ingresados y proporcionará recomendaciones estratégicas específicas para tu nivel de producción óptimo.</p>
                </div>
                
                <div class="factors-impact">
                    <h3><i class="fas fa-balance-scale"></i> Impacto de los Factores</h3>
                    <div id="factorsImpactList">
                        <!-- Los factores se generarán dinámicamente -->
                        <div class="factor-impact-item">
                            <span class="factor-name">Demanda del Mercado</span>
                            <span class="impact-level high">Alto Impacto</span>
                        </div>
                        <div class="factor-impact-item">
                            <span class="factor-name">Capacidad de Producción</span>
                            <span class="impact-level high">Alto Impacto</span>
                        </div>
                        <div class="factor-impact-item">
                            <span class="factor-name">Costos de Producción</span>
                            <span class="impact-level medium">Medio Impacto</span>
                        </div>
                        <div class="factor-impact-item">
                            <span class="factor-name">Nivel de Inventario</span>
                            <span class="impact-level medium">Medio Impacto</span>
                        </div>
                        <div class="factor-impact-item">
                            <span class="factor-name">Estacionalidad</span>
                            <span class="impact-level low">Bajo Impacto</span>
                        </div>
                        <div class="factor-impact-item">
                            <span class="factor-name">Competencia</span>
                            <span class="impact-level low">Bajo Impacto</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="tree-visualization">
            <h2><i class="fas fa-project-diagram"></i> Visualización del Árbol de Decisión</h2>
            <div class="tree-container" id="treeContainer">
                <!-- El árbol se generará dinámicamente con JavaScript -->
                <div style="color: #7f8c8d; text-align: center; padding: 50px;">
                    <i class="fas fa-project-diagram" style="font-size: 3rem; margin-bottom: 15px;"></i>
                    <p>El árbol de decisión se mostrará aquí después de calcular</p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>© 2023 Sistema de Árbol de Decisión para Optimización de Producción | Herramienta de apoyo a la toma de decisiones empresariales</p>
            <p style="margin-top: 10px;">Nota: Este es un sistema de recomendación basado en algoritmos. Considere esta información como una guía y no como asesoramiento financiero.</p>
        </footer>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Elementos DOM
            const demandSlider = document.getElementById('demandSlider');
            const demandValue = document.getElementById('demandValue');
            const capacitySlider = document.getElementById('capacitySlider');
            const capacityValue = document.getElementById('capacityValue');
            const costSlider = document.getElementById('costSlider');
            const costValue = document.getElementById('costValue');
            const calculateBtn = document.getElementById('calculateBtn');
            const resetBtn = document.getElementById('resetBtn');
            const productionResult = document.getElementById('productionResult');
            const productionLabel = document.getElementById('productionLabel');
            const strategyText = document.getElementById('strategyText');
            const treeContainer = document.getElementById('treeContainer');
            const factorsImpactList = document.getElementById('factorsImpactList');
            
            // Mapeo de valores de demanda
            const demandMap = {
                1: "Muy Baja",
                2: "Baja",
                3: "Media",
                4: "Alta",
                5: "Muy Alta"
            };
            
            // Mapeo de valores de costo
            const costMap = {
                1: "Muy Bajos",
                2: "Bajos",
                3: "Medios",
                4: "Altos",
                5: "Muy Altos"
            };
            
            // Actualizar valores de sliders en tiempo real
            demandSlider.addEventListener('input', function() {
                demandValue.textContent = demandMap[this.value];
            });
            
            capacitySlider.addEventListener('input', function() {
                capacityValue.textContent = `${this.value}%`;
            });
            
            costSlider.addEventListener('input', function() {
                costValue.textContent = costMap[this.value];
            });
            
            // Manejar selección de radio buttons
            document.querySelectorAll('.radio-option').forEach(option => {
                option.addEventListener('click', function() {
                    const input = this.querySelector('input');
                    input.checked = true;
                    
                    // Actualizar clases de selección
                    document.querySelectorAll(`.radio-option[name="${input.name}"]`).forEach(opt => {
                        opt.classList.remove('selected');
                    });
                    this.classList.add('selected');
                });
            });
            
            // Inicializar selección de radio buttons
            document.querySelectorAll('input[type="radio"]:checked').forEach(radio => {
                radio.closest('.radio-option').classList.add('selected');
            });
            
            // Función para calcular producción usando árbol de decisión
            function calculateProduction() {
                // Obtener valores de los factores
                const demandLevel = parseInt(demandSlider.value); // 1-5
                const seasonality = document.querySelector('input[name="seasonality"]:checked').value;
                const capacity = parseInt(capacitySlider.value); // 0-100%
                const inventory = document.querySelector('input[name="inventory"]:checked').value;
                const costLevel = parseInt(costSlider.value); // 1-5
                const competition = document.querySelector('input[name="competition"]:checked').value;
                
                // Implementación del árbol de decisión
                let productionLevel;
                let productionLabelText;
                let strategy = "";
                
                // Nivel 1: Demanda
                if (demandLevel >= 4) {
                    // Demanda alta o muy alta
                    if (capacity >= 80) {
                        // Capacidad alta
                        if (costLevel <= 2) {
                            productionLevel = "ALTA+";
                            productionLabelText = "Producción Agresiva";
                            strategy = "Con demanda alta y capacidad disponible, aproveche los bajos costos para aumentar producción significativamente y capturar mayor cuota de mercado.";
                        } else {
                            productionLevel = "ALTA";
                            productionLabelText = "Producción Elevada";
                            strategy = "Aunque la demanda es alta, los costos elevados sugieren un aumento moderado de producción para maximizar rentabilidad.";
                        }
                    } else {
                        // Capacidad media o baja
                        if (inventory === "low") {
                            productionLevel = "MEDIA+";
                            productionLabelText = "Producción Moderada-Alta";
                            strategy = "Demanda alta pero capacidad limitada. Aumente producción gradualmente priorizando productos de mayor margen.";
                        } else {
                            productionLevel = "MEDIA";
                            productionLabelText = "Producción Moderada";
                            strategy = "Con inventario disponible, mantenga producción estable y enfoque en eficiencia operativa.";
                        }
                    }
                } else if (demandLevel >= 3) {
                    // Demanda media
                    if (competition === "high") {
                        productionLevel = "MEDIA-";
                        productionLabelText = "Producción Moderada-Baja";
                        strategy = "Demanda media con alta competencia. Mantenga producción estable o ligeramente reducida para evitar exceso de inventario.";
                    } else {
                        if (seasonality === "high") {
                            productionLevel = "MEDIA";
                            productionLabelText = "Producción Moderada";
                            strategy = "Considere ajustes estacionales. Produzca para demanda actual manteniendo flexibilidad para cambios.";
                        } else {
                            productionLevel = "MEDIA+";
                            productionLabelText = "Producción Moderada-Alta";
                            strategy = "Demanda estable sin alta competencia. Optimice producción para balancear costos y disponibilidad.";
                        }
                    }
                } else {
                    // Demanda baja o muy baja
                    if (inventory === "high") {
                        productionLevel = "BAJA";
                        productionLabelText = "Producción Reducida";
                        strategy = "Demanda baja con inventario alto. Reduzca producción para evitar acumulación excesiva de stock.";
                    } else {
                        if (costLevel >= 4) {
                            productionLevel = "BAJA-";
                            productionLabelText = "Producción Mínima";
                            strategy = "Demanda baja y costos altos. Minimice producción y enfoque en reducir costos operativos.";
                        } else {
                            productionLevel = "BAJA+";
                            productionLabelText = "Producción Baja-Moderada";
                            strategy = "Produzca solo para demanda confirmada. Mantenga operaciones mínimas para conservar recursos.";
                        }
                    }
                }
                
                // Ajuste final basado en capacidad
                if (capacity < 50 && productionLevel.includes("ALTA")) {
                    productionLevel = "MEDIA+";
                    productionLabelText = "Producción Moderada-Alta (Capacidad Limitada)";
                    strategy += " Nota: La capacidad limitada restringe el potencial de aumento de producción.";
                }
                
                // Calcular valor numérico para la visualización
                let productionValue;
                switch(productionLevel) {
                    case "ALTA+": productionValue = "95%"; break;
                    case "ALTA": productionValue = "85%"; break;
                    case "MEDIA+": productionValue = "75%"; break;
                    case "MEDIA": productionValue = "65%"; break;
                    case "MEDIA-": productionValue = "55%"; break;
                    case "BAJA+": productionValue = "45%"; break;
                    case "BAJA": productionValue = "35%"; break;
                    case "BAJA-": productionValue = "25%"; break;
                    default: productionValue = "65%";
                }
                
                // Actualizar resultados
                productionResult.textContent = productionValue;
                productionLabel.textContent = productionLabelText;
                strategyText.textContent = strategy;
                
                // Actualizar impacto de factores
                updateFactorsImpact(demandLevel, seasonality, capacity, inventory, costLevel, competition);
                
                // Generar visualización del árbol
                generateDecisionTree(demandLevel, seasonality, capacity, inventory, costLevel, competition, productionLevel);
            }
            
            // Actualizar impacto de factores
            function updateFactorsImpact(demand, seasonality, capacity, inventory, cost, competition) {
                factorsImpactList.innerHTML = "";
                
                const factors = [
                    { 
                        name: "Demanda del Mercado", 
                        value: demand,
                        impact: demand >= 4 ? "high" : demand >= 3 ? "medium" : "low"
                    },
                    { 
                        name: "Capacidad de Producción", 
                        value: capacity,
                        impact: capacity >= 80 ? "high" : capacity >= 60 ? "medium" : "low"
                    },
                    { 
                        name: "Costos de Producción", 
                        value: cost,
                        impact: cost >= 4 ? "high" : cost >= 3 ? "medium" : "low"
                    },
                    { 
                        name: "Nivel de Inventario", 
                        value: inventory,
                        impact: inventory === "low" ? "high" : inventory === "medium" ? "medium" : "low"
                    },
                    { 
                        name: "Estacionalidad", 
                        value: seasonality,
                        impact: seasonality === "high" ? "medium" : "low"
                    },
                    { 
                        name: "Competencia", 
                        value: competition,
                        impact: competition === "high" ? "medium" : "low"
                    }
                ];
                
                factors.forEach(factor => {
                    const item = document.createElement('div');
                    item.className = 'factor-impact-item';
                    
                    const impactText = factor.impact === "high" ? "Alto Impacto" : 
                                      factor.impact === "medium" ? "Medio Impacto" : "Bajo Impacto";
                    
                    item.innerHTML = `
                        <span class="factor-name">${factor.name}</span>
                        <span class="impact-level ${factor.impact}">${impactText}</span>
                    `;
                    
                    factorsImpactList.appendChild(item);
                });
            }
            
            // Generar visualización del árbol de decisión
            function generateDecisionTree(demand, seasonality, capacity, inventory, cost, competition, productionLevel) {
                treeContainer.innerHTML = "";
                
                // Crear estructura del árbol
                const tree = document.createElement('div');
                tree.style.display = 'flex';
                tree.style.flexDirection = 'column';
                tree.style.alignItems = 'center';
                tree.style.position = 'relative';
                tree.style.padding = '20px';
                
                // Nivel 1: Demanda
                const demandNode = document.createElement('div');
                demandNode.className = 'tree-node active';
                demandNode.innerHTML = `
                    <div class="node-title">Demanda</div>
                    <div class="node-value">${demandMap[demand]}</div>
                `;
                
                // Conexión vertical
                const connection1 = document.createElement('div');
                connection1.className = 'tree-connection vertical';
                connection1.style.marginTop = '10px';
                
                // Nivel 2: Capacidad
                const capacityNode = document.createElement('div');
                capacityNode.className = 'tree-node';
                capacityNode.innerHTML = `
                    <div class="node-title">Capacidad</div>
                    <div class="node-value">${capacity}%</div>
                `;
                
                // Conexión vertical
                const connection2 = document.createElement('div');
                connection2.className = 'tree-connection vertical';
                connection2.style.marginTop = '10px';
                
                // Nivel 3: Costos
                const costNode = document.createElement('div');
                costNode.className = 'tree-node';
                costNode.innerHTML = `
                    <div class="node-title">Costos</div>
                    <div class="node-value">${costMap[cost]}</div>
                `;
                
                // Conexión vertical
                const connection3 = document.createElement('div');
                connection3.className = 'tree-connection vertical';
                connection3.style.marginTop = '10px';
                
                // Nivel 4: Nodos secundarios
                const secondaryNodes = document.createElement('div');
                secondaryNodes.style.display = 'flex';
                secondaryNodes.style.gap = '30px';
                secondaryNodes.style.marginTop = '10px';
                
                // Inventario
                const inventoryNode = document.createElement('div');
                inventoryNode.className = 'tree-node';
                inventoryNode.innerHTML = `
                    <div class="node-title">Inventario</div>
                    <div class="node-value">${inventory === 'high' ? 'Alto' : inventory === 'medium' ? 'Medio' : 'Bajo'}</div>
                `;
                
                // Competencia
                const competitionNode = document.createElement('div');
                competitionNode.className = 'tree-node';
                competitionNode.innerHTML = `
                    <div class="node-title">Competencia</div>
                    <div class="node-value">${competition === 'high' ? 'Alta' : competition === 'medium' ? 'Media' : 'Baja'}</div>
                `;
                
                // Estacionalidad
                const seasonalityNode = document.createElement('div');
                seasonalityNode.className = 'tree-node';
                seasonalityNode.innerHTML = `
                    <div class="node-title">Estacionalidad</div>
                    <div class="node-value">${seasonality === 'high' ? 'Alta' : seasonality === 'medium' ? 'Media' : 'Baja'}</div>
                `;
                
                secondaryNodes.appendChild(inventoryNode);
                secondaryNodes.appendChild(competitionNode);
                secondaryNodes.appendChild(season
