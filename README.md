# Nesting Problem Short Survey
Just some articles that deal with nesting problem (Irregular Knapsack Problem)

<details>  
  <summary>
    <b>(Base Paper) Algorithms for nesting with defects </b> &emsp;<a  href="https://www.sciencedirect.com/science/article/pii/S0166218X12001308#:~:text=The%20nesting%20problem%20is%20an,master%20surface%20could%20contain%20defects."> Baldacci et. al. (2014)</a>
  </summary>
 <p align=justify>
  The nesting problem is an irregular two-dimensional cutting problem where the shapes of the pieces to cut and the master surfaces are irregular in shape and different in size. In particular, we consider nesting problems where the master surface could contain defects. Some of them can be accepted (i.e., incorporated) in certain types of pieces, while other defected areas must be avoided. The problems considered in this paper arise in the leather garment and furniture industry.
 </p>
  <p align=justify>
First, we solve nesting problems involving a single master surface (Irregular Single Knapsack Problem) for which we propose three different constructive (placement) procedures for the pieces. These procedures generate sets of cutting patterns, which are global configurations of the pieces, as sets on the master surface, and are included in an iterative algorithm motivated by a Lagrangean relaxation approach, where the Lagrangean dual seeds a Guided Local Search hybrid. Finally, we embed this iterative algorithm into a heuristic for solving the problem of cutting more than one master surface for producing all of the requested pieces, minimizing the total waste (Irregular Multiple Stock-Size Cutting Stock Problem).
</p>
  <p align=justify>
We test our algorithms on three sets of test problem instances. In order to validate the new heuristics for the nesting problem involving a single master surface we use a set of well-known irregular strip packing instances from the literature, where defects are not considered. The new heuristics for the nesting problem involving multiple master surfaces are then tested on a set of rectangular bin-packing instances and on a set of real-world instances obtained from leather garment and furniture industries with defects in the master surface.
</p>
</details>


## Scientific Tutorial 

<details>
<summary>
  <b>The geometry of nesting problems: A tutorial</b> &emsp;
  <a href="https://paginas.fe.up.pt/~balobo/PPExt/Papers/O09.pdf"> Bennell, Oliveira - (2008) </a>
</summary>
  <p align=justify>
Cutting and packing problems involving irregular shapes is an important problem variant with a wide variety of indus-
trial applications. Despite its relevance to industry, research publications are relatively low when compared to other cutting
and packing problems. One explanation offered is the perceived difficulty and substantial time investment of developing a
geometric tool box to assess computer generated solutions. In this paper we set out to provide a tutorial covering the core
geometric methodologies currently employed by researchers in cutting and packing of irregular shapes. The paper is not
designed to be an exhaustive survey of the literature but instead will draw on the literature to illustrate the theory and
implementation of the approaches. We aim to provide a sufficiently instructive description to equip new and current
researchers in the area to select the most appropriate methodology for their needs.
  </p>
</details>

<details>
  <summary>
      <b> A Tutorial in Irregular Shape Packing Problems </b> &emsp;
      <a href="https://www.jstor.org/stable/40206728"> Bennell, Oliveira - (2009) </a> 
  </summary>
  <p align=justify>
  Cutting and packing problems have been a core area of research for many decades. Irregular shape packing is one of the most recent variants to be widely researched and its history extends over 40 years. The evolution of solution approaches to this problem can be attributed to increased computer power and advances in geometric techniques as well as more sophisticated and insightful algorithm design. In this paper we will focus on the latter. Our aim is not to give a chronological account or an exhaustive review, but to draw on the literature to describe and evaluate the core approaches. Irregular packing is combinatorial and as a result solution methods are heuristic, save a few notable exceptions. We will explore different ways of representing the problem and mechanisms for moving between solutions. We will also propose where we see the future challenges for researchers in this area.
  </p>
</details>

## Surveys

