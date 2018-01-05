### 4.9 非线性系统

　　尽管大多数实际系统是非线性的，但是线性理论有些惊人的特性对于控制系统分析和综合极其有用。在古典控制理论中，考虑非线性效应的必要性是众所周知的;引用Truxal (1955, p. viii) 的话:

>第五,设计师必须熟悉用来分析非线性系统的基本技术。设计师必须能够分析系统中不想要的非线性效应，并将非线性综合到系统中以提高动态性能。

　　他提到的典型非线性有摩擦、间隙、饱和滞后(Atherton,1975;Graham&McRuer,1961;Oldenburger, 1956)。非线性分析的近似法在非线性动力学中发展出来(Andronov et al., 1937; Krylov &Bogoliubov, 1937; Minorsky, 1962)。探索极限环的一种方法称为谐波平衡，包括研究一次谐波的传播，类似于线性系统的奈奎斯特分析方法。这个方法的一个版本被称为描述函数法(Kochenburger, 1959; Tustin, 1947a)。开关控制在控制早期比较流行，因为可以用简单的设备获得高增益；重要的理论也被开发出来(Flügge-Lotz, 1968; Tsypkin, 1949,1958, 1984)。

　　李雅普诺夫稳定性理论在苏联被广泛使用(Malkin, 1951)。该理论由卡尔曼和Bertram得到普及，他们借鉴了普林斯顿Lefschetz的想法，于是西方的许多相关研究受到了刺激。Krasovskii(1963)和LaSalle(1960)提供了一些有用的扩展。Willems表明，能量和耗散的概念与李雅普诺夫理论密切相关，并且发展了一套针对于耗散系统的理论(Willems, 1972)。李雅普诺夫理论现在广泛用于分析和设计(Freeman & Kokotovic, 2008)。Sontag和Wang (1995)引入的控制李雅普诺夫函数与输入状态稳定性概念被证明是有用的。Khalil的书(Khalil, 1992)是该领域一本受欢迎的标准教材。

　　无记忆非线性和线性系统反馈串接成的系统稳定性问题由Lurie和Postnikov (1944)提出。Aizerman猜想，如果非线性是扇区有界的，且线性系统对于扇区中的任何线性增益是稳定的，则闭环系统将是稳定的 (Aizerman,1949)。这个猜想是错误的，但却刺激了很多创造性的研究。最初问题是由李雅普诺夫理论解决的，但重要的突破却是由Popov做出的，他用对线性部分奈奎斯特曲线的约束给出了稳定性条件(Popov, 1973a,b)。Yakubovich(Yakubovic,1964)证明, Popov的结论可以表达和扩展成线性矩阵不等式形式(LMI)。

　　然而Sandberg（1964）和Zames（1964）在1964年的国家电子会议（National Electronics Conference）上展示了另一种稳定性。他们的报告后来付予详细出版(Sandberg, 1964, 1965; Zames, 1966a,b)。Zames专注于输入输出特性而避开了状态空间的概念。他从麻省理工学院的Singer那里借鉴了泛函分析，并引入了小增益定理和无源性定理。这些理论推广了线性系统中增益和相位的概念。这些想法得到了很多关注，并迅速成为控制理论核心的一部分(Desoer & Vidyasagar,1975; Vidyasagar, 1978)。

　　20世纪70年代该领域涌入了微分几何（Boothby，1975）的思想，导致了几何控制理论的发展。Brockett，Jurdjevic，Hermann，Krener，Lobry和Sussman是推动该研究进程的关键研究人员。他们研究了控制仿射非线性系统的能控性和能观性概念(Brockett, 1972, 1976; Haynes & Hermes, 1970; Hermann & Krener, 1977; Hermann, 1963; Krener, 1974; Lobry, 1970, 1974; Sussman & Jurdjevic, 1972);其判据基于李代数。非线性系统的可控性和可观性的概念被提出精炼为控制器(Brockett,1972,1976;Haynes&Hermes,1970;Hermann&Krener,1977; Hermann, 1963; Krener, 1974; Lobry, 1970, 1974; Sussman& Jurdjevic, 1972)。反馈线性化作为非线性系统设计的一种技术被引入(Hunt, Su, & Meyer, 1983)。Fliess使用微分代数来定义微分平坦的概念，后者变成了前馈和跟踪设计的有力方法(Fliess, Lévine,Martin, & Rouchon, 1975, 1992; Fliess, Lévine, Ollivier, & Rouchon,1995)。计算机代数用来计算李括号。Isidori和Byrnes引入了零动态的概念，推广了线性系统的零点(Isidori&Byrnes,1990)。几何控制理论有很多有趣的应用，如航天器姿态控制（Sidi，1997）、飞机大攻角飞行（Stengel＆Robert，2004，第7.4节）、拖车倒车（Fliess，Lévine和Martin ，1993）、步行机器人（Westervelt，Grizzle，Chevallereau，Choi，＆Morris，2007）和量子系统（Huang,Tarn,&Clark,1983;Khaneja,Brockett,&Glaser,2001）。几何控制理论是一些书中非线性控制理论的核心部分(Isidori, 1995; Nijmeijer & van der Schaft,1990)。
