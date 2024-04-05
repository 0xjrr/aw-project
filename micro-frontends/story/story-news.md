```mermaid
stateDiagram-v2

    classDef coloring fill:teal

    state "micro-frontend" as LegendView
    state "Action" as ActionView





    [*] --> NewsPage: Navigate Menu
    NewsPage --> StatisticsPage: Statistics button
    NewsPage --> news: Contains
    StatisticsPage --> [*]: Check the latest statistics 
    StatisticsPage --> news: Contains

    Class Geolocalization, Account, news, LegendView, FilterView coloring
```