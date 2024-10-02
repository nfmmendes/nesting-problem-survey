# Nesting Problem Short Survey
Just some articles that deal with nesting problem (Irregular Packing Problem) and similar problems.

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

## Topics

<ul>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#scientific-tutorial">Scientific Tutorial </a> </li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#surveys">Surveys </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#nesting-problem"> Nesting problems </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#strip-packing"> Strip packing </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#irregular-shapes-clustering"> Irregular shapes clustering </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#irregular-2d-bin-packing"> Irregular 2d bin packing </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#irregular-cutting-stock"> Irregular cutting stock </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#irregular-knapsack-problem"> Irregular knapsack problem </a> </li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#irregular-3d-packing-problem"> Irregular 3d packing problem </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#ai-approaches"> AI approaches </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#quantum-computing-approaches"> Quantum computing approaches </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#thesis"> Thesis </a></li>
<li><a href="https://github.com/nfmmendes/nesting-problem-survey#auxiliar-algorithms"> Auxiliar algorithms </a></li>
</ul>

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
    <a href="https://www.tandfonline.com/doi/abs/10.1080/0951192X.2015.1036522"> Pinheiro, Amaro Junior, Saraiva - (2016) </a>
  </summary>
  <p align=justify>
    This article presents a random-key genetic algorithm (RKGA) for the nesting problem, a particular case of cutting and packing problems in which a collection of items (or polygons) has to be packed onto a rectangular object with the aim of minimising its length. In general, our approach prescribes the integration of the aforementioned metaheuristic and well-known placement rules (e.g. bottom-left). Furthermore, a shrinking algorithm – that operates within the RKGA – is also proposed to improve partial solutions. To assess the potentials of the proposed methodology, computational experiments performed on a set of difficult benchmark instances of the nesting problem are discussed here for evaluation purposes, showing that our algorithm is able to compete with previous successful studies in some particular problem instances.
  </p>
</details>

<details>
  <summary>
    <b>A pairwise exact placement algorithm for the irregular nesting problem </b> &emsp;
    <a href="https://www.tandfonline.com/doi/full/10.1080/0951192X.2015.1033018"> Sato, Martins, Tsuzuki - (2016) </a>
  </summary>
  <p align=justify>
    The irregular nesting problem, a subset of cutting and packing problems, aims to minimise waste or unoccupied space inside a container and is found in wood, glass, shipbuilding and textile industries. The problem consists in finding the most compact arrangement of two-dimensional items inside a rectangular container without overlap. The length of the container is variable and up to four different orientations are allowed for each item. Overlap is avoided by using a constructive placement heuristic which places items one at a time, without colliding with other items. The proposed algorithm in this work uses a pairwise placement strategy in which one item is always positioned in exact fitting or sliding placements, which are positions where the item movement is restricted. A simulated annealing algorithm controls the placement sequence and guides the search over the solution space. Several placement heuristics were proposed and tests were conducted with benchmark instances. Results show improvement in efficiency and speed over previous works in some cases.
  </p>
</details>

<details>
  <summary>
    <b>Heuristic methods for the leather nesting problem in the automotive industry</b> &emsp;
    <a href="https://www.inderscienceonline.com/doi/epdf/10.1504/IJBEX.2016.075594">  Pinto, et. al - (2016) </a>
  </summary>
  <p align=justify>
    In this paper, we address a real leather nesting problem (LNP) with holes and quality zones that arises in the automotive industry. We describe two approaches for the solution of the LNP. The first approach consists in a constructive heuristic, while the second relies on local search methods. The constructive heuristic is based on a simulation of the positioning of a piece so as to evaluate its fitness within the hide and within the current layout. The later approach suggested in this paper is based in a local search method whose neighbourhood structure operates on cutting patterns. In order to improve this procedure, we also describe an improvement of our constructive heuristic to apply it at each iteration of the local search procedure. The proposed methods were implemented and tested on real instances of the automotive industry. The obtained results for both heuristics illustrate the adequacy and the potential of the proposed approaches.
  </p>
</details>

<details>
  <summary>
    <b>A biased random key genetic algorithm for open dimension nesting problems using no-fit raster</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417417302233"> Mundim, Andretta, Queiroz - (2017) </a>
  </summary>
  <p align=justify>
    We consider two NP-hard open dimension nesting problems for which a set of items has to be packed without overlapping into a two-dimensional bin in order to minimize one or both dimensions of this bin. These problems are faced by real-life applications, such as textile, footwear and automotive industries. Therefore, there is a need for specialized systems to help in a decision making process. Bearing this in mind, we derive new concepts as the no-fit raster, which can be used to check overlapping between any two-dimensional generic-shaped items. We also use a biased random key genetic algorithm to determine the sequence in which items are packed. Once the sequence of items is determined, we propose two heuristics based on bottom-left moves and the no-fit raster concept, which are in turn used to arrange these items into the given bin observing the objective criteria. As far as we know, the problem with two-open dimensions is being solved for the first time in the context of nesting problems and we present the first whole quadratic model for this problem. Computational experiments conducted on benchmark instances from the literature (some from the textile industry and others including circles, convex, and non-convex polygons) show the competitiveness of the approaches developed as they were able to calculate the best results for 74.14% of the instances. It can be observed that these results show new directions in terms of solving nesting problems whereby approaches can be coupled in existing intelligent systems to support decision makers in this field.
  </p>
</details>

<details>
  <summary>
    <b>A general heuristic for two-dimensional nesting problems with limited-size containers</b> &emsp;
    <a href="https://www.tandfonline.com/doi/abs/10.1080/00207543.2017.1394598"> Mundim et. al. - (2017) </a>
  </summary>
  <p align=justify>
    Cutting raw-material into smaller parts is a fundamental phase of many production processes. These operations originate raw-material waste that can be minimised. These problems have a strong economic and ecological impact and their proper solving is essential to many sectors of the economy, such as the textile, footwear, automotive and shipbuilding industries, to mention only a few. Two-dimensional (2D) nesting problems, in particular, deal with the cutting of irregularly shaped pieces from a set of larger containers, so that either the waste is minimised or the value of the pieces actually cut from the containers is maximised. Despite the real-world practical relevance of these problems, very few approaches have been proposed capable of dealing with concrete characteristics that arise in practice. In this paper, we propose a new general heuristic (H4NP) for all 2D nesting problems with limited-size containers: the Placement problem, the Knapsack problem, the Cutting Stock problem, and the Bin Packing problem. Extensive computational experiments were run on a total of 1100 instances. H4NP obtained equal or better solutions for 73% of the instances for which there were previous results against which to compare, and new benchmarks are proposed.
  </p>
</details>


<details>
  <summary>
    <b>A customized branch-and-bound approach for irregular shape nesting</b> &emsp;
    <a href="https://link.springer.com/article/10.1007/s10898-018-0637-y"> Wang, Hanselman, Gounaris - (2018) </a>
  </summary>
  <p align=justify>
    We study the Nesting Problem, which aims to determine a configuration of a set of irregular shapes within a rectangular sheet of material of fixed width, such that no overlap among the shapes exists, and such that the length of the sheet is minimized. When both translation and rotation of the shapes are allowed, the problem can be formulated as a nonconvex quadratically constrained programming model that approximates each shape by a set of inscribed circles and enforces that circle pairs stemming from different shapes do not overlap. However, despite many recent advances in today’s global optimization solvers, solving this nonconvex model to guaranteed optimality remains extremely challenging even for the state-of-the-art codes. In this paper, we propose a customized branch-and-bound approach to address the Nesting Problem to guaranteed optimality. Our approach utilizes a novel branching scheme to deal with the reverse convex quadratic constraints in the quadratic model and incorporates a number of problem-specific algorithmic tweaks. Our computational studies on a suite of 64 benchmark instances demonstrate the customized algorithm’s effectiveness and competitiveness over the use of general-purpose global optimization solvers, including for the first time the ability to find global optimal nestings featuring five polygons under free rotation.
  </p>
</details>

<details>
  <summary>
    <b>Optimality in nesting problems: New constraint programming models and a new global constraint for non-overlap</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S2214716019300594"> Cherri et. al. - (2019) </a>
  </summary>
  <p align=justify>
    In two-dimensional nesting problems (irregular packing problems) small pieces with irregular shapes must be packed in large objects. A small number of exact methods have been proposed to solve nesting problems, typically focusing on a single problem variant, the strip packing problem. There are however several other variants of the nesting problem which were identified in the literature and are very relevant in the industry.
  </p>
  <p align=justify>
In this paper, constraint programming (CP) is used to model and solve all the variants of irregular cutting and packing problems proposed in the literature. Three approaches, which differ in the representation of the variable domains, in the way they deal with the core constraints and in the objective functions, are the basis for the three models proposed for each variant of the problem. The non-overlap among pieces, which must be enforced for all the problem variants, is guaranteed through the new global constraint NoOverlapin one of the proposed approaches.
  </p>
  
  <p align=justify>
Taking the benchmark instances for the strip-packing problem, new instances were generated for each problem variant. Extensive computational experiments were run with these problem instances from the literature to evaluate the performance of each approach applied to each problem variant. The models based on the global constraint NoOverlap performed consistently better for all variants due to the increased propagation and to the low memory usage.
  </p>

  <p align=justify>
The performance of the CP model for the strip packing problem with the global constraint NoOverlap was then compared with the Dotted Board with Rotations using larger instances from the literature. The experiments show that the CP model with global constraint NoOverlap can quickly find good quality solutions in shorter computational times even for large instances.
  </p>
</details>


<details>
  <summary>
    <b> A one-pass heuristic for nesting problems </b> &emsp;
    <a href="https://cejsh.icm.edu.pl/cejsh/element/bwmeta1.element.desklight-335f3bdb-e516-4d4f-a360-288a78635757"> Kierkosz, Luczak - (2019) </a>
  </summary>
  <p align=justify>
    A two-dimensional cutting (packing) problem with items of irregular shape and rectangular sheets is studied. Three types of problems are considered: single-sheet problems without restrictions on the number of elements, single-sheet problems with restrictions on the number of elements, and cutting stock problems (restricted number of items and unrestricted number of sheets). The aim of the optimization is to maximize the total area of the elements cut from a single plate or to minimize the number of sheets used in cutting. A one-pass algorithm is proposed which uses the popular concept of a no-fit polygon (NFP). The decision on whether an item is cut from a sheet in a given step depends on the value of a fitting function. The fitting function depends on the change in the NFP of individual items. We test eight different criteria for the evaluation of partial solutions. On the basis of numerical experiments, the algorithm that generates the best solution for each of the considered problem types is selected. The calculation results for these algorithms are compared with results obtained by other authors.
  </p>
