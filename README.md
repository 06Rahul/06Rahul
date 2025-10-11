<h1 align="center">Hi 👋, I'm Rahul Mamgain</h1>
<h3 align="center">🚀 A passionate Software Developer & Lifelong Learner</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&size=28&center=true&vCenter=true&lines=Software+Developer;Spring+Boot+Enthusiast;DSA+Learner+%F0%9F%92%BB;Java+%7C+JS+%7C+SQL+Lover;Always+growing+with+Anime!+%F0%9F%8E%A9" alt="Typing SVG" />
</p>

---

```java
/**
 * @author Rahul
 * @version 1.0
 * 🚀 A passionate Software Developer & Lifelong Learner
 */

public class SoftwareEngineer {

    private String name;
    private String role;
    private String[] techStack;
    private String[] learning;
    private String[] interests;

    public SoftwareEngineer() {
        this.name = "Rahul Mamgain";
        this.role = "Software Developer";
        this.techStack = new String[]{"Java", "Spring Boot", "JavaScript", "SQL"};
        this.learning = new String[]{"Advanced DSA", "JavaScript"};
        this.interests = new String[]{"Anime", "Manga"};
    }

    public void introduce() {
        System.out.println("Hi 👋, I'm " + name);
        System.out.println("🚀 A passionate " + role + " & lifelong learner.");
        System.out.println("\n🌱 Currently learning: " + String.join(", ", learning));
        System.out.println("💬 Ask me about: " + String.join(", ", techStack));
        System.out.println("⚡ Fun fact: I love " + String.join(" & ", interests) + "!");
        System.out.println("\n📫 Reach me at: rahulmamgain269@gmail.com");
        System.out.println("🌐 Portfolio: https://v0-javascript-portfolio-navy.vercel.app/");
        System.out.println("💻 LinkedIn: https://www.linkedin.com/in/rahulmamgainmca/");
        System.out.println("🧠 LeetCode: https://leetcode.com/u/rahulmamgain/");
        System.out.println("🧩 GeeksforGeeks: https://auth.geeksforgeeks.org/user/mamgai1g2q/");
        System.out.println("\nThanks for visiting! Keep coding and growing ✨");
    }

    public static void main(String[] args) {
        SoftwareEngineer me = new SoftwareEngineer();
        me.introduce();
    }
}
