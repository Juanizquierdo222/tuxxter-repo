
**Izquierdo Fiscal Juan Alberto**  
*Ingeniería en Sistemas Computacionales*  
*Redes de Computadoras*  

---

**Universidad:INSTITUTO TECNOLOGICO DE CANCUN**   
**Fecha: 14/07/2025**  

---






# Medios de Transmisión en Cableado Estructurado

## 1. Cable Coaxial

### Características técnicas
- **Ventajas**:
  - Mayor distancia de transmisión que par trenzado
  - Alta resistencia a interferencias
  - Ancho de banda amplio con baja atenuación
  - Ampliamente usado en TV por cable y redes antiguas

- **Limitaciones**:
  - Atenúa señales de alta frecuencia
  - Requiere amplificadores para largas distancias
  - Costo elevado de instalación (conectores especiales)
  - Velocidades limitadas comparado con estándares modernos

### Tipos principales:
- **RG-58**: 50Ω, conector BNC (Ethernet delgado)
- **RG-59**: 75Ω, conectores DNC/TNC (WANGNET)
- **RG-62**: 93Ω (ARCnet/IBM 3270)

## 2. Par Trenzado

### Comparativa entre tipos:

| Característica | UTP         | FTP         | STP         |
|---------------|-------------|-------------|-------------|
| Blindaje      | Ninguno     | Global      | Por par     |
| Frecuencia Máx | 100 MHz    | 600 MHz     | 1 GHz       |
| Coste         | Bajo        | Medio       | Alto        |
| Uso típico    | Oficinas    | Industria   | Datacenters |

### Categorías de cable UTP:

1. **Cat 1**: Telefonía básica
2. **Cat 3**: 16 MHz (10Base-T)
3. **Cat 5**: 100 MHz (100Base-TX)
4. **Cat 6**: 250 MHz (1000Base-T)
5. **Cat 6A**: 500 MHz (10GBase-T)

## 3. Fibra Óptica

### Tipos y características:

- **Multimodo (MMF)**:
  - Diámetro núcleo: 50/62.5μm
  - Distancias cortas (hasta 550m)
  - Tipos: OM1 (100MHz), OM4 (4700MHz)

- **Monomodo (SMF)**:
  - Diámetro núcleo: 9μm
  - Largas distancias (hasta 40km)
  - Ancho de banda: 50GHz

### Ventajas:
- Total inmunidad a EMI
- Mayor ancho de banda
- Distancias extendidas
- Seguridad en transmisión

## 4. Normativas clave

- **TIA/EIA-568-D**: Estándar principal para América
- **ISO/IEC 11801**: Estándar internacional
- **ANSI/EIA/TIA 568-A**: Especificaciones para fibra óptica

## 5. Consideraciones de instalación

- **Distancias máximas**:
  - UTP: 100m (90m cable + 10m patch cords)
  - Fibra multimodo: 550m (10Gbps)
  
- **Recomendaciones**:
  - Evitar interferencias electromagnéticas
  - Mantener curvaturas adecuadas
  - Usar herramientas de certificación
  - Seguir normativas de seguridad

## 6. Tendencias actuales

- Migración a Cat 6A/8 para 10Gbps
- Adopción creciente de fibra óptica
- Convergencia voz/datos/video
- Mayor demanda de ancho de banda

# Cableado Estructurado: Medios de Transmisión

## 1. Cable Coaxial

### Características principales
- **Ventajas**:
  - Mayor distancia de transmisión que par trenzado
  - Alta resistencia a interferencias
  - Gran ancho de banda con baja atenuación
  - Amplio uso en TV por cable y redes antiguas

- **Limitaciones**:
  - Atenúa señales de alta frecuencia (pérdida proporcional a √f)
  - Requiere amplificadores para largas distancias
  - Mayor costo de instalación (conectores especiales)
  - Velocidades limitadas comparado con estándares modernos

### Estructura física
1. Conductor central de cobre
2. Aislante dieléctrico (polietileno)
3. Malla conductora
4. Cubierta externa de PVC

### Tipos principales:
- **10Base5 (Ethernet grueso)**: 50Ω, conector tipo N
- **RG-58**: 50Ω, conector BNC (Ethernet delgado)
- **RG-59**: 75Ω, conectores DNC/TNC (WANGNET)
- **RG-62**: 93Ω, conector BNC (ARCnet/IBM 3270)

## 2. Cable de Par Trenzado

### Tipos principales:

#### UTP (Unshielded Twisted Pair)
- Más económico y fácil de instalar
- 4 pares trenzados (8 hilos)
- Categorías:
  - Cat 1: Telefonía (1 MHz)
  - Cat 3: 16 MHz (10Base-T)
  - Cat 5: 100 MHz (100Base-TX)
  - Cat 6: 250 MHz (1000Base-T)

