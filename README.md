# Personal Squirrel Config

[Squirrel](https://github.com/rime/squirrel) is the MacOS version of [Rime](https://rime.im/) input method engline.

The Config is based on [Rime 鼠须管输入法傻瓜式配置指南](https://github.com/wongdean/rime-settings) 

Good-to-know:
- `*.dict.yaml` are generally third party dictionaries.
- `⌃` + `` ` `` to switch CH/ENG or simplified/traditional Chinese.
- After making changes to the yaml config files, don't forget to click `deploy` to let the changes take immediate effect.

Changes:
- Enable dark mode for MacOS. Add `color_scheme_dark: mojave_dark` to `squirrel.custom.yaml` > `style:`. 
- Only use squirrel as the Chinese input source, i.e. using native macOS keyboard as latin input source. （因为我觉得自动切换到英文，除了raycast以外，都比较无语，我懂得看右上角图标，而且没必要用squirrel当英文输入法）
  - Disable `⇧` as a switch key for last used latin input source.
  - Disable default Latin input for certain apps. Toggle comments for all `app_options` entries in `squirrel.custom.yaml`.