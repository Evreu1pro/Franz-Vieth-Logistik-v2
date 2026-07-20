# Franz Vieth Logistik — Professional Concept v4

Полностью переосмысленный demo/MVP для презентации клиенту.

## Концепция

**Operations-first logistics**: не «ещё одна транспортная компания», а понятный партнёр, который слушает, планирует и отвечает за результат.

- Клиентский путь главный: Transport / Lager / Baustoffe
- Карьера остаётся сильным вторым направлением
- Без искусственного preloader и автослайдеров
- Визуальный язык: industrial editorial, глубокий Vieth Blue, Signal Red только для действий
- Системные шрифты: сайт не зависит от Google Fonts и VPN

## Страницы

- `index.html` — новая главная
- `stellen/berufskraftfahrer.html` — вакансия водителя
- `stellen/disponent.html` — вакансия диспетчера
- `impressum.html`, `datenschutz.html`, `404.html` — юридические/служебные страницы

## Запуск

```bash
python3 -m http.server 8080
```

Открыть `http://localhost:8080`.

## Важно для production

Формы работают в прозрачном demo-режиме и не передают данные. Перед запуском подключить backend endpoint, серверную валидацию, защиту от спама и актуализировать Datenschutz/Impressum.

---

## Status · Статус · Status

| Lang | Note |
|:--|:--|
| **EN** | Client presentation concept (v4). Forms are demo-only. |
| **RU** | Концепт для презентации клиенту. Формы в demo-режиме. |
| **DE** | Präsentationskonzept für den Kunden. Formulare nur Demo. |

**Live demo:** https://franz-vieth-logistik-v2.vercel.app

Maintained by [@Evreu1pro](https://github.com/Evreu1pro) · Leipzig

