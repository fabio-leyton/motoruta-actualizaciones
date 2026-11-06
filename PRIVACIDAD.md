# Política de privacidad de MotoRuta

**Vigente desde:** 5 de noviembre de 2026

**Versión de la app:** 0.17.1 o posterior

MotoRuta es una app para Android que registra el consumo de gasolina, los
recorridos, los viajes y el mantenimiento de tus motos. Esta política explica qué
datos usa, dónde quedan y a quién se envían.

**En resumen:** tus datos se guardan en tu teléfono. MotoRuta no tiene cuentas de
usuario, publicidad ni estadísticas de uso, y el responsable de la app no recibe
tus registros. Solo salen del teléfono los datos necesarios para buscar lugares,
calcular rutas y buscar actualizaciones, y los que tú decidas compartir.

## 1. Responsable

El desarrollador de MotoRuta, en Colombia.
Contacto para temas de privacidad: WhatsApp +57 311 806 8358.

## 2. Qué datos guarda la app en tu teléfono

- **Motos:** nombre, marca, modelo, año, tanque, kilometraje, líneas del medidor y
  demás datos que escribas.
- **Gasolina:** tanqueadas, precios, valores pagados, gasolineras, trip,
  kilometraje y la foto del recibo si la agregas.
- **Ubicación de tus gasolineras:** el lugar (coordenadas) de cada gasolinera donde
  registras una tanqueada, para escogerla sola la próxima vez que tanquees ahí.
- **Recorridos y viajes:** kilómetros, destinos y tramos que planeas.
- **Viajes con GPS:** fecha, hora, kilómetros, destino, avisos de gasolina y **la
  ruta recorrida** (un punto de ubicación cada 50 metros, aproximadamente), la
  velocidad promedio y máxima, y cómo se comportó la señal del GPS.
- **Mantenimiento y gastos:** servicios, talleres, costos, vencimientos (SOAT,
  técnico-mecánica) y observaciones.
- **Fotos y documentos que agregues:** fotos de la moto, del SOAT, la
  técnico-mecánica u otros documentos (en foto o PDF), facturas y fotos de
  repuestos y mejoras. Un documento como el SOAT puede tener tu nombre, tu número
  de documento y la placa. Las fotos se guardan reducidas.
- **Ajustes y licencia:** preferencias de la app y el estado de tu licencia.

Estos datos no se envían al responsable de la app ni a terceros, salvo en los
casos de las secciones 3 y 4. Puedes borrarlos desde la app o desinstalándola
(ver la sección 7).

## 3. Datos que salen del teléfono

| Cuándo | Qué se envía | A quién |
|---|---|---|
| Al planear un viaje nuevo (el punto de partida se llena solo), al tocar "mi ubicación", al calcular la distancia de un viaje con GPS o al registrar una tanqueada con la ubicación activa | Tu ubicación o la de la gasolinera (coordenadas) para ponerle nombre al lugar o mostrar su dirección | El servicio de ubicación de Android (Google) y, si no responde, OpenStreetMap (Nominatim) |
| Al buscar un sitio, dirección, barrio o destino | El texto que escribes; si no escribes la ciudad, se le agrega la del punto de partida o la de tu ubicación, y a OpenStreetMap se le envía además una zona aproximada de unos 30 km alrededor de ti para preferir lo cercano | El servicio de ubicación de Android (Google) y OpenStreetMap (Nominatim) |
| Al calcular la distancia de un tramo o de un viaje | Las coordenadas de origen y destino | OSRM (router.project-osrm.org), un servicio público de rutas |
| Al abrir Google Maps o Waze, o al buscar gasolineras | El destino o la búsqueda | La app de mapas que elijas |
| Al dictar una tanqueada con el micrófono | Tu voz, para convertirla en texto. La app no graba ni pide el micrófono: lo hace el servicio de voz del teléfono | El servicio de dictado de Android (normalmente Google) |
| Al abrir la app y al descargar una actualización | Solo la consulta y la descarga de la versión nueva, sin datos tuyos | GitHub |

Estos servicios reciben, además, la dirección IP de tu conexión, como cualquier
servicio de internet. Cada uno tiene su propia política de privacidad. MotoRuta no
les envía tus registros, tu nombre ni el código de tu teléfono.

