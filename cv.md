# Meleshko Nikita

## Junior Frontend Developer


## Contact information:

**Phone:** +375(29)342-91-83

**E-mail:** melexa001@gmail.com

**Telegram** @Nifikus

**Discord** Nikita Meleshko(@Nifikus)

[LinkedIn](https://www.linkedin.com/in/nikita-meleshko-9b7498262/)



## Briefly About Myself:

I strive to become a full-fledged Frontend developer. Easy to learn and hardworking. I really like to learn new things for me, this is the meaning of my life.



## Skills:

* HTML5, CSS3

* JavaScript Basics

* Git, GitHub

* VS Code

* Adobe Photoshop



## Code example:

**Create Phone Number Cata from CODEWARS:** Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.

```
function isPangram(string){
  let lowerStr = string.toLowerCase();
  let arrOfLetters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z'];
  let quantity = [];
  let pos = -1;
  for (let elem of arrOfLetters){
    while ((pos = lowerStr.indexOf(elem, pos + 1)) != -1) {
      quantity.push(elem);
      }
  }
  let alphabet = 0;//26
  for(let letter of arrOfLetters){
    if(quantity.includes(letter)){
      alphabet += 1;
    }
    
  }
  if(alphabet == 26){
    return true
  }else{
    return false
  }
  
  
}
```



## Courses:

* Stepik corse "HTML and CSS"

* JavaScript Manual on [learnjavascript](https://learn.javascript.ru/) (in progress)

* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)



## Languages:

* English - B1

* Russian - Native

* Belarusian - Native