</details>

<details>
  <summary>
    <b>A biased random-key genetic algorithm using dotted board model for solving two-dimensional irregular strip packing problems</b> &emsp;
    <a href="https://ieeexplore.ieee.org/abstract/document/9185794">  Amaro Junior et al - (2020) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem (ISPP) is a combinatorial optimisation problem that has applicability in several industrial processes since it aims for the efficient use of material. Most of the techniques reported in the literature for solving the ISPP employ metaheuristics as they can cope with complex requirements that prevent the use of exact model formulations. This paper presents a biased random-key genetic algorithm (BRKGA) that uses the dotted board model to compute the fitnesses of candidate solutions aiming for the minimisation of the height of the large object. The algorithm allows the pieces to rotate in order to achieve better layouts. Computational experiments using instances from the literature were conducted to demonstrate the efficiency of the proposed method, with promising results.
  </p>
</details>


<details>
  <summary>
    <b>A Genetic Algorithm for the Nesting Problem With Continuous Rotations</b> &emsp;
    <a href="https://ieeexplore.ieee.org/document/9504813">  Nunes, Moreira, Andretta - (2021) </a>
  </summary>
  <p align=justify>
   The Nesting problem, or the irregular cutting and packing problem, aims to find the best position of irregular pieces within a board, minimizing the space used by them. The problem's relevance is that it is widely used in the furniture, textile, and footwear industries. We consider a two-dimensional scope with convex and non-convex parts, with continuous rotation. We implement a genetic algorithm that uses five positioning rules, five sorting rules, and two rotation rules to create individuals and populations. Two positioning rules outperformed the others, obtaining promising results compared with the literature.
  </p>
</details>

<details>
  <summary>
    <b>A fast and scalable bottom-left-fill algorithm to solve nesting problems using a semi-discrete representation</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221721008936"> Chehrazad, Roose, Wauters - (2022) </a>
  </summary>
  <p align=justify>
    We present a fast algorithm to solve nesting problems based on a semi-discrete representation of both the 2D non-convex pieces and the strip. The pieces and the strip are represented by a set of equidistant vertical line segments. The discretization algorithm uses a sweep-line method and applies minimal extensions to the line segments of a piece to ensure that non-overlapping placement of the segments, representing two pieces, cannot cause overlap of the original pieces. We implemented a bottom-left-fill greedy placement procedure, using an optimised ordering of the segments overlap tests. The C++ implementation of our algorithm uses appropriate data structures that allow fast execution. It executes the bottom-left-fill algorithm for typical ESICUP data sets in a few milliseconds, even when rotation of the pieces is considered, and thus provides a suitable ‘building block’ for integration in metaheuristics. Moreover, we show that the algorithm scales well when the number of pieces increases.
  </p>
</details>

<details>
  <summary>
    <b> A study on GPU acceleration applied to 2D irregular packing problems </b> &emsp;
    <a href="https://www.tandfonline.com/doi/full/10.1080/0951192X.2022.2050302"> Sato, Martins, Tsuzuki - 2022  </a>
  </summary>
  <p align=justify>
   Irregular packing problems are an important subject of study in C&P problems. An efficient solution can have a great economic and environmental impact. The main objective is to obtain a feasible layout, a configuration whereby items are completely placed inside one or more containers without overlap. Although many solutions in the literature are capable of achieving high density solutions for benchmark instances, they are limited to small and medium problems. The best packing algorithms adopt the overlap minimization approach, in which the overlap restriction is relaxed by adopting an overlap function. Thus, a study of parallel implementation is proposed to accelerate the overlap minimization solution and reduce the processing time, potentially allowing for the solution of more complex instances. The results showed high speedups for the parallelization of the local search algorithm, achieving an acceleration of up to 16x. Then, by applying this accelerated method to a packing algorithm, speedups of up to 4.5 were observed. Due to their stochastic nature, the tests were repeated several times for each instance and the average results were computed. These results demonstrated the potential for GPU application with irregular packing, which can be extended to achieve its full capability.
  </p>
</details>

<details>
  <summary>
    <b>A separation and compaction algorithm for the two-open dimension nesting problem using penetration-fit raster and obstruction map</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417423002178"> Sato, et. al. - (2023)  </a>
  </summary>
  <p align=justify>
    Nesting Problems, which are important subjects in the cutting and packing field, involve convex and nonconvex polygons and are common in several industries. These irregular open dimensional problems have been studied for decades, particularly the variant with one open dimension. However, in real-world applications, situations that are better suited to a two open dimensional model may arise and, in this sense, the literature is very limited. We here propose new separation and compaction algorithms for two-open dimension nesting problem. The paper develops an adaptation of the no-fit polygon to consider the penetration depth of pieces. The approach is based on an iterative compaction scheme, in which the key step is an obstruction map-based separation algorithm. The algorithms proposed found optimal solutions for artificial instances with up to 28 items within a small runtime. The results of benchmark instances indicate that the new algorithm is competitive when compared with other literature algorithms. It improved 14 of 15 benchmark instances when considering literature approaches on two open dimensions. In addition, the new algorithm achieved better occupation for some open dimension instances than the state of the art.
  </p>
</details>

<details>
  <summary>
    <b>Efficient 2D irregular layout by vector superposition NFP and mixed-integer programming</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417423010503"> Guo, et al - (2023)  </a>
  </summary>
  <p align=justify>
    As a typical combinatorial optimization problem, two-dimensional (2D) irregular layout is a common problem in the engineering field. No-fit polygon (NFP) is a common geometric tool for solving layout problems. Although it is necessary to calculate NFP frequently in the process of layout, the search efficiency of the NFP generation algorithm is affected. The existing unfitting polygon algorithms have difficulties in dealing with complex contours, especially irregular contours with cavities. The large-scale layout process takes the long time with the low material utilization. A vector superposition NFP (VS-NFP) method is proposed in this paper to improve the solution efficiency of 2D irregular layout problems with complex contours. Based on the VS-NFP, an improved mixed integer programming (MIP) model is built. The model increases compression constraints for high solution search efficiency. A hybrid algorithm based on the VS-NFP and MIP is proposed to solve the problem. Comparing with the existing methods, the proposed method shortens the search time and improves the material utilization. The proposed method is verified in the application of large-scale layout problems.
  </p>
</details>

<details>
  <summary>
    <b>Repair Method and Muéganos Structure Applied to the Nesting Problem in Finite Materials</b> &emsp;
    <a href="https://www.mdpi.com/2076-3417/13/18/10117"> Rodriguez, Cuevas, Esparza - (2023)  </a>
  </summary>
  <p align=justify>
    During an optimization process which uses a metaheuristic strategy applied to the nesting problem, it is required to apply a repair method if the random solution contains overlapping items. In this paper, a repair method is proposed to avoid the overlap of pixels between items obtained by a randomly generated solution using metaheuristics. The proposed procedure runs through each one of the items. When it finds at least one overlapping pixel, it performs four moves: up, down, left, and right, and it is repeated until no more overlaps appear. In addition, a structure called muéganos is defined. It contains items that are nested more compactly to minimize waste. This structure allows the nesting of elements in a more efficient way. To complete the procedure, a sequential greedy algorithm (SGA) was implemented to nested the items in the available area of the material. A comparison was made between nesting without and with muéganos, obtaining better results using muéganos, with a material utilization of more than 70%. From the experimental results, it was obtained that the solutions are improved by more than 1% through our proposed method, which is competitive when compared to other methods proposed in the literature.
  </p>
</details>

<details>
  <summary>
    <b>Optimal decomposition approach for solving large nesting and scheduling problems of additive manufacturing systems</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S0377221724001784">  Nascimento, et al - (2024) </a>
  </summary>
  <p align=justify>
    This paper addresses the challenges associated with nesting and production scheduling in additive manufacturing (AM). The problem studied consists of grouping a set of parts into batches, which are then assigned to and sequenced across the available machines, guaranteeing the production of all parts. This work stands out by proposing exact methods for the AM nesting and scheduling problem considering irregular-shaped parts with specific release dates, processing times, and due dates, with the aim of minimizing the cumulative tardiness. The proposed approaches include two logic-based Benders decompositions: one combining Mixed Integer Programming (MIP) and Constraint Programming (CP), and the other relying solely on CP. To deal with the sub-problems, a strategic procedure was developed to reduce the solution space while maintaining low resolution times per iteration. Problem-specific cuts are also generated to improve the efficiency of these approaches. Computational experiments show that both decompositions significantly outperform a prior monolithic CP model, with the decomposition based solely on CP yielding the best results. Moreover, the results show that this approach has the potential to achieve similar computational performance of non-exact approaches that are currently considered state-of-the-art. A set of instances is provided to serve as a benchmark for future studies.
  </p>
</details>

<details>
  <summary>
    <b>An Iterative Compression Method for the Two-Dimensional Irregular Packing Problem With Lead Lines</b> &emsp;
    <a href="https://ieeexplore.ieee.org/abstract/document/10621026"> Tang et. al. - (2024) </a>
  </summary>
  <p align=justify>
    In industry, cutting various irregular pieces from a large raw material plate of a given size is often necessary to minimize the number of raw material sheets used. This problem is known as the two-dimensional irregular bin packing problem (2DIBPP). An iterative compression algorithm is proposed to address the irregular packing problem in the sheet metal industry, considering lead lines to maximize raw material sheet utilization. Firstly, three methods of lead lines pre-processing are proposed to effectively transform lead lines constraints into non-overlapping constraints between pieces. Secondly, an improved greedy heuristic, incorporating the sticking-edge and insertion-space strategies, is designed to obtain an initial solution for compact packing. Finally, through the iterative compression strategy, the occupied space of the pieces is continuously contracted to further enhance raw material sheet utilization. The efficiency of the proposed algorithms is demonstrated through testing and analysis of real-world instances from industry. The lead lines processing strategy and algorithm presented in this paper effectively resolve the irregular packing problem associated with lead lines, demonstrating their utility in industrial production.
  </p>
