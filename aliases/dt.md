This alias is used for tracking downtime. 

**Initial Setup**

Running this command without setting up the prerequisite svar will prompt a command which will set that svar. __Please adjust the command rather than running it as-is__. This will involve:
* Replacing "your-text-here" with some other words "like-this". Note the use of double quotes, and the lack of spaces.
* Deleting true/ or /false.

**Manual Adjustments**

These can be made via including a floating-point (decimal) number after the command:
`!dt -0.3` and `!dt 1`
Be advised that the default unit is in days, and I do not currently plan on supporting other units.

**Uvar or Cvar?**

When this alias is initially setup by your server admins, they decide whether downtime is tracked per-player, or per-character. The easiest way to tell which setting you are using is to run the command! If the name in the title belongs to your character, it's at the per-character level. If the name in the title belongs to your discord account, it's at the player level.
