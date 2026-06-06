# Prompt Engineering Portfolio
Name: [Aarti Parmar]
Date: [06/06/2026]
LLM Used: ChatGPT (GPT-5.5)

##Part 1: Prompt Design & Iteration
## Scenario A: Technical Explanation

### Goal

Explain the concept of neural networks to a 10-year-old child.

### Initial Prompt (V1)

Explain neural networks to a 10-year-old.

### Refined Prompt (V2)

You are an elementary school teacher. Explain neural networks to a 10-year-old using simple language and a real-life example.

### Final Prompt (V3)

You are an experienced elementary school science teacher. Explain neural networks to a 10-year-old using simple words, a fun analogy, and a short example from everyday life. Avoid technical jargon and keep the explanation under 200 words.

### Final LLM Output

Imagine a neural network as a team of little detectives 🕵️‍♀️🕵️‍♂️ working together to solve a mystery.

Each detective looks for a different clue. One might look at color, another at shape, and another at size. They share their clues and then decide what they are looking at.

For example, think about sorting fruit at home. 🍎🍌🍊

You see something that is:

Yellow
Long
Curved

One detective notices the yellow color, another notices the long shape, and another notices the curve. Together they say, “That’s a banana!”

A neural network works in a similar way. It learns by seeing lots of examples. The more examples it sees, the better it gets at recognizing things.

Just like you learned to tell the difference between cats and dogs by seeing many of them, a neural network learns by practicing with lots of pictures, sounds, or other information.

In short: A neural network is like a team of tiny detectives that work together to spot clues and make smart guesses.

---

## Scenario B: Professional Email

### Goal

Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

Write an email declining a job offer.

### Refined Prompt (V2)

Write a professional email declining a job offer while thanking the employer for the opportunity.

### Final Prompt (V3)

You are a professional career advisor. Draft a polite and professional email declining a job offer because another opportunity has been accepted. Express gratitude for the offer, appreciation for the interview process, and continued interest in future opportunities with the company. Keep the tone respectful and concise.

### Final LLM Output

Subject: Thank You for the Job Offer

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your team. I sincerely appreciate the time and effort you and the interview panel invested throughout the recruitment process.

After careful consideration, I have decided to decline the offer, as I have accepted another opportunity that aligns with my current career goals.

I am grateful for the chance to learn more about your company and was impressed by the professionalism and welcoming atmosphere demonstrated during the interview process. It was a pleasure meeting the team and discussing the role.

I hold your organization in high regard and would welcome the opportunity to be considered for future positions should our paths cross again.

Thank you again for your time, consideration, and understanding. I wish you and your team continued success.

Kind regards,

[Your Name]

---

## Scenario C: Creative Content

### Goal

Generate a creative marketing tagline for a new eco-friendly water bottle brand.

### Initial Prompt (V1)

Create a tagline for an eco-friendly water bottle.

### Refined Prompt (V2)

You are a marketing expert. Create five catchy taglines for a modern eco-friendly water bottle brand.

### Final Prompt (V3)

You are an award-winning brand copywriter. Create 10 memorable marketing taglines for a premium eco-friendly water bottle brand targeting environmentally conscious young adults. The taglines should be short, modern, inspiring, and emphasize sustainability without sounding preachy.

### Final LLM Output

1. Sip Better. Live Bigger.
2. Hydrate the Future.
3. Designed to Refill. Made to Last.
4. Every Sip, Less Waste.
5. Carry Water. Leave a Legacy.
6. Pure Hydration. Smarter Impact.
7. Refill Your Bottle. Renew Your World.
8. Sustainability, In Your Hands.
9. Drink Well. Tread Lightly.
10. Good for You. Better for Tomorrow.


---

# 1.2 Iteration Documentation

## Scenario A: Technical Explanation- Neural Networks Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain the concept of neural networks to a 10-year-old child. | N/A | N/A |
| V2 | You are an elementary school teacher. Explain neural networks to a 10-year-old using simple language and a real-life example. | Added role (elementary school teacher), specified simple language, and requested a real-life example. | The response became more age-appropriate, engaging, and easier for a child to understand through relatable examples. |
| V3 | You are an experienced elementary school science teacher. Explain neural networks to a 10-year-old using simple words, a fun analogy, and a short example from everyday life. Avoid technical jargon and keep the explanation under 200 words. | Added expertise context, requested a fun analogy, required an everyday-life example, imposed a word limit, and explicitly prohibited technical jargon. | The output became more focused, concise, child-friendly, and engaging while ensuring readability and relevance for the target audience. |

