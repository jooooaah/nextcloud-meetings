# nextcloud-meetings
Nextcloud-Plugin for organizing meetings with highly embedding other plugins

# Imagine
Your team wants to organize a meeting. Now, someone has to set up the meeting, defining the date, the (virtual) place and has to invite participants. The next steps are collecting the items of the agenda, sort them, weight them and perhaps assign a responsible person to them. 

Now, the meeting is happening. You have someone for moderation, someone for logging and in ideal circumstances your team produces remakable decisions, information, and assigns tasks to different people. 

Afterwards, several things are usually done: the protocol is sent to everyone who is affected by it, it is archived, content from it is forwarded to various offices. It can be publicly viewable or only available to certain target groups.  

# Goal
Now imagine there's an app for Nextcloud that helps you make it all happen in a highly integrated way in your instance. 

- [Calendar](https://github.com/nextcloud/calendar) takes care of the timing placement and inviting the [appropriate](https://github.com/nextcloud/bookmarks) people. 
- In case of a virtual meeting [Talk](https://github.com/nextcloud/spreed) gives the needed vieoconferencing technology  
- The individual agenda items are entered directly into the app by the authorized people, perhaps linked to appropriately relevant files.
- Info points, e.g. [bookmarks](https://github.com/nextcloud/bookmarks) can thus be made available to everyone in advance and then, nicely, take up hardly any valuable meeting time later on.
- Other team members can comment and ask questions - perhaps clarifying some things in advance or showing the importance of the item for the meeting.
- Before the meeting, the moderator can weight the items on the agenda, put them in chronological order, and rearrange them if necessary. 
- [Logging](https://github.com/nextcloud/text) takes place directly in the app under the respective item and can be divided into different categories: for example, info point, immediate [announcements](https://github.com/nextcloud/announcementcenter), resolution,[task](https://github.com/nextcloud/tasks),... 
- If the log can be followed live by the others, a later approval may be unnecessary, since an intervention can happen immediately.  
- [Tasks](https://github.com/nextcloud/tasks) takes care of correctly assigning tasks to people - maybe [Deck](https://github.com/nextcloud/deck/) comes (live) into play?
- The minutes end up as a PDF document in the shared group folder or in a [mail](https://github.com/nextcloud/mail), decisions perhaps end up in a database, public parts of the minutes are forwarded to interested people via other apps.

# Annotation
I know that this kind of meeting and logging seems a bit anachronistic in the age of agile working. But I am sure that there are many teams that still coordinate in a similar way and for whom this would be a huge relief - and perhaps also a step towards more dynamic work. 

A lot of inspiration from [minutes.io](https:://minutes.io) and [Humhub Meeting](https://www.humhub.com/de/marketplace/meeting/) - both are precious tools, but an integration into an environment like Nextcloud really gives the boost
