## What is a Pull Request?

A **Pull Request (PR)** is a way to **propose changes** to a repository and ask the project owner (or teacher) to **review and merge** those changes.

Instead of directly modifying the main branch, you submit your work for review.

👉 A Pull Request means:  
**“Here are my changes. Please review them and decide if they can be added.”**

---

## Why Use Pull Requests?

Pull Requests are important because they:

- Enable **code review**  
- Allow **feedback and discussion**  
- Prevent **breaking the main project**  
- Encourage **safe collaboration**  
- Track **who changed what and why**

They are commonly used in:

- Team projects  
- Open-source contributions  
- Professional software development  
- GitHub Classroom assignments

---

## How Does a Pull Request Work?

A typical Pull Request workflow:

1. Create a **branch or fork**  
2. Make your **changes**  
3. **Commit** your work  
4. **Push** changes to GitHub  
5. Open a **Pull Request**  
6. A reviewer **checks your work**  
7. Changes are **approved and merged** (or feedback is given)

---

##  Basic Pull Request Workflow

### Create a new branch
```bash
git checkout -b feature/my-changes
```

### Commit your changes
```bash
git add .
git commit -m "Describe your changes clearly"
```

### Push the branch
```bash
git push origin feature/my-changes
```

### Open the Pull Request
1. Go to the repository on GitHub  
2. Click **Compare & pull request**  
3. Add a **clear title** and **description**  
4. Click **Create pull request**

---

##  What Happens After Opening a Pull Request?

The reviewer can:

- Approve the Pull Request ✅  
- Request changes 💬  
- Reject the Pull Request ❌  

If changes are requested, you can **update your code** and push new commits to the same branch.

---

## 🆚 Pull Request vs Direct Push

| Action       | When to use                          |
|-------------|-------------------------------------|
| Direct push | You own the repository and work alone |
| Pull Request| Team work, forks, classroom submissions |

Pull Requests are **safer and more professional**.
