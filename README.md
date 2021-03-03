# video-player

## Видеоплеер для просмотра видео в браузере

Построен на базе библиотеки [Playable](https://wix.github.io/playable/).

![Alt text](screenshot/video-player.png?raw=true "Optional Title")

## Запуск плеера

Скачайте репозиторий и запустите файл `index.html` в браузере.

Пример работы [видео по этой ссылке](https://kostyamorales.github.io/video-player/).

Если хочется выбрать другое видео, с помощью аргумента src плееру можно указать какое видео проигрывать, ссылки обязаны заканчиваться расширением файла:

```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/78/db/78db3456-3fd3-4504-9ed9-d2d1fd843c0b/highest_peak.mp4'
  });
</script>
```


## Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org.](https://dvmn.org/)
