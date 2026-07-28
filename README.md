# make-algo.com

Sitio corporativo de **Make Algo, S.L.** — desarrollo de software y consultoría en
inteligencia artificial, Madrid.

Sitio estático bilingüe (español / inglés). Sin build, sin dependencias y sin recursos de
terceros: HTML, una hoja de estilos, un archivo JavaScript sin librerías y las tipografías
autoalojadas.

## Estructura

| Ruta | Contenido |
|---|---|
| `index.html` · `en/index.html` | Portada en español e inglés |
| `aviso-legal.html` · `en/legal-notice.html` | Aviso legal (art. 10 LSSI-CE) |
| `privacidad.html` · `en/privacy.html` | Política de privacidad (RGPD / LOPDGDD) |
| `404.html` | Página de error, bilingüe |
| `assets/css/style.css` | Hoja de estilos única |
| `assets/js/main.js` | Menú móvil, barra fija y aparición al hacer scroll |
| `assets/fonts/` | Montserrat variable (woff2), autoalojada |
| `assets/img/` | Logotipos e iconos de las aplicaciones |

## Privacidad

El sitio **no utiliza cookies** ni herramientas de analítica, publicidad o seguimiento, y no
carga tipografías, scripts ni ningún otro recurso desde servidores de terceros. Por eso no
muestra banner de consentimiento.

## Desarrollo local

```bash
python3 -m http.server 4321
```

## Licencia

El código de este sitio se publica para su consulta. Los textos, logotipos, el emblema y los
iconos de las aplicaciones son titularidad de Make Algo, S.L.; su reproducción o uso requiere
autorización expresa. Ver el [aviso legal](aviso-legal.html).
