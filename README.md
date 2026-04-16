<div align="center">
  <img src="YOUR_IMAGE_URL_HERE" width="150" style="border-radius: 50%;" />
</div>

```javascript
/**
 * @summary
 * Full Stack Developer specializing in the MERN stack.
 * Experienced in building scalable web platforms and GS1 standards.
 * Open to innovative projects and AI/ML collaborations.
 */

class INFORMATION {
  constructor() {
    this.NAME = "Muhammad Sadeeq";
    this.TITLE = "Full Stack Web Developer";
    this.EMAIL = "sadeeq499@example.com"; // Replace with your actual email
    this.LOCATION = ["Saudi Arabia", "Remote"];
    this.EMPLOYER = "GS1 Saudi Arabia";
    this.STATUS = "University Student & Professional Developer";
  }
}

enum TECH_STACK {
  FRONTEND = ["React.js", "Next.js", "Vite", "Tailwind CSS", "Shadcn/ui"],
  BACKEND = ["Node.js", "Express.js", "REST APIs"],
  DATABASE = ["MongoDB", "PostgreSQL"],
  STATE_MGMT = ["Redux", "Context API"]
}

enum TOOLS {
  IDE = ["VS Code", "Cursor AI", "WebStorm"],
  DEPLOYMENT = ["VPS", "Nginx", "SSL/Certbot", "Docker"],
  DESIGN = ["Figma", "AI Image Generation (Nano Banana)"]
}

enum MEDIA {
  GITHUB = "[https://github.com/Sadeeq499](https://github.com/Sadeeq499)",
  PORTFOLIO = "[https://sadeeq-portfolio.com](https://sadeeq-portfolio.com)", // Replace with your link
  LINKEDIN = "[https://linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)"
}

class PROJECTS extends EXPERIENCE {
  static async GS1_Official_Platforms() {
    return {
      task: "Member Registration Portal",
      features: ["Multi-step forms", "Barcode Logic", "National Address API"],
      standards: ["GTIN", "GLN", "SSCC"]
    };
  }

  static async Real_Estate_System() {
    const project = "Sue-Realty";
    const focus = ["Franchise Logic", "Seller Portals", "MongoDB Schemas"];
    return { project, focus };
  }
}

class CURRENT_LEARNING {
  constructor() {
    this.FOCUS = "Artificial Intelligence & Machine Learning";
    this.GOALS = ["Data Cleaning", "Model Training", "Neural Networks"];
    this.TIMELINE = "30-Day Intensive Mastery";
  }
}
