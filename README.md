Challenge to understand my truth


let a = 10;
let b = "20";
let c = 80;






console.log(++a + +b++ + +c++ - +a++);
//Explain: ++a = 11 + +b = 20 + c = 80 - a = 11 = "100"; but if we print again new we will see "103" becuse post of b and c and a



console.log(++a + -b + +c++ - -a++ + +a);
//Explain: ++a = 11; b = -20; c = 80; (- - = +) so c = 80 + a = 11 = 91; + 1(post of a) + a = 11 ; TOTAL: "94"


console.log(--c + +b + --a * +b++ - +b * a + --a - +true)


//Explain: c = 79; b = 20; a = 9 * b = 20 | 180; b = 21 * a = 9 = 189 | and add (-) = -189 |a = 8 - true = 1 = 7 | Total : "97"
