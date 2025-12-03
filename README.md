📖 El Recetario de Nini

Bienvenido al repositorio digital de las recetas de la familia. Este proyecto busca preservar y compartir el legado culinario de Nini, digitalizando sus manuscritos originales en una interfaz moderna, accesible y fácil de usar.

🌟 Características

Búsqueda Inteligente: Encuentra recetas por ingredientes o título.

Filtros: Categorías para platos Salados, Dulces, Licores, etc.

Calculadora de Porciones: Ajusta automáticamente las cantidades de los ingredientes según los comensales.

Modo Nostalgia: Visualiza la foto del manuscrito original de Nini con un solo clic.

Apto Celíacos: Indicadores visuales de recetas Gluten Free o Con Gluten.

🚀 Cómo ver el recetario

Puedes visitar la versión online del recetario aquí:

[Enlace a tu GitHub Pages aquí - Aparecerá después de configurar Settings > Pages]

Si quieres verlo en tu computadora sin internet:

Descarga este repositorio (Botón verde Code > Download ZIP).

Descomprime la carpeta.

Haz doble clic en el archivo index.html.

🛠️ Cómo agregar nuevas recetas

Si encuentras más hojas del cuaderno de Nini, puedes agregarlas editando el archivo index.html.

Abre index.html con un editor de texto (como Notepad++ o VS Code).

Busca la sección const recipesDB = [...].

Agrega un nuevo bloque siguiendo este formato:

{
    id: 50, // Número siguiente
    title: "Nombre de la Receta",
    category: "Dulce", // O "Salado", "Bebida"
    containsGluten: true, // o false
    imgFile: "NOMBRE_DE_LA_FOTO.jpg", // Asegúrate de subir la foto a la carpeta
    ingredients: [
        { qty: 200, unit: "gr", name: "Harina" },
        { qty: 100, unit: "gr", name: "Manteca" }
    ],
    instructions: "Paso 1. Mezclar todo..."
},


📸 Créditos

Recetas originales: Nini

Digitalización y Desarrollo: [Tu Nombre]

Hecho con ❤️ y harina leudante.