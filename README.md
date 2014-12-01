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

The {query} value must be the name of a TwiML Verb:

```
client
conference
dial
enqueue
hangup
leave
message
number
pause
play
queue
record
redirect
reject
say
sip
sms

```

or

```rest {query}``` to search Twilio's REST API (https://www.twilio.com/docs/api/rest) documentation.

The {query} value must be the name of a Twilio REST document resource:

```
account
applications
authorized-connect-apps
available-phone-numbers
call
call-feedback
change-call-state
conference
connect-apps
credential-list
domain
incoming-phone-numbers
ip-access-control-list
making-calls
making-calls-sip
member
message
media
notification
outgoing-caller-ids
participant
queue
recording
sending-messages
short-codes
subaccounts
transcription
usage-records
usage-triggers
```

Note that some list resoures are plural, and most individual resources are singular.

or

```client {query}``` to search Twilio's Twilio Client (https://www.twilio.com/docs/client) documentation.

The {query} value must be the name of a Twilio Client document resource:

```
android
capability-tokens
errors
ios
twilio-js
```

or

```rrk {query}``` to search Twilio.org's Rapid Response Kit GitHub (https://github.com/Twilio-org/rapid-response-kit/) repository.

The {query} can be any value, but for best results use Twilio Rapid Response Kit Tool names (see below) or other Twilio keywords (see above).

```
autorespond
broadcast
conference
forward
noticeboard
ringdown
simplehelp
survey
town_hall
volunteer
```

Have fun!
