## 演習2-7
ATMで「お金を引き出す」ユースケース図
###ユースケース図
ATMで「お金を引き出す」
### 概略
銀行のATMを利用して、自分の口座からキャッシュカードで必要なお金を引き出します。
###アクター
利用者
###事前条件
アクターが口座とキャッシュカードを持っていること。
###事後条件
アクターの口座から指定された金額が引き出されること。
###基本フロー
1. 利用者がATMにキャッシュされたカードを入れるとこのユースケースは始まる。
2. 認証番号を入力引き出す残高を入力する。
3. 引き出す残高を入力する。
3. 現金を引き取る
###代替えフロー
1. 基本フローの2で認証番号の入力に失敗した時、正しい認証番号を入力する
1. 基本フロー3において現金を引き出す際に指定した残高がない、再入力する。
###例外フロー
1. キャッシュカードを入れても口座がない。
###ユースケース名
ATMで「お金を引き出す」
【基本シナリオ】
1. キャッシュカードをATMに挿入する
2. 認証番号を入力する
3. 希望する金額を入力する
4. お金を取り出す
5. 領収書を取り出す

【例外シナリオ】
1. キャッシュカードを挿入しても使えない