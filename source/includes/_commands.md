## body

```plaintext
/body
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Body](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Body.java)

手に持っているアイテムを背中に付けます。

### `/body`

手に持っているアイテムを背中に付けます。

## boots

```plaintext
/boots
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Boots](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Boots.java)

手に持っているアイテムを足に付けます。

### `/boots`

手に持っているアイテムを足に付けます。

## brb

```plaintext
/brb
/brb <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Brb](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Brb.java)

バリアブロックを入手します。

### `/brb`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

バリアブロックをコマンド実行者のメインハンドのアイテムと置き換えます。

### `/brb <player>`

バリアブロックを指定したプレイヤーのメインハンドのアイテムと置き換えます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | Player | はい | バリアブロックを付与するプレイヤー名 |

## bug

```plaintext
/bug
/bug true
/bug false
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Bug](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Bug.java)

本によるIssueの作成を行います。

### `/bug`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

本によるIssueの作成を行います。

### `/bug true`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

本によりIssue作成処理を行います。

### `/bug false`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

記入済みの本を記入可能な本に戻します。

## calctree

```plaintext
/calctree [placeEdgeTree]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Calctree](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Calctree.java)

WorldEditの選択範囲で植木算を行います。

### `/calctree [placeEdgeTree]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

WorldEditの選択範囲で植木算を行います。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `placeEdgeTree` | Boolean | いいえ | 両端に木を置くかどうか。 |

## chat

```plaintext
/chat <player> <message>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Chat](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Chat.java)

偽のプレイヤーに喋らせます。

### `/chat <player> <message>`

偽のプレイヤーに喋らせます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | String | はい | 喋らせるプレイヤー名 |
| `message` | String | はい | 喋らせるメッセージ |

## chatban

```plaintext
/chatban add <player> <reason>
/chatban remove <player>
/chatban status [player]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_ChatBan](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_ChatBan.java)

ChatBanに関する処理を行います。

### `/chatban add <player> <reason>`

ターゲットをChatBanします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | はい | 対象のプレイヤー |
| `reason` | String | はい | 理由 |

### `/chatban remove <player>`

ターゲットのChatBanを解除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | はい | 対象のプレイヤー |

### `/chatban status [player]`

ChatBan一覧もしくは詳細を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | いいえ | 詳細を表示するプレイヤー |

## cmdb

```plaintext
/cmdb
/cmdb <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Cmdb](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Cmdb.java)

コマンドブロックを入手します。

### `/cmdb`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

コマンドブロックをコマンド実行者のメインハンドのアイテムと置き換えます。

### `/cmdb <player>`

コマンドブロックを指定したプレイヤーのメインハンドのアイテムと置き換えます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | Player | はい | コマンドブロックを付与するプレイヤー名 |

## debstick

```plaintext
/debstick
/debstick <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Debstick](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Debstick.java)

デバッグステイックを入手します。

### `/debstick`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

デバッグステイックをコマンド実行者のメインハンドのアイテムと置き換えます。

### `/debstick <player>`

デバッグステイックを指定したプレイヤーのメインハンドのアイテムと置き換えます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | Player | はい | デバッグスティックを付与するプレイヤー |

## ded

```plaintext
/ded
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Ded](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Ded.java)

最後に死亡した場所にテレポートします。

### `/ded`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

最後に死亡した場所にテレポートします。

## dedbull

```plaintext
/dedbull
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Dedbull](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Dedbull.java)

プレイヤーに暗視効果を付与します。すでに付与されている場合は削除します。

### `/dedbull`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

プレイヤーに暗視効果を付与します。すでに付与されている場合は削除します。

## dedmessage

```plaintext
/dedmessage
/dedmessage register <message>
/dedmessage disable
/dedmessage remove <id>
/dedmessage list [page]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_DedMessage](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_DedMessage.java)

カスタム死亡メッセージを設定します。

### `/dedmessage`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

今いる場所にカスタム死亡メッセージが設定されているかどうかを調べます。

### `/dedmessage register <message>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

カスタム死亡メッセージを登録します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `message` | String | はい | カスタム死亡メッセージ（%player% はプレイヤー名、%killer% はキルした人の名前に置き換わります） |

### `/dedmessage disable`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

死亡メッセージ表示を無効化します。

### `/dedmessage remove <id>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

カスタム死亡メッセージを削除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `id` | Integer | はい | カスタム死亡メッセージID |

