# KnowledgeGraph v9.1 完整包（7z 分卷备份）

`D:\A\Ai_Work\knowledge-graph-v9-1-exe` 项目的完整分卷压缩备份。

- 源目录：3874 个文件夹 / 28819 个文件 / 878 MB（含 KnowledgeGraph.exe 主程序及全部依赖）
- 压缩后：12 个分卷，前 11 卷各 20 MB，末卷约 2.2 MB
- 压缩格式：7z（LZMA2）

## 恢复步骤

1. **下载全部 12 个分卷**（`.7z.001` ~ `.7z.012`），放到同一个文件夹里，文件名保持不变。
2. 确认 12 个文件齐全后，右键 `knowledge-graph-v9-1-exe.7z.001` → 7-Zip → 解压到当前位置；
   或命令行：
   ```
   7z x knowledge-graph-v9-1-exe.7z.001 -oD:\A\Ai_Work\restore
   ```
   7-Zip 会自动按顺序合并所有分卷。
3. 解压完成后得到完整的项目目录，运行其中的 `start.bat` 启动。

> 注意：分卷必须全部齐全才能解压，缺少任何一个分卷都无法恢复。
