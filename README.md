# KU休講情報Bot
京都大学の休講情報をTwitterに呟くBotです。(@KUBotver2)

以前から同じ名前のTwitterアカウント(@ku_kyukou_bot)が存在していましたが、運営の方が卒業され止まったままだったので、
その機能を引き継ぎました。


# 使い方
1. account.jsonとtwtter_account.jsonを作成します。
- account.json : ecs-id とパスワード
- twwiter_account.json : twitter apiで使用する4つの鍵

2. "python main.py n"で起動します。
- n : n限目-5限目までの情報をつぶやきます。6を指定した場合は明日の情報を1限目-5限目までつぶやきます。