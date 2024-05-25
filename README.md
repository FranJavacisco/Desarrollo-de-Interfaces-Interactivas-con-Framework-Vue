## Desarrollo de Interfaces Interactivas con Framework Vue
https://franjavacisco.github.io/Desarrollo-de-Interfaces-Interactivas-con-Framework-Vue/

![Pokémon Silueta](https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/International_Pokémon_logo.svg/320px-International_Pokémon_logo.svg.png)

### Descripción del Proyecto

Este proyecto consiste en desarrollar una aplicación interactiva con temática de la serie Pokémon, utilizando el framework Vue.js y la PokéAPI para obtener datos. La aplicación recrea la experiencia de adivinar el nombre de un Pokémon viendo solo su silueta, similar a un segmento de la serie Pokémon.

### Funcionalidades

1. **Visualización de Pokémon:**
   - La aplicación muestra 20 Pokémon con sus imágenes iniciales filtradas para ocultar su identidad.

2. **Interacción del Usuario:**
   - Debajo de cada imagen hay un campo de entrada para que el usuario ingrese el nombre del Pokémon.
   - Al presionar el botón “Descubrir” o al pulsar la tecla Enter, se validará el nombre ingresado.

3. **Validación y Feedback:**
   - Si el nombre ingresado es correcto, se quitará el filtro de la imagen, revelando el Pokémon.
   - Si el nombre es incorrecto, se mostrará una ventana emergente indicando el error.

4. **Características Adicionales:**
   - Al descubrir un Pokémon, se oculta el campo de entrada y el botón, y se muestra el nombre del Pokémon.
   - Se muestra un contador que indica la cantidad de Pokémon descubiertos hasta el momento.

### Uso de la PokéAPI

Para obtener los datos necesarios, se consulta el siguiente endpoint de la PokéAPI, que proporciona 20 nombres de Pokémon y las URL con detalles de cada uno:

[https://pokeapi.co/api/v2/pokemon](https://pokeapi.co/api/v2/pokemon)

### Tecnologías Utilizadas

- **Framework:** Vue.js
- **Herramienta de Construcción:** Vite
- **API:** PokéAPI
- **Lenguajes:** JavaScript, HTML, CSS

### Instrucciones para Ejecutar o Visualizar

1. **Configuración del Proyecto:**
   - Asegúrate de tener Node.js y npm instalados.
   - Clona este repositorio y navega a la carpeta del proyecto.
   ```sh
   git clone https://github.com/tu-usuario/mi-proyecto-vue.git
   cd mi-proyecto-vue
   ```

2. **Instalar Dependencias:**
   - Ejecuta `npm install` para instalar las dependencias.
   ```sh
   npm install
   ```

3. **Ejecutar el Servidor de Desarrollo:**
   - Utiliza `npm run dev` para iniciar el servidor de desarrollo.
   ```sh
   npm run dev
   ```

4. **Visualizar la Aplicación:**
   - Abre tu navegador y navega a `http://localhost:5173` para visualizar la aplicación.

### Contribuir

¡Me encantaría contar con tu colaboración para mejorar este proyecto! Si tienes ideas para nuevas funcionalidades, mejoras en la interfaz, corrección de errores o cualquier otra sugerencia, no dudes en contribuir. Aquí tienes cómo puedes hacerlo:

1. **Fork del Repositorio:**
   - Haz un fork de este repositorio para tener una copia en tu cuenta de GitHub.

2. **Clonar el Repositorio:**
   - Clona el repositorio a tu máquina local.
   ```sh
   git clone https://github.com/tu-usuario/mi-proyecto-vue.git
   ```

3. **Crear una Rama para tu Funcionalidad:**
   - Crea una nueva rama para trabajar en tu funcionalidad o corrección.
   ```sh
   git checkout -b nombre-de-tu-rama
   ```

4. **Realizar tus Cambios y Confirmar:**
   - Realiza los cambios necesarios y confirma los cambios.
   ```sh
   git add .
   git commit -m "Descripción de tus cambios"
   ```

5. **Enviar tus Cambios:**
   - Envía tus cambios a tu repositorio fork.
   ```sh
   git push origin nombre-de-tu-rama
   ```

6. **Crear un Pull Request:**
   - Desde tu repositorio fork en GitHub, crea un pull request hacia el repositorio original.

¡Gracias por tu interés en contribuir! Espero tus pull requests y sugerencias para hacer de esta aplicación algo aún más increíble.

