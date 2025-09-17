# GitHub Copilot C# Demos

This repository contains a collection of C# demo projects designed for a developer session on GitHub Copilot, hosted for NYC DDC. The objective is to showcase how GitHub Copilot can be integrated into the Software Development Lifecycle (SDLC) to enhance developer productivity, automate tasks, and support architectural design.

## 📦 Repository Structure

Each folder includes:
- ✅ Sample C# code
- 📜 Step-by-step demo script
- 🗣️ Speaker notes for presenters

### 1. Code Documentation
**Overview:** Demonstrates how GitHub Copilot can automatically generate XML documentation comments for methods and classes.

**Setup Instructions:**
- Open the solution in Visual Studio
- Navigate to the `CodeDocumentationDemo.cs` file
- Begin typing method signatures and observe Copilot's suggestions

**Presenter Guidance:**
- Show a method without documentation
- Use Copilot to generate XML comments
- Discuss benefits for maintainability and readability

---

### 2. Code Review
**Overview:** Simulates a pull request scenario where Copilot suggests improvements and identifies potential issues.

**Setup Instructions:**
- Open the `CodeReviewDemo.cs` file
- Introduce intentional inefficiencies or bugs
- Use Copilot to suggest fixes

**Presenter Guidance:**
- Highlight Copilot’s ability to refactor code
- Discuss how it supports peer review and quality assurance

---

### 3. Copilot Coding Agent
**Overview:** Uses natural language prompts to build a minimal ASP.NET Core web application.

**Setup Instructions:**
- Open the `CopilotAgentDemo.csproj` project
- Start with a comment prompt like `// Create a basic ASP.NET Core web app with a homepage`
- Let Copilot generate controllers, views, and routing

**Presenter Guidance:**
- Emphasize Copilot’s ability to scaffold applications
- Discuss time savings and rapid prototyping

---

### 4. Contextual Intelligence
**Overview:** Demonstrates Copilot’s awareness across multiple files and its ability to suggest contextually relevant code.

**Setup Instructions:**
- Open `Main.cs` and `Utils.cs`
- Modify a function in `Utils.cs` and observe Copilot’s suggestions in `Main.cs`

**Presenter Guidance:**
- Show how Copilot understands project structure
- Discuss implications for large codebases

---

### 5. Architectural Design Whiteboarding
**Overview:** Uses prompts to generate architectural components for a microservices-based e-commerce platform.

**Setup Instructions:**
- Open `ArchitectureDesignPrompt.txt`
- Paste prompt into a Copilot-enabled IDE
- Review generated architecture classes and interfaces

**Presenter Guidance:**
