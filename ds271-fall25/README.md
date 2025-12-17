# Abstract: Detecting Structural Breaks in Marathon Performance: A Statistical Analysis of Course Modifications

This statistical analysis investigated whether a significant course modification creates a statistically detectable structural break in finish times, motivated by the significant 2018 NYC Half Marathon course revision. Since historical NYC Half Marathon data was unavailable, the study utilized the NYC Marathon Results dataset from Kaggle, focusing on the documented 1976 course change (from Central Park loops to all five boroughs). The methodology involved applying the Zivot-Andrews (ZA) Test, a classical structural break test designed to identify the timing of a single break. Initial testing was complicated because the 1976 break fell within the ZA test's required 15% endpoint trimmed region, which is necessary for asymptotic validity. However, by restricting the sample window to 1970–1990 to reposition the 1976 course change outside the trimmed area, the ZA test successfully rejected the null hypothesis (unit root, no break), detecting a break consistent with the documented modification. This analysis validated that classical structural break tests successfully detect regime changes in athletic performance data resulting from course modifications, underscoring the importance of careful sample selection due to the 15% endpoint trimming constraint for accurate break point positioning.

[Check out this notebook](DS271_Final_Presentation.ipynb)

<p align="center">
  <img src="banner_ds271.jpg">
</p>
