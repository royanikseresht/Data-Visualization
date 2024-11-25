## Case study 3: Data visualisation

#### Pay gap 1997–2017

Completed the visualisation defined in `pay-gap-1997-2017.js` to create
a line graph representing the pay gap between female and male
employees over time.

1. The raw data:
   `./data/pay-gap/all-employees-hourly-pay-by-gender-1997-2017.csv`.

2. In the `for` loop in the `draw()` method extract the relevant data
   from each table row and store it in the `current` object.

3. Completed the `mapPayGapToHeight()` method. Look at how `mapYearToWidth()`
   works.
   - Check that the y-axis tick labels are drawn correctly.

4. Completed the `line()` function in the `draw()` method to plot the
   pay gap over time. You will need to use both `mapYearToWidth()` and
   `mapPayGapToHeight()` methods.

#### Climate change

Completed the visualisation defined in `climate-change.js` to create a
line graph with gradient fill background representing the change in
the Earth’s surface temperature.

1. Using the `mapTemperatureToColour()` method set the `fill()` in the
   `draw()` method. You need to pass the current temperature to this
   method to get the correct colour.

2. Completed the `rect()` function below the `fill()` to create a
   gradient effect background (rectangles spaced evenly across the
   x-axis – one rectangle per year). All of the values you need are
   already accessible within this visualisation object – you need to
   find them!

#### Tech diversity: Race

Completed the visualisation defined in `tech-diversity-race.js` to
create a pie chart to represent the racial diversity of prominent tech
companies.

1. The raw data: `./data/tech-diversity/race-2018.csv`.

2. Created a select DOM element using p5.dom.js (see
   [`createSelect`](https://p5js.org/reference/#/p5/createSelect)) and
   populate the options *programmatically* using the company names
   obtained from the columns of `this.data`.

3. Changed the hard-coded company name to instead get the value from
   the select.

4. Tested that when selecting a company name from the list the correct
   data is visualised on the canvas and the correct title is
   generated.

#### Pay gap by job 2017

Completed the visualisation defined in `pay-gap-by-job-2017.js` to
create a scatter plot representing the difference in pay for men and
women across different jobs.

In the `draw()` method completed the `for` loop that draws all of the
data points on the canvas as ellipses with the following properties.

    - x = proportion of female employees
    - y = pay gap
    - size = number of jobs
