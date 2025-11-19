# My-First-Cyber-Lab-
A safe place on my laptop where I can learn how computers communicate, practice using Linux and explore cybersecurity tools. 

# What This Lab Is

This lab is like building an internet playground inside my laptop. I will use it to:

* Learn how to use Ubuntu (a flavor of Linux)
* Practice using command-line tools 
* Set up pretend computer networks
* Snapshot everything like a save game, so I can try stuff and go back if I mess up


# What I Used

* My Computer: HP laptop running Windows 11 Home
* VirtualBox: A free app that lets me make pretend other computers are inside my real one
* Ubuntu 24.04.3 LTS: My first virtual computer (also called a VM)

---

# How I Set It Up

# Step 1: Set Up VirtualBox

* I installed VirtualBox 7.2.4 so I could make VMs

<img width="1366" height="768" alt="Screenshot 2025-11-17 195038" src="https://github.com/user-attachments/assets/488410d1-9e29-4b5c-b786-8301569ebece" />


# Step 2: Download Ubuntu

* I got the latest version of Ubuntu from their website (24.04.3 LTS)

<img width="1366" height="768" alt="Screenshot 2025-11-17 195402" src="https://github.com/user-attachments/assets/6901a798-e2b2-4a0d-a03a-68f3231951db" />


# Step 3: Make My First VM

* Name: `UbuntuLab`
* Memory: 8 GB
* CPUs: 2
* Hard Drive: 25 GB
* Started the VM and chose “Try or Install Ubuntu”

<img width="1366" height="768" alt="Screenshot 2025-11-17 201933" src="https://github.com/user-attachments/assets/3393ebbf-26b0-49eb-a7ce-ede6eefee39f" />

<img width="1366" height="768" alt="Screenshot 2025-11-17 203124" src="https://github.com/user-attachments/assets/3807e3a4-ba57-4e82-8051-2dbfa70ebc8a" />

<img width="1366" height="768" alt="Screenshot 2025-11-17 203150" src="https://github.com/user-attachments/assets/e5d66220-e24d-479b-a528-1d9cb3ad9f29" />


# Step 4: Connect the VM to the World 

I gave my pretend computer two ways to communicate:

* One to reach the internet (called NAT) so it can get updates
* One to talk only to other pretend computers I will make later (called Host-Only) so it stays safe


<img width="1366" height="768" alt="Screenshot 2025-11-17 213650" src="https://github.com/user-attachments/assets/9ab9d891-2709-41ce-a4e2-5dc4ae6559e0" />

<img width="1366" height="768" alt="Screenshot 2025-11-17 213852" src="https://github.com/user-attachments/assets/eb584273-7891-4396-80f8-0f44e958f7e7" />

```
     [Internet]
         |
     My Laptop
     (Windows 11)
         |
   -------------------
   | NAT (Internet)  |
   | Host-Only (Lab) |
   -------------------
         |
     Ubuntu VM
```



# Saving My Progress (Snapshots!)

Before doing something new or scary, I take a snapshot. It's like saving in a video game so I can go back if I break something.


What’s Next

Here’s what I’ll do later:

* Add a second VM (like Kali Linux) to pretend to be a hacker 
* Add a third VM to be the victim 
* Try using tools to test security
* Maybe draw maps of my mini network and write up what I learn


# Why This Is Cool

I can break stuff and fix it without messing up my real computer.
I can learn how networks work.
I’m getting ready for real cybersecurity skills.

I’ll keep updating this repo with everything I try, what I learn, and what works (and what doesn’t). Thanks for stopping by!
