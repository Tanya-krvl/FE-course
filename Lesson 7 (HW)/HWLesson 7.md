 Homework

- [x] [Return the Missing Element](https://www.codewars.com/kata/even-or-odd): [Solution](https://www.codewars.com/kata/reviews/52995cff9ce954dc50000a86/groups/5ed3f9edb5d4a00001916063)
- [X] [Find Your Villain Name](https://www.codewars.com/kata/return-negative): [Solution](https://www.codewars.com/kata/reviews/536c36d47fc09aeb04000006/groups/536c52e62f4036f33f0001b5)
- [ ] [Add property to every object in array](https://www.codewars.com/kata/jennys-secret-message): [Solution](#link)
- [Х] [Take a Ten Minute Walk](https://www.codewars.com/kata/opposites-attract): [Solution](#link)

При тестировании результатов показывает, что решено правильно,  но при запросе решения - его нет
(function isValidWalk(walk) {
  //insert brilliant code here
  let ns = 0, we = 0; 
    for (let direction of walk) { 
      if (direction  == 'n') ns += 1; 
      if (direction  == 's') ns -= 1; 
      if (direction  == 'w') we += 1; 
      if (direction  == 'e') we -= 1; 
    } 

    return walk.length == 10 && ns === 0 && we === 0; 
}

)