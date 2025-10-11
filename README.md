<h1 align="center">Hi 👋, I'm Rahul Mamgain</h1>
<h3 align="center">🚀 Software Developer | Java Enthusiast | Lifelong Learner</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=28&center=true&vCenter=true&lines=Software+Developer;Spring+Boot+Developer;Java+%7C+Spring+%7C+SQL+Lover;Power+Platform+%7C+Dynamics+365;Always+learning+with+Anime!+⚡" alt="Typing SVG" />
</p>

```java
public final class RahulMamgain {

    public static final String PORTFOLIO = "https://v0-javascript-portfolio-navy.vercel.app/";
    public static final String EMAIL = "mailto:rahulmamgain269@gmail.com";
    public static final String LINKEDIN = "https://www.linkedin.com/in/rahulmamgainmca/";
    public static final String LEETCODE = "https://leetcode.com/u/rahulmamgain/";
    public static final String GEEKSFORGEEKS = "https://www.geeksforgeeks.org/user/mamgai1g2q/";
    public static final String HACKERRANK = "https://www.hackerrank.com/dashboard";

    private static final String[] LANGUAGES = {
        "Java", "JavaScript (Basic)", "C# (Basic)", "SQL", "HTML"
    };

    private static final String[] FRAMEWORKS = {
        "Spring Boot", "Spring Framework", "Spring Security", "JPA/Hibernate ORM", "Spring Cloud"
    };

    private static final String[] DATABASES = {
        "MySQL", "PostgreSQL"
    };

    private static final String[] TOOLS = {
        "Git/GitHub", "Postman", "Swagger", "Linux", "CI/CD", 
        "IntelliJ IDEA", "VS Code", "Cursor AI", "GitHub Copilot"
    };

    private static final String[] PLATFORMS = {
        "Dynamics 365 CRM", "Power Platform (Power BI, Power Automate, Power Pages)"
    };

    private static final String[] AI_TOOLS = {
        "ChatGPT", "Gemini API"
    };

    private RahulMamgain() {}

    public static void main(String[] args) {
        banner();
        links();
        skills();
        funFact();
    }

    private static void banner() {
        println("==============================================");
        println("   👋 Hi, I'm Rahul Mamgain");
        println("   Software Developer | Java | Spring Boot | SQL");
        println("   Exploring Power Platform & Cloud | Anime Lover ⚡");
        println("==============================================");
    }

    private static void links() {
        println("🔗 Connect with me:");
        println("  📫 Email: " + EMAIL);
        println("  💼 LinkedIn: " + LINKEDIN);
        println("  💻 Portfolio: " + PORTFOLIO);
        println("  🧩 LeetCode: " + LEETCODE);
        println("  🧠 GeeksforGeeks: " + GEEKSFORGEEKS);
        println("  🏆 HackerRank: " + HACKERRANK);
        println("");
    }

    private static void skills() {
        section("💬 Languages", LANGUAGES);
        section("⚙️ Frameworks", FRAMEWORKS);
        section("🗄️ Databases", DATABASES);
        section("🧰 Tools", TOOLS);
        section("🌐 Platforms", PLATFORMS);
        section("🤖 AI Tools", AI_TOOLS);
    }

    private static void funFact() {
        println("");
        println("⚡ Fun Fact: I find design patterns and anime arcs strangely similar — both teach structure, pacing, and patience!");
    }

    private static void section(String title, String[] items) {
        println(title + ":");
        for (String i : items) println("  • " + i);
        println("");
    }

    private static void println(String s) {
        System.out.println(s);
    }
}
