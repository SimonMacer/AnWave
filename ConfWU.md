### Configure Windows Update for Business
===================================================

### 【AnWave】AnWave Windows Key-Point - Windows 設定選項管理器:https://github.com/SimonMacer/AnWave/discussions/9

### 【設定商務用 Windows Update】
![Configure Windows Update for Business](https://i.imgur.com/vvFMBti.png "Configure Windows Update for Business")

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

![停用 Windows 更新的驅動程式](https://i.imgur.com/oC9L8od.png "停用 Windows 更新的驅動程式")

### For Windows 10/11 家用版 (Home) - 停用【Windows Update 的驅動程式更新模組功能】以防止驅動程式被覆蓋

如果您安裝的 Windows 是家用版本 (Home)，那麼【不包含 Windows 更新的驅動程式】ExcludeWUDriversInQualityUpdate 原則設定可能沒有作用。您可以在 Windows Key-Point 中停用【Windows Update 的驅動程式更新模組功能】選項以在家用版 (Home) 上停止接收驅動程式更新。

如何停用?【設定商務用 Windows Update】標籤頁中的【接收驅動程式更新】>【Windows Update 的驅動程式更新模組功能】取消勾選狀態。

### For Windows 10/11 專業版 (Pro) 或更高級的版本 - 啟用【不包含 Windows 更新的驅動程式】原則設定以防止驅動程式被覆蓋
專業版 (Pro) 或更高級的版本適用【不包含 Windows 更新的驅動程式】ExcludeWUDriversInQualityUpdate 原則。
