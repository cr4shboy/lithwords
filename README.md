# lithwords
Lithuanian words | Lietuviški žodžiai

Lithuanian word so use with John The Ripper mangle rules
Rules are simple, while effective to crack most simple passwords, which, in most cases, uses vast majority of users

John Rules:
```
[List.Rules:TMall]
Az"[0-9]"
cAz"[0-9]"
Az"[0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
cAz"[0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
Az"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=][0-9]"
cAz"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=][0-9]"
Az"[0-9][0-9]"
cAz"[0-9][0-9]"
Az"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=][0-9][0-9]"
cAz"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=][0-9][0-9]"
Az"[0-9][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
cAz"[0-9][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
Az"[0-9][0-9][0-9]"
cAz"[0-9][0-9][0-9]"
Az"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=][0-9][0-9][0-9]"
cAz"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=][0-9][0-9][0-9]"
Az"[0-9][0-9][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
cAz"[0-9][0-9][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
Az"19[4-9][0-9]"
Az"20[0-1][0-9]"
Az"2020"
cAz"19[4-9][0-9]"
cAz"20[0-1][0-9]"
cAz"2020"
Az"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]19[4-9][0-9]"
Az"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]20[0-1][0-9]"
Az"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]2020"
cAz"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]19[4-9][0-9]"
cAz"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]20[0-1][0-9]"
cAz"[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]2020"
Az"19[4-9][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
Az"20[0-1][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
Az"2020[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
cAz"19[4-9][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
cAz"20[0-1][0-9][\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
cAz"2020[\-\+\_\#\:\.\!\@\$\*\%\^\&\=]"
```
