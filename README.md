# Inducing non-orthogonal and non-linear decision boundaries in decision trees via interactive basis functions

Paez, A., López, F., Ruiz, M., Camacho, M., 2019. Inducing non-orthogonal and non-linear decision boundaries in decision trees via interactive basis functions. Expert Systems with Applications 122, 183-206.

https://doi.org/10.1016/j.eswa.2018.12.041

## Abstract

Decision Trees (DTs) are a machine learning technique widely used for regression and classification purposes. Conventionally, the decision boundaries of Decision Trees are orthogonal to the features under consideration. A well-known limitation of this is that the algorithm may fail to find optimal partitions, or in some cases any partitions at all, depending on the underlying distribution of the data. To remedy this limitation, several modifications have been proposed that allow for oblique decision boundaries. The objective of this paper is to propose a new strategy for generating flexible decision boundaries by means of interactive basis functions (IBFs). We show how oblique decision boundaries can be obtained as a particular case of IBFs, and in addition how non-linear decision boundaries can be induced. One attractive aspect of the strategy proposed in this paper is that training Decision Trees with IBFs does not require custom software, since the functions can be precalculated for use in any existing implementation of the algorithm. Since the underlying mechanisms remain unchanged there is no substantial computational overhead compared to conventional trees. Furthermore, this also means that IBFs can be used in any extensions of the Decision Tree algorithm, such as evolutionary trees, boosting, and bagging. We conduct a benchmarking exercise to understand under which conditions the use of IBFs can improve model the performance. In addition, we present three empirical applications that illustrate the approach in classification and regression. As part of discussing the empirical applications, we introduce a device called decision charts to facilitate the interpretation of DTs with IBFs. Finally, we conclude the paper by outlining some directions for future research.

## Keywords

- Decision trees
- Oblique trees
- Oblique decision boundaries
- Non-orthogonal decision boundaries
- Non-linear decision boundaries
- Basis functions
- Interactive basis functions
- Simulation experiments
