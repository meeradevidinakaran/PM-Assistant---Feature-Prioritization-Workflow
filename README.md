# PM-Assistant---Feature-Prioritization-Workflow
This is a simple multi agent workflow that is built to help Product Managers (PM) to prioritize products features that are requested by the customer, considering resource and time constraints.

# Problem Statement :
You are a Product Manager at a B2B SaaS company. Customers have requested 5 features, but you only have capacity to build 2 this quarter. 
Which 2 should you prioritize? 
The features: 
 • Dark Mode (200 requests, 2 weeks)
 • PDF Export (50 enterprise requests, 4 weeks)
 • Mobile App (500 requests, 12 weeks)
 • SSO Integration (30 requests, $150K deals blocked) 
 • Dashboard Redesign (100 requests, 4 weeks) 

Your constraints:
 • 2 engineers available
 • 10 weeks in the quarter
 • Must ship at least one customer-visible improvement

# Objective 
Build a multi agent LangFlow pipeline that helps a PM prioritize features for the next quarter. Your pipeline will demonstrate the core multi-agent pattern: specialized agents working together, each with ONE job. 

# Solution
We Will Use the below agents on langflow platform , each of them performing specific tasks using system prompts and Open AI LLM model.
1. Planner Agent - Breaks down the decision into tasks, identifies missing info, defines criteria. Does NOT recommend. 
2. Analyzer Agent - Makes a recommendation with tradeoffs, risks, and next steps. 
3. Critic Agent - Finds holes, challenges assumptions, gives a verdict( Approve / Revise/ Escalate )
4. Reviser Agent - Reviser fixes the memo using critique, provide Clearer mitigations + stronger next steps.

# System Design

# Scaling_Stragey

# Demo


