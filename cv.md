# **Andrey Sapak**

## Junior Frontend Developer

## **Contact information:**

#### Phone number: +380 50 012 12 81
#### Email: andreysapak312@gmail.com
#### Github: [andrewsapak](https://github.com/andrewsapak)
#### Discord: Andrey Sapak #7645

## **About myself**

#### Previously, I tried to take a course at [Mate Academy](https://mate.academy/). I did not go through it to the end, it was prevented by quarantine and a  change of priorities.
#### At the moment I work as a system administrator and in my free time I go through this course. The desire to develop your skills and learn new things is #### great. Therefore, I will do my best to further master the profession of Front End Developer thanks to your course.

## **My Skills:**

* ### HTML5
* ### CSS3
* ### GITHUB, GIT
* ### Java Script (Beginner)

## **Languages:** 

1. ### Ukrainian: Native
2. ### English: Intermediate

## **Code example:**

### Task: 

### Complete the solution so that it returns true if the first argument(string) passed in ends with the 2nd argument (also a string).

### Solution:

```
function solution(str, ending){
    let endIndex = ending.length;
    let endOfStr = str.slice(str.length - endIndex, str.length);
    if (ending === endOfStr) {
        return true;
    }
    return false;
  }
```