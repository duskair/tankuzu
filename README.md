# takuzu

a logic puzzle game involving the placement of two symbols on a grid

## rules

### base rules  all variants

- **no three consecutive:** no more than two of either symbol can appear adjacent in a row or column
- **equal count:** there must be equal amounts of symbols in each row or column

### variants
---

#### classic takuzu

- played using `0`'s and `1`'s 
- **uniqueness:** no identical rows or columns

#### linkedin tango

- played using `☀️` (suns) and `🌙` (moons)
- **= (equals):** sits between two adjacent cells that must hold identical symbols
- **× (crosses):** sits between two adjacent cells that must hold opposite symbols


## Structure

```
takuzu/
├── index.html
├── styles.css
└── src/
    ├── board.js
    ├── config.js
    ├── generator.js
    ├── main.js
    ├── rng.js
    ├── room.js
    ├── rules.js
    ├── solver.js
    └── timer.js
```