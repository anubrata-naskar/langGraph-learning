# 🚀 LangGraph Learning Project

Master AI workflows with hands-on examples covering all LangGraph patterns - Sequential, Conditional, Iterative, Parallel processing, and Persistence using Google Gemini AI.

## 📖 Overview
Complete learning repository with 9+ interactive Jupyter notebooks demonstrating real-world AI agent architectures, from basic workflows to advanced multi-agent systems with persistent memory.

## 📁 Project Structure
```
langGraph-learning/
├── sequentialWorkFlow/     # Foundation: Linear processing patterns
│   ├── withoutLLM.ipynb   # Basic LangGraph fundamentals
│   ├── withLLM.ipynb      # AI-powered sequential chains
│   └── prompt_chaining.ipynb # Advanced prompt engineering
├── conditionalWorkFlow/    # Intermediate: Decision-making workflows
│   ├── quadraticEqu.ipynb # Math problem solving with branching
│   └── withLLM.ipynb      # AI-driven conditional routing
├── iterativeWorkFlow/      # Advanced: Feedback loops
│   └── post_creation.ipynb # Content creation with optimization
├── parallelWorkFlow/       # Expert: Concurrent processing
│   ├── cricket.ipynb      # Sports analytics pipeline
│   └── withLLM.ipynb      # Multi-agent coordination
├── persistence/            # Memory & State Persistence
│   └── 10_persistence.ipynb # Advanced persistent workflows
├── post_creation.ipynb     # Standalone iterative content example
├── requirements.txt        # Complete dependency list
├── .env                   # Secure API configuration
├── .gitignore            # Git ignore rules
└── README.md             # This comprehensive guide
```

## 🚀 Quick Setup (3 Minutes)
```bash
# 1. Clone and setup
git clone https://github.com/anubrata-naskar/langGraph-learning.git
cd langGraph-learning
python -m venv myenv && myenv\Scripts\activate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your Google API key to .env
echo "GOOGLE_API_KEY=your_key_here" > .env

# 4. Start learning!
jupyter notebook
```

## 📚 Learning Path

### 🎓 Week 1: Fundamentals
- `sequentialWorkFlow/withoutLLM.ipynb` - Core concepts
- `sequentialWorkFlow/withLLM.ipynb` - AI integration
- `conditionalWorkFlow/quadraticEqu.ipynb` - Decision making

### 🎓 Week 2: Advanced Patterns  
- `conditionalWorkFlow/withLLM.ipynb` - Smart routing
- `iterativeWorkFlow/post_creation.ipynb` - Feedback loops
- `sequentialWorkFlow/prompt_chaining.ipynb` - Prompt engineering

### 🎓 Week 3: Expert Level
- `parallelWorkFlow/cricket.ipynb` - Parallel processing
- `parallelWorkFlow/withLLM.ipynb` - Multi-agent systems
- `persistence/10_persistence.ipynb` - State persistence & memory

## 🛠️ Core Patterns

### Sequential: `Input → Process → Output`
Linear workflows for data pipelines and content generation.

### Conditional: `Input → Evaluate → Branch A/B/C → Output`  
Smart routing based on conditions and AI decision-making.

### Iterative: `Input → Process → Evaluate → Improve ↺ → Output`
Feedback loops for optimization and quality improvement.

### Parallel: `Input → [Agent1, Agent2, Agent3] → Merge → Output`
High-throughput concurrent processing with multiple agents.

### Persistent: `Input → Process → Save State → Resume → Output`
Workflows with memory and state persistence across sessions.

## 🎯 Real-World Applications
- **Content Creation**: Blog posts, social media with AI feedback and iterative improvement
- **Data Analytics**: Sports statistics, business intelligence with parallel processing
- **Problem Solving**: Mathematical equations, decision support with conditional routing
- **Automation**: Multi-agent systems, workflow orchestration with state persistence
- **Conversational AI**: Chatbots and assistants with memory and context preservation

## 🔧 Key Technologies
- **LangGraph**: Workflow orchestration and state management
- **Google Gemini**: Advanced AI model integration
- **LangChain**: AI application framework and tools
- **Python**: Core programming language
- **Jupyter Notebooks**: Interactive development environment

## 🐛 Quick Troubleshooting
```bash
# API Key issues
cat .env  # Check: GOOGLE_API_KEY=your_actual_key
# Then restart Jupyter kernel

# Dependency issues  
myenv\Scripts\activate
pip install -r requirements.txt --upgrade

# Workflow errors - Check state structure matches TypedDict
```

## 📝 Quick Example
```python
# Iterative content creation with feedback loops
init_state = {
    'topic': "AI in healthcare",
    'iteration': 1, 
    'max_iterations': 3
}
result = workflow.invoke(init_state)
print(f"Generated content: {result['content']}")
print(f"Iterations completed: {result['iteration']}")
```

## 🔗 Resources
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [Google AI Studio](https://aistudio.google.com/app/apikey)
- [LangChain Documentation](https://python.langchain.com/)
- [Project Repository](https://github.com/anubrata-naskar/langGraph-learning)

**Get your Google API key → Setup environment → Start with `sequentialWorkFlow/withoutLLM.ipynb` → Happy Learning! 🎉**
