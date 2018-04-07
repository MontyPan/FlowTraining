《我在這個 task 中理解到的 git 是什麼東西》
==========================================


我的理解

*	專案版本控管工具。
*	可離線編輯版本，可以本機更新版本也可以恢復舊版資料。。
*	可新增 branch，是為了上傳更新時不引響其他 branch([ref](https://backlog.com/git-tutorial/tw/stepup/stepup1_1.html))。
*	可利用 git status 看到那些檔案有變動，可以全部都更新也可以只更新部分檔案。
*	可利用 git log 觀察檔案屬性。
*	可修改上傳 origin master，也可以新增上傳 github。
*	可利用 git commit 簡介說明更新的主要目的。


|B	|A	|B	|
|------:|:-----:|:-----	|	
|A	|B	|A	|
|B	|A	|B	|
|X	|X	|X	|


______________________________________________________________________


Task-1.1 《請「試圖」解釋為什麼在那個時間點你沒有辦法發 PR 給我》
----------------------------------------------------------------


根據 Task_1.md 步驟，第一個步驟是 fork [FlowTraining](https://github.com/hybrid274/FlowTraining)，第二個步驟用 git clone 下載自己 github fork 出來的 FlowTraining。
第一個步驟我就做錯了，因為我沒有先 fork [FlowTraining](https://github.com/hybrid274/FlowTraining)，而是直接 git clone [FlowTraining](https://github.com/hybrid274/FlowTraining)。
上傳時我改了 origin master，因為無法上傳給 [FlowTraining](https://github.com/hybrid274/FlowTraining)，所以我直接改成我的 FlowTraining。
所以當要 pull request 時才沒有其他人的 fork。