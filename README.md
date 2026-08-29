# reNix Clock Card - Nixie style clock
[![GitHub All Releases](https://img.shields.io/github/downloads/vasques666/renix-clock-card/total?color=orange&label=Downloads&logo=github)](https://github.com/vasques666/renix-clock-card/)


<p align="center">
  <img src="https://raw.githubusercontent.com/vasques666/renix-clock-card/refs/heads/main/docs/images/renix-clock-card-v1.3.2-en.png" alt="Renix Clock Card" width="100%">
</p>

A custom Home Assistant Lovelace card with a layered reNix tube-style clock, weather/date information and configurable sensor panels.

## Version

**1.4.1**

## Features

- Integrated `reNix-Regular.woff2` font.
- 24-hour clock with seconds and grid layers.
- Weather icon, date and weekday.
- Outside temperature/humidity, pressure and room temperature/humidity.
- Pressure displayed to one decimal place.
- Independent night brightness for upper and lower sections.
- Configurable clock glow and colors through the visual editor.
- Frosted Glass blur support.
- Theme-controlled card background, border, shadow and radius when set to `null`.
- Language selection: Auto, Русский, English.
- Automatic language detection from the Home Assistant locale.

## HACS installation

1. Open HACS in Home Assistant.
2. Add this repository as a **Custom repository** with category **Dashboard**.
3. Install `reNix Clock Card`.
4. Add the resource if HACS does not do so automatically.
5. Add `type: custom:renix-clock-card` to a Lovelace dashboard.

## Example

See [`example.yaml`](example.yaml).


# Renix Clock Card

Красивая Nixie-style карточка часов для **Home Assistant**, созданная на основе шрифта **reNix**.

<p align="center">
  <img src="https://raw.githubusercontent.com/vasques666/renix-clock-card/refs/heads/main/docs/images/renix-clock-card-v1.3.2.png" alt="Renix Clock Card" width="100%">
</p>

Карточка объединяет часы, дату, погоду, температуру, влажность и атмосферное давление в одном блоке и позволяет настраивать внешний вид через визуальный редактор Home Assistant.

## Возможности

- встроенный шрифт **reNix** — отдельная установка шрифта не требуется;
- часы **HH:MM + секунды**;
- дата и день недели;
- текущая погода и иконка погоды;
- температура и влажность на улице;
- температура и влажность в помещении;
- атмосферное давление с округлением до **0,1**;
- выбор языка: `Auto`, `Русский`, `English`;
- автоматическое определение языка Home Assistant;
- настройка цвета часов и нижних датчиков;
- настройка `clock_glow`;
- отдельное управление яркостью верхней и нижней частей в ночном режиме;
- Frosted Glass и `backdrop-filter`;
- поддержка прозрачного фона и тем Home Assistant;
- визуальный редактор настроек непосредственно в Home Assistant.

## Установка через HACS

### Пользовательский репозиторий

1. Откройте **HACS → Frontend**.
2. Нажмите **⋮ → Пользовательские репозитории**.
3. Добавьте:

```text
https://github.com/vasques666/renix-clock-card
```

4. Тип репозитория: **Dashboard**.
5. Нажмите **Добавить**.
6. Найдите **Renix Clock Card** и установите последнюю версию.

## Настройка

Карточку можно добавить через визуальный редактор Home Assistant. Также доступна YAML-конфигурация:

[`example.yaml`](example.yaml).

## Обратная связь

Ошибки и предложения можно отправлять через [Issues](https://github.com/vasques666/renix-clock-card/issues).

Pull Request с улучшениями также приветствуются.

## Версия

**1.4.1** — текущая стабильная версия.

## GitHub

https://github.com/vasques666/renix-clock-card

---

**Renix Clock Card** — Nixie-style часы и датчики для Home Assistant.
