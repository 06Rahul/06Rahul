/**
 * Hi 👋, I'm Rahul Mamgain
 * Software Developer | Java Enthusiast | Lifelong Learner
 *
 * Links (clickable in README above):
 * - Email: mailto:rahulmamgain269@gmail.com
 * - LinkedIn: https://www.linkedin.com/in/rahulmamgainmca/
 * - LeetCode: https://leetcode.com/u/rahulmamgain/
 * - GeeksforGeeks: https://www.geeksforgeeks.org/user/mamgai1g2q/
 * - HackerRank: https://www.hackerrank.com/dashboard
 * - Portfolio: https://v0-javascript-portfolio-navy.vercel.app/
 *
 * Focus: Java, Spring Boot, SQL, JavaScript
 * Platforms: Dynamics 365 CRM, Power Platform
 * Fun: Anime & Manga
 */
public final class RahulMamgain {

    // ===== Links as plain strings (for console display) =====
    public static final String EMAIL = "mailto:rahulmamgain269@gmail.com";
    public static final String LINKEDIN = "https://www.linkedin.com/in/rahulmamgainmca/";
    public static final String LEETCODE = "https://leetcode.com/u/rahulmamgain/";
    public static final String GEEKSFORGEEKS = "https://www.geeksforgeeks.org/user/mamgai1g2q/";
    public static final String HACKERRANK = "https://www.hackerrank.com/dashboard";
    public static final String PORTFOLIO = "https://v0-javascript-portfolio-navy.vercel.app/";

    // ===== Skills =====
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

    // ===== Learning tracks =====
    private static final String[] CURRENTLY_LEARNING = {
        "JavaScript fundamentals", "Data Structures & Algorithms"
    };

    private static final String[] DSA_TOPICS = {
        "Arrays", "Strings", "HashMaps/Sets", "Heaps", "Sliding Window"
    };

    private RahulMamgain() {}

    public static void main(String[] args) {
        banner();
        links();
        learning();
        skills();
        javaFocusSnippet();
        funFact();
    }

    private static void banner() {
        println("==============================================");
        println("   👋 Hi, I'm Rahul Mamgain");
        println("   Software Developer | Java | Spring Boot | SQL");
        println("   Exploring Power Platform & Cloud | Anime Lover ⚡");
        println("==============================================");
        println("");
    }

    private static void links() {
        println("🔗 Connect with me:");
        println("  📫 Email     : " + EMAIL);
        println("  💼 LinkedIn  : " + LINKEDIN);
        println("  🧩 LeetCode  : " + LEETCODE);
        println("  🧠 GfG       : " + GEEKSFORGEEKS);
        println("  🏆 HackerRank: " + HACKERRANK);
        println("  🌐 Portfolio : " + PORTFOLIO);
        println("");
    }

    private static void learning() {
        println("🌱 Currently learning:");
        for (String s : CURRENTLY_LEARNING) println("  • " + s);
        println("🧠 DSA focus:");
        for (String s : DSA_TOPICS) println("  • " + s);
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

    private static void javaFocusSnippet() {
        println("---- Java Focus Snippet ----");
        println("@org.springframework.web.bind.annotation.RestController");
        println("class HelloController {");
        println("    @org.springframework.web.bind.annotation.GetMapping(\"/api/v1/hello\")");
        println("    public java.util.Map<String, Object> hello() {");
        println("        return java.util.Map.of(\"message\", \"Hello from Spring Boot\", \"stack\", \"Java\");");
        println("    }");
        println("}");
        println("----------------------------");
        println("");
    }

    private static void funFact() {
        println("⚡ Fun Fact: Design patterns and anime arcs both teach structure, pacing, and patience!");
    }

    // ===== helpers =====
    private static void section(String title, String[] items) {
        println(title + ":");
        for (String i : items) println("  • " + i);
        println("");
    }

    private static void println(String s) {
        System.out.println(s);
    }
}
