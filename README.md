# Streaming sensor data into PostgreSQL


## Vaisala Stream API
```mermaid
  flowchart TD
    subgraph Vaisala
        A1[Vaisala]
    end

    subgraph Process B
       B1[Node Red] --> B2[PostgreSQL]
        
    end



    A1 -->  |Cache the data until a row is full|B1

```






## AppScript Stream

```mermaid

```
```








