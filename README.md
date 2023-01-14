# Проект: Путешествие по России
Проект о красотах России. Это мой третий проект. В прошлых проектах мне не хватало адаптивности под все типы устройств. В этом проекте я решил это реализовать.

__Проект написан на HTML5 и CSS.__
___

# ___Технологии, использованные в проекте:___
1. Nested-структура и привязка ```@import```
```css
@import url(../blocks/header/__lang-link/header__lang-link.css);
```
2. ```@media и CSS grid layout```
```css
@media screen and (max-width: 1024px) {
  .photo-grid {
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 14px;
  }
}
```

__Ссылка на проект__
https://viktor641.github.io/russian-travel/index.html