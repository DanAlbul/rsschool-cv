# Daniel Albul

![DanielAlbul_Profile_Photo](https://media-exp1.licdn.com/dms/image/C5603AQEzGSQFHyhiAQ/profile-displayphoto-shrink_400_400/0/1638886090555?e=1666828800&v=beta&t=5_3sSynYs_aDkyJCliSSFpD4t_37VCVWPIsRrChTJNk)

## Contact Info:
* **Phone: +380 63 8302847 (viber, telegram)**
* **E-mail: daniel.albul.bz@gmail.com**
* **GitHub: [DanAlbul](https://github.com/DanAlbul)**
* **Linkedin: [Daniel Albul](https://www.linkedin.com/in/daniel-albul-83461921a)**
* **CodeWars: ![DanAlbul-codewars-badge](https://www.codewars.com/users/DanAlbul/badges/small)**

## About Me:
***General QA Engineer at Doc-HQ*** (British Health-care startup) with 3 years of experience in Manual QA and 1 year in Automation Testing.
Active, Curious, Flexible, Loyal, Passionate to technologies, Self-critical and Communicative person. Team player with focus on the project and user experience.
Appart from testing software, I also prefer to create own at free time. 
Working hard to switch speciality from QA to Front End Engineer.

## Skills:
* JavaScript (Core JS, DOM, Events, Functional Programming, Asynchronous JavaScript, OOP, ES6 syntax, Basic NodeJS)
* CSS (SASS, Flexbox, Grid, Responsive Design, Bootstrap)
* HTML
* Cypress (Javascript Web Automation framework)
* Python (Fundamentals)
* GIT (Basics)
* Postman (API testing, Basics)
* Linux (Debian 10, WSL2, basic commands)
* Other tools: Confluence, Jira, Chrome Dev Tools, Clickup, Testrail

## Code example:
```js
const container = [ 
  {type: 'rotten apples', material: 'organic'},
  {type: 'out of date yogurt', material: 'organic', secondMaterial: 'plastic'},
  {type: 'wine bottle', material: 'glass', secondMaterial: 'paper'},
  {type: 'amazon box', material: 'paper'},
  {type: 'beer bottle', material: 'glass', secondMaterial: 'paper'} ]

const recycle = trash_box => {
  const recycle_box = {
    paper: [], glass: [], organic: [], plastic: []
  };
  
  for (let item of trash_box) {
    recycle_box[item.material].push(item.type);
    if (item.hasOwnProperty('secondMaterial')) {
      recycle_box[item.secondMaterial].push(item.type);
    }
  }
 return Object.values(recycle_box);
}

console.log(recycle(container))

/* Output:
 ['wine bottle', 'amazon box', 'beer bottle'],
 ['wine bottle', 'beer bottle'],
 ['rotten apples', 'out of date yogurt'],
 ['out of date yogurt']
*/
```
## Experience:
Company . Position . Period|Responsibilities
-------------------------|---------------------------------------------------
**DocHQ (UK)** . Automation QA (JS) . Since August 2021 | Writing end-to-end web automation tests using Cypress framework for Health-Tech platform
**Ubisoft (Ukraine)** . Manual QA . September 2019 - August 2021 | Performing testing of AAA gaming project (“Riders Republic”) almost at all stages in multicultural team.
**GlobalLogic (Ukraine)** . Trainee . April 2019 - July 2019 | Obtaining testing practice by working under web project ("anotepad.com").
