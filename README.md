# Yukita

## Esquema de Colores Yuquita para Windows Terminal

# Paleta de Colores Yuquita para Windows Terminal

**Yuquita** es una paleta de colores para Windows Terminal que ofrece un esquema visual elegante y moderno con tonos oscuros y vibrantes. Ideal para quienes buscan una experiencia visual atractiva y contrastante en su terminal.

## Características

- **Tonos Oscuros**: Ideal para un entorno de trabajo de bajo brillo.
- **Colores Vibrantes**: Aumenta la legibilidad y la estética de la terminal.
- **Contraste Atractivo**: Facilita la visualización prolongada sin fatiga ocular.

## Configuración

Para aplicar la paleta de colores Yuquita en Windows Terminal, sigue estos pasos:

### 1. Abre Windows Terminal

Busca y abre "Windows Terminal" desde el menú de inicio.

### 2. Accede a la Configuración

Haz clic en la flecha hacia abajo en la parte superior de la ventana y selecciona "Settings" (Configuración), o presiona `Ctrl` + `,`.

### 3. Edita el Archivo de Configuración

Dependiendo de tu versión de Windows Terminal, la configuración se encuentra en un archivo `profiles.json` o `settings.json`. Busca el archivo adecuado en tu sistema.

### 4. Añade la Paleta de Colores

Inserta la siguiente configuración en la sección "schemes":

```json
{
  "schemes": [
    {
      "name": "Yuquita",
      "foreground": "#eff0eb",
      "background": "#282a36",
      "selectionBackground": "#3e404a",
      "cursorColor": "#97979b",
      "black": "#282a36",
      "red": "#ff5c57",
      "green": "#5af78e",
      "yellow": "#f3f99d",
      "blue": "#57c7ff",
      "purple": "#ff6ac1",
      "cyan": "#9aedfe",
      "white": "#f1f1f0",
      "brightBlack": "#686868",
      "brightRed": "#ff5c57",
      "brightGreen": "#5af78e",
      "brightYellow": "#f3f99d",
      "brightBlue": "#57c7ff",
      "brightPurple": "#ff6ac1",
      "brightCyan": "#9aedfe",
      "brightWhite": "#eff0eb"
    }
  ]
}
```

### 5. Aplica el Esquema de Colores

En la configuración de Windows Terminal, selecciona el perfil al que deseas aplicar el esquema.
En el campo "colorScheme", usa el nombre Yuquita.
Ejemplo:

```json
{
  "profiles": {
    "list": [
      {
        "guid": "{your-profile-guid}",
        "name": "Profile Name",
        "colorScheme": "Yuquita"
      }
    ]
  }
}
```

### 6. Guarda y Cierra la Configuración

Guarda los cambios y cierra el editor de configuración. La nueva paleta de colores Yuquita debería estar activa en tu Windows Terminal.

### Nota

Asegúrate de revisar la documentación específica de tu versión de Windows Terminal, ya que los pasos pueden variar ligeramente según la versión.

### Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar la paleta o agregar nuevas características, por favor, envía un pull request o abre un issue.

Contacto
Para cualquier pregunta o comentario, no dudes en abrir un issue en el repositorio de GitHub.