<details>
  <summary>
    <b>Irregular packing problems: A review of mathematical models </b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221719303820">Leao, et. al. (2020)</a>
  </summary>
  <p align=justify>
  Irregular packing problems (also known as nesting problems) belong to the more general class of cutting and packing problems and consist of allocating a set of irregular and regular pieces to larger rectangular or irregular containers, while minimizing the waste of material or space. These problems combine the combinatorial hardness of cutting and packing problems with the computational difficulty of enforcing the geometric non-overlap and containment constraints. Unsurprisingly, nesting problems have been addressed, both in the scientific literature and in real-world applications, by means of heuristic and metaheuristic techniques. However, more recently a variety of mathematical models has been proposed for nesting problems. These models can be used either to provide optimal solutions for nesting problems or as the basis of heuristic approaches based on them (e.g. matheuristics). In both cases, better solutions are sought, with the natural economic and environmental positive impact. Different modeling options are proposed in the literature. We review these mathematical models under a common notation framework, allowing differences and similarities among them to be highlighted. Some insights on weaknesses and strengths are also provided. By building this structured review of mathematical models for nesting problems, research opportunities in the field are proposed.
  </p>
</details>

## Nesting problem
<details>
  <summary>
    <b>On genetic algorithms for shoe making nesting – A Taiwan case</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417407005192?via%3Dihub"> Yang, Ling - (2009) </a> 
  </summary>
  <p align=justify>
  This paper proposes a methodology that integrates in-house placement heuristics with genetic algorithms to solve the nesting problems of shoe making. The problems are classified as placing a set of irregular patterns on a regular area and limited to at most two different types of patterns on the area. Because of the intractability of the nesting problem, our objective is to utilize genetic algorithms’ fast convergence and solution quality to improve material utilization and reduce the calculation time of the pattern. Using the real-life data of two international brands of athletic shoes, the empirical results show that our proposed methodology can reduce average material requirements by 2.64% and average nesting time by 69.15% compared to those of current in-house software. The reduction of materials is becoming more important given that the industry is facing continuingly declining profit margins.
  </p>
</details>
<details>
  <summary>
    <b>Irregular Packing Using the Line and Arc No-Fit Polygon</b> &emsp;
    <a href="https://pubsonline.informs.org/doi/abs/10.1287/opre.1090.0770"> Burke et. al. - (2010) </a>
    
  </summary>
  <p align=justify>
  The no-fit polygon is a geometric construct that can offer faster and more efficient handling of geometry between pairs of shapes than traditional line-by-line intersection. The detection of intersections is a critical operation within the irregular two-dimensional stock-cutting problem (also known as “nesting”), which aims to place shapes onto sheets of material so that the material is utilised as efficiently as possible and the waste (or trim loss) is reduced. The problem forms an important process within many real-world manufacturing industries such as metalworking, automotive production, aerospace, clothing and conservatory manufacture, and others. If manufacturers can reduce their costs by utilising raw materials more effectively, this can directly translate into increased profit margins or greater competitiveness within the marketplace. Moreover, there are significant environmental benefits to be gained. Several methods have been proposed to calculate no-fit polygons, but most, if not all, can only operate on geometry that consists of line segments. This paper extends the orbital sliding method of calculating no-fit polygons to enable it to handle arcs and then shows the resultant no-fit polygons being utilised successfully on the two-dimensional irregular packing problem. As far as the authors are aware, this is the first time that a no-fit polygon algorithm has been able to handle arcs robustly without decomposing to their line approximations. The modification of the authors' previously published packing algorithm to utilise the proposed no-fit polygon approach yields solutions of excellent quality (including several best-known) on well-established literature benchmark problems after only a few minutes. The authors believe that the success of the packing strategy and the line and arc no-fit polygon algorithm make this approach a serious candidate for use in real-world production environments.
    </p>
</details>

<details>
  <summary>
    <b>New constructive algorithms for leather nesting in the automotive industry</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S030505481100253X"> Alves et. al. - (2012)</a>
  </summary>
  <p align=justify>
    In this paper, we address one of the hardest two-dimensional cutting stock problems that can be found in industry. The problem is called the Leather Nesting Problem, and it consists in finding the best layouts for a set of irregular shapes within large natural leather hides with highly irregular contours, and which may have holes and quality zones. Here, we focus on a real case from the automotive industry, and in particular on the production of car seats. In this case, the irregular shapes that have to be cut from the hides are pieces of the car seats.
  </p>
  <p align=justify>
