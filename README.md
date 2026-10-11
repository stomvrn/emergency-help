# Emergency Help

> Первая помощь для не медиков. 14 алгоритмов. Работает офлайн.

<span style="display:inline-block;padding:3px 10px;border-radius:6px;font-family:ui-monospace,SFMono-Regular,Consolas,monospace;font-size:11px;font-weight:700;margin-right:6px;margin-bottom:4px;border:1px solid;background:rgba(123,196,127,.12);color:#7bc47f;border-color:#7bc47f">license: CC0</span>
<span style="display:inline-block;padding:3px 10px;border-radius:6px;font-family:ui-monospace,SFMono-Regular,Consolas,monospace;font-size:11px;font-weight:700;margin-right:6px;margin-bottom:4px;border:1px solid;background:rgba(123,196,127,.12);color:#7bc47f;border-color:#7bc47f">offline: yes</span>
<span style="display:inline-block;padding:3px 10px;border-radius:6px;font-family:ui-monospace,SFMono-Regular,Consolas,monospace;font-size:11px;font-weight:700;margin-right:6px;margin-bottom:4px;border:1px solid;background:rgba(123,196,127,.12);color:#7bc47f;border-color:#7bc47f">tracking: none</span>
<span style="display:inline-block;padding:3px 10px;border-radius:6px;font-family:ui-monospace,SFMono-Regular,Consolas,monospace;font-size:11px;font-weight:700;margin-right:6px;margin-bottom:4px;border:1px solid;background:rgba(122,169,217,.12);color:#7aa9d9;border-color:#7aa9d9">single-file: yes</span>

> ⚠ **Информационный материал.** Не является медицинской рекомендацией. Все решения — после консультации с врачом.

**🔗 Открыть:** [stomvrn.github.io/emergency-help](https://stomvrn.github.io/emergency-help/)

---

## Что это

Справочник первой помощи для людей без медицинского образования. Простые пошаговые алгоритмы на случай, когда рядом никого, кроме тебя, а счёт идёт на секунды.

14 состояний: остановка дыхания, потеря сознания, сильное кровотечение, удушье, ожог, отравление, судороги, утопление, обморок, инфаркт, инсульт, перелом, шок, анафилаксия.

Алгоритмы составлены по приказу Минздрава России № 220н от 03.05.2024 и методическим материалам МЧС и Минздрава.

## Какую проблему решает

Человек в критической ситуации теряется. Он не знает что делать, а скорая едет десять минут. За эти десять минут можно потерять человека или сохранить ему жизнь. Разница — в простых действиях, которые нужно помнить наизусть и делать без паники.

Приложение показывает эти действия крупным шрифтом, пошагово, без интернета.

## Принципы

- **Single-file** — один HTML-файл, ноль зависимостей
- **Offline-first** — работает без интернета
- **CSP strict** — `connect-src 'none'`, ни одного сетевого запроса
- **No tracking** — ни телеметрии, ни cookies, ни аналитики
- **Local-only** — данные не покидают устройство

## Чего здесь нет

- Не собирает данные
- Не показывает рекламу
- Не требует регистрацию
- Не обещает медицинских гарантий
- Не заменяет обучение первой помощи

## Быстрый старт

1. Скачайте `index.html`
2. Откройте в любом современном браузере
3. Работает без интернета, без установки, без регистрации

**На телефоне:** сохраните файл в «Файлы» и откройте через браузер. Или добавьте на главный экран — работает как обычное приложение.

**Оффлайн:** после первого открытия страница работает без сети. Можно сохранить на флешку, отправить в мессенджере, распечатать.

## Структура

Один файл — всё внутри. Никаких `src/`, `lib/`, `app/`. Служебные файлы репозитория — вокруг, для GitHub.

## Безопасность

Этот инструмент — информационный справочник. Он **не заменяет** обучение первой помощи или консультацию врача.

Все алгоритмы составлены по общедоступным источникам:

- Приказ Минздрава России № 220н от 03.05.2024
- Методические материалы МЧС
- ФЗ-323 от 21.11.2011 «Об основах охраны здоровья граждан»

## Приватность

Все вычисления происходят локально. Никакие данные не отправляются на серверы. Никакая аналитика не собирается. CSP `connect-src 'none'` запрещает браузеру любой сетевой запрос.

## Лицензия

**CC0 · Public Domain.** Свободно к копированию, печати, распространению и использованию любым способом, без указания авторства.

Распечатайте, раздайте в школе, отправьте в родительский чат, разместите на сайте, раздайте в машине скорой. Ничего не нужно согласовывать.

## Автор

**Холин Иван Алексеевич (VanXo)** — врач-стоматолог, методолог, разработчик.

- GitHub: [@stomvrn](https://github.com/stomvrn)
- Telegram: [@ivan_kholin_digital](https://t.me/ivan_kholin_digital)
- Email: stom.vrn@gmail.com

---

**urn:vanxo:artifact:emergency-help:2.4.0** · Паспорт артефакта — в `artifact.json`
