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
        System.out.println("\nThanks for visiting! Keep coding and growing ✨");
    }

    public static void main(String[] args) {
        SoftwareEngineer me = new SoftwareEngineer();
        me.introduce();
    }
}
