# ztime
一个新的十进制计时器

# 思路
每天分为10个小时，每小时100分钟，每分钟100秒。<br>
这样一天就总共100000秒。<br>
1个小时相当于目前标准时间的2.4小时。<br>
1分钟相当于目前标准时间的1.44分钟。<br>
1秒相当于目前标准时钟的0.864秒。<br>
比如标准时间的14:59:30，换算成Z时间，就大约是06:24:65。<br>

# 为什么会有这样的想法
虽然我们习惯了目前的计时方式。一天24小时，每小时60分钟，每分钟60秒。<br>
但是，有时候我还是会问，为啥秒到分是60进制，分到时是60进制，时到天又是24进制呢？<br>
这样的计时方式其实并不算很科学，比如任意给你一个时间，比如上面举例的14:59:30。<br>
你无法知道今天过去了多少秒，过去了多少分。虽然凭经验我们可以知道14:59:30大概是中午过后下午的某个时刻。<br>
但是如果我们的时间是这样的：06:24:65<br>
那么我可以直观地告诉你，今天总共过去了62465秒，现在是一天的第624分钟，整天已经过去62.4%了。<br>
当然，还有一个问题就是，我在跟我3岁的女儿讲时间的时候，发现很难跟她讲清楚一天的时间到底是怎么回事。<br>
那么，用Z时钟，会不会对小朋友更清楚一点呢？<br>
只能算是一种探索吧。<br>

# 实现
代码不是很多，任何人都可以直接下载src/ztime.html，用浏览器打开，就能看到当前的Z时钟时间了。