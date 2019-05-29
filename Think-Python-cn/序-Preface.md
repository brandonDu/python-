# 神奇起源

1999年1月，我正计划用**Java**教一个班级编程入门，这门课程我教过三次，但我很沮丧。因为班级中很多人无法达标，即使有人成绩优秀，但是其总体成果并不好。

我注意到一个问题就是课本，这些课本/教案/书籍都太厚了，写了太多关于**Java**的不必要的细节，同时关于如何编程的架构指导写得也不全面。因此学生总是忍受一些痛苦轮回：起步容易，坎坷前进，半路迷失。学生学得囫囵吞枣，新知识太多，导致我不得不在后半学期不断回顾。

开学两周前，我决定自己写本书，我的目标如下：

- 少。对于学生来说，读10页很容易，50页很难。
- 精。我尽量精简专业术语，并在开始就明确术语。
- 缓。为了避免学习遇到突然的障碍，我将大部分有难度的跳跃切分成一系列的小步慢跑。
- 专。聚焦编程思想，而不是程序。_JAVA_ 代码能少就少。

我需要一个题目，莫名其妙就叫了 ***如何像计算机专家一样思考***。

第一版有点粗略，但是有效。学生们读了并且读懂了，所以我就能聚焦课堂时间于难题，趣题和实践。绝知此事要躬行，实践是必须的，也是最难而有趣的。

我基于*GNU Free Documentation License*(GNU自由文档许可证)发布本书，也就是说，任何人都可以基于此协议，复制，修改，分享本书。

后续的事情很酷了，一名叫*Jeff Elkner*的弗吉尼亚州的高校教师采用本书，并转成了*Python*。他发给我他的一个译本(Java To Python)， 我通过读自己的书，享受了一次不同寻常的*Python*学习之旅。作为绿茶出版社，我于2001年发布了第一个python版。

在2003年，我开始在欧林学院任职，并且首次教授*Python*。和教授*Java*相比，惊喜非凡，学生乐于学习并乐在其中。

过去九年，我持续不断地优化本书，校正错误，提高案例水准，并增加一些新的例子和练习。

因此，本书就有了个不太响亮的名字， *Think Python*。 修改如下：

- 每章结尾增加了调试部分。这些部分重点展示如何发现问题，避免错误，预防漏洞。
- 增加了一些练习。从简易小练习到项目实操，都有涉及，重点是，我写了大部分的解决办法。
- 增加了一系列的案例：涵盖练习-解答-讨论三个阶段的训练。部分案例采用*Swampy*(教学中使用的Python程序套件)，相关代码和解决方案请前往*http://www.thinkpython.com/*。
- 讨论了一些程序开发流程以及基础设计模式。
- 增加了调试，算法分析以及采用*Lumpy*进行UML绘图等附录部分。

希望本书对大家在如何编程，如何思考，至少像计算机专家一般思考方面有所裨益。

*Allen B. Downey*  
*Needham MA*

*Allen Downey*是富兰克林欧林工程学院的计算科学教授。

## 致谢

感谢*Jeff Elkner*把本书翻译为*Python*,并让我爱上了*Python*.

感谢*Chris Meyers*写了部分章节。

感谢创建GNU自由文档协议的自由软件基金会。由于此协议，我才能和*Jeff*， *Chris*一起合作。

感谢*Lulu*的编辑们。

感谢使用本书前期版本的学生们，感谢所有提出建议和修正错误的贡献者们(名单如下)。

## 贡献者名单

过去几年，一百多位聪明睿智，目光敏锐的读者为本书献策纠误。他们对本书的贡献以及热情，对本书意义非凡。

如果你有良好建议，或者发现问题，请发送邮件到*feedback@thinkpython.com*。如果你的建议被采纳，你将会被加入贡献者名单(除非要求匿名)。

希望你能最好附上错误的相关语句，这样我们能够快速定位，如果只有页数和章节，也有帮助，只是会不太容易确认，谢谢。

