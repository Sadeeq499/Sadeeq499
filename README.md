```
 ____  _______     __  __        ____  _     ____  
|  _ \| ____\ \   / / \ \      / / _ \| |   |  _ \ 
| | | |  _|  \ \ / /   \ \ /\ / / | | | |   | | | |
| |_| | |___  \ V /     \ V  V /| |_| | |___| |_| |
|____/|_____|  \_/       \_/\_/  \___/|_____|____/ 
```

---

```csharp
/// <summary>
/// Full Stack Developer & UI/UX Designer
/// 5+ years building scalable web apps, REST APIs & mobile solutions.
/// Available for freelance & full-time roles worldwide.
/// </summary>

public class INFORMATION
{
    public string NAME       = "Muhammad Sadeeq";
    public string TITLE      = "Full Stack Developer & UI/UX Designer";
    public string EMAIL      = "muhammadsadeeq11223@gmail.com";
    public string PHONE      = "+92 306 5799407";
    public string WEBSITE    = "https://www.sadeeqdev.tech";
    public string LOCATION   = "Pakistan";
    public int    EXPERIENCE = 5; // years
}
```

---

```csharp
public enum LANGUAGES
{
    JavaScript,
    TypeScript,
}

public enum FRAMEWORKS
{
    // Backend
    Node_js,
    Express_js,

    // Frontend
    React,
    Next_js,
    React_Native,

    // State Management
    Redux_Toolkit,
    Zustand,
    React_Query,
    Context_API,

    // UI & Styling
    Tailwind_CSS,
    Material_UI,
    Framer_Motion,
    HTML5,
    CSS3,
}

public enum DATABASES
{
    MongoDB,
    MySQL,
    PostgreSQL,
    Redis,
    Prisma_ORM,
    Mongoose,
}

public enum DEVOPS
{
    Docker,
    NGINX,
    PM2,
    Vercel,
    Netlify,
    Firebase,
    VPS,
    Jenkins,
    Certbot,
}

public enum AUTH_AND_SECURITY
{
    JWT,
    OAuth2,
    Google_Login,
    Facebook_Login,
    RBAC,
    Rate_Limiting,
}

public enum PAYMENTS
{
    Stripe,
    Razorpay,
    PayPal,
    Webhooks,
    Subscriptions,
}

public enum TESTING
{
    Jest,
    Mocha,
    Cypress,
    Playwright,
    Postman,
}

public enum TOOLS
{
    Git,
    GitHub,
    VS_Code,
    Figma,
    Webpack,
    Vite,
    ESLint,
    Prettier,
    Insomnia,
    Chrome_DevTools,
}
```

---

```csharp
public partial class EDUCATION : Universities
{
    private void IslamiaCollegeUniversityPeshawar()
    {
        var _Degree = "Bachelor of Science";
        var _Major  = "Software Engineering";
        var _Date   = Range(debut: 2019, fin: 2023);
        var _Focus  = new string[]
        {
            "Algorithms & Data Structures",
            "Software Development Methodologies",
            "Computer Science Fundamentals",
        };
    }

    private void MuslimModelSchoolAndCollege()
    {
        var _Level = "Higher Secondary Education";
        var _Major = "Computer Science";
        var _Date  = Range(debut: 2017, fin: 2019);
    }
}
```

---

```csharp
public static class EXPERIENCE
{
    public void GS1_Saudi_Arabia()
    {
        var _Title = "Software Engineer — MERN Stack";
        var _Date  = Range(debut: "Dec 2025", fin: "PRESENT");
        var _Link  = "https://gs1.org.sa";

        /* Developing and maintaining enterprise-grade web applications
         * and internal tools based on GS1 global standards. Building
         * scalable MERN solutions to streamline supply chain and retail
         * operations while ensuring high performance and spec compliance. */
    }

    public void Nartec_Solutions()
    {
        var _Title = "Full Stack Engineer";
        var _Date  = Range(debut: "Nov 2023", fin: "Dec 2025");
        var _Link  = "https://nartec-solutions.com";

        /* Full-stack development across multiple enterprise products.
         * Delivered scalable REST APIs, real-time dashboards, IoT tools,
         * and business process automation systems. */
    }

    public void ExtremSoft()
    {
        var _Title = "Full Stack Developer";
        var _Date  = Range(debut: "Dec 2020", fin: "Oct 2023");

        /* End-to-end web application development for diverse clients.
         * Built REST APIs, integrated third-party services, and managed
         * VPS deployments with CI/CD pipelines. */
    }

    public void Tech_Emulsion()
    {
        var _Title = "Frontend Developer";
        var _Date  = Range(debut: "Feb 2020", fin: "Sep 2020");

        /* Translated Figma UI/UX designs into responsive, performant
         * React interfaces. Built component libraries and styling systems. */
    }
}
```

