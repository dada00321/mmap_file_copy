透過 Linux 提供的記憶體映射函數: mmap，可將檔案（e.g., 文字檔）映射到虛擬記憶體，對「檔案-記憶體 對應(mapping, 映射)」做 read, write 等操作，而非直接操作文件本身。

主要還利用到了 memcpy() 做虛擬記憶體的 bytes copy。

此為作業系統課程的實驗二。主要是練習利用 perf 練習做系統程式(Linux kernel function) 的效能分析(profiling / performance analysis) 以及一拖拉庫指令並撰寫實驗報告。

因為看起來很有趣，於是把範例程式碼自己練習做了一遍。

