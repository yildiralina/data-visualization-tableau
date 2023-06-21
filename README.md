# data-visualization-tableau
Tableau

<ul>
  <li>Measures get aggregated, and dimensions specify the level of granularity.</li>
  <li>To remove aggregation (to plot every single row of a data set separately on a chart): Analysis -> Aggregate Measures (unchecked) -> Shape.</li>
  <li>Instead of switching aggregation off, we can introduce a dimension that will change the granularity level of our dashboard and, therefore, affect the aggregation. So, we're going to take Gender, and we're going to drag it on to Colour. And right away, you can see here that we have twice as many dots. We have made the chart more detailed by adding a new dimension. We can introduce more dimensions to increase granularity even further. Let's take Age and drag it into shape.</li>
  <li>You don't want to affect the visual, like colouring or other parts of your dashboard, but you want to increase the level of granularity. Let's take Age, and instead of dragging it on to Shape like we did last time, let's put it into Detail. Now you can see that the shapes haven't changed, but the granularity of the chart has changed. This option allows you to add dimensions and measures to your dashboard without affecting the visual representation but the granularity level. It's for you to control at which level the aggregation will happen.</li>
  <li>As you can see from the colour legend here, men are represented in blue circles, and women are represented in orange circles. What happens if you want to specifically interrogate one of these genders and understand what's happening there? All you have to do is go to your colour legend and click on the gender you're interested in. If you're interested in looking at women, click on women, and there you go.</li>
  <li>If you are <strong>highlighting</strong> by, for example, a province, ensure your result graph has granularity on the same level. Each dot on the graph should represent only one province, not a combination of provinces such as AB + ON + BC. Instead, use only one province at a time, such as AB / ON / BC.</li>
</ul>
