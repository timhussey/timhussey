<h1 align="center">Hey there 👋, I'm timhussey!</h1>
<p align="center">
    <i>Self proclaimed</i> <b>Director of Fun 🎉</b> <i>and</i> <b>PHP Nerd 🤓</b>
    <br />
    <br />
    <a href="https://hits.seeyoufarm.com/">
        <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Ftimhussey&title_bg=%232D2D2D&count_bg=%2300CC69&icon=github.svg&icon_color=%23E7E7E7&title=Views%20%28Day%20%2F%20All%29&edge_flat=false" />
    </a>
    <a href="https://github.com/STRRL/serverless-github-badges">
        <img src="https://badges.strrl.dev/years/timhussey?style=flat&labelColor=333333&logoColor=E7E7E7&color=0089FF&label=Years&logo=github" />
    </a>
    <a href="https://github.com/Willy-JL?tab=followers">
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


```js
class AboutMe {
  constructor() {
    this.username = "@timhussey";
    this.fullname = "Tim Hussey";
    this.location = "Arizona";
    this.occupation = "Software Engineer";
    this.company = "Showit";
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
[![Top Languages](https://readme-stats.clckblog.space/api/top-langs/?username=timhussey&count_private=true&show_icons=true&title_color=39ff14&icon_color=79ff97&text_color=fff&bg_color=151515)](https://github.com/timhussey)