---

```csharp
public enum SERVICES
{
    // Full-Stack Web Development
    //   Scalable & secure apps — React · Node.js · MongoDB · PostgreSQL

    // Backend API Development
    //   REST APIs · Express.js · Prisma · Swagger docs · Validation

    // Frontend Architecture
    //   React · Vite · Redux Toolkit · React Query · Code Splitting

    // UI_UX_And_Design_Systems,
    //   Figma → Code · Tailwind CSS · Material UI · Framer Motion

    // Authentication_And_Security,
    //   JWT · OAuth 2.0 · Social Logins · RBAC · Rate Limiting

    // Payment_Gateway_Integration,
    //   Stripe · Razorpay · PayPal · Webhooks · Subscriptions

    // Maps_And_Location_Services,
    //   Google Maps · Mapbox · Leaflet · Autocomplete · Tracking

    // Deployment_And_DevOps,
    //   Docker · PM2 · NGINX · SSL · CI/CD · VPS · Vercel

    // Real_Time_Communication,
    //   Socket.io · STOMP · Redis Queues · Live Chat

    // Testing_And_QA,
    //   Jest · Cypress · Playwright · Postman · Mocha
}
```

---

```csharp
public enum FEATURED_PROJECTS
{
    // Artworks_by_Afreen         → artworksbyafreen.com
    //   E-commerce · Digital artworks · Custom stickers & prints

    // Selftor                    → selftor.com
    //   Real estate · Short-term rental marketplace (Airbnb-style)

    // GS1_Saudi_Arabia           → gs1.org.sa
    //   Official GS1 portal · Barcodes · Product identification standards

    // ME_Accounts_Audit          → meaccountsaudit.com
    //   UAE auditing · VAT consultancy · Financial advisory portal

    // Sabi_Unique_Collection     → sabiuniquecollection.com
    //   Luxury fashion e-commerce · Premium ready-to-wear clothing

    // Vacanzy                    → vacanzy.co
    //   Company formation · Trade licensing · Visa support platform

    // Cyber_Nexus_LLC            → cybernexusllc.us
    //   IT & cybersecurity consulting · Threat assessments

    // Food_App_React_Native      → github.com/Sadeeq499/food-app-react-native
    //   Mobile food delivery · Order & delivery tracking

    // FWatch                     → fwatch.gstsa1.org
    //   Fire safety equipment · Compliance tracking · Real-time monitoring

    // Quranic_World              → quranic-world.vercel.app
    //   Online Quran & Arabic courses · Live scheduling · Expert teachers

    // SUE_Realty                 → suerealty.com
    //   Dubai real estate · Luxury listings · Off-plan investments

    // Nartec_Solutions           → nartec-solutions.com
    //   Tech solutions · Software · IoT · Business automation
}
```

---

<div align="center">

```
╔═══════════════════════════════════════════╗
║      // LET'S BUILD SOMETHING GREAT       ║
╚═══════════════════════════════════════════╝
```

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-sadeeqdev.tech-0A66C2?style=for-the-badge)](https://www.sadeeqdev.tech)
[![Email](https://img.shields.io/badge/📧_Email-muhammadsadeeq11223@gmail.com-D14836?style=for-the-badge)](mailto:muhammadsadeeq11223@gmail.com)
[![WhatsApp](https://img.shields.io/badge/💬_WhatsApp-%2B92_306_5799407-25D366?style=for-the-badge)](https://wa.me/923065799407)

---

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Sadeeq499&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Sadeeq499&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

---

<sub><code>// © 2026 Muhammad Sadeeq — Full Stack Developer & UI/UX Designer</code></sub>

</div>
