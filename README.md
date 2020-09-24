Rogue stock tracker!
-------

This script periodically checks for the [Bravo Bar & Bumper](https://www.roguefitness.com/bravo-bar-bumper-set) set from Rogue fitness, which has been sold out due to the COVID19 pandemic. 

To accomplish this, we periodically refresh the linked URL above. The script makes a request for the  

Setup
-----

First, you must install Twilio:

```
pip install twilio
```

You must also create a file named `twilio_credentials.py` in the project directory. Add the following content to this file:

```
account_sid = "YOUR_TWILIO_ACCOUNT_SID"
auth_token  = "YOUR_TWILIO_AUTH_TOKEN"
welsny_cell = "YOUR_CELL_NUMBER"
twilio_cell = "YOUR_TWILIO_NUMBER"
```

Finally, run the script:

```./main.py &```

Configuration
-------------

You can configure the delay between checks in `main.py`. You can also configure this script to run on different web pages. 

