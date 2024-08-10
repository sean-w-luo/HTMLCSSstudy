# vscode 和 github 的使用

VS code 和 github 连接的实例讲解：
【VSCode ☆ Git 】最佳代码管理 ➔ 高效且优雅
https://www.bilibili.com/video/BV1w14y1C7oi/?spm_id_from=333.337.search-card.all.click&vd_source=8ae83aab44e87f2c16dd05a8901bdac3

观看记录：综合案例（上）
https://www.bilibili.com/video/BV14J4114768/?p=30&spm_id_from=pageDriver&vd_source=8ae83aab44e87f2c16dd05a8901bdac3

为什么 VScode 的过程很慢？
提交的时候填写一下信息即可，这是 VScode 的一个 bug

VS code 上传代码到 github 的教程，参考链接：
https://blog.51cto.com/u_15715491/5464984

git clone （自己的 git 仓库地址 http 的）https://github.com/sunshinehu39/test.git

VScode 里面拉取(pull)并推送(push)提交是什么意思？可以单独提交吗？
拉取（‌Pull）‌：‌ 这个操作是从远程仓库获取最新的代码更改，‌ 并将其合并到本地分支中。‌ 在进行提交和推送之前，‌ 通常需要先执行拉取操作，‌ 以确保本地代码与远程仓库保持同步。‌ 拉取操作可以防止由于本地代码落后于远程仓库而导致的合并冲突。‌

推送（‌Push）‌：‌ 在本地进行了代码更改后，‌ 通过推送操作将这些更改上传到远程仓库。‌ 这样，‌ 其他开发者可以获取到你提交的更改，‌ 或者你可以分享你的代码给他人查看或使用。‌

关于是否可以单独提交，‌ 答案是可以的。‌ 在 VScode 中，‌ 你可以通过暂存更改并直接提交这些更改，‌ 而不必先进行拉取操作。‌ 但是，‌ 为了保持代码的一致性和避免合并冲突，‌ 建议在提交前先进行拉取操作，‌ 确保你的代码是最新的。‌ 这样做可以避免因为本地代码落后于远程仓库而导致的合并问题

Git pull 或 merge 遇到的一些问题：(You have not concluded your merge (MERGE_HEAD exists)) 1.需要先 commit。在 Android studio 的 VCS--- Commit Changes 或者 terminal 输入下面的指令:
git commit -m"commit info"。之后再 pull 或 merge 就可以顺利进行。 2.放弃本地修改，直接覆盖之
git reset --hard
git pull
参考链接：https://blog.csdn.net/qq_20801369/article/details/73290373

Github 仓库更改名字会影响上传吗？
https://blog.csdn.net/weixin_41287260/article/details/100545927
