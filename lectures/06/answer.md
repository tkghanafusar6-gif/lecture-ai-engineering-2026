# 第6回 解答

## 演習

<!-- [tool call] の行は、表示された行をそのまま貼り付けてください。終わらなかった STEP は、空欄のままでかまいません。 -->

- STEP 1 のツールの名前：glossary_search_glossary
- STEP 2 の [tool call]：glossary_search_glossary({'query': '3レベル'})
- STEP 3 の [tool call]：fetch_fetch({'url': 'https://modelcontextprotocol.io/'})
- STEP 4 の [tool call]： aws_aws___search_documentation({'topics': ['general'], 'search_phrase': 'Using versioning in S3 buckets overview'})
- 気づき・疑問：外部サーバを使うことで、トークン数が大きく変化。

## 宿題

<!-- 基礎・実装・発展のどれか1つに取り組めば完了です。 -->

- 取り組んだレベル：基礎
- やったこと：toolでget_lecture_summaryを公開
- 結果：toolが８個になり、[glossary_get_lecture_summary]が追加された。
[tool call]   glossary_get_lecture_summary({'lecture': 2})
- 気づき・疑問：どのサーバーを使ったらよいのかを、どのように決めるのか疑問に思った。
