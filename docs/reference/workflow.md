# Workflow

This a flowchart that illustrates a process.

``` mermaid
graph LR
A(["Log in"]) --> B["Home
page"];
B --> C[Search];
C --> D{Found?};
D -->|Yes| E{"Add,
Update, or
Delete?"};
D -->|No| C;
E --> |Add| F["Add
page"];
E -->|Update| G["Update
page"];
E -->|Delete| H["Delete
page"];
F --> I["Submit"];
G --> I;
H --> I;
I --> J(["Log out"]);
```



## Description

This is a description of the flowchart.
