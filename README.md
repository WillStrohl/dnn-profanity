# dnn-profanity
DNN CMS includes an administration feature that allows a website owner to load and filter out profane words and phrases.  By default, DNN doesn't assume any specific word or phrase to be profane or obscene, because it doesn't know anything about where and how it's being used.  For example, words that are profane in the US might be perfectly acceptable and maybe have a different meaning altogether in the UK.  Additionally, some websites might want to cater to and allow such words.  It's completely up to you.  

This project exists to help anyone load their DNN website with the most words that may be considered to be profane.  As of right now, it's only a SQL script that will load the words directly into the `Lists` table in your DNN database.  Immediately after applying these words, you'll be filtering for 1,800+ profane words.  

In the future, this project may or may not begin to include additional tooling to help non-technical people manage the profanity filter.  I guess it depends on you.  ;)  

# WARNING! 
This project and repository contains words and phrases that may be considered to be offensive to you and/or others.  Please do not use or contribute to this project if this may disturb or otherwise offend you.  

This list was originally obtained and based on the list found at the URL below.  It has since been iterated on, to include more words/phrases and exclude others that didn't make any sense.  

[Full List of Bad Words Banned by Google](https://www.freewebheaders.com/full-list-of-bad-words-banned-by-google/)

## Usage  
1.  Backup your database.  
2.  Copy the SQL script or download it.  
3.  Review all of the words that will be added.  Be sure to pay special attention to the ones that are commented out. You may want to include them.  They have been commented out due to ambiguity.  
4.  Execute the respective script against your DNN database.  

## Files  
* _Add-Profanity-List.sql_ - Use this file if you're executing the script using SQL Server Management Studio (SSMS).   
* _Add-Profanity-List.sql_ - Use this file if you're executing the script in DNN's SQL Console in the  persona bar.  
