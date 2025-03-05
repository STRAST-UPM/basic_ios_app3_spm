# 📱 basic_app

## 📦 Librerías Importadas
Las siguientes librerías han sido importadas y utilizadas en la aplicación:

### 🔹 **Redes y Peticiones HTTP**
- **Alamofire (5.10.2)** → Cliente HTTP moderno basado en Swift para realizar peticiones de red.

### 🔹 **Firebase (Core y Servicios)**
- **Firebase (11.9.0)** → Core de Firebase para la configuración principal.
- **FirebaseCore** → Librería base para Firebase.
- **FirebaseAnalytics** → Seguimiento de eventos y métricas en la app.
- **AppCheck (11.2.0)** → Protección contra el uso indebido de Firebase.
- **GoogleAppMeasurement (11.9.0)** → Seguimiento de métricas avanzadas.
- **GoogleDataTransport (10.1.0)** → Transporte de datos en Firebase.
- **GoogleUtilities (8.0.2)** → Utilidades internas de Firebase.
- **GTMSessionFetcher (4.4.0)** → Manejo de sesiones HTTP en Firebase.
- **InteropForGoogle (10.1.0)** → Soporte de interoperabilidad para Google SDK.

### 🔹 **Base de Datos y Serialización**
- **leveldb (1.22.5)** → Base de datos ligera utilizada por Firebase Firestore.
- **nanopb (2.30901.0)** → Codificación de datos en Firebase.
- **SwiftProtobuf (1.29.0)** → Implementación de Protocol Buffers en Swift.

### 🔹 **gRPC y Comunicación Remota**
- **gRPC (1.69.0)** → Implementación de gRPC en Swift para comunicación eficiente.

### 🔹 **Utilidades**
- **Promises (2.4.0)** → Biblioteca de promesas para manejar asincronía de manera eficiente.

## 🔧 Instalación
Este proyecto utiliza **Swift Package Manager (SPM)** para la gestión de dependencias. Para instalar las librerías, sigue estos pasos:

1. **Abrir el proyecto en Xcode**.
2. Ir a **File > Add Packages**.
3. Agregar las siguientes dependencias mediante sus URLs:

   - **Alamofire** → `https://github.com/Alamofire/Alamofire.git`
   - **Firebase SDK** → `https://github.com/firebase/firebase-ios-sdk.git`
   - **Google Utilities** → `https://github.com/google/promises.git`


