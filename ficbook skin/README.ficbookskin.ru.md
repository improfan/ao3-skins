# Фикбук скин

[![Назад](https://img.shields.io/badge/Назад-blue.svg)](https://github.com/improfan/ao3-skins)

Этот скин был вдохновлен Фикбуком, очевидно.

Скин состоит из 3 (трёх) css, то есть для каждого нужно будет создать свой собственный скин. Тут я расскажу, как их объединить, чтобы они работали как один.

Перво-наперво хочу сказать, что иконки для скина я брала отсюда: [Replace the AO3 icons and default images [Site skin]](https://archiveofourown.gay/works/54831748). Не поленитесь и жмакните kudos на работе! Дефолтные иконки слишком выделялись, а иконки с приглушенными цветами подошли идеально. Скорее всего позже я сделаю свои.

Итак, необходимо сделать 3 (три) скина: 

- ficbook skin - main
- ficbook skin - icons
- ficbook skin - mobile

> [!NOTE]
> Помните, что названия должны быть уникальными! 

## 1. Main

1. Воспользуемся Wizard (кнопка "Use Wizard"), чтобы настроить цвета (Header Color, Accent Color и Background Color). Жмём Submit (Update, если уже создали скин до этого).

| Header Color | Accent Color | Background Color |
| :----------: | :----------: | :--: |
| #442302      | #ead6b5 | #f9f5ea |

2. Жмём Edit, чтобы закинуть наш кастомный css. Копируем css из файла [ficbook skin - main](/ficbook%20skin/ficbook%20skin%20-%20main.css), вставляем в поле для css и жмём Update.

## 2. Icons

1. Копируем css из файла [ficbook skin - icons](/ficbook%20skin/ficbook%20skin%20-%20icons.css), вставляем в поле для css и 
2. Раскрывавем секцию Advanced и в секции Parent Skins жмём Add Parent Skin и начинаем вводить название своего скина [Main](#1-main), выбираем его.
3. Жмём Submit (Update, если уже создали скин до этого).
   ![mobile](/images/advanced-section.png)

## 3. Mobile

1. Копируем css из файла [ficbook skin - mobile](/ficbook%20skin/ficbook%20skin%20-%20mobile.css), вставляем в поле для css. 
2. Раскрывавем секцию Advanced и проставляем в поле Media следующий пункт: only screen and (max-width: 42em)
![mobile](/images/advanced-section.png)
3. В секции Parent Skins жмём Add Parent Skin и начинаем вводить название своего скина [Main](#1-main), выбираем его.
4. Повторяем предыдущий пункт со скином [Icons](#2-icons).
4. Жмём Submit (Update, если уже создали скин до этого).

![mobile skin](/images/mobile-skin.png)

Прожимаем Use на Mobile скине и готово!

![skin showcase](/images/skin-showcase-1.png)
![skin showcase](/images/skin-showcase-2.png)
