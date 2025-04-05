
# ReactionTestApp 🎮

A Java-based reaction time testing game built with **Swing GUI**. This app challenges users with visual cues to test their reflexes and reaction speed through multiple difficulty levels.

---

## 🚀 Features

- 🎨 Color-based visual cues
- 🧠 Multiple levels with increasing difficulty
- 🖥️ GUI built using Java Swing
- 🧪 Unit tests with JUnit 5
- 📏 Code quality checks with Checkstyle and test coverage via JaCoCo

---

## 📂 Project Structure

```
reactionapp/
├── src/
│   ├── main/
│   │   └── java/edu/neu/mgen/
│   │       ├── ReactionTestApp.java   # Level 1: basic reaction test
│   │       ├── RT_level2.java         # Level 2: enhanced challenge
│   │       ├── RT_level3.java         # Level 3: advanced difficulty
│   │       └── App.java               # Entry point / setup
│   └── test/
│       └── java/edu/neu/mgen/
│           └── AppTest.java           # Unit tests
├── pom.xml                            # Maven build config
```

---

## 🛠️ Requirements

- Java 8+
- Maven

---

## ⚙️ How to Run

```bash
# Compile the project
mvn compile

# Run the app (ensure you have a display for Swing GUI)
mvn exec:java -Dexec.mainClass="edu.neu.mgen.App"
```

> Note: You may need to configure `App.java` to invoke a specific level (e.g., `ReactionTestApp`, `RT_level2`, etc.)

---

## 📦 Build & Test

```bash
# Run tests
mvn test

# Generate code coverage report
mvn jacoco:report
```

---

## 📄 License

This project is licensed under the terms of the LICENSE file.
