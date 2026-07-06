📝 Today's Technical Notes (Day 2)
🐧 Part 1: Advanced Linux Navigation & Environment
Today, I explored deeper into the Linux filesystem hierarchy and learned how to customize and control the terminal environment.

Key Concepts & Architecture
The Linux Filesystem Structure: Unlike Windows, Linux uses a unified tree structure starting from the root directory (/).

Crucial Directories Handled:

/root: The separate home directory reserved strictly for the System Administrator (Superuser).

/home: The standard location where regular users (like /home/hadis) store their personal files, configurations, and projects.

/mnt: The mount point used to access external filesystems, such as accessing Windows drives (/mnt/c/) from inside WSL.

Navigation Shortcut: Mastered using cd ~ to immediately jump back to the user's personal home directory from anywhere in the system.

Environment Variables & Customization
Variables ($): Learned how to store temporary data in memory using variables (e.g., NAME="Hadis").

The echo Command: Used to print text or evaluate the value of variables in the terminal using the $ sign (e.g., echo $NAME).

Practical Lab Executed
Bash
# Checking current location in the filesystem
pwd

# Navigating to the native Linux Home directory
cd ~

# Declaring a local variable and printing its value
MY_ROLE="DevOps Engineer"
echo $MY_ROLE

# Navigating to the Windows Desktop via the mount directory
cd /mnt/c/Users/Lenovo/Desktop
📂 Part 2: GitHub & Professional Personal Branding
Understanding the strategic importance of version control and maintaining an active open-source profile.

Why GitHub Documentation Matters:
Executive Presence: A well-documented GitHub profile acts as a living portfolio for international employers and cloud clients.

Knowledge Retention: Writing clean markdown files ensures technical concepts are safely stored and easily retrievable.

Tracking Progress: Committing daily tasks builds consistency and visually shows career growth over time.
