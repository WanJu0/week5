# week5
## 要求三

1.使用 INSERT 指令新增一筆資料到 member 資料表中，這筆資料的 username 和 password 欄位必須是 test。接著繼續新增至少 4 筆隨意的資料。

<img width="524" alt="image" src="https://user-images.githubusercontent.com/95067096/196851231-405b39e4-7c50-42b8-a058-ff0f89382bc3.png">

2.使用 SELECT 指令取得所有在 member 資料表中的會員資料。

<img width="484" alt="image" src="https://user-images.githubusercontent.com/95067096/196851445-80c7eb1b-9ec8-4f7e-bc22-1037068a7029.png">

3.使用 SELECT 指令取得所有在 member 資料表中的會員資料，並按照 time 欄位，由近到遠排序。

<img width="505" alt="image" src="https://user-images.githubusercontent.com/95067096/196851540-89beed04-f829-4279-a83a-0822a6e6198c.png">

4.使用 SELECT 指令取得 member 資料表中第 2 ~ 4 共三筆資料，並按照 time 欄位，由近到遠排序。( 並非編號 2、3、4 的資料，而是排序後的第 2 ~ 4 筆資料 )

<img width="501" alt="image" src="https://user-images.githubusercontent.com/95067096/196851698-a39d13b2-6c98-4bb4-90be-5a349c555d26.png">

5.使用 SELECT 指令取得欄位 username 是 test 的會員資料。

<img width="502" alt="image" src="https://user-images.githubusercontent.com/95067096/196851784-ec3d8ca7-1928-4dd3-9a98-7275b9e1d29a.png">

6.使用 SELECT 指令取得欄位 username 是 test、且欄位 password 也是 test 的資料。

<img width="552" alt="image" src="https://user-images.githubusercontent.com/95067096/196851857-db9ab62e-45d5-4a9e-9fea-80e4ab100f90.png">

7.使用 UPDATE 指令更新欄位 username 是 test 的會員資料，將資料中的 name 欄位改成 test2。

<img width="503" alt="image" src="https://user-images.githubusercontent.com/95067096/196852024-41e4bfbe-b775-41f9-9779-0076fd1d28d4.png">

## 要求四:SQL Aggregate Functions 利用要求二建立的資料庫和資料表，寫出能夠滿足以下要求的 SQL 指令:

1.取得 member 資料表中，總共有幾筆資料 ( 幾位會員 )。

<img width="280" alt="image" src="https://user-images.githubusercontent.com/95067096/196852222-b104be35-392f-48b1-b1d8-64baf5e0646c.png">

2.取得 member 資料表中，所有會員 follower_count 欄位的總和。

<img width="551" alt="image" src="https://user-images.githubusercontent.com/95067096/196852293-261e678b-e4b8-48f0-b4dc-0d62ee220bca.png">

3.得 member 資料表中，所有會員 follower_count 欄位的平均數。

<img width="336" alt="image" src="https://user-images.githubusercontent.com/95067096/196852365-00bfa1ee-2179-4fe6-b13d-87eccb254492.png">

## 要求五:SQL JOIN (Optional)

1.在資料庫中，建立新資料表紀錄留言資訊，取名字為 message。資料表中必須包含以
下欄位設定:

<img width="336" alt="image" src="https://user-images.githubusercontent.com/95067096/196852509-9d54d21f-3043-436a-966b-2cd68b200dec.png">
<img width="570" alt="image" src="https://user-images.githubusercontent.com/95067096/196852606-f80436d6-ea47-4110-a330-908f6aed172d.png">
<img width="562" alt="image" src="https://user-images.githubusercontent.com/95067096/196852733-52b41a82-c6b4-4c91-a68b-99de644b7bdd.png">

2.使用 SELECT 搭配 JOIN 語法，取得所有留言，結果須包含留言者會員的姓名。

<img width="574" alt="image" src="https://user-images.githubusercontent.com/95067096/196852778-1d742f6d-61d1-47ea-b9ef-80158805f8b4.png">

3.使用 SELECT 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有留言，資料中須包含留言者會員的姓名。

<img width="828" alt="image" src="https://user-images.githubusercontent.com/95067096/196852854-e5f65be2-620e-4020-ac39-f755c4cb8aa8.png">

4.使用 SELECT、SQL Aggregate Functions 搭配 JOIN 語法，取得 member 資料表中 欄位 username 是 test 的所有留言平均按讚數。 

<img width="765" alt="image" src="https://user-images.githubusercontent.com/95067096/196852988-316bd8f7-11bf-4e62-ab34-8f39ec1a9e14.png">



