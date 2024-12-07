// count-frequency-in-javascript

 count frequency
// convert array to object and repet no, how many times, amazon interview question

let arr=[1,2,1,2,5,1,5,7,8];
let o={}
for(let i=0;i<arr.length;i++){
  if(o[arr[i]] ){
    o[arr[i]] ++;
    }else{
        o[arr[i]]=1;
    }
}
console.log(o);
