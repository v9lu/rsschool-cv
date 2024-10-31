# rsschool-cv
## Contact Information:

|   Name   | Uladzislau Hupalo |
| :------: | :---------------: |
| Location |  Warsaw, Poland   |
|          |                   |

## About me
*Versatile developer with a focus on Python, currently working on a bot for trading meme coins. Alongside coding, I am actively expanding my skills in JavaScript through RS Courses. My background includes reverse engineering and exploit research, where I analyzed malware and submitted detailed reports to cybersecurity firms. A creative thinker with a technical edge, I also produce music in FL Studio, combining artistic and analytical talents across multiple fields.*
## Skills

| Skill               | Level        |
| ------------------- | ------------ |
| Python              | Intermediate |
| Reverse Engineering | Elementary   |
| HTML5               | Beginner     |
| CSS                 | Beginner     |
| JavaScript          | Beginner     |
## Code example:
**Codewars Task:** *Jack really likes his number five: the trick here is that you have to multiply each number by 5 raised to the number of digits of each numbers, so, for example:*
```examples
  3 -->    15  (  3 * 5¹)
 10 -->   250  ( 10 * 5²)
200 --> 25000  (200 * 5³)
  0 -->     0  (  0 * 5¹)
 -3 -->   -15  ( -3 * 5¹)
```

```javascript
function multiply(number){
  return number * 5 ** Math.abs(number).toString().length
}
```