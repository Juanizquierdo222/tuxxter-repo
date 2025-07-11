# **Investigación del IEEE 802**  

---

**Izquierdo Fiscal Juan Alberto**  
*Ingeniería en Sistemas Computacionales*  
*Redes de Computadoras*  

---

**Universidad:INSTITUTO TECNOLOGICO DE CANCUN**   
**Fecha: 14/07/2025**  

---




# IEEE 802: Historia, Características, Arquitectura y Estándares

##  **Historia del IEEE 802**
- **Fundación**:  
  - Creado en **1980** por el IEEE para estandarizar redes locales (LAN).  
  - Nombre "802" proviene del año (febrero de 1980, mes 2).  
- **Primer estándar**:  
  - **IEEE 802.3 (Ethernet)** publicado en **1983** (10BASE5).  
- **Evolución**:  
  - 1990s: Expansión a redes inalámbricas (Wi-Fi, Bluetooth).  
  - 2000s: Alta velocidad (Gigabit Ethernet, Wi-Fi 4/5/6).  
  - 2020s: Enfoque en IoT, 5G, y baja latencia (TSN, Wi-Fi 7).  



##  **Características Principales**
- **Ámbito**:  
  - Estándares para **capas física y de enlace de datos** (OSI Layers 1 & 2).  
- **Enfoque**:  
  - **Interoperabilidad** entre dispositivos de diferentes fabricantes.  
  - **Escalabilidad** (desde redes domésticas hasta industriales).  
- **Método de acceso**:  
  - **CSMA/CD** (Ethernet cableado).  
  - **CSMA/CA** (Wi-Fi).  



##  **Arquitectura IEEE 802**
Se divide en **dos subcapas**:
1. **LLC (Logical Link Control, 802.2)**:  
   - Gestiona el flujo de datos y el control de errores.  
2. **MAC (Media Access Control)**:  
   - Específica para cada tecnología (ej: 802.3, 802.11).  



---

##  **Estándares IEEE 802 para Redes Alámbricas**
| Estándar | Nombre          | Aplicación                          | Velocidad             |
|----------|-----------------|-------------------------------------|-----------------------|
| 802.3    | Ethernet        | Redes cableadas (UTP/fibra)         | 10 Mbps – 1.6 Tbps   |
| 802.3ah | Ethernet First Mile | Acceso de banda ancha (fibra)    | 1 Gbps               |
| 802.1Q   | VLAN Tagging    | Segmentación de redes               | N/A                  |
| 802.1X   | Port-Based Auth | Autenticación en redes              | N/A                  |

###  **Tecnologías Clave**:
- **Power over Ethernet (PoE)**:  
  - Estándares **802.3af/at/bt** (hasta 90W).  
- **TSN (Time-Sensitive Networking)**:  
  - Para aplicaciones industriales de baja latencia.  

---

##  **Estándares IEEE 802 para Redes Inalámbricas**
| Estándar  | Nombre          | Frecuencia           | Velocidad Máxima      |
|-----------|-----------------|-----------------------|-----------------------|
| 802.11a   | Wi-Fi (5 GHz)   | 5 GHz                | 54 Mbps              |
| 802.11b   | Wi-Fi (2.4 GHz) | 2.4 GHz              | 11 Mbps              |
| 802.11g   | Wi-Fi (2.4 GHz) | 2.4 GHz              | 54 Mbps              |
| 802.11n   | Wi-Fi 4         | 2.4/5 GHz            | 600 Mbps             |
| 802.11ac  | Wi-Fi 5         | 5 GHz                | 6.9 Gbps             |
| 802.11ax  | Wi-Fi 6/6E      | 2.4/5/6 GHz          | 9.6 Gbps             |
| 802.11be  | Wi-Fi 7 (2024)  | 2.4/5/6 GHz          | 40 Gbps              |
| 802.15.1  | Bluetooth       | 2.4 GHz              | 3 Mbps (BLE)         |
| 802.15.4  | Zigbee          | 2.4 GHz/Sub-GHz      | 250 kbps             |

###  **Tendencias en Inalámbricas**:
- **Wi-Fi 7 (802.11be)**:  
  - Canales de **320 MHz**, **MLO** (Multi-Link Operation).  
- **Redes IoT**:  
  - **802.15.4** (Zigbee, Thread) para dispositivos de baja potencia.  



## **Comparativa: Alámbricas vs. Inalámbricas**
| Característica       | Alámbricas (802.3)       | Inalámbricas (802.11)  |
|----------------------|--------------------------|------------------------|
| **Velocidad**        | 1.6 Tbps (800G Ethernet) | 40 Gbps (Wi-Fi 7)      |
| **Latencia**         | <1 ms (TSN)              | 1–10 ms                |
| **Seguridad**        | MACsec (802.1AE)         | WPA3                   |
| **Uso típico**       | Data centers, industria  | Hogares, móviles       |


##  **Futuro del IEEE 802**
1. **Convergencia 5G/Wi-Fi**:  
   - Integración con redes celulares.  
2. **Redes Cuánticas**:  
   - Protocolos para comunicación cuántica.  
