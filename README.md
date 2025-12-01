<h1 align="center">Hi 👋, I'm Rahul Mamgain</h1>
<h3 align="center">🚀 A passionate Software Developer & Lifelong Learner</h3>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=28&center=true&vCenter=true&lines=Software+Developer;Spring+Boot+Enthusiast;DSA+Learner+%F0%9F%92%BB;Java+%7C+JS+%7C+SQL+Lover;Always+growing+with+Anime!+%F0%9F%8E%A9" alt="Typing SVG" />
</p>

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://www.linkedin.com/in/rahulmamgainmca/" target="_blank" rel="noopener noreferrer">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin" height="30" width="40" />
  </a>
  <a href="https://leetcode.com/u/rahulmamgain/" target="_blank" rel="noopener noreferrer">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="leetcode" height="30" width="40" />
  </a>
  <a href="https://auth.geeksforgeeks.org/user/mamgai1g2q/" target="_blank" rel="noopener noreferrer">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/geeks-for-geeks.svg" alt="geeksforgeeks" height="30" width="40" />
  </a>
  <a href="https://www.hackerrank.com/profile/rahulmamgain269" target="_blank" rel="noopener noreferrer">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="hackerrank" height="30" width="40" />
  </a>
  <a href="mailto:rahulmamgain269@gmail.com" target="_blank" rel="noopener noreferrer">
    <img align="center" src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg" alt="email" height="30" width="40" />
  </a>
  <a href="https://v0-javascript-portfolio-navy.vercel.app/" target="_blank" rel="noopener noreferrer">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/dribbble.svg" alt="portfolio" height="30" width="40" />
  </a>
</p>


---

```java
public class SoftwareDeveloper {

    private final String name;
    private final String role;
    private final String[] techStack;
    private final String[] frameworks;
    private final String[] cloudAndTools;
    private final String[] aiAndAutomation;
    private final String[] learning;
    private final String[] interests;

    public SoftwareEngineer() {
        this.name = "Rahul Mamgain";
        this.role = "Software Developer";

        this.techStack = new String[]{
            "Java", "JavaScript (Basic)", "C# (Beginner)", "SQL", "HTML/CSS", "RDBMS"
        };

        this.frameworks = new String[]{
            "Spring Boot", "Spring Framework", "Spring Security", "Spring Cloud (Eureka, Config, Gateway)",
            "Hibernate", "JWT", "RabbitMQ"
        };

        this.cloudAndTools = new String[]{
            "Docker", "Git/GitHub", "Postman", "Swagger", "Linux", "CI/CD", "Azure"
        };

        this.aiAndAutomation = new String[]{
            "Dynamics 365 CRM", "Power Platform (Power BI, Power Automate, Power Pages)",
            "Gemini API", "ChatGPT", "Cursor AI", "GitHub Copilot"
        };

        this.learning = new String[]{
            "Advanced DSA", "System Design", "Microservices Architecture"
        };

        this.interests = new String[]{
            "Anime", "Manga", "Tech Blogging", "Open Source"
        };
    }

    public void introduce() {
        System.out.println("Hi, I'm " + name);
        System.out.println("A passionate " + role + " & lifelong learner");

        System.out.println("Tech Stack: " + String.join(", ", techStack));
        System.out.println("Frameworks: " + String.join(", ", frameworks));
        System.out.println("Cloud & Tools: " + String.join(", ", cloudAndTools));
        System.out.println("AI & Automation: " + String.join(", ", aiAndAutomation));
        System.out.println("Currently learning: " + String.join(", ", learning));
        System.out.println("Fun fact: I recharge my brain with " + String.join(" & ", interests) + "!");

        System.out.println("Keep coding, keep exploring, keep evolving!");
    }

    public static void main(String[] args) {
        SoftwareEngineer rahul = new SoftwareEngineer();
        rahul.introduce();
    }
}
