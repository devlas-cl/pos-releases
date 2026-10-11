# Devlas POS

Sistema de punto de venta para comercios en Chile, con boleta y factura electrónica al SII incluidas. Funciona sin internet y sincroniza al reconectar.

Sitio oficial: [www.devlas.cl/pos](https://www.devlas.cl/pos)

## Descargar

| Plataforma | Dónde |
|---|---|
| Windows 10 u 11 | [Última versión (.exe)](https://github.com/devlas-cl/pos-releases/releases/latest) |
| macOS 12 o superior | [Última versión (.dmg)](https://github.com/devlas-cl/pos-releases/releases/latest) |
| Android | [Google Play](https://play.google.com/store/apps/details?id=pos.devlas.app) |
| iPhone | [TestFlight](https://testflight.apple.com/join/3vN525k3) (versión beta) |
| Navegador | [pos.devlas.cl](https://pos.devlas.cl), sin instalar nada |

En Windows 7 u 8 no se puede instalar la aplicación de escritorio. Usa la versión web.

## Qué incluye

- Boleta y factura electrónica al SII, con firma, timbraje y folios automáticos.
- Inventario multi sucursal, bodegas, compras y guías de despacho.
- Caja con apertura, cierre y arqueo, y varios usuarios con roles.
- Cobro con tarjeta (SumUp, Mercado Pago Point) y medios de pago propios.
- Importación y exportación a Excel y CSV. Tus datos son tuyos.
- API REST y webhooks: [api.devlas.cl/docs](https://api.devlas.cl/docs).

## Planes

| Plan | Precio al mes |
|---|---|
| Starter | $7.490 CLP |
| Pro | $17.990 CLP |
| Full | $34.990 CLP |

14 días gratis, sin tarjeta de crédito, sin contratos ni permanencia. El detalle actualizado está en [devlas.cl/pos](https://www.devlas.cl/pos#precios).

## Cómo probarlo

1. Descarga la aplicación y regístrate con el RUT de tu comercio.
2. Sube tu certificado digital y emite una boleta de prueba. Revisa que aparezca aceptada en tu portal del SII.
3. Conecta tu impresora y tu lector de códigos de barras y haz una venta completa.
4. Exporta tus ventas y productos a Excel desde Ajustes, Suscripción, Exportar mis datos.

## Historial público

Cada versión publicada queda registrada en la [página de releases](https://github.com/devlas-cl/pos-releases/releases), con más de 140 versiones desde agosto de 2025. El número 1.0.0 marca la graduación a versión estable, no el inicio del producto.

## Quién lo desarrolla

Devlas SpA, RUT 78.206.276-K, Santiago de Chile. Devlas POS es desarrollo propio, no es marca blanca ni reventa. El motor de facturación electrónica es [@devlas/dte-sii](https://github.com/devlas-cl/dte-sii), con código abierto (MIT) y publicado en [npm](https://www.npmjs.com/package/@devlas/dte-sii).

## Soporte

WhatsApp directo con el equipo, todos los días de 7:00 a 22:00 (hora de Chile): [wa.me/56972269035](https://wa.me/56972269035). También en contacto@devlas.cl.
