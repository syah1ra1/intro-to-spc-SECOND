---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Statistical Analysis & Process Control Applications
#### NURIN SYAHIRA BINTI MOHD SHUKRI
#### Universiti Malaysia Perlis
#### [s251043273@studentmail.unimap.edu.my](mailto:s251043273@studentmail.unimap.edu.my)

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Foundation Concepts
**Key Concepts:**
- Energy conservation principles derived from core statistical mechanics and engineering frameworks @carnot1824.
- Thermodynamic baseline calculations:
  $$\Delta U = Q - W$$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="System Overview Overview"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics applied to system modeling:

$$\Delta U = Q - W$$

The work done $W$ is treated as positive when the system boundary expands against an external pressure vector.
:::

::: {.column width="50%"}
<video data-src="media/videos/sample.mp4" data-autoplay loop muted width="100%"></video>
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- Examination of P, V, and T boundary relationships.
- Use the integrated slider interface to adjust localized pressure limits.
- Observe the phase transition boundaries in real time.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Student Performance Insights
**Key Observations:**

- Evaluation of student scores from the `bigclass` tracking dataset.
- Clear stratification observed between quantitative metrics and performance tiers.
- Measurement variations and errors are bounded utilizing $\epsilon$ variation models.

> Note: Outliers can be filtered dynamically using the interactive legend on the right.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/academic_analysis.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Math vs Verbal Score Analysis
**Key Observations:**

- This scatter plot visualizes the direct correlation between students' Mathematics and Verbal scores.
- Data points are segmented by demographic attributes to observe behavioral clusters.
- Allows for swift tracking of performance correlations across different disciplines.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/math_verbal_scatter.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Math Score Distribution
**Key Observations:**

- Frequency distribution tracking mathematics scores from the target population.
- The histogram isolates student density spikes across explicit testing ranges.
- Essential for mapping foundational capabilities and baseline capability metrics.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/math_score_histogram.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Math Score Distribution (Optimized Model)
**Key Observations:**

- Iterated histogram visualization containing updated metrics from the `bigclass` array.
- Allows verification of model stability across shifting dataset configurations.
- Demonstrates process optimization and comparative stability analysis.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/math_score_histogram_new.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::


---

:::: {.columns}
::: {.column width="50%"}
### Machine Data Analysis: Temperature Trend
**Key Observations:**

- This section introduces the `machine_data` dataset, which contains sensor readings from manufacturing machines.
- We can analyze the `Temperature` over `Timestamp` to identify operational patterns or anomalies.
- The dataset includes `Machine`, `Pressure`, `PartLength`, and `PartResistance` which can be further explored.
- Understanding these trends is crucial for process control and predictive maintenance.
:::

::: {.column width="50%"}
<iframe
  data-src="media/plots/machine_data_temperature_plot.html"
  width="100%"
  height="500px"
  style="border:none;"
  scrolling="no">
</iframe>
:::
::::


---

:::: {.columns}
::: {.column width="50%"}
### Student Performance Insights
**Key Observations:**

- Evaluation of student scores from the `bigclass` dataset.
- Clear stratification observed between quantitative metrics.
- Measurement errors are bounded by $\epsilon$ variation models.

> Note: Outliers can be filtered dynamically using the legend on the right.
:::

::: {.column width="50%"}
<iframe
  data-src="media/plots/academic_analysis.html"
  width="100%"
  height="500px"
  style="border:none;"
  scrolling="no">
</iframe>
:::
::::


---

:::: {.columns}
::: {.column width="50%"}
### Math Score Distribution
**Key Observations:**

- Visualization of student mathematics scores from the `bigclass` dataset.
- The histogram shows the frequency of scores across different ranges.
- This helps in understanding the overall academic performance in Math.
:::

::: {.column width="50%"}
<iframe
  data-src="media/plots/math_score_histogram.html"
  width="100%"
  height="500px"
  style="border:none;"
  scrolling="no">
</iframe>
:::
::::


---

:::: {.columns}
::: {.column width="50%"}
### Math vs Verbal Score Analysis
**Key Observations:**

- This scatter plot visualizes the relationship between students' Mathematics and Verbal scores.
- Points are colored by 'sex' to observe any potential differences.
- Allows for quick identification of correlation or clusters in academic performance.
:::

::: {.column width="50%"}
<iframe
  data-src="media/plots/math_verbal_scatter.html"
  width="100%"
  height="500px"
  style="border:none;"
  scrolling="no">
</iframe>
:::
::::


---

:::: {.columns}
::: {.column width="50%"}
### Math Score Distribution
**Key Observations:**

- Visualization of student mathematics scores from the `bigclass` dataset.
- The histogram shows the frequency of scores across different ranges.
- This helps in understanding the overall academic performance in Math.
:::

::: {.column width="50%"}
<iframe
  data-src="media/plots/math_score_histogram.html"
  width="100%"
  height="500px"
  style="border:none;"
  scrolling="no">
</iframe>
:::
::::


---

:::: {.columns}
::: {.column width="50%"}
### Math Score Distribution (New)
**Key Observations:**

- A new visualization of student mathematics scores from the `bigclass` dataset.
- The histogram shows the frequency of scores across different ranges.
- This helps in understanding the overall academic performance in Math.
:::

::: {.column width="50%"}
<iframe
  data-src="media/plots/math_score_histogram_new.html"
  width="100%"
  height="500px"
  style="border:none;"
  scrolling="no">
</iframe>
:::
::::

---
# Bibliography
<div id="refs"></div>