3. **Realidad Extendida (XR)**:  
   - Baja latencia para VR/AR.  

 # IEEE 802.11 (Wi-Fi): Estándares, Evolución y Tecnología

##  **Introducción al Wi-Fi (IEEE 802.11)**
- **Definición**: Tecnología de red inalámbrica para acceso a Internet y comunicación local.
- **Organismo regulador**: Wi-Fi Alliance (certifica compatibilidad).
- **Bases técnicas**: 
  - Opera en bandas ISM (2.4 GHz, 5 GHz y 6 GHz).
  - Usa CSMA/CA para evitar colisiones.



##  **Evolución Histórica de los Estándares 802.11**

| Estándar | Año   | Nombre Comercial | Banda    | Velocidad Máx. | Características Clave |
|----------|-------|------------------|----------|----------------|-----------------------|
| 802.11   | 1997  | Wi-Fi Legacy     | 2.4 GHz  | 2 Mbps         | Primer estándar       |
| 802.11b  | 1999  | Wi-Fi 1          | 2.4 GHz  | 11 Mbps        | Popular en los 2000s  |
| 802.11a  | 1999  | Wi-Fi 2          | 5 GHz    | 54 Mbps        | Menor interferencia   |
| 802.11g  | 2003  | Wi-Fi 3          | 2.4 GHz  | 54 Mbps        | Compatibilidad con "b"|
| 802.11n  | 2009  | Wi-Fi 4          | 2.4/5 GHz| 600 Mbps       | MIMO, 40 MHz channels |
| 802.11ac | 2013  | Wi-Fi 5          | 5 GHz    | 6.9 Gbps       | MU-MIMO, 160 MHz      |
| 802.11ax | 2019  | Wi-Fi 6/6E       | 2.4/5/6 GHz | 9.6 Gbps   | OFDMA, BSS Coloring   |
| 802.11be | 2024  | Wi-Fi 7          | 2.4/5/6 GHz | 40 Gbps    | 320 MHz, Multi-Link   |



##  **Características Técnicas Avanzadas**

### 1. **Modulación y Canales**
- **OFDM/OFDMA**: Usado desde Wi-Fi 4 (802.11n) para eficiencia espectral.
- **Ancho de canal**:
  - 20 MHz (802.11a/g)
  - Hasta 320 MHz (Wi-Fi 7).

### 2. **MIMO y MU-MIMO**
- **MIMO (Multiple Input Multiple Output)**: Múltiples antenas (desde Wi-Fi 4).
- **MU-MIMO**: Multi-Usuario (Wi-Fi 5 en downlink, Wi-Fi 6 en uplink).

### 3. **Seguridad**
- **WPA3** (2018): Reemplaza a WPA2, con:
  - SAE (Secure Authentication).
  - Cifrado de 192 bits (Enterprise).



##  **Bandas de Frecuencia y Su Impacto**

| Banda    | Ventajas                     | Desventajas               | Estándares que la usan |
|----------|------------------------------|---------------------------|------------------------|
| **2.4 GHz** | Mayor alcance               | Mucha congestión          | 802.11b/g/n/ax/be     |
| **5 GHz**   | Más canales, menos ruido    | Menor penetración         | 802.11a/n/ac/ax/be    |
| **6 GHz**   | Espacio amplio (Wi-Fi 6E)   | Regulación limitada       | 802.11ax/be           |



##  **Wi-Fi 7 (IEEE 802.11be) - Últimos Avances**
1. **Multi-Link Operation (MLO)**: 
   - Agrega múltiples enlaces simultáneos (ej: 5 GHz + 6 GHz).
2. **320 MHz Channels**: 
   - Doble ancho que Wi-Fi 6 (requiere 6 GHz).
3. **4096-QAM**: 
   - Mayor densidad de datos (20% más velocidad).
4. **Latencia Ultra-Baja**: 
   - <1 ms para realidad virtual/industrial.



##  **Aplicaciones Prácticas**
- **Hogares**: Streaming 8K, gaming en la nube.
- **Empresas**: Oficinas sin cables, VoIP.
- **Industria 4.0**: Wi-Fi 6/7 con TSN para robótica.
- **IoT**: 802.11ah (Wi-Fi HaLow) para dispositivos de baja potencia.



##  **Futuro del Wi-Fi**
- **Wi-Fi 8 (802.11bn)**: En investigación (2030):
  - Integración con redes celulares (6G).
  - IA para gestión dinámica de redes.
- **AR/VR**: Bajísima latencia (<0.5 ms).


##  **Comparativa Wi-Fi 6 vs. Wi-Fi 7**
| Característica       | Wi-Fi 6 (802.11ax)     | Wi-Fi 7 (802.11be)     |
|----------------------|------------------------|------------------------|
| **Velocidad Máx.**   | 9.6 Gbps               | 40 Gbps                |
| **Canales**          | Hasta 160 MHz          | Hasta 320 MHz          |
| **Modulación**       | 1024-QAM               | 4096-QAM               |
| **Multi-Link**       | No                     | Sí                     |

