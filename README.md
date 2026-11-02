# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

# AIM:
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

# Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

# AI Tools Used:
* ChatGPT
* Gemini

# Algorithm:
Step 1: Select a technical article for summarization (e.g., The Basics of Blockchain Technology).

Step 2: Choose one or more AI platforms such as ChatGPT, Gemini, Claude, or Copilot.

Step 3: Prepare different prompt types:

Basic Prompt
Role Prompt
Context Prompt
Constraint Prompt
Output Format Prompt

Step 4: Enter the selected article and corresponding prompt into the AI platform.

Step 5: Generate the summary for each prompt type.

Step 6: Collect and save all generated outputs.

Step 7: Evaluate each output based on:

Accuracy
Coherence
Simplicity
Speed
User Experience

Step 8: Compare the performance of different prompting techniques.

Step 9: Identify the prompt type that produces the most effective summary.

Step 10: Document the observations, analysis, and final results.

# Experiment: 

## Comparing Prompting Techniques for Text Summarization

## Selected Article Topic:

**The Basics of Blockchain Technology**

## Article:

Blockchain is a decentralized digital ledger that records transactions across multiple computers. Each transaction is stored in a block, and blocks are linked together using cryptographic hashes, forming a chain. Because records are distributed across a network, altering data is difficult and requires consensus from participants. Blockchain improves transparency, security, and trust without relying on a central authority. It is widely used in cryptocurrencies such as Bitcoin, but it also has applications in supply chain management, healthcare, banking, and digital identity systems. Common blockchain mechanisms include Proof of Work (PoW) and Proof of Stake (PoS), which help validate transactions and maintain network integrity.

## 1. Basic Prompt:

Summarize the following article on Blockchain Technology in about 100 words.

## 2. Role Prompt:

You are a university professor teaching first-year engineering student. Summarize the following blockchain article in simple and easy-to-understand language.

## 3. Context Prompt:

The audience consists of undergraduate students with limited knowledge of blockchain. Summarize the article and explain the key concepts in a student-friendly manner.

## 4. Constraint Prompt:

Summarize the article in exactly 60 words using simple language and include the terms “decentralized,” “security,” and “cryptocurrency.”

## 5. Output Format Prompt:

Summarize the blockchain article and present the result in bullet points.

# Output:

## 1. Basic Prompt:
## ChatGPT:

Blockchain is a decentralized digital ledger that stores transactions in linked blocks secured through cryptographic techniques. Data is distributed across multiple computers, making it transparent and difficult to modify. Transactions are verified through consensus mechanisms such as Proof of Work and Proof of Stake. Blockchain eliminates the need for a central authority, increasing trust and security. Although best known for powering cryptocurrencies like Bitcoin, it is also used in healthcare, banking, supply chain management, and digital identity systems. Its key benefits include transparency, security, decentralization, and efficient record keeping.

## Gemini:

**Blockchain** is a decentralized, distributed digital ledger that securely records transactions across a network of computers. Transactions are grouped into blocks and cryptographically linked to previous ones, forming an immutable chain. Because no central authority controls the ledger, data cannot be altered or erased without network consensus. Key features include transparency, heightened security, and full traceability. Originally created to power cryptocurrencies like Bitcoin, blockchain technology is now widely applied across industries—including supply chain management, healthcare, smart contracts, and finance—to automate processes and establish trust without reliance on intermediaries.

## 2. Role Prompt:
## ChatGPT:

Blockchain is like a digital notebook shared by many computers. Every transaction is stored in a block, and these blocks are connected to form a chain. Once information is recorded, it is very difficult to change, making the system secure and trustworthy. Instead of one company controlling the data, many computers work together to verify transactions. Blockchain is used in Bitcoin and other cryptocurrencies, but it is also helpful in banking, healthcare, and supply chains. Its main advantages are security, transparency, and decentralization.

## Gemini:

Think of blockchain as a shared, tamper-proof digital notebook distributed across a global network of computers rather than stored on a single central server.

Core Concepts Broken Down:

The Structure (Blocks and Chains): Every transaction is grouped into a data package called a block. Each block receives a unique mathematical fingerprint (a cryptographic hash) that connects it permanently to the block before it, creating a chronological chain. If anyone tries to alter an old block, its hash changes, breaking the chain and alerting the entire network.

Trust Without a Middleman: Because identical copies of the notebook exist on thousands of computers, there is no single point of failure or central authority (like a bank). To edit or add new data, the majority of the network must agree—a process known as consensus.

Validation Rules (PoW vs. PoS): To reach consensus and prevent spam, networks use rules called consensus mechanisms:

Proof of Work (PoW): Computers compete to solve complex math puzzles to validate transactions.

Proof of Stake (PoS): Participants lock up digital assets as collateral for the right to validate transactions.

Real-World Applications:

While blockchain gained fame through cryptocurrencies like Bitcoin, its core superpower—tamper-proof transparency—makes it valuable for far more than financial tokens:

Supply Chains: Tracking raw materials from factory to shelf.

Healthcare: Securing patient medical records across hospital networks.

Banking & Identity: Automating contracts and protecting digital identities against fraud.

