
#### for..of :

`let arr = ["a","b","c"]`

மேல் உள்ள arrayன் index 0,1,2 மற்றும் values a,b,c ஆகும்.

ES5ல் உள்ள for..in loopஐ மேல் உள்ள arrல் பயன்படுத்தும் போது அதன் index கிடைக்கும்.

`for (let i in arr){
  console.log(i); 
  }`
   
 Outputs : 0,1,2

ES6ல் உள்ள for..of loop பயன் படுத்தும் போது arrன் values கிடைக்கும்.

`for (let i of arr){
  console.log(i);

Outputs : a,b,c

> **குறிப்பு :**
> 
> -  for..in உபயோகிக்கும் போது index கிடைக்கும்.
> -  for..of  உபயோகிக்கும் போது values கிடைக்கும்.
