---
icon: lucide/waypoints
---

Moran's I
---
[Moran's I](https://en.wikipedia.org/wiki/Moran%27s_I) is a measure of spatial autocorrelation. It measures the degree to which a variable is correlated with itself in space. The formula for Moran's I is given by:

$$
I = \frac{N}{W} \frac{\sum_{i=1}^{N} \sum_{j=1}^{N} w_{ij}(x_i - \bar{x})(x_j - \bar{x})}{\sum_{i=1}^{N} (x_i - \bar{x})^2}
$$

LISA
---

$$
I_i = \frac{x_i - \bar{x}}{m_2} \sum_{j=1}^{N} w_{ij} (x_j - \bar{x})
$$

Standardized Z-score:

$$
I_i = z_i \sum_{j=1}^{N} w_{ij} z_j\
$$

$$
m_2 = \frac{\sum_{i=1}^{N} (x_i - \bar{x})^2}{N}\
$$