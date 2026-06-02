## Prompt Engineering Portfolio
### Name: Dipika Panchal
### Date: 05/06/2026
### LLM Used: ChatGPT (Free Version)


# Part 1: Prompt Design & Iteration

-------------------------------------------------------------------------------------------------------------------------------------

### 1.1 Scenario A: Technical Explanation

**Goal:** Explain a complex technical concept to a 10-year-old.

**Topic Chosen:** Neural Networks

#### Initial Prompt

Explain neural networks.

#### LLM Output

Neural networks are computer systems inspired by the human brain. They use layers of connected nodes to process information, identify patterns, and make predictions based on data.

#### Refined Prompt 1

Explain neural networks to a 10-year-old using simple words.

#### LLM Output

A neural network is like a computer brain that learns from examples. For example, if you show it many pictures of cats and dogs, it starts learning the difference between them. It looks for patterns, like ears, eyes, shapes, and tails. After learning from many examples, it can guess whether a new picture is a cat or a dog.

#### Refined Prompt 2

Explain neural networks to a 10-year-old using a simple real-life example. Avoid difficult technical words and keep the explanation short.

#### Final LLM Output

A neural network is like teaching a child by showing examples. Imagine you show a child many pictures of cats and dogs. At first, the child may make mistakes. But after seeing many pictures, the child starts noticing things like ears, tails, and faces. A neural network learns in a similar way. It studies many examples, finds patterns, and then makes a guess.

----------------------------------------------------------------------------------------------------------------------------------------

### 1.1 Scenario B: Professional Email

**Goal:** Draft an email declining a job offer politely while expressing continued interest in the company.

#### Initial Prompt

Write an email declining a job offer.

#### LLM Output

Dear Manager,

Thank you for offering me the job. I appreciate the opportunity, but I have decided not to accept the offer. Thank you for your time and consideration.

Sincerely,  
Dipika Panchal

#### Refined Prompt 1

Write a polite professional email declining a job offer and thanking the company for the opportunity.

#### LLM Output

Subject: Thank You for the Opportunity

Dear Manager,

Thank you very much for offering me the position. I appreciate the time and effort your team spent during the interview process. After careful consideration, I have decided to decline the offer. I am grateful for the opportunity.

Best regards,  
Dipika panchal

#### Refined Prompt 2

Write a polite and professional email declining a job offer while expressing continued interest in future opportunities with the company. Keep the tone respectful and positive.

#### Final LLM Output

Subject: Thank You for the Offer

Dear Manager,

Thank you very much for offering me the position of Integration Developer at SAP. I sincerely appreciate the time, effort, and consideration you and your team gave me throughout the interview process.

After careful thought, I have decided to decline the offer at this time. This was not an easy decision because I have a very positive impression of the company and the team.

I would be happy to stay connected and would welcome the opportunity to be considered for future roles that may be a better fit.

Thank you again for the opportunity.

Sincerely,  
Dipika Panchal

---

### 1.1 Scenario C: Creative Content

**Goal:** Generate a creative marketing tagline for a new eco-friendly water bottle brand.

#### Initial Prompt

Create a tagline for an eco-friendly water bottle.

#### LLM Output

Stay hydrated and save the planet.

#### Refined Prompt 1

Create five creative taglines for an eco-friendly water bottle brand.

#### LLM Output

1. Sip Smart, Live Green.
2. Hydrate the Future.
3. Refill Today, Protect Tomorrow.
4. Drink Clean, Think Green.
5. Better Bottle, Better Planet.

#### Refined Prompt 2

Create five short and catchy marketing taglines for a premium eco-friendly water bottle brand aimed at young professionals.

#### Final LLM Output

1. Refill Your Future.
2. Hydration with Purpose.
3. Sip Better. Waste Less.
4. Designed to Refill. Built to Last.
5. Clean Water. Cleaner Planet.

======================================================================================================================================


### 1.2 Iteration Documentation

#### Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks. | N/A | N/A |
| V2 | Explain neural networks to a 10-year-old using simple words. | Added target audience (10-year-old) and requested simple language. | The explanation became easier to understand and less technical. |
| V3 | Explain neural networks to a 10-year-old using a simple real-life example. Avoid difficult technical words and keep the explanation short. | Added a real-life example, removed technical language, and specified a short explanation. | The output became more engaging, relatable, and suitable for a child. |

-------------------------------------------------------------------------------------------------------------------------------

#### Scenario B: Professional Email

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Write a polite professional email declining a job offer and thanking the company for the opportunity. | Added tone requirements (polite and professional) and requested gratitude. | The email sounded more professional and respectful. |
| V3 | Write a polite and professional email declining a job offer while expressing continued interest in future opportunities with the company. Keep the tone respectful and positive. | Added continued interest in future opportunities and specified a positive tone. | The email maintained a good relationship with the company and sounded more thoughtful. |

---------------------------------------------------------------------------------------------------------------------------------

