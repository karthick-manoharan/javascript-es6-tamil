

#### ஃபங்சன்ஸ் :

ES6ல்  `function` கிவேட் வுபயோகிப்பதற்கு பதில் `=>` அம்புக்குறி உபயோகிக்க வேண்டும்.

ES6 Syntax:

`var  functionName = (arguments) => {expressions}`

ES5 Syntax:

`var  functionName = function(arguments) {expressions}`

இப்பொழுது `function` கிவேடை `arguments`ன் வழது புறம் ஆக்கவும்.
`var  functionName = (arguments)function {expressions}`
ES6ன் படி `function` கிவேட் வுபயோகிப்பதற்கு பதில் `=>` அம்புக்குறி உபயோகிக்க வேண்டும்.

`var  functionName = (arguments) => {expressions}`

அவ்வளவு தான் ES6 functions.

**எடுத்துகாட்டு:**

ES5:

`function square (x) {
	  console.log('ES5 function result: '+ x*x);
}`

ES6:

`var square = (x) => {console.log('ES6 function result :' + x*x)};`



> **குறிப்பு :**
> 
> - `=>` அம்புக்குறி `function` கிவேடின் அடயாலம் (symbol) என்று நினைத்து கொள்ளவும். 
> - `function` கிவேடை வழது புறம் இடம் பெயற்கவும்.

 


