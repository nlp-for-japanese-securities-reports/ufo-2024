# ufo-2024
[UFO-2024タスク](https://sites.google.com/view/ufo-2024/home?authuser=0, "UFO-2024")は、 **Table Retrievalサブタスク（以下、TRタスク）** と、 **Table QAサブタスク（以下、TQAタスク）** から構成されます。

## 更新情報
- (2024/8/15) データのPrivate公開

## タスク設定
以下をご参照ください。\
[TRタスク](https://sites.google.com/view/ufo-2024/subtasks/table-retrieval?authuser=0, "Table Retrieval")\
[TQAタスク](https://sites.google.com/view/ufo-2024/subtasks/table-qa?authuser=0, "Table QA")

## データ数
|  | train | valid | test |
| --- | ---: | ---: | ---: |
| Table Retrieval | 8390 | 1533 | 4487 |
| Table QA | 8390 | 1534 | 4488 |

## Baseline Scores
準備中です

## 特記事項
- データセットについて、Question IDは各タスクで連番になっていませんが、これはタスク間でQuestionの重複を防ぐためです。

## 出典
- `table_retrieval`および`table_qa`ディレクトリ内のファイルは、EDINET 閲覧（提出）サイト（※）をもとに UFO-2024 タスクオーガナイザが作成したものです。
    - （※）例えば書類管理番号が `S100ISN0` の場合、当該ページの URL は `https://disclosure2.edinet-fsa.go.jp/WZEK0040.aspx?S100ISN0` となります。書類管理番号は、`train`/`test` ディレクトリ内の各ファイル名の先頭 8 文字です。
