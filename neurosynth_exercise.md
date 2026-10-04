## Neurosynth exercise (for Brain Networks lecture)

1.  Break into your thread teams.

2.  Each team should identify two brain areas that are relevant to their thread project.

3.  Use your favorite LLM to identify some anatomical coordinates for the areas.  Here is a suggested prompt:

> Give me two plausible MNI152 seed coordinates for [brain region] in the same hemisphere, specifying hemisphere and X, Y, Z in millimeters, for exploration in Neurosynth. Use a published atlas or study, link the source, and distinguish sourced coordinates from estimates.

If you have a specific hemisphere in mind, then modify the prompt to ask for that specifically.

4. Go to the [Neurosynth.org locations page](https://neurosynth.org/locations/) and enter each of the two locations for one of the seeds.  It should show the "functional connectivity" map (based on resting connectivity) by default (you should see an eye without a cross in the panel to the right next to the "functional connectivity" label).
   - Identify one similarity and one difference between the maps for the two coordinates for the first area, then do the same for the second area.
   - Then select a coordinate for each area to use in the next step.

6. Enter an MNI coordinate for one of the regions into the coordinate at the top of the page, and then enter a coordinate for the other region into the x/y/z locator below the images.
   - Does the second region fall within the displayed positive connectivity map of the first? Does your answer change when you adjust the display threshold?

8. Toggle the "meta-analytic coactivation" flag to the right of the images for each of your areas.
   - How similar are the resting connectivity and meta-analytic coactivation patterns for the area?  Identify one similarity and one difference.
   - How does the result change if you use the 
  
9. For each of the areas, explore the associated function terms using the "Associations" tab.
    - Are your project concepts reflected in the terms associated with the seed’s network? 
  
10.  Go to the [terms-based meta-analysis tool](https://neurosynth.org/analyses/terms/) and enter some terms that are relevant to your thread.
    - How do the results differ between the uniformity test and association test when you toggle the two analyses in the right panel?

12. Find a peak location from one of the term maps, and enter it on the locations page, and then look at the associations.
    - Are there any surprising associated concepts?
