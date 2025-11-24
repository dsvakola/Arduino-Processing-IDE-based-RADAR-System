# Contributing to Arduino + Processing RADAR System

Thank you for your interest in improving this educational project!  
This repository is primarily for **students and educators**, so contributions should keep clarity and learning value as top priorities.

---

## 🧑‍💻 Who can contribute?

- Students of Vidyasagar Academy  
- Teachers and mentors  
- Open-source enthusiasts interested in Arduino + Processing

You can contribute by:
- Improving documentation and comments  
- Suggesting better code structure or readability  
- Adding small, well-explained new features  

---

## 🐛 Reporting Issues

If you find a bug or have a suggestion:

1. Go to the **Issues** tab.
2. Click **New issue**.
3. Clearly describe:
   - What you expected to happen  
   - What actually happened  
   - Steps to reproduce the issue  
   - Your OS, Arduino IDE version, and Processing version (if relevant)

Screenshot(s) are very helpful.

---

## 🔀 Making Changes (Pull Requests)

1. **Fork** this repository.
2. **Create a new branch** for your change:
   - Example: `feature/adjustable-sweep-speed` or `fix/serial-port-index-comment`
3. Make your changes with:
   - Clear, meaningful variable names  
   - Enough comments for students to understand  
4. **Test** your changes:
   - Upload to Arduino and verify compilation  
   - Run the Processing sketch and check that RADAR still works properly  
5. Commit with a descriptive message:
   - Example: `Add option to change sweep speed in Processing sketch`
6. Open a **Pull Request**:
   - Explain what you changed and why  
   - Mention any related issue numbers (if applicable)

---

## 🧩 Coding Style

- Prefer **clear code over clever code**.  
- Use meaningful names like `servoAngle`, `distanceInCm`, `maxRangeCm`.  
- Keep indentation clean and consistent.  
- Comment key parts of logic, especially anything involving:
  - Angle calculations  
  - Mapping distances to screen coordinates  
  - Serial data format between Arduino and Processing  

---

## 📦 Versioning

- The current main release is **v1.0**.
- Small, backward-compatible improvements should target **v1.x**.
- Major redesigns of the Processing UI or protocol may go into **v2.0** and beyond.

---

## 🙏 Acknowledgements

By contributing, you help make learning **Electronics, Robotics, and Visualization** easier for many students.

Thank you for your support!