</details>


## Strip packing

<details>
  <summary>
    <b>An algorithm for the strip packing problem using collision free region and exact fitting placement</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0010448512000565"> Sato, Martins, Tsuzuki - (2012) </a>
  </summary>
  <p align=justify>
    The irregular shape packing problem is approached. The container has a fixed width and an open dimension to be minimized. The proposed algorithm constructively creates the solution using an ordered list of items and a placement heuristic. Simulated annealing is the adopted metaheuristic to solve the optimization problem. A two-level algorithm is used to minimize the open dimension of the container. To ensure feasible layouts, the concept of collision free region is used. A collision free region represents all possible translations for an item to be placed and may be degenerated. For a moving item, the proposed placement heuristic detects the presence of exact fits (when the item is fully constrained by its surroundings) and exact slides (when the item position is constrained in all but one direction). The relevance of these positions is analyzed and a new placement heuristic is proposed. Computational comparisons on benchmark problems show that the proposed algorithm generated highly competitive solutions. Moreover, our algorithm updated some best known results.
  </p>
</details>

<details>
  <summary>
    <b>Extended local search algorithm based on nonlinear programming for two-dimensional irregular strip packing problem</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0305054811001596"> Leung, Lin, Zhang - (2012) </a>
  </summary>
  <p align=justify>
    This paper presents an extended local search algorithm (ELS) for the irregular strip packing problem. It adopts two neighborhoods, swapping two given polygons in a placement and placing one polygon into a new position. The local search algorithm is used to minimize the overlap on the basis of the neighborhoods mentioned above and the unconstrained nonlinear programming model is adopted to further minimize the overlap during the search process. Moreover, the tabu search algorithm is used to avoid local minima, and a compact algorithm is presented to improve the result. The results of standard test instances indicate that when compared with other existing algorithms, the presented algorithm does not only show some signs of competitive power but also updates several best known results.
  </p>
</details>

<details>
  <summary>
    <b>A Particle Swarm Optimization Algorithm for a 2-D Irregular Strip Packing Problem</b> &emsp;
    <a href="https://www.scirp.org/html/2-1040217_29233.htm">  Shalaby, Kashkoush - (2013)</a>
  </summary>
  <p align=justify>
    Two-Dimensional Irregular Strip Packing Problem is a classical cutting/packing problem. The problem is to assign, a set of 2-D irregular-shaped items to a rectangular sheet. The width of the sheet is fixed, while its length is extendable and has to be minimized. A sequence-based approach is developed and tested. The approach involves two phases; optimization phase and placement phase. The optimization phase searches for the packing sequence that would lead to an optimal (or best) solution when translated to an actual pattern through the placement phase. A Particle Swarm Optimization algorithm is applied in this optimization phase. Regarding the placement phase, a combined algorithm based on traditional placement methods is developed. Competitive results are obtained, where the best solutions are found to be better than, or at least equal to, the best known solutions for 10 out of 31 benchmark data sets. A Statistical Design of Experiments and a random generator of test problems are also used to characterize the performance of the entire algorithm.
  </p>
</details>

<details>
  <summary>
    <b>Robust mixed-integer linear programming models for the irregular strip packing problem</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221716301370"> Cherry et. al. - (2016) </a>
  </summary>
  <p align=justify>
    Two-dimensional irregular strip packing problems are cutting and packing problems where small pieces have to be cut from a larger object, involving a non-trivial handling of geometry. Increasingly sophisticated and complex heuristic approaches have been developed to address these problems but, despite the apparently good quality of the solutions, there is no guarantee of optimality. Therefore, mixed-integer linear programming (MIP) models started to be developed. However, these models are heavily limited by the complexity of the geometry handling algorithms needed for the piece non-overlapping constraints. This led to pieces simplifications to specialize the developed mathematical models. In this paper, to overcome these limitations, two robust MIP models are proposed. In the first model (DTM) the non-overlapping constraints are stated based on direct trigonometry, while in the second model () pieces are first decomposed into convex parts and then the non-overlapping constraints are written based on nofit polygons of the convex parts. Both approaches are robust in terms of the type of geometries they can address, considering any kind of non-convex polygon with or without holes. They are also simpler to implement than previous models. This simplicity allowed to consider, for the first time, a variant of the models that deals with piece rotations. Computational experiments with benchmark instances show that outperforms both DTM and the best exact model published in the literature. New real-world based instances with more complex geometries are proposed and used to verify the robustness of the new models.
  </p>
</details>

<details>
  <summary>
    <b>A model-based heuristic for the irregular strip packing problem </b> &emsp;
    <a href="https://www.scielo.br/j/pope/a/DXgtyMFKv4KHqcQVw93W8LD/?lang=en#ModalTutors"> Cherri, Carravilla, Toledo - (2016) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem is a common variant of cutting and packing problems. Only a few exact methods have been proposed to solve this problem in the literature. However, several heuristics have been proposed to solve it. Despite the number of proposed heuristics, only a few methods that combine exact and heuristic approaches to solve the problem can be found in the literature. In this paper, a matheuristic is proposed to solve the irregular strip packing problem. The method has three phases in which exact mixed integer programming models from the literature are used to solve the sub-problems. The results show that the matheuristic is less dependent on the instance size and finds equal or better solutions in 87,5% of the cases in shorter computational times compared with the results of other models in the literature. Furthermore, the matheuristic is faster than other heuristics from the literature.
  </p>
</details>

<details>
  <summary>
    <b>Study of the grid size impact on a raster based strip packing problem solution</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S2405896316328476"> Sato et al - (2016)  </a>
  </summary>
  <p align=justify>
    Cutting and packing (C&P) is an important area of operational research and its problems arise in various industries such as: textile, wood, glass and shipbuilding. The main objective is to maximize the efficiency of a layout by rearranging and/or reassigning items inside containers in order to reduce costs and environmental impact. In this work, a raster solution to the bidimensional irregular strip packing problem, which consists of placing irregular shapes items inside a single rectangular container with variable length, is studied. In raster methods, the selection of the grid size is very important to the outcome of the algorithm. It influences the size of the search space, the overlap algorithm efficiency, as well as the memory requirements of the packing algorithm. An analysis of the impact of the choice of grid size is performed using 15 benchmark cases from the literature and, through careful observation of such test results, a simple rule to define the grid size is suggested.
  </p>
</details>

<details>
  <summary>
    <b>A clique covering MIP model for the irregular strip packing problem</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0305054816302702"> Rodrigues, Toledo - (2017) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem consists in the cutting of a set of two-dimensional pieces from an object of fixed width using the minimum possible length. Despite its economic importance for many industries, few exact studies have addressed this problem. Recently, a mixed integer programming model in which pieces are placed on a grid has been proposed. Although the model has proved the optimality for some large instances, it has a large number of non-overlap constraints, which grows quickly according to the discretization resolution and number of distinct pieces. This paper proposes a clique covering model to reduce the number of constraints and improve the linear relaxation. The model has outperformed the previous model in most evaluated instances and obtained an optimal solution for instances with up to 25 pieces (22 distinct pieces) subject to grid discretization.
  </p>
</details>

<details>
  <summary>
    <b>A Parallel Biased Random-Key Genetic Algorithm with Multiple Populations Applied to Irregular Strip Packing Problems</b> &emsp;
    <a href="https://onlinelibrary.wiley.com/doi/10.1155/2017/1670709"> Amaro Junior - (2017) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem (ISPP) is a class of cutting and packing problem (C&P) in which a set of items with arbitrary formats must be placed in a container with a variable length. The aim of this work is to minimize the area needed to accommodate the given demand. ISPP is present in various types of industries from manufacturers to exporters (e.g., shipbuilding, clothes, and glass). In this paper, we propose a parallel Biased Random-Key Genetic Algorithm (µ-BRKGA) with multiple populations for the ISPP by applying a collision-free region (CFR) concept as the positioning method, in order to obtain an efficient and fast layout solution. The layout problem for the proposed algorithm is represented by the placement order into the container and the corresponding orientation. In order to evaluate the proposed (µ-BRKGA) algorithm, computational tests using benchmark problems were applied, analyzed, and compared with different approaches.
  </p>
</details>

<details>
  <summary>
    <b>Solving irregular strip packing problems with free rotations using separation lines </b> &emsp;
    <a href="https://www.scielo.br/j/pope/a/RcXzqWKwBnL7QhcgkgNyZPv/?format=pdf&lang=en"> Peralta, Andretta, Oliveira - (2018)  </a>
  </summary>
  <p align=justify>
    Solving nesting problems or irregular strip packing problems is to position polygons on
a fixed width and unlimited length strip, obeying polygon integrity containment constraints and non-
overlapping constraints, in order to minimize the used length of the strip. To ensure non-overlapping, we
use separation lines, i.e., straight lines that separate polygons. We present a nonlinear programming model
that considers free rotations of the polygons and of the separation lines. This model uses a considerable
smaller number of variables than the few other approaches proposed in the literature. We use the nonlinear
programming solver IPOPT (an algorithm of interior points type), which is part of COIN-OR. Computa-
tional tests were run using established benchmark instances and the results were compared with the ones
obtained with other methodologies in the literature that use free rotations.
  </p>
</details>

<details>
  <summary>
    <b>Mixed integer quadratically-constrained programming model to solve the irregular strip packing problem with continuous rotations</b> &emsp;
    <a href="https://link.springer.com/article/10.1007/s10898-018-0638-x"> Cherri, Cherri, Soler - (2018) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem consists of cutting a set of convex and non-convex two-dimensional polygonal pieces from a board with a fixed height and infinite length. Owing to the importance of this problem, a large number of mathematical models and solution methods have been proposed. However, only few papers consider that the pieces can be rotated at any angle in order to reduce the board length used. Furthermore, the solution methods proposed in the literature are mostly heuristic. This paper proposes a novel mixed integer quadratically-constrained programming model for the irregular strip packing problem considering continuous rotations for the pieces. In the model, the pieces are allocated on the board using a reference point and its allocation is given by the translation and rotation of the pieces. To reduce the number of symmetric solutions for the model, sets of symmetry-breaking constraints are proposed. Computational experiments were performed on the model with and without symmetry-breaking constraints, showing that symmetry elimination improves the quality of solutions found by the solution methods. Tests were performed with instances from the literature. For two instances, it was possible to compare the solutions with a previous model from the literature and show that the proposed model is able to obtain numerically accurate solutions in competitive computational times.
  </p>
