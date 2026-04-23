# Evidencias de manera local
Captura de pantalla que muestra el correcto funcionamiento de docker y la insercion de los datos de empleados.
De igual manera se muestra que la api se encuentra funcionando junto con steamlit para la visualizacion de los datos.
Todo de manera local.
<img width="1915" height="1188" alt="Captura desde 2026-04-21 12-18-14" src="https://github.com/user-attachments/assets/e5d8a15b-c2aa-4ccb-a057-58b874fa83d2" />

# Evidencias de maquinas virtuales

## Api1 
Muestra el despliegue del servidor de lógica en la instancia api1. Se observa el servicio de FastAPI corriendo a través de Uvicorn, configurado para escuchar peticiones externas y gestionar la conexión hacia el entorno virtual de base de datos (base1).

<img width="820" height="445" alt="Captura desde 2026-04-23 10-56-25" src="https://github.com/user-attachments/assets/19dd7ac8-2f3b-4fce-bb08-ae008af6b139" />

## Visualizacion1
Captura del entorno de visualizacion1 ejecutando la interfaz de Streamlit. Este nodo actúa como la capa de presentación, consumiendo los datos procesados por la API distribuida para generar un dashboard interactivo y accesible vía red.

<img width="817" height="578" alt="Captura desde 2026-04-23 10-56-31" src="https://github.com/user-attachments/assets/4426f258-3825-4269-8ddb-b5bd79e7dd81" />

## Base1
Muestra la configuración y estado del entorno base1, donde reside el motor de base de datos PostgreSQL. Se evidencia la persistencia de la tabla de empleados y la disponibilidad del servicio para recibir consultas SQL desde el entorno de la API.

<img width="817" height="578" alt="Captura desde 2026-04-23 10-56-37" src="https://github.com/user-attachments/assets/f5e45837-ef42-4b6e-9b8a-a4ea6cdd8a8a" />

## Evidencia del corrrecto funcionamiento
Captura integral que demuestra el éxito de la arquitectura de tres niveles. Se observa el dashboard final cargando datos reales a través de la dirección IP de red, junto con las consolas de las máquinas virtuales sincronizadas, validando la conectividad total entre las diversas maquinas virtuales de Datos, API y Visualización.

<img width="1920" height="1200" alt="Captura desde 2026-04-23 10-56-54" src="https://github.com/user-attachments/assets/2f02b4a4-7073-42a7-975a-c0a7caba9e99" />
