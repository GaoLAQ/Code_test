# 前中后序遍历问卷

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
                    left: null, 
                    right: null
                }, 
                right：{
                    val:'g',
                    left: null,
                    right: null
                }
            }
            right:{
                val:'e',
                left: null, 
                right: null
            }
        }, 
        right:{
            val:'d',
            left:{
                val:'h',
                left: null, 
                right: null 
            }, 
            right:{
                val:'i',
                left: null, 
                right:null 
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
## 写出 Pre-order 
```
const preorder = (root)=>{
  
}
```
## 写出 In-order 
```
const inorder = (root)=>{

}
```
## 写出 Post-order 
```
const postorder = (root)=>{
    
}
```
要求：非递归版
## 写出 Pre-order 
```
const preorder = (root)=>{
  
}
```
## 写出 In-order 
```
const inorder = (root)=>{

}
```
## 写出 Post-order 
```
const postorder = (root)=>{
    
}
```
