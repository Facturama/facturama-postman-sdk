# 🚀 Facturama Postman Collection

Colección de Postman basada en la API de Facturama que permite probar, entender e integrar fácilmente los endpoints de facturación electrónica.

Este proyecto está diseñado como una herramienta práctica para desarrolladores que necesitan interactuar con la API sin necesidad de implementar un SDK desde cero.

---

## ⚡ Quick Start

Sigue estos pasos para comenzar rápidamente:

1. Descarga o clona este repositorio
2. Importa el archivo:
3. Abre Postman y configura tus variables de entorno
4. Ejecuta las requests desde la colección

✅ En pocos minutos podrás realizar operaciones reales contra la API

---

## 📦 Contenido de la colección

La colección incluye ejemplos funcionales de:

- 👤 Gestión de clientes
- 📦 Productos / conceptos
- 🧾 Creación de facturas
- 📄 Consulta de facturas
- ❌ Cancelación de facturas
- 🔄 Flujos completos de uso

---

## 🧩 Estructura

La colección está organizada por módulos funcionales:

- `Clientes`: Crear, consultar, actualizar y eliminar clientes  
- `Productos`: Administración de productos  
- `Facturación`: Creación, consulta y cancelación de facturas  
- `Complementos`: Cfdis de tipo complemento y otros recursos relacionados  

---

## 🔐 Configuración

## 🌍 Environments

La colección soporta múltiples entornos:

- `Facturama API Test`
- `Facturama API Prod`

Selecciona el entorno adecuado antes de ejecutar las requests.

Cada entorno contiene su propia configuración de:
- SERVER
- UserName
- Password

---

## 🧪 Ejemplo de uso

### Crear una factura

1. Ejecuta la request de creación de factura 
2. Consulta el estado de la factura creada
3. Usa el ID generado en la siguiente request  
4. Con el mismo ID, prueba la cancelación (si es necesario)


---

## 🔄 Flujo recomendado

Para una mejor experiencia, se recomienda seguir este orden:

1. Crear factura
2. Consultar factura
3. Descargar factura (PDF/XML) 
4. Enviar factura por email (opcional)
5. Cancelar factura (opcional)  

---

## 🧠 Notas importantes

- La colección puede requerir datos válidos del SAT dependiendo del entorno  
- Algunas operaciones dependen de datos previamente creados  
- Asegúrate de usar credenciales válidas  
- Puedes duplicar requests para pruebas personalizadas  

---


## 🛠️ Requisitos

- Postman  
- Cuenta activa en Facturama  

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas.

Puedes abrir un issue o enviar un pull request para mejorar la colección.

---

## 📄 Licencia

MIT License

---

## ⭐ Soporte

Si este proyecto te es útil, considera darle una estrella ⭐ al repositorio.