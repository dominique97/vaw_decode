vaw_decode
==========

vawtrak\neverquest traffic decoder

Will process a pcap file that has vawtrak encoded data.

Change the fileName and outFileName to the input and output file of yyour choice (lines 502, 503)
Change the URL tests starting at line 342 to look for the url that your version of vawtrak is using for C2

Creates a comma separated file with the date/timestamp, source->destination IPs, url, and decoded data columns.
