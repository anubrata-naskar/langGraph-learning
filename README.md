# 🚀 LangGraph Learning Project

Master AI workflows with hands-on examples covering all LangGraph patterns - Sequential, Conditional, Iterative, and Parallel processing using Google Gemini AI.

## 📖 Overview
Complete learning repository with 8 interactive Jupyter notebooks demonstrating real-world AI agent architectures, from basic workflows to advanced multi-agent systems.

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
├── requirements.txt        # Dependencies
└── .env                   # API configuration
```

## 🚀 Quick Setup (3 Minutes)
```bash
# 1. Clone and setup
git clone <repo-url> && cd langGraph-learning
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

## 🛠️ Core Patterns

### Sequential: `Input → Process → Output`
Linear workflows for data pipelines and content generation.

### Conditional: `Input → Evaluate → Branch A/B/C → Output`  
Smart routing based on conditions and AI decision-making.

### Iterative: `Input → Process → Evaluate → Improve ↺ → Output`
Feedback loops for optimization and quality improvement.

### Parallel: `Input → [Agent1, Agent2, Agent3] → Merge → Output`
High-throughput concurrent processing with multiple agents.

## 🎯 Real-World Applications
- **Content Creation**: Blog posts, social media with AI feedback
- **Data Analytics**: Sports statistics, business intelligence  
- **Problem Solving**: Mathematical equations, decision support
- **Automation**: Multi-agent systems, workflow orchestration

## 🔧 Key Technologies
- **LangGraph**: Workflow orchestration and state management
- **Google Gemini**: Advanced AI model integration
- **LangChain**: AI application framework
- **Python**: Core programming language

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
# Iterative content creation
init_state = {
    'topic': "AI in healthcare",
    'iteration': 1, 
    'max_iterations': 3
}
result = workflow.invoke(init_state)
print(result['content'])
```

## 🔗 Resources
- [LangGraph Docs](https://langchain-ai.github.io/langgraph/)
- [Google AI Studio](https://aistudio.google.com/app/apikey)
- [LangChain Docs](https://python.langchain.com/)

**Get your Google API key → Setup environment → Start with `sequentialWorkFlow/withoutLLM.ipynb` → Happy Learning! 🎉**