</details>

<details>
  <summary>
    <b>A Study in Pairwise Clustering for Bi-dimensional Irregular Strip Packing Using the Dotted Board Model</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S2405896318314216"> Sato, et. al. - (2018) </a>
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
    <b>Raster penetration map applied to the irregular packing problem</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221719304837"> Sato, et. al. - (2019) </a>
  </summary>
  <p align=justify>
    Among the most complex problems in the field of 2-dimensional cutting & packing are irregular packing problems, in which items may have a more complex geometry. These problems are prominent in several areas, including, but not limited to, the textile, shipbuilding and leather industries. They consist in placing a set of items, whose geometry is often represented by simple polygons, into one or more containers such that there is no overlap between items and the utility rate of the container is maximized. In this work, the irregular strip packing problem, an irregular packing variant with a variable length container, is investigated. The placement space is reduced by adopting a rectangular grid and a full search is performed using preprocessed raster penetration maps to efficiently determine the new position of an item. Tests were performed using simple dotted board model cases and irregular strip packing benchmark instances. The comparison of our results with the state of the art solutions showed that the proposed algorithm is very competitive, achieving better or equal compaction in 9 out of 15 instances and improving the average density in 13 instances. Besides the contribution of the new best results, the proposed approach showed the advantage of adopting discrete placement, which can be potentially applied to other irregular packing problems.
  </p>
</details>

<details>
  <summary>
    <b> Integrating irregular strip packing and cutting path determination problems: A discrete exact approach </b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0360835220304721"> Oliveira, et. al. - (2020) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem arises in a wide variety of industrial sectors, from garment and footwear to the metal industry, and has a substantial impact in raw-material waste minimization. The goal of this problem is to find a layout for a large object to be cut into smaller pieces. What differentiates this problem from all the other cutting and packing problems, and is its primary source of complexity, is the irregular (non-rectangular) shape of the small pieces. However, in practical applications, after a layout has been determined, a second problem arises: finding the path that the cutting tool has to follow to actually cut the pieces, as previously planned. This second problem is known as the cutting path determination problem. Although the solution of the first problem strongly influences the resolution of the second one, only a few studies are dealing with cutting/packing and cutting path determination together, and, to the best of the authors’ knowledge, none of them considers the irregular strip packing problem. In this paper, we propose the first mathematical programming model that integrates the irregular strip packing and the cutting path determination problems. Computational experiments were run to show the correctness of the proposed model and the advantage of tackling the two problems together. Two variants of the cutting path determination problem were considered, the fixed vertex and the free cut models. The strengths and drawbacks of these two variants are also established through computational experiments. Overall, the computational results show that the integration of these problems is advantageous, even if only small instances could be solved to optimality, given that solving to optimality the integrated is at least as difficult as solving each one of the other problems individually. As future research, it should be highlighted that the proposed integrated model is a solid basis for the development of matheuristics aiming at tackling real-world size problems
  </p>
</details>


<details>
  <summary>
    <b>Greedy Adaptive Search: A New Approach for Large-Scale Irregular Packing Problems in the Fabric Industry</b> &emsp;
    <a href="https://ieeexplore.ieee.org/abstract/document/9093914"> Hu, Li, Cui - (2020)  </a>
  </summary>
  <p align=justify>
    The 2-dimensional irregular packing problems are important in the fabric industry. Under several restrictions, fabric packing problems require placing a given set of parts within a fixed-width rectangular sheet, aiming at a minimum length use. In textile industry production, the fabric packing problems are usually large-scale with time limits, where the total number of parts is large, and a high-utilization solution should be computed in several minutes. However, there are few existing works on large-scale packing problems. In this paper, we propose a greedy adaptive search algorithm by constructing a new evaluation function and introducing a new restricted local search strategy. In our algorithm, with a given initial sequence of parts, we iteratively search the best-fit part in succeeding several parts and place it on sheet. Moreover, we employ a two-stage heuristic searching algorithm to search over all the possible sequences for a good initial sequence with high utilization. Numerical examples involve some large-scale industrial instances, together with some large-scale instances generated from benchmarks. Numerical tests show that our algorithm outperforms existing state-of-the-art solvers in large-scale packing problems. The results show the potential of our algorithm to large-scale packing problems in industrial production.
  </p>
</details>

<details>
  <summary>
    <b>MIP models for the irregular strip packing problem: new symmetry breaking constraints</b> &emsp;
    <a href="https://www.itm-conferences.org/articles/itmconf/abs/2017/06/itmconf_apmod2017_00005/itmconf_apmod2017_00005.html"> Rodrigues, Cherri, Mundim - (2020) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem consists in minimizing the length used to cut a set of pieces from a board with fixed width. Recently, a mixed integer programming model was proposed for the problem, but it may allow a large number of symmetric solutions. In this paper, new symmetry breaking constraints are proposed to improve the model. Computational experiments were performed for instances with convex pieces. The results show the proposed formulation is better than the previous one for most instances, since it improves lower bounds and reduces run-time and number of nodes explored to prove optimality.
  </p>
</details>

<details>
  <summary>
    <b>Enhanced solution for the irregular strip packing problem: valid inequalities and branching priorities</b> &emsp;
    <a href="https://repositorio.usp.br/bitstreams/83b7bc41-fac2-413f-b6f7-deab749a57b7">  Leão, Toledo - (2021) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem consists of packing a set of regular and irregular
pieces on a board with fixed width and infinite length. All pieces are packed in such a way that
they do not overlap while minimizing the used length of the board. Despite a few mathematical
models having been proposed in the literature, solving the problem to optimality is still a challenge,
and for only very few small instances, it is possible to find an optimal solution. In this paper, we
apply a different branching strategy in the branch-and-bound method and add valid inequalities in
a mathematical model of the literature. The usage of branching strategies and valid inequalities
improve the performance of the commercial solver used to solve the mixed-integer programming
model and provide the optimal solution for up to ten instances not proved in the previous paper.
  </p>
</details>

<details>
  <summary>
    <b>A branch-and-cut algorithm for the irregular strip packing problem with uncertain demands</b> &emsp;
    <a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/itor.13122"> Queiroz, Andretta - (2022) </a>
  </summary>
  <p align=justify>
    This work presents a tailored branch-and-cut algorithm for the two-dimensional irregular strip packing problem with uncertain demand for the items to be cut. A two-stage stochastic programming model is developed, considering a discrete and finite set of scenarios. The strip is discretized over a mesh of points in the model and includes constraints to ensure items are non-overlapping based on the concepts of inner-fit raster and no-fit raster. The algorithm considers lower and upper bounds from a heuristic based on the variable neighborhood search. This heuristic is also used during optimization to obtain new solutions and help to prune unsatisfactory nodes. The numerical results indicate the effectiveness of the proposed algorithm when observing other exact algorithms on the same problem without uncertainty. The algorithm can also provide optimal solutions for instances with uncertainty having more than 60 scenarios within some hours of execution. Besides, the conclusions show it is preferable to handle uncertainty to achieve minimum cost decisions.
  </p>
</details>

<details>
  <summary>
    <b>Coordinate descent heuristics for the irregular strip packing problem of rasterized shapes</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S0377221722002582"> Umetani, Murakami - (2022) </a>
  </summary>
  <p align=justify>
    We consider the irregular strip packing problem of rasterized shapes, where a given set of pieces of irregular shapes represented in pixels should be placed into a rectangular container without overlap. The rasterized shapes provide simple procedures of the intersection test without any exceptional handling due to geometric issues, while they often require much memory and computational effort in high-resolution. To reduce the complexity of rasterized shapes, we propose a pair of scanlines representation called the double scanline representation that merges consecutive pixels in each row and column into strips with unit width, respectively. Based on this, we develop coordinate descent heuristics for the raster model that repeat a line search in the horizontal and vertical directions alternately, where we also introduce a corner detection technique used in computer vision to reduce the search space. Computational results for test instances show that the proposed algorithm obtains sufficiently dense layouts of rasterized shapes in high-resolution within a reasonable computation time.
  </p>
</details>

<details>
  <summary>
    <b>A new mixed-integer programming model for irregular strip packing based on vertical slices with a reproducible survey</b> &emsp;
    <a href="https://arxiv.org/abs/2206.00032"> Lastra-Diaz, Ortuño - (2022) </a>
  </summary>
  <p align=justify>
    The irregular strip-packing problem, also known as nesting or marker making, is defined as the automatic computation of a non-overlapping placement of a set of non-convex polygons onto a rectangular strip of fixed width and unbounded length, such that the strip length is minimized. Nesting methods based on heuristics are a mature technology, and currently, the only practical solution to this problem. However, recent performance gains of the Mixed-Integer Programming (MIP) solvers, together with the known limitations of the heuristics methods, have encouraged the exploration of exact optimization models for nesting during the last decade. Despite the research effort, the current family of exact MIP models for nesting cannot efficiently solve both large problem instances and instances containing polygons with complex geometries. In order to improve the efficiency of the current MIP models, this work introduces a new family of continuous MIP models based on a novel formulation of the NoFit-Polygon Covering Model (NFP-CM), called NFP-CM based on Vertical Slices (NFP-CM-VS). Our new family of MIP models is based on a new convex decomposition of the feasible space of relative placements between pieces into vertical slices, together with a new family of valid inequalities, symmetry breakings, and variable eliminations derived from the former convex decomposition. Our experiments show that our new NFP-CM-VS models outperform the current state-of-the-art MIP models. Finally, we provide a detailed reproducibility protocol and dataset based on our Java software library as supplementary material to allow the exact replication of our models, experiments, and results. 
  </p>
</details>