The practical relevance of this problem, and the potential value of the savings that good solutions may generate, contrasts with the very small number of contributions that have been reported in the literature. In this paper, we aim to contribute to the efficient resolution of this problem by exploring in depth many new different constructive procedures. Our approaches rely on the computation of no-fit polygons, and try to use the information provided by these polygons as much as possible. Different strategies for sorting, selecting and placing the pieces, and for evaluating the placement of these pieces are proposed and discussed. We also report on an extensive set of computational experiments using real instances. To evaluate our approaches, we applied the real criteria used by companies operating in this sector. These experiments show that our approaches can generate very high quality layouts within the same time limits as those needed by human operators.
  </p>
</details>

<details>
  <summary>
    <b> A Variable Neighborhood Search Algorithm for the Leather Nesting Problem </b> &emsp;
    <a href="https://www.hindawi.com/journals/mpe/2012/254346/"> Alves, et. al - (2012)</a>
  </summary>
  <p align=justify>
    The leather nesting problem is a cutting and packing optimization problem that consists in finding the best layout for a set of irregular pieces within a natural leather hide with an irregular surface and contour. In this paper, we address a real application of this problem related to the production of car seats in the automotive industry. The high quality requirements imposed on these products combined with the heterogeneity of the leather hides make the problem very complex to solve in practice. Very few results are reported in the literature for the leather nesting problem. Furthermore, the majority of the approaches impose some additional constraints to the layouts related to the particular application that is considered. In this paper, we describe a variable neighborhood search algorithm for the general leather nesting problem. To evaluate the performance of our approaches, we conducted an extensive set of computational experiments on real instances. The results of these experiments are reported at the end of the paper.
  </p>
</details>

<details>
  <summary>
    <b>A branch & bound algorithm for cutting and packing irregularly shaped pieces</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0925527313001692">Alvares-Valdes, Martinez, Tamarit - (2013)</a>
  </summary>
  <p align=justify>
    Cutting and packing problems involving irregular shapes, usually known as Nesting Problems, are common in industries ranging from clothing and footwear to furniture and shipbuilding. Research publications on these problems are relatively scarce compared with other cutting and packing problems with rectangular shapes, and are focused mostly on heuristic approaches. In this paper we make a systematic study of the problem and develop an exact Branch & Bound Algorithm. The initial existing mixed integer formulations are reviewed, tested and used as a starting point to develop a new and more efficient formulation. We also study several branching strategies, lower bounds and procedures for fixing variables, reducing the size of the problem to be solved at each node. An extensive computational study allows us first to determine the best strategies to be used in the Branch & Bound Algorithm and then to explore its performance and limits. The results show that the algorithm is able to solve instances of up to 16 pieces to optimality.
  </p>
</details>

<details>
  <summary>
    <b> Efficient parts nesting schemes for improving stereolithography utilization </b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0010448512002783">Canellidis, Giannatsis, Dedoussis - (2013)</a>
  </summary>
  <p align=justify>
    In the present paper, the platform layout optimization problem for the simultaneous fabrication of different parts, which is addressed in the batch planning of Stereolithography Additive Manufacturing technology, is studied. The methodology proposed in the paper employs a Genetic Algorithm technique for the 2D nesting of parts on the platform of the stereolithography machine. The build orientation of the parts is assumed fixed and is decided prior to layout optimization, according to part-specific quality and cost requirements. Three placement schemes, appropriately adapted to the problem, are considered for the parts nesting and fabrication layout definition. The algorithms and placement schemes developed are evaluated in several test cases/benchmarks involving parts with both simple and complex geometries. The computational results included in the paper indicate that the proposed methodology can lead to satisfactory layout/packing–nesting arrangements in a time efficient manner, leading, therefore, to substantial improvement of stereolithography machine utilization.
  </p>
</details>