### `/dedmessage list [page]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

カスタム死亡メッセージの一覧を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `page` | Integer | いいえ | カスタム死亡メッセージID |

## delhome

```plaintext
/delhome
/delhome [name]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_DelHome](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_DelHome.java)

ホームを削除します。

- エイリアスがあります: `removehome, remhome`

### `/delhome`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

デフォルトホームを削除します。

### `/delhome [name]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定された名前のホームを削除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `name` | String | いいえ | ホーム名 |

## discordlink

```plaintext
/discordlink <authKey>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_DiscordLink](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_DiscordLink.java)

DiscordアカウントとMinecraftアカウントを紐づけます。

### `/discordlink <authKey>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

DiscordアカウントとMinecraftアカウントを紐づけます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `authKey` | String | はい | 認証コード |

## dt

```plaintext
/dt <markerName>
/dt tp <targets> <markerName>
/dt add <markerName> <markerType> [markerIcon]
/dt del <markerName>
/dt random
/dt near
/dt neartp
/dt list [page]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_DT](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_DT.java)

DynmapのMarkerを編集・テレポートします。

### `/dt <markerName>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

マーカーにテレポートさせます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `markerName` | String | はい | マーカー名 |

### `/dt tp <targets> <markerName>`

エンティティをマーカーにテレポートさせます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `targets` | MultipleEntitySelector | はい | エンティティ対象セレクター |
| `markerName` | String | はい | マーカー名 |

### `/dt add <markerName> <markerType> [markerIcon]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

マーカーを追加します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `markerName` | String | はい | マーカー名 |
| `markerType` | String | はい | マーカー種別 |
| `markerIcon` | String | いいえ | マーカーアイコン |

### `/dt del <markerName>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

マーカーを削除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `markerName` | String | はい | マーカー名 |

### `/dt random`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ランダムに選ばれたマーカーにテレポートします。

### `/dt near`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

近くのマーカーを表示します。

### `/dt neartp`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

近くのマーカーにテレポートします。

### `/dt list [page]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

マーカーの一覧を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `page` | Integer | いいえ | ページ |

## eban

```plaintext
/eban add <player> <reason>
/eban remove <player>
/eban status [player]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_EBan](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_EBan.java)

EBanに関する処理を行います。

### `/eban add <player> <reason>`

ターゲットをEBanします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | はい | 対象のプレイヤー |
| `reason` | String | はい | 理由 |

### `/eban remove <player>`

ターゲットのEBanを解除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | はい | 対象のプレイヤー |

### `/eban status [player]`

EBan一覧を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | いいえ | 説明なし |

## elytra

```plaintext
/elytra
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Elytra](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Elytra.java)

プレイヤーにエリトラと花火を付与します。

### `/elytra`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

プレイヤーにエリトラと花火を付与します。

## flyspeed

```plaintext
/flyspeed [target]
/flyspeed set <percent>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_FlySpeed](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_FlySpeed.java)

クリエイティブ飛行速度を変更します。

### `/flyspeed [target]`

指定したプレイヤーのクリエイティブ飛行速度を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | Player | いいえ | ターゲットプレイヤー |

### `/flyspeed set <percent>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

クリエイティブ飛行速度を設定します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `percent` | Float | はい | クリエイティブ飛行速度(通常100%) |

## g

```plaintext
/g
/g <gamemode>
/g <gamemode> <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_G](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_G.java)

ゲームモードを変更します。

- エイリアスがあります: `gm`

### `/g`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ゲームモードを切り替えます。

### `/g <gamemode>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定されたゲームモードに切り替えます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `gamemode` | String | はい | ゲームモード |

### `/g <gamemode> <player>`

指定されたプレイヤーのゲームモードを切り替えます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `gamemode` | String | はい | 説明なし |
| `player` | Player | はい | ゲームモード |

## getlookloc

```plaintext
/getlookloc
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Getlookloc](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Getlookloc.java)

見ているブロックの座標を提案します。

### `/getlookloc`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

見ているブロックの座標を提案します。

## getuserkey

```plaintext
/getuserkey
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_GetUserKey](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_GetUserKey.java)

ユーザーを認証するためのキー(ユーザーキー)に関する操作を行います。

### `/getuserkey`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ユーザーキーを生成し、表示します。

## glookup

