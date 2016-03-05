# global_on_windows
Use global on the windows system and parse c#

1. the global would be better installed at the directory which has no space in the name
 d:\global\

2. environment variables
set GTAGSCACHE=17179869184          
set GTAGSCONF=d:\global\etc\gtags.conf
set GTAGSLABEL=pygments

3. gtags.conf
:gtags_parser=XSLT\:d./global/etc/pygments-parser.dll:\

4. run it
gtags -v --gtagsconf d:\global\etc\gtags.conf  --gtagslabel pygments --statistics
htags --suggest3



