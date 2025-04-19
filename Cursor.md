# [Cursor](https://www.cursor.com/)
## Общие сведения
* Описание: закрытая сборка на основе [VS Code](VS%20Code.md) ориентированная на разработку с ассистентом.
* Ассистенты: проприетарный с набором разных моделей с расширенным функционалом, работает без VPN. Можно подключить сторонние модели по OpenAI протоколу. Локальные модели не поддерживаются
* Доступность: обновление без VPN
* Оплата: российскими картами не работает. Есть бесплатный тарифный план, в котором использование ассистента доступно, но ограничено
## Стоимость на 19.04.2025

![](Pasted%20image%2020250419202605.png)
## Возможности
* использование плагинов [VS Code](VS%20Code.md), импорт из уже настроенной [VS Code](VS%20Code.md) плагинов и настроек;
* использование как встроенных моделей, так и сторонних проприетарных через API, однако подключить http://io.net/ пока не получилось:
![](Pasted%20image%2020250410113931.png)
* Использование ряда моделей в бесплатной версии:
	* Deepseek-r1;
	* Deepseek-v3.1;
	* cursor-fast;
	* cursor-small;
	* gpt-4o-mini.
## Что посмотреть и почитать
* https://www.youtube.com/watch?v=5rlhqupf7sE - базовый обзор возможностей и настроек;
* https://www.youtube.com/watch?v=pHr179iQ6rU - # Cursor AI на максималках! | 7 фичей, о которых вы не знали (rules, directory, MCP, docs, commit);
* https://github.com/PatrickJS/awesome-cursorrules?tab=readme-ov-file - а curated list of awesome .cursorrules files for enhancing your Cursor AI experience. `.cursorrules` files define custom rules for Cursor AI to follow when generating code, allowing you to tailor its behavior to your specific needs and preferences.
## Нерешенные проблемы
* подключить модели с [IO.net](IO.net) пока не получилось:
![](Pasted%20image%2020250419211109.png)