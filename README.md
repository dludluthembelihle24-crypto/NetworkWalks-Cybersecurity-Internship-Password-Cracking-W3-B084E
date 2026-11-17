
# NetworkWalks-Cybersecurity-Internship-Password-Cracking-W3-B084E
Continued development of practical cybersecurity skills, focusing on password security and hashing analysis

Practical exercise focusing on password security, hash analysis and authentication. Recovering the passwords of two encrypted PDF Files, employing two methods: John the Ripper (the command-line tool), NetworkWalks Hash calculator (web based) as well as a Password Cracker. Both successfully recovered the password and unlocked the PDF's, revealing the flags. 


# 1. Project Overview

This project documents my hands-on learning experience in password security, password cracking and hash analysis as part of my cybersecurity and ethical hacking journey.

The objective of this project is to understand how passwords are stored, how password hashes work, how password-cracking tools operate and why strong password security practices are essential in protecting digital systems.

Through practical exercises, I explored John the Ripper, its graphical user interface (Johnny), password hash concepts, file handling, tool configuration and troubleshooting.

This project also documents the challenges I encountered, how I approached troubleshooting and the technical knowledge I gained throughout the process.

 - Project Type: Cybersecurity Practical Lab

 - Focus Area: Password Security and Hash Analysis

 - Tools: John the Ripper, Johnny GUI

 - Operating System: Windows

 - Learning Approach: Hands-on Practical Exercises


# 2. Project Objectives

The main objectives of this project were to:

 - Understand the fundamentals of password hashing.

 - Explore different password-hashing concepts and algorithms.

 - Understand the difference between encryption and hashing.

 - Install and configure John the Ripper.

 - Explore Johnny as a graphical interface for John the Ripper.

 - Understand how password-cracking tools perform password recovery.

 - Explore the role of wordlists in password auditing.

 - Understand how weak passwords can be identified through authorised security testing.

 - Develop troubleshooting skills when working with cybersecurity tools.

 - Understand the importance of strong passwords and secure authentication practices.

# 3. Tools and Technologies Used

 - John the Ripper

*John the Ripper is an open-source password security auditing and password recovery tool.*

*It is used to assess password strength by testing candidate passwords against password hashes.*

**Version:** John the Ripper 1.9.0 Jumbo

**Platform:** Windows 64-bit

 - Johnny GUI

*Johnny is a graphical user interface for John the Ripper.*

*It provides a visual way of interacting with John the Ripper instead of relying entirely on command-line operations.*

During this project, I explored Johnny's configuration and its relationship with the main John the Ripper executable.

**Supporting Tools:**

 - Windows File Explorer

 - 7-Zip

 - Windows Task Manager

 - Notepad

# 4. Installation and Configuration

**Step 1: Downloading John the Ripper**

I downloaded John the Ripper 1.9.0 Jumbo for Windows 64-bit.

The downloaded package contained multiple supporting files and folders required for the application to function.

**Step 2: Extracting the Downloaded Files**

I used 7-Zip to extract the downloaded archive.

During this process, I learned that John the Ripper contains several supporting files, and it is important to understand the folder structure before attempting to configure the application.

**Step 3: Exploring the Application Files**

After extraction, I explored the available folders and files to identify the main executable and supporting components.

This helped me understand the difference between application executables, configuration files, input files and other supporting resources.

**Step 4: Exploring Johnny GUI**

I proceeded to work with Johnny, the graphical interface for John the Ripper.

One of the configuration requirements was identifying and setting the correct path to the main John the Ripper executable.

This introduced me to the importance of correct executable paths when connecting graphical interfaces to command-line security tools.

# 5. Practical Exploration and Technical Challenges

This section documents some of the challenges I encountered while setting up and exploring the tools.

**Challenge 1:** Understanding File Types

While working with the John the Ripper files, I encountered a file named:

 <u> tests.in </u>

Initially, I was unsure how to open or extract this file.

I explored its available Windows file-opening options and attempted to understand its purpose.

**What I learned:**

 - Not every file is an archive.

 - File extensions indicate different file types.

 - An .in file can contain input or test data.

 - Files should not automatically be treated as compressed archives.

 - Notepad can be useful for inspecting text-based files.

**Challenge 2:** Configuring the John Executable Path

While configuring Johnny, I encountered difficulties identifying and selecting the correct John the Ripper executable.

The application displayed a red indicator when I attempted to configure the path.

This required further investigation into the extracted folder structure and the correct executable location.

**What I learned:**

 - Graphical interfaces depend on correctly configured executable paths.

 - Selecting the wrong file can prevent an application from functioning correctly.

 - Understanding the relationship between a GUI and its underlying application is important when configuring cybersecurity tools.

**Challenge 3:** Johnny Opening Multiple Instances

Another issue occurred when launching Johnny.

Instead of opening a single application window, Johnny repeatedly opened multiple instances.

I attempted to resolve this by:

Uninstalling Johnny.

Reinstalling the application.

