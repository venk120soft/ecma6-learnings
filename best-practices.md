#### Checking for the length of an array
      const length = myArray? myArray.length:0;
      const length = (myArray||[]).length
#### Truncating the array
      let myArray=[0,1,2,3,4,5,6,10,23,232];
      myArray.length = 4; // all other elements will be removed 
      
      // This can also be done using the slice operation which is faster than above approace
      myArray = myArray.slice(0,4);
      console.log(myArray); // [0,1,2,3]
#### Get the last item from an array
    myArray[myArray.length-1] // 3
    myArray.slice(-1) // [3]
    
#### Ternary operator replace with &&
    if(myArray){
      const length= myArray.length;
    }else{
      const length=0;
    }
    const length = myArray? myArray.length:0;
    const length = myArray &&  myArray.length;
    
