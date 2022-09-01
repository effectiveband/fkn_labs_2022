# Лабораторная 4. Добавить локальное хранилище

Лабораторная работа является продолжением [Лабораторной работы 3](./Lab03.md)
<br>
<br>
Необходимо добавить локальное хранилище для списка героев из вселенной **Marvel**

<p align="center">
  <img src="../Images/marvel_offline.gif" width="300">
</p>

## Критерии приемки:

- Используется [Room](https://developer.android.com/training/data-storage/room) для работы с локальной базой данных
- При получении информации о героях используя **GET** запрос _/public/characters_ из [**Marvel Api**](https://developer.marvel.com/docs#!/public/getCreatorCollection_get_0), полученные данные сохраняются в локальное хранилище 
- На главном экране, разработанном в [лабораторной работе 1](./Lab01.md), в случае неуспешной загрузки информации о героях из сети данные отображаются из локального хранилища
- Лабораторная работа должна быть залита на **github** с созданным [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

<br>

## Полезные материалы:

- Рекомендуется пройти codelab [Android Room with a view Kotlin](https://developer.android.com/codelabs/android-room-with-a-view-kotlin#0) и [Android preferences datastore](https://developer.android.com/codelabs/android-preferences-datastore#0) для лучшего освоения материала
