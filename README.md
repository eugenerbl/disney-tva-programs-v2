# Disney TVA Programs
A summary of all programs aired by Disney Television Animation.

*Last Updated: January 10, 2026*


## About Disney TVA
**Disney Television Animation** (established December 5, 1984) is the animation studio that operates as the animation production unit for Disney Branded Television, a division of Walt Disney Television. This division is responsible for the creation, development, and production of animated television series, films, specials, and shorts.

Disney TVA has produced shows for major TV networks such as ABC and CBS, as well as for syndicated blocks such as “The Disney Afternoon” and “Disney's One Saturday Morning”. Today, Disney TVA primarily manages content for three TV networks (**Disney Channel**, **Disney XD**, and **Disney Junior**) and the **Disney+** streaming service.


## Variables

This database includes **102** programs that have aired or are currently broadcast by Disney TVA. This dataset will be updated periodically as shows premiere, end, and air new episodes.

Each row contains the following **10** variables:

**see Variable Notes for additional information*


| Variable      | Description |
| -----------   | ----------- |
| show_id        | Unique identifier. Shows are ordered by premiere date. |
| title         | Name of the show. |
| short_title	| A 3-5 character abbreviation for the title. Unique for every show.
| creator       | Main creator(s) or developer(s) of the show. Does not include producers or directors. |
| seasons       | Number of seasons. |
| episodes      | Number of episodes aired.* |
| primary_time   | Typical length of an episode, in minutes.* |
| premiere_date  | Air date of the show's first episode, in YYYY-MM-DD format. |
| finale_date    | Air date of the show's last episode, in YYYY-MM-DD format.* |
| channel	| List of channels that regularly aired new episodes at any point during the show’s run (see List of Channels). |


#### Variable Notes

- **episodes**: Count does not include feature films, television specials, or additional shorts (unless the program consists primarily of shorts).
- **primary_time**: Describes the length of a majority of the show's episodes. For most shows, this will be either 11 or 22 minutes long. However, some shows consist of shorts or segments much shorter than 11 minutes. These shows are assigned the value 5.
- **finale_date**: If the show is currently airing, this variable is set to December 31 of the current year ("2026-12-31", for example).


#### List of Channels
-	**Disney Channel**:  1983-Present
-	**Syndication Blocks**: The Disney Afternoon (1990-1997), Disney's One Saturday Morning (1997-2002), ABC Kids (2002-2011), Disney's One Too (1999-2003)
-	**ABC**: aired shows as part of syndication blocks
-	**CBS/UPN**: aired shows as part of syndication blocks; UPN was owned by CBS and replaced with The CW in 2006
-	**Toon Disney**: 1998-2009; includes Jetix (2004-2009); rebranded as Disney XD in 2009
-	**Disney XD**: 2009-Present
-	**Disney Junior**: 2011-Present; includes Playhouse Disney (1999-2011)
-	**Disney+**: 2019-Present; streaming service 


#### Specific Show Notes

- *Doug* aired a total of 166 episodes over seven seasons. The first four seasons were broadcast on Nickelodeon, while the last three aired on ABC. This database only includes the final three seasons (65 episodes) that aired during the show's run under Disney TVA.
- *Phineas and Ferb* was revived for a fifth season in 2025, a decade after the show originally ended. The database has been updated to include a new entry for the 2025 revival, with the premiere date indicating the start of the fifth season. The season and episode counts for this entry include the totals from the original run.


## More Information

If you believe there is inaccurate or misleading data, please leave a comment, and I'll make sure to write back!

This database and repository are protected under the [MIT license](https://choosealicense.com/licenses/mit/).
