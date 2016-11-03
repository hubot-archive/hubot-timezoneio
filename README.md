# hubot-timezoneio

Hubot interface for timezone.io

See [`src/hubot-timezoneio.coffee`](src/hubot-timezoneio.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-timezoneio --save`

Then add **hubot-timezoneio** to your `external-scripts.json`:

```json
[
  "hubot-timezoneio"
]
```

## Sample Interaction

```
user1>> hubot tz
hubot>> 
[Thu 03:59PM -0700 PDT   America/Los_Angeles] Amy, Andy, Brian, Caryn, Christina, Daniel, Daniel Siemaszkiewicz, Emily, Hamish, Karinna, Katie, Michael, Mike Eckstein, Nicole, Spencer Lanoue, Sunil, Tyler
[Thu 04:59PM -0600 MDT   America/Denver     ] Darcy, Matt Allen, kevan
[Thu 05:59PM -0500 CDT   America/Chicago    ] Bonnie, Carolyn, Courtney Seiter, Harrison Harnisch, Jordan Morgan, Phil
[Thu 06:59PM -0400 EDT   America/New_York   ] Adam Farmer, Alex, Arielle Tannenbaum, Dan Farrelly, David, Hailley, Jenny, Joel, Julia, Julian, Kelly, Leo, Patrik, Pioul, Ross, Roy, Super, Tigran, Todd Balsley, Tom
[Thu 07:59PM -0300 PYST  America/Asuncion   ] Humber
[Thu 10:59PM +0000 GMT   Europe/London      ] Ash Read, Colin, Danny Mulcahy, Dave C, Dave O, Hannah, James, Joe, Juliet, Melissa Alvarez, Mick, Steve Dixon, Tom Dunn
[Thu 11:59PM +0100 CET   Europe/Paris       ] Boris, David Gasquez, Deborah Rippol, Federico, Ivana, José, Lorenz, Marcus, Max , Mike, Rodolphe Dutel, Åsa
[Fri 12:59AM +0200 SAST  Africa/Johannesburg] Niel de la Rouviere
[Fri 04:29AM +0530 +0530 Asia/Colombo       ] Adnan
[Fri 06:59AM +0800 SGT   Asia/Singapore     ] Alfred, Eric, Octa, Stephanie, Steven
[Fri 08:59AM +1000 AEST  Australia/Brisbane ] Paul
```
