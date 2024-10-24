# TestMaps

## Descripción
Este proyecto es una aplicación Android que implementa medidas de seguridad para proteger contra vulnerabilidades comunes.

## Vulnerabilidades Identificadas
- Aplicación firmada con un certificado de depuración.
- Instalación en versiones vulnerables de Android.
- Depuración habilitada.
- Datos de la aplicación pueden ser respaldados.
- Permisos peligrosos solicitados (ACCESS_FINE_LOCATION, ACCESS_COARSE_LOCATION).

## Mejoras Implementadas
- Cifrado de datos sensibles.
- Comunicación segura (HTTPS).
- Validación y sanitización de entradas.

## Documentación
- [Vulnerabilidades](vulnerabilities.md)
- [Best Practices](best_practices.md)
- [Security Tips](security_tips.md)
- [Security Improvement Program](security_improvement_program.md)

## Cómo Ejecutar la Aplicación de Forma Segura
1. Clonar el repositorio.
2. Importar el proyecto en Android Studio.
3. Ejecutar la aplicación en un dispositivo o emulador.
4. Asegurarse de que los permisos necesarios están configurados.

## Reporte de Vulnerabilidades 
El reporte detallado se encuentra en el archivo `descarga.pdf`.