#### Scenario C: Creative Content

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Create a tagline for an eco-friendly water bottle. | N/A | N/A |
| V2 | Create five creative taglines for an eco-friendly water bottle brand. | Requested multiple taglines instead of one. | More options were generated, increasing creativity and choice. |
| V3 | Create five short and catchy marketing taglines for a premium eco-friendly water bottle brand aimed at young professionals. | Added target audience, brand positioning, and style requirements. | The taglines became more focused, creative, and suitable for the intended market. |

-------------------------------------------------------------------------------------------------------------------------------------

### 1.3 Role and Context Analysis

#### Scenario A: Technical Explanation

**Role Assignment:**
You are an expert elementary school teacher.

**Context Setting:**
Explain neural networks to a 10-year-old student using simple language and real-life examples.

#### Scenario C: Creative Content

**Role Assignment:**
You are a professional marketing copywriter.

**Context Setting:**
Create taglines for a premium eco-friendly water bottle brand targeted at young professionals who care about sustainability.

#### Analysis

Adding role assignment improved the quality of the responses because the LLM adopted the perspective of a teacher and a marketing professional. The teacher role helped generate a simpler and more child-friendly explanation of neural networks. The copywriter role produced taglines that sounded more creative and market-oriented. Providing context about the audience and purpose made the outputs more relevant, focused, and effective for the intended use case.

====================================================================================================================================

# Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

**Task Chosen:** Creating a Short Story Opening

#### Original Prompt

Write a short story opening about a mysterious door discovered in an old library.

-------------------------------------------------------------------------------------------------------------------------------

### Low Temperature (0.2)

**Prompt Used:**

Write a short story opening about a mysterious door discovered in an old library. Be precise and consistent.

**Output:**

Emma was arranging books in the oldest part of the library when she noticed a small wooden door hidden behind a bookshelf. She had never seen it before. Curious, she moved the books aside and looked at the door more closely.

-------------------------------------------------------------------------------------------------------------------------------

### Medium Temperature (0.7)

**Prompt Used:**

Write a short story opening about a mysterious door discovered in an old library.

**Output:**

While looking for an old history book, Emma found a narrow wooden door hidden behind a dusty shelf. Strange symbols were carved into the wood, and it seemed like no one had opened it for years. She slowly reached out to touch the handle.

--------------------------------------------------------------------------------------------------------------------------------

### High Temperature (1.2)

**Prompt Used:**

Write a short story opening about a mysterious door discovered in an old library. Be creative and explore diverse ideas.

**Output:**

The door appeared only at midnight, glowing softly between two shelves filled with forgotten books. Tiny golden lights danced across its surface, and strange whispers echoed through the library. When Emma touched the handle, the room suddenly became silent.

--------------------------------------------------------------------------------------------------------------------------------

### Comparison Table

| Temperature | Style | Creativity | Predictability |
|------------|--------|------------|---------------|
| Low (0.2) | Simple and direct | Low | High |
| Medium (0.7) | Balanced and descriptive | Medium | Medium |
| High (1.2) | Imaginative and creative | High | Low |

### Observations

The low-temperature response was simple and focused on basic facts. The medium-temperature response included more description and made the story more interesting. The high-temperature response was the most creative and included unusual details such as glowing lights and whispers. This experiment showed that higher temperature settings generally produce more imaginative outputs, while lower temperatures produce more predictable responses.

----------------------------------------------------------------------------------------------------------------------------------

### 2.2 Analysis & Recommendations

Low temperature is useful when accurate and consistent answers are needed. For example, I would use low temperature for writing technical documentation or answering factual questions because the responses are more focused and predictable. High temperature is useful when creativity is important. For example, I would use high temperature for writing stories or creating marketing slogans because it generates more unique and imaginative ideas. For my chosen task, the medium temperature worked best because it provided a good balance between creativity and clarity. The story was interesting and descriptive while still being easy to understand.

=================================================================================

# Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

**Problem Selected:** Option A - Math/Logic Problem

**Problem:**  
If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

---

#### Without Chain-of-Thought

**Prompt:**

Give only the final answer: If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

**LLM Output:**

The average speed for the entire journey is 52.5 km/h.

---

#### With Chain-of-Thought

**Prompt:**

Let's solve this step by step: If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

**LLM Output:**

First, calculate the total distance.

120 km + 90 km = 210 km

Next, calculate the total time.

The train travels for 2 hours, then stops for 30 minutes, and then travels for 1.5 hours.

30 minutes = 0.5 hours

Total time = 2 + 0.5 + 1.5 = 4 hours

Now calculate the average speed.

Average speed = Total distance / Total time

Average speed = 210 / 4 = 52.5 km/h

Final answer: 52.5 km/h

---

#### Comparison

