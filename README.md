## 给予data sctructure
```
const tree = [
    {
        val:'a', 
        children:[
            {
                val:'b', 
                children:[
                    val:'c',
                    children:[]
                ], 
            },
            {
                val:'d', 
                children:[], 
            }
        ], 
    }, 
    {
        val:'e',
        children:[
            {
                val:'f', 
                children:[], 
            },
            {
                val:'g', 
                children:[], 
            }
        ]
    }
]
```

```mermaid
    graph TD; 
      Start--->A
      Start--->E
      E---> F
      E--->G
      A--->B
      B--->C
      A--->D
      
      
      
```


## 广度优先遍历 
