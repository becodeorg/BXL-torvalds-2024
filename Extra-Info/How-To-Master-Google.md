# How To Master Google

Here are a couple of tips to master your Google searching skills:

## Search in English

English is **_the_** language of the world.  
The chance that you find something useful in dutch, french, or your mother tongue regarding your search is way smaller than in English.

## Use quotation marks and remove specific info

Using quotation marks in Google search will search for those EXACT words on websites. This can be very handy when looking for error codes. But always do a first search without quotes, sometimes you get lucky.

For example, if you get the following error message:

```
Warning: Cannot modify header information - headers already sent by (output started at /path/to/geeklog/public_html/config.php:581) in /path/to/geeklog/public_html/system/lib-sessions.php on line 180
```

You could copy paste that into the Google search bar, break it down into the core words, remove the stuff that is specific to your files,
wrap it in quotation marks and look it up. Your Google search would look like this:

```
"Warning: Cannot modify header information – headers already sent by"
```

**Advanced tip**: you can also replace the non-relevant or user-specific part of the debug message with a wildcard (\*). Example:

```
"Warning: Cannot modify header information - headers already sent by (output started at *) in *"
```

## Searching on a specific site

Type "site:" followed by the url of the site you wish to search on.
For example you could search the above line of text and limit results to stackoverflow.com.

Example:

```
site:stackoverflow.com "Warning: Cannot modify header information - headers already sent by"
```

## Add the language/framework you use

If you are looking to solve issues with your coding always try to write in front of the search the name of the language you are using. That will limit results to that language.

Example:

`php array push`  
`javascript array push`  
`sql joint tutorial`  
`react why does it not refresh`

## Improve your search step by step

Improve your google search step by step and come closer to the perfect answer gradually to learn more about the process. If your first search gives too many and too generic results, add some keywords.

Example:

```
php array
php array push
php array push many elements
```

## What important words (keywords) would the website you are looking for use?

Don't use a fully formed question, delete prepositions and punctuation, use a professional tone.  
For example, instead of `I'm looking for a job in Antwerp` try to serach `Jobs developer Antwerp`.

## Other fun tips

### What does Google know about my site?

```
site:pixeline.be
```

### Who is linking to my site?

```
link:yoursite.be
```

### Find related sites

```
related:pixeline.be
```