<details>
  <summary>
    <b>A biobjective matheuristic for integrated solution of the irregular strip packing and cutting path determination problems </b> &emsp;
    <a href="https://www.scielo.br/j/pope/a/HC4hSckvFZVqhYDLF9Btncz/?lang=en#"> Oliveira et. al. - (2023) </a>
  </summary>
  <p align=justify>
    Irregular strip packing problems are present in a wide variety of industrial sectors, such as the garment, footwear, furniture and metal industry. The goal is to find a layout in which an object will be cut into small pieces with minimum raw-material waste. Once a layout is obtained, it is necessary to determine the path that the cutting tool has to follow to cut the pieces from the layout. In the latter, the goal is to minimize the cutting distance (or time). Although industries frequently use this solution sequence, the trade-off between the packing and the cutting path problems can significantly impact the production cost and productivity. A layout with minimum raw-material waste, obtained through the packing problem resolution, can imply a longer cutting path compared to another layout with more material waste but a shorter cutting path, obtained through an integrated strategy. Layouts with shorter cutting path are worthy of consideration because they may improve the cutting process productivity. In this paper, both problems are solved together using a biobjective matheuristic based on the Biased Random-Key Genetic Algorithm. Our approach uses this algorithm to select a subset of the no-fit polygons edges to feed the mathematical model, which will compute the layout waste and cutting path length. Solving both strip packing and cutting path problems simultaneously allows the decision-maker to analyze the compromise between the material waste and the cutting path distance. As expected, the computational results showed the trade-off’s relevance between these problems and presented a set of solutions for each instance solved.
  </p>
</details>

<details>
  <summary>
    <b>An extended model formulation for the two-dimensional irregular strip packing problem considering general industry-relevant aspects</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221722006403"> Kimms, Király - (2023) </a>
  </summary>
  <p align=justify>
    Two-dimensional cutting and packing problems including irregular items (nesting problems) are common, e.g., in the clothing, paper, glass and leather industries. In the irregular strip packing problem considered in this work a finite number of rotations of convex as well as non-convex polygons with and without holes are permitted. To deal with the geometry of irregular items, direct trigonometry is applied. The focus is on aspects and characteristics that are typical for many affected industries and have been neglected so far. In the mentioned sectors, it is conceivable that items can be created from smaller parts by assembling them using various techniques. There might be several possible combinations of parts to be joined together to result in the desired item, i.e., there might be several cutting patterns to choose from. Also, whether the large material, i.e., large object is single-colored or has a particular structure or design is of great importance. In the latter case, special attention must be paid to the rotation of certain items or parts in order to achieve the desired (uniform or non-uniform) appearance of the final product. The utilized data structure is introduced, to address the mentioned aspects in the presented mixed-integer linear model which is an extension of a formulation published by previous authors. Furthermore, the method of calculating “critical vertices” is introduced, which requires only a reduced number of comparisons between edges and vertices of two items to ensure overlap-free positioning. Industry-relevant examples are highlighted in the computational study to illuminate the versatility of the model.
  </p>
</details>

<details>
  <summary>
    <b>Solutions for New Variants of Packing Problem</b> &emsp;
    <a href="https://link.springer.com/chapter/10.1007/978-981-19-5916-5_5"> Rao, Luo - (2023) </a>
  </summary>
  <p align=justify>
    The 2DRSP and 2DISP problems are the most studied problem in the academic community. However, there are many kinds of packing problems in the reality according to the constraints and requirements. These problems have different characteristics resulting in designing the suitable approach to solve. In this chapter, three new variants of the packing problems are introduced. The solution method is proposed for each problem, i.e., the biased genetic algorithm hybridized with variable neighborhood search for the two-dimensional knapsack packing problem with defects, genetic algorithm, and grey wolf optimization algorithm for the irregular packing problem with defects, and biased genetic algorithm and grey wolf optimization for the rectangular packing problem with divisible items.
  </p>
</details>

<details>
  <summary>
    <b>Mixed-integer programming models for irregular strip packing based on vertical slices and feasibility cuts</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S0377221723006148">  Lastra-Diàz, Ortuño - (2024) </a>
  </summary>
  <p align=justify>
    The irregular strip-packing problem, also known as nesting or marker making, is defined as the automatic computation of a non-overlapping placement of a set of non-convex polygons onto a rectangular strip of fixed width and unbounded length, such that the strip length is minimized. Nesting methods based on heuristics are a mature technology, and currently, the only practical solution to this problem. However, recent performance gains of the Mixed-Integer Programming (MIP) solvers, together with the known limitations of the heuristics methods, have encouraged the exploration of exact optimization models for nesting during the last decade. Despite the research effort, there is room to improve the efficiency of the current family of exact MIP models for nesting. In order to bridge this gap, this work introduces a new family of continuous MIP models based on a novel formulation of the NoFit-Polygon Covering Model (NFP-CM), called NFP-CM based on Vertical Slices (NFP-CM-VS). Our new family of MIP models is based on a new convex decomposition of the feasible space of relative placements between pieces into vertical slices, together with a new family of valid inequalities, symmetry breakings, and variable eliminations derived from the former convex decomposition. Our experiments show that our new NFP-CM-VS models outperform the current state-of-the-art MIP models. Ten instances are solved up to optimality within one hour for the first time, including one with 27 pieces. Finally, we provide a detailed reproducibility protocol and dataset as supplementary material to allow the exact replication of our models, experiments, and results.
  </p>
</details>

## Irregular shapes clustering

<details>
  <summary>
    <b> Optimal clustering of a pair of irregular objects  </b> &emsp;
    <a href="https://link.springer.com/article/10.1007/s10898-014-0192-0"> Bennel et. al. - (2014)  </a>
  </summary>
  <p align=justify>
    Cutting and packing problems arise in many fields of applications and theory. When dealing with irregular objects, an important subproblem is the identification of the optimal clustering of two objects. Within this paper we consider a container (rectangle, circle, convex polygon) of variable sizes and two irregular objects bounded by circular arcs and/or line segments, that can be continuously translated and rotated. In addition minimal allowable distances between objects and between each object and the frontier of a container, may be imposed. The objects should be arranged within a container such that a given objective will reach its minimal value. We consider a polynomial function as the objective, which depends on the variable parameters associated with the objects and the container. The paper presents a universal mathematical model and a solution strategy which are based on the concept of phi-functions and provide new benchmark instances of finding the containing region that has either minimal area, perimeter or homothetic coefficient of a given container, as well as finding the convex polygonal hull (or its approximation) of a pair of objects.
  </p>
</details>


## Irregular 2D Bin Packing 


<details>
  <summary>
    <b>Solving an optimization packing problem of circles and non-convex polygons with rotations into a multiply connected region</b> &emsp;
    <a href="https://www.tandfonline.com/doi/abs/10.1057/jors.2011.41"> Stoyan, Zlotnik, Chugay - (2011)  </a>
  </summary>
  <p align=justify>
    This paper deals with the packing problem of circles and non-convex polygons, which can be both translated and rotated into a strip with prohibited regions. Using the Φ-function technique, a mathematical model of the problem is constructed and its characteristics are investigated. Based on the characteristics, a solution approach to the problem is offered. The approach includes the following methods: an optimization method by groups of variables to construct starting points, a modification of the Zoutendijk feasible direction method to search for local minima and a special non-exhaustive search of local minima to find an approximation to a global minimum. A number of numerical results are given. The numerical results are compared with the best known ones.
  </p>
</details>

<details>
  <summary>
    <b>An effective heuristic for the two-dimensional irregular bin packing problem</b> &emsp;
    <a href="https://link.springer.com/article/10.1007/s10479-013-1341-4"> Lopez-Camacho, Ochoa - (2013)  </a>
  </summary>
  <p align=justify>
    This paper proposes an adaptation, to the two-dimensional irregular bin packing problem of the Djang and Finch heuristic (DJD), originally designed for the one-dimensional bin packing problem. In the two-dimensional case, not only is it the case that the piece’s size is important but its shape also has a significant influence. Therefore, DJD as a selection heuristic has to be paired with a placement heuristic to completely construct a solution to the underlying packing problem. A successful adaptation of the DJD requires a routine to reduce computational costs, which is also proposed and successfully tested in this paper. Results, on a wide variety of instance types with convex polygons, are found to be significantly better than those produced by more conventional selection heuristics.
  </p>
</details>


<details>
  <summary>
    <b>Construction heuristics for two-dimensional irregular shape bin packing with guillotine constraints</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221713003627"> Han et al. - (2013)  </a>
  </summary>
  <p align=justify>
    The paper examines a new problem in the irregular packing literature that has many applications in industry: two-dimensional irregular (convex) bin packing with guillotine constraints. Due to the cutting process of certain materials, cuts are restricted to extend from one edge of the stock-sheet to another, called guillotine cutting. This constraint is common place in glass cutting and is an important constraint in two-dimensional cutting and packing problems. In the literature, various exact and approximate algorithms exist for finding the two dimensional cutting patterns that satisfy the guillotine cutting constraint. However, to the best of our knowledge, all of the algorithms are designed for solving rectangular cutting where cuts are orthogonal with the edges of the stock-sheet. In order to satisfy the guillotine cutting constraint using these approaches, when the pieces are non-rectangular, practitioners implement a two stage approach. First, pieces are enclosed within rectangle shapes and then the rectangles are packed. Clearly, imposing this condition is likely to lead to additional waste. This paper aims to generate guillotine-cutting layouts of irregular shapes using a number of strategies. The investigation compares three two-stage approaches: one approximates pieces by rectangles, the other two approximate pairs of pieces by rectangles using a cluster heuristic or phi-functions for optimal clustering. All three approaches use a competitive algorithm for rectangle bin packing with guillotine constraints. Further, we design and implement a one-stage approach using an adaptive forest search algorithm. Experimental results show the one-stage strategy produces good solutions in less time over the two-stage approach.
  </p>
</details>

<details>
  <summary>
    <b>Waste minimization in irregular stock cutting</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0278612513001209"> Dalalah, Khrais, Bataineh (2014)  </a>
  </summary>
  <p align=justify>
    This paper addresses a category of two dimensional NP-hard knapsack problem in which a given convex/non-convex planner items (polygons) have to be cut out of a single convex/non-convex master surface (stock). This cutting process is found in many industrial applications such as sheet metal processes, home-textile, garment, wood, leather and paper industries. An approach is proposed to solve this problem, which depends on the concept of the difference between the area of a collection of polygons and the area of their convex hull. The polygon assignment inside the stock is subjected to feasibility tests to avoid overlapping, namely, angle test, bound test, point inclusion and polygon intersection test. An iterative scheme is used to generate different polygon placements while optimizing the objective function. Computer software is developed to solve and optimize the problem under consideration. Few examples are conducted for different combinations of convex, non-convex items and stocks. Well-known benchmark problems from the literature are tested and compared with our approach. The results of our algorithm have an interesting computational time and can compete with the results of previous work in some particular problems. The computational performance of the developed software indicates the efficiency of the algorithm for solving 2-D irregular cutting of non-convex polygons out of non-convex stock.
  </p>
