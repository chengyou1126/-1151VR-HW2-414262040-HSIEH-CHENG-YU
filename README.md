# 1151VR-HW2

**1. 專案截圖**
(請在這裡貼上或插入您的 Unity 專案截圖)

**2. GitHub 連結**
(請貼上您這個 GitHub Repository 的網址)

**3. YouTube 連結**
(請貼上您剛才上傳的 YouTube 影片網址)

**4. 說明製作流程和相關操作**
* 製作流程：
  1. 建立 Universal 2D 專案，並匯入從開源圖庫下載的 2D 角色去背圖片。
  2. 在場景中建立 GameObject，加入 Sprite Renderer 顯示角色圖片，並調整 Scale 放大尺寸以利觀看。
  3. 撰寫 C# 腳本，宣告 Vector3 陣列 (Waypoints) 來儲存移動路徑點，並使用 Vector3.MoveTowards 實作角色移動。
  4. 在 Unity Inspector 中將陣列大小設為 4，分別輸入起點、前進、上跳、下跳的 Vector3 座標。
* 相關操作：按下 Play 鍵後，角色會自動讀取陣列中的座標，依序完成走到定點、跳躍並落下至終點的動作。
