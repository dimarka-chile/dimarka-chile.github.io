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

## Cómo probarlo

1. Elegir "Aluvión · Las Condes" y presionar **EMITIR ALERTA**: aparece la alerta SAE simulada.
2. Presionar **Ver mapa y ruta**. Probar las ubicaciones 1 (zona roja), 2 (amarilla) y 3 (fuera de riesgo), y el botón **♿ Movilidad reducida**.
3. Usar ▶ para ver avanzar el aluvión y el botón **SOS**.

Proyecto estudiantil (Ingeniería Civil Industrial UV y Arquitectura U. de Chile) para el concurso "Innovando con Ingeniería".

- Es una simulación: no usa datos ni logos oficiales y no envía nada a servicios de emergencia.
- Mapas y datos: © colaboradores de OpenStreetMap, Esri y Open-Meteo.
