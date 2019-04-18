# tetsu_physic（教材のアレな設定）
## 内容
* circle_eqnumber.sty：align環境での数式番号を丸数字にする．参照はeqrefを使うと，丸数字になる．
* enumitem_extended.sty：enumerate環境の番号を更に増やしたもの．カウンターの出力型としても使える．
* h XXX.sty：高２，高３の教材など．目的に合わせて使い分ける．
## アップデート方法
デスクトップ上にあるget-sty.commandを開けば，
1. 既存の/usr/local/texlie/texmf-local/tex/latex/tetsu_physic を削除する
2. git clone で，レポジトリを移植
3. ls-Rファイル作成の実行（TeXが見つけられるようにするための設定）

を自動で行います．パスワードの入力が必要です．
