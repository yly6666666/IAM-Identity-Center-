| IAM Identity Center設定手順                                                                                                  |
|--------------------------------------------------------------------------------------------------------------------------|
| 一．IAM Identity Centerの配置を有効化する                                                                                           |
| １．IAM Identity Centerにアクセスし、有効しているIAM Identity Centerの配置がないなら「有効にする」をクリックする                                              |
![alt text](image.png)
![alt text](image-1.png)
| 二．許可セットを作成する                                                                                                             |
| ２．他のアカウントからのアクセス許可を作成するために、「マルチアカウント」タブの「許可セット」をクリックする                                                                   |
![alt text](image-2.png)
| ３．存在している許可がないため新しく作成する。真ん中か右上かにある「許可セットを作成」をクリックする                                                                       |
![alt text](image-3.png)
| ４．今回は３つの許可セットのポリシーが必要であるため、一つずつ作成する<br>まず「事前定義された許可セット」を選択し、下にある「事前定義された許可セットのポリシー」からAdministratorAccessを選択し、「次へ」をクリックする |
![alt text](image-4.png)
![alt text](image-5.png)
| ５．「セッション期間」のみを「12時間」と設定し、ほかはそのままにし、「次へ」をクリックする                                                                           |
![alt text](image-6.png)
![alt text](image-7.png)
| ６．「作成」をクリックする                                                                                                            |
![alt text](image-8.png)
![alt text](image-9.png)
| ７．手順「３」「４」「５」「６」が記述したように、「PowerUserAccess」と「ReadOnlyAccess」の「許可セット」も作成する<br>作成したら、下記の画面になる                               |
![alt text](image-10.png)
| 三．ユーザーとグループを作成する                                                                                                         |
| ８．「ユーザー」をクリックする                                                                                                          |
![alt text](image-11.png)
| ９．「ユーザーを追加」をクリックする                                                                                                       |
![alt text](image-12.png)
| １０．画面通りに「ユーザー名」「メールアドレス」「名」「姓」を設定し、「次へ」をクリックする                                                                           |
![alt text](image-13.png)
![alt text](image-14.png)
| １１．「次へ」をクリックする                                                                                                           |
![alt text](image-15.png)
| １２．「ユーザーを追加」をクリックする                                                                                                      |
![alt text](image-16.png)
![alt text](image-17.png)
| １３．手順「８」「９」「１０」「１１」「１２」にように、ほかのユーザーも追加する                                                                                 |
![alt text](image-18.png)
| １４．「グループ」タブをクリックする                                                                                                       |
![alt text](image-19.png)
| １５．「グループ作成」をクリックする                                                                                                       |
![alt text](image-20.png)
| １６．「グループ名」を入力し、決められたユーザーをチェックし、「グループ作成」をクリックする                                                                           |
![alt text](image-21.png)
![alt text](image-22.png)
| ほかのグループが必要であれば、手順「１４」「１５」「１６」をしたがって作成しましょう                                                                               |
| 四．ユーザーとグループをAWSアカウントに割り当て                                                                                                |
| １７．「AWSアカウント」をクリックする                                                                                                     |
![alt text](image-23.png)
| １８．「リスト」クリックし、チェックを入れ、「ユーザーまたはグループを割り当て」をクリックする                                                                          |
![alt text](image-24.png)
| １９．グループをチェックし、「次へ」をクリックする                                                                                                |
![alt text](image-25.png)
| ２０．許可セットをチェックし、「次へ」をクリックする                                                                                               |
![alt text](image-26.png)
| ２１．「送信」をクリックする                                                                                                           |
![alt text](image-27.png)
![alt text](image-28.png)
| ２２．「設定」タブをクリックし、「AWSアクセスポータルのURL」を確認する                                                                                   |
![alt text](image-29.png)
![alt text](image-30.png)
| ２３．以下のように表示していれば無事完了                                                                                                     |
![alt text](image-31.png)