<details>
  <summary>
    <b> (State-of-the-art heuristic) A new approach for sheet nesting problem using guided cuckoo search and pairwise clustering  </b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221713005080">Elkeran - (2013)</a>
  </summary>
  <p align=justify>
    The nesting problem is commonly encountered in sheet metal, clothing and shoe-making industries. The nesting problem is a combinatorial optimization problem in which a given set of irregular polygons is required to be placed on a rectangular sheet. The objective is to minimize the length of the sheet while having all polygons inside the sheet without overlap. In this study, a methodology that hybridizes cuckoo search and guided local search optimization techniques is proposed.
  </p>
  <p align=justify>
To reduce the complexity of the nesting problem, pairwise clustering is introduced to group congruent polygons together in pairs. Pairwise clustering is done automatically to discover matched features among multiple present polygons. Computational experiments show that the implementation is robust and also reasonably fast. The proposed approach provides significantly better results than the previous state of the art on a wide range of benchmark data instances.
  </p>
</details>


<details>
  <summary>
    <b> The Dotted-Board Model: A new MIP model for nesting irregular shapes </b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0925527313001722">Toledo, et. al. - (2013)</a>
  </summary>
  <p align=justify>
    The nesting problem, also known as irregular packing problem, belongs to the generic class of cutting and packing (C&P) problems. It differs from other 2-D C&P problems in the irregular shape of the pieces. This paper proposes a new mixed-integer model in which binary decision variables are associated with each discrete point of the board (a dot) and with each piece type. It is much more flexible than previously proposed formulations and solves to optimality larger instances of the nesting problem, at the cost of having its precision dependent on board discretization. To date no results have been published concerning optimal solutions for nesting problems with more than 7 pieces. We ran computational experiments on 45 problem instances with the new model, solving to optimality 34 instances with a total number of pieces ranging from 16 to 56, depending on the number of piece types, grid resolution and the size of the board. A strong advantage of the model is its insensitivity to piece and board geometry, making it easy to extend to more complex problems such as non-convex boards, possibly with defects. Additionally, the number of binary variables does not depend on the total number of pieces but on the number of piece types, making the model particularly suitable for problems with few piece types. The discrete nature of the model requires a trade-off between grid resolution and problem size, as the number of binary variables grows with the square of the selected grid resolution and with board size.
  </p>
</details>

<details>
  <summary>
    <b> A Hybrid Methodology for Nesting Irregular Shapes: Case Study on a Textile Industry </b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S1474667016321590">Amaro Junior, Pinheiro, Saraiva - (2013)</a>
  </summary>
  <p align=justify>
    The aim of this paper is to describe a hybrid methodology that combines a Genetic Algorithm and a Bottom-Left Greedy procedure for solving the two-dimensional Nesting Problem. The No-Fit Polygon construct is applied for obtaining local optima. Furthermore, a shrinking algorithm is incorporated to the metaheuristic engine to identify good quality solutions. Computational experiments performed on standard benchmark problems, as well as a practical case study developed in a textile industry, are also reported and discussed here in a manner as to testify the potentialities behind the novel approach.
  </p>
</details>

<details>
  <summary>
    <b> Sequential optimization approach for nesting and cutting sequence in laser cutting</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0278612514000661">Sherif, Jawahar, Balamurali - (2014)</a>
  </summary>
  <p align=justify>
    The economy of the laser cutting process depends on two productivity issues: (i) nesting, a classic problem of finding the most efficient layout for cutting parts with minimum material waste; (ii) cutting sequence, which targets the optimal sequence of edges of the parts to be cut for minimum cycle time. This paper presents a two stage sequential optimization procedure for nesting and cutting sequence for the objectives of maximizing material utilization and minimization of ideal (non-cut) travel distance of laser cut tool. However, the focus of this paper is the development of solution technique for optimal cutting sequence to any given layout. Simulated annealing algorithm (SAA) is considered to evolve the optimal cutting sequence. The proposed SAA is illustrated with the optimal material utilization layout obtained using sheet cutting suite software, a professional rectangular nesting software package. The robust test carried out with five typical problems shows that the SAA proposed for cutting sequence is capable of providing near optimal solutions. The performance comparison with two literature problems reveals that the proposed SAA is able to give improved result than GA and ACO algorithms.
  </p>
