# アプリ名

位置共有アプリ

# 概要

友人や家族と位置共有できるアプリ

# 開発の背景

少し前に位置共有アプリが流行ったこともあり、純粋に「面白そう！どういう仕組みなんだろう」という好奇心から作りました

# こだわった点

・別のユーザのログイン状況をDBからリアルタイムで取得し、「〇〇がログインしました」とポップアップを出す機能  

・マーカーをクリックするとその人の情報を表示する機能

# 苦労した点

・相手の位置情報を取得する 

・取得した位置にマーカーを表示する 

・ログアウト時にデータベースから自動で位置情報を削除する機能

# 使用技術
HTML/CSS/javascript/firebase

# 選定理由

位置を取得するのに必要な認証機能が簡単に実装できる
