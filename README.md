# prompt-lab

🧪 Prompt Lab
A curated collection of high-quality prompt templates, prompt experiments, and prompt engineering patterns for LLMs like GPT-5, Claude, Gemini, Llama, and more.
This repository acts as a playground, library, and reference hub for building reliable AI workflows—whether you're creating apps, agents, chatbots, or automation pipelines.


🚀 Features
📚 Organized prompt templates for multiple use-cases
🧠 Prompt engineering techniques (CoT, ReAct, RCI, FEW-SHOT, etc.)
🎛️ Reusable structures for coding, debugging, writing, summaries, agents
🔬 Experiments folder for exploring prompt variations
🧩 Modular prompt components (intros, constraints, roles, outputs)
🛠️ Works with any LLM provider (OpenAI, Anthropic, Google, etc.)

📁 Repository Structure



prompt-lab/
│
├── templates/
│   ├── coding/
│   ├── writing/
│   ├── analysis/
│   ├── agents/
│   ├── productivity/
│   └── misc/
│
├── experiments/
│   ├── chain-of-thought/
│   ├── reasoning/
│   ├── compression/
│   └── styles/
│
├── patterns/
│   ├── system-prompts/
│   ├── role-based/
│   ├── task-based/
│   └── persona/
│
├── components/
│   ├── constraints/
│   ├── tone/
│   ├── formatting/
│   └── reusable-blocks/
│
└── README.md


🔧 How to Use
Browse the /templates folder to find ready-to-use prompts.
Copy any prompt into your LLM interface or API code.
Customize variables inside {curly_brackets}.
Use /components to build advanced, modular prompts.
Try new prompts in /experiments and compare outputs.


🧠 Prompt Engineering Best Practices

Be explicit — define role, task, and constraints clearly.
Keep format predictable — specify output structure.
Use hierarchy — system → instructions → examples → user.
Iterate — test small prompt variations to improve reliability.
Chain tasks — break complex reasoning into steps.


🎛️ Example Prompt (General Purpose)

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


🤝 Contributing
Contributions are welcome!
Add your own templates, clean up existing ones, or improve documentation.
Fork the repo
Create a new branch
Add/update prompts
Submit a pull request


📜 License
This project is licensed under the MIT License.
You’re free to use, modify, share, and integrate these prompts in personal or commercial projects.


⭐ Support
If you find this repository useful:
⭐ Star the repo
📤 Share it with other developers
💬 Suggest new prompt categories


