# mcasiano1.github.io
Web Design Homework - Web Visualization Dashboard (Latitude)

I built a dashboard with individual pages for each waether plot and a means by which I can navigate between them. These pages contain the visualizations and their corresponding explanations. I also have a landing page, a page where I can see a comparison of all of the plots, and another page where I can view the data used to build them.

**Website Requirements My website consists of 7 pages total, including:**

**A landing page containing:**

An explanation of the project. Links to each visualizations page with a sidebar containing preview images of each plot.

**I created four visualization pages, each with:**

A descriptive title and heading tag. The plot/visualization itself for the selected comparison. A paragraph describing the plot and its significance.

**I created a "Comparisons" page that:**

Contains all of the visualizations on the same page so I can easily visually compare them. I used a Bootstrap grid for the visualizations. The grid contained two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

**I created a "Data" page that:**

Displays a responsive table containing the data used in the visualizations. Includes a table with a bootstrap table component. The data I used came from exporting the .csv file as HTML using the Pandas tool, to_html, which allowed me to generate a HTML table from a pandas dataframe.

**The website, at the top of every page, has a navigation menu that:**

Has the name of the site on the left of the nav which allows me to return to the landing page from any page. Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page. Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
