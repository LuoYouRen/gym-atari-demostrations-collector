**Status:** Archive (code is provided as-is, no updates expected)

this repository is clone from https://github.com/openai/atari-demo

# atari-demo
Record demonstrations for atari.
Collect observations and actions by human playing. 

Use as `pythonw record_demo.py --game='MontezumaRevenge'`

Requires gym[atari]  (`pip install --no-index -f https://github.com/Kojoley/atari-py/releases atari_py`) for windows

Requires pygame  (`pip install pygame`) 

**key for playing:**

大部分遊戲以方向鍵與空白鍵遊玩

press b: 回溯

press s: 儲存目前的遊玩進度並且將demonstrations存成 .bin檔 

(注意：若遊戲已結束則遊玩進度將會被刪除)

有任何需要增加的功能與更好的實作方式請與我討論
