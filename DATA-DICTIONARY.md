# 資料字典

book.json為固定文字主本。pages[]依官方影像幀排列，page_id=fXX；unit ID開頭pXX指物理面，兩者不同於葉數。methods.physical_faces原樣保存初稿的物理面metadata、layout_note、running_title、printed_page_number及other_paratext；原稿units的order由陣列順序表示。initial_metadata保存原稿身分、階段、時間與worker聲明，不由封裝推定實際模型。

units[].layer固定original-print；role保留初稿layer。running_title、printed_page_number與other_paratext各投影為獨立unit；缺值不補。附文在原始unit後依running-title、printed-page-number、other_paratext陣列序排列；這是資料序，不表示附文紙面位置。side為全幅影像left/right，bbox=null。不同位置的相同印字串不自動去重。

本固定稿role統計：{"body": 194, "caption": 7, "colophon": 3, "diagram-label": 4, "paratext": 1, "preface": 20, "printed-page-number": 17, "running-title": 36, "section-running-title": 10, "small-note": 6, "table": 25, "title": 11, "版心序次": 2, "版心篇題": 7}。由同一固定稿計數，不預設欄數或角色數。

uncertainties以unit_id及Unicode碼點0起算半開區間[start,end)定位；surface須等於text[start:end]。extent=known只表示定位明確，不代表讀法已核。candidates與reason保留原稿，候選不替換正文。uncertainties.json展平並帶fXX page_id。

source-pages.json與pages[]一一對應，保存來源URL、canvas、固定影像hash與尺寸；images_redistributed=false。metrics.codepoints含空白與點號，不是漢字數。無疑讀不等於逐字確定。
