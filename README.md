# Hi, I'm Jeremy 👨‍💻 👋  

## Full‑Stack / Frontend Developer & Co‑Founder en Solvegrades  

💻 Full‑Stack / Frontend Developer con sólidos fundamentos en backend, bases de datos, redes y sistemas operativos  
🚀 Co‑Founder en **Solvegrades**, startup EdTech donde construyo soluciones web escalables orientadas a educación  
🎨 Especializado en crear interfaces modernas y responsivas con **Angular** y **TypeScript**  
🌐 Experiencia en integración de APIs REST/GraphQL y arquitectura de aplicaciones web  
🔧 Fundamentos en backend con **Node.js** y **Express**  
🗄️ Conocimientos en **SQL Server, MySQL y MongoDB**, diseño de esquemas y optimización de consultas  
🖥️ Base técnica en redes y administración de sistemas operativos  
📊 Apasionado por crear dashboards interactivos y experiencias de usuario intuitivas  
🤝 Abierto a colaboraciones y oportunidades como practicante o developer en proyectos de impacto educativo o social

---

### 🛠️ Tech Stack

```typescript
class Jeremy {
  private stack = {
    frontend: ["Angular", "TypeScript", "PrimeNG", "SCSS", "HTML5", "CSS3"],
    backend: ["Node.js", "Express", "GraphQL", "REST APIs"],
    databases: ["SQL Server", "MySQL", "MongoDB"],
    tools: ["Git", "VSCode", "Postman", "Cloudinary", "JWT Auth"],
    infrastructure: ["Rocky Linux", "Windows Server", "Networking"]
  };

  buildProject(type: "web" | "api" | "fullstack"): string[] | string {
    switch (type) {
      case "web":
        return [...this.stack.frontend, ...this.stack.backend];
      case "api":
        return ["Express", "Node.js", "SQL Server", "JWT Auth", "GraphQL"];
      case "fullstack":
        return [...this.stack.frontend, ...this.stack.backend, ...this.stack.databases];
      default:
        return "Proyecto personalizado";
    }
  }

  getCurrentFocus(): string {
    return "Building modern web applications with Angular & TypeScript";
  }
}
