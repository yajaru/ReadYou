English by DeepL | [简体中文](https://github.com/Ashinch/ReadYou/blob/main/README-zh.md)

# Read You

[Telegram](https://t.me/ReadYouApp) | [Figma](https://www.figma.com/file/ViBW8GbUgkTMmK6a80h8X1/Reader-You?node-id=7028%3A23673)

This is a copy of [Reeder](https://reederapp.com/), in order to give Android an RSS reader similar to Reeder.

## Features

**Read You** combines the interaction logic of Reeder with the design style of [Material Design 3 (You)](https://m3.material.io/).

The following are the progress made so far and the goals to be worked on in the near future:

-   [x] Local

    -   [x] Subscribe to Feed Links
    -   [x] Import from OPML
    -   [x] Article Sync
    -   [x] Article Update Notification
    -   [x] Full Content Parsing
    -   [x] Filter unread and starred
    -   [x] Feed Grouping
    -   [x] Localization
    -   [x] Export as OPML
    -   [ ] Search for articles
    -   [ ] Preference settings
    -   [ ] Release APK
    -   [ ] Widget
    -   [ ] ...

-   [ ] Fever API Support
-   [ ] Google Reader API Support
-   [ ] Inoreader API Support
-   [ ] ...

> The above features are only preliminary implementations and there may be unknown issues.

## Build

> If you want to preview the Read You app, you can get the **preview version** of the APK file in [Telegram](https://t.me/ReadYouApp).

**Read You** is implemented on Android's native [Jetpack Compose](https://developer.android.com/jetpack/compose) architecture.

1. First you need to get the source code of **Read You**.

    ```shell
    git clone https://github.com/Ashinch/ReadYou.git
    ```

2. Then open it via [Android Studio (latest version)](https://developer.android.com/studio).

3. When you click the `▶ Run` button, it will be built and run automatically.

    > In case of lag, please select Release version build.

## Credits

-   [MusicYou](https://github.com/Kyant0/MusicYou)
-   [ParseRSS](https://github.com/muhrifqii/ParseRSS): [MIT](https://github.com/muhrifqii/ParseRSS/blob/master/LICENSE)
-   [Readability4J](https://github.com/dankito/Readability4J): [Apache License 2.0](https://github.com/dankito/Readability4J/blob/master/LICENSE)
-   [opml-parser](https://github.com/mdewilde/opml-parser): [Apache License 2.0](https://github.com/mdewilde/opml-parser/blob/master/LICENSE)
-   （To be improved）

## License

[GNU GPL v3.0](https://github.com/Ashinch/ReadYou/blob/main/LICENSE)
