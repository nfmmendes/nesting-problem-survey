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

[Yang, Ling - (2009)](https://www.sciencedirect.com/science/article/abs/pii/S0957417407005192?via%3Dihub)

[Burke et. al. - (2010)](https://pubsonline.informs.org/doi/abs/10.1287/opre.1090.0770)

[Alves et. al. - (2012)](https://www.sciencedirect.com/science/article/abs/pii/S030505481100253X)

[Alves, et. al - (2012)](https://www.hindawi.com/journals/mpe/2012/254346/)

[Alvares-Valdes, Martinez, Tamarit - (2013)](https://www.sciencedirect.com/science/article/abs/pii/S0925527313001692)

[Canellidis, Giannatsis, Dedoussis - (2013)](https://www.sciencedirect.com/science/article/abs/pii/S0010448512002783)

[Elkeran - (2013)](https://www.sciencedirect.com/science/article/abs/pii/S0377221713005080)
* State-of-the-art heuristic

[Toledo, et. al. - (2013)](https://www.sciencedirect.com/science/article/abs/pii/S0925527313001722)

[Amaro Junior, Pinheiro, Saraiva - (2013)](https://www.sciencedirect.com/science/article/pii/S1474667016321590)

[Sherif, Jawahar, Balamurali - (2014)](https://www.sciencedirect.com/science/article/abs/pii/S0278612514000661)

[Leao et. al. - (2014)](https://www.tandfonline.com/doi/abs/10.1080/00207543.2015.1041571)

[Pinheiro, Amaro Junior, Saraiva - (2014)](https://www.tandfonline.com/doi/full/10.1080/0951192X.2022.2050302)

[Martins, et. al. - (2016)](https://www.tandfonline.com/doi/full/10.1080/0951192X.2015.1033018?scroll=top&needAccess=true)

[Pinto, et. al - (2016)](https://www.inderscienceonline.com/doi/epdf/10.1504/IJBEX.2016.075594)

[Mundim, Andretta, Queiroz - (2017)](https://www.sciencedirect.com/science/article/abs/pii/S0957417417302233)

[Mundim et. al. - (2017)](https://www.tandfonline.com/doi/abs/10.1080/00207543.2017.1394598)

[Wang, Hanselman, Gounaris - (2018)](https://link.springer.com/article/10.1007/s10898-018-0637-y)

[Cherri et. al. - (2019)](https://www.sciencedirect.com/science/article/pii/S2214716019300594)

[Kierkosz, Luczak - (2019)](https://cejsh.icm.edu.pl/cejsh/element/bwmeta1.element.desklight-335f3bdb-e516-4d4f-a360-288a78635757)

[Amaro Junior, et al - (2020)](https://ieeexplore.ieee.org/abstract/document/9185794)

[Chehrazad, Roose, Wauters - (2022)](https://www.sciencedirect.com/science/article/abs/pii/S0377221721008936)

[Sato, Martins, Tsuzuki - (2022)](https://www.tandfonline.com/doi/full/10.1080/0951192X.2022.2050302)

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
