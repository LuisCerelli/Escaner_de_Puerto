# IP Port Scanner

Este es un simple escáner de puertos que utiliza el módulo `socket` de Python para identificar puertos abiertos en una dirección IP específica. El script intenta conectarse a todos los puertos dentro del rango (1-65535) y reporta cuáles están abiertos y cuáles están cerrados.

## ¿Cómo funciona?

El script solicita al usuario que ingrese una dirección IP a escanear y luego intenta conectarse a todos los puertos posibles en esa dirección. Si el puerto está abierto, lo reporta como tal. Si está cerrado, lo indica también.

### Funcionamiento básico:

- El script solicita la **dirección IP** a escanear.
- Recorre los puertos del **1 al 65535**.
- Intenta establecer una conexión con cada puerto.
- Si el puerto está abierto (retorna 0), lo muestra como "Puerto Abierto".
- Si el puerto está cerrado (retorna cualquier otro valor), muestra "Puerto Cerrado".

# Beneficios del Escaneo de Puertos
El escaneo de puertos es una técnica útil para evaluar la seguridad de una red o un servidor. Algunas aplicaciones incluyen:

Auditoría de seguridad: Ayuda a identificar qué puertos están abiertos y pueden representar vulnerabilidades.
Monitoreo de servicios: Los administradores de sistemas pueden verificar que solo los servicios necesarios están accesibles a través de los puertos abiertos.
Evaluación de configuración: Para asegurarse de que los puertos no utilizados estén correctamente cerrados, reduciendo el riesgo de ataques externos.
Diagnóstico de conectividad: Permite verificar si ciertos puertos en un servidor están accesibles o si hay problemas de conectividad.

# Advertencia
Este script está destinado únicamente para fines educativos o para auditar la seguridad de redes propias. No debe usarse para escanear redes o sistemas sin el consentimiento del propietario, ya que puede violar las leyes locales o internacionales.

## Contribuciones
Si deseas mejorar este proyecto o agregar más funcionalidades, siéntete libre de hacer un fork y abrir un pull request con tus cambios.
