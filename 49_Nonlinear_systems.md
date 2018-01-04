4.9非线性系统
尽管大多数实际系统是非线性的，但是线性理论有些令人惊讶的特性使得它对控制系统分析和综合极其有用。在古典控制理论中，考虑非线性效应的必要性是众所周知的;引用Truxal (1955, p. viii) :

第五,设计师必须熟悉用来分析非线性系统的基本技术。设计师必须能够分析系统中不想要的非线性效应，并将非线性综合到系统中以提高动态性能。
他提到的典型非线性有摩擦、间隙、饱和和滞后(Atherton,1975;Graham&McRuer,1961;Oldenburger, 1956)。
非线性分析的近似法在非线性动力学中发展出来(Andronov et al., 1937; Krylov &Bogoliubov, 1937; Minorsky, 1962)。探索极限环的一种方法称为谐波平衡，包括研究一次谐波的传播，类似于线性系统的奈奎斯特的分析方法。这个方法的一个版本被称为描述函数法(Kochenburger, 1959; Tustin, 1947a)。开关控制在控制早期比较流行，因为可以用简单的设备获得高增益；重要的理论也被开发出来(Flügge-Lotz, 1968; Tsypkin, 1949,1958, 1984)。

李雅普诺夫稳定性理论在苏联被广泛使用(Malkin, 1951)。该理论由卡尔曼和Bertram得到普及，他们捡起了普林斯顿Lefschetz的想法，于是西方的许多相关研究受到了刺激。Krasovskii(1963)和LaSalle(1960)提供了一些有用的扩展。Willems表明，能量和耗散的概念与李雅普诺夫理论密切相关，并且发展了一套针对于耗散系统的理论(Willems, 1972)。李雅谱诺夫理论现在广泛用于分析和设计(Freeman & Kokotovic, 2008)。Sontag和Wang (1995)引入的控制李雅谱诺夫函数与输入状态稳定性概念被证明是有用的。Khalil的书(Khalil, 1992)是该领域一本受欢迎的标准教材。

Lurie和Postnikov (1944)提出：系统的稳定性的问题可以通过无记忆非线性和线性反馈系统的反馈得到。Aizerman猜想如果非线性领域有界或象限的任何线性增益的线性系统稳定，则闭环系统是稳定的,如果 (Aizerman,1949)。这个猜想是错的但它激发了许多创造性的研究。最初的问题是Lyapunov理论引出,但一个主要接突破是由Popov提出,提供了一个稳定条件的限制的线性部分的奈奎斯特图(Popov, 1973a,b)。Yakubovich(Yakubovic,1964)表明, Popov的结果是可以表达和扩展的线性矩阵不等式(LMI)。
然而1964年还有Sandberg(1964) 和Zames (1964)在National Electronics Conference提出另一种方法确定稳定性。这份简报后来被详细刊登(Sandberg, 1964, 1965; Zames, 1966a,b)。Zames专注输入状态特性避开了状态空间的想法。他在MIT从Singer选出函数分析法，同时也提出小增益定理和钝化定理。这些内容描述了增益和相位对线性系统的概念。这些想法衍生了许多成果后来都变成了控制理论的核心内容(Desoer & Vidyasagar,1975; Vidyasagar, 1978)。
在1970年从微分几何学流入了一种想法使得几何控制理论得到发展。Brockett, Jurdjevic, Hermann, Krener, Lobry和 Sussman都是推动者个研究的关键成员。基于Lie algebra的准则，非线性系统的可控性和可观性的概念被提出精炼为控制器(Brockett,1972,1976;Haynes&Hermes,1970;Hermann&Krener,1977; Hermann, 1963; Krener, 1974; Lobry, 1970, 1974; Sussman& Jurdjevic, 1972)。回馈线性化做为设计非线性系统的技术被提出(Hunt, Su, & Meyer, 1983)。Fliess用微分代数来定义微分平滑的过程后来成为一种设计前馈器和跟随器的有力手段(Fliess, Lévine,Martin, & Rouchon, 1975, 1992; Fliess, Lévine, Ollivier, & Rouchon,1995)。计算机代数用来计算Lie brackets。Isidori和Byrnes针对现行系统的零点提出扩展zero dynamics(Isidori&Byrnes,1990)。几何控制学有许多有趣的应用，比如：宇宙飞船的姿态控制(Sidi, 1997)，飞行器高迎角飞行(Stengel & Robert, 2004, Section 7.4)，
拖车(Fliess,Lévine,&Martin,1993)，行走机器人(Westervelt,Grizzle, Chevallereau, Choi, & Morris, 2007)，和量子系统(Huang,Tarn,&Clark,1983;Khaneja,Brockett,&Glaser,2001)。几何控制理论是非线性控制的核心部分(Isidori, 1995; Nijmeijer & van der Schaft,1990)。
