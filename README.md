修正Stable Diffusion Forge Neo 的 Generate Forever 在背景停止
將檔案直接覆蓋舊檔，記得備份
共四個檔案
- /modules/shared_state.py
- /modules/call_queue.py
- /modules/progress.py
- /javascript/contextMenus.js
目前在 Generate Forever 過程中，不會接收修改的參數包含prompt，請 Cancel Generate Forever 後再重新 Generate 就可以了'
