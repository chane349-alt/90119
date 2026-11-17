HTML


<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <title>我的暑假最難忘回憶</title>
    <style>
        /* 1. 網頁整體背景與字體設定（可依主題修改色碼） */
        body {
            font-family: "微軟正黑體", sans-serif;
            background-color: #f0f8ff; /* 淺藍色背景，適合海邊或夏日主題 */
            color: #333333;            /* 深灰色文字，閱讀最舒適 */
            margin: 0;
            padding: 0;
            line-height: 1.8;          /* 行距拉開，文字不擁擠 */
        }

        /* 2. 頂部主視覺橫幅 */
        header {
            background-color: #0284c7; /* 主色調：海洋藍 */
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2.2em;
        }

        /* 3. 中間內容容器（置中對齊，限制最大寬度） */
        .container {
            max-width: 800px;
            margin: 30px auto;
            background-color: white;
            padding: 30px;
            border-radius: 12px;       /* 圓角設計 */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* 淡淡的陰影 */
        }

        /* 4. 標題裝飾線 */
        h2 {
            color: #0284c7;
            border-bottom: 2px solid #bae6fd;
            padding-bottom: 8px;
        }

        /* 5. 照片網格排版（兩張並排） */
        .photo-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 15px;
        }
        .photo-card {
            flex: 1 1 45%;             /* 每張卡片佔約一半寬度 */
            background-color: #f8fafc;
            padding: 10px;
            border-radius: 8px;
            text-align: center;
        }
        .photo-card img {
            width: 100%;               /* 圖片自動符合卡片寬度 */
            height: 220px;
            object-fit: cover;         /* 保持比例裁切，圖片不變形 */
            border-radius: 6px;
        }
        .caption {
            font-size: 0.9em;
            color: #64748b;
            margin-top: 8px;
        }

        /* 6. 頁尾版權宣告 */
        footer {
            text-align: center;
            padding: 20px;
            color: #64748b;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <!-- 頁首標題區 -->
    <header>
        <h1>🌊 追逐七星潭的第一道曙光</h1>
        <p>2026年8月12日 ｜ 花蓮・七星潭海邊</p>
    </header>

    <!-- 主要內容區 -->
    <div class="container">
        
        <!-- 第一區塊：300字回憶故事 -->
        <h2>📖 那天清晨的故事</h2>
        <p>
            今年暑假最讓我難忘的，不是去了多遠的遊樂園，而是凌晨四點半摸黑騎車前往七星潭看日出的那一天。剛到海邊時，天空還是深邃的藍黑色，海風吹在臉上帶著微微的涼意與鹹味，耳邊只有海浪規律拍打鵝卵石的「嘩啦」聲。
        </p>
        <p>
            我們一群人坐在石灘上安靜等待，看著海平面的雲層慢慢從紫灰色染成橘紅，最後金黃色的太陽突然躍出海面，把整片大海照得閃閃發光。那一瞬間，早起的疲憊全都消失了，心裡只有滿滿的感動。這道夏天的陽光，成了我國中最後一個暑假最耀眼的記憶。
        </p>

        <!-- 第二區塊：真實照片展示 -->
        <h2>📸 現場真實紀錄</h2>
        <div class="photo-grid">
            <div class="photo-card">
                <!-- 把 photo1.jpg 換成你的照片檔名 -->
                <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=600" alt="海邊風景">
                <p class="caption">▲ 清晨五點的海邊，天空正準備亮起來</p>
            </div>
            <div class="photo-card">
                <!-- 把 photo2.jpg 換成你的照片檔名 -->
                <img src="https://images.unsplash.com/photo-1470252649378-9c29740c9fa8?w=600" alt="日出瞬間">
                <p class="caption">▲ 太陽躍出海面的那一刻，全場都在歡呼</p>
            </div>
        </div>

        <!-- 第三區塊：AI 生成氛圍圖展示 -->
        <h2>🎨 AI 氛圍意境圖</h2>
        <div class="photo-grid">
            <div class="photo-card">
                <!-- 把 ai1.jpg 換成你用 AI 畫出來的圖片檔名 -->
                <img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b?w=600" alt="AI意境圖1">
                <p class="caption">▲ AI 生成：陽光灑在海浪上的溫暖氛圍</p>
            </div>
            <div class="photo-card">
                <!-- 把 ai2.jpg 換成你用 AI 畫出來的圖片檔名 -->
                <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=600" alt="AI意境圖2">
                <p class="caption">▲ AI 生成：記憶中最夢幻的夏日時光</p>
            </div>
        </div>

    </div>

    <!-- 頁尾區 -->
    <footer>
        <p>九年級數位回憶專案 ｜ 製作人：你的名字</p>
    </footer>

</body>
</html>
