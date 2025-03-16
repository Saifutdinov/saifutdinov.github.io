---
theme: jekyll-theme-cayman
---
# Мое резюме (Русская версия)

{% include common/nav.md %}

![Мое фото](assets/images/avatar.jpg)


<!-- Навигация по блокам -->
- [Обо мне](#обо-мне-about-me)
- [Team Lead](#мой-опыт-team-lead)
- [Senior](#сеньор-разработчик-senior)

<!-- Вставляем блоки из _includes/ru/ -->
{% include ru/about.md %}
{% include ru/teamlead.md %}
{% include ru/senior.md %}

---
<!-- Кнопка, печатающая текущую страницу (скачивание в PDF через Print) -->
<button onclick="printPage()">Скачать текущую страницу в PDF</button>

---
Контакты

{% include common/contacts.md %}