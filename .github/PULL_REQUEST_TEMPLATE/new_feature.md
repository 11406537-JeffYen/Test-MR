---

### 範例二：新功能/新平台擴充 new_feature.md (功能新增專用)
這個範本適合用在新增支援平台（例如引入新的 OCP 專案、San Miguel 平台支援）、新增測試參數或輔助函式時。

```markdown
## 🚀 New Feature / Platform Support

### Summary
- **目的：** - **新增項目：** - 

### Code Quality Check
- [ ] 現代化型別標註已清理 (Modern type annotations `dict | None`)
- [ ] 已移除所有不必要的 `pyre-fixme` 抑制註解
- [ ] 異常處理已使用明確的 `TestError` 代替不具名的 `Exception`

### Test Plan
1. **驗證步驟：**
2. **預期結果：**
3. **實際測試 Log 輸出：**
   ```text
   [在此貼上自動化測試成功的關鍵 Log]