</details>

<details>
  <summary>
    <b>Constructive procedures to solve 2-dimensional bin packing problems with irregular pieces and guillotine cuts</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0305048314001285"> Sykora, et. al - (2015)  </a>
  </summary>
  <p align=justify>
    This paper presents an approach for solving a new real problem in cutting and packing. At its core is an innovative mixed integer programme model that places irregular pieces and defines guillotine cuts. The two-dimensional irregular shape bin packing problem with guillotine constraints arises in the glass cutting industry, for example, the cutting of glass for conservatories. Almost all cutting and packing problems that include guillotine cuts deal with rectangles only, where all cuts are orthogonal to the edges of the stock sheet and a maximum of two angles of rotation are permitted. The literature tackling packing problems with irregular shapes largely focuses on strip packing i.e. minimizing the length of a single fixed width stock sheet, and does not consider guillotine cuts. Hence, this problem combines the challenges of tackling the complexity of packing irregular pieces with free rotation, guaranteeing guillotine cuts that are not always orthogonal to the edges of the stock sheet, and allocating pieces to bins. To our knowledge only one other recent paper tackles this problem. We present a hybrid algorithm that is a constructive heuristic that determines the relative position of pieces in the bin and guillotine constraints via a mixed integer programme model. We investigate two approaches for allocating guillotine cuts at the same time as determining the placement of the piece, and a two phase approach that delays the allocation of cuts to provide flexibility in space usage. Finally we describe an improvement procedure that is applied to each bin before it is closed. This approach improves on the results of the only other publication on this problem, and gives competitive results for the classic rectangle bin packing problem with guillotine constraints.
  </p>
</details>


<details>
  <summary>
    <b>Irregular packing: MILP model based on a polygonal enclosure</b> &emsp;
    <a href="https://link.springer.com/article/10.1007/s10479-015-1971-9"> Santoro, Lemos - (2015) </a>
  </summary>
  <p align=justify>
    This paper addresses the two-dimensional irregular packing problem, also known as the nesting problem. This is a subset of cutting and packing problems of renowned practical and theoretical relevance. A mixed integer-linear programming formulation is proposed to optimize the packing of particular polygonal shapes, convex forms with 3–8 sides, since their opposite sides are parallel. The model can be used to pack enclosures of general irregular shapes, generating upper bounds to the optimal solutions. The model was tested with 270 mass generated instances of small dimensions.
  </p>
</details>

<details>
  <summary>
    <b>Jostle heuristics for the 2D-irregular shapes bin packing problems with free rotation</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0925527317302980"> Abeysooriya, Bennell, Martinez-Sykora - (2018)  </a>
  </summary>
  <p align=justify>
    The paper investigates the two-dimensional irregular packing problem with multiple homogeneous bins (2DIBPP). The literature on irregular shaped packing problems is dominated by the single stock sheet strip packing problem. However, in reality manufacturers are cutting orders over multi-stock sheets. Despite its greater relevance, there are only a few papers that tackle this problem in the literature. A multi-stock sheet problem has two decision components; the allocation of pieces to stock sheets and the layout design for each stock sheet. In this paper, we propose a heuristic method that addresses both the allocation and placement problems together based on the Jostle algorithm. Jostle was first applied to strip packing. In order to apply Jostle to the bin packing problem we modify the placement heuristic. In addition we improve the search capability by introducing a diversification mechanism into the approach. Furthermore, the paper presents alternative strategies for handling rotation of pieces, which includes a restricted set of angles and unrestricted rotation. Very few authors permit unrestricted rotation of pieces, despite this being a feature of many problems where the material is homogeneous. Finally, we investigate alternative placement criteria and show that the most commonly applied bottom left criteria does not perform as well as other options. The paper evaluates performance of each algorithm using different sets of instances considering convex and non-convex shapes. Findings of this study reveal that the proposed algorithms can be applied to different variants of the problem and generate significantly better results.
  </p>
</details>

<details>
  <summary>
    <b>A beam search approach to solve the convex irregular bin packing problem with guillotine cuts</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0377221718302571"> Benell, Cabo, Martinez-Sykora - (2018)  </a>
  </summary>
  <p align=justify>
    This paper presents a two dimensional convex irregular bin packing problem with guillotine cuts. The problem combines the challenges of tackling the complexity of packing irregular pieces, guaranteeing guillotine cuts that are not always orthogonal to the edges of the bin, and allocating pieces to bins that are not necessarily of the same size. This problem is known as a two-dimensional multi bin size bin packing problem with convex irregular pieces and guillotine cuts. Since pieces are separated by means of guillotine cuts, our study is restricted to convex pieces.A beam search algorithm is described, which is successfully applied to both the multi and single bin size instances. The algorithm is competitive with the results reported in the literature for the single bin size problem and provides the first results for the multi bin size problem.
  </p>
</details>

<details>
  <summary>
    <b>Practical Algorithms for Two-Dimensional Packing of General Shapes</b> &emsp;
    <a href="https://www.taylorfrancis.com/chapters/edit/10.1201/9781351236423-33/practical-algorithms-two-dimensional-packing-general-shapes-yannan-hu-hideki-hashimoto-shinji-imahori-mutsunori-yagiura"> Hu et al - (2018)  </a>
  </summary>
  <p align=justify>
    This chapter discusses the heuristics, metaheuristics, and exact algorithms for two-dimensional packing problems of general shapes. It explores the procedure of applying the bottom-left strategy to a given order the bottom-left algorithm. The chapter explains the irregular strip packing problem and introduces some practical algorithms for irregular packing problems. It focuses on the problem of packing irregular shapes represented in bitmap format and analyses the rectilinear block packing problem and also introduces various schemes used to represent solutions to the rectilinear block packing problem and algorithms based on such coding schemes. The chapter considers two-dimensional irregular packing problems, which have been actively studied in the last decade. It provides some basic techniques including bottom-left strategy, clustering strategy, and no-fit polygons. The chapter shows that various algorithms proposed for the irregular strip packing and bin packing problems and their variants. T. Imamichi et al. proposed an iterated local search based on nonlinear programming for the irregular strip packing problem.
  </p>
</details>

<details>
  <summary>
    <b>Hybridizing Beam Search with Tabu Search for the Irregular Packing Problem</b> &emsp;
    <a href="https://www.hindawi.com/journals/mpe/2021/5054916/"> Rao, Wang, Luo - (2020)  </a>
  </summary>
  <p align=justify>
    The irregular packing problem involves arranging all the irregular pieces on a plate with the objective of maximizing the use of material. In this article, the layout is formed by the ordered sequence of the irregular pieces which is obtained by a hybrid search algorithm and where the order is decoded by a proposed placement principle. First, a novel no-fit-polygon (NFP) generator is introduced. Then, a placement principle is presented with the new NFP generator. Finally, a search algorithm hybridized with beam search (BS) and tabu search (TS) is proposed to search over the sequence. The numerical experiments with many benchmark problems show that the hybrid algorithm is an applicative and effective approach for solving the irregular packing problem. The hybrid algorithm can produce competitive solutions in less time than many other typical algorithms.
  </p>
</details>


<details>
  <summary>
    <b>GA and GWO algorithm for the special bin packing problem encountered in field of aircraft arrangement</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S1568494621009716">  Luo, Rao, Peng - (2022) </a>
  </summary>
  <p align=justify>
    This paper addresses a special case of irregular bin packing problem which the irregular pieces with free rotation have to fill a large irregular stock sheet with defective regions while satisfying the special boundary constraint, i.e., the piece can protrude from the sheet so long as the key points in the piece’s interior lie within the container. The objective of this problem is to maximize the number of filled pieces. To our best knowledge, the piece must be placed completely inside the sheet for all packing problem tackled by published literature. Thus, existing approaches are not good solutions to this special packing problem. To achieve the goal of automated arrangement of pieces and maximize the space utilization, the genetic algorithm and grey wolf optimization algorithm are designed to solve it. The genetic algorithm adopts the elitism strategy for maintaining the portion of the best chromosomes. A new method of updating the main controlling parameter is applied for reinforcing the exploration ability of the grey wolf optimization. These two algorithms use a vector of pieces as the solution representation, and a novel heuristic algorithm decodes it to produce a layout. The proposed heuristic algorithm divides the process of packing into two stages with the objective of satisfying constraints and achieving good space utilization of sheet. Computational experiments show that the presented methods can solve this new kind of the packing problem very well.
  </p>
</details>


<details>
  <summary>
    <b>An iteratively doubling local search for the two-dimensional irregular bin packing problem with limited rotations</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0305054821002847">  Zhang et. al. - (2022) </a>
  </summary>
  <p align=justify>
    This paper proposes an iteratively doubling local search approach for the two-dimensional irregular bin packing problem (2DIRBPP) with limited rotations, whose objective is to pack a given set of irregular pieces into the minimum number of rectangular bins. The allowable angles of each piece are limited. To solve this problem, a waste least first decreasing strategy is introduced to assign the piece to the bins. A simple greedy local search approach by moving the pieces from one bin to another is utilized to improve the solution. We adapt an overlap minimization approach to solving the one bin placement problem. The classical bottom-left method is utilized to generate the initial position for each piece, and the random local search by exchanging the positions of two pieces is used to minimize the overlap. Moreover, a novel warm start and an iteratively doubling search strategy are proposed to speed up the search process. The standard benchmark results show that our approach improves the results for most of the instances in the literature.
  </p>
</details>

<details>
  <summary>
    <b>A hierarchical hyper-heuristic for the bin packing problem</b> &emsp;
    <a href="https://link.springer.com/article/10.1007/s00500-022-07118-4">  Guerriero, Saccomanno - (2023) </a>
  </summary>
  <p align=justify>
    This paper addresses the two-dimensional irregular bin packing problem, whose main aim is to allocate a given set of irregular pieces to larger rectangular containers (bins), while minimizing the number of bins required to contain all pieces. To solve the problem under study a dynamic hierarchical hyper-heuristic approach is proposed. The main idea of the hyper-heuristics is to search the space of low-level heuristics for solving computationally difficult problems. The proposed approach is “dynamic” since the low-level heuristic to be executed is chosen on the basis of the main characteristics of the instance to be solved. The term “hierarchical” is used to indicate the fact that the main hyper-heuristic can execute either simple heuristics or can run in a “recursive fashion” a hyper-heuristic. The developed solution strategy is evaluated empirically by performing extensive experiments on irregular packing benchmark instances. A comparison with the state-of-the-art approaches is also carried out. The computational results are very encouraging. 
  </p>
