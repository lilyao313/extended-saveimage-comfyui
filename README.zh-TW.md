# Extended Save Image for ComfyUI

這是一份由社群維護的 **Extended Save Image for ComfyUI** 保存版 / fork。原始專案作者為 **palant**。

我非常喜歡這個節點，因為它保持得很簡潔，沒有加入太多複雜的項目，只是單純提供儲存圖片時選擇格式的功能。也因為這份單純好用，我才想要保存一份副本。

原始儲存庫先前位於：

```text
https://github.com/palant/extended-saveimage-comfyui
```

原始儲存庫已由作者封存，目前為唯讀狀態，因此這份 fork 保存在這裡，供 ComfyUI 社群繼續使用。

## 這個節點的功能

這個自訂節點大致上與 ComfyUI 預設的 Save Image 節點相同，但額外支援將圖片儲存為：

- PNG
- JPEG
- WEBP 無損壓縮
- WEBP 有損壓縮

圖片中會照常嵌入 metadata，產生的圖片也可以用來載入 workflow。

## 這個 fork 的變更

與原始版本相比，這個 fork 包含以下變更：

- 支援在 `filename_prefix` 中替換日期 placeholder，包括：
  - `%Y-%m-%d`
  - `%date%`
  - `%date:yyyy-MM-dd%`

## 安裝方式

將這個儲存庫 clone 到你的 `ComfyUI/custom_nodes` 資料夾：

```bash
git clone https://github.com/lilyao313/extended-saveimage-comfyui
```

然後重新啟動 ComfyUI。

## 原作者標示

原始專案作者為 **palant**。

這個儲存庫是由 **lilyao313** 維護的保存版與修改版 fork。

如果原作者或貢獻者希望調整署名方式，歡迎開 issue 聯絡。

## 授權

本專案採用 GNU General Public License v3.0 授權。詳情請見 [LICENSE](LICENSE)。

這個 fork 保留原始的 GPLv3 授權，並標示原始版本發布後所做的修改。
