# Arquitectura Empresarial - Control de Versiones

## Tipo de Servicio Web
Este proyecto implementa una API de tipo **REST**.

### Justificación:
- REST utiliza HTTP estándar, lo que mejora la **interoperabilidad**.
- Es más ligero que SOAP, mejorando el **rendimiento**.
- Usa JSON como formato de datos, más fácil de consumir.

# Servicio Web REST

## Endpoints definidos
- GET  /usuarios       → Lista todos los usuarios
- POST /usuarios       → Crea un nuevo usuario
- GET  /usuarios/{id}  → Obtiene un usuario por ID