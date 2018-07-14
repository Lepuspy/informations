# informations
BOT向けDiscord&amp;Line通知モジュール
使い方
----------------
pip install requests
```python
from informations import Discord,Line

discord = Discord(url="WebhockURL",name="表示名",icon="アイコンURL")
discord.send("任意のメッセージ")
discord.send("これは画像テストです","test.png")

line = Line("Lineトークン")
line.send("任意のメッセージ")
line.send("画像テスト","test.png")
```