Opening Windows Task Manager.

Identifying Johnny processes running in the background.

Attempting to end the processes manually.

I also noticed that additional Johnny processes continued appearing after ending existing tasks.

**What I learned:**

 - Reinstalling an application does not always resolve configuration or process-related problems.

 - Windows Task Manager is useful for investigating running processes.

 - Multiple application instances may indicate an underlying launch or configuration issue.

 - Troubleshooting requires identifying the root cause rather than repeatedly reinstalling software.

# 6. Password Hashing: Technical Concepts

Password hashing is a security process that transforms a password into a fixed-length output using a hashing algorithm.

Unlike encryption, hashing is designed to be a one-way process.

When a user logs into a system, the submitted password can be hashed and compared against the stored password hash.

**Important Concepts**

*Plaintext Password*

 - The original readable password before hashing.

*Password Hash*

 - The output generated when a password is processed through a hashing algorithm.

*Hashing Algorithm*

 - The mathematical function used to generate a hash.

*Salt*

 - Random data added to a password before hashing to make identical passwords produce different hashes.

*Wordlist*

 - A collection of candidate passwords used during password auditing.

*Brute-Force Attack*

 - A password-guessing approach that systematically tests possible combinations.

*Dictionary Attack*

 - An approach that tests candidate passwords from a predefined list.

*Rainbow Tables*

 - Precomputed tables used to assist in reversing certain unsalted hash values.

# 7. Understanding John the Ripper

John the Ripper supports different password-testing techniques.

*These include:*

 - Wordlist-based password testing.

 - Single-crack mode.

 - Incremental password testing.

 - Password hash identification and format handling.

 - Password auditing using different supported hash formats.

The effectiveness of password recovery depends on several factors, including password complexity, the hashing algorithm, available candidate passwords and computational resources.

# 8. Practical Testing and Results

This section will document the practical exercises performed during the lab.

**Areas to investigate and document:**

 - Identifying password hash formats.

 - Understanding the structure of different hashes.

 - Preparing authorised test hash files.

 - Exploring wordlist-based password testing.

 - Understanding password recovery results.

 - Comparing weak and stronger password choices.

 - Understanding how password hashing algorithms influence password security.


# 9. Skills Developed

*Throughout this project, I developed and explored the following skills:*

 - Basic password security concepts.

 - Understanding password hashing.

 - Introduction to password auditing.

 - Familiarity with John the Ripper.

 - Familiarity with Johnny GUI.

 - Windows application installation and configuration.

 - File extraction and file management.

 - Executable path configuration.

 - Basic Windows process management.

 - Technical troubleshooting.

 - Cybersecurity research and documentation.

 - Problem-solving and independent learning.

# 10. Lessons Learned

One of the biggest lessons from this project was that cybersecurity involves more than simply installing and running tools.

Understanding how a tool works, identifying its dependencies, configuring it correctly and troubleshooting unexpected behaviour are equally important.

**I also learned that:**

 - Understanding the fundamentals makes practical exercises easier.

 - File extensions and directory structures matter.

 - GUI applications often depend on underlying command-line tools.

 - Troubleshooting is an important technical skill.

 - Password security is an essential part of cybersecurity.

 - Weak passwords can expose systems to unnecessary security risks.

 - Continuous practice is necessary when developing technical skills.


# 13. Ethical Considerations

All password-testing and password-auditing exercises associated with this project are intended for educational purposes and authorised security assessments.

Password-cracking techniques should only be performed on systems, accounts and test data for which permission has been granted.

The objective is to understand password vulnerabilities, improve authentication security and develop responsible cybersecurity skills.

# 14. Conclusion

This project represents another step in my journey towards becoming a cybersecurity professional.

Working with John the Ripper and exploring password hashing has helped me understand the importance of password security and the practical challenges involved in using cybersecurity tools.

Although I encountered several configuration and troubleshooting challenges, each experience provided an opportunity to learn, investigate and develop my technical problem-solving abilities.

I am continuously building my knowledge through practical exercises, research and hands-on cybersecurity projects

# 15. Methodology<u/>

**A.** *W3-PM1: John the Ripper (JTR)*

1. **Hash Extraction:** Uploaded a PDF then ran the extracted file for conversion output

2. **Cracking:** Hitherto the hash was copied to a notepad and saved to a file as 'hash1.txt', then from Johnny you open a password file, choose the saved file, start an          attack and the plain text is recovered just like that.

3. **Result:** John successfully cracked the hash and recovered password.

4. **Flag:** Upon opening the PDF with the recovered password, the flag was revealed.
   



**B**. *W3-PM2: Networkwalks Web Tools*
   
1. **Uploaded** the locked PDF to the Networkwalks Hash Calculator to extract the hash.
   
2. **Pasted** the extracted hash into the Networkwalks Password Cracker.

3. **Result:** The web tool successfully recovered the password: password1.
   
4. **Flag:** Upon opening the PDF with the recovered password, the flag was revealed.


