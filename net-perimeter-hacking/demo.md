- discuss how to get slowlowris
- up arrow to git command
- ls the slowloris folder
- switch to apache site...refresh to see it's up to speed
- up arrow to slowloris command
- discuss the command 
- return to apache and show its really not slowlorising it.
- bring up hping3 command and discuss
    - c is packet count
    - d is data size
    - S is syn flood
    - w is window size
    - p is port 80
    - --flood is fire at will as fast as you can...no replies
    - --rand-source says send random source addresses to the target of 192.168.0.176
- Refresh browser see if there's latency
### Mod 3
1. Have wireshark open
2. Scroll to http session
3. Right click and select follow stream
4. Identify the get http command and the servers response
5. click back
6. Expand Transmission control protocol
7. Call out three areas to focus on as we go through the http stream...TCP Segment length, Sequence Number, and acknowledgement number
8. Identify the raw sequence number.
9. Show where we can toggle from relative to just raw...relative makes it easier for us, but the real number is raw
10. Now show the sequence numbers and tell the learner to be prepared to calculate the next number based on both relative and raw
11. switch back to relative to do easier math
12. Call out after three way hand shake how you can see the sequence and acknowledgements in the main window
13. step to the fourth Get, which is we saw when we followed the stream.
14. Call out the TCP segment length is 480 and the next sequence number is 481
15. Step through the remaining
16. Make sure to the learner is prepared to do simple math with the relative sequence numbers v the raw sequence numbers...the math is the same.