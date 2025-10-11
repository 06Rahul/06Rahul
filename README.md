




<h1 align="center">Hi 👋, I'm Rahul Mamgain</h1>
<h3 align="center">🚀 A passionate Software Developer & Lifelong Learner</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=28&center=true&vCenter=true&lines=Software+Developer;Spring+Boot+Enthusiast;DSA+Learner+%F0%9F%92%BB;Java+%7C+JS+%7C+SQL+Lover;Always+growing+with+Anime!+%F0%9F%8E%A9" alt="Typing SVG" />
</p>

/**
 * Hi 👋, I'm Rahul Mamgain
 * A passionate Software Developer & Lifelong Learner.
 *
 * Portfolio: v0-javascript-portfolio-navy.vercel.app
 * Email: rahulmamgain269@gmail.com
 *
 * Focus: Java, Spring Boot, SQL, JavaScript
 * Interests: Anime & Manga
 */
public final class RahulMamgain {

    // ===== Quick Links =====
    public static final String PORTFOLIO = "https://v0-javascript-portfolio-navy.vercel.app/";
    public static final String EMAIL = "rahulmamgain269@gmail.com";
    public static final String LINKEDIN = "https://www.linkedin.com/in/rahulmamgainmca/";
    public static final String LEETCODE = "https://leetcode.com/u/rahulmamgain/";
    public static final String GEEKSFORGEEKS = "https://auth.geeksforgeeks.org/user/mamgai1g2q/";

    // ===== Tech Stack =====
    private static final String[] LANGUAGES = {
            "Java", "JavaScript", "SQL", "HTML", "CSS"
    };

    private static final String[] FRAMEWORKS = {
            "Spring Boot"
    };

    private static final String[] DATABASES = {
            "MySQL", "PostgreSQL"
    };

    private static final String[] TOOLS = {
            "Git", "Postman", "Docker", "RabbitMQ"
    };

    // ===== Learning Tracks =====
    private static final String[] CURRENTLY_LEARNING = {
            "JavaScript fundamentals", "Data Structures & Algorithms"
    };

    private static final String[] DSA_TOPICS = {
            "Arrays", "Strings", "HashMaps/Sets", "Heaps", "Sliding Window"
    };

    // ===== Status =====
    private static final boolean OPEN_TO_DSA_HELP = true;

    private RahulMamgain() {}

    /**
     * Prints a banner in a Java-console style.
     */
    public static void banner() {
        println("==============================================");
        println("  Rahul Mamgain — Software Developer");
        println("  Java | Spring Boot | SQL | JavaScript");
        println("  Always learning, powered by anime ⚡");
        println("==============================================");
    }

    /**
     * Shows what is being learned currently.
     */
    public static void learning() {
        println("🌱 Currently learning:");
        for (String topic : CURRENTLY_LEARNING) {
            println("  - " + topic);
        }
        println("🧠 DSA focus:");
        for (String t : DSA_TOPICS) {
            println("  - " + t);
        }
        println("🤝 Open to help with Advanced DSA: " + OPEN_TO_DSA_HELP);
    }

    /**
     * Displays tech stack in sections.
     */
    public static void stack() {
        section("Languages", LANGUAGES);
        section("Frameworks", FRAMEWORKS);
        section("Databases", DATABASES);
        section("Tools", TOOLS);
    }

    /**
     * Lists important links.
     */
    public static void links() {
        println("🔗 Links:");
        println("  Portfolio: " + PORTFOLIO);
        println("  Email: " + EMAIL);
        println("  LinkedIn: " + LINKEDIN);
        println("  LeetCode: " + LEETCODE);
        println("  GeeksforGeeks: " + GEEKSFORGEEKS);
    }

    /**
     * A minimal Spring-like snippet representing Java focus.
     */
    public static void javaFocusSnippet() {
        println("---- Java Focus Snippet ----");
        println("@RestController");
        println("class HelloController {");
        println("    @GetMapping(\"/api/v1/hello\")");
        println("    public Map<String, Object> hello() {");
        println("        return Map.of(\"message\", \"Hello from Spring Boot\", \"stack\", \"Java\");");
        println("    }");
        println("}");
        println("----------------------------");
    }

    /**
     * Fun fact block.
     */
    public static void fun() {
        println("⚡ Fun fact: Anime and manga spark creativity and consistency.");
    }

    /**
     * Entry point to render the README-like output.
     */
    public static void main(String[] args) {
        banner();
        links();
        println("");
        learning();
        println("");
        stack();
        println("");
        javaFocusSnippet();
        println("");
        fun();
    }

    // ===== helpers =====

    private static void section(String name, String[] items) {
        println("📦 " + name + ":");
        for (String s : items) {
            println("  - " + s);
        }
    }

    private static void println(String s) {
        System.out.println(s);
    }
}
