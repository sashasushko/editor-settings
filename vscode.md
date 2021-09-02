## Настройки для VS Code
Чтобы применить настройки, нужно вызвать строку команд `Ctrl + Shift + P`, вписать там _Settings JSON_, в открывшийся файл вставить код:

```js
{
    /* приятная глазу стандартная тема */
    "workbench.colorTheme": "Solarized Light",
    /* нестандартные шрифты */
    "editor.fontFamily": "Monaco, Consolas, monospace",
    "editor.fontLigatures": false,
    /* увеличенный интерфейс, чтобы не щуриться */
    "window.zoomLevel": 1,
    /* приятные глазу размер и высота шрифта при указанном масштабе */
    "editor.fontSize": 15,
    "editor.lineHeight": 21,
    "terminal.integrated.fontSize": 13,
    /* ограничитель для наглядности, совпадает --print-width у Prettier */
    "editor.rulers": [100],
    /* чтобы миникарта не занимала место справа */
    "editor.minimap.enabled": false,
    /* чтобы кнопки развернуть/свернуть были всегда */
    "editor.showFoldingControls": "always",
    /* чтобы список открытых файлов не дублировал табы */
    "explorer.openEditors.visible": 0,
    /* чтобы понимать изменения по быстрому взгляду на вкладку */
    "workbench.editor.highlightModifiedTabs": true,
    /* чтобы не выскакивали лишние предупреждения */
    "git.confirmEmptyCommits": false,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "workbench.startupEditor": "newUntitledFile"
}
```
