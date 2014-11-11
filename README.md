# Twilio for Alfred

This is a workflow for [Alfred](http://www.alfredapp.com/) that makes it easy to search [Twilio's](https://twilio.com) documentation.

## Installation

Installation is easy:

1. [Download this repository](https://github.com/phalt/twilio_alfred/archive/master.zip) and open the zip folder.

2. Double-click or open the twilio.alfredWorkflow file with Alfred.

3. Et viola! It should now be installed.

## Usage

Open up Alfred and use the following keywords:

```twiml {query}``` to search Twilio's [TwiML](https://www.twilio.com/docs/api/twiml) documentation.

The {query} value must be the name of a TwiML tag:

```
say
play
record
sms
dial
number
sip
client
conference
queue
enqueue
leave
hangup
redirect
reject
pause
message
```

or

```twilio {query}``` to search Twilio's standard REST API documentation.

The {query} value must be the name of a Twilio resource:

```
account
subaccounts
available-phone-numbers
outgoing-caller-ids
incoming-phone-numbers
applications
connect-apps
authorized-connect-apps
call
call-feedback
conference
queue
short-codes
message
media
recording
transcription
notification
```

Note that some list resoures are plural, and most individual resources are singular.

Have fun!
