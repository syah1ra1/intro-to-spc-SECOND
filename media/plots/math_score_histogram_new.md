%%R
library(plotly)
p_math_hist_new <- plot_ly(data = bigclass, x = ~Math, type = 'histogram', marker = list(color = '#0072B2'))
saveWidget(p_math_hist_new, file = 'media/plots/math_score_histogram_new.html', selfcontained = TRUE)
