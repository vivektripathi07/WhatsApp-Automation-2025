This is a working model of scrapping contacts from a whatsApp group and sending the messages automatically.

I have used 2 approches for my extraction,

1. If you can extract the contacts from WhatsApp Web by inspecting the webpage, then you just copy the outerHTML and paste it in a txt file. Then run the "Group.ipynb" file.

2. If you dont want know how to inspect and extract, just run the "For_Group.ipynb"


Now for sending, the approach is very straight-forward,

Just have an input csv which would hold you contacts and run "send.ipynb".

All three codes are independent of each other have different utitlies and could be used as per requirements.

Another side note, this proogram would become unuseable if WhatsApp choses to update its HTML structure, in that case look for the current HTML structure and update the XPaths accordingly.