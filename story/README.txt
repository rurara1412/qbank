好感度專屬故事的場景圖放這裡

1. 打開 SCENES.csv（用 Excel 或 Google 試算表開），每一列是一張要生成的圖。
2. 用其他 AI 依「場景描述」生成圖片，建議橫式 16:9（例如 1600×900），存成 JPG。
3. 檔名照第一欄，例如 qk15.jpg，放進這個 img/story 資料夾，上傳到 GitHub 的 img/story/。
4. App 讀到專屬故事時，會自動在故事開頭顯示這張圖；還沒放圖的故事，就不顯示，不會壞掉。
5. 新增故事後執行 node src/tools/make_scene_list.js，可以重新產生 SCENES.csv。
