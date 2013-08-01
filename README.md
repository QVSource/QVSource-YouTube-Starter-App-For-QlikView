YouTube Starter App
===================
This is a starter QlikView application showing how to get started using the [QVSource YouTube Connector](http://www.qvsource.com/wiki/YouTube-Connector-For-QlikView.ashx) for QlikView. 

If you are a QlikView + QVSource user you can simply click the ["Download ZIP"] (https://github.com/QVSource/QVSource-YouTube-Starter-App-For-QlikView/archive/master.zip) button on GitHub to grab this application.

The content below is copied from the change log in the first tab of the load script.

1.5.1 - 08/07/13
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
Some ideas which would improve this application.
* Accumulate results into QVD file(s).
* Download comments using the new Async feature (http://www.qvsource.com/wiki/Synchronous-Asynchronous-And-Batch-Requests-Explained.ashx).
* Add sentimnent analysis.
* Add automatic pagination through blocks of insights results (because you can currently only specify a single time span of no more than 31 days).
* Add Channel Insights tables.
