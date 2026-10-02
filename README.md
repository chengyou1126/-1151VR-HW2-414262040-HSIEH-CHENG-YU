# 1151VR-HW2

## 1. 專案截圖
<img width="886" height="427" alt="image" src="https://github.com/user-attachments/assets/e6534b73-c36f-41a9-b4bd-96c7a0969b05" />


## 2. GitHub 連結
https://github.com/chengyou1126/-1151VR-HW2-414262040-HSIEH-CHENG-YU/blob/main/README.md


## 3. YouTube 連結
https://youtu.be/K3U1PkCBCMo



## 4. 說明製作流程和相關操作
首先建立 Universal 2D 專案，匯入從圖庫下載的 2D 角色並去背圖片。
接著在場景中建立 GameObject，加入 Sprite Renderer 顯示角色圖片，並調整 Scale尺寸。撰寫 C# 腳本，宣告 Vector3 陣列 (Waypoints) 來儲存移動路徑點，使用 Vector3.MoveTowards 來實作角色移動。並在 Unity Inspector 中將陣列大小改設為 4，分別輸入起點、前進、上跳、下跳的 Vector3 座標。最後，按下 Play 鍵後，角色會自動讀取陣列中的座標，依序完成走到定點、跳躍並落下至終點的動作。
