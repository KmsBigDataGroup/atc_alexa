![Logo for Air Traffic Control](https://github.com/ckuzma/atc_alexa/blob/master/misc/atc_large.png)

# atc_alexa
Air Traffic Control skill for Amazon Alexa

## Alexa Skill Deployment Status:
2016.11.17 @ 19:15 -- Submitted for certification

## Instructions
1. Clone the repo
2. Get an API Key for the Google Maps Geocoding API. Go here for more information: https://developers.google.com/maps/documentation/geocoding/start
2. Modify the key values in `config.py.example` with your credentials. Open in an editor for more detailed instructions. (If not deploying to AWS Lambda, no need to modify the Alexa App ID.)
3. Execute the AirTrafficControl class (`python atc.py`) to make sure everything is working. Modify line 72 of `atc.py` with different location strings to test how that works.
4. If you want to deploy using AWS Lambda and the Alexa Skills Kit, zip all of the files and upload. See the Amazon Alexa developer portal (https://developer.amazon.com/alexa) for more information on how to deploy.
