# SeguidoresPlus

## Descripción

SeguidoresPlus es una aplicación web desarrollada con Django y Vue.js que ayuda a los usuarios a aumentar sus seguidores en plataformas populares como TikTok y YouTube. La aplicación ofrece estrategias, consejos y herramientas personalizadas para mejorar la presencia en estas redes sociales.

## Características

- **Autenticación de Usuario:** Registro e inicio de sesión de usuarios.
- **Panel de Control Personalizado:** Vista personalizada del panel de control con análisis de cuentas y recomendaciones.
- **Estrategias Personalizadas:** Sugerencias personalizadas basadas en el contenido del usuario.
- **Herramientas de Análisis:** Análisis de rendimiento de las cuentas en TikTok y YouTube.
- **Integración con API:** Conexión a las API de TikTok y YouTube para obtener estadísticas en tiempo real.

## Tecnologías Utilizadas

- **Backend:** Django
- **Frontend:** Vue.js
- **Base de Datos:** PostgreSQL
- **Autenticación:** JWT (JSON Web Tokens)
- **Estilos:** Tailwind CSS
- **Despliegue:** Docker y Docker Compose

## Requisitos

- Python 3.8+
- Node.js 14+
- Docker y Docker Compose

## Instalación

### Backend (Django)

1. Clona el repositorio:
    ```sh
    git clone https://github.com/tuusuario/seguidoresplus.git
    cd seguidoresplus
    ```

2. Crea y activa un entorno virtual:
    ```sh
    python -m venv env
    source env/bin/activate   # En Windows: .\env\Scripts\activate
    ```

3. Instala las dependencias:
    ```sh
    pip install -r requirements.txt
    ```

4. Realiza las migraciones y carga datos iniciales:
    ```sh
    python manage.py migrate
    python manage.py loaddata initial_data.json
    ```

5. Inicia el servidor de desarrollo:
    ```sh
    python manage.py runserver
    ```

### Frontend (Vue.js)

1. Ve a la carpeta del frontend:
    ```sh
    cd frontend
    ```

2. Instala las dependencias:
    ```sh
    npm install
    ```

3. Inicia el servidor de desarrollo:
    ```sh
    npm run serve
    ```

## Uso de Docker

1. Asegúrate de tener Docker y Docker Compose instalados.

2. Construye y levanta los contenedores:
    ```sh
    docker-compose up --build
    ```

3. La aplicación estará disponible en `http://localhost:8000`.

## Contribución

¡Las contribuciones son bienvenidas! Por favor, sigue estos pasos:

1. Haz un fork del proyecto.
2. Crea una rama nueva (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit (`git commit -m 'Agrega nueva característica'`).
4. Sube tus cambios a tu fork (`git push origin feature/nueva-caracteristica`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para cualquier pregunta o sugerencia, por favor contacta a [tuemail@example.com](mailto:tuemail@example.com).

---

¡Gracias por usar SeguidoresPlus! 🚀
