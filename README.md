# input-method-data

Data files that the Open Infinity pinyin input method downloads on demand. Nothing here is
meant to be downloaded by hand: the app fetches a pinned release asset, checks its size and
SHA-256, and installs it.

Open Infinity 拼音输入法按需下载的数据文件。这里的文件不需要手动下载：软件按固定的发布地址下载，
核对大小和 SHA-256 后安装。

## Releases

| Release | File | Bytes | SHA-256 |
|---|---|---|---|
| `wanxiang-lts-2026-10-26` | `wanxiang-lts-zh-hans.gram` | 418078764 | `e34500ab44626dc039a0641792ecba98ab63307646eb3d29186be56608ffe094` |

### wanxiang-lts-zh-hans.gram

The simplified-Chinese grammar model of Wanxiang (万象拼音) LTS, used by librime's octagram
plugin to score whole-sentence candidates. In the app it is the optional accuracy pack
(增强准确率包). This is an unmodified copy of the asset `wanxiang-lts-zh-hans.gram` in the
`LTS` release of [amzxyz/RIME-LMDG](https://github.com/amzxyz/RIME-LMDG/releases/tag/LTS) as
uploaded there on 2026-10-26; the release is named after that date. The file name must stay as
it is: the input method's schema names the model `wanxiang-lts-zh-hans`, and librime looks for
`<name>.gram`.

万象拼音 LTS 的简体语法模型，librime 的 octagram 插件用它给整句候选打分，在软件里是可选的「增强准确率包」。
文件原样取自 [amzxyz/RIME-LMDG](https://github.com/amzxyz/RIME-LMDG/releases/tag/LTS) 的 `LTS`
发布中 2026-10-26 上传的 `wanxiang-lts-zh-hans.gram`，未作修改，发布按该日期命名。文件名不能改：输入法配置里的模型名是
`wanxiang-lts-zh-hans`，librime 按「模型名.gram」查找。

## Licence

The grammar model is part of the Wanxiang data by amzxyz, licensed under
[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)
(CC BY 4.0); the full text is in [LICENSE](LICENSE). Source:
<https://github.com/amzxyz/RIME-LMDG>. No changes were made.

语法模型属于 amzxyz 的万象数据，按 CC BY 4.0 授权，全文见 [LICENSE](LICENSE)。来源：
<https://github.com/amzxyz/RIME-LMDG>。未作修改。
