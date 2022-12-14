
Bugs to report 2022.12.13 (Full listing)

System-wide

Ubuntu e# bug
Known to affect:
Operating Systems
    • Ubuntu 20.04 (Dell XPS 13)
    • Ubuntu 22.04 (System76 Pangolin)
    • Ubuntu 22.04.1 (System76 Pangolin)
Programs
    • Gedit
    • GNOME Calculator
    • LibreOffice Writer
Description:
This bug will occur `<instance>` and will prevent any input, instead showing the characters e# with an underscore. I originally thought it lasted for the rest of the session, but it turns out it can be mitigated without restarting. I have lost work in the past, and would love to have known I could have mitigated it.
Steps to reproduce:
    • Unknown
Steps to mitigate:
1. Emoji menu
    • a. Open a program capable of inserting Emojis
    • b. Open the Emoji menu (inserting an emoji is optional)
    • c. Fixed for now
2. Simple restart
    • a. Restart your computer
    • b. Hope it doesn't come back within 5 minutes

Ubuntu Appearance settings bug 2022
Known to affect:
Operating Systems
    • Ubuntu 22.04 (System76 Pangolin)
    • Ubuntu 22.04.1 (System76 Pangolin)
Programs:
Not counting programs affected by changing from light to dark mode

    • GNOME/Ubuntu Settings
    • Ubuntu Core
    • Gedit
Steps to reproduce:
Appearance menu in Ubuntu 22.04 automatically changing upon opening the tab (if light mode is enabled, it will switch to dark mode until manually fixed, or escaping the tab and opening it again, and vice versa) and resetting the appearance preferences for Gedit
Steps to mitigate:
1. Reconfigure settings
    • a. Change the lighting theme back to what you prefer
    • b. Reset the appearance preferences in any affected program
2. Don't
    • a. Don't go to the appearance menu