```plaintext
/glookup <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Glookup](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Glookup.java)

他人のゲームモードを確認します。

### `/glookup <player>`

他人のゲームモードを確認します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | Player | はい | プレイヤー名 |

## hat

```plaintext
/hat
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Hat](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Hat.java)

手に持っているアイテムを頭に載せます。

### `/hat`

手に持っているアイテムを頭に載せます。

## head

```plaintext
/head
/head <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Head](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Head.java)

頭ブロックを入手します。

### `/head`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

自分の頭ブロックを入手します。

### `/head <player>`

指定したプレイヤーの頭ブロックを入手します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | はい | 対象のプレイヤー |

## help

```plaintext
/help [params]
/help register
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Help](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Help.java)

ヘルプブックを取得・登録します。

- エイリアスがあります: `?`

### `/help [params]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ヘルプブックを取得します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `params` | String | いいえ | ヘルプパラメーター |

### `/help register`

ヘルプブックを登録します。

## hide

```plaintext
/hide
/hide <target>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Hide](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Hide.java)

他のプレイヤーから姿を隠します。

### `/hide`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

他のプレイヤーから姿を隠します。

### `/hide <target>`

指定したプレイヤーを他のプレイヤーから姿を隠します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | Player | はい | 対象のプレイヤー |

## history

```plaintext
/history add <target> <message>
/history disable <target> <item>
/history notify <target> <item> <changeTo>
/history status <target>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_History](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_History.java)

jaoHistoryに関する操作を行います。

### `/history add <target> <message>`

指定したプレイヤーのjaoHistoryにデータを追加します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | OfflinePlayer | はい | 対象のプレイヤー |
| `message` | String | はい | メッセージ |

### `/history disable <target> <item>`

指定したプレイヤーのjaoHistory項目を無効化します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | OfflinePlayer | はい | 対象のプレイヤー |
| `item` | Integer | はい | jaoHistoryId |

### `/history notify <target> <item> <changeTo>`

指定したプレイヤーのjaoHistory項目の通知設定を行います。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | OfflinePlayer | はい | 対象のプレイヤー |
| `item` | Integer | はい | jaoHistoryId |
| `changeTo` | Boolean | はい | 変更後の通知設定 |

### `/history status <target>`

指定したプレイヤーのjaoHistory情報を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | OfflinePlayer | はい | 説明なし |

## home

```plaintext
/home
/home [name]
/home list [Page]
/home view [name]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Home](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Home.java)

ホームにテレポートします。

### `/home`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

デフォルトホームにテレポートします。

### `/home [name]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定された名前のホームにテレポートします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `name` | String | いいえ | ページ |

### `/home list [Page]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ホーム一覧を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `Page` | Integer | いいえ | ページ |

### `/home view [name]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定したホームに関する情報を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `name` | String | いいえ | ページ |

## invedit

```plaintext
/invedit <target>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_InvEdit](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_InvEdit.java)

プレイヤーのインベントリを編集します。

### `/invedit <target>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定したプレイヤーのインベントリを編集します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | Player | はい | 対象のプレイヤー |

## invload

```plaintext
/invload <target> [saveName] [player]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_InvLoad](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_InvLoad.java)

プレイヤーのインベントリを復元します。

### `/invload <target> [saveName] [player]`

指定したプレイヤーにおける指定した名前のインベントリを復元します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | SinglePlayerSelector | はい | インベントリを保存したプレイヤー |
| `saveName` | String | いいえ | 保存名 |
| `player` | SinglePlayerSelector | いいえ | 復元先のプレイヤー |

## invsave

```plaintext
/invsave <target> [saveName]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_InvSave](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_InvSave.java)

プレイヤーのインベントリを保存します。

### `/invsave <target> [saveName]`

指定したプレイヤーのインベントリを指定した名前で保存します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | SinglePlayerSelector | はい | インベントリを保存するプレイヤー |
| `saveName` | String | いいえ | 保存名 |

## invshow

```plaintext
/invshow <target>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_InvShow](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_InvShow.java)

プレイヤーのインベントリを閲覧します。

### `/invshow <target>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定したプレイヤーのインベントリを閲覧します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | Player | はい | 対象のプレイヤー |

## jail