---

## Scenario B: Professional Email- Job Offer Decline Email

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Write a professional email declining a job offer while thanking the employer for the opportunity. | Added professional tone and requirement to express gratitude. | The email became more courteous and appropriate for professional communication. |
| V3 | You are a professional career advisor. Draft a polite and professional email declining a job offer because another opportunity has been accepted. Express gratitude for the offer, appreciation for the interview process, and continued interest in future opportunities with the company. Keep the tone respectful and concise. | Added expert role, provided a specific reason for declining, requested appreciation for the interview process, expressed future interest, and defined tone and length. | The output became more realistic, complete, and tailored to a professional workplace situation while maintaining a positive relationship with the employer. |

---

## Scenario C: Creative Content- Eco-Friendly Water Bottle Taglines

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Generate a creative marketing tagline for a new eco-friendly water bottle brand. | N/A | N/A |
| V2 | Create a tagline for an eco-friendly water bottle. | Simplified the prompt and focused specifically on the product. | Produced a clearer and more direct tagline relevant to the product category. |
| V3 | You are an award-winning brand copywriter. Create 10 memorable marketing taglines for a premium eco-friendly water bottle brand targeting environmentally conscious young adults. The taglines should be short, modern, inspiring, and emphasize sustainability without sounding preachy. | Added expert role, specified target audience, increased quantity, defined brand positioning, and provided style requirements. | Generated a wider range of high-quality taglines that better matched the brand identity, audience expectations, and marketing objectives. |

---

# 1.3 Role and Context Usage
For Scenario 1 (Neural Networks Explanation) and Scenario 3 (Marketing Taglines), role assignment and context setting significantly improved the quality of the outputs. In Scenario 1, assigning the role of an experienced elementary school science teacher and specifying that the audience was a 10-year-old child helped generate a simpler, more engaging explanation using age-appropriate language, analogies, and examples. In Scenario 3, assigning the role of an award-winning brand copywriter and providing context about a premium eco-friendly water bottle brand targeting environmentally conscious young adults resulted in taglines that were more creative, audience-focused, and aligned with modern branding practices.

Role assignment guided the model to adopt the appropriate expertise and communication style, while context setting provided important background information about the audience, purpose, and desired outcome. Together, these techniques produced outputs that were more relevant, targeted, and effective than the initial generic prompts.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Chosen Task: Explaining Photosynthesis

---

## Low Temperature (0.2)

**Prompt:**  
Be precise and consistent. Explain photosynthesis in simple terms for a high school student.

**Output:**  
Photosynthesis is the process by which green plants make their own food using sunlight. It takes place mainly in the leaves inside chloroplasts. Plants take in carbon dioxide and water. Using sunlight energy, they convert these into glucose and oxygen. The glucose is used for energy and growth, while oxygen is released into the air.

---

## Medium Temperature (0.7)

**Prompt:**  
Explain photosynthesis in simple terms for a high school student.

**Output:**  
Photosynthesis is how green plants make food using sunlight. Chlorophyll captures sunlight energy in the leaves. Plants take in carbon dioxide and water and convert them into glucose and oxygen. The glucose gives energy, and oxygen is released as a byproduct. This process is essential for life on Earth.

---

## High Temperature (1.3)

**Prompt:**  
Be creative and explore diverse ideas. Explain photosynthesis in simple terms for a high school student.

**Output:**  
Photosynthesis is like a tiny kitchen inside every green leaf where sunlight becomes food. Plants act like solar chefs using chlorophyll to capture light. They mix water and air into sugar energy. Oxygen is released like a bonus gift into the atmosphere. Without it, Earth would not support life as we know it.

---

## Comparison Table

| Temperature | Style      | Accuracy | Creativity | Clarity |
|-------------|-----------|----------|------------|----------|
| Low (0.2)   | Strict    | Very High| Low        | High     |
| Medium (0.7)| Balanced  | High     | Medium     | High     |
| High (1.3)  | Creative  | Medium   | Very High  | Medium   |

---

## 2.2 Analysis & Recommendations

