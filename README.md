# fabrishotUnofficial

Неофициальные порты [Fabrishot](https://github.com/ramidzkh/fabrishot) для Minecraft **26.2** и **26.3**.

- Отображаемое имя мода: `fabrishotUnofficial`
- Автор в метаданных: `Kwizeek`
- Внутренний Fabric ID сохранён как `fabrishot` для совместимости
- Лицензия: MIT; исходная лицензия сохранена в `LICENSE`

## Готовые файлы

- `fabrishotUnofficial-1.17.0-mc26.2.jar`
- `fabrishotUnofficial-1.17.0-mc26.3.jar`

## Исходники

Полные проекты находятся в отдельных каталогах:

- `ports/mc26.2/`
- `ports/mc26.3/`

## Сборка

Требуется **JDK 25**.

```bash
cd ports/mc26.2
FABRISHOT_VERSION=1.17.0+26.2 ./gradlew build
```

```bash
cd ports/mc26.3
FABRISHOT_VERSION=1.17.0+26.3 ./gradlew build
```
