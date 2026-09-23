# Plantilla de entrega individual

## 1. Datos generales

- **Nombre o alias**: NATSAN
- **Fecha**: 2 de septiembre de 2026

## 2. Qué estoy entregando

- [x] Mi archivo CSV
- [x] Mi vista previa PNG
- [x] Mi reflexión breve
- [x] Mi nombre o alias, si corresponde

## 3. Evidencia

- **CSV**: NATSAN-rgb-discovery-output.csv (adjunto en esta PR)
- **PNG**: NATSAN-rgb-discovery-revealed.png (adjunto en esta PR)
- **Notas**: Corrí el Colab RGB paso a paso primero con la imagen de ejemplo. [Después lo repetí con una imagen mía / Me quedé con la imagen de ejemplo.]

## 4. Reflexión breve

- **¿Qué descubriste?** Que la planilla ya era la imagen. Cada celda del CSV tiene un código de color como #FFFFFF (blanco) o #1E1612 (casi negro), y cada celda es un píxel. El CSV tiene 33 columnas y 50 filas, y en el PNG se ve exactamente esa misma grilla, pero pintada.
- **¿Cómo te diste cuenta?** Abrí el CSV y el PNG al mismo tiempo y los comparé. Donde el CSV tenía códigos que empiezan con F o E, la imagen era clara; donde tenía códigos que empiezan con 1, 2 o 3, la imagen era oscura. Ahí entendí que los datos y la imagen eran lo mismo escrito de dos formas.
- **¿Qué te costó más?** La verdad, fue difícil. En Colab me perdí y no sabía qué celda seguía. Además me salió un error (RGBDiscoveryError) porque escribí mi alias como "nat_san", y tenía que ser NATSAN: seis letras en mayúscula, sin guion bajo ni espacios. Tuve que volver a ejecutar la celda con el alias bien escrito y recién ahí pude seguir.
- **¿Qué aprendiste al colaborar?** Que pedir ayuda sirve para destrabarme, pero la explicación tiene que salir de mí, porque si no, no la entiendo ni yo.

## 5. Checklist antes de enviar

- [x] Mi explicación se entiende sola.
- [x] Mi evidencia muestra el resultado.
- [x] No subí datos privados.
- [x] No agregué información sensible.
- [x] Mi entrega representa mi propio trabajo.

## 6. Propuesta de entrega/cambio

- **Título**: Entrega Desafío RGB - NATSAN
- **Resumen corto**: Entrego el CSV y el PNG generados en el Colab del desafío RGB, más mi reflexión sobre cómo una planilla de códigos de color se convierte en una imagen.
- **Qué debería revisar quien corrige**: Mirá primero la evidencia (CSV y PNG) y después mi reflexión.
