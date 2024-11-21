# Challenge AluraGeek

**Challenge AluraGeek** es una aplicación web que permite a los usuarios gestionar una lista de productos. Los usuarios pueden **visualizar**, **agregar** y **eliminar** productos, utilizando tecnologías frontend modernas y un servidor JSON simulado.

## 🔥 Características

- **Visualizar** productos existentes.
- **Agregar** nuevos productos proporcionando nombre, precio e imagen.
- **Eliminar** productos de la lista.
- Manejo dinámico del DOM para actualizar productos sin recargar la página.
- Conexión con un servidor simulado mediante **json-server** para realizar operaciones **CRUD**.

## 💻 Tecnologías Utilizadas

- **HTML5/CSS3**: Estructura y diseño.
- **JavaScript (ES6 Modules)**: Lógica e interacción.
- **json-server**: API RESTful simulada.
- **Fetch API**: Solicitudes HTTP.

## 🚀 Instalación

### Requisitos previos

- **Node.js** instalado.
- **Instalacion de servidor json** 
```bash
  npm install json-server
```


### Pasos

1. Clona este repositorio:

   ```bash
   git clone https://github.com/t-brillyth/challenge-AluraGeek
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd challenge-AluraGeek
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Inicia el servidor JSON estando dentro del tu carpeta donde este la DB:

   ```bash
   npx json-server --watch db.json --port 3001
   ```

5. Abre `index.html` en tu navegador o puedes correr tu Live server

## 🗂️ Estructura del Proyecto

- **index.html**: Estructura de la aplicación.
- **css/reset.css**: Reinicio de estilos.
- **css/style.css**: Estilos personalizados.
- **js/main.js**: Lógica de agregar y eliminar productos.
- **js/product-services.js**: Solicitudes HTTP (GET, POST, DELETE).
- **db.json**: Base de datos simulada para **json-server**.

## 🛠️ API Simulada

**json-server** simula una API RESTful con las siguientes rutas:

- `GET /products`: Lista los productos.
- `POST /products`: Crea un nuevo producto.
- `DELETE /products/:id`: Elimina un producto.

## 📋 Uso de la Aplicación

1. **Visualizar Productos**: Los productos se cargan automáticamente desde el servidor simulado al abrir la página.
   
2. **Agregar Producto**: Completa el formulario con nombre, precio y URL de la imagen, luego haz clic en **"Enviar"**.
   
3. **Eliminar Producto**: Haz clic en el ícono de la papelera para eliminar un producto.

---
Desarrollado por Tania Forero