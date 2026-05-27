# ADTask — Gestor Inteligente de Procesos para Windows

> Mata lo que sobra. Deja lo que importa.

---

## ¿Qué es esto?

**ADTask** es una herramienta ejecutable para Windows (.exe) diseñada para liberar CPU y memoria RAM de forma rápida y segura. Está pensada para usuarios que quieren control total sobre los procesos del sistema, ya sea de forma manual e informada, o delegando la decisión a un motor de limpieza inteligente.

Sin instalación. Sin dependencias. Doble clic y listo.

---

## Características principales

### Modo 1 — Borrado Manual con Explicación
- Lista todos los procesos activos del sistema en tiempo real.
- Muestra para cada proceso:
  - Nombre del ejecutable
  - Descripción legible (qué es y para qué sirve)
  - Uso actual de CPU y RAM
  - Estado: activo / suspendido / segundo plano
- El usuario decide qué procesos matar de forma individual e informada.
- Ideal para usuarios que quieren saber exactamente qué están eliminando.

---

### Modo 2 — Limpieza Inteligente (Smart Kill)
- Analiza automáticamente todos los procesos en ejecución.
- Clasifica y termina procesos según criterios de seguridad y eficiencia:
  - Procesos maliciosos o sospechosos detectados por patrones conocidos.
  - Procesos inactivos que consumen recursos sin estar en uso activo.
  - Procesos no críticos como navegadores, aplicaciones secundarias y servicios opcionales.
- Nunca toca procesos esenciales del sistema operativo:
  - `explorer.exe`, `svchost.exe`, `lsass.exe`, `winlogon.exe`, y similares.
- Resultado: reducción significativa de uso de CPU y RAM en segundos.

---

## Seguridad

- El programa no modifica archivos del sistema, solo gestiona procesos en ejecución.
- La lista de procesos protegidos está integrada directamente en el ejecutable.
- El Modo Inteligente aplica una lógica de lista blanca: todo lo crítico está excluido por defecto.
- Se recomienda ejecutar como **Administrador** para acceso completo a todos los procesos.

---

## Requisitos

| Componente | Requisito mínimo |
|---|---|
| Sistema Operativo | Windows 10 / 11 |
| Permisos | Administrador (recomendado) |
| Instalación | Ninguna |
| Dependencias | Ninguna |

---

## Uso

1. Descarga el archivo `.exe` desde la sección [Releases](../../releases).
2. Haz clic derecho y selecciona **Ejecutar como administrador**.
3. Elige tu modo:
   - `[1]` Borrado manual con explicación
   - `[2]` Limpieza inteligente automática
4. Sigue las instrucciones en pantalla.

---

## Autor

**Nox** · [@nostraxiten](https://github.com/nostraxiten)