#### STP (Shielded Twisted Pair)
- Blindaje individual por par
- Mayor protección contra EMI
- Soporta hasta 400 MHz
- Costo más elevado

#### FTP (Foiled Twisted Pair)
- Blindaje global de aluminio
- Compromiso entre UTP y STP
- Recomendado para entornos industriales

### Normativas:
- **EIA/TIA-568**: Estándar de cableado estructurado
- **TSB-36**: Especificaciones técnicas para UTP
- **TSB-67**: Parámetros de rendimiento

## 3. Fibra Óptica

### Tipos:
1. **Multimodo salto de índice**: 100 MHz
2. **Multimodo índice gradual**: 1 GHz
3. **Monomodo**: 50 GHz

### Ventajas:
- Inmunidad total a EMI
- Mayor ancho de banda
- Distancias extendidas
- Mayor seguridad

### Desventajas:
- Costo elevado
- Conectores complejos
- Requiere equipos especializados

### Conectores comunes:
- LC, SC, ST, MTP

## 4. Comparativa general

| Característica | Coaxial | UTP | Fibra Óptica |
|---------------|---------|-----|-------------|
| Distancia máxima | 500m | 100m | 40km |
| Ancho de banda | 1 GHz | 250 MHz | 50 GHz |
| Inmunidad EMI | Alta | Baja | Total |
| Coste instalación | Medio | Bajo | Alto |

## 5. Implementación en edificios

### Elementos clave:
- Cableado horizontal
- Backbone principal
- Cuarto de telecomunicaciones
- Sistema de puesta a tierra

### Normativas aplicables:
- ANSI/EIA/TIA 568-A
- ISO/IEC 11801
- NEC NFPA 70 (Artículo 800)

# Consideraciones Adicionales sobre Medios de Transmisión

## 1. Tendencias Actuales en Cableado Estructurado

### Evolución tecnológica:
- **Migración a categorías superiores**: 
  - Cat 6A (500 MHz) para 10GBase-T
  - Cat 8 (2000 MHz) para centros de datos
- **Fibra óptica omnipresente**:
  - Mayor adopción de OM5 (WBMMF)
  - Uso creciente de conectores LC duplex
- **Convergencia tecnológica**:
  - Unificación de redes de voz/datos/video
  - Mayor demanda de PoE (802.3bt)

## 2. Recomendaciones de Instalación

### Buenas prácticas:
- **Para UTP**:
  - Mantener curvatura >4x diámetro cable
  - Evitar fuentes de interferencia electromagnética
  - Usar canaletas separadas de cableado eléctrico

- **Para fibra óptica**:
  - Limpieza exhaustiva de conectores
  - Uso de kits de prueba OLTS/OTDR
  - Protección de empalmes contra tensiones mecánicas

- **Para coaxial**:
  - Correcta terminación de conectores
  - Uso de herramientas de crimpado certificadas
  - Verificación de impedancia constante

## 3. Parámetros Críticos de Rendimiento

| Parámetro       | Coaxial | UTP Cat 6 | Fibra OM4 |
|-----------------|---------|-----------|-----------|
| Atenuación      | 20 dB/100m @ 1GHz | 19.8 dB/100m @ 250MHz | 3.5 dB/km @ 850nm |
| NEXT            | N/A     | 44.3 dB   | N/A       |
| ACR             | N/A     | 24.5 dB   | N/A       |
| Retardo         | 5 ns/m  | 5.7 ns/m  | 3.84 μs/km|

## 4. Consideraciones de Seguridad

### Aspectos clave:
- **Protección física**:
  - Canalizaciones ignífugas para áreas plenum
  - Sistemas de etiquetado y documentación
- **Seguridad lógica**:
  - Ventajas de fibra en prevención de eavesdropping
  - Uso de cableado blindado en áreas sensibles
- **Certificaciones**:
  - Pruebas de certificación según ANSI/TIA-1152
  - Documentación de resultados (IL/RL para fibra)

## 5. Futuro del Cableado Estructurado

### Tecnologías emergentes:
- **Fibra de cristal fotónico**:
  - Pérdidas <0.1 dB/km
  - Mayor tolerancia a curvaturas
- **Cobre de alta velocidad**:
  - Cableado Cat 8.1/8.2 para 40GBase-T
  - Mejoras en materiales dieléctricos
- **Automatización**:
  - Sistemas de gestión inteligente de cableado
  - Soluciones IoT para monitoreo de infraestructura

## 6. Glosario Técnico

- **ACR** (Attenuation to Crosstalk Ratio): Diferencia entre atenuación y diafonía
- **NEXT** (Near-End Crosstalk): Interferencia entre pares adyacentes
- **OLTS** (Optical Loss Test Set): Equipo para medición de pérdida óptica
- **PoE** (Power over Ethernet): Alimentación eléctrica a través de cableado de datos
