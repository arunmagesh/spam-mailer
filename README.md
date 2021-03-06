# Spam mailer

## How to use?

### Step 1: Prerequisites

This program has some prerequisites that need to be met in order to test your new
features.

#### Node.js

For this program to function, you need to install the
[Node.js JavaScript Runtime](https://nodejs.org/).

Install version `12.x.x LTS`, **NOT** version `14`.

#### NPM

NPM comes built in with [Node.js](#nodejs), so there isn't a need to worry about
it.

### Step 2: Cloning the repository

Run `git clone https://github.com/oml33t/spam-mailer` in your terminal to clone the 
repository to your local system.

### Step 3: Installing dependencies

Change the directory to the cloned repository by running `cd spam-mailer` in your 
terminal.

Now, run the command `npm install` in your terminal. This will install all of
our dependencies.

### Step 4: Nodemailer setup

This project uses [Nodemailer](https://nodemailer.com/) to send mails and it requires 
certain configurations to run.

Run the command `cp .env.example .env` in your terminal to create a copy of the example env file.

Now, edit the `.env` file to add your email and app password. Check 
[Nodemailer using GMail](https://nodemailer.com/usage/using-gmail/) for more information about 
how to enable 2FA and create App passwords.

### Step 5: Running the program

Run the command `npm start <target_email>` in your terminal. 
