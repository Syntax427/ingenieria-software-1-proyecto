# 🚀 Proyecto de Ingeniería Software ♻️
Proyecto semestral del ramo Ingeniería de Software I 2025-2 en la Universidad de Concepción.

## 📑 Índice  
- [Índice](#-índice)  
- [Requerimientos](#-requerimientos)  
  - [Visión del problema](#visión-del-problema)  
  - [Visión del producto](#visión-del-producto)  
  - [Requisitos de software](#requisitos-de-software)  
  - [Actores involucrados](#actores-involucrados)  
- [Equipo de trabajo](#-equipo-de-trabajo)

## ✅ Requerimientos
En esta etapa definimos los requisistos y requerimientos de nuestros software.
### Visión del problema

En la actualidad la recolección de materiales reciclables en distintas comunas del país se hace de manera ineficiente debido a la falta de digitalización y organización entre usuario y recolector, causando mayores gastos, confusiones, rutas ineficientes, mal uso del tiempo y solicitudes pérdidas.

### Visión del producto

Se busca crear un software donde los usuarios puedan realizar solicitudes de retiro de sus materiales, validándose automáticamente según su ubicación geográfica y agrupándolos por zonas para formar rutas de recolección eficientes para los trabajadores. Asimismo los recolectores podrán notificar el resultado de cada retiro y emitir comprobantes para los hogares.

### Requisitos de software

Para los **requisitos funcionales**, el sistema debe permitir:
- Ingresar solicitudes de retiro de materiales, así como editarlas o cancelarlas.
- Validar las solicitudes de retiro a través de la ubicación geográfica.
- Integrar rutas eficientes en base a agrupación de las solicitudes por zona. 
- Reportar el resultado de cada retiro por parte de los recolectores.
- Que el recolector genere comprobantes para los hogares.
- Registro de los actores a través de correo y contraseña.
- Almacenamiento de los datos personales del usuario (contemplando dirección, nombre completo, correo y número telefónico)
- Diferenciar el actor según su cuenta para mostrar una interfaz personalizada.
- Ofrecer una visualización de un tutorial de uso de la aplicación personalizado para cada actor.

Y para los **requisitos no funcionales**: 
- Seguridad: Uso de protocolo SSL/TLS para el manejo de los datos, junto con jerarquías de acceso separadas para usuarios y trabajadores.
- Usabilidad: Diversidad de idiomas para la interfaz (contempla inglés y español). Todas las acciones principales se pueden realizar en menos de 5 pasos. 
- Fiabilidad: El sistema posee una capacidad de restaurar al menos el 90% de los datos en operaciones ante interrupciones en los procesos. En caso de fallo en la base de datos de solicitudes, aún se podrá recibir solicitudes en caché temporal - para luego ser sincronizadas. 
- Eficiencia: Capacidad de respuesta menor a 1 segundo. El sistema debe procesar hasta 500 solicitudes de recolección por minuto sin que afecte el desempeño de la aplicación.

### Actores involucrados:
- Usuarios: Personas que solicitarán la recolección de los materiales de reciclaje.
- Recolectores: Personas encargadas de recolectar los materiales de reciclaje.
- Coordinadores: Personas que administran y supervisan el proceso de recolección.

## 🤝 Equipo de trabajo
Somos el **equipo 1**:
- Pablo Ignacio Bettancourt Pinto
- Bastián Guido Ceballos Zapata 
- Angie Verónica Ramírez González
- Walter Andrés Zárate Solar

![fondo-dino](https://github.com/Angie161/Tarea_1/assets/146099765/e2be2eb8-e713-4d04-97fb-bb1f2bc89fa8)
