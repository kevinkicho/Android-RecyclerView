# Android-RecyclerView

<h3>Description</h3>
<p>This project serve as a RecyclerView template to use for basic Text/Image Display with onClick method. </p>
<p><code>https://jsonplaceholder.typicode.com/posts</code> provides easy to use json file over the web. RecyclerView and CardView are used in this application to display items and give material-look. </p>
<img src="screenshots.jpg">
<h3>Implementation</h3>
<ol>
<li>Using Volley, <code>loadRecyclerViewData()</code> retrieves JSON object from URL_DATA with GET method.</li>
<li><code>progressDialog</code> show/dismissal happens while data is being loaded.</li>
<li>ListItems are stored as <code>ListItem</code> object. Adapter Class sets View and specified onClickEvent.</li>
  <p></p>
<img src="recyclerview_workflow.jpg" >

</ol>
