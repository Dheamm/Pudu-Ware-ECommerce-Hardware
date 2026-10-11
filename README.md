# Pudú-Ware

E-commerce de venta de hardware. Proyecto Solemne 02.

## Equipo

- Benjamín Del Valle (Scrum Master)
- Damon Murray
- Benjamín Juanillo
- Matías Palma
- Benjamín Gonzales
- Ítalo Osorio

Las tareas de cada integrante están asignadas en [Jira](https://pudu-ware.atlassian.net/jira/software/projects/SCRUM/boards/1).

## Contexto y alcance

Tienda pública y panel de administración, con pagos en sandbox (sin cobros reales) en pesos chilenos.
No incluye despacho, facturación electrónica, cupones, valoraciones ni múltiples monedas.

## Arquitectura

TODO: diagrama en `docs/`.

| Servicio            | Responsabilidad                              | Datos      |
| ------------------- | -------------------------------------------- | ---------- |
| `servicio-gestion`  | Usuarios, roles, contenidos, temas, contacto | PostgreSQL |
| `servicio-catalogo` | Productos, existencias, reservas             | MongoDB    |
| `servicio-comercio` | Carrito, órdenes, pagos, notificaciones      | PostgreSQL |
| `frontend`          | React + Vite                                 | —          |

## Versiones

Python TODO · Django TODO · DRF TODO · PostgreSQL TODO · MongoDB TODO · Node TODO

## Instalación

Prerrequisitos y cuentas: TODO

```bash
git clone TODO
# comandos por servicio: TODO
```

Variables de entorno: copiar `.env.example` a `.env` en cada servicio (sin valores secretos).

## Datos iniciales y primer administrador

TODO

## Pruebas

TODO

## Estados, reservas e idempotencia

TODO

## Despliegue

URLs, plataformas, cuotas y persistencia: TODO

## Logs, reintentos, respaldos y recuperación

TODO

## Trazabilidad y contribuciones

TODO

## Limitaciones conocidas

TODO

## Procedencia y licencias de recursos

TODO
