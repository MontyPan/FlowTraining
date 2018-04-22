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


[TestResult_img]:https://i.imgur.com/jwpBxj4.jpg
[listfork_ref]:https://help.github.com/articles/listing-the-forks-of-a-repository/


我先在 GitHub create repo 名稱是 FlowTraining，因為 create 是沒有來源，[fork 清單][listfork_ref]也沒有 MontyPan/FlowTraining，

而 MontyPan/FlowTraining 來源是 DontCareAbout/FlowTraining，而不是我的 FlowTraining，所以才無法發 Pull requests 給 MontyPan。

假如 MontyPan fork 我的 FlowTraining 後，再更新我的 FlowTraining 就可以發 Pull requests 給 MontyPan。

最後發現，如果 fork 一個自己（帳號下）已經有相同名稱的 repo，會導致 fork 的 repo 名稱尾端加上 -1 ，此為實際測試的[結果][TestResult_img]。