## 3. Context Prompt:
## ChatGPT:

Blockchain is a technology that stores information in connected blocks of data. These blocks are linked securely using cryptography, creating a chain that is difficult to alter. Unlike traditional databases controlled by one organization, blockchain data is shared across many computers, improving transparency and security. Transactions are validated through consensus methods such as Proof of Work and Proof of Stake. Blockchain is commonly used in cryptocurrencies but also supports applications in healthcare, finance, and supply chain management. It helps create secure and trustworthy digital systems.

## Gemini:

<img width="2048" height="1657" alt="image" src="https://github.com/user-attachments/assets/7f3fe88d-d688-4bc0-8be7-bbde6c046eb9" />

Blockchain is a decentralized, tamper-proof digital record-keeping system that logs transactions across a massive computer network. Instead of trusting a central entity like a bank, the network relies on cryptographic links between data "blocks" and majority agreement (consensus) among computers to keep information secure and transparent. While famously used for cryptocurrencies like Bitcoin, its reliability makes it useful across banking, supply chains, healthcare, and digital security.

Key Concepts Explained:

1. Decentralized Ledger:
   
Everyday Analogy: Imagine a shared Google Doc given to a whole class where everyone has "view" access and sees updates in real time, rather than one student keeping a private paper notebook on their desk.

Why it Matters: Because everyone has an exact copy of the record, no single person or central authority can secretly alter past data or control the system.

2. Blocks, Hashes, and Chains:
   
Everyday Analogy: Think of a block as a digital page of transactions. Every time a page fills up, it gets stamped with a unique mathematical seal called a hash (like a digital fingerprint).

The "Chain": Each new page includes the fingerprint of the previous page. If a hacker changes even one letter on page 2, its fingerprint instantly changes, breaking the link to page 3 and alerting everyone on the network that someone cheated.

3. Consensus Mechanisms: How the Network Agrees:
   
Before new transactions are added to the notebook, the network must agree they are valid. The article highlights two common rules for reaching agreement:

Proof of Work (PoW):

How it works: Computers on the network run heavy computations to solve complex mathematical puzzles. The first computer to solve the puzzle wins the right to add the next block.

Analogy: A high-tech math contest where solving the problem proves you put in the physical work and compute power.

Proof of Stake (PoS):

How it works: Instead of burning energy on hard math puzzles, participants lock up a portion of their own digital funds (staking) as collateral for the right to validate transactions.

Analogy: Putting down a security deposit. If you validate honest transactions, you earn a reward; if you cheat, you lose your deposit.

Real-World Applications Beyond Crypto:

Blockchain isn't just about digital money like Bitcoin—its core strength is tamper-proof transparency:

Supply Chain: Track a box of fresh produce from the exact farm it was picked at all the way to your local grocery shelf.

Healthcare: Allow patients to securely share encrypted medical records between different hospital systems without risk of data leaks.

Digital Identity & Banking: Verify identities and process automated financial agreements without needing slow, expensive middleman institutions.

## 4. Constraint Prompt:
## ChatGPT:

Blockchain is a decentralized system that records transactions in connected digital blocks. Information is shared across many computers, making changes difficult and improving security. Transactions are verified through consensus methods before being added to the chain. Blockchain powers cryptocurrency systems like Bitcoin and is also used in banking, healthcare, and supply chain management for secure record keeping.

## Gemini:

Blockchain is a decentralized digital ledger that records transactions across a network of computers. Data is organized into connected blocks using cryptographic codes, ensuring high security and preventing tampering without majority approval. Though essential for cryptocurrency like Bitcoin, this technology also improves transparency and trust in industries like healthcare, banking, and supply chain management without needing central authorities.

## 5. Output Format Prompt:
## ChatGPT:

• Blockchain is a decentralized digital ledger.
• Transactions are stored in connected blocks.
• Cryptography secures the data.
• Information is shared across multiple computers.
• Consensus mechanisms validate transactions.
• Common methods include Proof of Work and Proof of Stake.
• Blockchain supports cryptocurrencies such as Bitcoin.
• It is also used in healthcare, banking, and supply chains.
• Key benefits include transparency, security, and trust.

## Gemini:

Decentralized Ledger: Blockchain records transactions across a distributed computer network rather than a single central server, eliminating the need for a middleman or central authority.

Cryptographic Security: Data is stored in chronological "blocks" linked together using unique mathematical signatures (cryptographic hashes), making records permanent and resistant to tampering.

Consensus-Driven: Any additions or changes to the ledger require agreement across network participants, ensuring high data integrity and transparency.

Validation Mechanisms: Uses validation rules like Proof of Work (PoW) (solving complex math puzzles) or Proof of Stake (PoS) (locking up assets as collateral) to approve transactions.

Diverse Applications: Originally developed to power cryptocurrencies like Bitcoin, it is now widely applied to supply chains, healthcare records, banking, and digital identity management.

# Comparison:
## Comparison of Prompting Techniques (ChatGPT vs Gemini):

