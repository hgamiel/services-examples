services-examples
=================

Examples of third-party integration scripts for [Slack](https://slack.com/)

* [Nagios](https://github.com/tinyspeck/services-examples/blob/master/nagios.pl)
* [SVN](https://github.com/tinyspeck/services-examples/blob/master/subversion.pl)

[slack_room_message.pl](/slack_room_message.pl) is a simple wrapper for use from the command line, with
minimal dependencies. Use it like so:

    slack_room_message.pl -text="some event happened" -channel="#events" -username='a_bot'
    
**Hannah's Changes**
Only subversion.pl has been changed in this fork. It has been changed to have its payload formatted such that Slack will still accept it. The original services-examples project is extremely outdated and has been a stale repo for a long time.
