# 1131405_上課練習：BeepPlayer 簡易電子琴

## 介面截圖

<img width="971" height="256" alt="image" src="https://github.com/user-attachments/assets/de5efc5a-d3e6-4df3-babf-fcf3d996ec19" />

## 功能

1. **簡易電子琴介面**
   - 將按鈕設計成鋼琴琴鍵的形式，包含白鍵與黑鍵，畫面更直覺

2. **白鍵音階播放**
   - 提供 Do、Re、Mi、Fa、Sol、La、Si、高音 Do

3. **黑鍵音階播放**
   - 加入 Do#、Re#、Fa#、Sol#、La#

4. **視窗縮放**
   - 程式會記錄初始控制項位置與大小
   - 當視窗大小改變時，琴鍵會依照比例調整位置與尺寸

5. **關閉確認**
   - 關閉程式前會跳出確認視窗
   - 避免使用者誤觸關閉按鈕
     <img width="972" height="528" alt="image" src="https://github.com/user-attachments/assets/3a581819-cfd1-45e6-8c9d-f3d8c4d4b870" />


## 音階對照表

### 白鍵

| 按鍵 | 音階 | 頻率 |
|---|---|---:|
| btn1 | Do | 523 Hz |
| btn2 | Re | 587 Hz |
| btn3 | Mi | 659 Hz |
| btn4 | Fa | 698 Hz |
| btn5 | Sol | 784 Hz |
| btn6 | La | 880 Hz |
| btn7 | Si | 988 Hz |
| btn8 | 高音 Do | 1046 Hz |

### 黑鍵

| 按鍵 | 音階 | 頻率 |
|---|---|---:|
| btnDoSharp | Do# | 554 Hz |
| btnReSharp | Re# | 622 Hz |
| btnFaSharp | Fa# | 740 Hz |
| btnSolSharp | Sol# | 831 Hz |
| btnLaSharp | La# | 932 Hz |
