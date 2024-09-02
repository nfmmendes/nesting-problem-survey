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
    <a href="https://ieeexplore.ieee.org/abstract/document/9185794">  Amaro Junior, et al - (2020) </a>
  </summary>
  <p align=justify>
    The irregular strip packing problem (ISPP) is a combinatorial optimisation problem that has applicability in several industrial processes since it aims for the efficient use of material. Most of the techniques reported in the literature for solving the ISPP employ metaheuristics as they can cope with complex requirements that prevent the use of exact model formulations. This paper presents a biased random-key genetic algorithm (BRKGA) that uses the dotted board model to compute the fitnesses of candidate solutions aiming for the minimisation of the height of the large object. The algorithm allows the pieces to rotate in order to achieve better layouts. Computational experiments using instances from the literature were conducted to demonstrate the efficiency of the proposed method, with promising results.
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
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417423002178">  </a>
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
    <b>Optimal decomposition approach for solving large nesting and scheduling problems of additive manufacturing systems</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/pii/S0377221724001784">  Nascimento, et al - (2024) </a>
  </summary>
  <p align=justify>
    This paper addresses the challenges associated with nesting and production scheduling in additive manufacturing (AM). The problem studied consists of grouping a set of parts into batches, which are then assigned to and sequenced across the available machines, guaranteeing the production of all parts. This work stands out by proposing exact methods for the AM nesting and scheduling problem considering irregular-shaped parts with specific release dates, processing times, and due dates, with the aim of minimizing the cumulative tardiness. The proposed approaches include two logic-based Benders decompositions: one combining Mixed Integer Programming (MIP) and Constraint Programming (CP), and the other relying solely on CP. To deal with the sub-problems, a strategic procedure was developed to reduce the solution space while maintaining low resolution times per iteration. Problem-specific cuts are also generated to improve the efficiency of these approaches. Computational experiments show that both decompositions significantly outperform a prior monolithic CP model, with the decomposition based solely on CP yielding the best results. Moreover, the results show that this approach has the potential to achieve similar computational performance of non-exact approaches that are currently considered state-of-the-art. A set of instances is provided to serve as a benchmark for future studies.
  </p>
</details>

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
    <b>An expert system to react to defective areas in nesting problems</b> &emsp;
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S095741742201363X"> Bartmeyer et. al. -(2022) </a>
  </summary>
  <p align=justify>
    Production plans in the textile industry, and other practical applications, involve cutting irregular pieces from raw materials. Defective areas in the raw material may be detected during the cutting process, requiring an adaptation of the original layout. The response time to provide an alternative layout is short, precluding the use of exact methods to overcome defective areas. The main contribution of this paper is to provide an expert system to quickly obtain an alternative layout, overcoming defective areas in the object. The expert system comprises a greedy heuristic based on the allocation sequence suggested by reinforcement learning. Computational experiments have two main objectives. The first one is to validate reinforcement learning as a suitable strategy to tackle nesting problems. The results attest to the ability of the strategy to achieve the best results in the literature. The second objective is to show the ability of the expert system to provide alternative layouts within a short response time. The quality of the solutions obtained by the expert system evidence the strength of the proposed system in overcoming defective areas.
  </p>
</details>

<details>
  <summary>
    <b>A reinforcement learning algorithm for the 2D-rectangular strip packing proble</b> &emsp;
    <a href="https://iopscience.iop.org/article/10.1088/1742-6596/2181/1/012002/pdf"> Zhao, Hao, Fang - (2021) </a>
  </summary>
  <p align=justify>
    Packing problems, also known as nesting problems or bin packing problems, are classic and popular NP-hard problems with high computational complexity. Inspired by classic reinforcement learning (RL), we established a mathematical model for two-dimensional (2D) irregular-piece packing combined with characteristics of 2D irregular pieces. An RL algorithm based on Monte Carlo learning (MC), Q-learning, and Sarsa-learning is proposed in this paper to solve a 2D irregular-piece packing problem. Additionally, mechanisms of reward–return and strategy-update based on piece packing were designed. Finally, the standard test case of irregular pieces was used for experimental testing to analyze the optimization effect of the algorithm. The experimental results show that the proposed algorithm can successfully realize packing of 2D irregular pieces. A similar or better optimization effect can be obtained compared to some classical heuristic algorithms. The proposed algorithm is an early attempt to use machine learning to solve 2D irregular packing problems. On the one hand, our hybrid RL algorithm can provide a basis for subsequent deep reinforcement learning (DRL) to solve packing problems, which has far-reaching theoretical significance. On the other hand, it has practical significance for improving the utilization rate of raw materials and broadening the application field of machine learning.
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