</details>

<details>
  <summary>
    <b> A semi-continuous MIP model for the irregular strip packing problem </b> &emsp;
    <a href="https://www.tandfonline.com/doi/abs/10.1080/00207543.2015.1041571"> Leao et. al. - (2014) </a>
  </summary>
  <p align=justify>
    Solving nesting problems involves the waste minimisation in cutting processes, and therefore it is not only economically relevant for many industries but has also an important environmental impact, as the raw materials that are cut are usually a natural resource. However, very few exact approaches have been proposed in the literature for the nesting problem (also known as irregular packing problem), and the majority of the known approaches are heuristic algorithms, leading to suboptimal solutions. The few mathematical programming models known for this problem can be divided into discrete and continuous models, based on how the placement coordinates of the pieces to be cut are dealt with. In this paper, we propose an innovative semi-continuous mixed-integer programming model for two-dimensional cutting and packing problems with irregular shaped pieces. The model aims to exploit the advantages of the two previous classes of approaches and discretises the -axis while keeping the -coordinate continuous. The board can therefore be seen as a set of stripes. Computational results show that the model, when solved by a commercial solver, can deal with large problems and determine the optimal solution for smaller instances, but as it happens with discrete models, the optimal solution value depends on the discretisation step that is used.
  </p>
</details>

<details>
  <summary>
    <b>A random-key genetic algorithm for solving the nesting problem</b> &emsp;
    <a href="https://www.tandfonline.com/doi/abs/10.1080/0951192X.2015.1036522"> Pinheiro, Amaro Junior, Saraiva - (2061) </a>
  </summary>
  <p align=justify>
    This article presents a random-key genetic algorithm (RKGA) for the nesting problem, a particular case of cutting and packing problems in which a collection of items (or polygons) has to be packed onto a rectangular object with the aim of minimising its length. In general, our approach prescribes the integration of the aforementioned metaheuristic and well-known placement rules (e.g. bottom-left). Furthermore, a shrinking algorithm – that operates within the RKGA – is also proposed to improve partial solutions. To assess the potentials of the proposed methodology, computational experiments performed on a set of difficult benchmark instances of the nesting problem are discussed here for evaluation purposes, showing that our algorithm is able to compete with previous successful studies in some particular problem instances.
  </p>
</details>

