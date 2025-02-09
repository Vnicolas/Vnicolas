# Salut ! 👋

```typescript
class FrontendDeveloper {
  name: string;
  role: string;
  location: string;
  blog: string;
  knowledgeBase: string[];

  // Constructeur pour initialiser les valeurs
  constructor() {
    this.name = "Nicolas Vairaa";
    this.role = "Développeur Frontend";
    this.location = "Nantes, France";
    this.website = "https://webefficiency.carrd.co/";
    this.knowledgeBase = [
      "HTML5",
      "CSS (SCSS)",
      "JavaScript",
      "TypeScript",
      "RGAA (web accessibility)"
      "Git",
      "Markdown",
      "Bash"
    ];
    this.knowledgeBase.unshift("Angular et NextJS"); 
  }

  sayHi(): void {
    console.log(
      `Bonjour mon ami, merci de passer par ici !
      
Je suis ${this.name}, je vis à ${this.location}. Je travaille en tant que ${this.role} et récemment, je me concentre sur ${this.knowledgeBase[0]} pour mon développement personnel.

J'ai des centres d'intérêt variés, mais la plupart d'entre eux incluent ${this.knowledgeBase.slice(1).join(", ")}.

👉 Je propose également un accompagnement qui te permet de transformer ton potentiel, de booster tes workflows et
doubler ta productivité. Tu peux réserver ta place ici : ${this.website}`
    );
  }
}

const me = new FrontendDeveloper();
me.sayHi();

```

## Langages et Outils
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

## Frameworks
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)

[![](https://img.shields.io/badge/linkedin-0a66c2)](https://www.linkedin.com/in/%E2%88%99-nicolas-vairaa-%E2%88%99-19779155/)
