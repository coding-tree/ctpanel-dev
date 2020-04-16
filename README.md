# MEET-UP Organizer for Coding Tree


## Development

### To run application in development mode

#### First Install dependencies for root folder 

    npm install

#### Next Install dependiencies for client and server folder

    npm run install:both

#### You need .env file in server folder

example: 

    MEETUP_SECRET=hehetomobbyn
    AUTH0_DOMAIN=sgwtfgg.eu.auth0.com
    AUTH0_CLIENT_ID=qwpeoqdokqopwd
    AUTH0_CLIENT_SECRET=sqwoekqowdmqwd
    AUTH0_CALLBACK_URL=http://localhost:3001/callback

#### Next you need to make config file, 

#### You can use this command to firstrun project and generating config file

    npm run firstrun

#### If you already have got config generated use this

    npm run dev
