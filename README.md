# drug-json-api-server

## 不可更動之假資料(模擬回應正常，但資料不更新)

https://my-json-server.typicode.com/JunTingLin/drug-json-api-server-old


| 目的       | 方法        | URL         |
| -------- | --------- | ----------- |
| 取得所有藥物資料 | GET       | /XXX      |
| 取得某藥物資料  | GET       | /XXX/1    |
| 新增藥物     | POST      | /XXX      |
| 更改某藥物資料  | PUT/PATCH | /XXX/{id} |
| 刪除某藥物    | DELETE    | /XXX/{id} |

註解: 新增、修改、刪除會傳回正確成功資訊，但不會真的影響，僅作為練習使用

![image](https://user-images.githubusercontent.com/92431095/221526122-d82df3b9-c9af-43d8-99d7-f898aafd7376.png)

![image](https://user-images.githubusercontent.com/92431095/221526491-8dab3888-3b55-41a5-af10-6f7d56892fef.png)

## 可更動之假資料(有效請求後db.json資料會變)
npm下載，其實也非常方便(需裝好Node.js)

`npm init`

`npm install -save json-server`
(-g 是global)

`json:server": "json-server --watch db.json`

![image](https://user-images.githubusercontent.com/92431095/221579582-6260780a-a8ee-4de8-9a6b-194f2e77acea.png)


repo: https://github.com/typicode/json-server

tutorial: https://www.youtube.com/watch?v=1zkgdLZEdwM&ab_channel=TraversyMedia




