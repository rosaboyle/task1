### Hands on task: Autonomous Source Code Vulnerability Analysis Using GPT-4 and Claude

#### Objective:
The purpose of this assignment is to familiarize you with the tools and technologies we utilize within our company for analyzing source code vulnerabilities. This hands-on experience will involve using GPT-4 and Claude to autonomously identify vulnerabilities in source code.

#### Task Overview:
1. **Create a GitHub Repository:**
   - Initialize a new GitHub repository.
   - Add files containing vulnerabilities, such as basic C files with buffer overflow vulnerabilities (basic examples will be available online or use Intro to Infosec course examples (If source code for vulns are available)). Ensure there is a simple makefile to compile the C files into a binary. Set this repository to public access. 

2. **Use a Separate Repository for the Following Tasks:**
   - The code should enable various functions, including:
     - Cloning a Git repository when a link is provided.
     - Extracting the folder structure of the repository.
     - Reading a file.
     - Executing a binary along with the arguments.
     - Making updates on a file.
     - Creating a diff of a file and its update.
   - For simplicity, you may use Ubuntu, Mac, or a Docker image of Ubuntu. If you are comfortable with PowerShell, Windows is also an option. There are no restrictions on the operating system.

3. **Programming ChatGPT:**
   - Implement a loop that allows ChatGPT to run multiple times, appending the output back to the message list. This will enable ChatGPT to automatically detect vulnerabilities in the code.
   - All details of the functions should be added to ChatGPT.
   - Use a prompt to instruct ChatGPT on the tasks to perform. You will write the code for the functions but not the entire pipeline for vulnerability detection. The prompt will guide GPT on its tasks.
   - Create a ground truth list indicating where vulnerabilities exist, formatted as (File path, line number, column number) tuples.

4. **Evaluation:**
   - Generate a confusion matrix for the prediction, including False Positives (FP), False Negatives (FN), True Negatives (TN), and True Positives (TP).

5. **Repeat the Process with Claude:**
   - Once the tasks have been completed using OpenAI's GPT, replicate the process using Claude to compare the effectiveness and accuracy of both AI models in detecting source code vulnerabilities.

#### Deliverables:
- Two GitHub repositories as per the instructions.
- A script or application that performs the specified functions and interacts with GPT and Claude for vulnerability detection.
- A report including the ground truth list of vulnerabilities, the prompts used for GPT and Claude, and the confusion matrices resulting from their predictions.

#### Additional Notes:
- Ensure that you document your process thoroughly, including any challenges faced and how they were overcome.
- Pay close attention to the accuracy of the vulnerability detection, as this is crucial for the effectiveness of the tool.
- Collaboration and communication with team members are encouraged to foster a learning environment and achieve the best possible outcomes.

This assignment is designed not only to introduce you to the tools we use but also to encourage a deep understanding of their application in real-world scenarios. Good luck, and we look forward to seeing your innovative solutions.

% Things you might have to learn
1. Writing a makefile
2. Understanding about buffer overflow and the functions in stdlib that are vulnerable to buffer overflow.
3. Using docker and other command line tools
4. OpenAI and claude API for tool use/function calling, requiring JSON format and File upload and analysis. 


Read FURTHER_INSTRUCTIONS.md for more detail about security considerations.
