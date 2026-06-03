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

## Sample slides
#### NURIN SYAHIRA BINTI MOHD SHUKRI
#### Universiti Malaysia Perlis
#### [s251043273@studentmail.unimap.edu.my](mailto:s251043273@studentmail.unimap.edu.my)

<audio id="bg-music" src="media/audio/sb.m4a" loop></audio>

<div id="audio-credit"
     style="position: absolute; bottom: 40px; right: 20px; font-size: 0.6em; opacity: 0.6;">
  Music: “Adrift” by Scott Buckley (CC BY 4.0)
</div>

<script>
  document.addEventListener('DOMContentLoaded', () => {
    const audio = document.getElementById('bg-music');
    const credit = document.getElementById('audio-credit');

    // hide credit by default
    credit.style.display = 'none';

    const test = new Audio('media/audio/bgm.mp3');

    test.addEventListener('canplaythrough', () => {
      // bgm.mp3 exists → use it, keep credit hidden
      audio.src = 'media/audio/bgm.mp3';
    }, { once: true });

    test.addEventListener('error', () => {
      // bgm.mp3 missing → sb.m4a will play → show credit
      credit.style.display = 'block';
    }, { once: true });

    document.addEventListener('click', () => {
      if (Reveal.getIndices().h === 0) {
        audio.volume = 0.5;
        audio.play();
      }
    }, { once: true });

    Reveal.on('slidechanged', (event) => {
      if (event.indexh > 0) { audio.pause(); }
      else { audio.play(); }
    });
  });
</script>

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Slide one
**Key Concepts:**
- Energy conservation per @carnot1824.
- $\Delta U = Q - W$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics:

$$\Delta U = Q - W$$

The work done $W$ is positive when the system expands against an external pressure.
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

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
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
# Bibliography
<div id="refs"></div>
