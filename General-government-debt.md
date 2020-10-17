
#### The government debt bar chart
<iframe src="https://data.oecd.org/chart/65F5" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/65F5" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>

#### The grid of line charts
<div class="flourish-embed flourish-chart" data-src="visualisation/3749433" data-url="https://flo.uri.sh/visualisation/3749433/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### Self-designed chart
<div class="flourish-embed flourish-heatmap" data-src="visualisation/3756083" data-url="https://flo.uri.sh/visualisation/3756083/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### Comparison of three charts

<table>
    <tr>
      <td>Type of Chart </td>
      <td>Advantages</td>
      <td>Disadvantages</td>
    </tr>
     <tr>
      <td>Bar Chart  </td>
      <td>1. Easy to compare data among different countries.    <br>2. Simple and clear. </td>
      <td>1. Not able to show data from different years at the same time, hard to see trends throughout the years.</td>
    </tr>
     <tr>
      <td>Grid of lines </td>
      <td>1. Simple and intense.   <br> 2. Able to show multiple information in one big chart (the GDP debt ratio of a number of countries and years).</td>
      <td>1. Data are separated into each grid, hard to make any close comparison.</td>
    </tr>
     <tr>
      <td>Heat Chart </td>
      <td>1. Easy to see trends in the whole chart(both countries and years). <br> 2. Provide a perceptual and recognizable understanding of data through color.</td>
      <td>1. Not very precise on information(since it relies on color, more like overall sense) <br> 2. Good color is hard to choose.</td>
    </tr>
</table>


All the data used in the above charts come from [The Organization for Economic Co-operation and Development](https://data.oecd.org/gga/general-government-debt.htm)
In conclusion, all three charts have their own pros and cons. The Bar chart is the most simple and classic chart among them. It can be used to give a relatively precise interpretation of the data. For example, when we look at the bar chart on this page, it's easy to figure out, in one certain year, which country has the highest/lowest debt-to-gdp ratio. We can also have a sense of how each country's ratio differs from each other (e.g. A is twice as B). But it's hard to make comparison/seek trends across different years through one bar chart. Grid of lines is good at this. Since there a lot of different countries to explore across a number of different years, grid chart can arrange multiple small charts into one big grid so that we can visualize the debt-to-gdp ratio easily across a number of countries and years. But at the same time, since all the lines are separated into small grids, it's hard to make close comparison among two random lines. 

So, our goal is to focus on country, year, debt-to-gdp ratio all at the same time. We have to show all three types of information on a two-dimensional chart. This is where a heat chart can be of great use. Besides X and Y axis, we can additionally use color to represent the third type of information. To make the heat chart more understandable, I sort the data so that countries with higher debt-to-gdp ratios will appear in the upper part of the chart. The overall color trend will then be dark(up) --> light(down). As I mentioned above, one disadvantage of heat chart is that it provides us with more overall sense. But with the help of flourish's "popup" function, we can make up for that. If the viewer wants to see precise data about the ratio, it can just move the cursor to a certain position to look for the information. Considering all these facts, I feel a heat chart might be a good choice to show changes in government debt over time for different countries and thus further reflect the impact of past government deficits.

[Back to homepage](/README.md)
