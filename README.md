# Driver-fads
$hTimer = TimerInit() $nDiff = TimerDiff($hTimer) MsgBox(0, "", "msecs = " &amp; $nDiff &amp; @CRLF &amp; "nsecs = " &amp; ($nDiff * 1000000))
