> 本文件原有的 v0.2.0 校讀與數量敘述保留為歷史；本版 v0.2.1 的局部非盲覆核、現行數量及未解狀態見 [METHODS.md](METHODS.md) 與 [TARGETED-CORRECTIONS.md](TARGETED-CORRECTIONS.md)。

# v0.1.0至v0.2.0訂正

初錄DOI：https://doi.org/10.5281/zenodo.23874194。本版比較獨立AI讀稿及固定初錄，再作非盲原圖裁定。21幅官方影像、37個目標物理面，合計344單位、5089個Unicode碼點；90單位字串變動（含新增1、移除0單位）。29筆初錄疑讀各有處理，本版保留49筆字串內未解，另有9處已查看但性質及字數未定的魚尾下或頁邊殘墨區。這些數量不是錯字數或準確率。

CORRECTIONS.json的changes逐單位記before／after、reason、source及codepoint_edits。null表示相應版本尚無／已移除該單位，與空字串不同。source_review_decisions投影有記錄的來源裁定；initial_uncertainty_resolutions覆蓋29項原疑讀，其status可能仍未解，不因已處理而宣稱辨明。

source包含官方影像URL、canvas、SHA-256、幀、物理面、左右及unit ID；bbox=null。字元區間按Unicode碼點0起算半開區間[start,end)，不是bytes或字形群。codepoint_edits是機械對齊，不是新的讀字裁定。

字串內未解見uncertainties.json；另9處魚尾下或頁邊殘墨區見untranscribed_regions，字數及是否本面殘題／鄰葉透見未定，沒有虛加unit或一字占位。回報請附版本、unit ID或region ID、官方影像、讀法與理由；回報、採納及發版分開。舊版保留。未公開掃描、裁片、專用程式、提示或完整私人工作紀錄，未提供由影像完整重跑的方法。