| Prompt Type              | Platform | Accuracy  | Coherence | Simplicity | Speed     | User Experience |
| ------------------------ | -------- | --------- | --------- | ---------- | --------- | --------------- |
| **Basic Prompt**         | ChatGPT  | Excellent | Excellent | Excellent  | Very Fast | Excellent       |
|                          | Gemini   | Excellent | Excellent | Good       | Very Fast | Good            |
| **Role Prompt**          | ChatGPT  | Excellent | Excellent | Excellent  | Very Fast | Excellent       |
|                          | Gemini   | Excellent | Good      | Moderate   | Fast      | Good            |
| **Context Prompt**       | ChatGPT  | Excellent | Excellent | Excellent  | Very Fast | Excellent       |
|                          | Gemini   | Excellent | Good      | Moderate   | Fast      | Good            |
| **Constraint Prompt**    | ChatGPT  | Excellent | Excellent | Excellent  | Very Fast | Excellent       |
|                          | Gemini   | Excellent | Excellent | Good       | Very Fast | Good            |
| **Output Format Prompt** | ChatGPT  | Excellent | Excellent | Excellent  | Very Fast | Excellent       |
|                          | Gemini   | Excellent | Good      | Good       | Very Fast | Good            |

## Result Summary:

| Category                | Best Performer           | Reason                                               |
| ----------------------- | ------------------------ | ---------------------------------------------------- |
| Best Overall Platform   | ChatGPT                  | Consistently concise, coherent, and student-friendly |
| Most Accurate Summary   | ChatGPT & Gemini (Tie)   | Both covered all major blockchain concepts correctly |
| Most Coherent Summary   | ChatGPT                  | Better flow and organization                         |
| Simplest Summary        | ChatGPT (Role Prompt)    | Easy for undergraduate students to understand        |
| Best User Experience    | ChatGPT                  | Clear, concise, and directly aligned with the task   |
| Best Prompt Type        | Context Prompt           | Balanced technical accuracy with readability         |
| Recommended Combination | ChatGPT + Context Prompt | Most effective for educational content summarization |

## Performance Comparison by Prompt Type:

| Prompt Type          | Accuracy  | Coherence | Simplicity | Speed     | User Experience | Overall Performance |
| -------------------- | --------- | --------- | ---------- | --------- | --------------- | ------------------- |
| Basic Prompt         | Excellent | Excellent | Good       | Very Fast | Good            | Very Good           |
| Role Prompt          | Excellent | Very Good | Excellent  | Very Fast | Excellent       | Excellent           |
| Context Prompt       | Excellent | Excellent | Excellent  | Very Fast | Excellent       | Outstanding         |
| Constraint Prompt    | Excellent | Excellent | Good       | Very Fast | Good            | Very Good           |
| Output Format Prompt | Excellent | Excellent | Good       | Very Fast | Excellent       | Very Good           |

## Ranking of Prompt Types:

| Rank | Prompt Type          | Reason                                                                  |
| ---- | -------------------- | ----------------------------------------------------------------------- |
| 1    | Context Prompt       | Best balance of accuracy, coherence, simplicity, and user understanding |
| 2    | Role Prompt          | Very effective for explaining concepts to beginners                     |
| 3    | Output Format Prompt | Highly readable and easy to review                                      |
| 4    | Basic Prompt         | Accurate but less tailored to the target audience                       |
| 5    | Constraint Prompt    | Meets specific requirements but may limit detail                        |

## Most Effective Prompt Type:

After evaluating all outputs based on Accuracy, Coherence, Simplicity, Speed, and User Experience, the Context Prompt was found to be the most effective overall.

Why Context Prompt Performed Best:

Maintained high accuracy by covering all major blockchain concepts.
Provided sufficient explanation for undergraduate students.
Balanced technical detail and simplicity.
Produced a clear and logically organized summary.
Enhanced understanding without overwhelming the reader.

Best Platform for Context Prompt:

ChatGPT performed better because:

The summary remained concise and focused.
Information was presented in a student-friendly manner.
The output directly matched the summarization objective.

Gemini provided additional explanations and examples, which were informative but moved beyond a concise summary.

# Observations:

* Basic Prompt:

Both platforms generated accurate summaries.
ChatGPT was more concise and easier to read.
Gemini included additional technical terminology and applications.

* Role Prompt:

ChatGPT effectively simplified blockchain concepts using an easy analogy.
Gemini provided a detailed educational explanation, but it resembled a lesson rather than a summary.

* Context Prompt:

ChatGPT balanced simplicity and technical accuracy very well.
Gemini expanded the explanation significantly, making it informative but less concise.

* Constraint Prompt:

Both platforms followed the constraints successfully.
ChatGPT produced a more compact summary.
Gemini added slightly more descriptive wording.

* Output Format Prompt:

ChatGPT generated clear bullet points that highlighted key ideas quickly.
Gemini used descriptive bullet points with more detail, improving depth but reducing brevity.

# Result:

For summarizing technical articles for undergraduate students, the Context Prompt is the most effective prompting technique. Among the evaluated platforms, ChatGPT delivered the best overall performance due to its concise, coherent, and easy-to-understand summaries, while Gemini excelled in providing detailed explanations and additional context.