```plaintext
/jail add <player> <reason>
/jail remove <player>
/jail status [player]
/jail testment <message>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Jail](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Jail.java)

Jailに関する処理を行います。

### `/jail add <player> <reason>`

ターゲットをJailします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | はい | 対象のプレイヤー |
| `reason` | String | はい | 説明なし |

### `/jail remove <player>`

ターゲットのJailを解除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | はい | 対象のプレイヤー |

### `/jail status [player]`

Jail一覧を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | OfflinePlayer | いいえ | 詳細を表示するプレイヤー |

### `/jail testment <message>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

遺言を記録します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `message` | String | はい | 遺言 |

## lead

```plaintext
/lead set [target]
/lead connect <from> <to>
/lead leave [target]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Lead](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Lead.java)

Mob（またはプレイヤー）にリードを付けます。

### `/lead set [target]`

1辺30ブロックの立方体内にある指定されたターゲットセレクターの[Mob]にリードを付けます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | SingleEntitySelector | いいえ | 対象のMob。指定しない場合見ているMob |

### `/lead connect <from> <to>`

[Mob（またはプレイヤー）]から、[Mob]にリードを付けます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `from` | SingleEntitySelector | はい | リードを持っている側のMob（またはプレイヤー） |
| `to` | SingleEntitySelector | はい | リードを付けられる側のMob |

### `/lead leave [target]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

[Mob（または実行者）]が付けられているか、持っているリードを外します。両方の場合は付けられているリードを優先します

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | SingleEntitySelector | いいえ | 対象のMob（または実行者）。対象を指定しない場合見ているMob、何も見ていない場合実行者 |

## legs

```plaintext
/legs
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Legs](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Legs.java)

手に持っているアイテムを背中に付けます。

### `/legs`

手に持っているアイテムを足首に付けます。

## link

```plaintext
/link
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Link](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Link.java)

linkコマンドはjMS Gamers Clubで実行するのだ。

### `/link`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

linkコマンドはjMS Gamers Clubで実行するのだ。

## logintext

```plaintext
/logintext
/logintext <loginText>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_LoginText](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_LoginText.java)

ログイン時に表示されるテキストに任意のテキストを追加します。

### `/logintext`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ログイン時に表示されるテキストをリセットします。

### `/logintext <loginText>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ログイン時に表示されるテキストに任意のテキストを追加します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `loginText` | String | はい | 変更後のログインテキスト |

## looking

```plaintext
/looking
/looking on <target>
/looking off
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Looking](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Looking.java)

プレイヤーを見続けます。

- エイリアスがあります: `eye, see, look`

### `/looking`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

今見ているプレイヤーを見続けはじめます。

### `/looking on <target>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

プレイヤーを見続けはじめます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | Player | はい | 見続けるプレイヤー |

### `/looking off`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

プレイヤーを見続けるのをやめます。

## makecmd

```plaintext
/makecmd
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_MakeCmd](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_MakeCmd.java)

giveコマンドを生成します。

- エイリアスがあります: `givecmd`

### `/makecmd`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

giveコマンドを生成します。

## mymaid4

```plaintext
/mymaid4 reload-blacklist
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_MyMaid4](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_MyMaid4.java)

MyMaid4基本コマンド

### `/mymaid4 reload-blacklist`

MyMaid4基本コマンド

## pigeon

```plaintext
/pigeon speaker add <speaker>
/pigeon messages add <message>
/pigeon speaker remove [speaker]
/pigeon messages remove [message]
/pigeon speaker list
/pigeon messages list
/pigeon broadcast [messageId]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Pigeon](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Pigeon.java)

伝書鳩ちゃんにお願いを伝えます。

- エイリアスがあります: `messenger`

### `/pigeon speaker add <speaker>`

伝書鳩ちゃんにスピーカーを追加してもらいます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `speaker` | String | はい | スピーカー名 |

### `/pigeon messages add <message>`

伝書鳩ちゃんにメッセージを追加してもらいます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `message` | String | はい | メッセージ内容 |

### `/pigeon speaker remove [speaker]`

伝書鳩ちゃんにスピーカーを削除してもらいます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `speaker` | String | いいえ | スピーカー名もしくはID |

### `/pigeon messages remove [message]`

伝書鳩ちゃんにメッセージを削除してもらいます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `message` | String | いいえ | メッセージ内容 |

### `/pigeon speaker list`

伝書鳩ちゃんにスピーカーが誰がいるか聞きます。

### `/pigeon messages list`

伝書鳩ちゃんにメッセージが何があるか聞きます。

### `/pigeon broadcast [messageId]`

伝書鳩ちゃんにメッセージを配信してもらいます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `messageId` | Integer | いいえ | メッセージID |

## player

```plaintext
/player
/player <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Player](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Player.java)