- *Lloyd Hugh Allen* 修正了8.4节的一处错误。
- *Yvon Boulianne* 修正了第5章的一处语义错误。
- *Fred Bremmer* 修正了2.1节的一处错误。
- *Jonah Cohen* 撰写Perl脚本，将本书LaTex源码转成了美观的HTML。
- *Michael Conlon* 修正了第2章的一处语法错误，以及优化第一章的一处格式，初次提出关于口译技术的讨论。
- *Benoit Girard* 修正了5.6节一个重大错误。
- *Courtney Gleason* 和 *Katherine Smith* 写了**horsebet.py**，这是本书早期版本的一个案例脚本，此程序现在仍然可以在网站找到。
- *Lee Harr* 修正了多个错误，所以应该把他列为主要编辑者。
- *James Kaylin* 作为学生，修正了大量错误。
- *David Kershaw* 修正了3.10节的 **catTwice**函数错误。
- *Eddie Lam* 修正了第1,2,3章大量错误，同时修复了Makefile文件，从而我们可以创建索引。同时帮助我们建立了版本库。
- *Man-Yong Lee* 修正了2.4节的一个样例。
- *David Mayo*指出第一章的某个词语(*unconsciously*)应该替换为*subconsciously*。
- *Chris McAloon* 修正了3.9和3.10节的错误。
- *Matthew J. Moelter*作为一个长期贡献者，为本书提供了大量修订和建议。
- *Simon Dicon Montford*发现了第3章的一个函数定义遗失和几个变量的命名错误。同时指出第13章的*increment*函数错误。
- *John Ouzts* 修正了第三章的 *"return value"* 的定义。
- *Kevin Parks*为本书的发行优化提供了宝贵的意见。
- *David Pool* 对本书给了善意的鼓励，并指出了第一章词汇表中的一个错字。
- *Michael Schmitt* 修正了文件和异常章节的一个错误。
- *Robin Shaw* 指出13.1节中，使用了没有预先定义的*printTime*函数。
- *Paul Sleigh* 指出了第7章的一个错误，以及*n Jonah Cohen* 的生成HTML的Prel脚本中的一个错误。 
- *Craig T. Snydal* 在 *Drew University* 使用本书教学，并给变量命名和修正提供了宝贵意见。
- *Ian Thomas* 和他的学生在编程课程中使用本书，他们是首批检验本书后半部分的贡献者，同时他们修订了大量错误，提供了大量建议。
- *Keith Verheyden* 修正了第3章的一个错误。
- *Peter Winstanley*指出了拉丁版第3章的一个长期存在的错误。
- *Chris Wrobel*修正了**I/O和异常**章节的一个错误。
- *Moshe Zadka*撰写了**字典**章节的早期草稿，为本书早期工作做出了杰出贡献。
- *Christoph Zwerschke*指出多个修正和教学建议，并解释了*gleich*和*selbe*的不同。
- *James Mayer* 修正了一堆拼写和排版问题，甚至包括贡献列表中的两个问题。
- *Hayden McAfee* 解决了一个在两个例子之间令人困惑的差异。
- *Angel Arnal*作为国际翻译组织的一员，参与了西班牙语的翻译，并在翻译过程中修正了英语版的一些错误。
- *Tauhidul Hoque* 和 *Lex Berezhny* 绘制了第一章的插图，并优化了其他章节插图。
- *Michele Alzetta* 博士修正了第8章的一个错误，并指出了**Fibonacci and Old Maid**案例的一些问题。
- *Andy Mitchell*指出了第1章的一个错字，第2章的一个错误例子。
- *Kalin Harvey*辨析了第7章的一个歧义，并修正了几个错字。
- *Christopher P. Smith*修正了错字，并给予Python2.2进行了修改。
- *David Hutchins* 修正了前言的一个错词。
- *Gregor Lingl*在奥地利的维也纳的一个高校教授Python，他翻译了德语版，并在翻译过程中，修正了第5章的多个错误。
- *Julie Peters* 修正了前言的一个错字。
- *Florin Oprina* 优化了 *makeTime*，修正了 *printTime*的错误，以及一个错字。
- *D. J. Webre* 辨析了第3章的一个歧义词。
- *Ken* 修正了8,9,11章的一堆错误。
- *Ivo Wever*修正了第3章的错字和第5章的歧义词。
- *Curtis Yanko* 辨析了第2章一个歧义。
- *Ben Logan* 修正了本书HTML版的大量错误。
- *Jason Armstrong* 发现第2章遗漏的一个词汇。
- *Louis Cordier* 指出了第16章的一个描述和代码不一致的问题。
- *Brian Cain*修正了第2,3章的数个错误。
- *Rob Black*修正了一系列错误，以及优化了Python2.2版部分内容。
- *Jean-Philippe Rey*[巴黎中央理工学院]针对Python2.2进行了部分优化。
- *Jason Mader*[乔治华盛顿大学]提供了大量修改意见。
- *Jan Gundtofte-Bruun* 指出 "a error" 是个错误。
- *Abel David* 和*Alexis Dinno*指出 "matrix" 的复数是 "matrices", 而部署 "matrixes"。这个错误存在多年，但是两人在同一天指出此错误，神奇啊！
- *Charles Thayer*建议我们在一些声明末尾勿用分号，以及避免使用"argument"和"parameter"。
- *Roger Sperberg*指出了第3章的一个逻辑问题。
- *Sam Bull*指出第2章的一处歧义表述。
- *Andrew Cheung* 修正了"use before def."的两个实例。
- *C. Corey Capel* 指出"调试的第三定律"章节的遗漏词汇，以及第4章的一个错词。
- *Alessandra*澄清了一些"Turtle"歧义。
- *Wim Champagne* 修正了字典例子中的一个"brain-o"错误。
- *Douglas Wright* 修正了 "arc" 中的一个"floor"错误。
- *Jared Spindor* 清理了数个画蛇添足。
- *Lin Peiheng*提供了多个建议。
- *Ray Hagtvedt* 修正了两个错误，提出一个优化。
- *Torsten Hübsch* 指出**Swampy**中的一处不一致。
- *Inga Petuhhov* 修正了第14章的一个案例问题。
- *Arne Babenhauserheide* 修正了数个错误。
- *Mark E. Casida* 敏锐发现了多个重复词汇。
- *Scott Tyler* 补充了一处遗漏词汇，并修正了大量错误。
- *Gordon Shephard* 多次发送邮件，指出错误。
- *Andrew Turner* 指出第8章的一处错误。
- *Adam Hobart* 修正了**arc**中的一处错误。
- *Daryl Hammond* 和 *Sarah Zimmerman*指出我太早使用 *math.pi* ， 同时 *Zim* 修正了一个拼写错误。
- *George Sass* 修复了*调试*一章的一处错误。
- *Brian Bingham* 提供了 11.10节的习题。
- *Leah Engelbert-Fenton* 指出我误用 *tuple*为变量名的问题，以至于发现大量类似问题(use before def.)。
- *Joe Funke* 指出一个拼写错误。
- *Chao-chao Chen* 指出 *Fibonacci* 例子中的一处不一致。
- *Jeff Paine* 指出了 *space* 和 *spam* 之间的不同。
- *Lubos Pintes* 指出了一处拼写错误。
- *Gregg Lind* 和 *Abigail Heithoff*提供了14.4节的习题。
- *Max Hailperin* 修正了大量错误，同时提供了大量建议。 *Max* 是 Concrete Abstractions 一书的作者之一，读完此书，你可以阅读这本非凡之作。
- *Chotipat Pornavalai* 修正了错误信息中的一处问题。
- *Stanislaw Antol* 提供了大量建议。
- *Eric Pashman* 修正了4-11章的大量错误。
- *Miguel Azevedo* 发现了多个拼写错误。
- *Jianhua Liu* 修正了大量错误。
- *Nick King* 发现了一处词汇遗漏。
- *Martin Zuther* 提供了大量建议。
- *Adam Zimmerman* 指出了 "instance"中的一处不一致问题，以及数个错误。
- *Ratnakar Tiwari* 提供了退化三角形说明脚注。
- *Anurag Goel* 提供了*is_abecedarian* 的另外一种方案，并修正了多个错误。同时他知晓如何拼写*Jane Austen*。
- *Kelli Kratzer* 指出了一处拼写错误。
- *Mark Griffiths* 澄清了第3章的一个令人困惑的案例。
- *Roydan Ongie* 指出了我的 "Newton"方法的一处错误。
- *Patryk Wolowiec* 修正了HTML版中的一个错误。
- *Mark Chonofsky* 让我知晓了Python3的一个关键字。
- *Russell Coleman* 让我增长了几何知识。
- *Wei Huang* 指出了数个排版错误。
- *Karen Barber* 指出了最早的一个拼写错误。
- *Nam Nguyen* 指出了一个拼写错误，并指出我用装饰器模式前，未有说明。
- *Stéphane Morin* 修正了数个错误，并提供了多个建议。
- *Paul Stoop* 修正了 *users_only* 中的一处拼写错误。
- *Eric Bronner* 指出了关于操作顺序的撰文中的一处歧义。
- *Alexandros Gezerlis*为他提交的建议数量和质量设定了新的标准，深表谢意。
- *Gray Thomas knows his right from his left.* 
- *Giovanni Escobar Sosa* 提供了大量修订。
- *Alix Etienne* 校正了一处*URL*错误。
- *Kuang He* 指出了一个拼写错误。
- *Daniel Neilson* 修正了操作顺序处的一个错误。
- *Will McGinnis* 指出 *polyline*在两处定义不同。
- *Swarup Sahoo* 修正了一处丢失分号错误。
- *Frank Hecker* 指出某个习题异于规定，同时发现了多个异常链接。
- *Animesh B* 澄清了一个令人困惑的案例。
- *Martin Caspersen* 发现两处四舍五入的错误。
- *Gregor Ulm* 提供多个修订和建议。
- *Dimitrios Tsirigkas* 建议我修正一个练习。
- *Carlos Tafur* 提供了大量修订和建议。
- *Martin Nordsletten* 发现了习题答案中的一处异常。
- *Lars O.D. Christensen* 指出某个参考已失效。
- *Victor Simeone* 发现一处拼写错误。
- *Sven Hoexter* 指出某处误用 *input* 这一内置函数。
- *Viet Le* 指出一处拼写错误。
- *Stephen Gregory* 指出 Python3 中的 *cmp* 的问题。
- *Matthew Shultz* 指出了一个失效链接。
- *Lokesh Kumar Makani* 指出多个失效链接，以及数个异常消息的修正。
- *Ishwar Bhat* 修订了关于费马大定理的描述。
- *Brian McGhie* 修正了一处歧义。
- *Andrea Zanella* 将此书翻译为意大利文，同时修正了多个错误。
