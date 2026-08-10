# INK DREAM — промпты для генерации графики (партия 1: текущие 3 зоны)

Как пользоваться:
1. Генерируй по одному промпту. **Стилевой блок добавляй в конец каждого промпта** — он даёт единый стиль.
2. Фоны — соотношение **3:2** (или 1152×768). Предметы — **квадрат 1:1**, один предмет по центру, чистый белый фон.
3. Присылай мне PNG прямо в чат (или загрузи в репозиторий: Add file → Upload files). Белый фон у предметов я вырежу сам.
4. Если вариант не в стиле остальных — лучше перегенерить: единый стиль важнее красоты отдельной картинки.

---

## Стилевой блок (копируй в конец КАЖДОГО промпта)

```
hand-drawn black ink illustration, monochrome, thin sketchy linework, dreamy
surreal minimalism, storybook style, off-white paper texture, lots of negative
space, no text, no letters, no watermark, no signature
```

⚠️ «no text, no letters» — критично: буквы в игре проявляются кодом, лишние буквы на арте сломают головоломки.

---

## Фоны (3 шт, соотношение 3:2)

### BG-1 · Зона I «Дерево»
```
a lonely tall gnarled tree on a low hill in an empty dream field, full moon in
the sky, a tiny wooden door embedded in the tree trunk at its base, an empty
rectangular picture frame hanging from a branch on a string, sparse grass
ticks, vast empty sky
```

### BG-2 · Зона II «Комната»
```
a strange empty dream room interior, bare wall, a wooden table with thin legs,
a small window with the moon visible through it, a tall closed wooden cupboard
on the right, a narrow vertical wall panel with three round empty dials on the
left, a small arched door in the far right wall
```

### BG-3 · Зона III «Озеро»
```
a still night lake under an empty sky, a bare dead tree on the left shore, a
low flat stone pedestal near the water, a tall standing oval mirror on the
right, a single closed wooden door standing impossibly on the water surface,
gentle ripple lines
```

---

## Предметы (квадрат 1:1, один предмет, белый фон)

К каждому: `single object centered on plain white background, isolated` + стилевой блок.

| # | ID в игре | Промпт |
|---|---|---|
| OB-1 | p1a | `a small curved bare tree branch, gentle S-curve, top hook shape` |
| OB-2 | p1b | `a small curved bare tree branch, gentle S-curve, bottom hook shape` |
| OB-3 | p2a/b/c | `three torn horizontal strips of old paper with ragged edges, stacked loosely` (нарежу на 3 куска сам) |
| OB-4 | p3a/b/c | `three small hand-drawn leaves of slightly different shapes in a row` (нарежу) |
| OB-5 | p4twig | `a thin bare twig with one small side shoot` |
| OB-6 | spoon | `an old simple metal spoon, side view` |
| OB-7 | p4key | `an old-fashioned skeleton key with round bow and two teeth` |
| OB-8 | p6a-d | `a broken ceramic plate shattered into four large shards, laid out slightly apart` (нарежу) |
| OB-9 | p7m | `a full moon disc with two faint craters, soft round outline` |
| OB-10 | p8a-c | `three smooth flat stones of decreasing size in a row, like a cairn kit` (нарежу) |
| OB-11 | p9h | `the left half of a symmetrical moth with folded wing, cut cleanly along the vertical center line` |
| OB-12 | дверь | `a small arched wooden door with a round knob, slightly ajar version and closed version side by side` |
| OB-13 | диски | `a round dial face with a single bold pointer line, like a strange clock without numbers` |
| OB-14 | банка | `an empty glass jar with a faint outline` |

## Финал и заставка (по желанию, 3:2)

### FIN-1
```
a small girl silhouette in a dress standing beside a lonely tree under a full
moon, seen from behind, vast empty dream field, quiet and peaceful
```

### TITLE-1
```
an open ink bottle with a thin wisp of ink smoke rising and forming a dreamy
swirl in the air, a fallen pen beside it
```

---

## Что произойдёт дальше

Ты присылаешь картинки → я вырезаю фон, сжимаю, встраиваю в игру поверх текущих
хитбоксов (логика паззлов не меняется) → прогоняю автотест всех 9 паззлов →
обновляю играбельную ссылку. Если какой-то предмет не ляжет по силуэту в
паззл с буквой — скажу, и для него оставим чернильный контур или перегенерим
с уточнённой формой.