プレイヤーの権限グループを取得します。

- エイリアスがあります: `group`

### `/player`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

あなたの権限グループを表示します。

### `/player <player>`

指定されたプレイヤーの権限グループを表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | String | はい | 対象のプレイヤー |

## respawn

```plaintext
/respawn <player>
/respawn <player> <delay>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Respawn](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Respawn.java)

プレイヤーをリスポーンします。

### `/respawn <player>`

指定したプレイヤーをリスポーンします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | Player | はい | リスポーンさせるプレイヤー |

### `/respawn <player> <delay>`

指定した秒数後にプレイヤーをリスポーンします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | Player | はい | リスポーンさせるプレイヤー |
| `delay` | Long | はい | 遅延させる秒数 |

## rider

```plaintext
/rider [target]
/rider ride <from> <to>
/rider leave [target]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Rider](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Rider.java)

プレイヤーやエンティティに乗ったり下ろしたりします。

### `/rider [target]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

プレイヤー・エンティティに乗ります。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | SingleEntitySelector | いいえ | 対象のプレイヤー・エンティティ。指定しない場合見ているプレイヤー |

### `/rider ride <from> <to>`

プレイヤー・エンティティをプレイヤー・エンティティに乗せます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `from` | SingleEntitySelector | はい | 乗せるプレイヤー・エンティティ |
| `to` | SingleEntitySelector | はい | 乗せられるプレイヤー・エンティティ |

### `/rider leave [target]`

乗っているプレイヤー・エンティティを下ろします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | SingleEntitySelector | いいえ | 対象のプレイヤー・エンティティ。指定しない場合実行者 |

## secrettp

```plaintext
/secrettp <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_SecretTP](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_SecretTP.java)

スペクテイターでテレポートします。

### `/secrettp <player>`

スペクテイターで特定のプレイヤーにテレポートします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `player` | Player | はい | テレポートするプレイヤー名 |

## selclick

```plaintext
/selclick
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Selclick](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Selclick.java)

SelClickの有効/無効を切り替えます。

### `/selclick`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

SelClickの有効/無効を切り替えます。

## sethome

```plaintext
/sethome
/sethome [name]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_SetHome](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_SetHome.java)

ホームを設定します。

- エイリアスがあります: `addhome`

### `/sethome`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

デフォルトホームを設定します。

### `/sethome [name]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定された名前のホームを設定します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `name` | String | いいえ | ホーム名。指定しない場合default |

## show

```plaintext
/show
/show <target>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Show](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Show.java)

姿を見えるようにします。

### `/show`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

姿を見えるようにします。

### `/show <target>`

指定したプレイヤーの姿を見えるようにします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | Player | はい | 対象のプレイヤー |

## sign

```plaintext
/sign editmode [changeTo]
/sign set <line> <text>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Sign](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Sign.java)

看板を編集します。

### `/sign editmode [changeTo]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

看板編集モードをオン・オフします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `changeTo` | Boolean | いいえ | オン・オフのいずれか (未指定の場合トグル) |

### `/sign set <line> <text>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

看板の指定行のテキストを置き換えします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `line` | Integer | はい | 編集する行 |
| `text` | String | はい | 置き換えるテキスト |

## skkcolor

```plaintext
/skkcolor
/skkcolor <color>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_SKKColor](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_SKKColor.java)

チャット欄に表示される四角の色を変更します。

### `/skkcolor`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

チャット欄に表示される四角の色をリセットします。

### `/skkcolor <color>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

チャット欄に表示される四角の色を変更します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `color` | String | はい | 変更後の四角色 |

## spawn

```plaintext
/spawn
/spawn true
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Spawn](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Spawn.java)

スポーン地点にテレポートします。

### `/spawn`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

ワールドのスポーン地点にテレポートします。

### `/spawn true`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

あなたのスポーン地点にテレポートします。

## tempmute

```plaintext
/tempmute [changeTo]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_TempMute](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_TempMute.java)

一時的なミュートを実施します。運営のみ使用できます。

### `/tempmute [changeTo]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

TempMuteをオン・オフします。指定しない場合、トグルで変更します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `changeTo` | Boolean | いいえ | オン・オフのいずれか (未指定の場合トグル) |

