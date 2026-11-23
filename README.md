# fanhanyunchris.github.io

這個網站空間只用來放 Firebase 的 Google 登入輔助檔（`__/auth/`），讓 Project.CD（https://fanhanyunchris.github.io/project-cd/）的登入跟網站在同一個網域，iPhone 主畫面 App 才能用 Google 登入。

- `__/auth/` 裡的檔案是從 `https://projectcd-c8577.firebaseapp.com/__/auth/` 原樣下載的（2026-11-23），Firebase 官方「自行託管登入輔助程式」做法。Firebase 更新 SDK 後如果登入出問題，重新下載這幾個檔案覆蓋即可。
- 首頁直接轉到 /project-cd/。
