/* General */
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    background-color: #f8e9f1; /* Rosa pastel */
    color: #333;
}

h1, h2 {
    margin: 0;
}

/* Header */
header {
    background-color: #bfbebe; /* Gris pastel */
    text-align: center;
    padding: 20px;
}

.logo-container {
    display: flex;
    align-items: center;
    justify-content: center;
}

.logo {
    max-width: 80px;
    margin-right: 15px;
}

header h1 {
    color: #fff;
    font-size: 28px;
    font-weight: bold;
}

/* Hero */
.hero {
    text-align: center;
    padding: 50px 20px;
    background-color: #f7cce2; /* Fondo rosa suave */
}

.hero h2 {
    font-size: 32px;
    color: #fff;
    font-weight: bold;
}

.hero p {
    font-size: 18px;
    color: #fff;
    margin: 10px 0;
}

.hero .btn {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background-color: #f4a8c4; /* Botón rosa pastel */
    color: #fff;
    text-decoration: none;
    font-size: 16px;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.hero .btn:hover {
    background-color: #e988af; /* Rosa más intenso */
}

/* Ubicación */
.ubicacion {
    text-align: center;
    padding: 40px 20px;
    background-color: #f8e9f1;
    color: #333;
}

.ubicacion h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

.ubicacion p {
    font-size: 18px;
    margin-bottom: 20px;
}

.mapa-container {
    display: flex;
    justify-content: center;
    align-items: center;
}

.mapa-container a {
    text-decoration: none;
}

.mapa-img {
    width: 80%;
    max-width: 600px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.mapa-img:hover {
    transform: scale(1.05);
}
/* Contenedor del botón de compartir */
.share-container {
    position: relative;
    text-align: center;
    margin: 30px 0;
}

/* Estilo del botón principal */
#share-button {
    padding: 10px 20px;
    font-size: 16px;
    font-family: 'Poppins', sans-serif;
    color: #fff;
    background-color: #f4a8c4; /* Botón rosa pastel */
    border: none;
    border-radius: 5px;
    cursor: pointer;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: background-color 0.3s ease, transform 0.2s ease;
}

#share-button:hover {
    background-color: #e988af; /* Rosa más intenso */
    transform: scale(1.05);
}

/* Opciones de compartir */
.share-options {
    display: none;
    position: absolute;
    top: 50px;
    left: 50%;
    transform: translateX(-50%);
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 10px;
    z-index: 1000;
    width: 250px;
    text-align: left;
}

.share-options.show {
    display: block;
}

.share-options a {
    display: block;
    padding: 8px 12px;
    font-size: 14px;
    color: #333;
    text-decoration: none;
    transition: background-color 0.3s ease;
}