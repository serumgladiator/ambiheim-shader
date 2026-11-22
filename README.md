# Ambiheim Shader

Личный форк Solas Shader. Сделан чисто под себя: свои пресеты.

Основа — [Solas Shader V3.9](https://github.com/Septonious/Solas-Shader) от Septonious (CurseForge и Modrinth).

## Пресеты

Общие: Very Low, Low, Medium, High (значения по умолчанию в коде), Ultra.

Под железо:

- **ARDOR GAMING NEO N15-I5ND411** (i5-12450H, RTX 3050 6GB, 16GB, 1080p 144 Гц)
  - `ARDOR_NEO_N15` — основной баланс
  - `ARDOR_NEO_PERF` — легче, ближе к 144 Гц
  - `ARDOR_NEO_MAX` — от сети, чуть выше High
- **Huawei MateBook D15** (встройка Iris Xe / Vega, часто 8GB, 1080p 60 Гц)
  - `MATEBOOK_D15` — бережный
  - `MATEBOOK_D15_PLUS` — если 16GB или iGPU посильнее

На Intel iGPU цветное освещение Solas часто само отключается. Это поведение оригинала.

## Установка

Положи `Ambiheim Shader.zip` в `.minecraft/shaderpacks` и выбери его в Iris или OptiFine. Профиль — вверху меню шейдера.
