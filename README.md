## monitorInterview

##### 背景：秋招期间笔试面试太多了，记住这些时间过于繁琐又可能会忘记，比如最近的小米笔试在最后6分钟才想起来去做，还好有选择题可以混混分。

于是写了一个简易的脚本自用，得知一些面试变化之后，运行updateStatus.php脚本，按照顺序传入参数，选填的可以空格忽略，然后更新到数据库中。<br>
有一个定时脚本notice.php每天早上八点跑一次，统计数据库中所有人当天的笔面试情况，通过邮件发送通知。<br>
todo 还有一个分钟级的crontab，在笔面试开始前10分钟邮件提醒。<br>



