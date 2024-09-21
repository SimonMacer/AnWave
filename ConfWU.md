### Configure Windows Update for Business
===================================================

### 【AnWave】AnWave Windows Key-Point - Windows 設定選項管理器:https://github.com/SimonMacer/AnWave/discussions/9

### 【設定商務用 Windows Update】
![Configure Windows Update for Business](https://private-user-images.githubusercontent.com/136802581/369606424-e6e0abae-9679-47c9-aed8-7b21ea8be2a5.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjY5NjEzMjAsIm5iZiI6MTcyNjk2MTAyMCwicGF0aCI6Ii8xMzY4MDI1ODEvMzY5NjA2NDI0LWU2ZTBhYmFlLTk2NzktNDdjOS1hZWQ4LTdiMjFlYThiZTJhNS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyMVQyMzIzNDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yMzlmMmNhNzgyOGYxMjA2YTYyYWYxYTI1ZmRiZTg3NjVlMjVmZDMxYzg3MjlhYjYyMzI3ZDRlZTFhY2E2MzZmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.HFemG3Ni6FTHGrhRGIJCmk1IhkIJ5p1K2y5ewcBSHPM "Configure Windows Update for Business")

### 【啟用/停用】移除對所有 Windows Update 功能的存取權。
啟用此原則可安全的停用 Windows Update 存取權限，此原則屬於 Windows 本機群組原則管理不會刪除及修改任何系統檔案。
### 【啟用/停用】選擇 [目標功能更新] 版本。
此原則可用於停止接收 Windows 的功能版本更新。例如: 我想停留在 Windows 10 22H2 版本，那麼選擇 Windows 10 及 22H2 後 Windows Update 不會接收及提醒 Windows 11 的版本更新。
### 【啟用/停用】使用暫停 Windows Update 的原則設定 (新原則設定)。
這使裝置能夠推遲對其當前產品 (或新產品，如果在選擇目標功能及品質更新版本原則中指定) 可用的下一個功能及品質更新。延遲 30 天。此原則最大可延遲 30 天，此原則適合所有版本，亦即家用版本也適用於此原則。
### 啟用【自動延長暫停更新的延遲時間】選項可以無限延長暫停更新日期直到您取消為止。此功能需要安裝 Windows Update Service Extended 服務才有作用。
注意: Windows 10 及 Windows 11 24H2 建議使用此原則。
### 【啟用/停用】使用暫停 Windows Update 的原則設定 (過時的原則設定)。
這使裝置能夠推遲對其當前產品 (或新產品，如果在選擇目標功能及品質更新版本原則中指定) 可用的下一個功能及品質更新。延遲至 3000 年。此原則最大可延遲至 3000 年，適合 Windows 11 21H2/22H2/23H2 版本，家用版本也適用於此原則。

### 【Windows Update】使用 AnWave - Windows Key-Point 停用 Windows Update 驅動程式的自動更新
--------

### For Windows 10/11 家用版 (Home) - 停用【Windows Update 的驅動程式更新模組功能】以防止驅動程式被覆蓋
如果您安裝的 Windows 是家用版本 (Home)，那麼【不包含 Windows 更新的驅動程式】ExcludeWUDriversInQualityUpdate 原則設定可能沒有作用。您可以在 Windows Key-Point 中停用【Windows Update 的驅動程式更新模組功能】選項以在家用版 (Home) 停止接收驅動程式更新。

![Windows Update 的驅動程式更新模組功能](https://private-user-images.githubusercontent.com/136802581/369606173-7ac8846d-fa41-464d-9cd9-8e0e56e4a4b0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjY5NjEzMjAsIm5iZiI6MTcyNjk2MTAyMCwicGF0aCI6Ii8xMzY4MDI1ODEvMzY5NjA2MTczLTdhYzg4NDZkLWZhNDEtNDY0ZC05Y2Q5LThlMGU1NmU0YTRiMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyMVQyMzIzNDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mMDk2MGYyN2Y0MmJkMzc2ZjZmNGVhYTFjZGM2OTU3NDNkYjg4NTI1OGQ0OTVjMGZkYWE3NWIwYTJlYWRhN2EwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Uw8dSsK9su_MjSb-NQ23oIzgvWbw-ffhHreElgISdvg "Windows Update 的驅動程式更新模組功能")

【設定商務用 Windows Update】標籤頁中的【接收驅動程式更新】>【Windows Update 的驅動程式更新模組功能】取消勾選狀態。

### For Windows 10/11 專業版 (Pro) 或更高級的版本 - 啟用【不包含 Windows 更新的驅動程式】原則設定以防止驅動程式被覆蓋
專業版 (Pro) 或更高級的版本適用【不包含 Windows 更新的驅動程式】ExcludeWUDriversInQualityUpdate 原則。

![不包含 Windows 更新的驅動程式](https://private-user-images.githubusercontent.com/136802581/369606201-fc5b53c4-1a38-441e-a816-78d4c25b2b09.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjY5NjEzMjAsIm5iZiI6MTcyNjk2MTAyMCwicGF0aCI6Ii8xMzY4MDI1ODEvMzY5NjA2MjAxLWZjNWI1M2M0LTFhMzgtNDQxZS1hODE2LTc4ZDRjMjViMmIwOS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkyMVQyMzIzNDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hNmMwZTU1Y2M2YTcwNGZhMTNkOWU2Y2E4ZmM4ZjY5ZmY4ZWQ3MDIyMjM0OGMwNDYxY2QwZWI4NmE5Y2E1ZGRhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.MOt_OEpBifnCywkOuF1SonBxk27C29RVxhY3mt15zVs "不包含 Windows 更新的驅動程式")
