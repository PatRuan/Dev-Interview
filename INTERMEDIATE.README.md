【笔试题】

请独立完成，其他注意事项见下方 FAQ。


请将完成的笔试题以“姓名-后端开发-完成所需时间“格式命名


【算法题】
要求：以下题目答题是 30 分钟,旨在考察面试者多方面的能力。请尽可能多答，

算法题可以任何编程语言的代码（欢迎加关键注释），也可以写出大概想法（得分会减少）。

题目：低谷元素查找

给你一个整数数组 nums，找到低谷元素并返回其索引。数组可能包含多个低谷，在这种情况下，返回任何一个低谷所在位置即可。

你可以假设 nums[-1] = nums[n] = +∞。

你必须实现时间复杂度为 O(log n) 的算法来解决此问题。

示例 1：

输入：nums = [1,2,1,3,5,6,4]
输出：2
解释：1 是低谷元素，你的函数应该返回其索引 2。
示例 2：

输入：nums = [6,5,4,3,2,3,2]
输出：4 或 6
解释：你的函数可以返回索引 4，其低谷元素为 2；
或者返回索引 6，其低谷元素为 2。
提示：

1 <= nums.length <= 1000
-2^31 <= nums[i] <= 2^31 - 1
对于所有有效的 i 都有 nums[i] != nums[i + 1]
代码写出算法，

并分析其时间复杂度，

为其编写尽量多 unit test。

【应用场景题】
要求：以下题目答题是 30 分钟,旨在考察面试者多方面的能力。请尽可能多答，
题目：电影院座位预订系统

假设你需要设计一个电影院座位预订系统，该系统需要处理两种类型的操作：

reserveSeat(row, seatNumber) - 预订指定行号和座位号的座位。
isAvailable(row, seatNumber) - 检查指定行号和座位号的座位是否可用。
电影院的座位按行和座位号组织，行号从1开始，座位号也从1开始。你需要实现这个座位预订系统，使得座位的预订和检查操作尽可能高效。

示例：

isAvailable(5, 8) -> True
reserveSeat(5, 8) -> 座位5排8号被预订
isAvailable(5, 8) -> False
要求：

假设电影院的座位数量和行数是已知的，且不会变化。
reserveSeat 操作和 isAvailable 操作需要尽可能地高效。
可以假设初始时所有座位都是可用的。

FAQ：

我可以上网吗？－－ 可以，make yourself comfortable。

我可以问别人吗？ －－ 请独立完成，if you lie , we’ll know sooner or later。

我超过 30 分钟怎么办？请尽量按时提交。如果超过 30 分钟，请标注下完成用时。

我做不完怎么办？没关系请尽量按点顺序完成


完成后，命名好邮件，请发PDF文档，发到邮箱：pat@footprint.network

