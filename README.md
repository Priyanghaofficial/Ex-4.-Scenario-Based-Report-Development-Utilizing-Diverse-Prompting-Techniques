


# Ex-4: Scenario-Based Report Development Utilizing Diverse Prompting Techniques  

**Objective:**  
The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Prompts using various AI prompting techniques guide the experiment, data collection, analysis, and report creation.  



## Aim  
To evaluate how diverse prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, and instruction-guided) enhance the effectiveness of AI-powered chatbots in handling retail customer queries such as order tracking, product recommendations, complaint resolution, and FAQs.  



## Algorithm  
1. Customer submits a query.  
2. Detect the intent (order tracking, product recommendation, complaint, or FAQ).  
3. Select the most suitable prompting technique.  
4. Generate response using the LLM.  
5. Validate output for accuracy, empathy, and structure.  
6. Deliver response to the customer.  
7. Log feedback for continuous improvement.  



## Scenario 1: Order Tracking  

**Prompt (Zero-shot):**  
```

Where is my order 12345?

```
**Output:**  
"Your order 12345 is out for delivery."  
**Result:** Factual but robotic, lacking empathy.  

**Prompt (Role-based):**  
```

You are a friendly assistant. Update the customer on their order.

```
**Output:**  
"Hello! I’ve checked your order 12345—it’s on the way and will reach you tomorrow. Thank you for shopping with us!"  
**Result:** Polite and empathetic, improving customer satisfaction.  

---

## Scenario 2: Product Recommendation  

**Prompt (Few-shot):**  
```

Example 1:
Q: I need a laptop for gaming.
A: Acer Nitro 16GB RAM.

Example 2:
Q: I need shoes for running.
A: Nike Air Zoom Pegasus.

User Prompt:
I want a phone for photography.

```
**Output:**  
"I suggest the Google Pixel 7 Pro, which has an advanced camera system."  
**Result:** Personalized and relevant suggestion.  

---

## Scenario 3: Complaint Resolution  

**Prompt (Chain-of-thought):**  
```

Step 1: Apologize.
Step 2: Confirm issue.
Step 3: Offer solution.

Customer: My item arrived damaged.

```
**Output:**  
"I’m very sorry your product was damaged. I have checked your order details. We can send a replacement within 3 days or issue a refund."  
**Result:** Structured, empathetic response with clear solutions.  

---

## Scenario 4: FAQ Handling  

**Prompt (Instruction-guided):**  
```

Answer concisely in less than 30 words.
Q: What is your return policy?

```
**Output:**  
"You can return items within 30 days if unused and in original packaging. Refunds are processed within 5 business days."  
**Result:** Concise, precise, and policy-compliant.  

---

## Overall Result  
A hybrid prompting strategy works best for retail chatbots.  
- Zero-shot handles simple queries.  
- Few-shot improves personalization.  
- Chain-of-thought resolves complaints.  
- Role-based adds empathy.  
- Instruction-guided ensures concise FAQs.  

Together, they make responses both accurate and customer-friendly, enhancing overall customer satisfaction.  


