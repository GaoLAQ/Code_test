# 前中后序遍历

给予data structure 
```
const tree = 
    {
        val:'a', 
        left:{
            val:'b', 
            left:{
                val:'c'
                left:{
                    val:'f',
                    left:{}, 
                    right:{}
                }, 
                right：{
                    val:'g',
                    left:{},
                    right:{}
                }
            }
            right:{
                val:'e',
                left:{}, 
                right:{}
            }
        }, 
        right:{
            val:'d',
            left:{
                val:'h',
                left:{}, 
                right:{}
            }, 
            right:{
                val:'i',
                left:{}, 
                right:{}
            }
        }, 
    }, 
```
``` mermaid
      graph TD; 
      a---> b
      b---> c
      b---> e
      c---> f
      c---> g
      a---> d
      d---> h
      d---> i
```

要求：递归版
## Pre-order 
```
const preorder = (root)=>{
  
}
```
## In-order 
```
const inorder = (root)=>{

}
```
## Post-order 
```
const postorder = (root)=>{
    
}
```
要求：非递归版
## Pre-order 
```
const preorder = (root)=>{
  
}
```
## In-order 
```
const inorder = (root)=>{

}
```
## Post-order 
```
const postorder = (root)=>{
    
}
```