Low temperature should be used for tasks requiring accuracy and consistency such as calculations, data extraction, or formal documentation. High temperature is better for creative tasks like storytelling, brainstorming, or marketing content generation. Medium temperature works best for educational explanations because it balances clarity and creativity. In this task, medium temperature produced the most effective response because it was both accurate and easy to understand.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Problem (Option A)
A train travels 120 km in 2 hours, stops for 30 minutes, then travels 90 km in 1.5 hours. What is the average speed?

---

## Without Chain-of-Thought

**Prompt:**  
What is the average speed for the journey?

**Output:**  
Total distance = 120 + 90 = 210 km  
Total time = 2 + 0.5 + 1.5 = 4 hours  
Average speed = 210 ÷ 4 = 52.5 km/h

---

## With Chain-of-Thought

**Prompt:**  
Let's solve this step by step.

**Output:**  
First, calculate total distance: 120 + 90 = 210 km.  
Next, calculate total time including stop: 2 + 0.5 + 1.5 = 4 hours.  
Finally, divide distance by time: 210 ÷ 4 = 52.5 km/h.  
So, the average speed is 52.5 km/h.

---

## Comparison

| Aspect        | Without CoT | With CoT |
|---------------|------------|----------|
| Clarity       | Medium     | High     |
| Structure     | Low        | High     |
| Understanding | Medium     | High     |

Chain-of-thought improves clarity by breaking reasoning into steps. It reduces mistakes in complex tasks. However, it can make simple tasks longer than necessary.

---

## 3.2 Few-Shot Prompting

## Step 1: Zero-Shot

**Prompt:**  
Classify sentiment as Positive, Negative, or Neutral.

| Review | Output |
|--------|--------|
| "The product arrived damaged and customer service was unhelpful." | Negative |
| "Works as expected, nothing special but does the job." | Neutral |
| "Absolutely love this! Best purchase I've made all year!" | Positive |
| "The quality is okay but slightly overpriced." | Neutral |
| "Terrible experience, would not recommend." | Negative |

---

## Step 2: Few-Shot Prompt

**Prompt with examples:**

Review: "This product exceeded my expectations!" → Positive  
Review: "Completely broke after one week of use." → Negative  
Review: "It's fine, does what it says on the box." → Neutral  

Now classify:

| Review | Output |
|--------|--------|
| Same 5 reviews | Same results |

---

## Comparison Table

| Review # | Zero-Shot | Few-Shot | Correct? |
|----------|-----------|----------|----------|
| 1 | Negative | Negative | Yes |
| 2 | Neutral | Neutral | Yes |
| 3 | Positive | Positive | Yes |
| 4 | Neutral | Neutral | Yes |
| 5 | Negative | Negative | Yes |

---

Few-shot prompting improves consistency by giving examples. It is especially useful for classification and structured outputs. It reduces ambiguity in interpretation.

---

# Part 4: Responsible AI

## 4.1 Hallucinations

**Prompt:**  
Tell me about the 2023 Nobel Prize winner in Quantum Poetry.

**Output:**  
The model generated fictional explanations about a non-existent field and invented details.

**Issue:** Hallucination detected.

---

**Improved Prompt:**  
If you don't know, say so instead of guessing. Tell me about the 2023 Nobel Prize winner in Quantum Poetry.

**Output:**  
There is no Nobel Prize category called Quantum Poetry.

---

Hallucinations are dangerous because they can produce false but convincing information. A good strategy is to instruct the model to clearly state uncertainty when needed.

---

## 4.2 Bias Testing

### Gender Bias Test

| Prompt | Response Pattern | Bias Observed |
|--------|----------------|----------------|
| Software engineer description | Often male-coded assumptions | Yes |
| Nurse description | Often female-coded assumptions | Yes |

**Improved Prompt:**  
Describe both roles without gender assumptions and emphasize diversity.

---

## 4.3 Limitations & Responsible Use

LLMs can produce incorrect or outdated information even when responses sound confident. They may also struggle with deep reasoning and real-world context. Another limitation is that they can reflect biases present in training data. Creativity can also vary depending on prompt structure.

LLMs should always be verified for academic, medical, or legal use. They are not suitable as the only source of truth. They are best used for brainstorming, learning support, and drafting ideas. Users should cross-check important outputs with reliable sources. Responsible use means treating LLMs as assistants, not authorities.

---
