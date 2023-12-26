what is block in JS?
combine multiple JS statement into a group

shadowing
var x =10
{
var x=5
cosole.log(x)//this variable shadow above variable
}
cosole.log(x)
both x refer to 10 bcz of shadowing

let x = 10 // script
// block
{
var a = 20 // global
let x =5
cosole.log(x)
}
cosole.log(x)
5
10

- you cannot shadow a let using var but with let you can
