# Лабораторная 4. Добавить локальное хранилище

Лабораторная работа является продолжением [Лабораторной работы 3](./Lab03.md)
<br>
<br>
Необходимо добавить локальное хранилище для списка героев из вселенной **Marvel**

## При выполнении лабораторной работы рекомендуется использовать:

- Сохранение данных и изображений в виде файлов в памяти устройства

**или**

- Использовать библиотеку [Moor](https://pub.dev/packages/moor_flutter) для создания sqlite db

<p align="center">
  <img src="../Images/marvel_offline.gif" width="300">
</p>

## Критерии приемки:

- При успешном получении информации о героях используя **GET** запрос _/public/characters_ из [**Marvel Api**](https://developer.marvel.com/docs#!/public/getCreatorCollection_get_0) полученные данные сохраняются в локальное хранилище
- На главном экране, разработанном в [лабораторной работе 1](./Lab01.md), в случае неуспешной загрузки информации о героях из сети данные отображаются из локального хранилища, если имеются
- Лабораторная работа должна быть залита на **github** с созданным [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

<br>

## Полезные материалы:

- Ознакомьтесь с [записью/чтением](https://flutter.dev/docs/cookbook/persistence/reading-writing-files) из файловой системы во flutter
- Ознакомьтесь со [статьей](https://objectbox.io/flutter-databases-sqflite-hive-objectbox-and-moor/) с обзором вариантов хранения данных во flutter