</details>

<details>
  <summary>
    <b>An iteratively doubling binary search for the two-dimensional irregular multiple-size bin packing problem raised in the steel industry</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0305054823003404"> Yao et. al. (2024)  </a>
  </summary>
  <p align=justify>
    This paper examines the two-dimensional irregular multiple-size bin packing problem, where the goal is to pack all the given irregular pieces into bins of various sizes such that the total area of the used bins is minimized. Meanwhile, the irregular pieces include holes, and the bins can be irregular, also. This problem is raised in the steel industry considering the reuse of leftover material. An iteratively doubling binary search is proposed to solve this problem. Moreover, a binary search strategy is introduced to search the bin combination with minimum area, and an iteratively doubling strategy is utilized to control the search effort on each bin combination. Once the bins are identified, a first-fit bottom-left method is utilized to generate the initial position for each piece. An overlap minimization approach, which includes a local search by exchanging the positions of two pieces, is adapted to minimize the overlap in the initial solution. Experiment results on existing instances show that our approach could find a better solution than existing methods. Several instances representing different application scenarios are generated, and the results show our approach’s effectiveness and generality.
  </p>
</details>

## Irregular cutting stock

<details>
  <summary>
    <b>An Efficient Heuristic Approach for Irregular Cutting Stock Problem in Ship Building Industry</b> &emsp;
    <a href="https://www.hindawi.com/journals/mpe/2016/8703782/"> Xu - (2016)  </a>
  </summary>
  <p align=justify>
    This paper presents an efficient approach for solving a real two-dimensional irregular cutting stock problem in ship building industry. Cutting stock problem is a common cutting and packing problem that arises in a variety of industrial applications. A modification of selection heuristic Exact Fit is applied in our research. In the case referring to irregular shapes, a placement heuristics is more important to construct a complete solution. A placement heuristic relating to bottom-left-fill is presented. We evaluate the proposed approach using generated instance only with convex shapes in literatures and some instances with nonconvex shapes based on real problem from ship building industry. The results demonstrate that the effectiveness and efficiency of the proposed approach are significantly better than some conventional heuristics.
  </p>
</details>

<details>
  <summary>
    <b>A GRASP meta-heuristic for two-dimensional irregular cutting stock problem</b> &emsp;
    <a href="https://link.springer.com/article/10.1007/s00170-015-7107-1"> MirHassani, Bashirzadeh - (2015)  </a>
  </summary>
  <p align=justify>
    Reducing expensive raw material waste is an important goal in the industry. In this paper, two-dimensional irregular cutting stock problem—a nesting problem that differs from other in their irregular shape of the pieces—with demand is studied, in which the required pieces has to be produced from large rectangular sheet minimizing material waste. Structure of this problem made it intractable for practical applications such that exact algorithms are not able to solve it in a reasonable time. Greedy randomized adaptive search procedure (GRASP) meta-heuristic algorithm is adapted to tackle the problem by providing high-quality solution in an appropriate time. The algorithm does not depend on the shape (convexity and regularity) of pieces and is able to deliver an optimum solution for instances up to 30 pieces of 7 different types. In addition, computational results are provided for different test problems from the related literature.
  </p>
</details>

## Irregular Knapsack Problem


<details>
  <summary>
    <b>Two effective methods for the irregular knapsack problem</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S1568494620304245"> Queiroz, Andretta, (2020)  </a>
  </summary>
  <p align=justify>
    Two methods are developed for a two-dimensional cutting problem with irregular shaped items. The concepts of inner-fit raster and no-fit raster are used to search for a feasible positioning of items on a rectangular container. The first method is a Biased Random Key Genetic Algorithm, which is a population method, while the other is a Variable Neighborhood Search, which is a single trajectory method. In the proposed methods, a solution is represented by a vector of items, and the positioning of items is achieved with three rules inspired by the bottom-left strategy. When positioning items, feasible positions can be skipped as a strategy to diversify the search and escape from local optima solutions. Numerical experiments performed on literature instances show that the methods are better than the current state-of-the-art method since they obtained equal or better solutions for all the instances. On average, the occupied area increased 6.44%, and the known optimal solution was obtained for 60% of the instances. The population-based method performed better overall, obtaining solutions with better-occupied areas.
  </p>
</details>

<details>
  <summary>
    <b>Heuristics for two-dimensional knapsack and cutting stock problems with items of irregular shape</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417412007233">  Del Valle, et. al. (2012) </a>
  </summary>
  <p align=justify>
    In this paper, the two-dimensional cutting/packing problem with items that correspond to simple polygons that may contain holes are studied in which we propose algorithms based on no-fit polygon computation. We present a GRASP based heuristic for the 0/1 version of the knapsack problem, and another heuristic for the unconstrained version of the knapsack problem. This last heuristic is divided in two steps: first it packs items in rectangles and then use the rectangles as items to be packed into the bin. We also solve the cutting stock problem with items of irregular shape, by combining this last heuristic with a column generation algorithm. The algorithms proposed found optimal solutions for several of the tested instances within a reasonable runtime. For some instances, the algorithms obtained solutions with occupancy rates above 90% with relatively fast execution time.
  </p>
</details>

<details>
  <summary>
    <b>Heuristic algorithms for the special knapsack packing problem with defects arising in aircraft arrangement</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417422024101"> Luo, Rao - (2023)  </a>
  </summary>
  <p align=justify>
    This paper addresses a special knapsack packing problem in which identical pieces are packed into an irregular board with unusable regions to maximize the number of pieces. This problem arises from a real-world application in which the aircraft is placed on the carrier’s deck to maximize the number of aircraft. We propose the support polygon concept to solve one of the challenges of the problem, i.e., ensure that the support points inside the piece’s interior are located within the board when the piece protrudes from the board. Many strategies for determining the piece’s location and selecting the rotation angle of the piece are proposed and compared. Based on these techniques, we propose a deterministic heuristic algorithm to solve the problem. In addition, we develop an improved version of the algorithm, called the recursive search heuristic algorithm, to get higher-quality solutions. Many experiments were conducted to test the performance of different combinations of strategies and the proposed algorithms. The computational results show that the proposed algorithms have a strong capacity for obtaining good solutions, and updating many of the best results in the benchmark instances provided by the literature.
  </p>
</details>

##  Irregular 3D Packing Problem

<details>
  <summary>
    <b>A hybrid chaos firefly algorithm for three-dimensional irregular packing problem</b> &emsp;
    <a href="https://www.aimsciences.org/article/id/1cac7d3a-9283-4f4d-90bb-add8fdfe811d">  Zhao, Jiang, Teo - (2020) </a>
  </summary>
  <p align=justify>
    The packing problem study how to pack multiple objects without overlap. Various exact and approximate algorithms have been developed for two-dimensional regular and irregular packing as well as three-dimensional bin packing. However, few results are reported for three-dimensional irregular packing problems. This paper will develop a method for solving three-dimensional irregular packing problems. A three-grid approximation technique is first introduced to approximate irregular objects. Then, a hybrid heuristic method is developed to place and compact each individual objects where chaos search is embedded into firefly algorithm in order to enhance the algorithm's diversity for optimizing packing sequence and orientations. Results from several computational experiments demonstrate the effectiveness of the hybrid algorithm.
  </p>
</details>


## AI Approaches 

<details>
  <summary>
    <b>A reinforcement learning algorithm for the 2D-rectangular strip packing proble</b> &emsp;
    <a href="https://iopscience.iop.org/article/10.1088/1742-6596/2181/1/012002/pdf"> Zhao, Hao, Fang - (2021) </a>
  </summary>
  <p align=justify>
    Packing problems, also known as nesting problems or bin packing problems, are classic and popular NP-hard problems with high computational complexity. Inspired by classic reinforcement learning (RL), we established a mathematical model for two-dimensional (2D) irregular-piece packing combined with characteristics of 2D irregular pieces. An RL algorithm based on Monte Carlo learning (MC), Q-learning, and Sarsa-learning is proposed in this paper to solve a 2D irregular-piece packing problem. Additionally, mechanisms of reward–return and strategy-update based on piece packing were designed. Finally, the standard test case of irregular pieces was used for experimental testing to analyze the optimization effect of the algorithm. The experimental results show that the proposed algorithm can successfully realize packing of 2D irregular pieces. A similar or better optimization effect can be obtained compared to some classical heuristic algorithms. The proposed algorithm is an early attempt to use machine learning to solve 2D irregular packing problems. On the one hand, our hybrid RL algorithm can provide a basis for subsequent deep reinforcement learning (DRL) to solve packing problems, which has far-reaching theoretical significance. On the other hand, it has practical significance for improving the utilization rate of raw materials and broadening the application field of machine learning.
  </p>
</details>

<details>
  <summary>
    <b>An expert system to react to defective areas in nesting problems</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S095741742201363X"> Bartmeyer et. al. -(2022) </a>
  </summary>
  <p align=justify>
    Production plans in the textile industry, and other practical applications, involve cutting irregular pieces from raw materials. Defective areas in the raw material may be detected during the cutting process, requiring an adaptation of the original layout. The response time to provide an alternative layout is short, precluding the use of exact methods to overcome defective areas. The main contribution of this paper is to provide an expert system to quickly obtain an alternative layout, overcoming defective areas in the object. The expert system comprises a greedy heuristic based on the allocation sequence suggested by reinforcement learning. Computational experiments have two main objectives. The first one is to validate reinforcement learning as a suitable strategy to tackle nesting problems. The results attest to the ability of the strategy to achieve the best results in the literature. The second objective is to show the ability of the expert system to provide alternative layouts within a short response time. The quality of the solutions obtained by the expert system evidence the strength of the proposed system in overcoming defective areas.
  </p>
</details>

