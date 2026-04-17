# Intro to Artificial Intelligence

Artificial Intelligence (AI) refers to computer systems that can perform tasks typically requiring human intelligence. Think of AI as software that can learn patterns from examples and make decisions or predictions based on what it has learned.

There are two main categories of AI that you'll encounter:

### Analytical AI
**Analytical AI** examines data to find patterns, make predictions, and extract insights. It can complete tedious tasks automatically and consistently, which is especially useful for participatory science projects where you may have thousands of photos.

*Examples:* Identifying species in photos, predicting weather patterns, detecting diseases in medical images

### Generative AI
**Generative AI** creates new content (text, images, etc.). You've likely seen a lot of examples from ChatGPT, but this type of AI is also present in caption generation, sentiment analysis, and more.

**This lesson focuses on Analytical AI and its applications in participatory science.**

---

## Understanding the World Through Data

Analytical AI is particularly valuable for participatory science (also called citizen science) because it helps volunteers and researchers process and understand large amounts of data collected from the real world.

### 1. Classification: Sorting Things into Categories

Classification looks at something and decides which category it belongs to.

The AI learns from thousands of labeled examples. If you show it 10,000 photos of birds with their species names, it learns to recognize the features that distinguish a cardinal from a blue jay.

**Applications:**
- Upload a photo of a bird, plant, or insect, and the AI identifies what species it is
- Classify water samples as "safe" or "needs attention" based on color and clarity
- Identify whether a galaxy in a telescope image is spiral, elliptical, or irregular
- Identify frog species by their calls or detect whale songs in ocean recordings

---

### 2. Regression: Predicting Continuous Values

Regression predicts a number or measurement rather than a category. The AI learns relationships between different measurements. If you show it historical data about temperature, humidity, and sunlight alongside plant growth measurements, it learns to predict how much a plant will grow under specific conditions.

**Applications:**
- Predict pollution levels (e.g., "PM2.5 concentration: 45 μg/m³") from sensor readings
- Estimate the number of animals in a habitat based on partial observations
- Predict when plants will bloom based on temperature and rainfall data collected by volunteers
- Assign numerical health scores to coral reefs based on photographs

---

### 3. Segmentation: Outlining and Separating

Segmentation draws precise boundaries around objects or regions of interest in images. The AI learns to recognize where each object begins and ends, pixel by pixel.

**Applications:**
- Automatically outline different land types (forest, wetland, urban) in satellite images
- Trace the boundaries of different coral types and algae coverage in underwater photos
- Outline and measure the extent of plastic debris in ocean cleanup efforts
- Calculate the exact area of tree coverage in urban neighborhoods

---

### 4. Object Detection: Finding and Locating

Object detection finds all instances of specific objects in an image and draws boxes around them. The AI recognizes what objects are present and where they're located, often handling multiple objects of different types in the same image.

**Applications:**
- Automatically detect and count animals in thousands of camera trap photos
- Find and track bird nests in trail camera footage
- Detect and count tiny plastic particles in water samples photographed under magnification
- Count and locate different bee species visiting flowers in time-lapse videos

---

### 5. Vision-Language Models: Connecting Images and Words

Vision-language AI understands both images and text, allowing it to answer questions about photos, generate descriptions, or search for images using natural language. These models learn the relationships between visual features and language, so they can "understand" what's happening in an image and communicate about it in words.

**Applications:**
- Find specific observations by describing them ("Show me all photos with purple flowers near water")
- Automatically generate detailed descriptions of field observations
- Identify and describe the same animal across multiple photos
- Evaluate whether observations meet research requirements ("Is this photo clear enough to identify the species?")

---

## Responsible AI

It's important to remember that **analytical AI works best when partnered with humans**. In participatory science:

- **Humans collect** diverse, real-world data from locations and conditions AI couldn't access
- **AI processes** large volumes of data quickly to find patterns
- **Humans verify** AI results, catch errors, and handle unusual or ambiguous cases
- **AI learns** from human corrections, continuously improving

This partnership allows participatory scientists to contribute to research at scales previously impossible, from tracking global bird migrations to monitoring ocean health to mapping biodiversity.

---

## Getting Started

Many participatory science projects now incorporate analytical AI. Look for projects on platforms like:
- [iNaturalist](https://www.inaturalist.org/)
- [SciStarter](https://scistarter.org/)
- [CitSci.org](https://citsci.org/)

Your observations and classifications help train and improve these AI systems while contributing to important research!