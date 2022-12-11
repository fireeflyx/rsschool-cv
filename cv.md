# Pavel Dubrovskiy

---

## Contacts:

* Phone: +375(33)383-36-60
* Email: paveldubrovskiyit@gmail.com
* Telegram: @pavel_dubrovskiy
* [Linkedin](https://www.linkedin.com/in/pavel-dubrovskiy-39b296255)

## About Myself:

I am a first-year student of Belarusian State University of Informatics and Radioelectronics (BSUIR). I started my journey with learning the basics of C.
Then I became interested in design and the sphere of web-programming. First of all I learned HTML and CSS, I have made some sites with responsive design.
I have already had experience using Figma and Adobe PhotoShop, also I used to create layout design. Afterwards my choice fell on JavaScript. I am realy keen on it. Besides I would like to mention my algorithm comprehension.
Now I try to improve my skills, abilities and do my best to get a job offer.

## Skills and Proficiency:

* HTML5, CSS3
* JavaScript(Basics)
* Git, GitHub
* Figma, PhotoShop
* Algorithms
* CMS(WordPress)

## Code example:

**Strip Comments KATA from CODEWARS (4kyu):** Complete the solution so that it strips all text that follows any of a set of comment markers passed in. Any whitespace at the end of the line should also be stripped out.

**Example:**

*Given an input string of:*&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;*The output expected would be:*
```
apples, pears # and bananas       apples, pears
grapes                            grapes
bananas !apples                   bananas
```
The code would be called like so:
```
var result = solution("apples, pears # and bananas\ngrapes\nbananas !apples", ["#", "!"])
// result should == "apples, pears\ngrapes\nbananas"
```
**My solution:**
```
function solution(input, markers) {
  let arr = input.split("\n");
  return arr.map(item => {
    if(item.includes(markers[0]) || item.includes(markers[1])){
      let delete_index = item.includes(markers[0]) ? item.indexOf(markers[0]) : item.indexOf(markers[1]);
      return item.slice(0, --delete_index);
    }    
    return item;
  }).join("\n");
};
```
## Education:
* HTML and CSS Tutorials on the [webref](https://webref.ru)
* JavaScript Manual on [learnjavascript.ru](learnjavascript.ru) (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
* [BSUIR](https://www.bsuir.by/en/) FIS (2022-2026)

## Langueges
* Russian - Native
* English - Intermediate (**B1**) (stydy in [streamline](https://str.by))