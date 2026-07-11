# mymate-registry

MYmate skill 的公開分發點。client 經 raw URL 讀取 `index.json` 與 `skills/`。

- `index.json`：skill 清單、版本、sha256、min_client_version
- `skills/<id>/<version>/<id>-<version>.tar.gz`：skill 套件

發布由 mymate code repo 的 `registry/tools/publish.py` 產生後推送至此。
skill 為領域知識包，無任何機密。
