Fest
====


Overview
========

You'll need to install yeoman [http://yeoman.io/]
You might need to do a bower update [http://bower.io/] inside fest-web

Run the web solution by cd'ing to the fest-web folder and running 'grunt serve'


Data 
====

1. Bands

Id
Name
Description
Picture
SampleSong
Facebook
Twitter
Spotify

2. Venues

Id
Name
Description
Location - Lat/Long
VenueType - Music / Food / Booze

3. Schedule

Id
VenueId
BandId
Start Time
End Time

4. User

Username
Name
Location
Description
Picture

5. User Schedule

User
Id

6. Friend Request

OriginUser
TargetUser
Occurance
Accepted

7. Friends

User
FriendUser


8. Messages

User
Message 
Occurance



