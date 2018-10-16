# ngrok Setup

- Create Account or Log In at [ngrok](https://ngrok.com)
	- You will need an account for your authtoken
- Download ngrok script, unzip, and move somewhere you will remember (mine is in a scripts folder in the root folder `~/scripts/ngrok`)
- CD to ngrok directory
- Run ` $ ./ngrok authtoken xxxxxx` where xxxxx is the authtoken provided by ngrok (this is provided via your ngrok account)
	- A hidden folder will be created in the root called '.ngrok2' with a file called ngrok.yml with the auth token
- Launch ngrok with `./ngrok http 3000` where '3000' is the port that your local server is running on
  - If you are using create-react-app, you can launch your local server with `yarn start`. By default, your local port is 3000.
