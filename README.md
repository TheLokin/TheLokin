# Meet `TheLokin` 👨‍💻

Welcome to my GitHub! Here's a fun TypeScript snippet that introduces me as a developer in a lighthearted way. 😄


```typescript
class TheLokin {
  private name: string;
  private username: string;
  private location: string;

  constructor() {
    this.name = 'Diego Ramil López';
    this.username = 'TheLokin';
    this.location = 'Spain';
  }

  introduceYourself(): string {
    return `
      Hi, I'm ${this.name}, but you can call me '${this.username}' (because 'Master of Divs' was taken).
      I'm a Frontend Developer from ${this.location} who lives on a steady diet of coffee and CSS bugs.
    `;
  }

  debug(): void {
    console.log(`Debugging ${this.username}...`);
    setTimeout(() => console.log('Still debugging...'), 1000);
    setTimeout(() => console.log('Alright, fixed... for now.'), 3000);
  }
}

// Main function to meet me
(function main() {
  const me = new TheLokin();
  console.log(me.introduceYourself());
  me.debug();
})();
```

# Statistics
<p align="left">
  <a href="https://github.com/TheLokin">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=TheLokin&count_private=true&show_icons=true&theme=gruvbox&hide_border=true" alt="Diego's Github Stats"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TheLokin&theme=gruvbox&hide_border=true&layout=compact&langs_count=6" alt="Diego's Github Languages" />
  </a>
</p>
