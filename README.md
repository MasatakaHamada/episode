# episodeのまとめ方

- ひとつのフォルダに次の4点を入れる

1. main.tex
2. maegaki.tex
3. atogaki.tex
4. kyouritu.cls
5. 全員分の原稿TeXファイル

- main.texに全員の原稿を入れる

\subfile{ファイル名}  
のようにして全員の原稿を読み込ませる

- main.texをコンパイルする

platex main  
platex main  
dvipdfmx main  
等でできる. 2回コンパイルしないと目次が更新されない（定理等の番号付けが2回コンパイルしないと反映されないのと同じ理屈）.

- その他の記事を編集する

前書き･あとがき等を編集する. 
表紙は別ファイルpdfで良いと思われる.

- 印刷

頑張る