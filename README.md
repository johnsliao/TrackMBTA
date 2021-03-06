# TrackMBTA 

Get the location of your next MBTA train. Follow (@TrackMBTA)

![alt tag](sample_tweet.png)

## Usage
The bot understands commands in this format:

`@TrackMBTA LINE DIRECTION`

- `LINE` - Any MBTA train line. (Currently only supports commuter rail trains)
- `DIRECTION` - Inbound or Outbound. (Can use either 'in' or 'inbound')

### Examples
- Middleborough/Lakeville Line (inbound) - `@TrackMBTA Middleborough Inbound` or `@TrackMBTA Lakeville Inbound`
- Kingston Line (inbound) - `@TrackMBTA kingston inbound`
- Fitchburg Line (outbound) - `@TrackMBTA Fitchburg out`

### Supported commuter rail lines
```
"Fairmount Line
"Fitchburg Line
"Framingham/Worcester Line
"Franklin Line
Greenbush Line
Haverhill Line
Lowell Line
Needham Line
Newburyport/Rockport Line
Providence/Stoughton Line
Kingston/Plymouth Line
"Middleborough/Lakeville Line
```

### Where is the bot running?

The bot is running on Digital Ocean Droplet instance [Sign up $10 off your first month](https://m.do.co/c/b2c8c49bf606) Disclaimer: Referral Link. The bot is not resource intensive and runs pretty much for free

# Running

### Requirements
- Python 2+
- pip

`$  pip install -r requirements.txt`

###Instructions

Create a file called config.py that looks like config_example.py. Fill in the necessary values.

For Twitter config:

1. Register your app
2. Get your secret tokens
3. Set your environment variables accordingly.

```
TWITTER_KEY
TWITTER_SECRET
TWITTER_ACCESS_TOKEN
TWITTER_ACCESS_STOKEN
```
