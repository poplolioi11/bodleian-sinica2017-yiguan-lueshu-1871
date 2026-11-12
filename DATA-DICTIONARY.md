> 本文件原有的 v0.2.0 校讀與數量敘述保留為歷史；本版 v0.2.1 的局部非盲覆核、現行數量及未解狀態見 [METHODS.md](METHODS.md) 與 [TARGETED-CORRECTIONS.md](TARGETED-CORRECTIONS.md)。

# 資料字典

book.json為本版固定主文。pages[]按官方影像幀排列，page_id=fXX；unit ID開頭pXX為物理面，與葉數及原刻頁碼不同。units[].layer=original-print，role保留正文、圖字、表列、細註等角色。side為全幅影像left/right；bbox=null，無逐字座標。

running_title、printed_page_number與other_paratext各投影一次為獨立unit；附文排在該面主unit後，是資料序，不推定紙面座標。methods.physical_faces保存本版metadata與layout_note，不是第二份正文。

methods.initial_metadata是初錄歷史聲明；initial_canonical_snapshot保存完整已核公開初錄欄位及固定SHA/DOI，排除私人source_reading_records。snapshot不是本版正文。adjudicated_metadata及source_adjudication屬本版階段。

uncertainties以unit_id及Unicode碼點0起半開區間[start,end)定位，surface=text[start:end]；extent=known或located-unit僅指定位方式。候選不替換正文。uncertainties.json展平並帶fXX。角色實計：{"body": 194, "caption": 7, "colophon": 3, "diagram-label": 4, "paratext": 1, "preface": 20, "printed-page-number": 18, "running-title": 36, "section-running-title": 10, "small-note": 6, "table": 25, "title": 11, "版心序次": 2, "版心篇題": 7}。

untranscribed_regions另存已查看但未定性／未定字數的殘墨區，extent=unknown、character_count=null、text=null，沒有虛加文字單位。相同記錄亦見CORRECTIONS.json與TEI declared-methods快照；最小TEI未在body另造文字或gap字數。

CORRECTIONS.json保存字串前後、理由與來源。codepoints含空白及點號，不是漢字數；變動數及未解數不是錯誤率。
