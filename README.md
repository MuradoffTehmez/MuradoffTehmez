// GitHub Profile README Generator for Tahmaz Muradov

class GitHubProfileReadme {
    constructor() {
        this.name = "Tahmaz Muradov";
        this.username = "MuradoffTehmez";
        this.socialLinks = {
            linkedin: "muradovtahmaz",
            github: "MuradoffTehmez",
            facebook: "muradoffcode",
            instagram: "muradoffcode",
            x: "muradoffcode"
        };
    }

    generateTechStackBadges() {
        return {
            programmingLanguages: [
                "![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)",
                "![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)",
                "![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)",
                "![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)"
            ],
            webDevelopment: [
                "![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)",
                "![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)",
                "![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)",
                "![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)"
            ],
            frameworksAndPlatforms: [
                "![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)",
                "![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)",
                "![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)",
                "![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)"
            ],
            databases: [
                "![Microsoft SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)",
                "![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)"
            ],
            toolsAndOthers: [
                "![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)",
                "![Adobe Photoshop](https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)",
                "![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)"
            ]
        };
    }

    generateSocialLinks() {
        const platforms = {
            linkedin: "https://www.linkedin.com/in/",
            github: "https://github.com/",
            facebook: "https://facebook.com/",
            instagram: "https://instagram.com/",
            x: "https://x.com/"
        };

        return Object.entries(this.socialLinks)
            .map(([platform, username]) => 
                `[![${platform.charAt(0).toUpperCase() + platform.slice(1)}](https://img.shields.io/badge/${platform}-${this.getPlatformColor(platform)}?style=for-the-badge&logo=${platform}&logoColor=white)](${platforms[platform]}${username})`
            )
            .join("\n");
    }

    getPlatformColor(platform) {
        const colors = {
            linkedin: "0077B5",
            github: "100000",
            facebook: "1877F2",
            instagram: "E4405F",
            x: "000000"
        };
        return colors[platform] || "000000";
    }

    generateReadme() {
        const techStack = this.generateTechStackBadges();
        const socialLinks = this.generateSocialLinks();

        return `# 👋 Merhaba! Ben ${this.name}

## 🚀 Hakkımda
Tutkulu bir full-stack yazılım geliştiricisi olarak, birden fazla programlama dili ve framework'te uzmanlaşmış bulunmaktayım. Amacım yenilikçi çözümler üretmek ve sürekli olarak yeni teknolojiler öğrenmektir.

## 🌐 Benimle Bağlantı Kur
${socialLinks}

## 💻 Teknoloji Yığını

### Programlama Dilleri
${techStack.programmingLanguages.join("\n")}

### Web Geliştirme
${techStack.webDevelopment.join("\n")}

### Frameworkler & Platformlar
${techStack.frameworksAndPlatforms.join("\n")}

### Veritabanları
${techStack.databases.join("\n")}

### Araçlar & Diğerleri
${techStack.toolsAndOthers.join("\n")}

## 📊 GitHub
