## Prompt Engineering Portfolio
### Name: Dipika Panchal
### Date: 05/06/2026
### LLM Used: ChatGPT


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

-------------------------------------------------------------------------------------------------------------------------------------

# Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

**Task Chosen:** Creating a Short Story Opening

#### Original Prompt

Write a short story opening about a mysterious door discovered in an old library.

---

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