<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>作物の紹介 - イチゴ</title>
  <style>
    /* CSSによる装飾 (条件6) */
    body {
      font-family: "Helvetica Neue", Arial, "ヒラギノ角ゴ Pro W3", "Hiragino Kaku Gothic Pro", メイリオ, Meiryo, sans-serif;
      background-color: #fcf8f2;
      color: #333333;
      line-height: 1.8;
      margin: 0;
      padding: 20px;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
    }

    h1 {
      color: #e63946;
      font-size: 2.2rem;
      border-bottom: 3px solid #e63946;
      padding-bottom: 10px;
      margin-top: 0;
    }

    h2 {
      color: #2a9d8f;
      font-size: 1.5rem;
      margin-top: 30px;
      border-left: 5px solid #2a9d8f;
      padding-left: 10px;
    }

    p {
      font-size: 1rem;
    }

    ul {
      background-color: #f4f9f8;
      padding: 20px 20px 20px 40px;
      border-radius: 8px;
    }

    li {
      margin-bottom: 8px;
    }

    img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      margin-top: 15px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 15px;
    }

    th, td {
      border: 1px solid #dddddd;
      padding: 12px;
      text-align: left;
    }

    th {
      background-color: #e9c46a;
      color: #ffffff;
      width: 30%;
    }

    .button-group {
      margin-top: 30px;
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      padding: 12px 24px;
      font-size: 1rem;
      font-weight: bold;
      color: #ffffff;
      text-decoration: none;
      border-radius: 6px;
      transition: background-color 0.3s ease;
      text-align: center;
    }

    .btn-school {
      background-color: #1d3557;
    }

    .btn-school:hover {
      background-color: #457b9d;
    }

    .btn-cultivation {
      background-color: #2a9d8f;
    }

    .btn-cultivation:hover {
      background-color: #e76f51;
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- 条件1: 一番上に大見出し（作物名） -->
    <h1>イチゴ（苺）の栽培</h1>

    <!-- 条件5: 画像が1枚以上 -->
    <img src="https://images.unsplash.com/photo-1464965911861-746a04b4bca6?auto=format&fit=crop&w=800&q=80" alt="おいしそうなイチゴ">

    <!-- 条件2: 特徴の説明文が3文以上 -->
    <h2>作物の特徴</h2>
    <p>
      イチゴは鮮やかな赤色と甘酸っぱい味わいが特徴で、子供から大人まで幅広く愛される人気のフルーツです。
      ビタミンCが非常に豊富に含まれており、風邪予防や美容効果にも優れた栄養価の高い作物です。
      家庭菜園や農業実習でも人気があり、プランターを使えば省スペースで栽培を楽しむことができます。
    </p>

    <!-- 条件3: 栽培のポイントが箇条書きで3つ以上 -->
    <h2>栽培のポイント</h2>
    <ul>
      <li>日光が良く当たる風通しの良い場所で育て、苗の根元（クラウン）を埋めすぎないように植え付けます。</li>
      <li>土の表面が乾いたらたっぷりと水を与えますが、過湿になると根腐れの原因になるため注意します。</li>
      <li>春先に花が咲いたら人工授粉を行い、果実が直接土に触れないようマルチングや敷き藁を敷きます。</li>
    </ul>

    <!-- 条件4: 表（table）を使って情報をまとめてある -->
    <h2>基本情報</h2>
    <table>
      <tr>
        <th>苗植え時期</th>
        <td>10月 〜 11月</td>
      </tr>
      <tr>
        <th>収穫時期</th>
        <td>4月 〜 6月</td>
      </tr>
      <tr>
        <th>栽培難易度</th>
        <td>中級（家庭菜園初心者でもプランターで栽培可能）</td>
      </tr>
    </table>

    <!-- ボタンエリア -->
    <div class="button-group">
      <!-- 条件7: ボタン① 西条農業高校のサイトが開く -->
      <a href="https://saijo-ag.esnet.ed.jp/" target="_blank" rel="noopener noreferrer" class="btn btn-school">
        西条農業高校のサイトを見る
      </a>

      <!-- 条件8: ボタン② 外部栽培サイト（サカタのタネ等）が開く -->
      <a href="https://www.sakataseed.co.jp/" target="_blank" rel="noopener noreferrer" class="btn btn-cultivation">
        イチゴの育て方（サカタのタネ）
      </a>
    </div>
  </div>

</body>
</html>
