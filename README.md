<!DOCTYPE html>
<html>
<head>
    <title>Inventario - Repuestos Disponibles</title>
    <style>
        body { font-family: Arial; margin: 40px; }
        table { border-collapse: collapse; width: 100%; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: left; }
        th { background-color: #f2f2f2; }
    </style>
</head>
<body>
    <h1>📦 Inventario de Repuestos</h1>
    <div id="inventario">Cargando inventario...</div>
    
    <script>
        // Aquí luego pondrás el código para cargar tus datos
        document.getElementById('inventario').innerHTML = `
            <table>
                <tr><th>Repuesto</th><th>Stock</th><th>Precio</th></tr>
                <tr><td>Filtro de aceite</td><td>15</td><td>$25</td></tr>
                <tr><td>Pastillas de freno</td><td>8</td><td>$45</td></tr>
            </table>
        `;
    </script>
</body>
</html>
