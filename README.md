"# teawizzy3"
Now you have 2 modes to run

npm run manualSnipe => This is for manual sniping. You provide a user's address (from a monitor, check my github for the monitor setup), how many keys you want to snipe, and a delay time (in milliseconds) and the bot will start running and attempt to buy a user's key until it reaches max retries or the script is stopped by the user
npm run autoSnipe => This creates an in-house monitor that actively watches for new users, checks their Twitter metrics, and begins a snipe if it thinks its solid from a simple algo. Sends Discord notification when snipes starts, so you can cancel out if you want to. Everything is automated, but you should customize the code to your liking. You also run chmod +x restartScript.sh and then start the script with ./restartScript.sh if you want it to continuously run (24/7). 
