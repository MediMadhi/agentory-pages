開発ログ差し込み用のマーカーを対象HTMLに追加してください。

必須マーカー:

<!-- DEVLOG:START -->
ここにActionsが生成した開発ログ（HTML <ul> ... </ul>）が挿入されます。
<!-- DEVLOG:END -->

デフォルトの対象ファイルは `index.html` です。別ファイルにしたい場合は、
repository_dispatch の payload で `target_file` を指定してください。

