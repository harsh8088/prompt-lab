# 🧪 Prompt Lab

A curated collection of high-quality **prompt templates**, **prompt experiments**, and **prompt engineering patterns** for LLMs like GPT-5, Claude, Gemini, Llama, and more.

This repository acts as a **playground**, **library**, and **reference hub** for building reliable AI workflows—whether you're creating apps, agents, chatbots, or automation pipelines.


---

## 🚀 Features

- 📚 Organized prompt templates for multiple use-cases  
- 🧠 Prompt engineering techniques (CoT, ReAct, RCI, Few-shot, etc.)  
- 🎛️ Reusable structures for coding, debugging, writing, summaries, agents  
- 🔬 Experiments folder for exploring prompt variations  
- 🧩 Modular prompt components (intros, constraints, roles, outputs)  
- 🛠️ Works with any LLM provider (OpenAI, Anthropic, Google, etc.)

---

## 📁 Repository Structure

<img width="550" height="629" alt="Repository Structure" src="https://github.com/user-attachments/assets/f2e8d8c1-b56e-43aa-aaa1-bdc8017274c5" />

---

## 🔧 How to Use

1. Browse the `/templates` folder to find ready-to-use prompts.  
2. Copy any prompt into your LLM interface or API code.  
3. Customize variables inside `{curly_brackets}`.  
4. Use `/components` to build advanced, modular prompts.  
5. Try new prompts in `/experiments` and compare outputs.  

---

## 🧠 Prompt Engineering Best Practices

- **Be explicit** — define role, task, and constraints clearly.  
- **Keep format predictable** — specify output structure.  
- **Use hierarchy** — system → instructions → examples → user.  
- **Iterate** — test small prompt variations to improve reliability.  
- **Chain tasks** — break complex reasoning into steps.  

---

## 🎛️ Example Prompt (General Purpose)

```md
You are an expert assistant specialized in {domain}.  
Your goal is to help the user complete {task} with maximum clarity and accuracy.

### Rules:
- Think step-by-step.
- Provide structured output.
- If information is missing, ask before answering.
- Avoid assumptions unless explicitly allowed.

### Output Format:
{desired_format}

User request:
{user_input}
```



## 🤝 Contributing
Contributions are welcome!
1. Add your own templates, clean up existing ones, or improve documentation.
2. Fork the repo
3. Create a new branch
4. Add/update prompts
5. Submit a pull request


## 📜 License
- This project is licensed under the MIT License.
- You’re free to use, modify, share, and integrate these prompts in personal or commercial projects.


## ⭐ Support
If you find this repository useful:
1. ⭐ Star the repo
2. 📤 Share it with other developers
3. 💬 Suggest new prompt categories


