%%R
library(plotly)
p_math_verbal_scatter <- plot_ly(data = bigclass, x = ~Math, y = ~Verbal, type = 'scatter', mode = 'markers', color = ~sex, colors = c('#0072B2', '#D55E00'))
saveWidget(p_math_verbal_scatter, file = 'media/plots/math_verbal_scatter.html', selfcontained = TRUE)
