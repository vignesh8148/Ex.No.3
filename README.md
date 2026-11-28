# Ex.No.3-Explaing the following Prompt Engineering types with examples - Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting.

### NAME: Vignesh K
### REGISTER NUMBER : 212225240183

# Aim: 
 To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. Using Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting techniques.


# Prompt Engineering Techniques for Chatbots

Prompt Engineering is the process of **crafting effective instructions** to guide an AI system toward producing accurate, helpful, and context-aware responses.

A **well-crafted prompt** can help a chatbot:

* Provide relevant answers to user queries.
* Maintain the desired tone (formal, friendly, empathetic).
* Handle different types of customer issues efficiently.
* Avoid misunderstandings by asking clarifying questions.

Different **prompting methods** can be applied depending on the complexity of the query and the detail required.

---

## Types of Prompt Engineering

### 1. Straightforward Prompts

**Definition:**
Straightforward prompting is a technique of giving a simple and direct instruction to AI to get the desired answer.

**Key Features:**

 1.Simple and clear instructions.
 2.Direct questions.
 3.Easy to understand.
 4.No examples are required.
 5.Gives quick answers.

**Use Cases:**

 1.Asking simple questions.
 2.Getting definitions.
 3.Translating languages.
 4.Summarizing text.
 5.Solving basic problems.

**Example:**

```plaintext
"Explain Artificial Intelligence in simple words."
```

**Conversation:**

* Customer: *"What’s the status of order #1456?"*
* Chatbot: *"Your order is currently being processed and will be delivered by September 15, 2025."*

**Advantages:** Fast and reliable for structured queries.
**Limitations:** Lacks flexibility, may fail for vague queries.

---

### 2. Tabular Format Prompting

**Definition:**
Tabular Format Prompting is a technique of asking AI to present information in a table with rows and columns.

**Key Features:**

 1.Presents information in table format.
 2.Easy to read and understand.
 3.Organizes data clearly.
 4.Allows easy comparison.
 5.Saves time.

**Use Cases:**

 1.Displaying student marks.
 2.Organizing data.
 3.Showing advantages and disadvantages.
 4.Creating schedules.

**Example Prompt:**

``
Compare Python and C programming languages in a table with features and differences.
``

**Conversation:**

* Customer: *"My package hasn’t arrived yet."*
* Chatbot: *"I understand your concern. Your order is still in transit and is expected to arrive by September 14, 2025. Tracking number: TR123456."*

**Advantages:** Easy scalability & consistency.
**Limitations:** May feel robotic if overused.

---

### 3. Missing Word Prompting (Cloze Prompting)

**Definition:**

Missing Word Prompting is a technique of asking AI to fill in the missing words in a sentence or paragraph.

**Key Features:**

1. Template-driven replies.
2. Guarantees inclusion of required fields (name, ID, date).
3. Reduces formatting errors.

**Use Cases:**

1. Personalized responses.
2. Order updates with placeholders.
3. FAQs with uniform style.

**Example Prompt:**

```plaintext
Missing Word Prompting is a technique of asking AI to fill in the missing words in a sentence or paragraph.
```

**Conversation:**

* Customer: *"Hi, I’m Arjun. My order 5678 hasn’t been delivered yet."*
* Chatbot: *"Hello Arjun, your order 5678 is currently delayed in transit. Expected delivery: September 16, 2025."*

**Advantages:** Highly structured & accurate.
**Limitations:** Rigid, may not handle free-flow conversations well.

---

### 4. Preceding Question Prompting

**Definition:**
The AI **first asks clarifying questions** when the query lacks details.

**Key Features:**

* Adds a confirmation step.
* Improves accuracy & trust.
* Reduces wrong replies.

**Use Cases:**

* Refund requests without order ID.
* Troubleshooting without device details.
* Subscription/account issues.

**Example:**

```plaintext
Prompt: "What is Artificial Intelligence? Before answering, ask me what I already know about AI. Then explain it in simple words based on my answer."
```

**Conversation:**

* Customer: *"I need a refund."*
* Chatbot: *"I can help with that! Could you please share your order number so I can check the refund details?"*

**Advantages:** Prevents errors, builds trust.
**Limitations:** Adds extra steps (slightly longer conversation).

---

# Comparison of Prompt Engineering Techniques

| Prompt Type                  | Purpose                         | Strengths                          | Best Use Case             |
| ---------------------------- | ------------------------------- | ---------------------------------- | ------------------------- |
| Straightforward Prompting    | Gives direct instructions       | Quick and simple answers           | General questions         |
| Tabular Format Prompting     | Arranges information in tables  | Clear and organized output         | Reports and comparisons   |
| Preceding Question Prompting |Asks a question before answering |Improves clarity and context        | Detailed explanations     |
| Missing Word Prompting       | Tests contextual understanding  | Improves comprehension             | Educational assessments   |

## Best Practices for Prompt Engineering

 1.Be Clear: Use simple and understandable words.
 2.Be Specific: Clearly mention what you want.
 3.Give Context: Provide necessary background information.
 4.Set a Role: Tell AI what role it should perform.
 5.Specify Output Format: Mention whether you need a paragraph, list, or table.
 6.Use Examples: Give examples to guide the AI.
 7.Avoid Ambiguity: Use clear instructions without confusion.
 8.Review and Improve: Modify prompts to get better results.
---
## Conclusion

Different prompt engineering techniques help chatbots give accurate and useful responses. Straightforward prompts provide quick answers, while tabular prompts organize information clearly. Missing word prompts help personalize responses, and preceding question prompts improve clarity. Each technique has its own benefits. Using these techniques together improves accuracy, saves time, and increases customer satisfaction. Good prompt design also makes chatbots more reliable, helpful, and user-friendly.

Key Takeaways:

 1.Improves accuracy, consistency, and personalization in responses.
 2.Builds user trust by making unclear questions easier to understand.
 3.Helps chatbots handle different customer needs effectively.
 
## Result

Using Straightforward, Tabular, Missing Word, Preceding Question, and Few-Shot Prompting helps customer service chatbots to:
1. Give accurate answers.
2. Provide smooth conversations.
3. Improve customer trust and satisfaction.
Each method has its **strengths and trade-offs**, and the right combination depends on the **type of query** and **business goals**.

---


