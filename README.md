
# The Lost Flag

Welcome to the The Lost Flag CTF challenge! This CTF is designed to test your basic exploitation techniques, focusing on finding hidden flags in a complex file structure and solving a quiz for root access. Your objective is to locate the flag hidden in a Docker container with various layers of decoy folders and misleading hints. 



![CTF](https://img.shields.io/badge/The_Lost-Flag-red) 
![Lab](https://img.shields.io/badge/hide_and_seek-blue)


## How to Participate
To start the challenge, you will need to pull the Docker image from DockerHub and run the container. Once inside, you will first need to solve a color-guessing quiz to gain root access and begin hunting for the flag.




## Challange Flow

- Start with a quiz: Answer a color-guessing question to gain root access.
- Hunt for the flag: Once you have root access, search through a complex directory structure filled with decoys and hidden files.
- Misleading flags: Beware of fake flags and decoy directories that are designed to waste your time.
- Self-destructing files: Some scripts will self-destruct once executed to prevent the challenge from being completed too easily.


## Requirements

Before you start, make sure you have the following installed:

  - Docker: This CTF runs within a Docker container. You can install Docker from (https://www.docker.com/get-started).

  - Docker Hub Account (optional): You may want an account to track the images you're pulling.

## Getting Started

1. Pull the Docker image:
   
   To get started, pull the image from DockerHub by running:
```bash
   docker pull yunchohang/hunt:f1ag
```
2. Run the Docker container:

   Once you’ve pulled the image, run the container with the following command:
```bash
   docker run -it --rm yunchohang/hunt:f1ag
```
  This will start the challenge and present you with the color-guessing quiz.

3. Solve the quiz:

   Follow the instructions within the container to solve the quiz. Once you answer correctly, you will gain root access and can begin searching for the flag.

4. Search for the flag:

   Explore the file system carefully to find the real flag. Remember, there are plenty of decoys and fake flags scattered around, so pay attention to details.
## Hints for Finding the Flag
Here are some hints to guide you along the way:

For the Quiz:
- Hint 1: Think of primary colors... Red, blue, and yellow.
- Hint 2: You can only ask for a hint once, so make it count!
- Hint 3: The color I’m thinking of is not too bright, but it’s also not too dark.
- Hint 4: The color I’m thinking of can often be found in traffic lights.

For Finding the Flag in the Directory Structure:
- Hint 1: Not all paths lead to the real treasure. Some directories are just distractions.
- Hint 2: If a folder looks too obvious, it's probably a dead-end. Check the unexpected places.
- Hint 3: Look for folders with names that seem too random to be of importance. The flag might be there.
- Hint 4: Fake flags can be found everywhere. Look closely at the content to see if it feels off.

## General Tips:
- The flag is hidden in a deep folder structure. Don’t rush; be patient.
- Be cautious of misleading file names and decoy directories.
- You will need to solve the color-guessing quiz to gain root access and continue the hunt.


## Important Notes
- Security: This CTF is designed to simulate a real-world environment, so pay attention to possible vulnerabilities and unexpected behavior.
- Self-Destruct: After you attempt the challenge, some files will be self-destructed to ensure the challenge can’t be replayed in the same session.
- No Root Access Without Solving the Quiz: You will not be able to access the deeper parts of the file structure without solving the quiz first.
## Enjoy the Hunt!

Good luck, and may you find the hidden flag! 🏴

If you encounter any issues or have suggestions for improvement, feel free to open an issue or pull request on the GitHub repository.

