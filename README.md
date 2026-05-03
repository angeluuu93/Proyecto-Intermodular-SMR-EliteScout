# Proyecto-Intermodular-SMR-EliteScout
Infraestructura técnica y documentación para el proyecto intermodular de 1º SMR".
# ⚽ Infraestructura Tecnológica EliteScout S.L. 

Este repositorio contiene el proyecto integral de diseño, montaje y configuración de la infraestructura informática para la agencia de scouting profesional **EliteScout S.L.**[cite: 7].

## 📋 Resumen del Proyecto
EliteScout S.L. es una empresa dedicada al análisis masivo de vídeo deportivo en resolución 4K[cite: 7]. Como técnicos de SMR, hemos desarrollado una solución que garantiza el alto rendimiento necesario para el renderizado de vídeo, la seguridad de los datos mediante sistemas RAID y una conectividad de red de baja latencia[cite: 3, 6].

*   **Inversión total:** 9.890 €.
*   **Sede:** Oficina técnica con 5 puestos de trabajo y almacenamiento centralizado[cite: 2, 6].

---

## 📂 Estructura de carpetas (Entregables)

El repositorio se divide en módulos siguiendo los requisitos de 1º de SMR:

### 1. [Montaje y Mantenimiento](./montaje/) 🔧
*   **Hardware:** Selección de componentes de alta gama (Intel i7-14700K, RTX 4070 SUPER) para estaciones de trabajo[cite: 6].
*   **Almacenamiento:** Configuración de Servidor NAS en **RAID 1** para redundancia de datos críticos[cite: 7].
*   **Documentación:** Guía de montaje paso a paso y plan de mantenimiento preventivo semestral.

### 2. [Redes Locales](./redes/) 🌐
*   **Topología:** Diseño en estrella con electrónica Cisco (Router 2911, Switch 2960)[cite: 3, 4].
*   **Direccionamiento:** Plan de IPs estáticas para garantizar la estabilidad de los servicios compartidos (NAS en .10)[cite: 5].
*   **Simulación:** Archivo operativo `cisco.pkt` con pruebas de conectividad (Ping) superadas con éxito[cite: 3, 4].

### 3. [Sistemas Operativos](./sistemas/) 💻
*   **Software:** Despliegue de Windows 11 Pro con optimizaciones para edición de vídeo.
*   **Seguridad:** Hardening del sistema, gestión de usuarios por niveles y reglas de Firewall personalizadas[cite: 1].

### 4. [Aplicaciones Ofimáticas y BBDD](./ofimatica/) 📊
*   **Gestión:** Inventario completo de activos y registro histórico de incidencias técnicas para soporte[cite: 1].
*   **Bases de Datos:** Diagrama Entidad-Relación (E/R) para la gestión de analistas, jugadores e informes.
*   **Cloud:** Propuesta de backup híbrido sincronizado para asegurar la disponibilidad fuera de la sede.

### 5. [Itinerario Profesional (IPE)](./empleabilidad/) 💼
*   **Perfil:** Análisis del sector de la IA aplicada al deporte (Olocip, Quantic Brains) y seguimiento de referentes en LinkedIn.
*   **Reflexión:** Análisis personal sobre las competencias adquiridas durante el desarrollo del proyecto[cite: 1].

---

## 👤 Autor
**Ángel Luis Martínez Calderón** - 1º Sistemas Microinformáticos y Redes (Escuela Online Prometeo).
