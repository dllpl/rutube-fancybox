# Fancybox с Rutube
*Fancybox — это популярный JavaScript-плагин, позволяющий элегантно отображать изображения, видео и другие медиафайлы во всплывающих окнах. Однако, по умолчанию, он не поддерживает RuTube — одну из ведущих видеоплатформ в России, которой сейчас активно пользуются из-за умышленного замедления работы YouTube. В данном репозитории размещен адаптированный Fancybox версии 3.5.7 для поддержки видео с RuTube. Почему именно версия 3.5.7? Это его последняя версия с открытым и не обфусцированным кодом под версией GPLv3.*

## Содержание
1. [Как устроен Fancybox](#как-устроен-fancybox)
2. [Интеграция RuTube в Fancybox](#интеграция-rutube-в-fancybox)
3. [Пример интеграции RuTube в Fancybox](#пример-интеграции-rutube-в-fancybox)
4. [PS](#ps)

## Как устроен Fancybox
Fancybox изначально поддерживает платформы YouTube и Vimeo, предоставляя встроенные инструменты для отображения видео. Однако, чтобы корректно работать с RuTube, требуется адаптировать функционал из-за уникальных особенностей API и плеера этой платформы.
## Интеграция RuTube в Fancybox
Для того чтобы Fancybox корректно отображал видео с RuTube, необходимо внести изменения в его исходный код. Напомню, что для работы Fancybox необходим jQuery >=1.9.0.
Скачать архив с исходными файлами можно по [ссылке](https://github.com/dllpl/rutube-fancybox/archive/refs/tags/3.5.7-rutube.zip)
```
jquery.fancybox.css - исходная версия стилей
jquery.fancybox.js - исходная версия скрипта
jquery.fancybox.min.css - минифицированный версия стилей
jquery.fancybox.min.js - минифицированный версия скрипта
```
## Пример интеграции RuTube в Fancybox
С демонстрацией работоспособности можно ознакомится на соответствующей статье на нашем сайте: [https://webseed.ru/](https://webseed.ru/blog/skachat-fancybox-s-rutube-kak-vstroit-rutube-v-fancybox/)

## PS
Интеграция RuTube в Fancybox требует небольших доработок, но значительно расширяет возможности сайта по показу видео. В текущих условиях такая интеграция будет особенно актуальна.

Ставьте звезды этому репозиторию, если вы считаете, что это было для вас полезно!
