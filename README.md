# Nature and Cognition Field Journal Project

## Introduction

Welcome to the collaborative field journal project for the course module **"The Cognitive Benefits of Direct Nature Observation."** This repository serves as the central hub for a semester-long project where students document their nature observations and reflect on the cognitive and emotional effects of these experiences.

### Project Goals
- Encourage direct, mindful engagement with natural environments
- Document changes in flora, fauna, and seasonal patterns (phenology)
- Connect sensory experiences with personal well-being and cognitive science
- Foster collaboration and peer feedback through a modern, version-controlled platform

By moving beyond traditional paper journals, we leverage GitHub's capabilities for structured data entry, transparent review, and collaborative knowledge building.

---

## How to Contribute

### 1. Set Up Your Local Environment
- Fork this repository to your own GitHub account
- Clone the forked repository to your local machine
- Ensure you have Git installed and a text editor of your choice

### 2. Branching Strategy
**Always create a new branch for each journal entry.**  
Branch names should follow the pattern:  
`entry-<your_username>-<short_description>-<date>`  
Example: `entry-jdoe-soundscape-2023-10-27`

Create a branch from `main`:
```bash
git checkout -b entry-yourusername-description-date
```

### 3. Creating a Journal Entry
- Navigate to the `entries/` directory (create it if it doesn't exist)
- Create a new markdown file named according to the convention:  
  `entries/<your_username>_<theme>_YYYY-MM-DD.md`
- Use the **Journal Entry Template** below to structure your content

### 4. Submitting Your Work
1. Commit your changes with a descriptive message:
   ```bash
   git add entries/yourfile.md
   git commit -m "Add soundscape observation for October 27"
   ```
2. Push your branch to your fork:
   ```bash
   git push origin your-branch-name
   ```
3. Open a **Pull Request (PR)** from your branch to the `main` branch of this repository.
4. In the PR description, include:
   - A brief summary of your observation
   - The issue number this entry addresses (e.g., `closes #2`)
   - Any questions or notes for reviewers

### 5. Peer Review Process
- Each PR will be reviewed by at least one peer and the instructor
- Reviewers will provide constructive feedback via inline comments
- Once approved, the PR will be merged using a **squash merge** to keep history clean

---

## Journal Entry Template

Copy the following template into your markdown file and fill in each section.

```markdown
# Journal Entry

**Date:** YYYY-MM-DD  
**Location:** (e.g., "Central Park, New York, NY")  
**Weather:** (e.g., "Sunny, 18°C, light breeze")  
**Observer:** (your name or username)

## Observation Focus
*Which specific task or theme guided this observation? (e.g., Soundscape Analysis, Phenology Focus, Biophilia Effect)*

## Observations (Flora/Fauna)
*Describe the plants, animals, fungi, or other living organisms you noticed. Be as specific as possible.*

## Sensory Details
### Sounds
*What did you hear? Identify natural and human-made sounds, their rhythms, volumes, and how they changed over time.*

### Smells
*Describe any scents in the air—soil, flowers, rain, etc.*

### Visual & Tactile
*Note colors, textures, light patterns, wind on skin, temperature, etc.*

## Cognitive / Emotional Reflection
*How did this observation affect your state of mind? Did you notice changes in focus, stress, creativity, or mood? Link your experience to concepts from cognitive science if possible.*

## Personal Notes & Questions
*Any lingering thoughts, curiosities, or future observations you'd like to pursue.*

---

*This entry was submitted as part of the Nature and Cognition Field Journal Project.*
```

---

## Repository Structure

```
nature-cognition-journal/
├── README.md                 # This file – project syllabus and guide
├── entries/                  # Directory for all student journal entries
│   ├── student_alpha_soundscape_2023-10-27.md
│   └── ... (more entries)
├── .github/                  # GitHub-specific configurations (optional)
└── LICENSE                   # Open-source license (MIT recommended)
```

---

## Code of Conduct
- Respect diverse perspectives and experiences
- Provide kind, constructive feedback during reviews
- Credit original ideas and observations when building on others' work
- Maintain a supportive, inclusive learning environment

---

## Acknowledgments
This project is inspired by the growing body of research on **nature therapy**, **attention restoration theory**, and **biophilia**. Special thanks to the open‑source community for making collaborative platforms like GitHub accessible for educational use.

---

**Happy observing, and may your time in nature bring both insight and tranquility.**