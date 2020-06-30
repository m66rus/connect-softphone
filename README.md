This GitHub repositry is for **Amazon Connect (AWS)**

Please feel free to use and provide feedback how it has helped and what updates
could be made.

These are updates to the standard CCP v2 softphone to over come specific issues 
when agents work at home or even in the office and do not change their state or logoff when they should

Also the ability if they close the window down before logging out, Conenct leaves their state as signed
in and therefore could route calls to them.

There will be flavours of the softphone so you can pick and chose the ones that will help.

```javascript
 var timeoutInMiliseconds = 14400000;
```
 is where you define in milliseconds the inactive time


