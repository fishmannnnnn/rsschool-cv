## Name

Vladislav Lemkov

## Contacts

**Telegram**: @uhhhpn

**Discord**: fishmannn#4290

**E-mail**: vlad.lemkov@yandex.ru

## About Myself

I really love english language and solving coding problems.
I am a punctual and motivated individual who is able to work in a busy environment and produce high standards of work. I am able to take instructions from all levels and build up good working relationships with all colleagues.

## Skills

I have done some projects using javascript and continue learning the language, sass pre-processor and electron framework.

## Code Example

Write a function that takes a string of parentheses, and determines if the order of the parentheses is valid. The function should return `true` if the string is valid, and `false` if it's invalid.

```
function validParentheses(parens) {
  let st = [];
  for (let i = 0; i < parens.length; i++) {
    if(parens[i] == "("){
      st.push(parens[i]);
    }else{
      if (st.at(-1) == "("){
        st.pop()
      }else{
        st.push(parens[i])
      }
    }
  }
  return st.length == 0;
}
```

## Projects

In progress:
[burgundy adaptive web site](https://fishmannnnnn.github.io/burgundy/)

## Education

Tolyatti State University (Software Engineering): 2022 - until now

## Languages

English - B2

Russian - Native
