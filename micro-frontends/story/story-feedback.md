```mermaid
stateDiagram-v2
    [*] --> Filter
    FilteredPage --> Geolocalization: Contains
    FilteredPage --> Filter: Contains
    FilteredPage --> Menu: Contains
    Filter --> FilteredPage: Observe
    FilteredPage --> ProductsPage: Select Category
    ProductsPage --> Products: Contains
    FeedbackPage --> Feedback: Contains
    ProductsPage --> FeedbackPage: Select product and give feedback
    FeedbackPage --> [*]
```
