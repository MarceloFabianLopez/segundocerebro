#test/hábito/ejercicio 

# Exercise habit
Think about what you want to achieve from running or jogging. Issues to consider may include:

-   **Getting fit** – if you're a beginner, you should start with brisk walking, progress to jogging and work up to running. This should take a few months.
-   **General fitness** – mix your running with other forms of exercise (such as swimming or team sports) to maximise your overall fitness.
-   **Weight loss** – adjust your diet to include plenty of fresh fruits and vegetables, lean meats, wholegrain cereals and low-fat dairy products. Cut back on dietary fats, takeaway foods, soft drinks and sugar.
-   **Companionship** – you could run with a friend or join a local running club.
-   **Competition** – running clubs may offer competitive events. Most clubs have sessions designed for beginners through to advanced runners. You can pit your running skills against others in fun runs or marathons. Many community-based running events cater for people of all ages and abilities. Join a local orienteering club to combine running with the challenge of navigating through various environments.

## Alternativas seguimiento hábitos
### Enlaces entrantes + Plugin Dataview
``` dataview
list
from [[DEPORTE]]
where file.ctime.year = 2021 and file.ctime.month= 3 
```


### Metadatos + Plugin Dataview
``` dataview
table nutrición, deporte, meditación, consciencia, foco, ayuno16h, vicq
from #diario 
where regexmatch("^2021-05", file.name)
sort file.name ascending

```


### Metadatos + Plugin Tracker

GRÁFICA LINEAL
``` tracker
searchType: frontmatter
searchTarget: foco
folder: 900 - 📆 DIARIO - JOURNAL
startDate: 2021-05-01
endDate: 2021-05-31
line:
    title: "Evolución foco"
    xAxisLabel: Number
    yAxisLabel: Value
    lineColor: red
	
```

lineColor: yellow, blue, white, red, black, orange, purple, green, cyan

BARRAS
``` tracker
searchType: frontmatter
searchTarget: foco
folder: 900 - 📆 DIARIO - JOURNAL
startDate: 2021-05-01
endDate: 2021-05-31
bar:
    title: "Evolución foco"
    xAxisLabel: Number
    yAxisLabel: Value
```

TERMÓMETRO (BULLET)

``` tracker
searchType: frontmatter
searchTarget: nutrición
folder: 900 - 📆 DIARIO - JOURNAL
startDate: 2021-05-01
endDate: 2021-05-31
bullet:
    title: "Meditation"
	dataset: 0
    orientation: vertical
	range: 3, 6, 10
	rangeColor: darkgray, silver, lightgray
	value: "{{average}}"
	valueUnit: times
	valueColor: steelblue
	showMarker: true
	markerValue: 5
	markerColor: red
```

RESUMEN VALORES NUTRICIÓN
``` tracker
searchType: frontmatter 
searchTarget: nutrición
folder: 900 - 📆 DIARIO - JOURNAL
startDate: 2021-05-01
endDate: 2021-05-31
summary:
  template: "Mínimo: {{min()}} puntos\nMáximo: {{max()}} puntos\nMediana: {{median()}} puntos\nMedia: {{average()}} puntos"
```