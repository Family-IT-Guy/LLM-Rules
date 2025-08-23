# LLM Rules Overview

This directory contains platform-specific rule sets designed to transform your AI assistant's behavior and capabilities.

## Available Rule Sets

### [Claude Desktop Rules](claude-desktop.md)
**Best for:** General analysis, problem-solving, and technical work

**Key Features:**
- First-principles thinking methodology
- Assumption validation requirements  
- Evidence-based reasoning
- Problem-first approach
- Structured analysis protocols

**Use cases:** Software development, technical analysis, research, complex problem-solving

---

### [Claude Desktop with MCP Rules](claude-desktop-mcp.md)
**Best for:** Advanced analysis requiring external tools and real-time data

**Key Features:**
- All standard Claude Desktop features
- Automatic sequential thinking tool usage
- Enhanced research protocols with web search
- Integration with MCP server capabilities

**Use cases:** Research with current data, complex technical analysis, multi-step reasoning problems

---

### [ChatGPT Web Rules](chatgpt-web.md)  
**Best for:** Consulting-style conversations and business ideation

**Key Features:**
- Consultant and thinking partner approach
- Core principle validation
- Matter-of-fact communication style
- Assumption prevention protocols

**Use cases:** Business consulting, strategic planning, ideation sessions, advisory conversations

## How Rules Transform AI Behavior

### Before Rules Applied
- Accepts user ideas without validation
- Provides generic, often enthusiastic responses
- Makes assumptions about user intent
- Focuses on providing answers quickly
- May suggest solutions without understanding problems

### After Rules Applied  
- Validates all assumptions with evidence
- Asks clarifying questions before proceeding
- Challenges weak reasoning and false assumptions
- Applies systematic, first-principles analysis
- Requires problem confirmation before suggesting solutions
- Provides rationale for all recommendations

## Choosing the Right Rule Set

| Situation | Recommended Rules |
|-----------|------------------|
| Technical problem-solving | Claude Desktop |
| Need current/external data | Claude Desktop + MCP |
| Business strategy/consulting | ChatGPT Web |
| Complex multi-step analysis | Claude Desktop + MCP |
| Quick ideation sessions | ChatGPT Web |
| Research requiring web search | Claude Desktop + MCP |

## Installation

See the main [README.md](../README.md) for detailed installation instructions for each platform.

## Customization

Feel free to modify these rules to fit your specific needs:

- **Add domain-specific requirements** (e.g., medical, legal, financial)
- **Adjust response length preferences** 
- **Include specific methodologies** (e.g., SWOT analysis, design thinking)
- **Add industry-specific terminology** and frameworks

## Tips for Best Results

1. **Be specific in your questions** - Rules encourage the AI to ask for clarification
2. **Provide context upfront** - Include relevant background information  
3. **Expect more back-and-forth** - AI will validate assumptions before proceeding
4. **Document your conversations** - Structured approaches produce reusable insights
5. **Combine with frameworks** - Use rules with structured frameworks like our [Thinking Partner](../frameworks/thinking-partner-consultant.md)