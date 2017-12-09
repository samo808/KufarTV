# Rotating dashboards in Tableau

One day I got a project with the purpose "To create a way for communication of our company bussness metrics to everyone". After some consideration and thinking over all pros and cons we decided to choose our TV sets in the office. Then we had to choose a tool for this: 
1. Google Slides & Google Sheets (with built-in options for rotating but worse visualisation)
2. Tableau (nice ETL and Visualization but without rotation option (even good enough workarounds were not found)
We choose the second one and here I tell you about how to create rotating dashboards and how to do it in Tableau.

## Plan:

[Why you need TV Dashboards](#why-you-need-tv-dashboards)

[Main rules of building TV Dashboard](#main-rules-of-building-tv-dashboard)

[Rotating Dashboards in Tableau](#rotating-dashboards-in-tableau)


## Why you need TV Dashboards

1. to Show main company indicators in one place
```
You likely recieve a lot of reports and emails, use different services for getting different measures. 
Something important sometimes pass you by. So it would be a dream to have at least the main indicators on hand.

But what are they - the main indicators? It's the first and very important question you are to answer before getting started.
Сarry out a survey and try to extract all usefull information.
```

2. to Form transparency & data-driven culture
```
Transparency means that employees feel the trust, know the company shares the joys and challenges. 
It's important. But don't forget about confidentiality.
Something company wants to keep inside or some information can be misinterpreted.
```

3. to Motivate your employees
```
One possible way is to create separate google slides for each Head of Department 
and to allow her/him to share the best results of the Department. 
Other colleagues really feel proud of the best staff of the month.
```

## Main rules of building TV Dashboard

1. Simplicity & clarity
```
My practice shows that too few persons would stay and stare at multiple charts on 1 slide.
It's better to place just 1 or 2 measures per slide and rotate multiple ones at slightly higher speed.
```

2. Logical grouping and consistency
```
For people passing by it's easier to get sliding information if it has some stucture or story.
1. Use color coding for groups of metrics. 
2. Use the same type of graphs.
```

3. Nice design
```
Some researchs shows that people stronger believe in pretty charts rather than in negligent ones.
So it's really cool if you made something you can meditate.
```

## Rotating Dashboards in Tableau

1. Create separate dashboards that should be rotated (possible in different workbooks)
```
for TV with 1080р use resolution 1700х960 for a separate sheet or you can experiment
```

2. Create a web-page with a list of dashboards & display timing (you can post it anywhere, e.g. on github pages or your web-site)
```
**[see an example of the page](https://github.com/AdamovichAleksey/KufarTV/blob/master/index.html)**
also you can add google slides in a special format
```

3. Create 1 dashboard with 1 “web-page” sheet
```
for TV with 1080р use resolution 1728х980
```
