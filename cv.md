# Shevchenko Yevhenii
***
## Contacts:
* **Phone** - +380 98 3315174
* **Telegram** - @Negven
* **E-mail** - supershevchenko548@gmail.com
* **GitHub** - [Negven](https://github.com/Negven)

---
## About Me:
My experience of frontend development has started a few years ago. I had practice at company when I was 16. I've started learning JS HTML and CSS. I have already taken part in some projects. I can easy learn new material if it needs for project.

***
## Skills:
* HTML5 CSS3
* JS Basis
* Git
* WebStorm, IntelliJ IDEA, VS.

---
## Code Example:
```
function descendingOrder(n){
  let numbers = [];
  let  maxId;
  while( n >= 10){
    numbers.push(n % 10);
    n = Math.floor(n/10);
  }
  numbers.push(n);
  for( let i in numbers){
    maxId = i; 
    for( let j = i; j < numbers.length; j++){
      if(numbers[j] > numbers[maxId]){
        maxId = j;
      }
    }
    let c;
    c = numbers[maxId];
    numbers[maxId] = numbers[i];
    numbers[i] = c;
  }
  
  let result = 0;
  for( let i in numbers){
    result *= 10;
    result += numbers[i];
  }
  
  return result;
}
```

***
# Experience:
Practice at company has given me a knowledge of basic JS and HTML DOM.
