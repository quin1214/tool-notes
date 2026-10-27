# ピン画像の指示書（Canva 用）

ピンは合計 30 枚（各サービス 10 枚）。内訳は次のとおり。

- ふつうの版: 画像 18 種類。b1・t1・s1 は同じ画像をタイトル A と B で 1 回ずつ投稿するので、ピンは 21 枚
- 攻め版: 9 枚（このファイルの後半）
- 外したピン 8 枚は、末尾の「予備」に残してある。反応の悪いピンと入れ替えるときに使う
1 枚ずつ、下の「共通ルール」と「型」に各ピンの文字を流し込めば作れる。タイトル・説明文・リンク先は `pins/<サービス名>.md` を使う。

## 共通ルール

- **サイズ:** 1000 × 1500 px（縦 2:3）。PNG で書き出す
- **余白:** 左右 80 px、上 80 px。下の 120 px はフッター用に空けておく
- **文字サイズ:** 下の数字は Canva の文字サイズ欄に入れる値（このサイズならほぼ px と同じ）
- **配色:**（解説ページと同じ）
  - 背景 `#FBFAF7`（生成り）
  - 文字 `#24221F`（墨）
  - アクセント `#2F5D50`（深緑）。強調したい 1 語、線、番号に使う
  - 注意書きの帯 `#FFF6DC`（薄い黄色）
  - カードの枠線 `#E3DED3`
- **反転版:** 表の「反転」に ● がついたピンは、背景を `#2F5D50`、文字を白 `#FFFFFF`、強調の 1 語を `#FFF6DC` にする。フィードで同じピンが並んで見えないようにするため
- **フォント:**（Canva 無料版にあるもの）
  - サービス名ラベル: Open Sans Semi Bold 36
  - 見出し: Lora Bold 120。見出しが 35 字を超えるときは 96
  - サブ文: Open Sans Regular 48〜56。2 行まで
  - カード・箇条書き: Open Sans 44 以上
  - フッター: Open Sans Regular 28
- **サービス名ラベル（全ピン共通。左上）:** 例 `beehiiv · newsletter platform`。墨色の普通の文字で、枠やロゴ風の装飾はつけない
- **フッター（全ピン共通。左下）:** `Independent notes · Prices checked Oct 2026`
  - 料金を確認し直したら、この日付も新しい月に変える（投稿は 2027-01 まで続くため）
- **やらないこと:**
  - 各社のロゴ、アプリの画面写真、ブランドカラーは使わない。サービス名は普通の文字で書く
  - 「公式」「Official」に見える表現、バッジ、認証マーク風のアイコンは使わない
  - 取り消し線の価格や「SALE」のような割引表現は使わない
  - 他社と比べているように見える表現は使わない
- **写真（使う場合だけ）:** Canva の無料素材から、机・ノート・マイク・カレンダーなど中立なものを 1 点。型 A の上 40% に置き、見出しはその下に置く。人の顔のアップは避ける

## 型（3 種類）

### 型 A: 大見出し
- 上 2/3 に見出しを大きく（2〜3 行）。強調する 1 語（表で **太字** の部分）だけアクセント色にする
- その下に細い線（アクセント色、幅 120 px）
- 線の下にサブ文（2 行まで）

### 型 B: カード 3 枚
- 上部に見出し（1〜2 行）
- その下に白いカード（`#FFFFFF`、枠線 2 px `#E3DED3`、角丸 24 px）を縦に 3 枚
- 各カードに「質問（Semi Bold）」と「答え（Regular、6 語以内）」。手順のピン（t3）は手順を 1 行ずつ書く
- カードの左に番号 1・2・3（アクセント色）

### 型 C: 一覧・注意点
- 上部に見出し
- 箇条書き 3 行（行頭は短い横線。チェックマークは使わない）
- 一番下に注意書きの帯（`#FFF6DC`）を 1 行

---

## beehiiv（ラベル: `beehiiv · newsletter platform`）

リンク先: `docs/beehiiv.html`

| # | 型 | 反転 | 見出し | サブ文・中身 | タイトル |
|---|---|---|---|---|---|
| b1 | A | ● | Start a newsletter for **$0** | Free plan: up to 2,500 subscribers, no credit card. | A と B で 2 回 |
| b3 | C | | Free newsletter plan: the **catches** | ・No custom domain ・beehiiv branding stays ・Paid subscriptions need a paid plan ／帯: Lite: $49/mo billed yearly at 1,000 subscribers | A |
| b4 | A | | Is the free trial a **trap**? | 14 days, no card. Don't upgrade, and you stay on Free. | A |
| b6 | A | ● | When does free stop being **free**? | When you pass 2,500 subscribers, or want paid features. | B |
| b8 | A | ● | **0%** cut of your paid subscriptions | beehiiv says it takes 0%. Stripe's fee still applies. Lite and up. | C |
| b9 | A | | What the free trial **won't** let you test | Custom domains and paid subscriptions are held back during the trial. | A |

