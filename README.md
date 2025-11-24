<h1 align="center">Hey there 👋, I'm timhussey!</h1>
<p align="center">
    <i>Senior Front-End Developer | React & TypeScript Expert | SaaS Founder | Creative Problem Solver | Director of Fun 🎉</b>
    <br />
    <br />
    <a href="https://hits.seeyoufarm.com/">
        <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftimhussey&title_bg=%232D2D2D&count_bg=%2300CC69&icon=github.svg&icon_color=%23E7E7E7&title=Views%20%28Day%20%2F%20All%29&edge_flat=false" />
    </a>
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/years/timhussey?style=flat&labelColor=333333&logoColor=E7E7E7&color=0089FF&label=Years&logo=github" />
    </a>
    <a href="https://github.com/timhussey?tab=followers">
        <img src="https://img.shields.io/github/followers/timhussey?labelColor=333333&logoColor=E7E7E7&color=8939FF&label=Followers&logo=github" />
    </a>
    <a href="#">
        <img src="https://img.shields.io/github/stars/timhussey?affiliations=OWNER%2CCOLLABORATOR&labelColor=333333&logoColor=E7E7E7&color=EEAA00&label=Stars&logo=github" />
    </a>
    <a href="#">
        <img src="https://badges.strrl.dev/contributions/all/timhussey" />
    </a>
    <br />
    <a href="#">
        <img src="https://img.shields.io/badge/Open_Source-❤-FF0069?style=flat&labelColor=333333&logoColor=E7E7E7">
    </a>
    <a href="#">
        <img src="https://img.shields.io/badge/PRs-Welcome-00CC00?style=flat&labelColor=333333&logoColor=E7E7E7">
    </a>
</p>

<br />

<br />

![HTML5](https://img.shields.io/badge/-HTML5-%23E44D27?style=flat&logo=html5&logoColor=ffffff)
![CSS3](https://img.shields.io/badge/-CSS3-%231572B6?style=flat&logo=css3)
![Javascript](https://img.shields.io/badge/-Javascript-%23282C34?style=flat&logo=javascript)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Nodejs](https://img.shields.io/badge/-Nodejs-black?style=flat&logo=Node.js)
![React.js](https://img.shields.io/badge/-React.js-%23282C34?style=flat&logo=react)
![Wordpress](https://img.shields.io/badge/-Wordpress-%231c769c?style=flat&logo=wordpress)
![PHP](https://img.shields.io/badge/-PHP-%23282C34?style=flat&logo=php)
![MySQL](https://img.shields.io/badge/-MySQL-%23017a9e?style=flat&logo=mysql&logoColor=%23ffffff)


![ESlint](https://img.shields.io/badge/-ESLint-%234B32C3?style=flat&logo=eslint)
![Prettier](https://img.shields.io/badge/-Prettier-%23F7B93E?style=flat&logo=prettier&logoColor=ffffff)
![VS Code](https://img.shields.io/badge/-VSCode-%23007ACC?style=flat&logo=visual-studio-code)
![PHP Storm](https://img.shields.io/badge/-PHP%20Storm-%23fb2d91?style=flat&logo=phpstorm)


![Git](https://img.shields.io/badge/-Git-%23F05032?style=flat&logo=git&logoColor=%23ffffff)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github)
![Docker](https://img.shields.io/badge/-Docker-black?style=flat&logo=docker)
![Amazon AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat&logo=amazon-aws)

```js
class AboutMe {
  constructor() {
    this.username = "@timhussey";
    this.fullname = "Tim Hussey";
    this.location = "San Jose, CA";
    this.occupation = "Senior Front-end Software Engineer";
    this.company = "Available now";
    this.birthday = new Date(1984, 6, 29); // months are 0-indexed Born in July
    this.hobbies = [
      "singing",
      "coding",
      "roller blading",
      "axe throwing",
      "gaming",
      "acting",
      "photography",
    ];
  }

  get age() {
    const currentYear = new Date().getFullYear();
    return currentYear - this.birthday.getFullYear();
  }

  introduce() {
    const { username, fullname, location, occupation, company } = this;
    return `Hello! I'm ${fullname} (known as ${username}). I'm a ${occupation} at ${company} and I live in ${location}.`;
  }

  isBirthdayToday() {
    const today = new Date();
    return today.getMonth() === this.birthday.getMonth() &&
      today.getDate() === this.birthday.getDate()
      ? "Hey, it's my birthday today! 🎉"
      : "Just a regular day for me.";
  }
}

const me = new AboutMe();
console.log(me.introduce());
console.log(`I'm currently ${me.age} years old.`);
console.log(me.isBirthdayToday());
```

[![timhussey's GitHub stats](https://github-readme-stats.vercel.app/api?username=timhussey)](https://github.com/timhussey)


