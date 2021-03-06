---
title: Компонент Card React
components: Card, CardActionArea, CardActions, CardContent, CardHeader, CardMedia, Collapse, Paper
---
# Карточки

<p class="description">Карточки содержат контент и действия по одной теме.</p>

[Карточки](https://material.io/design/components/cards.html) - это поверхности, которые отображают контент и действия по одной тематике.

Их должно быть легко сканировать для получения актуальной и выполнимой информации. Элементы, такие как текст и изображения, должны быть расположены на них так, чтобы четко отображать иерархию.

## Простая Карточка

Хотя карточки и могут поддерживать множество действий, таких как элементы управления пользовательского интерфейса и всплывающее меню, будьте сдержаны и помните, что карточки - это входные точки для более сложной и детальной информации.

{{"demo": "pages/demos/cards/SimpleCard.js"}}

## Сложное взаимодействие

На рабочем столе контент карточки может быть расширяемым.

{{"demo": "pages/demos/cards/RecipeReviewCard.js"}}

## Медиа

Пример карточки, использующей изображение для выделения контента.

{{"demo": "pages/demos/cards/MediaCard.js"}}

По умолчанию мы используем комбинацию `<div>` элемента и *background image* для отображения информации. Это может быть проблематично в некоторых ситуациях. Например, вы можете захотеть отобразить видео или адаптивное изображение. Используйте свойство `component` для этих случаев:

{{"demo": "pages/demos/cards/ImgMediaCard.js"}}

## Элементы управления пользовательского интерфейса

Дополнительные действия внутри карточки явно вызываются с помощью иконок, текста и элементов управления пользовательского интерфейса, обычно размещаемых в нижней части карточки.

Вот пример карточки с элементами управления мультимедиа.

{{"demo": "pages/demos/cards/MediaControlCard.js"}}