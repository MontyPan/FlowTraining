《我在這個 task 中理解到的 git 是什麼東西》
=====================================


我的理解

*	專案版本控管工具。
*	可離線編輯版本，可以本機更新版本也可以恢復舊版資料。
*   透過 git branch 可以讓接下來的 commit 處於隔離（isolate）狀態。
    *	利用 git merge 合併 branch，讓專案開發穩定和多人同時開發。
*	可利用 git status 尚未提交的檔案 （[reference](https://zlargon.gitbooks.io/git-tutorial/content/file/status.html)）
    *   Changes to be committed 將要提交的檔案。
    *   Changes not staged for commit 指被更動但尚未提交的檔案。
    *   Untracked files 指完全新加入的檔案，不曾被提交過。
*	可利用 git log 觀察檔案屬性。
*	可修改上傳 origin master，也可以新增上傳 github。
*	可利用 git commit 簡介說明更新的主要目的。




姓名		|體育	|操性	|美術	|家政
:-------|:------|:------|:------|:----
黃大楷	|88		|80		|72		|65
陳小明	|80		|75		|65		|65
王小慧	|70		|90		|85		|85
徐小珠	|75		|85		|80		|75


______________________________________________________________________


Task-1.1 《請「試圖」解釋為什麼在那個時間點你沒有辦法發 PR 給我》
----------------------------------------------------------------


根據 Task_1.md 步驟，第一個步驟是 fork [FlowTraining](https://github.com/hybrid274/FlowTraining)，第二個步驟用 git clone 下載自己 github fork 出來的 FlowTraining。
第一個步驟我就做錯了，因為我沒有先 fork [FlowTraining](https://github.com/hybrid274/FlowTraining)，而是直接 git clone [FlowTraining](https://github.com/hybrid274/FlowTraining)。
上傳時我改了 origin master，因為無法上傳給 [FlowTraining](https://github.com/hybrid274/FlowTraining)，所以我直接改成我的 FlowTraining。
所以當要 pull request 時才沒有其他人的 fork。