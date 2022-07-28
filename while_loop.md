## Please write while loop instead of for loop

```javascript
let sum = 0 
for(let i = 0; i<n; i++){
  sum += i 
  return sum 
}
```
## Please write down your understanding of while in while loop 

```javascript
function whileloop(){
  let i = 0 
  let k = 0 
  while(i<3){
    i++
    console.log('main loop' + i)
    while(k<2){
      k++ 
      console.log("side loop" + k) 
    }
  }
}
```
