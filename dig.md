## dig ##

see all nameservers for a given TLD

    dig -t ns com
    dig -t ns io
    dig -t ns dk

see "authoritative answer" flag for a nameserver

    $ dig @a.gtld-servers.net com | grep flags
    ;; flags: qr aa rd; QUERY: 1, ANSWER: 0, AUTHORITY: 1, ADDITIONAL: 0
