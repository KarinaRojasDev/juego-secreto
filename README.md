# 🎮 Juego del Número Secreto

Este proyecto es un juego interactivo desarrollado en **HTML, CSS y JavaScript**. El objetivo del juego es que el usuario intente adivinar un número secreto generado aleatoriamente.

## 🚀 Tecnologías Utilizadas
- **HTML**: Estructura de la página web.
- **CSS**: Diseño y estilos.
- **JavaScript**: Lógica del juego, manipulación del DOM y generación del número aleatorio.

## 🎯 Funcionamiento
- El usuario ingresa un número entre **1 y 10**.
- El sistema indica si el número es **mayor o menor** que el número secreto.
- El usuario sigue intentando hasta adivinarlo.
- Se muestra el número de intentos realizados.
- Se puede reiniciar el juego con un botón.

## 📂 Estructura del Proyecto
"""

    # Recorre el directorio y estructura los archivos en el README
    for root, dirs, files in os.walk("."):
        nivel = root.replace(os.getcwd(), "").count(os.sep)
        indentacion = "  " * nivel
        contenido += f"{indentacion}- 📁 {os.path.basename(root)}/\n"
        sub_indentacion = "  " * (nivel + 1)
        for file in files:
            contenido += f"{sub_indentacion}- 📄 {file}\n"

    contenido += """
## 🛠️ Cómo Ejecutarlo
1. **Clona** este repositorio:
   ```sh
   git clone https://github.com/usuario/juego-numero-secreto.git
