<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>福祉求人ドヤ検索</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .job-card { transition: transform 0.2s; }
        .job-card:active { transform: scale(0.98); }
        .gradient-header { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
    </style>
</head>
<body class="bg-gray-50 pb-20">

    <div class="gradient-header text-white p-6 shadow-lg text-center">
        <h1 class="text-2xl font-bold">福祉求人ドヤ検索</h1>
        <p class="text-sm opacity-80 mt-1">高齢者・障害福祉の厳選求人</p>
    </div>

    <div id="job-list" class="p-4 space-y-4">
        
        <!-- 求人1 -->
        <div class="job-card bg-white rounded-xl shadow-md overflow-hidden border border-gray-100 p-4">
            <div class="flex justify-between items-start">
                <span class="bg-blue-100 text-blue-600 text-xs font-bold px-2 py-1 rounded">障害福祉</span>
                <span class="text-gray-500 text-xs font-bold">法人名：株式会社ドヤ・ケア</span>
            </div>
            <h2 class="text-lg font-bold mt-2 text-gray-800">生活介護事業所 ドヤ</h2>
            <div class="mt-3">
                <p class="text-red-500 font-bold text-lg">時給 1,350円〜</p>
                <p class="text-gray-600 text-sm">（月給 220,000円〜）</p>
            </div>
            <div class="mt-4 bg-orange-50 p-3 rounded-lg border-l-4 border-orange-400">
                <p class="text-gray-700 text-xs font-bold">✨ アピールポイント</p>
                <p class="text-gray-600 text-xs mt-1">土日休み！無資格からスタートした20代スタッフが多数活躍中です。</p>
            </div>
            <button class="w-full mt-4 bg-green-500 text-white font-bold py-3 rounded-lg shadow-sm">この求人を詳しく聞く</button>
        </div>

        <!-- 求人2 -->
        <div class="job-card bg-white rounded-xl shadow-md overflow-hidden border border-gray-100 p-4">
            <div class="flex justify-between items-start">
                <span class="bg-green-100 text-green-600 text-xs font-bold px-2 py-1 rounded">高齢者福祉</span>
                <span class="text-gray-500 text-xs font-bold">法人名：社会福祉法人ドヤ会</span>
            </div>
            <h2 class="text-lg font-bold mt-2 text-gray-800">特別養護老人ホーム ドヤの里</h2>
            <div class="mt-3">
                <p class="text-red-500 font-bold text-lg">時給 1,500円〜</p>
                <p class="text-gray-600 text-sm">（夜勤手当 1回8,000円）</p>
            </div>
            <div class="mt-4 bg-orange-50 p-3 rounded-lg border-l-4 border-orange-400">
                <p class="text-gray-700 text-xs font-bold">✨ アピールポイント</p>
                <p class="text-gray-600 text-xs mt-1">最新の介護ロボット導入で腰痛の心配なし！有給消化率100%を目指しています。</p>
            </div>
            <button class="w-full mt-4 bg-green-500 text-white font-bold py-3 rounded-lg shadow-sm">この求人を詳しく聞く</button>
        </div>

    </div>

    <p class="text-center text-gray-400 text-[10px] mt-4 mb-8 leading-relaxed">
        ※求人情報の詳細や契約については公式LINEへお問い合わせください。<br>
        © 2026 福祉求人ドヤ All Rights Reserved.
    </p>

</body>
</html>
