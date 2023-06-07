## To start services run following commands in your terminal or powershell.
Note that following service is basicly a bash code!

```bash
git clone https://github.com/FIWARE/tutorials.CRUD-Operations.git
cd tutorials.CRUD-Operations
git checkout NGSI-LD

./services orion|scorpio
```

> **注 :** クリーンアップして最初からやり直す場合は、次のコマンドで実行できます :
>
> ```
> ./services stop
> ```


___
## Notes:
1. make sure your docker engin is already runnig.
2. depending on whether you use Orion or Scorpio, your request port might be diffrent.
3. a complete API refrence have been provided at [Postman](https://app.getpostman.com/run-collection/7764c9cbc3cfe2d5b403).
4. for live observation over data you can use following UI.
