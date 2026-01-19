# LunaChat

以下は、**LunaChat** プラグインについて、**一般プレイヤー目線**での特徴と基本的な使い方をまとめた内容です。その後に、プレイヤーがよく使うコマンド一覧を表形式でご紹介します。

***

### LunaChat の特徴と基本的な使い方（プレイヤー目線）

* **チャンネル制チャット**：複数のチャットチャンネルを使い分けられ、チャンネルごとに入室パスワードの設定や、リストからの非表示設定が可能です。モデレーターによる管理機能（キック・BANなど）も備わっています
* **日本語変換機能**：ローマ字入力したチャットを自動でかな／漢字に変換できます。たとえば “kakkakun” → “かっかくん” のように表示されます
* **/tell と /r も日本語化**：従来の `/tell`（個別メッセージ送信）と `/r`（返信）が組み込まれており、日本語変換対応可能です
* **クリック可能なチャット**：チャット内のテキストがクリック可能で、URL やチャンネル切り替えなどが簡単に行えます

***

### プレイヤー向けコマンド一覧

<table><thead><tr><th>コマンド</th><th>説明</th></tr></thead><tbody><tr><td><pre><code>/ch create &#x3C;channel>
</code></pre></td><td>新しいチャットチャンネルを作成する</td></tr><tr><td><pre><code>/ch join &#x3C;channel>
</code></pre></td><td>指定したチャンネルに参加する</td></tr><tr><td><pre><code>/ch join !
</code></pre></td><td>発言先を通常チャットに戻す（グローバルチャットへ）</td></tr><tr><td><pre><code>/ch leave
</code></pre></td><td>現在参加中のチャンネルから退出する</td></tr><tr><td><pre><code>/ch list [page]
</code></pre></td><td>チャンネル一覧を表示。参加中・未参加などが色分け表示される。ページ指定も可</td></tr><tr><td><pre><code>/ch info
</code></pre></td><td>チャンネルのメンバー情報（オンライン・オフライン、モデレーター）を表示する</td></tr><tr><td><pre><code>/ch log [d=YYYY][p=名][f=キーワード]
</code></pre></td><td>当日または指定日のログを表示。プレイヤー名やキーワードでフィルタ可能</td></tr><tr><td><pre><code>/ch accept
</code></pre></td><td>招待されたチャンネルの参加を承諾する</td></tr><tr><td><pre><code>/ch deny
</code></pre></td><td>チャンネルへの招待を拒否する</td></tr><tr><td><pre><code>/ch hide [channel]
</code></pre></td><td>特定チャンネルの発言を非表示にする（指定省略で現在のチャンネル）</td></tr><tr><td><pre><code>/ch unhide [channel]
</code></pre></td><td>非表示にしたチャンネルの発言を再表示する</td></tr><tr><td><pre><code>/jp off
</code></pre></td><td>日本語変換（Jp機能）をオフにする（英語入力を優先したい時など）</td></tr><tr><td><pre><code>/jp on
</code></pre></td><td>日本語変換をオンにする</td></tr></tbody></table>

([ucchyocean.github.io](https://ucchyocean.github.io/BukkitPluginRelease/lunachat_usage.htm?utm_source=chatgpt.com))

***

#### 補足：便利な使い方例

たとえば、特定の仲間だけで話せる「秘密チャット」を作りたい場合：

1. `/ch create mysecret` で新規チャンネル作成。
2. `/ch join mysecret` で参加。
3. `/ch option password=abc123` でパスワード設定。
4. 仲間のみ参加を許可すれば、安全に会話ができます。

そのほか、ゲームによっては範囲限定チャットやPvP用チャットなど、用途に応じた運用が柔軟に行えるのが魅力です。

***

さらに具体的な設定方法や運用のご相談も、気軽にどうぞ！
