# Instances_Two_sided_ALBP1
Instances for two-sided assembly line balancing problem to minimize the number of mated-station and (or) the number of stations  
This project contains the utilized instances in [1] (in folder of Instances) which contain most of the instances in published papers. To gain a more in-depth and thorough understanding of this problem, interested authors are encouraged to refer to our relevant papers[1-7].  

Instances for cost-oriented two-sided assembly line balancing problem with given cycle time to minimize the cost  
This project contains the instances utilized in [8] (in folder of Instances_Cost_TALBP1). The operation times and precedence relations are taken from the instances in. To gain a more in-depth and thorough understanding of this problem, interested authors are encouraged to refer to our relevant papers[8].   

Results for Enhanced exact and heuristic methods for the type-I two-sided assembly line balancing problem  
This project contains the computational results reported in [9] (in folder of "Results in 10.1007s11081-025-10067-0"). The results are organized in two main subdirectories:

- **Comparative results/**: Contains Excel files (.xlsx) with comparative analysis between different methods, including:
  - Data transfer.xlsx: Data transfer formats and mappings
  - Results by BBR and BS.xlsx: Comparison of BBR (Branch, Bound and Remember) and BS (Branch and Bound) algorithms
  - Results by models.xlsx: Comparison of different mathematical programming models
  - Results by published methods and developed methods.xlsx: Comparison of published methods vs. newly developed methods
  - Results by re-impelmented methods and developed methods.xlsx: Comparison of re-implemented methods vs. newly developed methods

- **Detailed results/**: Contains text files (.txt) with detailed computational results for various algorithms and models, including:
  - BBR-*.txt: Results for Branch, Bound and Remember algorithm variants
  - BS-*.txt: Results for Branch and Bound algorithm variants
  - Proposed *.txt: Results for newly proposed algorithms
  - ABC*, GA*, PSO*, etc.: Results for various meta-heuristic algorithms
  - MPModel*, CPModel*: Results for mathematical programming models

Each text file contains tab-separated values with columns typically representing: number of mated-stations, number of stations, solution quality (e.g., cycle time), and computation time (in seconds). The suffixes (-30.txt, -180.txt, -300.txt) indicate different time limits (30, 180, 300 seconds) used during computation.


References  
[1] Zixiang Li, Qiuhua Tang, LiPing Zhang. Two-sided assembly line balancing problem of type I: Improvements, a simple algorithm and a comprehensive study. Computers & Operations Research, 2017, 79:78-93.  
[2] Qiuhua Tang, Zixiang Li, Liping Zhang, Xiaojun Cao, Shuangmei Zhang. Balancing Two-sided Assembly Line Using Particle Swarm Optimization algorithm. International Journal of Advancements in Computing Technology, 2014, 6(2):136-144.  
[3] Qiuhua Tang, Zixiang Li, L Zhang, CA Floudas. A hybrid particle swarm optimization algorithm for large-sized two-sided assembly line balancing problem. ICIC Express Letters, 2014:1-12.  
[4] Zixiang Li, Qiuhua Tang, L Zhang, Jin Hu. Balancing two-sided assembly line with a simple and effective iterated local search algorithm. ICIC Express Letters, 2015, 9:1-7.  
[5] Yi Wu, Qiu Hua Tang, Li Ping Zhang, Zi Xiang Li, Xiao Jun Cao. Solving Two–sided Assembly Line Balancing Problem via Gravitational Search Algorithm. Applied Mechanics and Materials, 2015, 697:450-455.  
[6] 李梓响, 唐秋华, 张利平, 郑鹏. 求解第Ⅰ类双边装配线平衡问题的改进离散人工蜂群算法. 计算机集成制造系统, 2016, 22(04):974-982.  
[7] Zixiang Li, Ibrahim Kucukkoc, Zikai Zhang. Branch, bound and remember algorithm for two-sided assembly line balancing problem. European Journal of Operational Research, 2020, 284:896-905.  
[8] Zixiang Li, Sadegh Niroomand, Ibrahim Kucukkoc. Mathematical formulation and meta-heuristic algorithms for cost-oriented two-sided assembly line balancing problem.  Proceedings of 11th International Symposium on Intelligent Manufacturing and Service Systems. IMSS’21 Sakarya University - Sakarya/Turkey (Online)2021. p. 98-107.  
[9] Z. Li, I. Kucukkoc, Y. Liu, Z. Zhang and L. Zhang. Enhanced exact and heuristic methods for the type-I two-sided assembly line balancing problem. Optimization and Engineering, 2026. DOI: 10.1007/s11081-025-10067-0. https://doi.org/10.1007/s11081-025-10067-0  