## test

```plaintext
/test version
/test database
/test nbt
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Test](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Test.java)

MyMaidテストコマンド

### `/test version`

MyMaidテストコマンド

### `/test database`

MyMaidテストコマンド

### `/test nbt`

MyMaidテストコマンド

## testment

```plaintext
/testment <message>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Testment](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Testment.java)

Jailの遺言を残します。jail testmentのエイリアスです。

### `/testment <message>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

遺言を記録します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `message` | String | はい | 説明なし |

## time

```plaintext
/time set <timeName> [isRelative]
/time add <timeInt> [isRelative]
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Time](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Time.java)

自分だけに適用される時間を設定します。

### `/time set <timeName> [isRelative]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

自分だけに適用される時間を設定します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `timeName` | String | はい | 時間の名前 |
| `isRelative` | Boolean | いいえ | ワールド時間と相対的に保つか |

### `/time add <timeInt> [isRelative]`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

自分だけに適用される時間を進めます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `timeInt` | Integer | はい | 時間 |
| `isRelative` | Boolean | いいえ | ワールド時間と相対的に保つか |

## tpalias

```plaintext
/tpalias set <target> <replacement>
/tpalias remove <target>
/tpalias list
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_TpAlias](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_TpAlias.java)

テレポートエイリアスに関する操作を行います。

### `/tpalias set <target> <replacement>`

tpコマンド実行時、プレイヤー名を置き換えるように設定します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | String | はい | 置き換える対象のエイリアス名 |
| `replacement` | String | はい | 置き換えるエイリアス名 |

### `/tpalias remove <target>`

tpコマンド実行時の置き換え設定を削除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | String | はい | 置き換える対象のエイリアス名 |

### `/tpalias list`

tpコマンド実行時の置き換え設定一覧を表示します。

## tpdeny

```plaintext
/tpdeny add <target>
/tpdeny remove <target>
/tpdeny notify <target> <changeTo>
/tpdeny list
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_TpDeny](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_TpDeny.java)

TpDeny(特定ユーザーからのテレポート拒否)の設定をします。

### `/tpdeny add <target>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

TpDenyにプレイヤーを追加し、以降のテレポートを拒否します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | OfflinePlayer | はい | 拒否する対象プレイヤー |

### `/tpdeny remove <target>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

TpDenyからプレイヤーを解除し、以降のテレポートを許可します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | OfflinePlayer | はい | 解除する対象プレイヤー |

### `/tpdeny notify <target> <changeTo>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

テレポートを拒否した場合に通知するかどうかを設定します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | OfflinePlayer | はい | 通知設定する対象プレイヤー |
| `changeTo` | Enum | はい | 通知をするか |

### `/tpdeny list`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

現在TpDenyに追加されている(テレポートを拒否されている)プレイヤーの一覧を表示します。

## var

```plaintext
/var text <key> <value>
/var plus <setToKey> <keyOrValue1> <keyOrValue2>
/var minus <setToKey> <keyOrValue1> <keyOrValue2>
/var multiply <setToKey> <keyOrValue1> <keyOrValue2>
/var division <setToKey> <keyOrValue1> <keyOrValue2>
/var calc <setToKey> <keyOrValue1> <mathSign> <keyOrValue2>
/var output <key>
/var list [page]
/var clear <key>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Var](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Var.java)

変数に関することを利用できます。

### `/var text <key> <value>`

変数を設定(代入)します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `key` | String | はい | 変数名 |
| `value` | String | はい | 代入する値 |

### `/var plus <setToKey> <keyOrValue1> <keyOrValue2>`

加算し、結果を変数に代入します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `setToKey` | String | はい | 結果を代入する変数名 |
| `keyOrValue1` | String | はい | 加算する変数名もしくは値 |
| `keyOrValue2` | String | はい | 加算する変数名もしくは値 |

### `/var minus <setToKey> <keyOrValue1> <keyOrValue2>`

減算し、結果を変数に代入します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `setToKey` | String | はい | 結果を代入する変数名 |
| `keyOrValue1` | String | はい | 減算される変数名もしくは値 |
| `keyOrValue2` | String | はい | 減算する変数名もしくは値 |

### `/var multiply <setToKey> <keyOrValue1> <keyOrValue2>`

乗算し、結果を変数に代入します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `setToKey` | String | はい | 結果を代入する変数名 |
| `keyOrValue1` | String | はい | 乗算される変数名もしくは値 |
| `keyOrValue2` | String | はい | 乗算する変数名もしくは値 |

### `/var division <setToKey> <keyOrValue1> <keyOrValue2>`

除算し、結果を変数に代入します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `setToKey` | String | はい | 結果を代入する変数名 |
| `keyOrValue1` | String | はい | 除算される変数名もしくは値 |
| `keyOrValue2` | String | はい | 乗算する変数名もしくは値 |

### `/var calc <setToKey> <keyOrValue1> <mathSign> <keyOrValue2>`

計算し、結果を変数に代入します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `setToKey` | String | はい | 結果を代入する変数名 |
| `keyOrValue1` | String | はい | 計算される変数名もしくは値 |
| `mathSign` | String | はい | 計算記号 |
| `keyOrValue2` | String | はい | 計算する変数名もしくは値 |

### `/var output <key>`

指定されたキーの値を出力します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `key` | String | はい | 変数名 |

### `/var list [page]`

キーの一覧を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `page` | Integer | いいえ | ページ |

### `/var clear <key>`

キーを削除します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `key` | String | はい | 削除する変数の変数名 |

## varcmd

```plaintext
/varcmd <command>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_VarCmd](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_VarCmd.java)

