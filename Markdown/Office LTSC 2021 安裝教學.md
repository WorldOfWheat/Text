# Office LTSC 2021 安裝教學

Office LTSC為官方所提供的金鑰版，不需購買且功能完全一樣。

---

[TOC]

---

## 自動安裝

:::warning
僅在 Windows 10/11 測試成功，其它系統不一定能成功。
自動安裝腳本內包含 Word、Excel、PowerPoint、Access，如要安裝其它服務則需使用手動安裝。
:::

:::info
自動安裝使用 Windows Bat 腳本執行，可以點擊下方的超連結進行下載。
:::

:::info
**步驟**
1. 將 ++Office LTSC 2021 安裝.zip++ 解壓縮至同一個資料夾。
2. 使用系統管理員執行 ++Run（需以系統管理員執行）.bat++。
3. 等待安裝完成即可。
:::

==[下載 Office LTSC 2021 安裝.zip](https://bit.ly/3GHy8fI)==

---

## 手動安裝

:::info
手動安裝步驟較多，可以分為下面幾步。
:::

:::info
**步驟**
1. 點擊下方按扭下載 ++Office 部署工具++。
2. 開新一個資料夾，
並點擊 ++officedeploymenttool++，
勾選 ++Click here to accept the Microsoft Software License Terms.++，並點擊 ++continue++ 解壓縮至資料夾。
3. 進入 ++Office 自定義工具++，依圖片指示調整。
![](https://i.imgur.com/0sO9Aom.png)
![](https://i.imgur.com/SxRtJnb.png)

4. 點擊右上方的 Export 按鈕，並匯出至第二步所建立的資料夾。

5. 使用 Cmd 至第二步所建立的資料夾，並輸入以下指令。
```bash=
officedeploymenttool.exe
setup /download config.xml
setup /configure config.xml

C:
cd C:\Program Files\Microsoft Office\Office16
cscript ospp.vbs /sethst:kms.03k.org
cscript ospp.vbs /act
```

6. 安裝即完成。
**完成後建議重新啟動電腦。**

:::

==[下載 Office 部署工具](https://bit.ly/3Q2AlW9)==

==[Office 自定義工具](https://bit.ly/3ZcQvAu)==

---

## 參考資料

{%youtube XLjUfzoJYgo %}

