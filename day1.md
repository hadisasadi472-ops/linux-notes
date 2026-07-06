📝 Today's Technical Notes (Day 1)
🐧 Part 1: Setting up the DevOps Environment
Today marked the official start of my infrastructure journey by setting up a local Linux environment and learning how to interact with the Operating System via the Command Line Interface (CLI).

Key Concepts & Architecture
CLI vs. GUI: Understood that cloud servers do not have a graphical interface (GUI). Mastering the Command Line Interface (CLI) is essential for cloud automation and infrastructure management.

WSL (Windows Subsystem for Linux): Learned how WSL allows running a native Ubuntu Linux environment directly inside Windows without the overhead of a heavy Virtual Machine.

The Linux Shell: Introduction to Bash (Bourne Again Shell) as the command interpreter that executes the instructions we type.

🛠️ Part 2: Core Linux Commands Lab
Executed the very first set of essential commands to navigate and manipulate the filesystem.

Commands Mastered:
whoami: Displays the exact username of the current active session (e.g., hadislinux).

pwd (Print Working Directory): Outputs the absolute path of the current directory I am standing in.

ls (List): Lists all files and folders inside the current directory.

ls -la: An advanced flag used to show all hidden files (starting with a dot .) along with detailed permissions and sizes.

cd (Change Directory): Used to navigate between folders (e.g., cd / to go to root).

mkdir (Make Directory): Creates a brand new folder in the specified path.

touch: Quickly creates a new, blank file (e.g., touch test.txt).

clear: Cleans the terminal screen to maintain a focused and neat workspace.

Practical Lab Executed
Bash
# Check current user and location
whoami
pwd

# Create a dedicated workspace for DevOps studies
mkdir devops-journey
cd devops-journey

# Create a sample text file and verify its existence
touch baseline.txt
ls -la
🌐 Part 3: Foundational Networking Concepts
Introduction to how computers identify each other over a network, which is critical for cloud routing and security.

IP Address (Internet Protocol): The unique numerical label assigned to each device connected to a computer network (the computer's "home address").

Localhost (127.0.0.1): The standard loopback address that allows a computer to refer to itself. Essential for testing applications locally before deploying them to the cloud.
