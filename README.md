# Test01
用于测试的仓库

创建tag
git tag <tagname>

如果你想添加tag的描述，使用-a
git tag -a <tagname> -m "XXX..."

将tag推送到远程，使用以下命令：
git push origin --tags

推送refs / tags下的所有引用。
你如果只想推送单个tag:
git push origin <tag>
  
删除本地tag：
git tag -d <tagname>

删除远程tag：
git push origin :refs/tags/<tagname>
