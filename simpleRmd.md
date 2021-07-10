---
title: "Simple Rmd"
author: "Jon Williams"
date: "7/10/2021"
output: 
  html_document: 
    keep_md: yes
---



## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

## Including Plots {.tabset}

You can also embed plots, for example:


### pressure 


```{=html}
<div id="htmlwidget-a408d6b0bb7a68ce67f4" style="width:672px;height:480px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-a408d6b0bb7a68ce67f4">{"x":{"data":[{"x":[0,20,40,60,80,100,120,140,160,180,200,220,240,260,280,300,320,340,360],"y":[0.0002,0.0012,0.006,0.03,0.09,0.27,0.75,1.85,4.2,8.8,17.3,32.1,57,96,157,247,376,558,806],"text":["temperature:   0<br />pressure:   0.0002","temperature:  20<br />pressure:   0.0012","temperature:  40<br />pressure:   0.0060","temperature:  60<br />pressure:   0.0300","temperature:  80<br />pressure:   0.0900","temperature: 100<br />pressure:   0.2700","temperature: 120<br />pressure:   0.7500","temperature: 140<br />pressure:   1.8500","temperature: 160<br />pressure:   4.2000","temperature: 180<br />pressure:   8.8000","temperature: 200<br />pressure:  17.3000","temperature: 220<br />pressure:  32.1000","temperature: 240<br />pressure:  57.0000","temperature: 260<br />pressure:  96.0000","temperature: 280<br />pressure: 157.0000","temperature: 300<br />pressure: 247.0000","temperature: 320<br />pressure: 376.0000","temperature: 340<br />pressure: 558.0000","temperature: 360<br />pressure: 806.0000"],"type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(0,0,0,1)","opacity":1,"size":5.66929133858268,"symbol":"circle","line":{"width":1.88976377952756,"color":"rgba(0,0,0,1)"}},"hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null}],"layout":{"margin":{"t":26.2283105022831,"r":7.30593607305936,"b":28.4931506849315,"l":25.5707762557078},"plot_bgcolor":"rgba(235,235,235,1)","paper_bgcolor":"rgba(255,255,255,1)","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187},"xaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[-18,378],"tickmode":"array","ticktext":[null],"categoryorder":"array","categoryarray":[null],"nticks":null,"ticks":"outside","tickcolor":"rgba(51,51,51,1)","ticklen":3.65296803652968,"tickwidth":0.66417600664176,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"","size":11.689497716895},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(255,255,255,1)","gridwidth":0.66417600664176,"zeroline":false,"anchor":"y","title":{"text":"temperature","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187}},"hoverformat":".2f"},"yaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[-40.29979,846.29999],"tickmode":"array","ticktext":[null],"categoryorder":"array","categoryarray":[null],"nticks":null,"ticks":"outside","tickcolor":"rgba(51,51,51,1)","ticklen":3.65296803652968,"tickwidth":0.66417600664176,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"","size":11.689497716895},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(255,255,255,1)","gridwidth":0.66417600664176,"zeroline":false,"anchor":"x","title":{"text":"pressure","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187}},"hoverformat":".2f"},"shapes":[{"type":"rect","fillcolor":null,"line":{"color":null,"width":0,"linetype":[]},"yref":"paper","xref":"paper","x0":0,"x1":1,"y0":0,"y1":1}],"showlegend":false,"legend":{"bgcolor":"rgba(255,255,255,1)","bordercolor":"transparent","borderwidth":1.88976377952756,"font":{"color":"rgba(0,0,0,1)","family":"","size":11.689497716895}},"hovermode":"closest","barmode":"relative"},"config":{"doubleClick":"reset","showSendToCloud":false},"source":"A","attrs":{"cf7a4d5d6455":{"x":{},"y":{},"type":"scatter"}},"cur_data":"cf7a4d5d6455","visdat":{"cf7a4d5d6455":["function (y) ","x"]},"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

### mtcars 


```{=html}
<div id="htmlwidget-37e97d207158e2cea170" style="width:672px;height:480px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-37e97d207158e2cea170">{"x":{"data":[{"x":[110,110,93,110,175,105,245,62,95,123,123,180,180,180,205,215,230,66,52,65,97,150,150,245,175,66,91,113,264,175,335,109],"y":[21,21,22.8,21.4,18.7,18.1,14.3,24.4,22.8,19.2,17.8,16.4,17.3,15.2,10.4,10.4,14.7,32.4,30.4,33.9,21.5,15.5,15.2,13.3,19.2,27.3,26,30.4,15.8,19.7,15,21.4],"text":["hp: 110<br />mpg: 21.0","hp: 110<br />mpg: 21.0","hp:  93<br />mpg: 22.8","hp: 110<br />mpg: 21.4","hp: 175<br />mpg: 18.7","hp: 105<br />mpg: 18.1","hp: 245<br />mpg: 14.3","hp:  62<br />mpg: 24.4","hp:  95<br />mpg: 22.8","hp: 123<br />mpg: 19.2","hp: 123<br />mpg: 17.8","hp: 180<br />mpg: 16.4","hp: 180<br />mpg: 17.3","hp: 180<br />mpg: 15.2","hp: 205<br />mpg: 10.4","hp: 215<br />mpg: 10.4","hp: 230<br />mpg: 14.7","hp:  66<br />mpg: 32.4","hp:  52<br />mpg: 30.4","hp:  65<br />mpg: 33.9","hp:  97<br />mpg: 21.5","hp: 150<br />mpg: 15.5","hp: 150<br />mpg: 15.2","hp: 245<br />mpg: 13.3","hp: 175<br />mpg: 19.2","hp:  66<br />mpg: 27.3","hp:  91<br />mpg: 26.0","hp: 113<br />mpg: 30.4","hp: 264<br />mpg: 15.8","hp: 175<br />mpg: 19.7","hp: 335<br />mpg: 15.0","hp: 109<br />mpg: 21.4"],"type":"scatter","mode":"markers","marker":{"autocolorscale":false,"color":"rgba(0,0,0,1)","opacity":1,"size":5.66929133858268,"symbol":"circle","line":{"width":1.88976377952756,"color":"rgba(0,0,0,1)"}},"hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null}],"layout":{"margin":{"t":26.2283105022831,"r":7.30593607305936,"b":28.4931506849315,"l":25.5707762557078},"plot_bgcolor":"rgba(235,235,235,1)","paper_bgcolor":"rgba(255,255,255,1)","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187},"xaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[37.85,349.15],"tickmode":"array","ticktext":[null],"categoryorder":"array","categoryarray":[null],"nticks":null,"ticks":"outside","tickcolor":"rgba(51,51,51,1)","ticklen":3.65296803652968,"tickwidth":0.66417600664176,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"","size":11.689497716895},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(255,255,255,1)","gridwidth":0.66417600664176,"zeroline":false,"anchor":"y","title":{"text":"hp","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187}},"hoverformat":".2f"},"yaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[9.225,35.075],"tickmode":"array","ticktext":[null],"categoryorder":"array","categoryarray":[null],"nticks":null,"ticks":"outside","tickcolor":"rgba(51,51,51,1)","ticklen":3.65296803652968,"tickwidth":0.66417600664176,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"","size":11.689497716895},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(255,255,255,1)","gridwidth":0.66417600664176,"zeroline":false,"anchor":"x","title":{"text":"mpg","font":{"color":"rgba(0,0,0,1)","family":"","size":14.6118721461187}},"hoverformat":".2f"},"shapes":[{"type":"rect","fillcolor":null,"line":{"color":null,"width":0,"linetype":[]},"yref":"paper","xref":"paper","x0":0,"x1":1,"y0":0,"y1":1}],"showlegend":false,"legend":{"bgcolor":"rgba(255,255,255,1)","bordercolor":"transparent","borderwidth":1.88976377952756,"font":{"color":"rgba(0,0,0,1)","family":"","size":11.689497716895}},"hovermode":"closest","barmode":"relative"},"config":{"doubleClick":"reset","showSendToCloud":false},"source":"A","attrs":{"cf7a679b30d2":{"x":{},"y":{},"type":"scatter"}},"cur_data":"cf7a679b30d2","visdat":{"cf7a679b30d2":["function (y) ","x"]},"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
```

