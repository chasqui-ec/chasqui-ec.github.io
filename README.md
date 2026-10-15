# Chasqui

Programa de escritorio para contadores en Ecuador. Descarga los comprobantes
electrónicos recibidos del portal del SRI y arma el reporte en Excel, con los
artículos reales de cada factura, los impuestos y la forma de pago.

**Página y descarga:** https://lrecaldeherij-debug.github.io/Chasqui/

---

Este repositorio contiene **solo la página y las descargas**. El código fuente
del programa no se publica aquí.

| Archivo | Para qué |
|---|---|
| `index.html` | La página. Se basta sola: la captura y el logo van dentro. |
| `chasqui-ventana.png` | La imagen que aparece al compartir el enlace por WhatsApp. |
| `version.json` | La versión publicada. Chasqui la consulta y avisa cuando hay una nueva. |

## Publicar una versión nueva

1. Subir el número de versión en el proyecto y compilar el instalador.
2. **Releases → Create a new release**, con el `.exe` adjunto.
   El archivo debe llamarse exactamente `ChasquiSetup.exe`.
3. Editar `version.json`: la versión nueva y una línea de qué cambió.

El botón de descarga de la página apunta a `releases/latest/download`, que
siempre lleva al último Release. No hay que tocar la página al publicar.

---

Chasqui es un producto de Soluciones Servicios Industriales Herij Cía. Ltda.,
Quito, Ecuador. No es un producto del Servicio de Rentas Internas ni está
afiliado a él.
