# RUSSIAN TRAVEL

 **Russian travel** - это мой второй проект, который я писал на основе обучения в **[Яндекс.Практикуме](https://practicum.yandex.ru/)**.

Этот проект имеет несколько целей:
  + _Научиться работать с приложением Figma_
  + _Научиться адаптивной вёрсткой_
  + _Изучение расширенных возможностей GIT_

____

## Technologies

В этом проекте вы можете встретить несколько интересных технологий, которые я использовал для осуществления проекта.

### @meadia
```css
@media screen and (max-width: 1024px) {
  .cover {
    width: 100%;
    min-height: 640px;
    margin: 0 0 92px;
  }
}

@media screen and (max-width: 768px) {
  .cover {
    width: 100%;
    min-height: 480px;
    margin: 0 0 88px;
  }
}

@media screen and (max-width: 320px) {
  .cover {
    width: 100%;
    min-height: 200px;
    margin: 0 0 97px;
  }
}
```

### Display: grid;
```css
.photo-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(3, 1fr);
  margin: 0 auto 92px;
  max-width: 1184px;
  gap: 16px 16px;
}
```

## Info

Язык страницы - русский ```lang="ru"```.

Кодировка документа - ```charset="UTF-8"```.

Ссылка на сайт - https://t1tpain.github.io/russian-travel/