## Transistor（ラベル: `Transistor · podcast hosting`）

リンク先: `docs/transistor.html`

| # | 型 | 反転 | 見出し | サブ文・中身 | タイトル |
|---|---|---|---|---|---|
| t1 | A | | Switching podcast hosts? **3 things** to check | Price, download limits and moving your show. | A と B で 2 回 |
| t2 | A | | No overage fees. **Episodes keep playing.** | Still over 30 days after notice? New uploads lock. | A |
| t3 | B | | How switching podcast hosts **works** | 1 Export your old analytics ／ 2 Import your show by RSS ／ 3 Redirect the old feed | B |
| t5 | A | ● | One account, **unlimited** podcasts | Every plan. The download limit is shared across all your shows. | C |
| t6 | C | | The trial turns **paid** unless you cancel | ・14 days free ・Then it converts to a paid plan ・Set a reminder for day 13 ／帯: From Transistor's terms of service | A |
| t7 | A | | Under 20,000 downloads? **Starter** covers it | You can upgrade later from your account. | C |

## Sunsama（ラベル: `Sunsama · daily planner`）

リンク先: `docs/sunsama.html`

| # | 型 | 反転 | 見出し | サブ文・中身 | タイトル |
|---|---|---|---|---|---|
| s1 | A | | Tasks everywhere? **One list** each morning. | You pull calendar, email and work tasks into one daily list. | A と B で 2 回 |
| s2 | A | ● | 14-day trial. **No credit card.** | Every feature unlocked. A card only if you keep going. | B |
| s3 | A | ● | Is a **$17/month** planner worth it? | $17/mo billed yearly, $22 monthly. No free plan. | A |
| s4 | A | | Planning with a team? **Priced per person** | Each person added joins your bill, prorated the first month. | C |
| s7 | A | | Cancel any time, **no support email** | Access lasts to period end. Unsure? Start monthly. | A |
| s8 | C | | Who probably **doesn't** need Sunsama | ・A simple checklist already works for you ・You don't want a daily planning routine ・You don't need many tools connected ／帯: Then a free to-do app may be enough | A |

## 投稿と記録のメモ

- 1 日に何枚も出すより、3 か月に分けて週に数枚ずつ出す
- **タイトルの A/B 比較は b1・t1・s1 だけでやる。** 同じ画像をタイトル A と B で 1 回ずつ出すので、反応の差をタイトルの差として読める。ほかのピンは画像の内容に合うタイトルを付けているだけで、比較には使わない
- `tracking.csv` の memo 列にピン番号を書く（例 `b1-A`、`t4`）。どの画像が反応したかを追える

---

## 攻め版（キャッチーさ優先。9 枚）

ふつうの版より強い言い方と派手な見た目で、手を止めさせることを狙う。ただし次の線は越えない。

- **書いてよい:** 言い切り、問いかけ、短い文の畳みかけ、極端に大きい文字
- **書かない:**
  - 事実でないこと、根拠のない数字（例「200 人」のような作った数字）
  - 収益や結果の約束（「稼げる」「伸びる」など）。上限の数字は「UP TO」をつけて、結果に読めないようにする
  - 「今だけ」「残りわずか」のような、事実でない急かし
  - 他社や業界を下げる言い方。「他は〜する」と暗に読める言い方も含む
  - 乗り換えを命令する言い方（「STOP.」「SWITCH NOW」など）。ブランド自身の広告に見えやすい
  - 各社が話しているように読める一人称（「We」など）
  - 見出しにサービス名を大文字で入れること（ロゴ表記に似て見えるため）。サービス名はサブ文に普通の書き方で入れる

各ピンは、同じ話題のふつうの版とペアにしてある。タイトルもリンク先も同じにして出すと、見た目と言い方の違いだけで反応を比べられる。

- タイトル: ペアのふつうの版と同じものを付ける。b1・s1 のように A と B の両方で出すピンとペアのときは、**タイトル A に固定する**
- 出す順番: ペアは同じ週に出し、週ごとにどちらを先に出すかを入れ替える
- memo 列: `x-b1` のように書く
- ペアの相手が反転版（b1・t5・s2・s3）だと、見た目の差が小さくなる。結果を読むときに注意する

### 攻め版の共通ルール（ふつうの版と違うところだけ）

- **背景:** 黒 `#141414`。文字は白 `#FFFFFF`
- **強調:** 1 フレーズ（2 語まで）だけ色を変える。色は赤橙 `#FF5A36` か黄色 `#FFE14D`
  - そのサービスのブランドカラーに近いほうは使わない。投稿前に公式サイトの配色と見比べる
  - beehiiv は暖色系の印象があるので、まず赤橙で試す（記憶に基づく推測。要確認）
