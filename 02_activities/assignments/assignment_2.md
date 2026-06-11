# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did. 
      ```
      Viz 1: alluvial diagram, https://www.carniklirs.com/wp-content/uploads/2019/12/C_REP_Food_Course1_v5-9.png from https://datavizproject.com/data-type/alluvial-diagram/ 
      This is an example of a good visualization. 
        - aesthetic: the plot is pleasing to look at. the colors are simple and well contrasted, the viewers can easily understand what they stand for even without a figure legend. 
        - substantive: the data is accurately presented, with neutral language and no undue emphasis on any part of the data to push an agenda. 
        - perceptual: an alluvial diagram is well suited to present this data, as it clearly displays the proportion of gari that is wasted at each step along the food supply chain. 
        - cognitive load: load is low as the data, chart type and message are all simple to understand, so it is suitable for a general audience even if they have no expertise with the topic or chart type. absolute values are presented so no mental comparisons of the sizes of the bands are needed. importantly there is little crossover between the bands, which sometimes occurs in alluvial diagrams and can make it very confusing (when bands are constantly crossing over each other)
        - Gestalt principles: the two colors take advantage of the similarity principle, as they help the viewers group wasted and consumed gari easily. 

      Viz 2: chord diagram, https://github.com/bokeh/bokeh/issues/393 from https://datavizproject.com/data-type/chord-diagram/ 
      This is an example of a bad visualization.
        - aesthetic: the plot is generally nice to look at. there is quite a lot of overlapping and crossing over between lines that occurs, especially concentrated in the bottom right part, that can be confusing to viewers trying to trace the connection between state and president. 
        - substantive: it is accurately and honestly presented. the diagram is entirely factual and there is no biased narrative being pushed. 
        - perceptual: the viewer can easily understand the message being conveyed (which president is linked with home state during their campaign). 
        - Gestalt principles: does not appear to fulfill the principles well. There are two distinct and non-overlapping categories (presidents and states), but nothing is done to distinguish them and they are all on the same (circular) axis. There does not appear to be a sensible order, as some presidents are clustered together while some are interspersed with states. There is no figure legend and it is unclear whether the 4 colors stand for anything (it appears to just be assigned to president/state in order of appearance), so color does not help viewers group items either. 
        - Cognitive load: extraneous load is high with this diagram. aside from the issues with categories and colors, there is no indication whether the width of the bands mean anything (they don't, each band connecting a president-state pair has the same width), and the diagram is entirely exploratory with no explanations given (are there correlations between states and the political party of the president? has preferences for home states shifted with time?) 
        Overall it is unclear if a chord diagram is suitable at all for presenting this data. having two distinct categories on the same circle seems forced and contrived. a parallel sets/alluvial diagram would've been much easier to understand as it would much better represent the connection between two categorical variables. 


      ```
    - How could this data visualization have been improved?  
      ```
      Viz 1: 
        - it is not clear what the x axis is supposed to represent; for some bands it represents time (e.g. production -> postharvest handling -> consumer storage -> consumed by consumer) but for other bands it represents a breaking down of categories (e.g. the 'production loss' band is further split into bands that represent loss due to harvest, storage/spoilage, or the tuber being too small). labeling the x axis and standardizing what it represents would improve the plot 
        - although the color meaning is intuitive, it would still be best to have a figure legend to further reduce cognitive load (more explanatory)

      Viz 2: 
        - a figure legend plus a color scheme that represents something informative (e.g. political party of each president?) would be good 
        - distinguishing presidents from states would also be good, since they are two distinct and non-overlapping categories. e.g. states can be bolded so that viewers can intuitively distinguish the two groups. 






      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
