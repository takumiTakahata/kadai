```mermaid
graph TD;
subgraph "太郎"
1["スーパーに行く
作業時間10分"]-->2["豚肉を買う
作業時間10分"]-->4["キャベツを買う
作業時間10分"]-->5["油揚げを買う
作業時間10分"]-->6["米を買う
作業時間10分"]-->7["オレンジを買う
作業時間10分"]-->8["生姜チューブを買う
作業時間10分"]-->9["砂糖を買う
作業時間10分"]-->10["酒を買う
作業時間10分"]-->11["みりんを買う
作業時間10分"]-->12["オレンジを買う
作業時間10分"]
end
subgraph "三郎"
12-->13["米を研ぐ
作業時間10分"]-->14["米を炊く
作業時間30分"]
12-->15["水を沸騰させる
作業時間10分"]-->16["味噌を入れる
作業時間10分"]-->17["油揚げを入れる
作業時間10分"]
end
subgraph "松子"
12-->18["キャベツを洗う
作業時間10分"]-->19["キャベツを切る
作業時間10分"]-->21["たれを作る
作業時間10分"]-->22["肉を焼く
作業時間10分"]-->23["焼いた肉にたれを入れる
作業時間10分"]-->24["オレンジを切る
作業時間10分"]
end
subgraph "太郎"
14-->25["米を盛る
作業時間10分"]
17-->26["味噌汁を盛る
作業時間10分"]
23-->27["生姜焼きを盛る
作業時間10分"]
24-->28["オレンジを盛る
作業時間10分"]
end
```