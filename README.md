# 📱 basic_app

## 📦 Librerías Importadas
A continuación, se detallan las librerías utilizadas en la aplicación:

### 🔹 Redes y Autenticación
- **Alamofire (5.10.2)** → Cliente HTTP moderno basado en Swift.
- **AppAuth (1.7.6)** → Implementación del estándar OAuth 2.0 y OpenID Connect.

### 🔹 Seguridad y Cifrado
- **abseil (1.2024072200.0)** → Biblioteca de soporte utilizada en el ecosistema de Google.
- **GoogleUtilities (8.0.2)** → Utilidades internas de Firebase y Google.
- **GTMSessionFetcher (4.4.0)** → Framework para gestionar sesiones HTTP de forma eficiente.

### 🔹 Firebase (Core y Servicios)
- **Firebase (11.9.0)** → Plataforma de desarrollo para aplicaciones móviles.
- **AppCheck (11.2.0)** → Servicio de protección contra abusos en Firebase.
- **GoogleAppMeasurement (11.9.0)** → Biblioteca de medición de datos para Firebase Analytics.
- **GoogleDataTransport (10.1.0)** → Infraestructura de transporte de datos para Google Firebase.

### 🔹 gRPC y Base de Datos
- **gRPC (1.69.0)** → Implementación de gRPC en Swift para comunicación remota.
- **leveldb (1.22.5)** → Base de datos ligera utilizada por Firebase Firestore.
- **nanopb (2.30901.0)** → Implementación compacta de Protocol Buffers para dispositivos embebidos.
- **Promises (2.4.0)** → Biblioteca de promesas para Swift, utilizada en Firebase y Google SDKs.
- **protobuf (3.29.3)** → Serialización de datos basada en Google Protocol Buffers.
- **SwiftProtobuf (1.29.0)** → Implementación de Protocol Buffers en Swift.

## 🔧 Instalación
Este proyecto utiliza **Swift Package Manager (SPM)** para la gestión de dependencias. Para instalar las librerías, sigue estos pasos:

1. **Abrir el proyecto en Xcode**.
2. Ir a **File > Add Packages**.
3. Agregar las siguientes dependencias mediante sus URLs:

   - `https://github.com/Alamofire/Alamofire.git`
   - `https://github.com/openid/AppAuth-iOS.git`
   - `https://github.com/firebase/firebase-ios-sdk.git`
   - `https://github.com/grpc/grpc-swift.git`
   - `https://github.com/protocolbuffers/protobuf.git`
   - `https://github.com/google/leveldb.git`
   - `https://github.com/apple/swift-protobuf.git`
   - `https://github.com/google/promises.git`


