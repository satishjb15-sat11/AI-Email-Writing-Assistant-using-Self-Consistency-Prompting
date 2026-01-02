# AI-Email-Writing-Assistant-using-Self-Consistency-Prompting
Prompt-engineered email writing assistant using self-consistency for reliable outputs.

## Professional Email Refinement with Self‑Consistency
Prompt‑engineered email assistant that uses the **Self‑Consistency** technique to generate clear, polite, and reliable business emails.

### Overview
This project shows how multiple AI generations can be compared to select the most consistent and professional email, instead of trusting a single output. This is especially useful for business communication, where tone, clarity, and structure matter a lot.

## Problem
Users often start with rough, informal messages like:  
“I have not received my order yet. What’s going on?”  

If this is sent as‑is, it can sound rude, emotional, or unprofessional. A single AI rewrite might help, but one generation can still:  
- Be too informal  
- Miss clarity  
- Sound robotic or poorly structured  

Goal:  
Turn rough messages into:  
- Clear  
- Polite  
- Professional  
business emails by generating multiple versions and picking the best one using Self‑Consistency.

## Prompt Engineering Technique: Self‑Consistency
Instead of using just one AI output, the same task is run multiple times with the **same base prompt** (and possibly small controlled variations). The responses are then compared to select the most:  
- Consistent  
- Clear  
- Professional  
This reduces randomness and increases reliability for important tasks like email writing.

## Base Prompt (for All Generations)
You are a professional business email writer.  
Rewrite the following message into a clear, polite, and professional business email.
 
 Constraints:  
- Keep the tone formal  
- Do not add new information  
- Keep it concise  
- Output only the email body  

Input idea (implicit): a short, informal message about not receiving an order.

## Multiple Generations (Self‑Consistency Sampling)

### Generation 1

Dear Support Team,  
I hope you are doing well. I am writing to inquire about my order, as I have not yet received it.  
Please let me know the current status.  
Kind regards,  
[Name]  

### Generation 2

Hello,    
I would like to follow up regarding my order, as I have not received any update so far.    
I would appreciate your assistance in checking its status.  
Best regards,
[Name]  

### Generation 3

Dear Support Team,    
I am writing to follow up on my recent order, as I have not yet received any information regarding its delivery.   
I look forward to your response.    
Sincerely,  
[Name]  

## Self‑Consistency Analysis

Common strengths across all three:  
- Professional tone  
- Clear intent  
- No extra information added  

Differences:  
- Generation 1**: Polite, but slightly more casual and less specific.  
- Generation 2**: Concise, but feels less structured and less formal at the start (“Hello”).  
- Generation 3**: Most balanced in tone, clarity, and structure; reads like a complete, formal email.

## Final Selected Email (After Self‑Consistency)

Dear Support Team,  
I am writing to follow up on my recent order, as I have not yet received any information regarding its delivery.    
I would appreciate an update at your earliest convenience.    
Sincerely,  
[Name]  

This final version is chosen because it best matches the project goal: clear, polite, formal, and well‑structured business communication.
