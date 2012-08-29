GAE-webdiff
============

Google App Engine | small experimental app to display the diff between two pasted files or two gists, also provides a download of the resulting .diff  

- allows you to paste two files
- compare will display the diff
- once the diff is performed a download button will appear
- you can download and set the filename to download as
- in addition you can compare two gists by feeding the app their gist ids.

#### doing a gist compare  

currently limited to single file gists. `/webdiff/gist_id1-gist_id2`, for example `/webdiff/3482451-3487958`, will download the gists into the respective text areas and allow you to compare and download the diff. (currently no progress indicator connected to show you it is downloading, usually this happens quite fast but depends on GAE load)
