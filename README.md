# Pineapple & Cyberpunk Character Subject Analysis HUD

Набор интерактивных HUD-инструментов и бесшовных анимаций в стиле тактического сканера:
1. **[2D Мультирежимный HUD-анализатор (`index.html`)](https://arekanderu161.github.io/pineapple-subject-analysis/)** — 5 режимов визора (CCTV, Военный Дрон, Баллистический Прицел, Медицинский Био-Сканер, Кибер-Визор) с поддержкой загрузки собственных фото.
2. **[3D Киберпанк-инспектор игрового персонажа (`character.html`)](https://arekanderu161.github.io/pineapple-subject-analysis/character.html)** — интерактивная WebGL/Three.js демка с 360° вращением, переключением оружия, скинов/костюмов и уровней прокачки (`LVL 1` → `LVL 50` → `LVL 100`).

---

## 1. 3D Киберпанк-инспектор персонажа (`character.html`)

🔗 **Открыть 3D-демку персонажа:** https://arekanderu161.github.io/pineapple-subject-analysis/character.html

### Возможности:
- **Живое 3D-вращение на 360° (Three.js + OrbitControls):** персонажа можно крутить мышкой и приближать в любой момент, либо оставить в автоматическом 18-секундном цикле (`AUTO SHOWCASE`).
- **6 этапов анализа игрового юнита:**
  1. `01 · 360° SCAN` — захват цели на голографическом подиуме с телеметрией угла поворота.
  2. `02 · RIG & HITBOX` — включение 3D-wireframe сетки, отрисовка 13 костей игрового скелета и зон множителя урона (`CRIT HITBOX 2.5x`, `TORSO 1.0x`, `LIMBS 0.75x`).
  3. `03 · SUIT / SKINS` — демонстрация и смена **3 костюмов** (*Street Merc*, *Arasaka Spec-Ops*, *Netrunner Gold*) с выносками к броне и реактору.
  4. `04 · ARSENAL` — фокус камеры на оружии в руке, переключение **3 видов 3D-оружия** (*Plasma Rifle*, *Thermal Katana*, *Heavy EM-Railgun*) и разбор модулей.
  5. `05 · LVL 1→100` — визуальная и числовая прокачка персонажа (*LVL 1 Rookie* → *LVL 50 Veteran* с тяжелыми наплечниками → *LVL 100 Cyber-God* с энергетическими крыльями, нимбом и орбитальным дроном) + пятиугольная радарная диаграмма характеристик.
  6. `06 · DOSSIER` — финальная легендарная карточка оперативника (`SSR LEGENDARY`) с глитч-переходом.

---

## 2. 2D Анализ объекта (`index.html`)

🔗 **Открыть 2D-демку:** https://arekanderu161.github.io/pineapple-subject-analysis/

**15 секунд · 15 fps · 225 кадров · 998 × 748**

![Surveillance subject analysis](pineapple-subject-analysis.gif)

## Файлы репозитория

- [3D Киберпанк-персонаж (`character.html`)](character.html)
- [2D Мультирежимный HUD-терминал (`index.html`)](index.html)
- [Исходный промпт и согласованная адаптация (`PROMPT.md`)](PROMPT.md)
- [Скачать GIF](pineapple-subject-analysis.gif)
- [Скачать MP4](pineapple-subject-analysis.mp4)
- [Исходное изображение](source.png)
