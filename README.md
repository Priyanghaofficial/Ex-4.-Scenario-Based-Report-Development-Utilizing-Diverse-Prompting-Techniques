# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
## Objective: 
The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim: 
To evaluate and demonstrate how diverse prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, and instruction-guided) enhance the effectiveness of AI-powered retail chatbots in handling customer queries.
## Algorithm:
1.Query Input – Customer submits a query.

2.Intent Detection – Classify query (order tracking, recommendation, complaint, FAQ).

3.Prompt Selection – Choose appropriate prompting technique.

4.Model Processing – Feed prompt + query into LLM.

5.Output Validation – Check accuracy, tone, clarity.

6.Response Delivery – Return validated response to customer.

7.Feedback Storage – Save logs for future refinement.
## Prompt:

Scenario 1: Order Tracking

Prompt (Zero-shot):
Where is my order 12345?
Result: Provides a quick factual update but sounds robotic, lacking empathy.

Prompt (Role-based):
You are a friendly assistant. Update the customer on their order.
Result: Gives polite, empathetic information that reassures the customer.

Scenario 2: Product Recommendation

Prompt (Few-shot):
Example 1:  
Q: I need a laptop for gaming.  
A: Acer Nitro 16GB RAM.  

Example 2:  
Q: I need shoes for running.  
A: Nike Air Zoom Pegasus.  
User Prompt:  
I want a phone for photography.
Result: Generates a relevant, personalized suggestion (Google Pixel 7 Pro).

Scenario 3: Complaint Resolution

Prompt (Chain-of-thought):
Step 1: Apologize.  
Step 2: Confirm issue.  
Step 3: Offer solution.  
Customer: My item arrived damaged.
Result: Produces a structured, empathetic response with clear solutions.

Scenario 4: FAQ Handling

Prompt (Instruction-guided):
Answer concisely in less than 30 words.  
Q: What is your return policy?
Result: Provides a short, precise, and policy-compliant answer.
## Output:
[exp4prompt.pdf](https://github.com/user-attachments/files/22126041/exp4prompt.pdf)

## Result:
A hybrid prompting strategy works best for retail chatbots. Zero-shot handles simple queries, few-shot improves personalization, chain-of-thought resolves complaints, role-based adds empathy, and instruction-guided ensures concise FAQs. Together, they make responses both accurate and customer-friendly, enhancing overall customer satisfaction.
