# event_know-how
2018年に様々なイベントを実施した会場設営等のノウハウの共有

# IT業界のイベント類で確認してきた、イベント実施ノウハウ

イベント、勉強会を実施する際にはやることがたくさんあります。
2018年、様々なイベントを実施してきて運営・主催は10回以上やりました。

そこでのイベント実施のノウハウを共有知とすべくここに記載します。

ひとまず、会場設営時・下見時のチェックリストを作成しました。

AWS Well-Architected Framework　みたいな感じでチェックリストとして、よしなに参考にしてください。

# 会場を下見する際のチェックリスト

1. 会場までの道のり
    1. 公式サイトなどのアクセス方法で迷わずに行けるか
    1. 特別迷いそうな場所なら、connpassなどで注意が必要かも。目印なども。地図観てくださいでいければOK
1. PCがモニターに映るか
    1. PCがモニターに映るかどうかを確認する
    1. モニタなのか、スクリーンなのか、HDMIなのか、VGAなのか、数、位置、投影時の操作
1. 登壇者のPC、デバイスから音量が流れるか
    1. HDMIだとしも、OSやケーブル相性に注意
    1. マイクジャックを抜き差しする際に騒音がでるケースがある
    1. 最悪、PCなどのデバイスにマイクを近づけて対応できるか
1. 会場として許容できる音量
    1. 登壇者のマイク、参加者のわいがや、スマートスピーカーの音などの音量が他会場に迷惑にならないか
    1. モニタなのか、スクリーンなのか、HDMIなのか、VGAなのか、数、位置、投影時の操作
1. 登壇者の声が伝わるか
    1. 登壇者の声が会場全体に伝わるか
    1. 狭い会場ならマイクなしでも良い
    1. スマートスピーカーのような音をだすデバイスの音量が会場全体もしくは展示箇所で十分伝わるか    
1. マイクの個数
    1. 登壇者の1つのみか、質問者用、スタッフ用もあるか
    1. 有線か無線か
1. スクリーンやモニターが会場のどこからでも確認できるか
    1. 一番後ろの席に座った場合でも、スクリーンをみることができるか
1. ポインタの利用
    1. 会場でレーザーポインタ等の貸与はあるか、利用する場合に費用が発生するか
    1. オススメは「Logicool Spotlight」    
1. 電源まわり
    1. 【登壇者】のPCやデバイスが使用できる位置にコンセントがあるか
        1. 壁コンセント、床コンセントの配置と、1箇所あたりに何口差せるかの情報があると良い
    1. 【参加者】のPCやデバイスが使用できる位置にコンセントがあるか
    1. 電源タップや延長コードが必要か、必要なら長さや個数はどうするか
        1. 想定される参加者の机の島の位置と、コンセントとの位置関係を要確認
    1. 電源タップは会場で貸し出しがあるのか、貸出量がかかるのか
    1. 会場スポンサー以外の運営スタッフが自前で延長タップなどを持参することが許諾されるか
    1. 自前で用意する場合、物理的な運搬はどうするのか
    1. 電源タップが必要である場合、必要な端子の数はいくつか
        1. 参加者1人あたり2つまでとして計算するのがベター    
    1. 電気容量
        1. 同じコンセントを使いすぎて落ちたりしないか
        1. 壁電源が集約されている場合、何系統使用できるのか、および何ワットまで使えるのか事前に確認
    1. Macのでかいアダプタが抜き差しできるか
        1. 特にコンセントが床に埋め込み式の場合、挿せるが抜けない場合がある  
    1. 電源泥棒のケーブルで転ばないようにする
        1. コンセントの使用か制限されている場合、それでも電源をみつけると差す人がいる。この場合、無防備に配線を敷かれるので足がひっかかる可能性があるので注視すること。
        1. そもそも許可されていない人に電源を使わせるのは犯罪の可能性
1. ネットワーク環境まわり
    1. 会場のWifiが存在するか
    1. 会場のWifiが存在する場合、許容できるデバイス数はどのくらいか
    1. 会場のWifiが存在する場合、登壇者用と参加者等でアクセスポイントをわけることができるか    
    1. テザリング用端末・モバイルルータの準備はできるか
    1. 会場規定でテザリングが禁止であるかどうか
    1. ssidやpassはイベント時のみの使用か、再利用されるものか
        1. セキュティ上、再利用される場合はSNS等にWifiの設定情報は流さないように配慮すること
1. デモ対応
    1. ドローンを飛ばしてもOKか
    1. Pepperのようなロボットを動かしてもOKか    
    1. 暗幕を張れるか
    1. ロウソク程度の火なら使用可能か    
