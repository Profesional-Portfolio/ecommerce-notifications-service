# Notification Service

Servicio encargado de la comunicación en tiempo real con los usuarios finales mediante WebSockets.

## 📋 Características
-   🔔 **Tiempo Real**: Envío de alertas inmediatas vía WebSockets.
-   ⚡ **Velocidad**: Uso de Redis como Pub/Sub para escalabilidad horizontal.

## 🛠️ Tecnologías
-   NestJS
-   TypeScript
-   Socket.io
-   Redis

## 🚀 Configuración
1.  **Variables de Entorno**:
    ```bash
    cp .env.example .env
    ```
2.  **WebSockets**: El servicio escucha por defecto en el puerto 3003.
3.  **Ejecución**:
    ```bash
    pnpm run start:dev
    ```