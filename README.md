# string-to-array-react.js
class StrinfToArray extends{

state{
array:[],
}

let stringValue="10,20,30,40,50,60";
let arrayValue=stringValue.split(',');
this.setSate({
array:arrayValue,
});

render(){
return(
<>
{
console.log(this.state.array);
}

</>

}
