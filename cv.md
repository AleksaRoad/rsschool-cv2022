# BEZRODNAIA ALEKSANDRA

![Photo](https://avatars.mds.yandex.net/i?id=ea56245a4d9cb3624d5479fd5477066f88c7decc-7111467-images-thumbs&n=13 "Photo")

## **_CONTACTS_**

**Discord:** Muina#7889

## **_ABOUT ME_**

## **_EDUCATION_**

- 1
- 2
- 3

HTML, CSS, SCSS, Webpack, <span style="color:yellow">JS</span>, React, Git, BEM-methodology, ESLint, Prettier

## **_SAMPLE CODE_**

```js
function check(str, bracketsConfig) {
  const opens = Object.fromEntries(bracketsConfig);
  const stack = [];
  let leftBr = bracketsConfig.map((x) => x[0]);

  for (let i = 0; str.length > i; i++) {
    const char = str[i];
    if (leftBr.includes(char)) {
      if (char == opens[stack[stack.length - 1]]) stack.pop();
      else stack.push(char);
    } else if (char == opens[stack[stack.length - 1]]) stack.pop(char);
    else return false;
  }
  return !stack.length;
}
```

## **_EXPERIENCE_**

## **_REFERENCES_**

[Momentum](https://aleksaroad.github.io/momentum/ "Momentum")

## **_LANGUAGES_**

**English:** B1
