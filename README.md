# Engo3 App APK 下載站

公司內部人員安裝 Engo3 App 各版本 APK 的下載頁。

- **下載頁**：https://smart-engo-technology-corp.github.io/engo3-apk/
- APK 檔放在本 repo 的 [Releases](../../releases)，頁面透過 GitHub API 自動列出所有版本。

## 發新版

發版流程（`/release-apk`）打包完成後執行：

```bash
gh release create v3.0.34+445 v3.0.34_445.apk --repo Smart-enGo-Technology-Corp/engo3-apk --title "v3.0.34 (445)" --notes "變更摘要"
```

頁面無需改動，會自動出現新版本。
