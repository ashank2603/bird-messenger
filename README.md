# Bird Messenger - A Messaging App

How to run:

- Clone the repository.
- Open the directory in a terminal and run <code>npm install</code>
- Create a mongodb database and copy the connection string.
- Create a cloudinary account and follow the steps mentioned [here](https://cloudinary.com/documentation/upload_images). Copy the cloud name string.
- Create a pusher account and create a project. Copy the relevant strings as per the dotenv file below.
- Create a dotenv file and put the following in it:
```bash
DATABASE_URL="<YOUR_MONGODB_CONNECTION_STRING>"
NEXTAUTH_SECRET = "<YOUR_NEXTAUTH_SECRET>"
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME = "<YOUR_NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME>"
NEXT_PUBLIC_PUSHER_APP_KEY = "<YOUR_NEXT_PUBLIC_PUSHER_APP_KEY>"
PUSHER_APP_ID = "<YOUR_PUSHER_APP_ID>"
PUSHER_SECRET = "<YOUR_PUSHER_SECRET>"
```
- In the terminal now run <code>npx prisma db push</code>
- Now run <code>npm run dev</code> in the terminal.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Features
- Authentication
- Group Chat Functionality
- Send Image as chat functionality
- Read Receipts
- Edit Profile functionality

## Screenshots

Login Page
![image](https://github.com/ashank2603/bird-messenger/assets/61231703/aafaa567-fea3-4297-9cbd-bb56067aeceb)

Register Page
![image](https://github.com/ashank2603/bird-messenger/assets/61231703/9b107f63-d318-4012-a64d-843a6eb2f34a)

Users Page
![image](https://github.com/ashank2603/bird-messenger/assets/61231703/1abeef5a-5331-4f01-854f-683a9a6ee90b)

Chats Page
![image](https://github.com/ashank2603/bird-messenger/assets/61231703/c1b4dccb-c073-42b7-9e82-175c501fb9fe)
