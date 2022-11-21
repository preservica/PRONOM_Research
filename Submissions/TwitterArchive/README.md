# Twitter Archive

## Format Name
Twitter Archive

## Extension
zip

## MIME-Type
application/zip

## Description
The Twitter service enables users to request an archive of all their Twitter data, which includes all tweets and related media that they have sent.

This is delivered in a ZIP file, which contains the raw data, and also a self-contained viewer (a html page with associated styling and scripts).

The README.txt in the ZIP says:

> The data folder consists of machine-readable JSON files with a .js extension containing information associated with this account. We’ve included the information we believe is most relevant and useful, including profile information, Tweets, Direct Messages, Moments, images, videos and GIFs attached to Tweets, Direct Messages or Moments, followers, following, address book, Lists created, a member of, or subscribed to, interest and demographic information that we have inferred, information about ads seen or engaged with on Twitter, and more.

> Each file contains detailed information about that category of data. To see this information, simply double click on one of the JSON files. Note that some information, such as the media shared via Direct Messages, is included in a folder instead of a JSON file. Separately, also note that some files may not contain any information if your account is not associated with any of the data they cover.

> The information contained in this archive reflects the state of the account at the time when the archive was created.

## Format Type
Aggregate

## File Format Identification Signatures
Main signature is just the ZIP file signature and an outline entry for the Twitter Archive. This requires subsequent container identification.

The container signature looks for three files within the archive; the README that is included, the html viewer file, and the js file containing the main set of tweets.

## Example

