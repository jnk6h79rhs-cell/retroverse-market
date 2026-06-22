<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RetroVerse Market - Gestión de Registros</title>
    <style>
        body { font-family: 'Courier New', Courier, monospace; background-color: #1a1a1a; color: #00ff66; margin: 20px; }
        h1, h2 { color: #ff00ff; text-shadow: 2px 2px #000; }
        .container { display: flex; gap: 20px; flex-wrap: wrap; }
        .card { background: #2a2a2a; padding: 20px; border: 2px solid #00ff66; border-radius: 8px; flex: 1; min-width: 300px; }
        label { display: block; margin-top: 10px; font-weight: bold; }
        input, select { width: 100%; padding: 8px; margin-top: 5px; background: #000; color: #00ff66; border: 1px solid #ff00ff; box-sizing: border-box;}
        button { background: #ff00ff; color: white; border: none; padding: 10px 15px; margin-top: 15px; cursor: pointer; font-weight: bold; width: 100%; }
        button:hover { background: #00ff66; color: #000; }
        table { width: 100%; border-collapse: collapse; margin-top: 20px; background: #2a2a2a; }
        th, td { border: 1px solid #00ff66; padding: 10px; text-align: left; }
        th { background-color: #ff00ff; color: black; }
        .badge { background: #333; padding: 3px 6px; border-radius: 4px; font-size: 0.9em; }
    </style>
</head>
<body>

    <h1>🕹️ RetroVerse Digital Market</h1>
    <p>Simulador de estructura de datos: Registro y Clave Primaria (Unidad 2)</p>
    <hr>

    <div class="container">
        <div class="card">
            <h2>Cargar Nuevo Registro</h2>
            <form id="registroForm">
                <label>ID Producto (CLAVE ÚNICA - Alfanumérico):</label>
                <input type="text" id="id_producto" placeholder="Ej: RET-1985-NES-01" required>

                <label>Nombre del Artículo:</label>
                <input type="text" id="nombre" placeholder="Ej: Nintendo NES" required>

                <label>Categoría:</label>
                <select id="categoria">
                    <option value="Consolas">Consolas</option>
                    <option value="Computadoras">Computadoras</option>
                    <option value="Software">Software</option>
                </select>

                <label>Fabricante:</label>
                <input type="text" id="fabricante" placeholder="Ej: Nintendo" required>

                <label>Año de Lanzamiento:</label>
                <input type="number" id="anio" placeholder="Ej: 1985" required>

                <label>Estado de Conservación:</label>
                <select id="estado">
                    <option value="Nuevo">Nuevo (Inmaculado)</option>
                    <option value="Excelente">Excelente</option>
                    <option value="Bueno">Bueno</option>
                    <option value="Para repuesto">Para repuesto</option>
                </select>

                <label>Precio (USD):</label>
                <input type="number" step="0.01" id="precio" placeholder="Ej: 199.99" required>

                <label>
                    <input type="checkbox" id="caja"> ¿Incluye caja original?
                </label>

                <button type="submit">Guardar Registro en Inventario</button>
            </form>
        </div>

        <div class="card" style="flex: 2;">
            <h2>Inventario Actual (Estructuras Almacenadas)</h2>
            <table id="tablaProductos">
                <thead>
                    <tr>
                        <th>Clave (ID)</th>
                        <th>Nombre</th>
                        <th>Fabricante (Año)</th>
                        <th>Estado</th>
                        <th>Precio</th>
                        <th>¿Caja?</th>
                    </tr>
                </thead>
                <tbody>
                    </tbody>
            </table>
        </div>
    </div>

    <script>
        // Simulación de Base de Datos en memoria
        const inventario = {};

        // Carga de datos iniciales
        inventario["RET-1989-GB-0042"] = {
            id_producto: "RET-1989-GB-0042",
            nombre: "Game Boy Classic",
            categoria: "Consolas",
            fabricante: "Nintendo",
            anio: 1989,
            estado: "Excelente",
            precio: 150.00,
            caja: true
        };

        function actualizarTabla() {
            const tbody = document.querySelector("#tablaProductos tbody");
            tbody.innerHTML = "";

            // Recorremos la estructura usando sus claves
            for (let clave in inventario) {
                const prod = inventario[clave];
                const fila = `<tr>
                    <td><span class="badge" style="color:#ff00ff;">${prod.id_producto}</span></td>
                    <td><b>${prod.nombre}</b><br><small>${prod.categoria}</small></td>
                    <td>${prod.fabricante} (${prod.anio})</td>
                    <td>${prod.estado}</td>
                    <td>$${prod.precio}</td>
                    <td>${prod.caja ? "✅ Sí" : "❌ No"}</td>
                </tr>`;
                tbody.innerHTML += fila;
            }
        }

        // Manejar el formulario
        document.getElementById("registroForm").addEventListener("submit", function(e) {
            e.preventDefault();

            const clave = document.getElementById("id_producto").value.trim();

            // Validar unicidad de la clave
            if (inventario[clave]) {
                alert("❌ ERROR DE INTEGRIDAD: La clave '" + clave + "' ya existe. No se permiten registros duplicados.");
                return;
            }

            // Crear la estructura del registro
            inventario[clave] = {
                id_producto: clave,
                nombre: document.getElementById("nombre").value,
                categoria: document.getElementById("categoria").value,
                fabricante: document.getElementById("fabricante").value,
                anio: parseInt(document.getElementById("anio").value),
                estado: document.getElementById("estado").value,
                precio: parseFloat(document.getElementById("precio").value),
                caja: document.getElementById("caja").checked
            };

            alert("¡Registro guardado exitosamente!");
            document.getElementById("registroForm").reset();
            actualizarTabla();
        });

        // Primera renderización
        actualizarTabla();
    </script>
</body>
</html>
