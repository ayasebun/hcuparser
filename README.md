### Usage

This script must be executed with `--run` in order to successfully execute. Otherwise you'll receive rainbow ASCII art in your terminal buffer. The script's only intended purpose was to obtain information based on CTM-EM, CTM-S, CTM-A software with log information collected by a user. Generic information such as operating system, system specs, entire log directories.

### A bit of history -- This script was made out of spite.

Allow me to explain. I was tested constantly during my time here, and I really missed being in a terminal the entire time. My only hope was to live in my WSL terminal. As a result I'd show my work through various bits of `grep` and `awk` output. I then later learned that all of the testing that was done against me was for naught, as Notepad++ was the preferred... "log parser"... at this establishment.

By about the fourth time that I heard "You know, Notepad++ would be faster", my inner monologue decided that was the final "JUST DO A `grep -R`, WHAT DO YOU MEAN." This script was then born.

Now:
1. Could this have been done in a different language?

    ABSOLUTELY. Though I wanted to prove a point

2. Did this increase your productivity (during your time there)?

    ABSOLUTELY. After you get one REALLY nasty `grep` or `awk` out, the feeling is so good. Rather than keeping it in a personal wiki (like I used to do), I threw it in there instead. I gave the output colors for mental stimulation.

3. Okay but why?

    See Question 1.

This is no longer in use. I was not at that establishment for long. This was how I kept sane, and everything about this script made me really happy.

Of note there is a long section with ASCII Art. That is intentional -- I was snooped on constantly and I really wanted to drive home the point of "stop testing my bash if you can't run a script yourself". This happened often.

Thank you for listening to my rant. I will never update this again, but I do look at it occasionally because I did some very funny stuff in this script that brings a tear to my eye.


### Of Note

If there's something that you would like to rip from this script then there are some disclaimers that I would like to make

- The loop that I made to print the ASCII Art caused my work PC to crash. Personal PC? No issue. Personal-VM-as-strong-as-a-Nokia-flip-phone? No issue. Just that one crashed for some reason.

- The loop that was made to make the progress spinner did not work well on the work machine either, though I kept it in because the way that it would break my output made me laugh sometimes.

Do with that what you will
