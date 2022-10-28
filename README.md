Theory
summery:
coomon module extention:index.js 


common module:EXPORTS ARE OF TWO TYPES:---1.Default 

2.Named

1.Default syntax:- module.exports=add

2.Named Syntax:-module.exports.add=add

common module import access as follows:-const cal=require('./calculator)

-->Here require function is used to import function module @ trace the given path

-->Here ./calculator is path where we can access our requirements

2.ES6 module:---> extension is index.mjs 
Here also we have two types of exports EXPORTS ARE OF TWO TYPES:---1.Default 2.Named
Default Syntax:-export default add
Named Syntax:-export const add=(a,b)=>{ 
return a+b;
};
ES6 import---->import {add} from './calculator.mjs---> Observe here in the path we are mentioning mjs extension also;