1. 机
    1. 登壇者用の登壇時の机・演台が存在するか
    1. 登壇者用の登壇待機時の机が存在するか 
        1. ギリギリまで資料をつくりたい場合がある
        1. 登壇待機時にTwitterのハッシュタグなどを追う場合がある
    1. 参加者用の机がどのくらい存在するか
        1. 設営時に机が移動できるかも併せて確認、また、机の位置を変更する場合は戻すことを想定して事前に写真を撮影すること
    1. 参加者用の机の幅に、ノートPCとデバイス・ガジェット類を配置できる余裕があるか
    1. 受付用の机は用意できるか    
1. 椅子
    1. 登壇者用の椅子が存在するか
        1. ハンズオンやライブコーディングの場合、登壇中ずっと立ちっぱなしになるのか
    1. 参加者用の椅子の数はいくつか
        1. レイアウト変更を考慮する
    1. 椅子が机付きの場合とそうでない場合が混同する際、机付きは便利であるため会場前方に配置する        
1. 会場レイアウト
    1. 机や椅子などのレイアウトは変更可能か、必要であれば数を増減できるのか
    1. 机机や椅子はレイアウトを変更した場合、元に戻す必要があるか
        1. 基本的に会場を借りさせて頂いているので、運営スタッフが元に戻すべき
        1. 施錠やパーティションの操作などで、会場スポンサーの方々のみで撤収作業を行うケースも存在する
            1. あくまで主催させていただいているのであって、極力撤収作業は協力するのが大原則    
1. 飲食可否
    1. 当日の会場は飲食可能なのか
    1. 原則禁止の場合はペットボトル等の蓋ができる飲料ならば可能か
        1. 衛生管理上、飲食物の持ち込みは禁止の場合もある。個々人の持ち込みは個々人の責任であるが、可能なら事前周知した方が無難
1. 荷物の搬入
    1. 会場に／会場から荷物の送付などすることができるか
        1. 可能なら方法はどうなるか　宛先や受取人、業者など    
    1. 特に大型の荷物の移動は可能か
        1. 台車の有無や荷物用エレベーターの有無     
1. 時間
    1. イベント終了後に速やかに撤収できるか
        1. 撤収にかけられる時間はどのくらいか    
    1. 撤収の時間の期限
        1. 建物や部屋の退館に関する（部屋の予約、建物のセキュリティ上の都合など）
1. 避難経路確認
    1. 会場の避難経路および非常階段を確認する        
        1. イベント当日にアナウンスするのはほぼMUST  
1. 諸設備の位置・場所
    1. トイレ
    1. 自販機
    1. 喫煙所
    1. エレベーター
    1. 夜間出入り口    
1. 空調
    1. 冷房、暖房の設備有無
    1. 空調設備の操作方法と操作して良い人は誰か確認
1. 照明
    1. 会場の照明のON・OFFができるか
        1. 照明を操作できる人は誰か
        1. どのスイッチがどこの照明か
        1. 隣接する他会場の照明まで操作してしまう可能性があるか        
1. 入館・退館
    1. セキュリティカードの扱いは【最重要】
    1. 入館はそのままエレベータ利用等で入れるか、誘導が必要か
    1. 会場の部屋からトイレや喫煙所に行く際の、部屋の扉は出入り自由か    
    1. 特定の時間以降の入館は不可なのか、裏口から入館できるのか
    1. 退館した場合の再入場は可能か、またそのやり方   
    1. 会場への出入り口は1つか複数か      
    1. 遅刻者を拾い上げる方法を共有しておく    
1. 誘導
    1. 「会場は〇〇会議室です」のような誘導が必要か
    1. サイネージがあるなら対応可能か
    1. 案内板や看板を配置できるか、人間で対応しないといけないか
    1. 案内用の紙を用意する際に、以下のようなルールがあるか
        1. テープ類の使用は可能か
        1. 紙のサイズ
        1. 壁に貼る場合は配置していい場所、位置、高さ    
1. 懇親会
    1. 懇親会会場はイベント実施会場と同一か、移動か必要か
    1. アルコール以外の飲料物は複数種類用意する
    1. ビール類は缶単一なので、すぐに手に取れるが、一方で、ソフトドリンクは2リットルペットボトルから注ぐ作業が発生する場合が多い
        1. ソフトドリンクの待機列が分散できるように配慮する
    1. ピザは安パイではあるが、手がよごれる
        1. 名刺交換、デバイス操作等を考慮してウェットティッシュを用意する
    1. ピザではなく、マクドナ●ドのハンバーガーにすると個包装されており、手もたいして汚れない
        1. チーズバーガーをあえて少量混ぜると盛り上がる    
1. ゴミの分別
    1. 缶、瓶、紙皿、割りばし、紙コップ、プラスチックコップ、飲食物、生ごみ等の分別はあらかじめ袋をわけておいて設置する
    1. 飲料の飲み残しの対応は会場と事前に決めておく
        1. 液体物の廃棄の処理は手間もかかるので廃棄場所を事前に共有しておくと分散できる 
