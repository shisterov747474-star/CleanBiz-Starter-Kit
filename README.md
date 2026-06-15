# CleanBiz-Starter-Kit
My name is Shisterov Nikita, I'm a 26-year-old warehouse worker from Saint Petersburg. I created CleanBiz Starter Kit because I want to start my own cleaning business myself, but I faced the problem that business consultants are expensive and there are almost no free ready-to-use tools for Russia.
Why my project is good:
Solves a real problem — many people want to start their own business but don't know how to calculate startup costs, set prices, or create legal documents. My project fills these gaps for free.
Practical value — this is not just theory. The project includes a working financial calculator in Python, ready-to-use contract and invoice templates, marketing content, and AI prompts. People can use them immediately.
Accessibility — the project is open-source, so anyone can freely copy, improve, and adapt it for other regions. This lowers the barrier to starting a business.
AI integration — I intentionally included AI tools and prompts because I want to show how modern technology can help small businesses. This makes the project relevant and modern.
Future growth — with access to ChatGPT Pro, Coder, and API credits, I can add more features: a web interface, mobile app, chatbot for answering questions, and automate document generation.
Why I'm presenting this project:
I do not have the financial means to purchase these products on my own. Access to OpenAI tools will help me develop the project faster, make it more useful, and ultimately help other people start their business without big costs.
This project is my chance to move from warehouse work to my own business and at the same time help others do the same.
# CleanBiz Starter Kit

<div align="center">
  <p><strong>Open-source toolkit for launching a cleaning business in Russia</strong></p>
</div>

## 📦 What is This?

Free toolkit to launch a cleaning business:
- ✅ Business plan template
- ✅ Financial calculator
- ✅ Legal documents (contracts, invoices)
- ✅ Marketing templates
- ✅ AI tools & prompts

## 🚀 Quick Start

1. Clone: `git clone https://github.com/yourusername/cleanbiz-starter-kit.git`
2. Install: `pip install -r requirements.txt`
3. Run: `python business_plan/financial_calculator.py`

## 📜 License

MIT License
business_plan/financial_calculator.py:
python
def calculate_startup_costs():
    equipment = 50000
    marketing = 20000
    legal = 10000
    return equipment + marketing + legal

if __name__ == "__main__":
    print("Startup Costs:", calculate_startup_costs(), "rubles")
requirements.txt:
text
jupyter>=1.0.0
numpy>=1.21.0
pandas>=1.3.0
