Using GeoDeepDive (xDD) to Track North American Breeding Bird Survey
Citations in the White and Grey Literatures
================
Last updated: 2019-12-16

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-lightgrey.svg)](https://www.tidyverse.org/lifecycle/#experimental)

## About

This project seeks to identify publications within which the [USGS North
American Breeding Bird Survey](https://www.pwrc.usgs.gov/bbs/) has been
referenced or mentioned. This project uses pre-extracted information
available via API from the [GeoDeepDive](https://geodeepdive.org)
infrastructure.

## Overview of BBS in records available in the GeoDeepDive database.

We can use various search terms to identify potential uses of the
[NABBS](https://www.pwrc.usgs.gov/bbs/) data or results in the
literature. For example, here we found **2487** unique publications
which used any of the following phrases
exactly:

| Exact search phrase                   | Number of unique records in xDD/GDD |
| ------------------------------------- | ----------------------------------- |
| “North American Breeding Bird Survey” | 1430                                |
| “Breeding Bird Survey”                | 2407                                |
| “NABBS”                               | 93                                  |

![](README_files/figure-gfm/pubsvtime-1.png)<!-- -->

When we remove the redundancies in the records returned using the
abovementioned searches,2509 remain.

We can visualize the distribution of records among unique publishers.
Few publications contain the bulk of the records.
![](README_files/figure-gfm/topjrnls-1.png)<!-- -->

Viewing the publications with at least 25 unique records:
![](README_files/figure-gfm/topjrnls2-1.png)<!-- -->

## Results Files

Overviews of the results can be found in the [results](/results) folder
in this repository.

### Total records per publication

Here is a comprehensive list of all publications with relevant terms
(except
“BBL”):

| pubname                                                                                                                           | count |
| :-------------------------------------------------------------------------------------------------------------------------------- | ----: |
|                                                                                                                                   |   858 |
| Acta Ecologica Sinica                                                                                                             |    16 |
| Acta Oecologica                                                                                                                   |    95 |
| Advances in Ecological Research                                                                                                   |     8 |
| African Journal of Ecology                                                                                                        |     3 |
| African Zoology                                                                                                                   |    19 |
| Agriculture, Ecosystems & Environment                                                                                             |   279 |
| Agroecology and Sustainable Food Systems                                                                                          |     3 |
| Angewandte Chemie                                                                                                                 |     2 |
| Angewandte Chemie International Edition                                                                                           |     2 |
| Animal Behaviour                                                                                                                  |    44 |
| Animal Conservation                                                                                                               |   103 |
| Annals of the American Association of Geographers                                                                                 |    57 |
| Annals of the New York Academy of Sciences                                                                                        |    33 |
| Applied Animal Behaviour Science                                                                                                  |     8 |
| Aquatic Conservation: Marine and Freshwater Ecosystems                                                                            |    36 |
| Arboricultural Journal                                                                                                            |     3 |
| Asian Journal of Political Science                                                                                                |     4 |
| Asian Politics & Policy                                                                                                           |     7 |
| Austral Ecology                                                                                                                   |    27 |
| Australian Journal of International Affairs                                                                                       |     2 |
| Basic and Applied Ecology                                                                                                         |    26 |
| Bioacoustics                                                                                                                      |    62 |
| Biodiversity                                                                                                                      |    77 |
| Biological Conservation                                                                                                           |  1883 |
| Biological Journal of the Linnean Society                                                                                         |    62 |
| Biological Reviews                                                                                                                |    47 |
| Biologie in unserer Zeit                                                                                                          |     3 |
| Biomass and Bioenergy                                                                                                             |    24 |
| Biometrical Journal                                                                                                               |     6 |
| Biometrics                                                                                                                        |   156 |
| Bioorganic & Medicinal Chemistry                                                                                                  |    12 |
| Bioorganic & Medicinal Chemistry Letters                                                                                          |     7 |
| Biophysical Journal                                                                                                               |   113 |
| Biotropica                                                                                                                        |    60 |
| Bird Study                                                                                                                        |  1119 |
| Botanical Journal of the Linnean Society                                                                                          |     3 |
| Botany                                                                                                                            |     8 |
| Canadian Journal of Botany                                                                                                        |     3 |
| Canadian Journal of Fisheries and Aquatic Sciences                                                                                |     8 |
| Canadian Journal of Forest Research                                                                                               |    67 |
| Canadian Journal of Physics                                                                                                       |     3 |
| Canadian Journal of Plant Science                                                                                                 |     6 |
| Canadian Journal of Statistics                                                                                                    |    16 |
| Canadian Journal of Zoology                                                                                                       |   407 |
| Cartography and Geographic Information Science                                                                                    |     3 |
| ChemBioChem                                                                                                                       |     1 |
| ChemInform                                                                                                                        |     3 |
| Chemistry - A European Journal                                                                                                    |     3 |
| Circular                                                                                                                          |   320 |
| Cities & Health                                                                                                                   |     3 |
| Communications in Statistics - Simulation and Computation                                                                         |    12 |
| Communications in Statistics - Theory and Methods                                                                                 |    72 |
| Complexity                                                                                                                        |     8 |
| Conservation Biology                                                                                                              |  1688 |
| Conservation in Practice                                                                                                          |    11 |
| Contemporary Physics                                                                                                              |     8 |
| Critical Public Health                                                                                                            |     2 |
| Current Biology                                                                                                                   |     9 |
| Diatom Research                                                                                                                   |     6 |
| Diversity & Distributions                                                                                                         |     6 |
| Diversity and Distributions                                                                                                       |   784 |
| Ecography                                                                                                                         |   864 |
| Ecological Applications                                                                                                           |  1498 |
| Ecological Complexity                                                                                                             |    66 |
| Ecological Economics                                                                                                              |    96 |
| Ecological Entomology                                                                                                             |    14 |
| Ecological Indicators                                                                                                             |   626 |
| Ecological Informatics                                                                                                            |   106 |
| Ecological Modelling                                                                                                              |   327 |
| Ecological Monographs                                                                                                             |    88 |
| Ecological Research                                                                                                               |    11 |
| Ecology                                                                                                                           |  1501 |
| Ecology and Evolution                                                                                                             |   767 |
| Ecology Letters                                                                                                                   |   544 |
| Écoscience                                                                                                                        |   214 |
| Ecosphere                                                                                                                         |   690 |
| Electromagnetic Biology and Medicine                                                                                              |     6 |
| Encyclopedia of the Anthropocene                                                                                                  |    32 |
| Environment Concerns in Rights-of-Way Management 8th International Symposium 12–16 September 2004 Saratoga Springs, New York, USA |    15 |
| Environment: Science and Policy for Sustainable Development                                                                       |    68 |
| Environmental Impact Assessment Review                                                                                            |     3 |
| Environmental Modelling & Software                                                                                                |     3 |
| Environmental Research                                                                                                            |    16 |
| Environmental Reviews                                                                                                             |    30 |
| Environmental Science & Policy                                                                                                    |    22 |
| Environmental Toxicology and Chemistry                                                                                            |    42 |
| Environmetrics                                                                                                                    |   120 |
| Eos, Transactions American Geophysical Union                                                                                      |     3 |
| Ethology                                                                                                                          |    27 |
| Ethology Ecology & Evolution                                                                                                      |    11 |
| European Journal of Organic Chemistry                                                                                             |     6 |
| Evolution                                                                                                                         |    25 |
| Evolutionary Applications                                                                                                         |     3 |
| Fact Sheet                                                                                                                        |    26 |
| Federal Facilities Environmental Journal                                                                                          |     3 |
| Fisheries                                                                                                                         |    22 |
| Fisheries Research                                                                                                                |     8 |
| Forest Ecology and Management                                                                                                     |   803 |
| Forest Policy and Economics                                                                                                       |    16 |
| Freshwater Biology                                                                                                                |    41 |
| Frontiers in Ecology and the Environment                                                                                          |   124 |
| Functional Ecology                                                                                                                |    19 |
| GAP Bulletin                                                                                                                      |    23 |
| GCB Bioenergy                                                                                                                     |    22 |
| General Information Product                                                                                                       |    17 |
| Geographical Review                                                                                                               |    20 |
| Geography Compass                                                                                                                 |     8 |
| Global and Planetary Change                                                                                                       |     8 |
| Global Change Biology                                                                                                             |   865 |
| Global Ecology and Biogeography                                                                                                   |  1016 |
| Global Ecology and Conservation                                                                                                   |    90 |
| Growth and Change                                                                                                                 |     8 |
| Historical Research                                                                                                               |     1 |
| Human and Ecological Risk Assessment: An International Journal                                                                    |     3 |
| Human Dimensions of Wildlife                                                                                                      |    30 |
| Ibis                                                                                                                              |   739 |
| Influenza and Other Respiratory Viruses                                                                                           |     8 |
| Information and Technology Report                                                                                                 |    18 |
| Insect Conservation and Diversity                                                                                                 |     3 |
| Integrated Environmental Assessment and Management                                                                                |    73 |
| Integrative Zoology                                                                                                               |    14 |
| Interdisciplinary Science Reviews                                                                                                 |     3 |
| International Feminist Journal of Politics                                                                                        |     3 |
| International Journal for Parasitology: Parasites and Wildlife                                                                    |    16 |
| International Journal of Agricultural Sustainability                                                                              |    11 |
| International Journal of Applied Earth Observation and Geoinformation                                                             |     6 |
| International Journal of Digital Earth                                                                                            |    35 |
| International Journal of Environmental Studies                                                                                    |     3 |
| International Journal of Food Science & Technology                                                                                |     1 |
| International Journal of Geographical Information Science                                                                         |    57 |
| International Journal of Pest Management                                                                                          |    16 |
| International Journal of Remote Sensing                                                                                           |    14 |
| International Journal of Science Education, Part B                                                                                |    24 |
| International Journal of Sustainable Development & World Ecology                                                                  |    32 |
| International Statistical Review                                                                                                  |     3 |
| Internet Reference Services Quarterly                                                                                             |     3 |
| ISPRS Journal of Photogrammetry and Remote Sensing                                                                                |     3 |
| Journal for Nature Conservation                                                                                                   |    60 |
| Journal of Animal Ecology                                                                                                         |   279 |
| Journal of Applied Ecology                                                                                                        |   953 |
| Journal of Applied Microbiology                                                                                                   |     8 |
| Journal of Applied Statistics                                                                                                     |    32 |
| Journal of Arid Environments                                                                                                      |    75 |
| Journal of Avian Biology                                                                                                          |   191 |
| Journal of Biogeography                                                                                                           |   734 |
| Journal of Biomedical Materials Research Part A                                                                                   |     2 |
| Journal of Computational and Graphical Statistics                                                                                 |    33 |
| Journal of Contemporary Asia                                                                                                      |     3 |
| Journal of Ecology                                                                                                                |    24 |
| Journal of Environmental Management                                                                                               |    51 |
| Journal of Environmental Science and Health, Part A                                                                               |     8 |
| Journal of Evolutionary Biology                                                                                                   |    38 |
| Journal of Experimental Marine Biology and Ecology                                                                                |     3 |
| Journal of Field Ornithology                                                                                                      |   873 |
| Journal of Fish Biology                                                                                                           |     8 |
| Journal of Forensic Sciences                                                                                                      |     8 |
| Journal of Geography                                                                                                              |    16 |
| Journal of Geophysical Research: Atmospheres                                                                                      |     3 |
| Journal of Great Lakes Research                                                                                                   |    37 |
| Journal of International Wildlife Law & Policy                                                                                    |     8 |
| Journal of Land Use Science                                                                                                       |     8 |
| Journal of Medical Engineering & Technology                                                                                       |     1 |
| Journal of Molecular Biology                                                                                                      |   109 |
| Journal of Statistical Computation and Simulation                                                                                 |     3 |
| Journal of Sustainable Forestry                                                                                                   |     6 |
| Journal of the American Statistical Association                                                                                   |    41 |
| Journal of the American Water Resources Association                                                                               |     3 |
| Journal of the Royal Statistical Society: Series C (Applied Statistics)                                                           |    28 |
| Journal of Wildlife Management                                                                                                    |  1424 |
| Journal of Zoology                                                                                                                |    17 |
| Lake and Reservoir Management                                                                                                     |    68 |
| Land Use Policy                                                                                                                   |    20 |
| Landscape and Urban Planning                                                                                                      |   248 |
| Landscape Research                                                                                                                |     8 |
| Leisure Sciences                                                                                                                  |     2 |
| Limnology and Oceanography: Methods                                                                                               |    16 |
| Local Environment                                                                                                                 |     3 |
| Mammal Review                                                                                                                     |    53 |
| Managing Sport and Leisure                                                                                                        |     2 |
| Marine Mammal Science                                                                                                             |    19 |
| Methods in Ecology and Evolution                                                                                                  |   686 |
| Methods in Enzymology                                                                                                             |    36 |
| Molecular Ecology                                                                                                                 |   106 |
| Molecular Physics                                                                                                                 |     1 |
| Natural Gas & Electricity                                                                                                         |     3 |
| Natural Resource Modeling                                                                                                         |     6 |
| New Journal of Botany                                                                                                             |     3 |
| New Phytologist                                                                                                                   |     8 |
| New Zealand Journal of Marine and Freshwater Research                                                                             |     8 |
| New Zealand Journal of Zoology                                                                                                    |    16 |
| Northern History                                                                                                                  |     2 |
| Oikos                                                                                                                             |   415 |
| Open-File Report                                                                                                                  |   247 |
| Ostrich                                                                                                                           |    26 |
| Pest Management Science                                                                                                           |     3 |
| Plant Ecology & Diversity                                                                                                         |     6 |
| PLOS ONE                                                                                                                          |    84 |
| Polar Geography                                                                                                                   |     3 |
| Preventive Veterinary Medicine                                                                                                    |     8 |
| Process Biochemistry                                                                                                              |     1 |
| Professional Paper                                                                                                                |   580 |
| Reference Module in Life Sciences                                                                                                 |    63 |
| Remote Sensing in Ecology and Conservation                                                                                        |     6 |
| Remote Sensing of Environment                                                                                                     |   268 |
| Resource Publication                                                                                                              |    44 |
| Restoration Ecology                                                                                                               |    72 |
| Reviews of Geophysics                                                                                                             |    35 |
| Ringing & Migration                                                                                                               |   171 |
| Risk Analysis                                                                                                                     |     8 |
| River Research and Applications                                                                                                   |    14 |
| Rocks & Minerals                                                                                                                  |     1 |
| Scandinavian Journal of Forest Research                                                                                           |     6 |
| Science & Technology Libraries                                                                                                    |     8 |
| Science News                                                                                                                      |    29 |
| Scientific Investigations Report                                                                                                  |   163 |
| Separation Science and Technology                                                                                                 |     2 |
| Significance                                                                                                                      |    17 |
| Society & Natural Resources                                                                                                       |     8 |
| Statistics in Medicine                                                                                                            |     3 |
| Synthetic Communications                                                                                                          |     2 |
| Systematics and Biodiversity                                                                                                      |    14 |
| The Journal of Wildlife Management                                                                                                |  1473 |
| The Pacific Review                                                                                                                |     6 |
| The Reference Librarian                                                                                                           |    16 |
| The RUSI Journal                                                                                                                  |     1 |
| The Sciences                                                                                                                      |     6 |
| Transactions of the New York Academy of Sciences                                                                                  |     3 |
| Transactions of the Philological Society                                                                                          |     1 |
| Trends in Ecology & Evolution                                                                                                     |   128 |
| Water Resources Research                                                                                                          |     3 |
| Water-Resources Investigations Report                                                                                             |    18 |
| Wildlife Monographs                                                                                                               |    35 |
| Wildlife Society Bulletin                                                                                                         |   948 |
| Zoology in the Middle East                                                                                                        |     3 |
| Zoonoses and Public Health                                                                                                        |     3 |

## More Information

### This project relies on the UW Deepdive Infrastructure

[See the UW deepdive
infrastructure](UW-Deepdive-Infrastructure/app-template) for more
details. Check out [the
wiki](https://github.com/UW-Deepdive-Infrastructure/app-template/wiki)
for more information on getting started.

### Disclaimer

This software is preliminary or provisional and is subject to revision.
It is being provided to meet the need for timely best science. The
software has not received final approval by the U.S. Geological Survey
(USGS). No warranty, expressed or implied, is made by the USGS or the
U.S. Government as to the functionality of the software and related
material nor shall the fact of release constitute any such warranty. The
software is provided on the condition that neither the USGS nor the U.S.
Government shall be held liable for any damages resulting from the
authorized or unauthorized use of the software.
