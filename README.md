## 广度优先遍历 与 深度优先遍历问卷
给予data sctructure
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


### 写出广度优先遍历
```
const bfs = (root) =>{
    // write your code
}
```

### 写出深度优先遍历
```
const bfs = (root) =>{
    // write your code
}
```