- **見出し:** Anton、すべて大文字、180
  - 1 行 10〜12 字まで、全体で 4 行まで
  - 入らなければ 140 まで下げるか、幅の狭い Bebas Neue に替える
- **サブ文:** Open Sans Semi Bold 52、白、2 行まで。**サービス名を必ず入れる**（フィードではラベルの文字が小さすぎて読めないため）
- **ラベル:** ふつうの版と同じ位置と文言で、色だけ白にする
- **フッター:** `Independent notes · Affiliate link · Prices checked Oct 2026`。画像の中にも開示を残すため、ふつうの版より文言を足している
- **写真やイラストは使わない。** 文字だけで勝負する

| # | ペア | 見出し | サブ文 |
|---|---|---|---|
| x-b1 | b1 | A NEWSLETTER FOR **$0.** REALLY. | beehiiv Free: up to 2,500 subscribers, no card, no time limit. |
| x-b2 | b4 | TRIAL ENDS. **YOU PAY $0.** | beehiiv's 14-day trial: no card. You drop back to Free. |
| x-b3 | b3 | FREE PLAN. **3 CATCHES.** | beehiiv Free: no custom domain, branding stays, no paid subs. |
| x-t1 | t2 | OVER YOUR LIMIT? **NO SURPRISE BILL.** | Transistor: no overage fees. Uploads may lock if you stay over. |
| x-t2 | t5 | UNLIMITED PODCASTS. **ONE BILL.** | Every Transistor plan, from $19/month. Downloads are shared. |
| x-t3 | t3 | YOUR OLD STATS **WON'T** COME WITH YOU. | Moving to Transistor? Step 1 of 3: export old analytics. |
| x-s1 | s1 | EMAIL. CALENDAR. CHAT. **ONE LIST.** | In Sunsama, you pull tasks from your tools into one daily list. |
| x-s2 | s2 | FORGOT TO CANCEL? **YOU PAY $0.** | Sunsama's 14-day trial never asks for a card. |
| x-s3 | s3 | $17 A MONTH FOR A **TO-DO APP?!** | Sunsama, billed yearly ($22 monthly). No free plan. |

**広告として配信する場合:** 「?!」のような表現は、Pinterest の広告審査で煽り表現として止められることがある。ふつうの投稿として出すぶんには影響は小さい。

**数について:** ふつうの版 21 枚 ＋ 攻め版 9 枚で、合計 30 枚。

---

## 予備（30 枚に絞るときに外したもの）

ほかのピンと内容が重なるので外した。反応の悪いピンと入れ替えるときや、30 枚を出し終えた後に使う。型・配色のルールはふつうの版と同じ。

| # | 型 | 反転 | 見出し | サブ文・中身 | タイトル |
|---|---|---|---|---|---|
| b2 | A | | Up to 2,500 subscribers. **No card.** | What the Free plan includes, and what it leaves out. | B |
| b5 | B | | 3 questions before you start a **newsletter** | 1 Do I have to pay? — No. Free up to 2,500. ／ 2 Is the trial a trap? — No card. You stay on Free. ／ 3 What's the catch? — No custom domain. Branding stays. | A |
| b7 | C | | beehiiv's plans at **1,000** subscribers | ・Free: $0, up to 2,500 ・Lite: $49/mo billed yearly ・Pro: $95/mo billed yearly ／帯: Prices rise as your list grows | C |
| t4 | A | ● | Podcast hosting from **$19/month** | 14-day trial, no free plan. 20,000 downloads a month on Starter. | C |
| t8 | B | | 3 questions before choosing a **podcast host** | 1 Free plan? — No. 14-day trial. ／ 2 Over the limit? — No overage fees. ／ 3 Lose listeners? — Redirect your old feed. | B |
| t9 | C | | Transistor's 3 plans, **side by side** | ・Starter $19/mo — 20K downloads ・Professional $49/mo — 100K ・Business $99/mo — 250K ／帯: Yearly billing: 12 months for the price of 10 | C |
| s5 | C | | Your work tools → **one daily list** | ・Google Calendar, Outlook ・Gmail, Slack, Teams ・Notion, Asana, Trello, Todoist ／帯: Integrations listed on Sunsama's site | C |
| s6 | B | | 3 questions before paying for a **planner** | 1 Expensive? — $17/mo yearly. No free plan. ／ 2 Charged if I forget? — No card in the trial. ／ 3 Easy to cancel? — Any time, no support email. | B |

外した理由:

- b2: b1・x-b1 と同じ「$0・カード不要」
- b5: b1・b3・b4 の内容をまとめただけ
- b7: 料金の話は b6・b8 と攻め版で足りる
- t4: $19 は t7・x-t2 と重なる
- t8: t1・t2・t3 の内容をまとめただけ
- t9: 料金の一覧は t7・x-t2 と重なる
- s5: s1・x-s1 と同じ「1 つのリストにまとめる」
- s6: s2・s3・s7 の内容をまとめただけ