[Martins, et. al. - (2016)](https://www.tandfonline.com/doi/full/10.1080/0951192X.2015.1033018?scroll=top&needAccess=true)

[Pinto, et. al - (2016)](https://www.inderscienceonline.com/doi/epdf/10.1504/IJBEX.2016.075594)

[Mundim, Andretta, Queiroz - (2017)](https://www.sciencedirect.com/science/article/abs/pii/S0957417417302233)

[Mundim et. al. - (2017)](https://www.tandfonline.com/doi/abs/10.1080/00207543.2017.1394598)

[Wang, Hanselman, Gounaris - (2018)](https://link.springer.com/article/10.1007/s10898-018-0637-y)

[Cherri et. al. - (2019)](https://www.sciencedirect.com/science/article/pii/S2214716019300594)

[Kierkosz, Luczak - (2019)](https://cejsh.icm.edu.pl/cejsh/element/bwmeta1.element.desklight-335f3bdb-e516-4d4f-a360-288a78635757)

[Amaro Junior, et al - (2020)](https://ieeexplore.ieee.org/abstract/document/9185794)

[Chehrazad, Roose, Wauters - (2022)](https://www.sciencedirect.com/science/article/abs/pii/S0377221721008936)

<details>
  <summary>
    <b> A study on GPU acceleration applied to 2D irregular packing problems </b> &emsp;
    <a href="https://www.tandfonline.com/doi/full/10.1080/0951192X.2022.2050302"> Sato, Martins, Tsuzuki - 2022  </a>
  </summary>
  <p align=justify>
   Irregular packing problems are an important subject of study in C&P problems. An efficient solution can have a great economic and environmental impact. The main objective is to obtain a feasible layout, a configuration whereby items are completely placed inside one or more containers without overlap. Although many solutions in the literature are capable of achieving high density solutions for benchmark instances, they are limited to small and medium problems. The best packing algorithms adopt the overlap minimization approach, in which the overlap restriction is relaxed by adopting an overlap function. Thus, a study of parallel implementation is proposed to accelerate the overlap minimization solution and reduce the processing time, potentially allowing for the solution of more complex instances. The results showed high speedups for the parallelization of the local search algorithm, achieving an acceleration of up to 16x. Then, by applying this accelerated method to a packing algorithm, speedups of up to 4.5 were observed. Due to their stochastic nature, the tests were repeated several times for each instance and the average results were computed. These results demonstrated the potential for GPU application with irregular packing, which can be extended to achieve its full capability.
  </p>
</details>

[Sato, et. al - (2023)](https://www.sciencedirect.com/science/article/abs/pii/S0957417423002178)

[Guo, et al - (2023)](https://www.sciencedirect.com/science/article/abs/pii/S0957417423010503)

[Nascimento, et al - (2024)](https://www.sciencedirect.com/science/article/pii/S0377221724001784)

## Strip packing

[Sato, Martins, Tsuzuki - (2012)](https://www.sciencedirect.com/science/article/abs/pii/S0010448512000565)

[Leung, Lin, Zhang - (2012)](https://www.sciencedirect.com/science/article/abs/pii/S0305054811001596)

[Shalaby, Kashkoush - (2013)](https://www.scirp.org/html/2-1040217_29233.htm)

[Cherry et. al. - (2016)](https://www.sciencedirect.com/science/article/abs/pii/S0377221716301370)

[Cherri, Carravilla, Toledo - (2016)](https://www.scielo.br/j/pope/a/DXgtyMFKv4KHqcQVw93W8LD/?lang=en#ModalTutors)

[Sato et al - (2016)](https://www.sciencedirect.com/science/article/pii/S2405896316328476)

[Rodrigues, Toledo - (2017)](https://www.tandfonline.com/doi/abs/10.1080/0951192X.2015.1036522)

[Amaro Junior, Pinheiro, Coelho - (2017)](https://www.hindawi.com/journals/mpe/2017/1670709/)

[Peralta, Andretta, Oliveira - (2018)](https://www.scielo.br/j/pope/a/DXgtyMFKv4KHqcQVw93W8LD/?lang=en#ModalTutors)

[Cherri, Cherri, Soler - (2018)](https://link.springer.com/article/10.1007/s10898-018-0638-x)

[Sato, et. al. - (2019)](https://www.sciencedirect.com/science/article/abs/pii/S0377221719304837)

[Oliveira, et. al. - (2020)](https://www.sciencedirect.com/science/article/abs/pii/S0360835220304721)

[Hu, Li, Cui - (2020)](https://ieeexplore.ieee.org/abstract/document/9093914)

[Rodrigues, Cherri - (2020)](https://www.itm-conferences.org/articles/itmconf/abs/2017/06/itmconf_apmod2017_00005/itmconf_apmod2017_00005.html)

[Leão, Toledo - (2021)](https://repositorio.usp.br/bitstreams/83b7bc41-fac2-413f-b6f7-deab749a57b7)

[Queiroz, Andretta - (2022)](https://onlinelibrary.wiley.com/doi/abs/10.1111/itor.13122) 

[Umetani, Murakami - (2022)](https://www.sciencedirect.com/science/article/pii/S0377221722002582)

[Kimms, Király - (2023)](https://www.sciencedirect.com/science/article/abs/pii/S0377221722006403)

[Rao, Luo - (2023)](https://link.springer.com/chapter/10.1007/978-981-19-5916-5_5)

[Lastra-Diàz, Ortuño - (2024)](https://www.sciencedirect.com/science/article/pii/S0377221723006148)

## Irregular shapes clustering
[Bennel et. al. - (2014)](https://link.springer.com/article/10.1007/s10898-014-0192-0)

## Irregular 2D Bin Packing 

[Yao et. al. (2024)](https://www.sciencedirect.com/science/article/abs/pii/S0305054823003404)

[Dalalah, Khrais, Bataineh (2014)](https://www.sciencedirect.com/science/article/abs/pii/S0278612513001209)

[Luo, Rao, Peng - (2022)](https://www.sciencedirect.com/science/article/abs/pii/S1568494621009716)

[Lopez-Camacho, Ochoa - (2013)](https://link.springer.com/article/10.1007/s10479-013-1341-4)

[Sykora, et. al - (2015)](https://www.sciencedirect.com/science/article/abs/pii/S0305048314001285)

[Stoyan, Zlotnik, Chugay - (2011)](https://www.tandfonline.com/doi/abs/10.1057/jors.2011.41)

[Santoro, Lemos - (2015)](https://link.springer.com/article/10.1007/s10479-015-1971-9)

[Zhang, et. al. - (2022)](https://www.sciencedirect.com/science/article/abs/pii/S0305054821002847)

[Abeysooriya, Bennell, Martinez-Sykora - (2018)](https://www.sciencedirect.com/science/article/abs/pii/S0925527317302980)

[Han et al. - (2013)](https://www.sciencedirect.com/science/article/abs/pii/S0377221713003627)

[Guerriero, Saccomanno - (2023)](https://link.springer.com/article/10.1007/s00500-022-07118-4)

[Benell, Cabo, Martinez-Sykora - (2018)](https://link.springer.com/article/10.1007/s00500-022-07118-4)

[Hu et al - (2018)](https://www.taylorfrancis.com/chapters/edit/10.1201/9781351236423-33/practical-algorithms-two-dimensional-packing-general-shapes-yannan-hu-hideki-hashimoto-shinji-imahori-mutsunori-yagiura)

[Rao, Wang, Luo - (2020)](https://www.hindawi.com/journals/mpe/2021/5054916/)

## Irregular cutting stock

[Xu (2016)](https://www.hindawi.com/journals/mpe/2016/8703782/)

[MirHassani, Bashirzadeh - (2015)](https://link.springer.com/article/10.1007/s00170-015-7107-1)

## Irregular Knapsack Problem

[Queiroz, Andretta, (2020)](https://www.sciencedirect.com/science/article/abs/pii/S1568494620304245)

[Del Valle, et. al. (2012)](https://www.sciencedirect.com/science/article/abs/pii/S0957417412007233)

[Luo, Rao - (2023)](https://www.sciencedirect.com/science/article/abs/pii/S0957417422024101)

##  Irregular 3D Packing Problem

[Zhao, Jiang, Teo - (2020)](https://www.aimsciences.org/article/id/1cac7d3a-9283-4f4d-90bb-add8fdfe811d)

## AI Approaches 

[Fang et. al. - (2023)](https://www.mdpi.com/2227-7390/11/2/327)

[Bartmeyer et. al. -(2022)](https://www.sciencedirect.com/science/article/abs/pii/S095741742201363X)

[Zhao, Hao, Fang - (2021)](https://iopscience.iop.org/article/10.1088/1742-6596/2181/1/012002/pdf) 
* Regular 2D strip packing

## Quantum Computing Approaches

[Matt, Roth - (2024)](https://arxiv.org/abs/2402.17542)

## Thesis
[AS Souza - (2016)](https://www.lume.ufrgs.br/handle/10183/142744)

[AM Sykora - (2009)](https://www.uv.es/marsyan/docs/thesis.pdf)

[I Luzzi - (2003)](https://www.dei.unipd.it/~fisch/ricop/tesi/tesi_dottorato_Luzzi_2003.pdf)

## Auxiliar algorithms 
### Non-fit polygon generation
[Cuninghame-Gree - (1989)](https://www.newscientist.com/article/mg12316773-700/)

[Berg et al. - (1997)](https://link.springer.com/book/10.1007/978-3-662-04245-8?utm_medium=referral&utm_source=google_books&utm_campaign=3_pier05_buy_print&utm_content=en_08082017)

[Luo, Hao - (2022)](https://www.mdpi.com/2227-7390/10/16/2941)
