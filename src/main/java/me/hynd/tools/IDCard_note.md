1.中国公民身份证常识：

我国现行使用公民身份证号码有两种尊循两个国家标准，〖GB 11643-1989〗和〖GB 11643-1999〗。

〖GB 11643-1989〗中规定的是15位身份证号码：排列顺序从左至右依次为：六位数字地址码，六位数字出生日期码，三位数字顺序码，其中出生日期码不包含世纪数。

〖GB 11643-1999〗中规定的是18位身份证号码：公民身份号码是特征组合码，由十七位数字本体码和一位数字校验码组成。排列顺序从左至右依次为：六位数字地址码，八位数字出生日期码，三位数字顺序码和一位数字校验码。



行政区划分代码：表示编码对象常住户口所在县(市、旗、区)的行政区划代码。

行政区划分代码【国家标准GB T 2260-1999】

   出生日期码：表示编码对象出生的年、月、日，其中年份用四位数字表示，年、月、日之间不用分隔符。

   顺序码：表示同一地址码所标识的区域范围内，对同年、同月、同日出生的人员编定的顺序号。顺序码的奇数分给男性，偶数分给女性。

<校验码：是根据前面十七位数字码，按照ISO 7064:1983.MOD 11-2校验码计算出来的检验码。

ISO 7064:1983.MOD 11-2校验码计算法

按照中华人民共和国国家标准GB11643-1999规定中华人民共和国公民身份号码校验码的计算方法即为ISO 7064:1983.MOD 11-2校验码计算法。

假设某一17位数字是

17位数字	1	2	3	4	5	6	7	8	9	0	1	2	3	4	5	6	7
加权因子	2	4	8	5	10	9	7	3	6	1	2	4	8	5	10	9	7
计算17位数字各位数字与对应的加权因子的乘积的和
S：1×2＋2×4＋3×8＋4×5＋5×10＋6×9＋7×7＋8×3＋
9×6＋0×1＋1×2＋2×4＋3×8＋4×5＋5×10＋6×9＋7×7＝492；
计算S÷11的余数T：492 mod 11＝8；
计算（12-T）÷11的余数R，如果R＝10，校验码为字母“X”；如果R≠10，校验码为数字“R”：（12-8）mod 11＝4。
该17位数字的校验码就是4，聚合在一为123456789012345674。