# delantras-legal

Política de privacidad de **Delantrás** (JR Soft, `com.jrsoft.camara`), publicada con GitHub Pages en
`https://demual.github.io/delantras-legal/`.

- `index.html`: los 16 idiomas.
- `privacidad-<idioma>.html`: la política en cada idioma. La app abre la de su idioma
  (`PRIVACY_URL` + `privacidad-<idioma>.html`; si no hay, la inglesa).

No se edita a mano: se genera con `python -I tools/web_legal.py` en el repositorio de la app, a partir de
`docs/legal/privacidad_<idioma>.md`, y se copia aquí entera. Sin scripts ni recursos de fuera.
