# LinuxShell_ping
ping, quit, and suspend

ping 

    ✗ ping google.com
    PING google.com (172.217.160.110): 56 data bytes
    64 bytes from 172.217.160.110: icmp_seq=0 ttl=56 time=3.188 ms
    64 bytes from 172.217.160.110: icmp_seq=1 ttl=56 time=4.269 ms
    64 bytes from 172.217.160.110: icmp_seq=2 ttl=56 time=3.828 ms
    64 bytes from 172.217.160.110: icmp_seq=3 ttl=56 time=3.819 ms
    64 bytes from 172.217.160.110: icmp_seq=4 ttl=56 time=3.136 ms

ctrl + c

    ^C
    --- google.com ping statistics ---
    5 packets transmitted, 5 packets received, 0.0% packet loss
    round-trip min/avg/max/stddev = 3.136/3.648/4.269/0.429 ms
    
ping < dns name >

    ➜  ~ git:(react2) ✗ ping google.com
    PING google.com (172.217.160.110): 56 data bytes
    64 bytes from 172.217.160.110: icmp_seq=0 ttl=56 time=3.875 ms
    64 bytes from 172.217.160.110: icmp_seq=1 ttl=56 time=3.115 ms
    64 bytes from 172.217.160.110: icmp_seq=2 ttl=56 time=3.872 ms
    64 bytes from 172.217.160.110: icmp_seq=3 ttl=56 time=3.099 ms
    64 bytes from 172.217.160.110: icmp_seq=4 ttl=56 time=3.013 ms
    64 bytes from 172.217.160.110: icmp_seq=5 ttl=56 time=3.608 ms
    64 bytes from 172.217.160.110: icmp_seq=6 ttl=56 time=3.952 ms
    64 bytes from 172.217.160.110: icmp_seq=7 ttl=56 time=3.793 ms
    
ctrl + z

    ^Z
    [1]  + 2202 suspended  ping google.com
    ➜  ~ git:(react2) ✗ 

