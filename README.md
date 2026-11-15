# Pollos Fácil — publicar en GitHub Pages

Este paquete contiene el código de la aplicación. No contiene ventas, respaldos personales, contraseñas ni archivos de la cuenta de ChatGPT.

## Publicar desde tu computadora

1. Descomprime Pollos_Facil_GitHub.zip.
2. En GitHub, crea un repositorio llamado pollos-facil. Para GitHub Pages con GitHub Free, debe ser público.
3. En el repositorio, elige Add file → Upload files. Sube TODOS los archivos descomprimidos, no el ZIP ni una carpeta que los envuelva. index.html debe aparecer directamente en la raíz del repositorio. Guarda con Commit changes.
4. Abre Settings → Pages. En Build and deployment, selecciona Deploy from a branch, rama main, carpeta / (root), y Save.
5. Espera a que termine la publicación. En Settings → Pages, pulsa Visit site y copia ese enlace exacto.

## Instalar en el Samsung

1. Abre el enlace publicado en Chrome con internet.
2. Usa Instalar en celular o el menú de Chrome → Instalar y crear acceso directo → Instalar. El nombre de la opción puede variar.
3. Abre el icono y espera «Listo para usar sin señal».
4. Comprueba que se abre después de activar el modo avión. Vuelve a activar las conexiones al terminar la prueba.

El ZIP no es un APK. Abrir index.html directamente desde Descargas no sustituye la publicación HTTPS y la instalación desde Chrome.

## Usar la aplicación

- Inventario inicial: cantidad que existía antes del primer movimiento. Para empezar registrando una compra, coloca 0 y registra esa compra. No registres los mismos pollos dos veces.
- Venta 3 por S/ 100: Precio total, cantidad 3, importe 100.
- Venta 3 a S/ 35 cada uno: Precio por pollo, cantidad 3, importe 35. Total S/ 105.
- Compra: cantidad, total pagado por los pollos y gastos de transporte. Los gastos se suman al costo de compra.
- Baja: registra muertos u otras pérdidas.
- Historial: toca un movimiento para corregirlo o anularlo.
- Respaldo: descarga un JSON al terminar la jornada y guarda una copia fuera del celular.

## Datos y cambio de enlace

Los registros se guardan en el dispositivo y navegador, no en GitHub. No subas respaldos JSON ni CSV con tus ventas al repositorio público.

El nuevo dominio tiene un almacenamiento separado. Si registraste datos en el enlace anterior, descarga el respaldo allí y recupéralo en el nuevo enlace. No se trasladan automáticamente. Chrome y otros navegadores también pueden tener registros separados.

No borres los datos del navegador ni uses incógnito. El resumen muestra ingresos por ventas y costos de compras, no utilidad contable.

## Alcance y condiciones

GitHub Pages ofrece alojamiento estático en repositorios públicos con GitHub Free, sujeto a sus condiciones y límites. No hay garantía de que un proveedor mantenga esas condiciones para siempre. GitHub prohíbe usar Pages como alojamiento gratuito de negocios en línea, comercio electrónico o SaaS comercial. Este paquete es una herramienta que registra datos localmente; no tiene cobros, pedidos de clientes ni procesamiento de pagos. Revisa la adecuación de tu uso antes de convertirla en un servicio comercial.

Documentación oficial:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
- https://support.google.com/chrome/answer/9658361?co=GENIE.Platform%3DAndroid&hl=es