<details>
  <summary>
    <b>A Hybrid Reinforcement Learning Algorithm for 2D Irregular Packing Problems </b> &emsp;
    <a href="https://www.mdpi.com/2227-7390/11/2/327"> Fang et. al. - (2023) </a>
  </summary>
  <p align=justify>
    Packing problems, also known as nesting problems or bin packing problems, are classic and popular NP-hard problems with high computational complexity. Inspired by classic reinforcement learning (RL), we established a mathematical model for two-dimensional (2D) irregular-piece packing combined with characteristics of 2D irregular pieces. An RL algorithm based on Monte Carlo learning (MC), Q-learning, and Sarsa-learning is proposed in this paper to solve a 2D irregular-piece packing problem. Additionally, mechanisms of reward–return and strategy-update based on piece packing were designed. Finally, the standard test case of irregular pieces was used for experimental testing to analyze the optimization effect of the algorithm. The experimental results show that the proposed algorithm can successfully realize packing of 2D irregular pieces. A similar or better optimization effect can be obtained compared to some classical heuristic algorithms. The proposed algorithm is an early attempt to use machine learning to solve 2D irregular packing problems. On the one hand, our hybrid RL algorithm can provide a basis for subsequent deep reinforcement learning (DRL) to solve packing problems, which has far-reaching theoretical significance. On the other hand, it has practical significance for improving the utilization rate of raw materials and broadening the application field of machine learning.
  </p>
</details>

<details>
  <summary>
    <b>Learning Gradient Fields for Scalable and Generalizable Irregular Packing</b>
    <a href="https://dl.acm.org/doi/abs/10.1145/3610548.3618235"> Xue, et. al - (2023)  </a>
  </summary>
  <p align=justify>
    The packing problem, also known as cutting or nesting, has diverse applications in logistics, manufacturing, layout design, and atlas generation. It involves arranging irregularly shaped pieces to minimize waste while avoiding overlap. Recent advances in machine learning, particularly reinforcement learning, have shown promise in addressing the packing problem. In this work, we delve deeper into a novel machine learning-based approach that formulates the packing problem as conditional generative modeling. To tackle the challenges of irregular packing, including object validity constraints and collision avoidance, our method employs the score-based diffusion model to learn a series of gradient fields. These gradient fields encode the correlations between constraint satisfaction and the spatial relationships of polygons, learned from teacher examples. During the testing phase, packing solutions are generated using a coarse-to-fine refinement mechanism guided by the learned gradient fields. To enhance packing feasibility and optimality, we introduce two key architectural designs: multi-scale feature extraction and coarse-to-fine relation extraction. We conduct experiments on two typical industrial packing domains, considering translations only. Empirically, our approach demonstrates spatial utilization rates comparable to, or even surpassing, those achieved by the teacher algorithm responsible for training data generation. Additionally, it exhibits some level of generalization to shape variations. We are hopeful that this method could pave the way for new possibilities in solving the packing problem.
  </p>
</details>

## Quantum Computing Approaches

<details>
  <summary>
    <b>A heuristic for solving the irregular strip packing problem with quantum optimization</b> &emsp;
    <a href="https://arxiv.org/abs/2402.17542"> Matt, Roth - (2024) </a>
  </summary>
  <p align=justify>
    We introduce a novel quantum computing heuristic for solving the irregular strip packing problem, a significant challenge in optimizing material usage across various industries. This problem involves arranging a set of irregular polygonal pieces within a fixed-height, rectangular container to minimize waste. Traditional methods heavily rely on manual optimization by specialists, highlighting the complexity and computational difficulty of achieving quasi-optimal layouts. The proposed algorithm employs a quantum-inspired heuristic that decomposes the strip packing problem into two sub-problems: ordering pieces via the traveling salesman problem and spatially arranging them in a rectangle packing problem. This strategy facilitates a novel application of quantum computing to industrial optimization, aiming to minimize waste and enhance material efficiency. Experimental evaluations using both classical and quantum computational methods demonstrate the algorithm's efficacy. We evaluate the algorithm's performance using the quantum approximate optimization algorithm and the quantum alternating operator ansatz, through simulations and real quantum computers, and compare it to classical approaches. 
  </p>
</details>

## Thesis

<details>
  <summary>
    <b> Exact and Heuristic Methods
for Nesting Problems </b> &emsp;
    <a href="https://www.dei.unipd.it/~fisch/ricop/tesi/tesi_dottorato_Luzzi_2003.pdf"> Fischetti, Luzzi - (2004)  </a>
  </summary>
</details>

<details>
  <summary>
    <b> Nesting Problems: Exact and Heuristic Algorithms </b> &emsp;
    <a href="https://www.uv.es/marsyan/docs/thesis.pdf"> Sykora - (2009) </a>
  </summary>
</details>

<details>
  <summary>
    <b>Algoritmos para o encaixe de moldes com formato irregular em tecidos listrados</b> &emsp;
    <a href="https://www.lume.ufrgs.br/handle/10183/142744"> Souza (2016)  </a>
  </summary>
  <p align=justify>
    This thesis proposes the solution for the packing problem of patterns on striped fabric in clothing industry. The patterns are pieces with irregular form that should be placed on raw material which is, in this case, the fabric. This fabric is cut after packing. In the specific problem of packing on striped fabric, the position that patterns are put in the fabric should ensure that, after the clothing sewing, the stripes should present continuity. Thus, the theoretical foundation of this project includes subjects about fashion and clothing design, such as types and rapports of striped fabric, and the possibilities of rotation and the correct place to put the patterns on striped fabric. In the theoretical foundation, there are also subjects about research in combinatorial optimization as: characteristics about bi-dimensional packing and cutting problems and algorithms used for several authors to solve the problem. In addition, the Markov Chain Monte Carlo method and the Metropolis-Hastings algorithm are described at end of theoretical foundation. Based on the bibliographic research, two different algorithms for the packing problem with striped fabric are proposed: algorithm with pre-processing step and algorithm of searching the best packing using the Metropolis-Hastings algorithm. Both algorithms are implemented in the Striped Riscare software, which is a continuity of Riscare software for clear fabrics developed in the Masters degree of the author. Both algorithms performances are tested with six literature benchmark problems and a new problem called “male shirt” is proposed here. The benchmark problems of literature were iniatially proposed for clear raw material and the male shirt problem, specifically for striped fabrics. Between the two developed algorithms, the algorithm of searching the best packing has shown better results with better efficiencies of the fabric usage for all the problems tested. When compared to the best results published in the literature for clear raw material, the algorithm of searching the best packing has shown packings with lower efficiencies. However, it showed results higher than recommended for the specific literature of fashion design for patterned fabrics.
  </p>
</details>

<details>
  <summary>
    <b>(Master thesis) Developing a plate nesting algorithm for a steel processing company</b> &emsp;
    <a href="http://essay.utwente.nl/102916/"> Oosten (2024)  </a>
  </summary>
  <p align=justify>
    This thesis addresses the two-dimensional irregular bin packing problem (2DIBPP), focusing on optimizing the layout of irregularly shaped metal parts on steel sheets, a process known as 2D/plate nesting. This optimization is crucial in manufacturing industries, where efficient material usage can significantly reduce costs and waste. Existing algorithms often fall short of the company's objectives and requirements, resulting in suboptimal outcomes and a reliance on manual adjustments. This research therefore aims to develop a plate nesting algorithm tailored to the specific needs of the steel processing company. The research involved designing a three-phase heuristic algorithm that strategically places parts on rectangular sheets, evaluates layout efficiency, and refines the arrangement to maximize sheet utilization and minimize scrap. The algorithm's performance was tested against existing methods, showing strong performance when placing irregular items on larger sheets, and effectively handling cases with a balance of large and small items. Ultimately, this work lays the groundwork for a nesting solution tailored to the specific needs of the steel construction industry, with the potential for future development and customization.
  </p>
</details>


## Auxiliar algorithms 
### Non-fit polygon generation

<details>
  <summary>
    <b>Geometry, shoemaking and the Milk Tray problem</b> &emsp;
    <a href="https://www.newscientist.com/article/mg12316773-700/"> Cuninghame-Gree - (1989) </a>
  </summary>
</details>


<details>
  <summary>
    <b> Computational Geometry </b> &emsp;
    <a href="https://link.springer.com/book/10.1007/978-3-662-04245-8?utm_medium=referral&utm_source=google_books&utm_campaign=3_pier05_buy_print&utm_content=en_08082017"> Berg et al. - (1997) </a>
  </summary>
  <p align=justify>
    Computational geometry emerged from the field of algorithms design and anal­ ysis in the late 1970s. It has grown into a recognized discipline with its own journals, conferences, and a large community of active researchers. The suc­ cess of the field as a research discipline can on the one hand be explained from the beauty of the problems studied and the solutions obtained, and, on the other hand, by the many application domains-computer graphics, geographic in­ formation systems (GIS), robotics, and others-in which geometric algorithms playafundamental role. For many geometric problems the early algorithmic solutions were either slow or difficult to understand and implement. In recent years a number of new algorithmic techniques have been developed that improved and simplified many of the previous approaches. In this textbook we have tried to make these modem algorithmic solutions accessible to a large audience. The book has been written as a textbook for a course in computational geometry, but it can also be used for self-study. 
  </p>
</details>

<details>
  <summary>
    <b>Improved Sliding Algorithm for Generating No-Fit Polygon in the 2D Irregular Packing Problem</b> &emsp;
    <a href="https://www.mdpi.com/2227-7390/10/16/2941"> Luo, Hao - (2022) </a>
  </summary>
  <p align=justify>
  This paper introduces an efficient and robust sliding algorithm for the creation of no-fit polygons. The improved algorithm can cope with complex cases and is given an implementation in detail. The proposed concept of a touching group can simplify the judging process when recognizing the potential translation vector for an orbital polygon. In addition, the generation of the no-fit polygon only involves three main steps based on the proposed concept. The proposed algorithm has a mechanism that searches other start positions to generate a complete no-fit polygon for handling complex cases. To improve the efficiency, many acceleration strategies have been proposed, such as point exclusion strategy and point inclusion test. The robust and efficient performance of the algorithm is tested by well-known benchmark instances and degenerate and complex cases, such as holes, interlocking concavities and jigsaw-type pieces. Experimental results show that the proposed algorithm can produce complete no-fit polygons for complex cases, and acceleration strategies can reduce the creation time of no-fit polygon on benchmark instances by more than sixteen percent on average.
  </p>
</details>
