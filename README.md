# Ex.No.3-Explaing the following Prompt Engineering types with examples - Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting.

### DATE: 20-11-2026  
### NAME: Navaneeth S
### REGISTER NUMBER : 212225240097

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
Prompt: "If customer’s query is missing details (like order ID), ask a clarifying question first."
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
| Straightforward Prompting    | Gives direct instructions       | Simple and quick responses         | General descriptions      |
| Tabular Format Prompting     | Organizes information           | Easy comparison and readability    | Documentation and reports |
| Preceding Question Prompting | Builds context before answering | Detailed reasoning and explanation | Analytical tasks          |
| Missing Word Prompting       | Tests contextual understanding  | Improves comprehension             | Educational assessments   |

## Best Practices for Prompt Engineering

* Keep prompts **clear, concise, and unambiguous**.
* Use **structured formats (tables, templates)** where consistency is needed.
* Apply **preceding questions** for vague or incomplete queries.
* Provide **examples (few-shot)** to teach style/pattern.
* Always test prompts with **edge cases** (e.g., missing data, typos).

---
## Conclusion

Implementing diverse prompt engineering techniques empowers chatbots to deliver accurate, context-aware, and user-friendly interactions. Straightforward prompts ensure fast, reliable responses for routine queries, while tabular format prompts provide consistency and structure across multiple scenarios. Missing word (cloze) prompts enable precise personalization, and preceding question prompts enhance clarity by addressing incomplete inputs. Each approach has unique advantages, and strategically combining them maximizes efficiency, accuracy, and customer satisfaction. Thoughtful prompt design not only improves response quality but also fosters trust, scalability, and adaptability, positioning chatbots as effective, reliable, and intelligent tools in modern customer service ecosystems.

Key Takeaways:

1.Enhances accuracy, consistency, and personalization in responses.

2.Builds user trust by clarifying incomplete or ambiguous queries.

3.Supports scalability and adaptability in customer service operations.

## Result

By applying **Straightforward, Tabular, Missing Word, Preceding Question, and Few-Shot Prompting**, customer service chatbots can:

1) Deliver accurate answers.
2) Maintain a natural conversational flow.
3) Improve customer trust and satisfaction.

Each method has its **strengths and trade-offs**, and the right combination depends on the **type of query** and **business goals**.

---


