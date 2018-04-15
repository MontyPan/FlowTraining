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


測試 table 左右置中功能。

|BBBBB	|AAA	|BBBB
|------:|:-----:|:------
|A	|B	|A	
|B	|A	|B	
|X	|X	|X	


______________________________________________________________________


Task-1.1 《請「試圖」解釋為什麼在那個時間點你沒有辦法發 PR 給我》
--------------------------------------------------------


我先在自己的 github 上 Create repository 而 repository name 是 FlowTraining
，之後要發 Pull requests 才找不到 MontyPan/FlowTraining。

因為是 Create repository，所以 fork 的人與 [FlowTraining](https://github.com/DontCareAbout/FlowTraining) 完全不一樣，才無法發給 MontyPan/FlowTraining。

假如 MontyPan fork 我的 FlowTraining 後，再更新我的 FlowTraining 就可以發 Pull requests 給 MontyPan。

最後發現 fork 有與自己相同的 repository name，會導致 fork 到自己 github 上的 repository name會最後加上 -1，此為實際測試的[結果](https://i.imgur.com/jwpBxj4.jpg)。

