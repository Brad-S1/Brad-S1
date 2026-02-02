# Hello, I'm Brad Sommer 👋

## About Me

I'm a Mechanical Engineer with 7.5+ years of defense experience, recently completed my BS in Computer Science (4.0 GPA). I combine systems thinking from naval engineering with software development skills, with particular interest in low-level programming, embedded systems, and hardware-software interfaces.

**Background:**
- BS Computer Science - Oregon State University (December 2025) | 4.0 GPA  
- BS Mechanical Engineering - Washington State University (2018) | 3.93 GPA
- 7.5 years defense engineering experience (Naval nuclear systems → undersea weapons)
- Active Secret clearance
- Washington State

## Technical Skills

### Languages
- **Systems Programming:** C, Assembly (MASM x86)
- **Scripting & General:** Python, JavaScript
- **Engineering:** MATLAB

### Systems & Tools
- **Development:** Linux/Unix, Git, Make, VS Code, PyCharm
- **Embedded/Low-level:** SDL2, systems programming, hardware/software integration
- **Testing:** unittest (Python)

### Engineering & Domain Expertise
- Systems analysis and troubleshooting
- Technical documentation and procedures
- Cross-functional project leadership
- Defense systems (torpedoes, naval propulsion, fluid systems)

### Web Development
- **Frontend:** React, HTML/CSS
- **Backend:** Node.js, Express
- **Databases:** MongoDB, MySQL

### Data Science & Machine Learning
- **Frameworks:** TensorFlow/Keras, scikit-learn
- **Libraries:** pandas, NumPy
- **Domains:** Deep learning (CNNs, RNNs, LSTMs), classification, time-series prediction

## Featured Projects

### Intel 8080 CPU Emulator
Cycle-accurate Intel 8080 CPU emulator in C capable of executing original Space Invaders ROM.
- Led technical development: implemented 63 opcodes, reviewed all 192 implementations
- Designed cross-platform build system (Make/sdl2-config) for macOS and WSL2
- Refactored modular architecture separating CPU core, graphics, and I/O subsystems
- Tech: C, SDL2, low-level systems programming, conditional compilation
- 🔗 [View Repository](https://github.com/Brad-S1/intel-8080-cpu-emulator)

### Unix Shell Implementation (smallsh)
POSIX-compliant Unix shell in C demonstrating low-level process control and signal handling.
- Implemented async-signal-safe signal handlers using only signal-safe functions (`write()`, `_exit()`)
- Designed process group management with graceful `SIGTERM`/`SIGKILL` cascade for complete child cleanup
- Built non-blocking background process monitoring using `waitpid()` with `WNOHANG` flag
- Engineered modular architecture with systematic memory management (zero leaks)
- Tech: C, Unix system calls (fork, exec, dup2, sigaction), POSIX signal handling, ~700 LOC
- 🔗 [View Repository](https://github.com/Brad-S1/smallsh-unix-shell)

### String Primitives & Low-Level I/O
MASM x86 assembly program demonstrating numeric I/O without standard library functions.
- Custom ASCII-to-integer conversion using `LODSB` with CPU flag-based overflow detection
- Integer-to-ASCII conversion using `STOSB` with INT32_MIN edge case handling
- STDCall calling convention with stack-based parameter passing
- Comprehensive byte-level input validation and error recovery
- Tech: MASM x86 Assembly, string primitives, systems programming
- 🔗 [View Repository](https://github.com/Brad-S1/assembly-string-primitives)

### Solar Flare Prediction: Comparative Neural Network Study (CS435 Portfolio Project)
Systematic comparison of neural network architectures for predicting major solar flares 
using multivariate time series data (60 timesteps × 24 magnetic field parameters).
- Implemented ANN and LSTM classifiers in TensorFlow/Keras with TSS-optimized 
  thresholds; ANN achieved 0.60 TSS vs LSTM 0.55 across 4 temporal partitions
- Designed temporal cross-validation framework to prevent data leakage across Solar 
  Cycle 24 phases; discovered LSTM maintained 14× better performance during challenging 
  cycle transitions (TSS 0.19 vs 0.01)
- Debugged LSTM training failures through systematic architecture simplification; 
  identified random seed sensitivity requiring careful initialization strategies
- Tech: Python, TensorFlow/Keras, scikit-learn, pandas, NumPy, imbalanced classification
- 🔗 [View Repository](https://github.com/Brad-S1/solar-flare-prediction)

## Professional Experience

**Mechanical Engineer, Lightweight Torpedo Systems**  
*Naval Undersea Warfare Center Division Keyport | September 2024 - Present*
- Lead In-Service Engineer for lightweight torpedo weapon systems projects
- Conduct technical risk analysis and system engineering reviews
- Develop lifecycle sustainment plans and reliability studies

**Nuclear Engineer**  
*Puget Sound Naval Shipyard & IMF | June 2018 - September 2024*
- Led technical problem-solving for complex electro-mechanical systems
- Developed 200+ technical procedures requiring precise specification compliance
- Managed cross-functional engineering teams on high-stakes projects
- Mentored 20+ junior engineers in systems thinking and diagnostic methodologies

[See [LinkedIn](https://www.linkedin.com/in/sommer-brad/) for complete experience]

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brad%20Sommer-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sommer-brad/)
[![GitHub](https://img.shields.io/badge/GitHub-Brad--S1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Brad-S1)

---

*Active Secret Clearance | Washington State*
