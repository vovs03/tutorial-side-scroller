# Этапы(результаты) воркшопа

> 2024-09-19 THU

- [x] запустил билд
- [x] изменил скорость `spaceship.script` движения по OY
- [x] понял, что нет возможности редактировать `*.md` в редакторе Дефолда
- [x] открыл форум [Markdown in the editor](https://forum.defold.com/t/markdown-in-the-editor/33087/2)
- [x] добавил 💚 коммент и свой `+1` к этой заметке `issue #5301` [Create and edit markdown and text files within the Defold editor.](https://github.com/defold/defold/issues/5301)
- [x] заметил, что в выводе на консоли в Дебаг-инфо `INFO:RESOURCE: /spaceship/spaceship.scriptc was successfully reloaded.` ❓ имя файла, указано расширение 🐛 `*.scriptc` а не `*.script`
- не все эмоджи корректно отображаются в дефол-редакторе (`*.md`)

## Увеличение скорости 🚀 корабля

- [x] выполнил хот-релоад  🔥 **Hot-Reload**`<Command>` + `<r>` | `local max_speed = 250` cool!

## Измение получаемых очков за ⭐ звезду

- [x] открыл `spaceship.script` и увеличил значение

```lua
local score = 1000
```

## Добавление бонусных 🌟 звёзд

<!-- 
После выполнения всех шагов, я потом добавил FX для бонус_стар(импровизация была)
-->
