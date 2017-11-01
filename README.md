# zip
Hi Krittika
  Thank you for your patience and help. Last night my real-time data was delayed even reached 1 hours. I solved the problem by shutting down the main node.Data time was slowly catching up.Temporary security.
    The detail of the incident is that Last day my colleague removed a node of 4 datastore which collapsed in October 25th and got a 70GB .dmp file in \DataStore\framework\runtime\tomcat. And then real-data was found delayed five minutes, and that was going to increase, even reached 1 hours when I arrived . I found many Error of GISDSSPTP3.SDMSA.GOV.CN/198.15.20.9:9320 in log of GeoEvent and there is no activity on disk at GISDSSPTP3 machine. Either description Tools or valid SpatialTemporal datastore on server need half an hour.And GISDSSPTP3 was the master node. It was so strange and so slow. So, I tried to close this node through closing the windows service of datastore, but the java process is still running. Then, the magic scene appeared that data time was slowly catching up. It solved temporarily. After the situation was stable, I started Datastore of windows service on GISDSSPTP3 machine. Up to now , everything is normal. But I don't know why. Could you help me to analyze please.
    The amount of data into datastore in seven minutes was 9.76MB with add and update. My GE log still has error information. Could you help me to analyze please?

ps: logs and part of data
( Last night == 2017.10.30 16:40)

Wish you happy！

Xu Danshi
