# WildSketch

Адаптивний односторінковий сайт студії малювання просто неба. Командний проєкт у
межах курсу GoIT Fullstack Developer (HTML + CSS).

**Живий сайт:** https://alexanderkobzarenko.github.io/project-98BENZIN/

## Превʼю

| Секція      | Десктоп (1440 px)                          | Планшет (768 px)                          | Мобільна (375 px)                             |
| ----------- | ------------------------------------------ | ----------------------------------------- | --------------------------------------------- |
| Header      | ![Header](./docs/desktop/header.jpg)       | ![Header](./docs/tablet/header.jpg)       | ![Header](./docs/mobile/header.jpg)           |
| Hero        | ![Hero](./docs/desktop/hero.jpg)           | ![Hero](./docs/tablet/hero.jpg)           | ![Hero](./docs/mobile/hero.jpg)               |
| Benefits    | ![Benefits](./docs/desktop/benefits.jpg)   | ![Benefits](./docs/tablet/benefits.jpg)   | ![Benefits](./docs/mobile/benefits.jpg)       |
| Gallery     | ![Gallery](./docs/desktop/gallery.jpg)     | ![Gallery](./docs/tablet/gallery.jpg)     | ![Gallery](./docs/mobile/gallery.jpg)         |
| Events      | ![Events](./docs/desktop/events.jpg)       | ![Events](./docs/tablet/events.jpg)       | ![Events](./docs/mobile/events.jpg)           |
| Team        | ![Team](./docs/desktop/team.jpg)           | ![Team](./docs/tablet/team.jpg)           | ![Team](./docs/mobile/team.jpg)               |
| Feedbacks   | ![Feedbacks](./docs/desktop/feedbacks.jpg) | ![Feedbacks](./docs/tablet/feedbacks.jpg) | ![Feedbacks](./docs/mobile/feedbacks.jpg)     |
| Register    | ![Register](./docs/desktop/register.jpg)   | ![Register](./docs/tablet/register.jpg)   | ![Register](./docs/mobile/register.jpg)       |
| Footer      | ![Footer](./docs/desktop/footer.jpg)       | ![Footer](./docs/tablet/footer.jpg)       | ![Footer](./docs/mobile/footer.jpg)           |
| Mobile menu | —                                          | —                                         | ![Mobile menu](./docs/mobile/mobile-menu.jpg) |

## Про проєкт

WildSketch — лендінг за макетом у Figma та технічним завданням. На сторінці є
секції: Header, Hero, Benefits, Gallery, Events, Team, Feedbacks, Register
(форма), Footer та мобільне меню.

## Можливості

- Адаптивна верстка за підходом mobile first: 375 / 768 / 1440 px
- Семантичний HTML5, валідні HTML і CSS
- `modern-normalize`, шрифти Caveat і Tajawal
- SVG-іконки через єдиний спрайт
- Зображення для retina-екранів (1x і 2x)
- Форма реєстрації з валідацією (`required`, `pattern`)
- Мобільне меню, що відкривається класом `is-open`

## Технології

- HTML5, CSS3
- [Vite](https://vitejs.dev/) з `vite-plugin-html-inject` (сторінка збирається з
  partials)
- GitHub Actions та GitHub Pages для деплою

## Команда

| Секція      | Розробник                                                                                                                                                  |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Header      | [@serhiy-ozheniok](https://github.com/serhiy-ozheniok)                                                                                                     |
| Hero        | [@denysprontsevych](https://github.com/denysprontsevych) (розмітка, стилі), [@victoralexandrovich](https://github.com/victoralexandrovich) (доопрацювання) |
| Benefits    | [@ps-bellatrix](https://github.com/ps-bellatrix)                                                                                                           |
| Gallery     | [@Daniil2707](https://github.com/Daniil2707)                                                                                                               |
| Events      | [@ps-bellatrix](https://github.com/ps-bellatrix)                                                                                                           |
| Team        | [@MuraDrogo](https://github.com/MuraDrogo)                                                                                                                 |
| Feedbacks   | [@MuraDrogo](https://github.com/MuraDrogo)                                                                                                                 |
| Register    | [@Ivanduik](https://github.com/Ivanduik)                                                                                                                   |
| Footer      | [@AlexanderKobzarenko](https://github.com/AlexanderKobzarenko)                                                                                             |
| Mobile menu | [@devlebid](https://github.com/devlebid)                                                                                                                   |

**Team Lead:** [@AlexanderKobzarenko](https://github.com/AlexanderKobzarenko)
**Scrum Master:** [@Ivanduik] **Ментор:** [@SergeyKorobka]

## Швидкий старт

Потрібно: [Node.js](https://nodejs.org/) (LTS-версія).

```bash
git clone git@github.com:AlexanderKobzarenko/project-98BENZIN.git
cd project-98BENZIN
npm install
npm run dev
```

Відкрийте http://localhost:5173. Сторінка перезавантажується після збереження
файлів.

| Команда           | Опис                                    |
| ----------------- | --------------------------------------- |
| `npm run dev`     | Запустити сервер розробки               |
| `npm run build`   | Зібрати продакшн-версію в папку `dist/` |
| `npm run preview` | Переглянути зібрану версію локально     |

## Структура проєкту

```
src/
├─ index.html        сторінка, зібрана з partials
├─ main.js
├─ partials/         HTML кожної секції (header.html, hero.html, benefits.html, gallery.html, events.html, team.html, feedbacks.html, register.html, footer.html, mobile-menu.html)
├─ css/              стилі кожної секції, підключені в main.css
├─ img/              зображення та спрайт icons.svg
└─ public/           favicon
```

## Робочий процес

- `main` — стабільна гілка, прямі коміти заборонені.
- Кожна задача виконується в окремій гілці, названій за секцією.
- Зміни потрапляють у `main` лише через Pull Request після перевірки.
- Кожен пуш у `main` автоматично збирається та розгортається в гілку `gh-pages`.

## Посилання

- Дизайн:
  [Figma](https://www.figma.com/design/n9IyoxHkRQEIRHwdqlDPOf/Wild-Sketch)