Mientras mide un viaje o un recorrido con GPS, la ruta se guarda **solo en tu
teléfono**. La lista de tus gasolineras con su ubicación tampoco sale del
teléfono, salvo en los respaldos; solo se consulta la dirección del punto donde
tanqueas, como dice la tabla, y la dirección no se guarda. La ubicación se usa de forma continua solo mientras la medición está
activa (entre Iniciar y Terminar), y Android lo indica con una notificación fija.
Fuera de eso, solo se lee una vez en los casos de la tabla.

## 4. Datos que tú decides compartir

- **Código del teléfono para activar la licencia.** Es un código derivado del
  identificador del teléfono, que no contiene tu nombre ni tu número. Solo lo
  recibe el responsable si tú lo envías, junto con los datos de contacto que uses
  para enviarlo (por ejemplo, tu número de WhatsApp). Se usa únicamente para
  generar tu código de activación y llevar el registro de tu licencia.
- **Respaldos e informes.** La app guarda copias en la carpeta Descargas de tu
  teléfono. Si compartes un respaldo, un PDF, un Excel o un CSV, quien lo reciba
  podrá ver lo que contiene. Los respaldos pueden cifrarse con contraseña desde
  Ajustes > Respaldos. Los respaldos incluyen tus fotos y documentos, y la ubicación de
  tus gasolineras.
- **Copia de seguridad de Android.** Si la tienes activa en tu teléfono, Android
  puede guardar una copia de los datos de la app en tu cuenta de Google. La clave
  de los respaldos cifrados y las fotos y documentos nunca se incluyen. Puedes
  desactivarla en los ajustes de Android.
- **Fotos y documentos que compartes.** Si compartes un SOAT o una factura desde la
  app, lo recibe la app o persona que elijas.

## 5. Permisos que pide la app

- **Ubicación:** para medir recorridos y viajes con GPS, para detectar el punto de
  partida de un viaje y para reconocer la gasolinera al registrar una tanqueada.
  Solo mientras usas esas funciones.
- **Notificaciones:** avisos de gasolina, mantenimiento, vencimientos y la
  notificación fija mientras mide el GPS.
- **Servicio en primer plano de ubicación:** para que la medición siga con la
  pantalla apagada o con otra app de mapas abierta.
- **Ignorar la optimización de batería (opcional):** solo si lo aceptas, para que
  Android no cierre la app durante un viaje.
- **Cámara y fotos:** solo cuando eliges tomar una foto o escogerla de la galería
  para guardarla en un registro. La app no ve tu galería: Android le entrega solo
  las fotos que eliges.
- **Micrófono:** la app no lo pide. Al dictar una tanqueada, el servicio de voz
  del teléfono escucha y le devuelve el texto a la app.
- **Instalar actualizaciones:** para instalar la versión nueva que descargas.
- **Internet:** para los servicios de la sección 3.
- **Iniciar con el teléfono:** para volver a programar los avisos de mantenimiento
  después de reiniciar.

## 6. Seguridad y conservación

Los datos, fotos y documentos quedan en el almacenamiento privado de la app,
donde otras apps no pueden verlos. Se conservan hasta que
los borres o desinstales la app. La app conserva las 5 copias de respaldo más
recientes dentro de la app y otras 5 en Descargas, y borra las anteriores.

El registro de licencias del responsable (código del teléfono y fechas de la
licencia) se conserva mientras la licencia esté vigente y el tiempo que exija la
ley.

## 7. Tus derechos

De acuerdo con la Ley 1581 de 2012 de Colombia, puedes conocer, actualizar,
rectificar y pedir que se supriman tus datos, y revocar tu autorización.

- **Datos en tu teléfono:** los manejas tú. Puedes editarlos o borrarlos en la app,
  borrar los datos de la app en los ajustes de Android o desinstalarla. Las copias
  en Descargas y las que hayas compartido se borran aparte.
- **Datos que enviaste al responsable** (código del teléfono y contacto para la
  licencia): escribe por WhatsApp al +57 311 806 8358. Responderemos en los plazos
  de la ley.

## 8. Menores de edad

MotoRuta está pensada para conductores de moto. No está dirigida a menores de
edad.

## 9. Cambios a esta política

Si la app empieza a usar datos de otra forma, por ejemplo con una copia en la nube,
esta política se actualizará antes y el cambio se anunciará en las novedades de la
versión.
