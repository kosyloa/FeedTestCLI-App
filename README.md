# FeedTestCLI-App
----
!!! Remove quarantine after extracting(to avoid problem with  "can’t be opened because the identity of the developer cannot be confirmed"):
```sudo xattr -r -d com.apple.quarantine folder_with_app```

----

1. [CLI-app](https://github.com/kosyloa/FeedTestCLI-App/blob/main/builds/FeedTestCLI%202023-02-17%2010-44-56.zip)

- supports address
- supports only one symbol
- supports only quote, time and sale
 
Usage: FeedTestCLI host:port event symbol <br>
where<br>
&emsp;host:port  - The address of dxFeed server demo.dxfeed.com:7300<br>
&emsp;event      - One of the {Quote,TimeSale}<br>
&emsp;symbol     - IBM, MSFT, ETH/USD:GDAX,  ...<br>

2. [CLI-app](https://github.com/kosyloa/FeedTestCLI-App/blob/main/builds/FeedTestCLI%202023-02-19%2011-48-06.zip)

- event counter
- remove NSDate for time fields
- remove runtime initialization of events
 
Usage: FeedTestCLI host:port event symbol <br>
where<br>
&emsp;host:port  - The address of dxFeed server demo.dxfeed.com:7300<br>
&emsp;event      - One of the {Quote,TimeSale}<br>
&emsp;symbol     - IBM, MSFT, ETH/USD:GDAX,  ...<br>

3. [CLI-app](https://github.com/kosyloa/FeedTestCLI-App/blob/main/builds/FeedTestCLI%202023-02-19%2015-05-06.zip)

- listener counter, average number of events
 
Usage: FeedTestCLI host:port event symbol <br>
where<br>
&emsp;host:port  - The address of dxFeed server demo.dxfeed.com:7300<br>
&emsp;event      - One of the {Quote,TimeSale}<br>
&emsp;symbol     - IBM, MSFT, ETH/USD:GDAX,  ...<br>

