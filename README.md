# pos-versao

Última versão estável publicada do app POS da Aftercode.

O `latest.json` é **gerado pelo CI** do repositório do app (job `publish-version` do
`release.yml`) a cada tag estável `vX.Y.Z`. Não edite à mão: o app compara o `versionCode`
daqui com o instalado para avisar o operador que há versão nova.

```json
{ "versionName": "2.20.0", "versionCode": 46, "tag": "v2.20.0", "publishedAt": "..." }
```
