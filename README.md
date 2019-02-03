# Taboo Experiment

Repository for hosting JsPsych code for implementation of "Taboo" experiment (friends vs. strangers).

## Experiment details

*Number of players*: 4  
*Number of teams*: 2  
*Number of rounds*: ?  

### Important variables

For any given turn (and session), it is important to log:  

* Who is speaking (ppt id)  
* Who is guessing (ppt id)  
* Which team is playing (ppt or team id)
* Whether it is a **friend** or **stranger** round  
* Which deck is being used (e.g. *red*)
* Which cards have already been used from that deck  

All of these variables (see above) should be able to be entered on a browser page before advancing to the timed turn.

All turns should have the following **constraints**:

* 1 minute per turn
* 20 seconds per individual card  
* Pull only from relevant deck for that turn
* Pull only from *unused* cards from that deck (for that session)

For each **card**:

* Track whether card was won, discarded, or lost (ran out of time)


