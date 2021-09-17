## My resume

This resume was built with Nick Strayer's 
[`datadrivencv`](https://github.com/nstrayer/datadrivencv) package.
I made a few adjustments during the set-up:

- Installing the package on `R` version 4.1.0, I encountered an error message
related to not finding package `icon`.
This issue has been fixed in a few forks, 
none of which has been not merged into the main branch.
I ended up installing one of the [forks](https://github.com/csthiago/datadrivencv).

- Manually change line 32 of `cv_printing_functions.r` from
`googlesheets4::sheets_deauth()` to `googlesheets4::gs4_deauth()`
following this [discussion](https://github.com/nstrayer/datadrivencv/issues/68).

- To feed data into the resume from a googlesheet,
I need to get the "editor" share link of the googlesheet.

The first two adjustments are only temporary as I expect 
the upcoming package update will fix those issues.

## Reflection

As an imposter syndrome survivor,
working on my resume has always been anxiety inducing.
Not to mention that fiddling with tight boxes and font size in a word document
are both tedious and error prone.
Surprisingly, when I migrated to this version,
I did not feel so much anxious as excited.
Listing my past experiences is no longer showing-off,
merely tabulating data points.
What a liberating idea!

## TODOs

I switched to the current version over an evening and could not spend much time
polishing it.
There are still lots of room for improvement.

[ ] Replace the footnotes with hyperlinks in the pdf output.
This seems a bug to me. Need to investigate.

[ ] Add side bars to some sections as highlights.

[ ] Create a few versions highlighting different types of experience.
Need to decide how to present them.

