# Javascript-code
/**
console.log("hello divu");
console.log("hi this is my first code in java script");
console.log(4+3);
x =45;
console.log(x);

// variable
var x;
x=67; =>let as var
const B=24;
var num="hello";
let e=4;
console.log(x);
console.log("let is the block variable its never defined outside the block and also redeclare");
console.log(x);
console.log(x,typeof x);
console.log(num,typeof num);
console.log(B,"constant no. can't be changed");
var a=45;
console.log(x+a);
console.log("Hosting process");
console.log(D);
var D=10;

//operater
//*arithematic, argument , comparison , logical, bitwise, conditional
// NAN Error

// if , elseif and else operater
var x=5;
if (x==5){
    console.log("hi");
}

-> loop
var a=2;
var i =0;
while(i<11)
{
    console.log(a,"*",i,"=",a*i);
    i++;
}
console.log("bye");
var b=0;
do{
    console.log("hi",b);
    i++;
}while(b<4);

// function in java script

function displayTable(y){
// it's return nothing & take argument
    for(var i=0;i<10;i++)
    {
        console.log(y,"*",i,"=",y*i);
    }
}
console.log("bye");
//calling
displayTable(4);
function sum(x,y){
   // console.log(x+y);
    var z =x*y;
    return z;
}
var res1=sum(3,5);
console.log(res1);// return ke liye peint krana pdta hai
console.log(res1-5);

-->> Arrow function 
const demo=()=>console.log("hello");
demo();// calling
//Return function
const sum=(x,y)=>{
    return x+y;
}
let re2=sum(3,5);
console.log(re2);// call to return function

// object in js.
const Student={
    firstName:"Divyanshi",//property: value
    lastName:"Gupta",
    dob:"11 march",
    pin:1234,
    displayName:function(){
        return this.firstName+" "+this.lastName
    }

}
const fullName= Student.displayName();
console.log(fullName);


//-->> array in js.
const Student =["hi","hello","bunjour","namste"]
var sty=[{},{},{}]// object in array
const newStudent= Student.slice(2);
console.log(newStudent);
Student.sort();
Student.reverse();
//console.log(Student);
//console.log(Student[0],Student[1]);
//console.log(Student.length);
Student.pop();
console.log(Student);
Student.push("subprabhab");
console.log(Student);

// for each loop  
const number=[54,85,1,65,70];
number.forEach(function(value,index,array){
    console.log(value,index,array);
})

//-->map:return the new array after the apply operation on old array
const number=[3,5,4,7];
const newNumber=number.map(function(value){
    return value*2;
}) 
console.log(number);
console.log(newNumber);

*/
