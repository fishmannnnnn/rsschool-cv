## Name

Vladislav Lemkov

## Contacts

**Telegram**: @uhhhpn
**Discord**: fishmannn#4290
**E-mail**: vlad.lemkov@yandex.ru

## About Myself

I am a punctual and motivated individual who is able to work in a busy environment and produce high standards of work. I am an excellent team worker and am able to take instructions from all levels and build up good working relationships with all colleagues.

## Skills

I have done some projects using javascript and continue learning the language, sass pre-processor and electron framework.

## Code Example

    let input = document.getElementById("binInput");
    input.setAttribute("maxlength", "8");

    let result = document.getElementById("result");
    let btn = document.getElementById("calculate");
    btn.onclick = function () {
        for (let char of input.value) {
            if (char != "0" && char != "1") {
                result.innerText = "you entered a non-binary number".toUpperCase();
                return 0;
            }
        }
        result.innerText = parseInt(input.value, 2);
    };

## Projects

[burgundy adaptive web site](https://fishmannnnnn.github.io/burgundy/)

## Education

Tolyatti State University (Software Engineering): 2022 - until now

## Languages
