# Karate PetStore Tests

Este proyecto utiliza Karate Framework para realizar pruebas automatizadas sobre la API
https://petstore.swagger.io/.

## 1. Prerequisitos
- Maquina local con el sistema operativo Windows 10 o superior
- Java JDK 17.0.12 (en el PATH)
- Apache Maven 3.9.1 (en el PATH)

## 2. Comandos de instalacion
Desde la carpeta del proyecto `karate-petstore`:
- `mvn clean install` (descarga dependencias del POM)

## 3. Instrucciones para ejecutar los test
1) Abrir una terminal en la carpeta `karate-petstore`.
2) Ejecutar: `mvn test`.
3) Revisar reportes en `karate-petstore/target/karate-reports`.

## 4. Informacion adicional
- Feature principal: `src/test/resources/TestPet.feature`.
- Datos de entrada: `src/test/resources/data.json`.
- Escenarios cubiertos: crear mascota, buscar por ID, actualizar nombre y estatus a "sold", y buscar por estatus.