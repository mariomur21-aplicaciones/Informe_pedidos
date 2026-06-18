<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visor de Pedidos - FERCOSUR</title>
    <style>
        /* Estilos optimizados para formato vertical de celular */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f6f9;
            margin: 0;
            padding: 10px;
            color: #333;
        }
        .header {
            background-color: #1e293b;
            color: #ffffff;
            padding: 15px;
            text-align: center;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        .header h1 {
            margin: 0;
            font-size: 1.4rem;
        }
        .search-box {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 1rem;
        }
        .lista-pedidos {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        /* Tarjeta de cada pedido */
        .pedido-card {
            background-color: #ffffff;
            border-left: 5px solid #3b82f6; /* Línea azul de énfasis */
            border-radius: 6px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            display: flex;
            flex-direction: column;
            gap: 5px;
        }
        .pedido-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            font-size: 1.05rem;
            color: #1e293b;
        }
        .pedido-cliente {
            font-size: 0.95rem;
            color: #475569;
            text-transform: uppercase;
        }
        .pedido-meta {
            display: flex;
            justify-content: space-between;
            font-size: 0.8rem;
            color: #94a3b8;
            margin-top: 5px;
        }
        .pedido-valor {
            color: #10b981; /* Verde profesional para valores financieros */
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Pedidos Recientes</h1>
    </div>

    <input type="text" class="search-box" placeholder="Buscar por cliente o número...">

    <div class="lista-pedidos" id="contenedor-pedidos">
        
        <div class="pedido-card">
            <div class="pedido-header">
                <span>Pedido #581</span>
                <span class="pedido-valor">$284.790</span> 
            </div>
            <div class="pedido-cliente">MARTINEZ PONCE FRANKLIN JAVIER</div>
            <div class="pedido-meta">
                <span>Vendedor: Roland Lopez</span>
                <span>01/06/2026</span>
            </div>
        </div>

    </div>

</body>
</html>
