# DIMARKA · Simulador de alertas

**Prototipo web (simulación no oficial).** Se abre en el navegador del celular o del computador; no requiere instalación:

👉 **https://dimarka-chile.github.io/**

DIMARKA propone ampliar el Sistema de Alerta de Emergencia (SAE, Cell Broadcast) con un enlace liviano. Ese enlace abre una página que adapta la instrucción a la ubicación de cada persona. La página muestra:

- qué está pasando y el nivel de riesgo;
- un mapa de la zona de peligro;
- una ruta accesible, también para personas con movilidad reducida;
- un botón de ayuda (SOS) geolocalizado.

## Escenarios

- **Aluvión · Las Condes:** reconstrucción del evento del 8 de octubre de 2026 a partir de prensa y cierres viales. Muestra zonas roja y amarilla sobre las calles por donde bajó el flujo, y la salida lateral del cauce o la evacuación vertical según el tiempo disponible.
- **Tsunami · Valparaíso:** sismo en el mar, con ruta a pie hacia zonas altas y lejos de la costa.
- **Incendio · Constitución:** reconstrucción del incendio Las Máquinas y la destrucción de Santa Olga (25–26 de enero de 2017). El área quemada, el frente activo y la lluvia de pavesas salen de focos satelitales reales (NASA FIRMS). Cada persona recibe una zona segura asignada según su capacidad y una ruta que evita los caminos cortados por el fuego.

## Cómo probarlo

1. Elegir "Aluvión · Las Condes" y presionar **EMITIR ALERTA**: aparece la alerta SAE simulada.
2. Presionar **Ver mapa y ruta**. Probar las ubicaciones 1 (zona roja), 2 (amarilla) y 3 (fuera de riesgo), y el botón **♿ Movilidad reducida**.
3. Usar ▶ para ver avanzar el aluvión y el botón **SOS**.
4. En "Incendio · Constitución", usar ▶ y ⏭ para recorrer la noche del 25 al 26 de enero. Con la ubicación 2, la alerta pasa de "Prepárese" a "Evacúe ahora" y vuelve a sonar.

Mapas y datos del incendio: NASA FIRMS (focos MODIS y VIIRS) y ESA WorldCover 2021.

Proyecto estudiantil (Ingeniería Civil Industrial UV y Arquitectura U. de Chile) para el concurso "Innovando con Ingeniería".

- Es una simulación: no usa datos ni logos oficiales y no envía nada a servicios de emergencia.
- Mapas y datos: © colaboradores de OpenStreetMap, Esri y Open-Meteo.