変数を含むコマンドの変数を置き換え、実行します。

### `/varcmd <command>`

変数を含むコマンドの変数を置き換え、実行します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `command` | String | はい | 変数を含むコマンド |

## walkspeed

```plaintext
/walkspeed [target]
/walkspeed set <percent>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_WalkSpeed](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_WalkSpeed.java)

移動速度を変更します。

### `/walkspeed [target]`

指定したプレイヤーの移動速度を表示します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `target` | Player | いいえ | ターゲットプレイヤー |

### `/walkspeed set <percent>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

移動速度を設定します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `percent` | Float | はい | 移動速度(通常100%) |

## weather

```plaintext
/weather <weatherName>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Weather](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Weather.java)

自分だけに適用される天気を設定します。

### `/weather <weatherName>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

自分だけに適用される天気を設定します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `weatherName` | String | はい | 天気名 |

## wire

```plaintext
/wire set <pos1> <pos2>
/wire setwe
/wire del <pos1> <pos2>
/wire delwe
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Wire](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Wire.java)

指定した地点間にリードを張ったり、撤去したりします。

- エイリアスがあります: `leadunit`

### `/wire set <pos1> <pos2>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定した2点間にリードを張ります。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `pos1` | ArgumentTriplet | はい | 1つ目のx・y・z座標。リードを付けられている側。 |
| `pos2` | ArgumentTriplet | はい | 2つ目のx・y・z座標。リードを持っている側。 |

### `/wire setwe`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

WorldEditで選択した地点間にリードを張ります。3地点以上を選択した場合、1-2,2-3,3-4地点間のようにリードが張られますが、選択した地点は全て同じ高さである必要があります。

### `/wire del <pos1> <pos2>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定した2点間のリードを撤去します。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `pos1` | ArgumentTriplet | はい | 1つ目のx・y・z座標。どちら側でも良いです。 |
| `pos2` | ArgumentTriplet | はい | 2つ目のx・y・z座標。どちら側でも良いです。 |

### `/wire delwe`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

WorldEditで選択した地点間のリードを撤去します。3地点以上を選択した場合、1-2,2-3,3-4地点間のようにリードが撤去されますが、選択した地点は全て同じ高さである必要があります。

## wt

```plaintext
/wt <worldName>
/wt <worldName> <player>
```

> ソースコード: [com.jaoafa.mymaid4.command.Cmd_Wt](https://github.com/jaoafa/MyMaid4/blob/master/src/main/java/com/jaoafa/mymaid4/command/Cmd_Wt.java)

他ワールドにテレポートします。

### `/wt <worldName>`

<aside class="notice">
このコマンドはプレイヤーからの実行のみに制限されています。
</aside>

指定したワールドにテレポートします。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `worldName` | String | はい | ワールド名もしくはワールド番号 |

### `/wt <worldName> <player>`

指定したプレイヤーを指定したワールドにテレポートさせます。

| 引数名 | 種類 | 必須か | 説明 |
| - | - | - | - |
| `worldName` | String | はい | ワールド名もしくはワールド番号 |
| `player` | Player | はい | テレポートさせるプレイヤー |
