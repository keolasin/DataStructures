INPUT first number  
INPUT second number  
IF the *first* number is GREATER THAN the *second* number THEN  
  PRINT *first* number  
ELSE  
  PRINT *second* number  
END IF  

SET counter to 0  
FOR each integer between 0 to 100  
  PRINT counter  
  INCREMENT counter  
END FOR  

SET phonebook  
INPUT entry  
FOR each item in phonebook  
  IF entry is equal to item  
    RETURN item  
  ELSE  
    RETURN nothing  
  END IF  
END FOR  

```
const phonebook = ['Tommy', 'Teresa', 'Timmy'];
let entry = 'Timmy';

for(let i = 0; i < phonebook.length; i++){
  entry === phonebook[i] ? console.log(`${entry} is at index ${i}`) : null
}
```
