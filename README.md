### Steps to start the cron job:

1. npm install
2. fill config.json
3. npm start


### If prerequisites are not intalled use npm -i
Create a config json file and paste the scrypt down below in order to get it working.

Have fun.


{
  "delay": "30s",
  "priorities": {
    "1": "45m",
    "2": "30m",
    "3": "15m"
  },
  "urls": [
    {
      "url": "https://github.com",
      "priority": "2"
    },
    {
      "url": "https://reddit.com"
    }
  ]
}

