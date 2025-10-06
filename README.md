# adatos_ta

#### Crear carpeta "data" en la raiz del proyecto

### Estructura General

- **Datos Crudos**: Archivos originales proporcionados por fuentes externas, generalmente en formato Excel (.xlsx).
- **Datos Procesados**: Archivos resultantes de los pasos de limpieza y transformación de datos, en formato CSV (.csv).
- **Diccionarios de Datos**: Documentos que describen las variables y estructuras de los datos, también en formato Exc
el.

### Archivos Esperados

1. **Diccionario de Datos**:
   - `Diccionario de Datos - Vehiculos_afectos_a_IPV_Ene-Marzo_2025 ITRIM25 [SAT].xlsx`: Contiene la definición de las columnas y variables del dataset principal.

2. **Datos Crudos**:
   - `Vehiculos_afectos_a_IPV_Ene-Mar_2025_3.xlsx`: Archivo principal con los datos de vehículos afectados por IPV para enero a marzo de 2025.

3. **Datos Procesados**:
   - `data_post_step3.csv`: Datos después del paso 3 de procesamiento (ej. limpieza inicial).
   - `datos_post_step4a.csv`: Datos después del subpaso 4a (ej. transformación específica).
   - `datos_post_Step4b.csv`: Datos después del subpaso 4b (ej. agregaciones o filtros adicionales).

