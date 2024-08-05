<div class="page" id="page-3" style="display: block;"><h1 class="pageTitle">Components of Dashboard and Expected layout</h1>
<h2><span class="header-link octicon octicon-link"></span>Components of the  Dashboard</h2><ol>
<li><p>Select Region</p>
</li><li><p>Select Year</p>
</li><li><p>Divison to display</p>
<ul>
<li>Pie Chart to display Monthly Average Estimated Fire Area for the selected Regions in the selected Year</li><li>Bar Chart to display Monthly Average Count of Pixels for Presumed Vegetation Fires for the selected Regions in the selected Year</li></ul>
</li></ol>
<hr>
<h2><span class="header-link octicon octicon-link"></span>Expected Layout</h2><p><img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-DV0101EN-Coursera/images/practice_ass_layout.png" alt="layout_PA_P2" title="layout_PA_P2"></p>
<h2><span class="header-link octicon octicon-link"></span>Requirements to create the expected result</h2><ul>
<li>A dropdown <a href="https://dash.plotly.com/dash-core-components/dropdown" target="_blank" rel="noopener noreferrer">menu</a>: For choosing year</li><li>A radioitem for choosing the Region</li><li>The layout will be designed as follows:</li><li>An outer division with two inner divisions (as shown in the expected layout) </li><li>One of the inner divisions will have information about the radioitem and dropdown (which are the input) and the other one is for adding graphs(the 2 output   graphs).</li><li>Callback function to compute data, create graph and return to the layout.</li></ul>
<h3><span class="header-link octicon octicon-link"></span>To do:</h3><ol>
<li>Import required libraries and read the dataset</li><li>Create an application layout</li><li>Add title to the dashboard using HTML H1 component</li><li>Add a radioitem using dcc.RaioItems and dropdown using dcc.dropdown</li><li>Add the pie chart and bar chart core graph components.</li><li>Run the app</li></ol>
<hr>
<div class="page-footer"><button class="previous">Previous</button><button class="next">Next</button></div></div>
