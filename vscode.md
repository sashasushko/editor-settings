## Настройки для VS Code
Чтобы применить настройки, нужно вызвать строку команд `Ctrl + Shift + P`, вписать там _Settings JSON_, в открывшийся файл вставить код:

```js
{
    /* нестандартные шрифты */
    "editor.fontFamily": "'DejaVu Sans Code','DejaVu Sans Mono', monospace",
    /* лигатуры для красоты */
    "editor.fontLigatures": true,
    /* увеличенный интерфейс, чтобы не щуриться */
    "window.zoomLevel": 1,
    /* приятные глазу размер и высота шрифта при указанном масштабе */
    "editor.fontSize": 13,
    "editor.lineHeight": 20,
    "terminal.integrated.fontSize": 13,
    /* ограничитель для наглядности, совпадает --print-width у Prettier */
    "editor.rulers": [100],
    /* чтобы миникарта не занимала место справа */
    "editor.minimap.enabled": false,
    /* чтобы кнопки развернуть/свернуть были всегда */
    "editor.showFoldingControls": "always",
    /* чтобы список открытых файлов не дублировал табы */
    "explorer.openEditors.visible": 0,
    /* чтобы не выскакивали лишние предупреждения */
    "workbench.editor.highlightModifiedTabs": true,
    /* чтобы не выскакивали лишние предупреждения */
    "git.confirmEmptyCommits": false,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false
}
```

В настройках указаны нестандартные шрифты, чтобы работали лигатуры. Поэтому потребутся установить их в систему:
* [DejaVu Sans Mono](https://dejavu-fonts.github.io/)
* [DejaVu Sans Code](https://github.com/SSNikolaevich/DejaVuSansCode)
