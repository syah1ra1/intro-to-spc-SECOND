%%R
library(plotly)
p <- plot_ly(data = bigclass, x = ~Math, y = ~Verbal, type = 'scatter', mode = 'markers', color = ~sex, colors = c('#0072B2', '#D55E00'))
saveWidget(p, file = 'media/plots/academic_analysis.html', selfcontained = TRUE)
