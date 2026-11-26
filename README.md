# Game Patches & Traditional Chinese Localizations (繁體中文補丁／遊戲修正合集)

由 **DeepSeek-V4.1-Flash** 輔助翻譯製作的各類遊戲繁體中文翻譯與修正補丁合集。  
所有檔案僅包含翻譯腳本、外掛或介面修改檔，**不包含任何原版遊戲主程式、CG、音樂或影片檔案**，請自行準備原版遊戲。

> [!NOTE]
> - 部份作品含 **18+ / NSFW** 內容，請自行斟酌下載。
> - **類型說明**：
>   - **翻譯 (`Translation`)**：日文原版直接翻譯為繁體中文（`JP → TC`）
>   - **補丁 (`Patch`)**：既有補丁修正、功能調整或簡轉繁（`Fix / SC → TC`）
> - 翻譯與修正若發現錯漏或異常歡迎開 Issue 回報；詳細安裝方式請參閱各壓縮檔內的 `README.txt`。

---

## 📑 目錄 / Table of Contents

- [📦 補丁列表 / Patch List](#patch-list)
  - [ぎりギリLOVE](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E3%81%8E%E3%82%8A%E3%82%AE%E3%83%AALOVE) (`Translation`)
  - [この恋、5分で終わります。](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E3%81%93%E3%81%AE%E6%81%8B%E3%80%815%E5%88%86%E3%81%A7%E7%B5%82%E3%82%8F%E3%82%8A%E3%81%BE%E3%81%99%E3%80%82) (`Translation`)
  - [D.C.P.K.～ダ・カーポーカー～](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/D.C.P.K.%EF%BD%9E%E3%83%80%E3%83%BB%E3%82%AB%E3%83%BC%E3%83%9D%E3%83%BC%E3%82%AB%E3%83%BC%EF%BD%9E) (`Translation`)
  - [どっちにするのっ？- Never Only Sisters -](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E3%81%A9%E3%81%A3%E3%81%A1%E3%81%AB%E3%81%99%E3%82%8B%E3%81%AE%E3%81%A3NeverOnlySisters) (`Translation`)
  - [Four-leaf](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/Four-leaf) (`Patch`)
  - [Desire Flowers](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/DesireFlowers) (`Translation`)
  - [Stay. -Fragments of Memories-](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/StayFragmentsofMemories) (`Translation`)
  - [CircusLand I](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/CircusLandI) (`Translation`)
  - [神次元アイドル ネプテューヌPP](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E7%A5%9E%E6%AC%A1%E5%85%83%E3%82%A2%E3%82%A4%E3%83%89%E3%83%AB%E3%83%8D%E3%83%97%E3%83%86%E3%83%A5%E3%83%BC%E3%83%8CPP) (`Translation`)
- [🛠 通用說明 / General Notes](#general-notes)
- [⚠️ 免責聲明 / Disclaimer](#disclaimer)

---

<a id="patch-list"></a>
## 📦 補丁列表 / Patch List

點擊下方 **直接下載** 可立即下載 `.zip` 壓縮檔，或點擊 **Release** 查看發佈資訊。

| 遊戲名稱 | 類型 | 平台 / 引擎 | 補丁說明 | 下載連結 |
| :--- | :---: | :---: | :--- | :--- |
| **ぎりギリLOVE**<br>([VNDB](https://vndb.org/v6428)) | `Translation`<br>(日→繁中) | PC (`SVIU / CialloHook`) | 完整劇本與介面繁中化、透過 `CialloHook`（VFS 掛載＋Big5 `CP950` 轉碼＋`sviu_tc.1337` 執行期修補，不修改原檔）、支援於 `CialloHook.ini` 或遊戲內自由切換繁體字體與粗細縮放 | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/%E3%81%8E%E3%82%8A%E3%82%AE%E3%83%AALOVE/GIRILOVE_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E3%81%8E%E3%82%8A%E3%82%AE%E3%83%AALOVE) |
| **この恋、5分で終わります。**<br>([VNDB](https://vndb.org/v63577)) | `Translation`<br>(日→繁中) | PC (`TyranoScript / Electron`) | 全劇本（含 Good/Bad End）與系統介面繁中化、解包 `resources/app` 替換（原 `app.asar` 備份為 `.bak`）、內建按 `F2` 開啟繁體中文字體與字級樣式即時調整面板 | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/%E3%81%93%E3%81%AE%E6%81%8B%E3%80%815%E5%88%86%E3%81%A7%E7%B5%82%E3%82%8F%E3%82%8A%E3%81%BE%E3%81%99%E3%80%82/kono_koi_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E3%81%93%E3%81%AE%E6%81%8B%E3%80%815%E5%88%86%E3%81%A7%E7%B5%82%E3%82%8F%E3%82%8A%E3%81%BE%E3%81%99%E3%80%82) |
| **D.C.P.K.～ダ・カーポーカー～** | `Translation`<br>(日→繁中) | PC DVD (`DCPKDVD`) | 全劇本繁中化（25,005 框＋471 選項）、201 bytes EXE 差量修補（Big5 `CP950`＋免光碟）、本機建置專用字型（請勿用轉區工具啟動） | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/D.C.P.K.%EF%BD%9E%E3%83%80%E3%83%BB%E3%82%AB%E3%83%BC%E3%83%9D%E3%83%BC%E3%82%AB%E3%83%BC%EF%BD%9E/DCPK_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/D.C.P.K.%EF%BD%9E%E3%83%80%E3%83%BB%E3%82%AB%E3%83%BC%E3%83%9D%E3%83%BC%E3%82%AB%E3%83%BC%EF%BD%9E) |
| **どっちにするのっ？- Never Only Sisters -** | `Translation`<br>(日→繁中) | PC (`KiriKiri2`) | 完整劇本繁中化、粗體白字＋黑邊、開啟頂部選單列、新增 BGM 音量調整（需 Locale Emulator） | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/%E3%81%A9%E3%81%A3%E3%81%A1%E3%81%AB%E3%81%99%E3%82%8B%E3%81%AE%E3%81%A3NeverOnlySisters/NeverOnlySisters_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E3%81%A9%E3%81%A3%E3%81%A1%E3%81%AB%E3%81%99%E3%82%8B%E3%81%AE%E3%81%A3NeverOnlySisters) |
| **Four-leaf** | `Patch`<br>(簡→繁/修正) | PC (`YU-RIS`) | 簡轉繁修正補丁（基於 GPT-4o v1.0 補丁）：轉換 1,802 句對話、修復錯位壞行／空白、本機生成微軟正黑體 Bold 字型 | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/Four-leaf/Four_leaf_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/Four-leaf) |
| **Desire Flowers** | `Translation`<br>(日→繁中) | PC (`Unity / Utage`) | BepInEx 5 執行期繁中化＋內附 Noto Serif TC 字型（不修改原檔，測試版本 v1.1） | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/DesireFlowers/Desire_Flowers_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/DesireFlowers) |
| **Stay. -Fragments of Memories-** | `Translation`<br>(日→繁中) | PC | 主線劇本繁中化（基於英文補丁版修改，部分 UI 描述顯示異常） | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/StayFragmentsofMemories/Stay_Fragments_of_Memories_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/StayFragmentsofMemories) |
| **CircusLand I** | `Translation`<br>(日→繁中) | PC | 劇本繁中化與專用字體（少量 UI／文本漏翻，偶有崩潰請頻繁存檔） | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/CircusLandI/CircusLand_I_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/CircusLandI) |
| **神次元アイドル ネプテューヌPP** | `Translation`<br>(日→繁中) | PS Vita (`Vita3K`) | 日版 v1.01 (`PCSG00181`) 繁中化；Unlimited Live 若閃退請改用 OpenGL 後端 | [⬇ 直接下載](https://github.com/hyther1111/visual-novels-patches-tc/releases/download/%E7%A5%9E%E6%AC%A1%E5%85%83%E3%82%A2%E3%82%A4%E3%83%89%E3%83%AB%E3%83%8D%E3%83%97%E3%83%86%E3%83%A5%E3%83%BC%E3%83%8CPP/Hyperdimension_Neptunia_PP_TC_Patch.zip) · [Release](https://github.com/hyther1111/visual-novels-patches-tc/releases/tag/%E7%A5%9E%E6%AC%A1%E5%85%83%E3%82%A2%E3%82%A4%E3%83%89%E3%83%AB%E3%83%8D%E3%83%97%E3%83%86%E3%83%A5%E3%83%BC%E3%83%8CPP) |

---

<a id="general-notes"></a>
## 🛠 通用說明 / General Notes

1. **查看所有發佈版本**：前往 [Releases](https://github.com/hyther1111/visual-novels-patches-tc/releases) 頁面下載對應遊戲的 `.zip` 壓縮檔。
2. **備份原檔**：凡需覆蓋原版資料夾（如 `AdvData`、`gamedata`、`romdata`、`ysbin`、`resources/app.asar`）的補丁，安裝前請務必先備份原始檔案；僅外掛／附加封裝類（如 `patch.xp3`、`BepInEx`、`CialloHook`）則不會動到原版遊戲檔案。
3. **日文語系環境**：部分 KiriKiri2 舊作（如《どっちにするのっ？》）需搭配 **Locale Emulator**（日本地區）啟動執行檔；已改寫為 Big5 的補丁（如《D.C.P.K.》）則請直接啟動，勿使用轉區工具。

---

<a id="disclaimer"></a>
## ⚠️ 免責聲明 / Disclaimer

- 本儲存庫僅分享個人製作之翻譯與機能修正補丁，所有遊戲版權歸原開發商與發行商所有。
- 若權利方認為本專案侵害權益，請聯繫移除。
