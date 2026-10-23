# Subject Analysis HUD Showcase Demos

Набор интерактивных автономных HUD-шоукейсов (без внешних зависимостей, 60 FPS Canvas/WebAudio, с экспортом в WebM):

1. **[🏎 Porsche 911 GT3 R — Livery & Visual Upgrade HUD (`car.html`)](https://arekanderu161.github.io/pineapple-subject-analysis/car.html)** — автомобильный телеметрический визор с живой перекраской кузова в **5 гоночных ливрей** (с K-Means раскладкой представленных цветов) и **3 стадиями визуального тюнинга/апгрейда** (`Stage 1 Stock Cup` → `Stage 2 GT3 R Aero` → `Stage 3 GT2 RS Time-Attack Evo`).
2. **[⚔️ Codex of the Fallen — 3D Dark Fantasy Character HUD (`character.html`)](https://arekanderu161.github.io/pineapple-subject-analysis/character.html)** — интерактивный 3D-инспектор тёмного фэнтези рыцаря (*Morvaine, The Ashen Warden*) с вращением на 360°, грозой с молниями, анимацией сборки брони из осколков, 3 доспехами, 3 видами оружия и 3 уровнями вознесения (`LVL 1` → `LVL 50` → `LVL 100`).
3. **[🍍 2D Мультирежимный HUD-анализатор объекта (`index.html`)](https://arekanderu161.github.io/pineapple-subject-analysis/)** — 5 режимов визора (CCTV, Военный Дрон, Баллистический Прицел, Медицинский Био-Сканер, Кибер-Визор) с поддержкой загрузки собственных фото.

---

## 1. Porsche 911 GT3 R — Livery & Visual Upgrade HUD (`car.html`)

🔗 **Открыть демку спорткара:** https://arekanderu161.github.io/pineapple-subject-analysis/car.html

### Возможности:
- **5 живых расцветок ливреи (Live Pixel Recoloring + K-Means палитра):**
  - `01 · FaZe Clan Crimson` (оригинальный красно-чёрный окрас)
  - `02 · Gulf Miami Cyan` (бирюзовый неон + оранжевые акценты)
  - `03 · Manthey Acid Green` (кислотно-зелёный Nürburgring "Grello")
  - `04 · Weissach Solar Gold` (золотой металлик Porsche Motorsport)
  - `05 · Ultraviolet RS` (ультрафиолетовый пурпур)
  - На левой панели всегда отображаются **свотчи представленных цветов (`PRESENTED COLORS (5)`)**, а на этапе `03 · LIVERY COLORS` выводится полная **K-Means раскладка из 6 доминирующих оттенков** с HEX-кодами и процентами покрытия кузова.
- **3 стадии визуального апгрейда машины (`STAGE 1` → `STAGE 2` → `STAGE 3`):**
  - **`STAGE 1 · STOCK CUP` (510 HP):** заводской клиренс, базовый передний бампер, убранное антикрыло и канарды, мягкий свет фар.
  - **`STAGE 2 · GT3 R AERO` (565 HP):** занижение подвески `-15 мм`, карбоновый передний сплиттер с вертикальными стойками диффузора, двойные боковые дайв-канарды и подсвеченные торцевые пластины антикрыла Swan-Neck.
  - **`STAGE 3 · GT2 RS TIME-ATTACK EVO` (890 HP):** экстремальное занижение `-28 мм`, **огромное двухплоскостное карбоновое антикрыло** на верхних пилонах, **карбоновый воздухозаборник на крыше (Roof Ram-Air Scoop)**, **четыре боковых канарда + жабры на крыльях**, треугольные воздуховоды **NACA на капоте**, лазерные фары **Angel-Eyes** и **неоновая подсветка днища** в цвет выбранной ливреи.
  - Переключение апгрейда сопровождается вспышкой, искрами сварки и анимацией пристыковки деталей обвеса.

---

## 2. 3D Dark Fantasy Инспектор Персонажа (`character.html`)

🔗 **Открыть 3D-демку персонажа:** https://arekanderu161.github.io/pineapple-subject-analysis/character.html

- Живое 3D-вращение на 360° мышкой или тачем.
- 3 сета брони (*Fallen Paladin*, *Blood Knight*, *Frost Revenant*), 3 вида оружия (*Soulreaver Greatsword*, *Hellfire Executioner Axe*, *Shadow Twin Scythes*), 3 уровня прокачки (`LVL 1` → `LVL 50` → `LVL 100` с костяными крыльями, короной и печатью Бездны).
- Атмосферная гроза с ветвистыми молниями (`⚡ Гроза`) и сборка доспеха из разлетающихся осколков при смене уровня.

---

## 3. 2D Анализ объекта (`index.html`)

🔗 **Открыть 2D-демку:** https://arekanderu161.github.io/pineapple-subject-analysis/

![Surveillance subject analysis](pineapple-subject-analysis.gif)
