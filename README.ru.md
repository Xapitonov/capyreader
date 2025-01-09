# Capy Reader

<img src="./site/capy.png" width="100px">

_Небольшая RSS-читалка с поддержкой Feedbin, FreshRSS и локальных лент._

![Тесты](https://github.com/jocmp/capyreader/actions/workflows/ci.yml/badge.svg) <a href="https://hosted.weblate.org/engage/capy-reader/">
 <img src="https://hosted.weblate.org/widget/capy-reader/strings/svg-badge.svg" alt="Состояние перевода" />
</a>

## Скачивание

- [Google Play][gplay_link]
- [F-Droid][fdroid_link]
- [IzzyOnDroid][izzy_link]
- [GitHub Releases][github_link]

Capy Reader бесплатен на всех источниках. Он доступен для устройств с Android 11 или выше.

### Выпуски

Выпуски в Google Play происходят каждую неделю в зависимости от новых функций, исправлений ошибок и переводов.

Выпуски на GitHub помечены суффиксом "-dev" и происходят чаще. Они всегда стабильны, протестированы.

## Сообщение об ошибке

Сообщения об ошибках всегда приветствуются и являются моим главным приоритетом.

Если вы столкнулись с проблемой, дайте мне знать, подав [сообщение об ошибке](https://github.com/jocmp/capyreader/issues/new?labels=bug&template=1-bug-report.yml).

## Запросы на функции

Если у вас есть вопросы или общий запрос на функцию, пожалуйста, опубликуйте их в [Обсуждениях](https://github.com/jocmp/capyreader/discussions).

### Поддержка полного содержания

Иногда режим полного содержимого в Capy не работает так, как ожидалось, из-за хаоса на сайте.

Если это произойдет, пожалуйста, отправьте отдельный заявку на добавление поддержки полного содержимого для этого сайта.: [Форма заявки на получение полного содержимого](https://github.com/jocmp/capyreader/issues/new?labels=full%20content%20request&template=2-full-content-request.yml)

## Дорожная карта

Ознакомьтесь с [дорожной картой проекта](https://github.com/users/jocmp/projects/3), чтобы увидеть, что сейчас в процессе и что запланировано.

## Переводы

Переводы размещены на [Weblate](https://hosted.weblate.org/projects/capy-reader). Не стесняйтесь добавлять или обновлять переводы.

Если вы не видите своего языка, пожалуйста, [подайте заявку](https://github.com/jocmp/capyreader/discussions) в обсуждениях.

## Сборка приложения

### Начинаем

1. Клонируйте этот репозиторий
2. Установите [Android Studio](https://developer.android.com/studio), если у вас её ещё нет
3. Синхронизируйте Gradle
4. В панели инструментов выберите **_Выполнить_** > **_Запустить_** *'приложение'*

#### Сборка с подписью релиза (необязательно)

По умолчанию приложение будет собрано с отладочным хранилищем ключей. Следуйте инструкциям ниже, чтобы собрать подписанный релиз.

1. Убедитесь, что у вас есть хранилище ключей с именем `release.keystore` в корневом каталоге.
2. Затем создайте файл с именем `secrets.properties`, также в корневом каталоге, со следующими значениями

    ```properties
    key_alias=
    store_password=
    key_password=
    ```


[gplay_link]: https://play.google.com/store/apps/details?id=com.capyreader.app
[fdroid_link]: https://f-droid.org/packages/com.capyreader.app/
[izzy_link]: https://apt.izzysoft.de/fdroid/index/apk/com.capyreader.app
[izzy_img]: https://img.shields.io/endpoint?url=https://apt.izzysoft.de/fdroid/api/v1/shield/com.capyreader.app&label=IzzyOnDroid
[github_link]: https://github.com/jocmp/capyreader/releases/latest
[github_img]: https://img.shields.io/github/v/release/jocmp/capyreader?logo=GitHub
