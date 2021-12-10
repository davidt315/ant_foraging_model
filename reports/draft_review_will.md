# Draft Review: [A Color Extension to a String Art Algorithm](https://github.com/YA9/complexity-project-2/blob/master/reports/draft_report.md)
Will

## Question
**What is your understanding of the experiment the team is replicating?  What question does it answer?  How clear is the team's explanation?**

The author is trying to replicate a type of string art that converts images into a series of discrete lines that stretch across a canvas. It is pretty clear from the abstract what the goal of the project is and the extension: using multiple string colors to more accurately recreate the image.


## Methodology
**Do you understand the methodology?  Does it make sense for the question?  Are there limitations you see that the team did not address?**

The methodology makes some sense. Currently the main alogirthm mentioned is find the darkest path between two nails, laying a string, and repeating until you reach the string limit. It would be nice to see a little more detail about the alogrithm implementation.

## Results
**Do you understand what the results are (not yet considering their interpretation)?  If they are presented graphically, are the visualizations effective?  Do all figures have labels on the axes and captions?**

It seems like the results will be comparing images made with the algorithm versus their original counterpart. So far there are no Figures in the draft so I can't comment on how effective the results are.


## Interpretation
**Does the draft report interpret the results as an answer to the motivating question?  Does the argument hold water?**

So far there is not a result section.

## Replication
**Are the results in the report consistent with the results from the original paper?  If so, how did the authors demonstrate that consistency?  Is it quantitative or qualitative?**

It seems like the alogrithm from the paper has not been completely reproduced yet.

## Extension
**Does the report explain an extension to the original experiment clearly?  Can it answer an interesting question that the original experiment did not answer?**

I think using different color strings will be a really interesting extension. It does seem, along with the replication, like a very challenging extension to implement. I'm not quite sure how the string algorithm works in detail so this may not work but a potentially easier way to implement colored string art: seperate a color image into three black and white images (one for each color channel), apply the original algorithm to each photo, change the color, and recombine the images. 

## Progress
**Is the team roughly where they should be at this point, with a replication that is substantially complete and an extension that is clearly defined and either complete or nearly so?**

I'm not sure where the author is in their implementation of the replication. Given the challenge, it's understandable that they haven't finished the replication part of the assignment. While it would be nice if they were further along, it's final seasons and everything is a time crunch.

## Presentation
**Is the report written in clear, concise, correct language?  Is it consistent with the audience and goals of the report?  Does it violate any of the recommendations in my style guidelines to an external site.?**

Overall the report is not too verbose which I really like. I think the structure of the report is overall good. The author may want to shift the annotated bibliography to the last section and reduce the description for each referenced source.

## Mechanics
**Is the report in the right directory with the right file name?  Is it formatted professionally in Markdown?  Does it include a meaningful title and the full names of the authors?  Is the bibliography in an acceptable style?**

All of the mechanics seem to be correct for their paper.
