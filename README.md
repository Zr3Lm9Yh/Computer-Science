# Computer-Science
40p的内容，花了三天时间，总算看完了，难度的话还行，主要是为了入门，和对计算机科学相关的看法，先谢谢Carrie Anne生动形象的课堂，噗哈哈哈哈哈哈哈
再来谈谈看完后关于这个cs，的看法。
第一次了解cs的时候是在，嗯~ o(*￣▽￣*)o我想想哈，大概是在小学三年级(⊙﹏⊙)哈哈哈，那时候一直把cs叫做反恐精英，哈哈哈哈，ps，虽然那时候呢很快乐，不过呢，哎，也长大。
大概我是通过搜索cv（计算机视觉）的时候看到的这个课程，当时只看了1p，就被老师的幽默，和那个过场动画给吸引住了，哎，良心教育吖，好啦，话又说回来，谈谈自己的看法吧
其实贯穿整个40p内容的是time，时间，也可以说整个计算机产业随着时间的不断推移慢慢地过度到如今的人工智能时代，以前的计算机元件，从机械，再到继电器，再到真空管，最后过度到现如今广泛应用的晶体管，其实仔细细看整个计算机的发展，正如同机械革命，全民进入工业时代一样，我们真的进入到了互联网的时代。
关于课程，让我对计算机有更进一步的思考和了解，在以前的时候，计算的特点，以及电与磁相继出现，趋势这个产业向计算时代演变，由于电路有通路和闭路的特点，就导致了计算机会出现两种情况，0，1，而因为布尔代数理论的知识所起到的基础的支撑（布尔代数可以表示加减乘除的任何操作）使得计算就以二进制的方式展开，使得0，1，0，1变成了计算机正真能够看得懂的东西，也就是元件 的开与 闭，有了元件的开 与 闭之后呢，我们再通过不同元件之间花哨的组和，以及设计不同原件控制电流的方式就形成了逻辑与逻辑门，于是就有了非，与，或的操作，就可以计算位与位之间的与，当然了0和1之间的与，谁不会嘛，于是计算机会朝着更难的计算发展，比如8位加法器，我们知道8位，最大可以表示256，也就是2的8次方，这时候我们的算术逻辑单元alu就出现了，如果说，计算是一个抽象的过程，那个alu则就是逻辑门的更深的抽象，我们可以看到半加器是由一个and逻辑元件，与非或逻辑门构成的，全加器同理，也是由一个个逻辑门元件一个个构造出来的，最后在进行一次构造打包，并可以计算一字节的内容了，是不是很酷呢，如果逻辑门与逻辑门之间的构造越多，那么计算的量就越来越多，就可以计算更大的数学公示了
但又会出现一个新的问题，如何存储计算得到的数据呢，也就是那些01010101所保存的二进制数，这时候便来到了 寄存器与内存这一p，首先介绍的是AND-OR LATCH锁存器，这个逻辑原件呢是由一个or逻辑元件，和一个and，还有一个not逻辑元件构成的，大概的原理呢就是，额，我不知道形容电容器形象吗噗哈哈哈，诶，我去百度下电容器能不能做存储器，好像还可以，哈哈哈哈
，其实呢原理就是一堆组建嘛，然后把输入的01给锁住了，让它的输出也是01并继续作为输入，这样就是010101的不断循环，从而锁住了里面的内容，哈哈哈哈，我也不知道正不正确哈，然后这个的话，因为插上电才具有锁住电流的能力诶，把电断了的话，那么寄存器上的电流就不能够锁住了嘛，就像高中学的电容器一样噗哈哈哈，我真的是逻辑鬼才哈哈，好啦有了锁存器，和超级超级多的alu之后呢，我们的cup就要诞生了，不过呢cup要复杂多得多得多，它由alu和内存还有clock，当然了他的工作便是由control unit来进行调度的，嘻嘻嘻，再继续讲下去，就要涉及到计算机组成原理啦，哎，我还没看，当然课堂也有讲到，但感觉自己听的不是很懂诶，大概就是control unit发出指令到ram去取命令吗，还是什么诶，然后保存到寄存器里，去执行，这部分的内容建议多去看看中国大学mooc里的内容也许会有更好的idea，当然课堂也提到了高级cpu的设计，比如cpu的告诉的缓冲区cache的原理，和现在比较火的ai芯片的原理，其实就是分支预测技术，比如弹幕里有个比喻，就是你运行1000次的指令，那么继续运行下去的概率就很大，也就推测出你接下来的指令啦，不过cup这种东西还有多个cup同时处理，也就是多核cup
讲了处理之后呢，接下来就是将我们的存储方式的进化啦，你可以看到呢这样的存储方式显然是不能存储断了电了的数据的额，于是乎随着科技不断的进步，出现了以磁盘存储0，1，这样的话，可存的东西就变得很多，还有磁盘用来存储模拟信号，我们可以听到我们能听到的音乐啦。
接下来便是讲到我们，我入门cs的方式，也就是编程，首先的编程是从硬件层面编程开始的，也就是在cup呀，上面不是有操作指令吗，在哪哪哪，干什么去编程的，也提到了冯诺依曼的结构体系，一个cpu+数据寄存器+指令寄存器+指令地址寄存器+内存构成，也继续提到了编程语言的发展史，首先从最开始 的对硬件进行操作的机器语0101，到后来的汇编器的汇编语言，再到现在程序的高级程序编程语言，总是由下而上一层一层地往上进行封装，也就是我们再用python，再用c++时候，为什么这些操作，电脑能够明白你在干什么，然后讲到了算法，还有数据结构，这部分的内容呢可以移步到https://github.com/Zr3Lm9Yh/STL ，我为自己挖的坑。
然后就以图灵和软件工程的方式进行了过度，因为我们分为科学和工程嘛，软件工程偏向于工程的生产流程，就像前端，后端一样，将万维网的应用分布成流水线的方式，比如前端就要学习html，css，js，想让你网页在网上跑就要学习linux，以及配置环境，想让你的网页变得高级些就要学习mysql，php，具体到工程项目中我想也是这样的职能部门，不过对于我来说还是专心搞我的算法好啦，系哈哈哈~
接下来讲到了集成电路和摩尔定律，这个集成电路就很nb了，以前电脑都是一个庞然大物的存在，有了集成电路后，可以把很多东西焊接到板子里面，也可以自己设计主板，焊接不同的系统，当然这一切就像摩尔所预言的，因为集成电路上的元器件，越来越小，所以元器件的数量就会越来越多，但是总会有达到瓶颈的时候，我记得我第一次听到摩尔定律的概念的时候，是在中国大学mooc上看到一个学术研讨会，提到了摩尔定律，当时觉得这个好厉害哈哈哈，其实说白了，也就那么回事诶，再后来讲到了操作系统，毕竟要面向人类嘛，，以及文件管理系统，哈哈哈这个文件管理系统，让我知道了，原来文件目录只是一个索引，记录的是文件的起始地址，还有时间，删除的话，也并不是全部都删掉，而是空出等着被覆盖掉，而且呢，因为文件不是也要更新嘛，就可能导致溢出 的可能，所以采用的是碎片化的整理方式，这一章和下一章还是蛮收益匪浅的，下一章的话是压缩，我以前就在想压缩会不会导致文件损失呀，结果听了游程编码，和字典编码之后瞬间，灵光一闪，这不就是我要的算法嘛，具体的话，第一个算法就是将相同的颜色用数字存出现的第几次，而后面的字典编码就更牛了，现存个字典，也就是数字01和rgb颜色的对应关系，再利用数的结构存储进去
然后讲命令行界面，计算机是要面向人的嘛，就有了我一开始觉得linux很神奇，也很头痛的命令行，当然了，和元件的发展，存储的方式改变一样，最开始呢，是没有现在的命令行终端的，而是电传打印机，后来觉得有必要，毕竟为了方便嘛，就出现了我们经常在电影里看到，二战那种大tuotuo（二声）~机器终端，插一些发光的灯，一闪一闪的哈哈，后来出现了屏幕和2d，这里就引入了我以前觉得很神秘的显卡，其实呢就是计算机需要额外的硬件来从内存里读取出字符，并且转化位光栅图形的东西
后来就是一个过度，讲了冷战和消费注意，我觉得这部分的内容一定要好好研究呀，这个是时代下的计算机发展呐，也讲了个人计算机的革命，还有图形用户界面，哈哈哈我们的windows就脱颖而出啦，以及3d图形的算法原理，就是那些炫酷的渲染技术，哈哈哈，比如呢我们的照亮算法，纹理算法，大概思路就要用到一个超级超级重要的处理思想，就是处理多边形也就似乎那个三角形，当然了这些图像渲染算法很吃处理能力的，于是我们gpu就诞生了。
接下来就是讲我们上学期的内容，计算机网络，也就让我复习了一边哈哈哈，不过多出了三个章节，一个是计算机安全 ，还有和黑客与安全，还有加密与解密，这部分的内容大概在密码学里面的吧，好难诶，所以呐，计算机真的是一个交叉学科，也难怪清华大学的信息交叉学院的姚班这么牛逼，交叉呀，交叉呀!!!
然后就是我接下来继续挖坑的机器学习和人工智能啦，首先明白一点，机器学习是为了实现人工智能这个宏大目标的技术之一，其实目前我觉得，现阶段的机器学习，无非在两个方面进行，预测和分类，比如在数据挖掘方面，我们用机器人通过数据，进行分析，设定好参数，构造预测的函数，然后通过函数推测以后，将来的股票呀，房价呀，等金融方面的，我估计就往分类那边发展，也就是分类器，常见的应用包括人脸识别等等等，计算机视觉相关的，当然大部分的机器学习都用了统计学，我就比较牛逼，上来就学不是用统计学的——人工神经网路（为tensorflow挖坑呀，url以后补上）（；′д｀）ゞ
于是我们就来到了计算机视觉（也是我以后想从事的( ?? ω ?? )?），首先讲到了一个入门实验，物品颜色的跟踪，当然这个还是很好实现的，大不了一个一个像素块地从图片的左上角往右下角扫描就是了，直到rgb大概一致，或相似就框 出来，这个还是不难想出来的（但是写不出来呀{{{(>_<)}}}），然后介绍了，如何判别边缘化的东西，我们就用卷积的思想（为了卷积层神经网络挖坑），首先呢先构造一个过滤器，是一个3*3的一个数字矩阵，也叫它核，因为都知道图片嘛，无非就是像素*像素构成的，一个1080*1080的图片，就是1080个像素*1080像素的矩阵，每个像素有3个字节，大概24位，用来存放rgb三颜色，首先呢先用算法将图片变为黑白图，这个的话只需要把像素变成一位向量就可以了，后面两位跟，0，0，然后用核（也就是那个过滤器）从左上往右下风别相乘，注意细节来啦，那个核的参数是-1，-1，-1，0，0，0，1，1，1（sorry，这是个3*3的矩阵，实在不知道怎样编辑格式）与原来的左上到右下的9个像素块分别相乘，把值大于异常值的标记出来，这就是边缘部分，于是我们的无人飞机，无人汽车，就可以识别出啦啦哈哈哈，同理我们修图片需要锐化图片只需要把核（过滤器的参数改为）（-1，-1，-1，-1，9，-1，-1，-，-1，-1）即可，那些修图的算法，很多也可以这样修改哈哈哈哈，@滤镜
好，有了这个卷积的概念，于是接着就讲到了卷积神经网络了（Convolutional Neural Networks—CNN），第一步将图片，用上面的算法边缘化，把轮廓的部分分离出来，再通过权重找到边缘组成的角落，再继续卷积，直到识别了一个个简单物品的特征，比如鼻子，耳朵，嘴巴，然后把所有特征放到一起，传回一个答案，他是不是这个东西（如是不是脸），当然了，我还是比较看好以后的发展是以后计算机视觉来做出新的交互体验，比如VR直播（想想觉得特别炫酷，就不用买游戏了，哈哈5g也在上海落基站了嘛，重庆不知道要等多久），以后的电影要是有vr版，然后出一个，和小伙伴联机体验vr电影（来恐怖电影哈哈哈）想想都觉得特别nice，还有我还想到一个，以后前置摄像头让软件监控算了，摄像头就捕捉眼球，眼球向左划表示返回，向右滑表示翻页（哇，我简直就是科学家o((>ω< ))o）计算机视觉就写这么多，再然后就是涨知识的NLP（自然语言处理）我看了下视频，发现真的有点难，就快进着过了，不过这部分也超级超级有意思，这可是机器学习的又一个理论呀，比如Siri，Cortana，都是自然语言处理的超级超级牛的应用，是不是你眼前就有一个机器人浮现在你面前啦，它既会识别图片，认出你来，又会自然语言和你对话，哇，恐怖吗
确实恐怖，所以讲完了机器学习这个章节后，紧接着就是计算机心理学，其中讲到了我初中看到的恐怖谷定理呀呀呀(简直是我童年的阴影)当时初中的数学还是物理教材，有这个玩意，卧槽，真的可怕，后来其实想了想不也是计算机心理 的内容嘛，当机器人和人类有95相似的时候，人类往往是惧怕机器人的，但当过了这个点，人类慢慢就接受了机器人，说不定，以后赛博朋克，银翼杀手真的会出现(? ?_?)?，紧接着讲了关于计算机的教育科技（不说了这个在中国完全是黑洞产业，差钱的，建议了解下这个），最后是奇点，天网，计算机的未来，奇点的话就是智能科技的失控性发展（哈哈哈，我的理解就是机器人会生孩子了噗哈哈哈）然后提到了机器取代传统行业哎，当然能了计算机的未来不是我说了算的，我也不知道哈哈哈哈哈，不过还是好好学习吧，还要好好学习数据结构，毕竟是现代编程的基石诶
