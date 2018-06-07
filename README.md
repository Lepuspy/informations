# informations
BOT向けDiscord&amp;Line通知モジュール
使い方
----------------
pip install requests
```python
from informations import Discord,Line

discord = Discord(url="WebhockURL",name="表示名",icon="アイコンURL")
discord.send("任意のメッセージ")

line = Line("Lineトークン")
line.send("任意のメッセージ")
```
