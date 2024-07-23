## Настройки для VS Code
Чтобы применить настройки, нужно вызвать строку команд `Ctrl + Shift + P`, вписать там _Settings JSON_, в открывшийся файл вставить код:

```js
{
    /* приятная глазу стандартная тема */
    "workbench.colorTheme": "Quiet Light",
    /* нестандартные шрифты */
    "editor.fontFamily": "Monaco, Consolas, monospace",
    "editor.fontLigatures": false,
    /* увеличенный интерфейс, чтобы не щуриться */
    "window.zoomLevel": 1,
    /* приятные глазу размер и высота шрифта при указанном масштабе */
    "editor.fontSize": 15,
    "editor.lineHeight": 21,
    "terminal.integrated.fontSize": 13,
    /* чтобы окно было больше */
    "workbench.layoutControl.enabled": false,
    /* чтобы миникарта не занимала место справа */
    "editor.minimap.enabled": false,
    /* чтобы кнопки развернуть/свернуть были всегда */
    "editor.showFoldingControls": "always",
    /* чтобы список открытых файлов не дублировал табы */
    "explorer.openEditors.visible": 0,
    /* чтобы пустые вложенные директории не схлопывались в боковом меню */
    "explorer.compactFolders": false,
    /* чтобы понимать изменения по быстрому взгляду на вкладку */
    "workbench.editor.highlightModifiedTabs": true,
    /* чтобы не выскакивали лишние предупреждения */
    "git.confirmEmptyCommits": false,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "workbench.startupEditor": "none",
    "extensions.ignoreRecommendations": true,
    "git.confirmSync": false,
    /* чтобы на ноутбуке было удобнее работать */
    "editor.wordWrap": "on",
    "window.commandCenter": false,
    /* чтобы начало строки не прыгало, если скрывать-показывать сайдбар */
    "workbench.sideBar.location": "right",
    /* чтобы при создании файлов выставлялся удобный отступ, если в проекте нет .editorconfig */
    "editor.detectIndentation": true,
    "editor.indentSize": "tabSize",
    "editor.tabSize": 2,
    /* чтобы Копайлот не "воровал" данные */
    "github.copilot.enable": {
        "*": true,
        "plaintext": false,
        "markdown": false,
        "scminput": true,
        "properties": false
    },
    /* чтобы ВС Код не "воровал" данные */
    "telemetry.enableTelemetry": true,
    "telemetry.enableCrashReporter": true,
    "telemetry.telemetryLevel": "off"
}
```
