# AMLL TTML Database

> [!Important]
>
> This lyric database is for **Chinese language only**!
> If you wish to upload your lyrics, please keep lyric translation line blank and only include original lyric line and transliteration line. Thank you!

作者特供给 [AMLL](https://github.com/Steve-xmh/applemusic-like-lyrics) 的 TTML 逐词歌词库，也欢迎大家前来建设本仓库！

如果需要制作逐词歌词，可以使用 [AMLL TTML Tool](https://github.com/Steve-xmh/amll-ttml-tool) 哦！

## 和原本主歌词库的区别

本仓库下的歌词不需要经过人工审核，在机器人基本确认没有格式上的问题后即会被自动提交到仓库中。

但是也因此，本仓库有可能会产生以下内容：

- 出错的歌词内容
- 不符合法律法规的内容
- 时间轴出错的歌词
- ...等任意失去人工审核导致的内容问题

使用本用户歌词库时，还请注意以上情况。

## 使用歌词数据库

> [!TIP]
> 虽然这并非强制，但我们希望你在使用本歌词数据库时，能够在你的项目中加入一个指向本仓库或者衍生项目的链接或说明，或是展示每个歌词文件中的歌词作者信息（均已在元数据中可以读取），以便更多人能够发现这个数据库，一同建设本歌词数据库。

如果你想要接入本歌词数据库，可以通过各类以平台类型区分的文件夹，用您对应平台的音乐 ID 来获取歌词文件。

现阶段支持以下平台的歌词索引：

- [Netease Cloud Music - 网易云音乐](./ncm-lyrics) 
- [QQ Music - QQ 音乐](./qq-lyrics)
- [Apple Music](./apple-lyrics)
- [Spotify](./spotify-lyrics)

每个歌词 ID 均已自动生成不同格式的歌词文件，通过文件后缀名区分：

- `.ttml`: 原 TTML 歌词格式
- `.lrc`: LyRiC 歌词格式
- `.yrc`: 网易云音乐逐词歌词格式
- `.qrc`: QQ 音乐逐词歌词格式
- `.lys`: Lyricify Syllable 逐词歌词格式
- `.eslrc`: ESLrc 逐词歌词格式

如果需要检索从建立数据库开始至今所有的歌词文件，可以访问 [./raw-lyrics](./raw-lyrics) 文件夹，内部的文件以 `[提交UNIX时间戳]-[提交者GithubID]-[8位随机ID].ttml` 命名。

同时，在每个平台文件夹下，还有一个存有基本信息的 `index.jsonl` 逐行存储了该平台下所属的所有歌词基本信息，以原始歌词文件顺序排列，也列出了所有历史歌词信息。

## 共享协议

本仓库的外来数据部分遵循原数据提供方的共享协议共享，提交者自主编写的部分使用 CC0 1.0 共享协议共享。

## 鸣谢

感谢所有为建设本仓库提供歌词的贡献者们！

[![贡献者头像画廊，点击可查阅](https://amll-ttml-db.stevexmh.net/contributors.png)](./CONTRIBUTORS.md)
