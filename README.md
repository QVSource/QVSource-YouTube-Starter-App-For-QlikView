YouTube-Starter-App
===================

A template application showing how to get started using the QVSouce YouTube Connector for QlikView.

1.5.1 - 08/07/12
----------------
* Added change log.
* Moved to YouTube Connector V2 (some column nane changes).
* Config now in separate Config.txt file.
* Moved to QVX format.
* Moved script into separate tabs/functions.
* Commented out keywords table for the time being as the value always appears to be empty in the API response (<media:keywords/>)
* Added check that QVSource is running.
* Added appId parameter to calls.
* Added to GitHub.

TODO
----
* Accumulate results into QVD file(s).
* Download comments using the new Async feature (http://www.qvsource.com/wiki/Synchronous-Asynchronous-And-Batch-Requests-Explained.ashx).
* Add sentimnent analysis.
* Add automatic pagination through blocks of insights results (because you can currently only specify a single time span of no more than 31 days).
* Add Channel Insights tables.
