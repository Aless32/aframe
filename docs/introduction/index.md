---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escena A-Frame con Texto y Diseños</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
</head>
<body>
    <a-scene>
        <!-- Caja 3D -->
        <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>

        <!-- Esfera 3D -->
        <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>

        <!-- Cilindro 3D -->
        <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>

        <!-- Texto -->
        <a-text value="¡Bienvenido a mi escena A-Frame!" position="-2 2.5 -4" rotation="0 0 0" color="#FFFFFF" width="6"></a-text>

        <!-- Diseño adicional -->
        <a-entity geometry="primitive: plane; width: 2; height: 2" material="color: #FF0000" position="0 1 -4"></a-entity>

        <!-- Luz -->
        <a-light type="point" position="2 3 -4" intensity="0.5" color="#FFF"></a-light>

        <!-- Cámara -->
        <a-camera position="0 1.6 0"></a-camera>
    </a-scene>
</body>
</html>
