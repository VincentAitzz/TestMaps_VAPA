# Vulnerabilidades Identificadas

## Resumen
El análisis de la aplicación **TestMaps** (com.vincentaitzz.testmaps) ha revelado varias vulnerabilidades críticas que deben ser abordadas.

## Vulnerabilidades Encontradas

1. **Aplicación firmada con un certificado de depuración**
   - **Severidad:** Alta
   - **Descripción:** La aplicación está firmada con un certificado de depuración, lo cual es inaceptable para aplicaciones en producción.

2. **Instalación en versiones vulnerables de Android**
   - **Severidad:** Alta
   - **Descripción:** La aplicación puede instalarse en versiones antiguas de Android (menor a API 29) que no reciben actualizaciones de seguridad.

3. **Depuración habilitada**
   - **Severidad:** Alta
   - **Descripción:** La opción de depuración está habilitada, lo que facilita la ingeniería inversa y el acceso no autorizado a la aplicación.

4. **Datos de la aplicación pueden ser respaldados**
   - **Severidad:** Advertencia
   - **Descripción:** La opción `android:allowBackup=true` permite que los datos sean respaldados, lo que puede ser un riesgo si se accede a dispositivos no seguros.

5. **Permisos peligrosos solicitados**
   - **Descripción:**
     - `ACCESS_FINE_LOCATION`: Permite el acceso a la ubicación precisa del usuario.
     - `ACCESS_COARSE_LOCATION`: Permite el acceso a la ubicación aproximada del usuario.
