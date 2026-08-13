## Business English - Clause Combiner

An interactive, single-file web application designed for intermediate/advanced adult ESL learners and exam candidates (IELTS, TOEFL, iTEP). Building on the foundational syntax learned in Module 1, this tool shifts the learner's focus from individual words to structural "chunks"—helping them master complex sentences, relative clauses, and passive voice.

🎯 Project Overview

Translating word-for-word is a major roadblock for students aiming for B1/B2/C1 proficiency. This module forces learners to process English the way native speakers do: in chunks. By dragging and dropping entire clauses and phrases, users build intuition for how independent clauses, dependent clauses, and conjunctions interact to form sophisticated, high-scoring sentences.

✨ Key Features

🧠 Syntactic Chunking: Users manipulate entire phrases (e.g., "Even though the deadline is tight,") rather than single words, preventing native-language translation habits.

🎨 Advanced Color-Coded Grammar: Visual reinforcement of clause architecture:

🟦 Blue: Main / Independent Clauses (Can stand alone)

🟪 Purple: Dependent / Subordinate Clauses (Needs support)

🟨 Yellow: Connectors / Conjunctions (The glue)

🟩 Green: Phrases (Time, Location, Condition)

🪤 Advanced "Trapdoors" (Error Handling):

Run-on Trap: Flags users if they combine two Main Clauses (Blue) without a Connector (Yellow).

Fragment Trap: Prevents users from submitting sentences made entirely of Dependent Clauses (Purple).

Hanging Connector: Stops users from ending sentences with conjunctions like and, but, or because.

📱 Fully Responsive: Desktop drag-and-drop combined with a seamless "tap-to-move" fallback for mobile and tablet users.

📚 Curriculum Breakdown (30 Levels)

The module progressively introduces complexity:

Levels 1-5: Simple Sentences + Adverbial Phrases (Time, Place, Reason).

Levels 6-12: Compound Sentences (Independent + Connector + Independent).

Levels 13-20: Complex Sentences (Relative Clauses & Noun Clauses).

Levels 21-25: The Passive Voice in complex contexts.

Levels 26-30: Exam-Level Mix (IELTS/TOEFL focus with advanced transitions like Furthermore, Not only... but also, Even though).

🛠 Tech Stack

Zero-dependency, single-file architecture designed for instant deployment and offline capability.

HTML5 (Structure)

Vanilla JavaScript (Game logic, state management, drag-and-drop API, validation algorithms)

Tailwind CSS via CDN (Styling, responsive design, animations)

🚀 Installation & Usage

No build tools or servers required.

Clone the repository:

git clone https://github.com/yourusername/english-clause-combiner.git


Navigate to the project directory.

Open lesson2_module.html directly in any modern web browser.

How to Play

Read the target sentence in the native language (e.g., Turkish) at the top of the screen.

Select the correct grammatical "chunks" from the phrase bank.

Drag and drop them into the Sentence Zone in the correct English syntactic order.

Ensure the grammatical colors align correctly to avoid run-on or fragment errors.

🧠 Pedagogical Methodology

This application is engineered for adult professionals and test-takers:

Built-in Punctuation: Commas are embedded in the blocks (e.g., "In the morning,") to subconsciously teach punctuation rules for introductory clauses.

Distractor Chunks: The word bank includes logically plausible but grammatically incorrect distractors to ensure active comprehension.

Professional Vocabulary: Uses high-utility vocabulary related to corporate environments, negotiations, and academic settings.

🤝 Contributing

Pull requests are highly encouraged! If you'd like to add new languages, new grammatical trapdoors, or expand the level set:

Fork the Project

Create your Feature Branch (git checkout -b feature/AdvancedGrammar)

Commit your Changes (git commit -m 'Add new relative clause levels')

Push to the Branch (git push origin feature/AdvancedGrammar)

Open a Pull Request
