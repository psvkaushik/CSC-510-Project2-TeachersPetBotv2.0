<p align="center"><img src="https://github.com/Ashwinshankar98/TeachersPetBot/blob/main/images/teacherspet.png" alt="alt text" width=200 height=200>
  
  <h1 align="center"> Teacher's Pet </h1>
  <h1 align="center"> For Intructors and Students </h1>   
  
<h2 align="center"> Streamline Your Class Discord</h2>

![Python](https://img.shields.io/badge/python-v3.7+-brightgreen.svg)
![GitHub issues](https://img.shields.io/github/issues/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
![GitHub closed issues](https://img.shields.io/github/issues-closed/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
[![codecov](https://codecov.io/gh/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/graph/badge.svg?token=3QCL57IUZF)](https://codecov.io/gh/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
![GitHub](https://img.shields.io/github/license/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
[![DOI](https://zenodo.org/badge/718312021.svg)](https://zenodo.org/doi/10.5281/zenodo.10211826)
[![](https://tokei.rs/b1/github/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0).
![Github pull requests](https://img.shields.io/github/issues-pr/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
![Github stars](https://img.shields.io/github/stars/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
![Respost - Write comment to new Issue event](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/actions/workflows/Respost.yml/badge.svg)
![version](https://img.shields.io/badge/version-2.1-blue)
![Close as a feature](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/actions/workflows/close_as_a_feature.yml/badge.svg)
![GitHub contributors](https://img.shields.io/github/contributors/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0)
[![Style Checker and Prettify Code](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/actions/workflows/Style_Checker_and_Prettify_Code.yml/badge.svg)](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/actions/workflows/Style_Checker_and_Prettify_Code.yml)
[![Running Code Coverage](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/actions/workflows/codecov.yml/badge.svg)](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/actions/workflows/codecov.yml)
![Pylint](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/actions/workflows/pylint.yml/badge.svg)

<!-- I am not sure about this parameter yet. Any idea what to do about this? -->
<!-- ![GitHub deployments](https://img.shields.io/github/deployments/Ashwinshankar98/TeachersPetBot/discord-bot-phase2)<br/> -->

## Contents

1. [ Description ](#desc)
2. [ New Features](#features)
3. [ Installation and Running ](#instrun)
4. [ Testing ](#testing)
5. [ Bot Commands ](#commands)
6. [ Future Scope ](#fscope)
7. [ Want to contribute? ](#contribute)
8. [ License ](#license)

<a name="desc"></a>

## Click Below to Watch The Video!

https://www.youtube.com/watch?v=QXUmwBD5vks

<h2>Software Engineering Project for CSC 510 : Phase V</h2>

Teacher's Pet is a Discord Bot for class instructors to streamline their Discord servers. Discord is a great tool for communication and its functionalities can be enhanced by bots and integrations.

For 5.0, we created new tools for instructors and students to use to improve course communication. After version 4.0's success, we decided we wanted to improve upon some of its features including spam, profanity settings, penalty, awarding-penalize XP, QNA channel etc. Our main objective for 5.0 was to make using Discord a more controlled and enjoyable experience.

<hr />

<a name="features"></a>

## New Features

[Click here to see the latest additions in detail](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/blob/main/docs/Improvements_Iteration4_vs_Iteration5.md)

[Click here to see the features of previous iterations I, II, III, and IV.](docs/feature-history.md)

1. **!Award XP**  
   Instructors award XP to users in the instructor channel for encouraging positive behaviors.

   ![award_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/c0ac2d86-96ae-46f9-add3-d3d3fa593733)

2. **!Penalize XP**  
   Instructors can reduce XP for reasons like invalid input or irrelevant discussions.

   ![penalize_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/c26fa9ed-2d64-4be3-9ae0-1064079d618b)

3. **!Leaderboard**  
   Users access the top 10 rankers' leaderboard based on their ranks and XP.

   ![leaderboard_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/730895ed-c163-4496-9dd9-defb8d442b82)

4. **Instructor Mentions Channel**  
   Tagging instructors results in questions being posted in the instructor QNA channel; replies are posted back to the main channel, ensuring no mention goes unnoticed.

   ![instructor_mention_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/e54c2fc2-67e2-4d81-83f3-7061e5d0120a)

5. **Spam Violation penalty**
   Users receive a 10XP penalty for spamming, enhancing the XP-based ranking system, and receiving timeouts for improper behavior.

   ![spam_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/0912b6ce-50ce-45e8-9180-02ad3be6ec8d)

6. **NSFW violation penalty**
   Custom XP penalties set by instructors for users posting NSFW messages in chat channels.

   ![nsfw_profanity_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/0a1a5f82-0da4-4b3f-a1d6-db4694e4791f)

7. **Custom profanity settings**  
   Users entering NSFW messages can be warned, timed out, or banned based on instructor-defined or default settings—warning, timeout, followed by server ban.

   ![set_profanity_settings_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/2fcb7cf5-98c1-46d9-9581-3037cfda9950)

8. **Persistent Block from server**  
   Banned users remain blocked; when the bot restarts, attempting reentry leads to an automatic kick if the bot is offline. Online attempts are barred.

   ![blocked_user_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/b9860091-fafd-4515-958c-835582126bdd)

9. **!unblock_user**  
   Instructors gain authority to unblock users by usernames, allowing banned individuals to rejoin.

   ![unblock_user_gif](https://github.com/psvkaushik/CSC-510-Project3-TeachersPetBotv2.0/assets/22112102/996ac853-8eb4-45aa-a3a9-f46b39cdd7ab)

10. **DB initialization**
    Proper integration with databases ensures new user entry upon bot restart; detects and creates missing user database entries on server join.

<a name="instrun"></a>

<h2> Installation and Running </h2>

#### Tools and Libraries Used

In addition to the packages from [requirements.txt](https://github.com/tanmaypardeshi/CSC-510-Project2-TeachersPetBot/blob/main/requirements.txt) which need to be installed, please have the following installed on your machine:

- [Python 3.9.7](https://www.python.org/downloads/)
- [Sqlite](https://www.sqlite.org/download.html)

To install and run Teacher's Pet, follow the instructions in the [here](https://github.com/psvkaushik/CSC-510-Project2-TeachersPetBotv2.0/blob/main/docs/InstallationGuide.md)

<a name="testing"></a>

<h2>Testing </h2>

To run tests on the Teacher's Pet, follow instructions in the [Installation and Testing Guide](Installation.md).

<hr />

<a name="commands"></a>

<h2> Bot Commands </h2>

<h3> Bot commands from iteration V </h3>

`!custom_profanity_settings` to set the profanity settings

`!leaderboard` any user can run to see the leaderboard of the top 10 rankers

`!penalize <@member> <xp_points_penalized>` can use this new command to reduce XP (Instructor command)

`!award <@member> <xp_points_awarded>` can use this in the instructor channel to award XP to users (Instructor command)

`!unblock_user` Allows instructors to have the power to unblock users (Instructor command)
<br>

<h3> Bot commands from iteration I, II, III, IV </h3>    
  
`set_spam_settings command` Set the spam_settings (Instructor command)

`!setInstructor <@member>` Set a server member to be an instructor (Instructor command)

`!removeInstructor <@member>` Remove a server member from the instructor role (Instructor command)

`!getInstructor` Get the current instructors in the server

`!attendance` Find attendance from voice channel (Instructor command)

`!ask "<question>"` Ask a question

`!answer <question_number> "<answer>"` Answer a question

`!poll <command>` Run a poll for students (Instructor command)

`!create` Start creating an event (Instructor command)

`!oh enter` Enter an office hour queue as an individual student

`!oh enter <group_id>` Enter an office hour queue with a group of students

`!oh exit` Exit the office hour queue

`!oh next` Go to the next student in the queue as an instructor (Instructor command)

`!help` Gets the descriptions for all commands

`!help <command>` Describes a command in detail

`!ping` Find the latency of the network

`!stats` Gets the statistics of the system and software used

`!regrade-request` This command lets a student add a regrade-request

`!update-request` This command lets a student update an existing regrade-request

`!remove-request` This command removes a regrade request

`!display_requests` This command lets a student display all regrade requests

`!chart` This command lets admins make a custom chart of any type with any size of dataset

`!check_chart` This command lets students/users check any chart if previously created

`!create_email` This command enables users to configure their email address to receive important reminder notifications and attachments

`!view_email` This command enables users to view their configured email address

`!update_email` This command enables users to update their configured email address

`!remove_email` This command enables users to delete their configured email address

`!create -> press project button` This command enables users to create a project

<hr />

<a name="fscope"></a>

<h2> Future Scope </h2>

This bot has endless possibilities for functionality. Features that we are interested in adding but did not have time for include but are not limited to:

- [ ] Adding detailed error display integration to the bot (next 1 month)
- [ ] Add Tutor role (next 1 month)
- [ ] Refactor code to use cogs (next 2 months)
- [ ] Add a gibberish detector that deletes comments that are irrelevant to the class (next 3 months)
- [ ] Funnel the AI chat responses to a limited set(so AI only answers questions an instructor wants them to answer) (next 5 months)
- [ ] Upgrade to a better chatbot API that is free (next 6 months)

<hr />

<a name="contribute"></a>

<h2>How to Contribute? </h2>

Check out our [CONTRIBUTING.md](https://github.com/psvkaushik/CSC-510-Project2-TeachersPetBotv2.0/blob/main/CONTRIBUTING.md) for instructions on contributing to this repo and helping enhance this Discord Bot, as well as our [Code of Conduct](https://github.com/psvkaushik/CSC-510-Project2-TeachersPetBotv2.0/blob/main/CODE_OF_CONDUCT.md) guidelines.

<a name="license"></a>

<h2> License </h2>

The project is licensed under the [MIT License](https://github.com/psvkaushik/CSC-510-Project2-TeachersPetBotv2.0/blob/main/LICENSE).

<hr />

<h3> Team Members </h3>

- :octocat: [Ayush Agarwal](https://github.com/ayush-ai8)
- :octocat: [Kaushik Pillalamarri](https://github.com/psvkaushik)
- :octocat: [Surya Upadyayula](https://github.com/SuryaUpadyayula)
- :octocat: [Vaishnavi Naik](https://github.com/VaishnaviNaik96)

<h3> Previous Authors </h3>

#### Sam Kwiatkowski-Martin

#### Abhinav Sinha

#### Chandana Ray

#### Tanmay Pardeshi

#### Sandesh Aladhalli Shivarudre Gowda

#### Chandatahas Reddy Mandapati

#### Sri Pallavi Damuluri

#### Niraj Lavani

#### Harini Bharata

#### Ashwin Shankar Umasankar

#### Itha Aswin

#### Kailash Singaravelu

#### Saikaushik Kalyanaraman

#### Shakthi Nandana Govindan

# Contact us

For any questions and contributions please contact: ncsuse23@gmail.com

Made with ❤️ on GitHub.