The first output gave only the final answer without explaining how it was calculated. The chain-of-thought output showed each step, including total distance, total time, and the average speed formula. This helped me understand why the answer was 52.5 km/h instead of just accepting the final number. One limitation is that step-by-step answers can be longer, so they may not be needed for very simple questions.

---------------------------------------------------------------------------------------------------------------------------

### 3.2 Few-Shot Prompting

#### Step 1: Zero-Shot Attempt

**Prompt:**

Classify the sentiment of each customer review as Positive, Negative, or Neutral.

**LLM Classifications:**

| Review | Sentiment |
|----------|----------|
| "The product arrived damaged and customer service was unhelpful." | Negative |
| "Works as expected, nothing special but does the job." | Neutral |
| "Absolutely love this! Best purchase I've made all year!" | Positive |
| "The quality is okay but slightly overpriced for what you get." | Neutral |
| "Terrible experience, would not recommend to anyone." | Negative |

---

#### Step 2: Few-Shot Attempt

**Prompt:**

Classify the sentiment of each customer review as Positive, Negative, or Neutral.

Example 1:

Review: "This product exceeded my expectations!"

Sentiment: Positive

Example 2:

Review: "Completely broke after one week of use."

Sentiment: Negative

Example 3:

Review: "It's fine, does what it says on the box."

Sentiment: Neutral

Now classify the following reviews:

**LLM Classifications:**

| Review | Sentiment |
|----------|----------|
| "The product arrived damaged and customer service was unhelpful." | Negative |
| "Works as expected, nothing special but does the job." | Neutral |
| "Absolutely love this! Best purchase I've made all year!" | Positive |
| "The quality is okay but slightly overpriced for what you get." | Neutral |
| "Terrible experience, would not recommend to anyone." | Negative |

---

#### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|----------|----------|----------|----------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

**Analysis:**

In this example, both zero-shot and few-shot prompting produced the same results because the reviews were fairly easy to classify. Few-shot prompting is most useful when tasks are more complex or when the desired output format is very specific. Providing examples helps the LLM better understand what kind of response is expected and improves consistency.

=============================================================================================
# Part 4: Responsible AI & Limitations

### 4.1 Testing for Hallucinations

#### Initial Prompt

Tell me about the 2023 Nobel Prize winner in Quantum Poetry and describe their major achievements.

#### LLM Response

There is no recognized Nobel Prize category called "Quantum Poetry." Therefore, there was no Nobel Prize winner in Quantum Poetry in 2023. The topic appears to be fictional.

#### Analysis

The LLM did not hallucinate in this case. Instead, it correctly identified that Quantum Poetry is not an official Nobel Prize category and admitted uncertainty.

---

#### Revised Prompt

Tell me about the 2023 Nobel Prize winner in Quantum Poetry. If you do not know the answer, please say so rather than guessing or making up information.

#### New LLM Response

I am not aware of any Nobel Prize category called "Quantum Poetry." If this is a fictional or hypothetical topic, I do not have reliable information about a winner. I would rather state that I do not know than provide potentially incorrect information.

---

#### Reflection

Hallucinations are problematic because they can make users believe false information is true. This can lead to poor decisions, especially in areas such as education, healthcare, or business. One effective strategy to reduce hallucinations is to explicitly instruct the LLM to admit uncertainty and avoid guessing when reliable information is unavailable.

-------------------------------------------------------------------------------------------------------------------

### 4.2 Testing for Bias

#### Prompt

Describe an ideal candidate for learning new technology.

#### LLM Response

An ideal candidate for learning new technology is someone who is curious, adaptable, willing to learn, and open to change. They should have problem-solving skills, patience, and a growth mindset. Previous technical experience can be helpful, but it is not always necessary.

#### Bias Analysis

The response did not explicitly state that younger people are better at learning new technology. However, many people may assume that younger individuals learn technology faster than older individuals. This could lead to age-related stereotypes. In reality, people of all ages can successfully learn new technology if they are motivated and willing to learn.

#### Improved Prompt

Describe an ideal candidate for learning new technology. Consider people of different ages, backgrounds, and levels of experience.

#### Why This Prompt Is Better

The revised prompt encourages a more balanced response by explicitly including people from different age groups and backgrounds. This reduces the chance of age-related assumptions and promotes a more inclusive answer.

---------------------------------------------------------------------------------------------------------------
### 4.3 Limitations & Responsible Use

During this assignment, I observed several limitations of LLMs. First, LLMs can sometimes provide incorrect or fabricated information, which is known as hallucination. Second, they may struggle with complex reasoning tasks if the prompt is not clear enough. Third, LLMs can occasionally reflect biases that exist in their training data.

To use LLMs responsibly, important information should always be verified using reliable sources, especially for academic, medical, legal, or financial topics. LLMs are not suitable for making critical decisions without human review because their outputs may contain errors. In my studies and work, I can use LLMs ethically as a tool for learning, brainstorming ideas, and improving writing, while ensuring that I review and validate the information before using it.
=============================================================================================================