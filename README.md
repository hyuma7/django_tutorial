# django_tutorial
ハンズオン用のチュートリアルです。

## 起動手順

作成したディレクトリ内で Python の `venv` を使用して仮想環境を作成します。

```powershell
PS C:> cd DjangoTutorial
PS C:\DjangoTutorial> python3 -m venv DjangoTutorial
```

`venv` を使用することでプロジェクトごとに異なるPythonライブラリのバージョンを管理できるようになります。これにより、複数のプロジェクトで依存関係の競合を防ぐことができます。

### Windowsの場合

Windows では PowerShell の実行ポリシーが仮想環境のスクリプト実行を制限しているため、以下のコマンドを実行して変更します。

```powershell
PS C:\DjangoTutorial> Set-ExecutionPolicy RemoteSigned -Scope CurrentUser -Force
```

2.2 仮想環境のアクティベート

次に仮想環境をアクティベートします。
```powershell
PS C:\DjangoTutorial> .\DjangoTutorial\Scripts\Activate.ps1
```


### macの場合
```bash
source DjangoTutorial/bin/activate
```
