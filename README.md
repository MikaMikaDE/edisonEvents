# edisonEvents
List of future edisonformat events.


## Json keys

Note that objects must be listed in chronological order.
Don't worry about deleting old events. The site won't display them at all (as long as everything is listed chronologically).

### "Name"
The content isn't especially important, but be consistent with other names.
If it's a shop, just the shop name will suffice.
Note that one line is about 12 characters long on both mobile and desktop. 
Try for 1 line of text if possible. Sometimes a 2nd line is unavoidable.

### Icon
- "FL"    - Format Library background image
- "RBET"  - Substitoad background image
- "DDEV"  - Deck Dev background image
- "Other" - Quickdraw background image
- "KONAMI"- Konami background image. Used for Ultimate Time Wizard. 
For very large/special events (like the ultimate time wizard) you can contact me to make a new one.
Don't think i'll be adding any/many more.

### Date
**MUST** be in this format: `January 1`. 
Do not use"Jan 01" or "1st Jan" etc, else the "days until tournament" won't calculate.

### Entry
Can be any of
- "Free"
- "Paid Entry"
- "{some amount, including currency symbol}" eg "$24.50"
- If it's truly unknown, you can write nothing (still needs the double quotation marks) `" "`.

### Location
Can be any of
- "Online"
- "CITY STATE"   eg "Orlando, FL"
- "{Name of the Shop itself} eg "Big Boy Gaming". You can include city name at the end of this, eg "Shuffle Deck Gaming Rome"

### Link
Either a discord link (make __sure__ that it is not a link that expires. When making the link you must click "Edit invite link", else it will expire.
Or a link to the shop / facebook page - anything that lets the user quickly get to where they need to be to sign up.

### A note on Json files
All objects (things inside {curly braces}) **must** be separated by a comma. 
The last object must not have a comma after it.

## Example

{

"Name":     "EWCQ 4",

"Icon":     "FL",

"Date":     "August 5",

"Entry":    "Free",

"Location": "Online",

"Link":     "https://discord.gg/formatlibrary"

},

{

"Name":     "Super Mika Tournament",

"Icon":     "Other",

"Date":     "August 10",

"Entry":    "Paid Entry",

"Location": "Mika's Basement",

"Link":     "www.mikasbasement.com"

}
