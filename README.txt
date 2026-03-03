# DOCUMENTACION - inventapp

## Instalar el Sistema
Para instalar el sistema, simplemente copie la carpeta `inventapp` completa a cualquier ubicación de su computadora (Disco C:, Escritorio, Pendrive, etc). El sistema es portátil y no requiere instalación formal.

## Cómo Iniciar
1. Entre a la carpeta `inventapp`.
2. Busque el archivo `inventapp.exe` (tiene el icono de la bolsa de compras).
3. Haga doble clic para abrir. El sistema se abrirá automáticamente en su navegador.

## Licencia y Activación
Este sistema requiere una activación mensual para funcionar en modo completo.
1. Al abrir el programa, si no tiene licencia activa, verá un botón que dice "Activar Licencia".
2. Haga clic y copie su "Clave de Máquina".
3. Envíe esa clave al proveedor para recibir su clave de activación del mes.

## Carpetas de Soporte
Es importante que NO borre ni mueva estas carpetas si desea que el sistema funcione correctamente:
- `static/`: Contiene imágenes de productos y reportes.
- `templates/`: Estructura del sistema.
- `HERRAMIENTA_DESARROLLADOR/`: Solo para uso del administrador del sistema.

## Migración de Datos
Si está actualizando desde una versión anterior, ejecute el archivo `migrar_db.py` antes de abrir el `inventapp.exe` para asegurar que su base de datos esté actualizada.
