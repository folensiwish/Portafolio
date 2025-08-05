# Mi Portafolio Web

## Descripción

Este es mi portafolio web personal, donde muestro mis proyectos, habilidades y experiencia como desarrollador.

**Versión:** 1.0

**Estado:** En desarrollo

## Características principales

*   **Diseño responsive:** El sitio web se adapta a diferentes tamaños de pantalla, desde ordenadores de escritorio hasta dispositivos móviles.
*   **Presentación de proyectos:** Muestra una selección de mis proyectos más recientes y relevantes.
*   **Información de contacto:** Proporciona una forma fácil para que los visitantes se pongan en contacto conmigo.
*   **Tecnologías utilizadas:**
    *   Flask (Python)
    *   HTML
    *   CSS
    *   JavaScript (opcional)
    *   Bootstrap (opcional, para el layout responsive)
    *   Gunicorn (servidor WSGI)
    *   SendGrid (para el envío de correos electrónicos)

## Instalación (si aplica)

Si deseas ejecutar este proyecto localmente, sigue estos pasos:

1.  Clona el repositorio:

    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```

2.  Crea un entorno virtual:

    ```bash
    python -m venv venv
    ```

3.  Activa el entorno virtual:

    *   En Windows:

        ```bash
        venv\Scripts\activate
        ```

    *   En macOS y Linux:

        ```bash
        source venv/bin/activate
        ```

4.  Instala las dependencias:

    ```bash
    pip install -r requirements.txt
    ```

5.  Configura las variables de entorno:

    *   Crea un archivo `.env` y define las variables necesarias (por ejemplo, la clave de API de SendGrid).

6.  Ejecuta la aplicación:

    ```bash
    gunicorn app:app
    ```

    (o `gunicorn app:create_app` si usas el patrón de fábrica de aplicaciones)

## Despliegue

Este proyecto está desplegado en Railway.

## Créditos

*   Este portafolio fue creado por Alberto Fernández.

## Licencia

[MIT](LICENSE) (opcional)
