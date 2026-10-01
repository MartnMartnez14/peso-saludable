# Peso Saludable ✦

Una web interactiva en español para calcular el IMC, recibir consejos según tus condiciones de salud y registrar el progreso, todo en una sola página.

## Abrir la web

[Visitar Peso Saludable](https://martnmartnez14.github.io/peso-saludable/)

También funciona sin internet: descarga el archivo `index.html` y ábrelo en el navegador.

## Capturas

**Calculadora de IMC**

![Calculadora](docs/images/calculadora.png)

**Consejos adaptados** (por ejemplo, si marcas diabetes)

![Hábitos y consejos](docs/images/habitos.png)

**Seguimiento** con gráfica de colores según suba o baje el peso

![Mi seguimiento](docs/images/seguimiento.png)

## Qué incluye

- Calculadora de IMC (sobrepeso, obesidad leve, obesidad moderada/severa).
- Consejos generales y, si marcas condiciones, recomendaciones adaptadas a diabetes, colesterol, hipertensión o enfermedad cardiovascular.
- Pestaña de evidencia, con el estudio de atención primaria [JABFM 2009;22(5):544](https://www.jabfm.org/content/22/5/544) y enlaces a [MedlinePlus en español](https://medlineplus.gov/spanish/).
- Seguimiento de peso, pasos y agua, guardado en el navegador (`localStorage`). La gráfica cambia de color: verde si bajó, amarillo si se mantuvo, rojo si subió.
- Fondo ambient con paleta azul / rojo / amarillo / verde.

La información es educativa y no sustituye el consejo de un profesional de la salud.

## Para quien desarrolla

Un solo archivo HTML (`index.html`) con CSS y JavaScript incluidos. Sin dependencias, sin build.

| Archivo | Uso |
| --- | --- |
| `index.html` | App (GitHub Pages sirve este archivo) |
| `docs/images/` | Capturas del README |
| `.nojekyll` | Evita que GitHub Pages procese la carpeta `docs` como Jekyll |

Para probar en local:

```bash
python3 -m http.server 8765
```

Abre [http://127.0.0.1:8765](http://127.0.0.1:8765).

Hecho con HTML, CSS y JavaScript; preparado para GitHub Pages.

## Apoyar el proyecto

¿Te gustó el proyecto? Si quieres colaborar voluntariamente, puedes invitarme a un cafecito o mate.

- [Ko-fi](https://ko-fi.com/martinmartinezgarcia)
- [PayPal](https://www.paypal.com/paypalme/blufferedtwitch)
- [Internet satelital Starlink](https://starlink.com/es?referral=RC-DF-5848974-78640-68&app_source=share) (enlace de afiliado; puede ofrecerte el primer mes según las condiciones vigentes de Starlink)
