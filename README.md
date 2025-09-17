# almacenamiento-web
index.html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tipos de Almacenamiento de Datos</title>
  <!-- Tailwind CSS via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-900">
  <header class="bg-blue-600 text-white p-4 text-center text-2xl font-bold">
    Tipos de Almacenamiento de Datos
  </header>

  <!-- Sección de Filtro -->
  <section class="max-w-4xl mx-auto p-4">
    <h2 class="text-xl font-semibold mb-2">Filtrar por categoría</h2>
    <select class="border p-2 rounded w-full md:w-1/2">
      <option value="todos">Todos</option>
      <option value="primario">Almacenamiento Primario</option>
      <option value="secundario">Almacenamiento Secundario</option>
      <option value="nube">Almacenamiento en la Nube</option>
    </select>
  </section>

  <!-- Sección de Tarjetas -->
  <section class="max-w-4xl mx-auto p-4 grid gap-4 md:grid-cols-3">
    <div class="bg-white p-4 rounded-2xl shadow">
      <h3 class="font-bold text-lg">RAM</h3>
      <p class="text-sm">Memoria de acceso aleatorio, rápida pero volátil.</p>
    </div>
    <div class="bg-white p-4 rounded-2xl shadow">
      <h3 class="font-bold text-lg">Disco Duro</h3>
      <p class="text-sm">Almacenamiento masivo, ideal para datos permanentes.</p>
    </div>
    <div class="bg-white p-4 rounded-2xl shadow">
      <h3 class="font-bold text-lg">Nube</h3>
      <p class="text-sm">Accesible desde internet, ideal para colaboración.</p>
    </div>
  </section>

  <!-- Tabla Comparativa -->
  <section class="max-w-4xl mx-auto p-4">
    <h2 class="text-xl font-semibold mb-2">Comparativa</h2>
    <div class="overflow-x-auto">
      <table class="w-full border-collapse border border-gray-300">
        <thead class="bg-gray-200">
          <tr>
            <th class="border border-gray-300 p-2">Tipo</th>
            <th class="border border-gray-300 p-2">Velocidad</th>
            <th class="border border-gray-300 p-2">Costo</th>
            <th class="border border-gray-300 p-2">Volatilidad</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="border border-gray-300 p-2">RAM</td>
            <td class="border border-gray-300 p-2">Muy Alta</td>
            <td class="border border-gray-300 p-2">Medio</td>
            <td class="border border-gray-300 p-2">Volátil</td>
          </tr>
          <tr>
            <td class="border border-gray-300 p-2">Disco Duro</td>
            <td class="border border-gray-300 p-2">Media</td>
            <td class="border border-gray-300 p-2">Bajo</td>
            <td class="border border-gray-300 p-2">No volátil</td>
          </tr>
          <tr>
            <td class="border border-gray-300 p-2">Nube</td>
            <td class="border border-gray-300 p-2">Depende de internet</td>
            <td class="border border-gray-300 p-2">Variable</td>
            <td class="border border-gray-300 p-2">No volátil</td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <!-- Glosario -->
  <section class="max-w-4xl mx-auto p-4">
    <h2 class="text-xl font-semibold mb-2">Glosario</h2>
    <dl class="space-y-2">
      <div>
        <dt class="font-bold">Volátil</dt>
        <dd>Se pierde la información al apagar el equipo.</dd>
      </div>
      <div>
        <dt class="font-bold">No volátil</dt>
        <dd>Los datos permanecen aun sin energía.</dd>
      </div>
    </dl>
  </section>

  <!-- Quiz -->
  <section class="max-w-4xl mx-auto p-4">
    <h2 class="text-xl font-semibold mb-2">Mini Quiz</h2>
    <p class="mb-2">¿Cuál es el tipo de almacenamiento más rápido?</p>
    <button class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700" onclick="alert('Correcto ✅: La RAM es la más rápida.')">
      RAM
    </button>
    <button class="bg-gray-300 px-4 py-2 rounded hover:bg-gray-400 ml-2" onclick="alert('Incorrecto ❌: El disco duro es más lento que la RAM.')">
      Disco Duro
    </button>
  </section>

  <footer class="bg-gray-200 text-center p-4 mt-6">
    &copy; 2025 Proyecto Educativo
  </footer>
</body>
</html>
