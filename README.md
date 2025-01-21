Q-Commerce Food Website - Food Tuck

Project Overview

A Q-commerce food website that allows users to browse and order food. The project is currently under construction due to some glitches. It includes features such as food listings, dynamic interactions, and API integration.

Current Status

Under Construction: The project is experiencing the following issues:

/Shop route: Food list is not appearing on Vercel or network address, but it works on localhost:3000.

In /Shop/:[id], some features like color-changing ratings, counters, and alert buttons are not functioning due to unknown glitch

APIs are functioning correctly:

GET /foods: Success

GET /food/:id: Success

Tech Stack

Framework: Next.js

CMS: Sanity

API: Hackathon-provided API

UI Library: Shadcn

Styling: Tailwind CSS

Icons: React Icons

Deployment Process

Steps for Deployment

Build the project:

npm run build
npm run start
npm run lint

Push code to GitHub:

git add .
git commit -m "your message"
git push -u origin main

Deploy to Vercel:

Log in to your Vercel account.

Import the GitHub repository for the project.

Start the deployment process.

Fix Environment Variables:

Navigate to the project dashboard in Vercel.

Go to Settings > Environment Variables.

Upload the .env.local file.

Redeploy the project:

Go to the project dashboard > Deployment section.

On the latest deployment, click the ... menu.

Select "Redeploy" and confirm.

Successful Deployment: Once redeployed, the project should work as expected.

Issues and Workarounds

Experimental API Warning:
The build log includes the following warning:

This is an experimental API version, which will change without warning and may have serious bugs.

Solution: Ensure the API version is compatible with the current dependencies and frameworks being used. Check the API documentation for updates or stable versions.

Route and Dynamic Features Glitch:

/Shop/:id route not functioning as expected on Vercel.

Dynamic features like rating color changes, counters, and alert buttons are not responsive.

Solution: Debug these features locally and ensure compatibility with the production environment. Use logging or debugging tools to identify the root cause.

Contact

If you have any questions or suggestions, feel free to contact me:

Email: fatima.zohra10122007@gmail.com

