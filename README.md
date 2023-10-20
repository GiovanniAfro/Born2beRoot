# Born2beRoot
Born2beRoot: A System Administration exercise for setting up a secure server, using VirtualBox or UTM, strict rules, and optional bonus tasks.

Born2beRoot Project
Summary

Born2beRoot is a System Administration exercise designed to familiarize you with the world of virtualization. This project will guide you in setting up your first virtual machine using VirtualBox (or UTM if VirtualBox is not available) while adhering to specific instructions. By the end of this project, you will have the knowledge and skills to configure your own operating system following strict rules.
Version

Version: 3
Table of Contents

    I Preamble
    II Introduction
    III General guidelines
    IV Mandatory part
    V Bonus part
    VI Submission and peer-evaluation

Chapter I - Preamble

This section sets the stage for the Born2beRoot project.
Chapter II - Introduction

The project's primary aim is to introduce you to the world of virtualization. You will create your first virtual machine in VirtualBox (or UTM) according to specific guidelines. At the project's completion, you'll have your own operating system set up with strict rules.
Chapter III - General Guidelines

    Mandatory Use of VirtualBox: You are required to use VirtualBox (or UTM if VirtualBox is not available).
    Submission: Submit a signature.txt file at the root of your repository containing the signature of your machine's virtual disk.

Chapter IV - Mandatory Part

The mandatory part of this project focuses on setting up your first server with specific rules:

    Choose Debian (latest stable version) or Rocky (latest stable version) as your operating system.
    Configure SELinux and AppArmor for Debian to run at startup.
    Create at least 2 encrypted partitions using LVM.
    Configure SSH service to run on port 4242, with no root access allowed.
    Implement a strong password policy.
    Install and configure sudo following strict rules.
    Create a user with your login as the username, belonging to the user42 and sudo groups.
    Develop a bash script called monitoring.sh to display system information on all terminals every 10 minutes.

Chapter V - Bonus Part

The bonus part allows you to earn additional points by achieving the following tasks:

    Set up partitions correctly.
    Create a functional WordPress website using lighttpd, MariaDB, and PHP.
    Set up a service of your choice (excluding NGINX and Apache2) and justify your choice during the defense.

The bonus part will only be assessed if the mandatory part is completed perfectly.
Chapter VI - Submission and Peer-Evaluation

To submit your project, create a signature.txt file at the root of your Git repository, containing the signature of your virtual machine's disk. Detailed instructions for retrieving the signature are provided.

Please note that submitting your virtual machine in your Git repository is forbidden. During the defense, the signature of the signature.txt file will be compared with the one of your virtual machine to ensure their identity.

Good luck with your Born2beRoot project!
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjwoeyjlYSCAxWRX_EDHTmvDcgQFnoECBMQAQ&url=https%3A%2F%2Fgithub.com%2Fpasqualerossi%2FBorn2BeRoot-Guide&usg=AOvVaw1aglbEq45-2MP_jAt74KAu&opi=89978449
