# Coding Tree Panel application

Application helps Coding Tree members to achieve great things!

- Meetings organization

    - Plan/Schedule Meetings (IN PROGRESS)
    - Google Calendar synchronization (TODO)
    - Facebook events synchronization (TODO)
    - Create and manage online meetings in popular applications (Zoom, Google Hangout, others?) (TODO)
    - Discord notifications about meetings (TODO)
- Track user experience
    - Register github profile (TODO)
    - Evaluate points based on users commits and pull requests (TODO)
    - Compare values between users (TODO)

## Development

We have great plans about this application.
You can help us with development regardless of your experience level.

### How to clone this repository

Some time ago we decided to use git submodules to split our repository to frontend and backend. This means that cloning this repository is not longer simple step. For most common usecases you dont have to clone this repository but specific one for your area of interest.

- Frontend
    
      git clone https://github.com/coding-tree/ctpanel-frontend.git

- Backend
      
      git clone https://github.com/coding-tree/ctpanel-backend.git

If you still want to clone this repository first make sure you get familiar with basic information about how to work with git submodules - there are planty of great articles out there:

    - https://git-scm.com/book/en/v2/Git-Tools-Submodules
    - https://github.blog/2016-02-01-working-with-submodules/
    - https://www.atlassian.com/git/tutorials/git-submodule

For reference these are 2 commands for quick repository cloning:

    git clone --recurse-submodules git@github.com:coding-tree/ctpanel-dev.git
    git submodule foreach git checkout develop

### Follow these simple and streight forward steps to easly start application on your machine

- npm install (from project root directory)
- Find env files for client and server
- Copy env files adding dot at the begining

    Linux commands:
    
        cd client
        cp env-cmdrc .env-cmdrc
        cd server
        cp env .env

- Update values in those files - ask for assistance if needed (: https://discord.gg/vTZqWmW
- npm run dev
- Application should be up and runing on your local system

## Not application for you but still want to help? Checkout our others repositories
