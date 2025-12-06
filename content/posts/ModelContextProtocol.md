+++
date = '2025-12-06T16:21:02+05:30'
draft = false
title = 'Model Context Protocol: From Function Calling to Agentic AI'
+++
## Introduction
When large language models (LLMs) first emerged, they revolutionized text generation but lacked true instruction-following capabilities.   
Early LLMs often responded based on statistical likelihood rather than following clear commands.

For example:  
**User**: "Write an email stating that I will be on leave today."  
**LLM Response**: "And then send it to my manager."

To improve this, researchers introduced **Supervised Fine Tuning (SFT)** and **Reinforcement Learning from Human Feedback (RLHF)**:  
- **SFT** trains models with explicit instruction-following data to improve response accuracy.  
- **RLHF** fine-tunes models based on human preferences for better relevance and coherence.  

These methods enabled models to generate appropriate responses like:

**Subject**: Leave Notification  
**Body**: Dear [Manager's Name], I will be on leave today. Please let me know if you need any further details. Best regards, [Your Name]  

## Challenges in AI Model Integration with External Data and Tools

As LLMs advanced, users expected them to handle factual, real-time queries such as:  
1. "What is the square root of 14.52321?"
2. "What is the current GDP of India?"

These proved difficult because:  
- LLMs are not calculators and can't perform computations natively.
- They rely on pretrained data without real-time access to external sources like economic updates or stock prices.

## Introduction to Function Calling

To overcome these limits, developers added **function-calling capabilities**, allowing models to invoke external tools or APIs for updated information or specific tasks.  

Example:  
**User**: "What is the current GDP of India?"  
**LLM (with function calling)**: Fetches real-time data and replies, "As of 2025, India's estimated GDP is $3.7 trillion."

This enabled accurate, up-to-date, and computationally precise answers.  

Users soon demanded more **action-oriented** features, like:  
- Sending emails automatically
- Messaging on platforms like Telegram
- Booking flights

## Rise of Agentic AI

This drive for AI that can **act** led to the rise of **Agentic AI**, where models interface with various apps and APIs to execute commands.  

Capabilities expanded to:
- Scheduling meetings via calendar access
- Sending messages on Telegram
- Conducting online transactions

Initially, integrations targeted one application at a time, such as Gmail for email or Slack for messaging. But this approach faced major challenges:  
- **Diverse technology stacks**: Apps use different languages and frameworks (JavaScript, Java, Python, Go), needing unique integration methods.
- **Inconsistent API structures**: Each app defines its own formats and limits, complicating standardization.
- **Authentication complexity**: Varied protocols like OAuth, API keys, or tokens require handling multiple security methods.
- **Scalability issues**: Manually integrating thousands of apps is inefficient and hard to maintain.

This landscape set the stage for a unified standard like the Model Context Protocol to streamline AI integrations.  

## Birth of Model Context Protocol(MCP)

Model Context Protocol (MCP) delivers a unified standard that lets AI models connect seamlessly to any application, regardless of its technology stack.  
You no longer need custom, hand-coded integrations for each service.  

Instead, define one standardized communication method. MCP enables:
- A single protocol linking LLMs to databases, web services, and apps
- Dynamic tool invocation based on context, without hardcoded logic
- Easy extension of AI capabilities across diverse ecosystems

## MCP Use Cases

Picture this: You say, "Schedule a Zoom meeting with my team tomorrow at 10 AM."  

Here's what happens with MCP:
1. The AI recognizes your request.
2. It calls a standardized MCP-compliant scheduling function.
3. That function reaches Zoom's API.
4. You get back: "Your Zoom meeting is set for tomorrow at 10 AM. Here's the link: [meeting_link]."

## Conclusion

MCP turns AI from passive responders into active agents that execute real tasks across any system.  
This enables a truly intelligent and autonomous AI ecosystem where models are not just passive responders but active agents capable of executing tasks across multiple domains.  
The journey from basic LLMs to MCP is important to understand why MCP is important, and why we need to know it. 


