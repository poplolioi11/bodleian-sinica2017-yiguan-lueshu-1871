# 醫館略述 · Bodleian Sinica 2017

## 摘要 / Abstract

本資料以牛津大學 Bodleian Libraries 藏 Sinica 2017《醫館略述》（1871）為底本，供醫學史、醫療慈善史及傳教醫療史的原文檢索、來源定位與後續訂正。v0.2.0 比較獨立 AI 讀稿與固定初錄，再對 37 個目標物理面作非盲回圖裁定，包含 344 單位、5,089 個 Unicode 碼點。相較初錄有 90 單位變動或新增；保留 49 筆文字疑讀與 9 處來源範圍未解的殘墨區。公開 TXT、JSON、TEI XML 及訂正資料；本版未經人類全文雙校，變動與疑讀數量不是準確率。

This dataset supports medical-history, medical-charity and medical-missions research through a source-linked transcription of Yi guan lue shu (1871), Bodleian Libraries Sinica 2017. Version 0.2.0 compares independent AI readings with the frozen initial transcription and applies non-blind source adjudication across 37 target physical faces. It contains 344 units and 5,089 Unicode code points, with 90 changed or added units relative to the initial version. Forty-nine textual uncertainties and nine inspected residual-ink regions of unresolved extent remain. Public TXT, JSON, TEI XML and corrections support discovery and further revision. No human double collation has been performed; change and uncertainty counts are not accuracy estimates.

**v0.2.0｜獨立AI讀稿與非盲回圖修訂，保留未解。**

整理者：曲宸宇（Chu, Chen-Yu；GitHub：poplolioi11；[ORCID](https://orcid.org/0009-0003-9738-6914)）。本資料供歷史文字檢索、定位、引用及後續訂正。未驗證歷史醫館自述、金額或治療主張，未進行生物研究、實驗或現代操作指引整理。

館藏書目題名《醫館略述》，1871年，Serica地點[Foochow]。題頁本版暫錄「醫舘畧述」、紀年「同治十年孟冬」、歷史責任題署「大美國醫士柯爲樑校訂」，與書目題名分開保存；刊記及出版者未核，不推定英文姓名。

本版比較獨立AI讀稿及固定初錄，再作非盲原圖裁定。21幅官方影像、37個目標物理面，合計344單位、5089個Unicode碼點；90單位字串變動（含新增1、移除0單位）。29筆初錄疑讀各有處理，本版保留49筆字串內未解，另有9處已查看但性質及字數未定的魚尾下或頁邊殘墨區。這些數量不是錯字數或準確率。

全21幅固定影像已有獨立AI讀稿；非盲裁定針對37物理面完整裁片、版心及必要細節回圖，不把引用全幅來源等同每位裁定者均逐幅直接看過全圖。

獨立原稿分段與初錄不同，曾漏列p14一整欄；版心及附文另有遺漏、角色誤判與未解。另作36面版心原像素補讀，仍有無法辨清者；原始獨立及補讀輸出保留，不回填裁定字串。格式修復只修JSON結構，未改字串。

本版以21幀來源影像的37個目標物理面完成AI來源覆核與控制端整合，保留344個文字及附文單位、5,089個Unicode碼點；相對初錄有90個修改或新增單位（含新增1個序頁印頁碼）。原獨立稿的分欄、版心分類差異及p14整欄漏錄紀錄均保留，沒有將最終稿填回原獨立稿。

仍有49筆疑讀，另有9個已覆核但來源未解的區域；這9處的文字範圍均為unknown，沒有猜補字符或字數，也不改稱未處理頁面或空白。9區與49疑讀是不同計數。這是AI來源校讀紀錄，未經人類專家全文校定，不提供字形準確率或學術正確性認證。

p00題頁、p01序、p04原印版心、圖字／圖說及末段原印表列納入；圖面p22、p24、p29、p30。f01、f21的現代標記及攝影尺／色卡僅描述。折緣缺筆與罕字各處保留暫讀，不由題名或語意補齊。

- [TXT](book.txt)、[JSON](book.json)、[TEI](book.tei.xml)、[來源](source-pages.json)、[未解](uncertainties.json)。
- [訂正](CORRECTIONS.json)、[訂正說明](CORRECTIONS.md)、[校讀範圍](COLLATION.md)、[品質](QUALITY-AND-CONTRIBUTIONS.md)。
- [資料字典](DATA-DICTIONARY.md)、[讀者指南](READING-GUIDE.md)、[文字政策](TRANSCRIPTION-POLICY.md)、[驗證](VALIDATION.json)、[權利](RIGHTS.md)、[引用](CITATION.cff)。

獨立AI實際模型為gemini-3.8-flash-high；原生初錄及非盲裁定細分實際模型未知，保持null。未做人類全文雙校、專家審定、同儕審查或準確率量測。AI一致、疑讀數、hash、格式通過或DOI均不證明文字正確。 未公開掃描、裁片、專用程式、提示或完整私人工作紀錄，未提供由影像完整重跑的方法。

初錄[v0.1.0](https://doi.org/10.5281/zenodo.23874194)與固定檔、tag保留。本版內含已核公開初錄快照，不要再拼接為第二份正文。系列DOI：https://doi.org/10.5281/zenodo.23874193。v0.2.0已正式公開，GitHub／Zenodo共8次匿名檔案下載與固定發行bytes相同；31項公開狀態與metadata檢查通過。這些檢查不表示文字準確率。

2026-11-02有限查重：沿用同日既有有限查詞與公開索引原觀測，未找到可直接使用的本件完整文字／OCR／TEI或現代點校；這次封裝沒有新增搜尋。 不宣稱全球首錄。

## English summary

Independent AI reading of 21 official frames was compared with the frozen initial transcription, followed by non-blind source-image adjudication of 37 target physical faces. This version has 344 units, 5089 Unicode code points, 90 changed unit strings and 49 located unresolved records. Nine inspected residual-ink regions have unresolved text extent and origin. Changes and uncertainties are not error or accuracy estimates. Independent raw observations include omissions and unresolved paratext readings; their original outputs were retained. No human double collation, expert review, peer review or measured accuracy is claimed. This is historical-document digitization and publication without biological research or a modern procedural guide.

Keywords: 醫館略述; 醫館畧述; Sinica 2017; 醫學史; 醫療慈善史; 傳教醫療史; 福州; 晚清; 捐款名錄; 歷史醫療圖說; history of medicine; medical charity; medical missions history; Fuzhou; hospital reports; Chinese medical print culture; 1871; digital humanities; TEI XML.

已發布版本 DOI： https://doi.org/10.5281/zenodo.23874525
