# Drill — Présent de l'indicatif

Quiz interactivo de conjugación del **presente de indicativo** en francés. 282 conjugaciones (47 verbos × 6 personas), en orden aleatorio.

🔗 **Demo:** https://nilquera.github.io/conjugaison-presente/

## Características

- Cubre las tres clasificaciones: verbos irregulares, verbos en `-er`, y verbos con otra terminación.
- Cubre verbos con 1, 2 y 3 radicales, incluyendo casos especiales: `offrir`/`découvrir`, `attendre`/`descendre`, verbos del 2.º grupo (`-iss-`), cambios ortográficos (`manger`, `commencer`), cambios de acento (`lever`, `préférer`), doble consonante (`appeler`, `jeter`), `y → i` (`envoyer`, `essuyer`), variantes opcionales (`payer`, `essayer`), pronominales (`s'évanouir`), y verbos de 3 radicales (`venir`, `prendre`, `devoir`, `boire`).
- Acepta variantes válidas (p.ej. `je paie` y `je paye`), apóstrofos rectos y curvos, y normaliza espacios.
- Pronunciación con un click en cada respuesta (Web Speech API; voz femenina francesa preferida).
- Modo "rehacer sólo los errores" al final.
- Botón para esconder la pista de categoría (útil para auto-evaluación más estricta).
- Modo claro/oscuro automático según el sistema operativo.
- Sin servidor, sin dependencias externas — funciona offline en cuanto se carga.

## Verbos incluidos

**Irregulares:** être, avoir, aller, faire, dire, pouvoir, vouloir.
**1 radical:** courir, rire, travailler, étudier, jouer, attendre, descendre, offrir, découvrir.
**2 radicales:** dormir, grossir, lire, écrire, mettre, guérir, choisir, vieillir, salir, rougir, applaudir, réfléchir, s'évanouir, voir, croire, lever, acheter, préférer, espérer, appeler, jeter, envoyer, essuyer, payer, essayer, manger, commencer.
**3 radicales:** venir, prendre, devoir, boire (+ pouvoir y vouloir, ya en irregulares).

## Cómo funciona localmente

Sólo abre `index.html` en cualquier navegador moderno. No hace falta servidor.

```bash
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

## Uso

1. El quiz muestra un verbo en infinitivo y un pronombre.
2. Escribe la conjugación completa (incluyendo el pronombre y la elisión cuando corresponda: `j'ai`, `j'offre`, `je m'évanouis`).
3. **Enter** para verificar; **Enter** otra vez para pasar a la siguiente.
4. Al final, repite sólo los errores con un click.

## Despliegue (GitHub Pages)

Repo público con `index.html` en la raíz. En **Settings → Pages**, source = `main` branch, folder = `/ (root)`.

## Licencia

MIT.
