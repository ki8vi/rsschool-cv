# Vitaliy Kim
 
+ Contacts:
    + LinkedIn: [https://www.linkedin.com/in/ki8vi/](https://www.linkedin.com/in/ki8vi)
    + Telegram: [@keepinminded](@keepinminded)
    + E-mail: oneofbln@gmail.com
    + Discord: KimV(@ki8vi)
   
---

+ About me:
    
In my life, I have worked in various fields, each of which has provided me with valuable life experience and broadened my horizons. As far as I can remember, I have always enjoyed learning something new because learning is never too late. I have always been fascinated by different technologies, and even from my early childhood, my bookshelf was filled with science fiction books. Recently, I have immersed myself in learning programming, and it's incredibly fascinating. My goal is to push the boundaries of my skills, refine my practice in building complex systems, and bring my imagination to life through real projects. I strive to expand my knowledge and expertise, and I am passionate about turning my ideas into tangible solutions.

---

+ Skills:
    + JavaScript
    + HTML
    + CSS
    + Sass
    + [Codewars](https://www.codewars.com/users/ki8vi)
    + [Github](https://github.com/ki8vi)
  
---

+ Example of my code:

    ```
    Find Highest Rank Number in an Array
    function highestRank(arr) {
    let out = []
    let hsh = {}
    for(let i = 0; i < arr.length; i++) {
        if(!hsh[arr[i]]) {
        hsh[arr[i]] = 1
        } else {
        hsh[arr[i]]++
        }
    }
    arr = Object.entries(hsh)
    const maxVal = Object.values(hsh).sort((a, b) => b-a)[0]
    for(let i = 0; i < arr.length; i++) {
        if(arr[i][1] === maxVal) {
        out.push(+arr[i][0])
        }
    }
      return Math.max(...out)
    }
    console.log(highestRank([12, 10, 8, 12, 7, 6, 4, 10, 12])) // -> 12
    ```
---

+ Education:
    + Turan Universtity - Jurisprudence
    + [FreeCodeCamp - JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/certification/KimV/javascript-algorithms-and-data-structures)
  
---

+ Languages:
    + Russian: native language
    + Korean: I lived in South Korea for some time, studying the culture and language, so I have conversational skills in Korean.
    + English: I lived in the UAE and worked at Ferrari World Abu-Dhabi park as an Attraction Consultant, where my responsibilities included providing information to park guests. Due to this role, I was able to enhance my English skills to an intermediate level.