rtmp-sniff
==========

Bash script to redirect rtmp traffic using iptables. Useful for sniffing streams with rtmpsrv/rtmpsuck. To be run as a 'sudoer', if you don't use sudo, you should know enough to make the adjustments for your system.

**Example usages**

Redirect rtmp traffic for sniffing.
 
    rtmp-sniff start

Undo redirection, restoring rtmp port to normal.

    rtmp-sniff stop
