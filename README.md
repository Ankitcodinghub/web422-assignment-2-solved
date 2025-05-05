# web422-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [WEB422 Assignment 2 Solved](https://www.ankitcodinghub.com/product/web422-assignment-2-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89758&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;WEB422 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
To work with our “Trips” API (from Assignment 1) on the client-side to produce a rich user interface for accessing data.&nbsp; We will practice using well-known CSS/JS code and libraries including Lodash, Leaflet, jQuery &amp; Bootstrap

Sample Solution:

You can see a video of the solution running at the following location: <a href="https://pat-crawford-sdds.netlify.app/shared/summer-2022/web422/A2/A2.mp4">https://pat</a><a href="https://pat-crawford-sdds.netlify.app/shared/summer-2022/web422/A2/A2.mp4">–</a><a href="https://pat-crawford-sdds.netlify.app/shared/summer-2022/web422/A2/A2.mp4">crawford</a><a href="https://pat-crawford-sdds.netlify.app/shared/summer-2022/web422/A2/A2.mp4">–</a><a href="https://pat-crawford-sdds.netlify.app/shared/summer-2022/web422/A2/A2.mp4">sdds.netlify.app/shared/summer</a><a href="https://pat-crawford-sdds.netlify.app/shared/summer-2022/web422/A2/A2.mp4">–</a><a href="https://pat-crawford-sdds.netlify.app/shared/summer-2022/web422/A2/A2.mp4">2022/web422/A2/A2.mp4</a> Specification:

For this assignment, we will create a single table that shows a subset of the trip data (ie: columns: <strong>Bike Id, Start Station, End Station and Duration (Minutes)</strong>). When the user clicks on a specific trip (row) in the table, they will be shown a modal window that shows an interactive map indicating both the start location and end location.&nbsp; We will be making use of the Bootstrap framework to help design our UI, jQuery to work with the DOM, Lodash to specify our template(s) and <a href="https://leafletjs.com/">Leaflet</a> to render the map.

&nbsp;

&nbsp;

<h1>The Solution Directory</h1>
The first step is to create a new directory for your solution, open it in Visual Studio Code and add following folders / files:

&nbsp;

We will not be including any of the JavaScript / CSS libraries locally.&nbsp; Instead, we will be leveraging their CDN locations (See the <a href="https://web422.ca/notes/week02">Week 2 notes</a> for the &lt;script&gt; and &lt;link&gt; elements necessary to include jQuery, Bootstrap, Lodash and Leaflet).&nbsp; <strong>Note:</strong> Remember that the order is important, ie: jQuery should be included <em>before</em> the Bootstrap JavaScript and your main.js file should be included last.

&nbsp;

Creating the Static HTML:

Next, we must create some Static HTML as a framework for the dynamic content.

Open your index.html file and add the minimum code required for an HTML5 page (HINT: type <strong>!</strong>

and then immediately type the <strong>tab </strong>key to get an HTML 5 skeleton).&nbsp; Once this is complete, include links for:

&nbsp;

<ul>
<li>The Bootstrap 3.4.1 Minified CSS File (Using the CDN)</li>
</ul>
&nbsp;

<ul>
<li>The CSS for <a href="https://leafletjs.com/download.html"><strong>Leaflet</strong></a><a href="https://leafletjs.com/download.html">,</a> ie:</li>
</ul>
&nbsp;

&lt;link rel=”stylesheet” <u>href=”https://unpkg.com/leaflet@1.7.1/dist/leaflet.css</u>” integrity=”sha512xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChS R7A==” crossorigin=””<strong>/&gt;</strong>

&nbsp;

<ul>
<li>Your <strong>css</strong> file (<strong>NOTE</strong>: This file will consist of four selectors (for now) to ensure that your “trips-table” (or whatever you wish to call it) causes the cursor to change to a “pointer” whenever a user moves their mouse over a row. Also, we must ensure that your map is a specific height and you have set classes for “Subscriber” and “Customer” background colours (to be used in your table rows, labels, etc) – please feel free to use whatever colours fit your design.</li>
</ul>
&nbsp;

#trips-table <strong>tr</strong>:hover { <strong>cursor</strong>:<strong>pointer</strong>; }

#leaflet { <strong>height</strong>: 400px; }

.Subscriber { <strong>background-color</strong>: …; <strong>color</strong>: …; }

.Customer { <strong>background-color</strong>: …; <strong>color</strong>: …; }

&nbsp;

<ul>
<li>The jQuery 3.4.1 Slim, Minified JS File (Using the CDN)</li>
</ul>
&nbsp;

<ul>
<li>The Bootstrap 3.4.1 Minified JS File (Using the CDN)</li>
</ul>
&nbsp;

<ul>
<li>The Lodash 4.17.5 Minified JS File (Using the CDN)</li>
</ul>
&nbsp;

<ul>
<li>The JS File for <a href="https://leafletjs.com/download.html"><strong>Leaflet</strong></a><a href="https://leafletjs.com/download.html">,</a> ie:</li>
</ul>
&nbsp;

<strong>&lt;script </strong><u>src=”https://unpkg.com/leaflet@1.7.1/dist/leaflet.js</u>” integrity=”sha512-

XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynx wA==” crossorigin=””<strong>&gt;&lt;/script&gt;</strong>

&nbsp;

<ul>
<li>Your <strong>js</strong> file</li>
</ul>
With all of our libraries and files in place, we can concentrate on placing the static HTML content on the page.&nbsp; This includes the following:

&nbsp;

<h2>Navbar</h2>
Assignment 2 will use an extremely simplified Bootstrap 3 navbar.&nbsp; Begin by copying the full <strong>Default Navbar</strong> example HTML code from the official documentation: <a href="https://getbootstrap.com/docs/3.4/components/#navbar-default">https://getbootstrap.com/docs/3.4/components/#navbar</a><a href="https://getbootstrap.com/docs/3.4/components/#navbar-default">–</a><a href="https://getbootstrap.com/docs/3.4/components/#navbar-default">default</a> and pasting it as the first element within the &lt;body&gt; of your file.

<ul>
<li>Next, proceed to remove <strong>all</strong> <strong>child elements</strong> from the “bs-example-navbar-collapse-1” &lt;div&gt; element</li>
<li>In the (now empty) “bs-example-navbar-collapse-1” &lt;div&gt; element, put back a single navigation item and label it “Trips”, ie:</li>
</ul>
<strong>&lt;ul</strong> class=”nav navbar-nav”<strong>&gt;</strong>

<strong>&nbsp;&nbsp;&nbsp; &lt;li</strong> class=”active”<strong>&gt;&lt;a</strong> href=”#”<strong>&gt;</strong>Trips<strong>&lt;span</strong> class=”sr-only”<strong>&gt;</strong>(current)<strong>&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;</strong>

<strong>&lt;/ul&gt;</strong>

<ul>
<li>Finally, change the “navbar-brand” to be your name</li>
</ul>
When completed, your navbar should look like the following

&nbsp;

&nbsp;

<h2>Bootstrap Grid System (1 Column)</h2>
Since we are leveraging Bootstrap for this assignment, we should make use of their excellent responsive grid system.&nbsp; Beneath the navbar, add the following HTML

<ul>
<li>Include a &lt;div&gt; element with the class “container” (so that our content is centered)</li>
<li>Within the “container”, create a &lt;div&gt; with class “row”</li>
<li>Within the “row”, create a &lt;div&gt; with class “col-md-12” (we will only have one column to show our data)</li>
</ul>
&nbsp;

<h2>Citibike Trips Header</h2>
Before we create our main table skeleton (next), we should create an appropriate header informing the user about the content of the table, as well as indicating your chosen colours to indicate “Subscribers” vs “Customers” in the table.

Start by adding a header (ie: &lt;h2&gt;) with the text “Citibike Trips”.&nbsp; Beneath this header, you can add two <a href="https://getbootstrap.com/docs/3.4/components/#labels">Bootstrap labels</a> with the class “Subscriber” and “Customer”, ie:

&lt;<strong>span</strong> <strong>class</strong>=”label Subscriber” <strong>style</strong>=”font-size:small”&gt;Subscribers&lt;/<strong>span</strong>&gt;

&lt;<strong>span</strong> <strong>class</strong>=”label Customer” <strong>style</strong>=”font-size:small”&gt;Customers&lt;/<strong>span</strong>&gt;

&nbsp;

Once these items are in place, your app should look similar the following (ie: you may have chosen different colours for “.Subscriber” and “.Customer”):

&nbsp;

&nbsp;

<h2>Main Table Skeleton</h2>
The main interface that users will interact with to view data in our application is a HTML table consisting of <strong>4 columns:</strong> <strong>Bike Id, Start Station, End Station </strong>and <strong>Duration (Minutes)</strong>.&nbsp; Create this table within your “col-md-12” container according to the following specification:

<ul>
<li>The &lt;table&gt; element should have the class “table” and a unique id, ie: “trips-table”, since we will be accessing it programmatically from JavaScript</li>
</ul>
&nbsp;

<ul>
<li>The &lt;thead&gt; element should contain one row</li>
</ul>
&nbsp;

<ul>
<li>The single header row should have 4 table heading elements with the text:
<ul>
<li>Bike Id o Start Station o End Station</li>
<li>Duration (Minutes)</li>
</ul>
</li>
</ul>
&nbsp;

<ul>
<li>The &lt;tbody&gt; element should be empty</li>
</ul>
&nbsp;

Once your table is in place, your app should appear similar to:

&nbsp;

&nbsp;

&nbsp;

<h2>Paging Control</h2>
Since our “trips” collection contains approximately 10000 documents, we will leverage our Web API’s pagination feature when pulling trips from the database (ie:

<strong>/api/trips?page=1&amp;perPage=10</strong>, etc).&nbsp; To give the user some control over which page they wish to see, we must include a primitive pagination control (for this assignment, we will not let them “jump” to a specific page, but instead we will let them go back and

forth between the pages in sequence).&nbsp; To accomplish this, we must place the pagination buttons on our page before wiring up their functionality using jQuery:

&nbsp;

<ul>
<li>Begin by copying the full <strong>Pagination</strong> HTML code from the official documentation:</li>
</ul>
<a href="https://getbootstrap.com/docs/3.4/components/#pagination">https://getbootstrap.com/docs/3.4/components/#pagination</a> and pasting it directly underneath your newly created “trips-table”.

<ul>
<li>Next, delete the list items that contain the numbers <strong>2</strong>, <strong>3</strong>, <strong>4</strong> and <strong>5</strong> (leaving just <strong>1</strong>)</li>
</ul>
&nbsp;

<ul>
<li>Give each of the 3 remaining &lt;a&gt; elements (nested within the &lt;li&gt; elements) unique id values such as “previous-page”, “current-page” and “next-page” (we will use these id values to add functionality to the links and display the current page)</li>
</ul>
&nbsp;

<ul>
<li>Finally, remove the text <strong>1</strong> from the middle link (it will be added dynamically later).</li>
</ul>
&nbsp;

Once your pagination control is in place, your app skeleton should look like the following:

&nbsp;

<h2>“Generic” Modal Window Container</h2>
We will be showing our map for a specific trip in a Bootstrap modal window.&nbsp; Since every time we show the modal window, it will have different content (Specific to the Trip that was clicked), we must add an empty, <strong>generic</strong> modal window to the bottom of our page.

To get the correct HTML to use for your Bootstrap modal window, use <a href="https://getbootstrap.com/docs/3.4/javascript/#modals-examples">the following</a> <a href="https://getbootstrap.com/docs/3.4/javascript/#modals-examples">example</a> from the documentation as a starting point.

Once you have copied and pasted the “modal” HTML into the bottom of your &lt;body&gt; element (ie, below the other content) , make the following changes:

<ul>
<li>Give your &lt;div&gt; with the class “<strong>modal fade</strong>” a unique <strong>id</strong>, ie: “<strong>trip-modal</strong>“. We will need to reference this element every time we wish to show / work with the <strong>modal window.</strong></li>
<li>Remove the “Modal Title” text from the &lt;h4&gt; element with class “<strong>modal-title</strong>“. We will be using jQuery to populate this later.</li>
<li>Remove the &lt;p&gt; element with the text “One fine body…” from the &lt;div&gt; element with class “<strong>modal-body</strong>” and replace it with the following elements:</li>
</ul>
&nbsp;

<strong>&lt;div</strong> id=”leaflet”<strong>&gt;&lt;/div&gt;</strong>

<strong>&lt;br /&gt;</strong>

<strong>&lt;div</strong> id=”map-details”<strong>&gt;&lt;/div&gt;</strong>

&nbsp;

These are placeholders for both the map, and map details respectfully.

<ul>
<li>Finally, remove the button element with the text “Save Changes”. This modal is used to display information only, so a “save” button is not required</li>
</ul>
&nbsp;

JavaScript File (main.js):

Now that we have all of our static HTML / CSS in place, we can start dynamically adding content and responding both user and bootstrap events using JavaScript.&nbsp; In your <strong>main.js</strong> file add the following variables &amp; functions at the top of the file:

&nbsp;

<ul>
<li><strong>tripData </strong>(array)</li>
</ul>
&nbsp;

This should be an empty array (we will populate it later with a “fetch” call to our back end API)

<strong>&nbsp;</strong>

<ul>
<li><strong>currentTrip </strong>(object)</li>
</ul>
&nbsp;

This should be an empty object (ie: {} – we will populate it later once the user clicks on a specific trip

within our UI)

<strong>&nbsp;</strong>

<ul>
<li><strong>page </strong>(number)</li>
</ul>
&nbsp;

This will keep track of the current page that the user is viewing.&nbsp; Set it to <strong>1</strong> as the default value

<strong>&nbsp;</strong>

<ul>
<li><strong>perPage </strong>(number)</li>
</ul>
&nbsp;

This will be a constant value that we will use to reference how many trip items we wish to view on each page of our application.&nbsp; For this assignment, we will set it to <strong>10</strong>.

<strong>&nbsp;</strong>

<ul>
<li><strong>map</strong> (leaflet “map” object)</li>
</ul>
&nbsp;

This will be a reference to our current “map”, once it has been initialized.&nbsp; For now, simply assign it a value of <strong>null</strong>

<strong>&nbsp;</strong>

<ul>
<li><strong>tableRows </strong>(Lodash template)</li>
</ul>
&nbsp;

This will be a constant value that consists solely of a Lodash template (defined using the _.template() function). The idea for this template is that it will provide the functionality to return all the rows for our main “trips-table”, given an array of “trip” data.&nbsp; For example, if the <strong>tableRows </strong>template was invoked with the first two results back from our <strong>Web API</strong> (<strong><em>left</em></strong>), it should output the following <strong>HTML</strong> (<strong><em>right</em></strong>):

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<strong>&lt;tr</strong> <strong>data-id</strong>=”572bb8222b288919b68abf5a”

<strong>class</strong>=”Subscriber”&gt;

<strong>&lt;td&gt;</strong>17827<strong>&lt;/td&gt;</strong>

<strong>&lt;td&gt;</strong>E 31 St &amp;amp; 3 Ave<strong>&lt;/td&gt;</strong>

<strong>&lt;td&gt;</strong>Broadway &amp;amp; W 32 St<strong>&lt;/td&gt;</strong>

<strong>&lt;td&gt;</strong>6.32<strong>&lt;/td&gt;</strong>

<strong>&lt;/tr&gt;</strong>

&nbsp;

&lt;<strong>tr</strong> <strong>data-id</strong>=”572bb8222b288919b68abf5b”

<strong>class</strong>=”Subscriber”&gt;

<strong>&lt;td&gt;</strong>22794<strong>&lt;/td&gt;</strong>

<strong>&lt;td&gt;</strong>Howard St &amp;amp; Centre St<strong>&lt;/td&gt;</strong>

<strong>&lt;td&gt;</strong>South End Ave &amp;amp; Liberty St<strong>&lt;/td&gt;</strong>

<strong>&lt;td&gt;</strong>14.82<strong>&lt;/td&gt;</strong>

&lt;/<strong>tr</strong>&gt;

You will notice a few things about the formatting of each row in the returned result, specifically:

<ul>
<li>The template loops through each object in the array to produce a &lt;tr&gt; element (<strong>HINT</strong>: .forEach() can be used here)</li>
</ul>
&nbsp;

<ul>
<li>Each &lt;tr&gt; has a “data-id” attribute that matches the <strong>_id</strong> property as well as a “class” attribute that matches the <strong>usertype</strong> property of the object in the current iteration</li>
</ul>
&nbsp;

<ul>
<li>The first &lt;td&gt; contains the <strong>bikeid</strong> property of the object in the current iteration</li>
</ul>
&nbsp;

<ul>
<li>The second &lt;td&gt; contains the <strong>“start station name”</strong> property of the object in the current iteration (<strong>NOTE</strong>: To access properties that contain spaces, you may use the syntax <strong>obj[“property name”]</strong> instead of <strong>property name</strong>)</li>
</ul>
&nbsp;

<ul>
<li>The second &lt;td&gt; contains the <strong>“end station name”</strong> property of the object in the current iteration</li>
</ul>
&nbsp;

<ul>
<li>The final &lt;td&gt; content contains the <strong>tripduration</strong> for the object in the current iteration in minutes, shown to two decimal places. This can be obtained by using the expression (<strong>tripduration</strong> / 60).toFixed(2)</li>
</ul>
&nbsp;

<strong>HINT: Place all the HTML / Code for your template within a string defined using ` `</strong> (this will allow you to write our template string across multiple lines.

&nbsp;

<ul>
<li><strong>loadTripData() </strong>(function)</li>
</ul>
<strong>&nbsp;</strong>

Now that our templates and global variables are in place, we can write a utility function to actually <strong>populate</strong> the <strong>tripData </strong>array with data from our API created in Assignment 1 (now sitting on Heroku).

To achieve this, the loadTripData function must:

&nbsp;

<ul>
<li>make a “fetch” request to our Web API hosted on Heroku using the route:</li>
</ul>
/api/trips?page=<strong><em>page</em></strong>&amp;perPage=<strong><em>perPage</em></strong>

<strong><em>Here, the values of </em>page</strong> and <strong>perPage </strong>must be the values of the variables: <strong>page</strong> and <strong>perPage </strong>that you declared at the top of the file at the beginning of this assignment – <strong>perPage</strong> is a constant value and <strong>page</strong> is the current working page.

<ul>
<li>When the fetch request has returned and the json data has been parsed:
<ul>
<li>set the global <strong>tripData </strong>array to be the data returned from the request</li>
</ul>
</li>
</ul>
&nbsp;

<ul>
<li>invoke the <strong>tableRows </strong>template with the data returned from the request (ie: <strong>tableRows({trips: data})</strong>) and store the return value in a variable.</li>
</ul>
&nbsp;

<ul>
<li>Select the &lt;tbody&gt; element of your main “trips-table” and set its html (.html()) to be the returned value from when you invoked the <strong>tableRows </strong>template function, above.</li>
</ul>
&nbsp;

<ul>
<li>Select the <strong>current-page</strong> element (from your pagination control) and set its html (.html()) to be the value of the current <strong>page</strong></li>
</ul>
&nbsp;

Now that our loadTripData() utility function as well as our templates and global variables are in place, let’s add the following code to be executed when the document is <strong><em>ready</em></strong> (ie: within the <strong>$(function(){</strong> … <strong>});</strong> callback ):

&nbsp;

The first thing that needs to be done, is to invoke the <strong>loadTripData()</strong> function to populate our table with data and set the current working page

&nbsp;

Next, we must wire up the following <strong>5 events </strong>using jQuery<strong>:</strong>

&nbsp;

<h2><strong>1)</strong> <strong><u>Click</u></strong><u> event for all <strong>tr</strong> elements within the <strong>tbody</strong> of the <strong>trips-table</strong></u></h2>
Once this event is triggered, we must perform the following actions:

<ul>
<li>Locate the trip object in the <strong>tripData </strong>array whose “_id” property matches the “data-id” property of the row that was clicked, and store it as the <strong>currentTrip</strong> object (declared at the top of the file). This will allow us to work with the clicked trip object (<strong>currentTrip</strong>) in our other events (below).</li>
</ul>
&nbsp;

HINT: the “data-id” value can be obtained by using the jQuery code: $(<strong>this</strong>).attr(“data-id”);)

&nbsp;

<ul>
<li>Set the content of the “modal title” (ie: &lt;h4 class=”modal-title”&gt;&lt;/h4&gt;) for the “trip-modal” to the text <strong>Trip Details (Bike: <em>bikeid</em></strong>), where <strong><em>bikeid</em></strong> is the value of “bikeid” for the <strong>currenttrip</strong></li>
</ul>
&nbsp;

<ul>
<li>Set the contents of the “map details” (ie: &lt;div id=”map-details”&gt;&lt;/div&gt;) to show the following pieces of data for the <strong>currentTrip</strong>:</li>
</ul>
&nbsp;

<ul>
<li>“start station name” o “end station name”</li>
<li>“tripduration” (represented in minutes, shown to two decimal places)</li>
</ul>
For example:

&nbsp;

&nbsp;

<ul>
<li>Open the “Trip” Modal window (ie: &lt;div id= “trip-modal” … &gt; … &lt;/div&gt;”).</li>
</ul>
&nbsp;

<h2><strong>2)</strong> <strong><u>Click</u></strong><u> event for the “previous page” pagination button</u></h2>
When this event is triggered we simply need to check if the current value of <strong>page</strong> (declared at the top of the file) is greater than <strong>1</strong>.&nbsp; If it is, then we decrease the value of <strong>page</strong> by 1 and invoke the <strong>loadTripData function</strong> to refresh the rows in the table with the new page value.

&nbsp;

<h2><strong>3)</strong> <strong><u>Click</u></strong><u> event for the “next page” pagination button</u></h2>
This event behaves almost exactly like the click event for the “previous page”, except that instead of <em>decreasing </em>the value of page, we <strong>increase</strong> the value of <strong>page</strong> by 1 and invoke the <strong>loadTripData function</strong> to refresh the rows in the table with the new page value.

&nbsp;

<h2><strong>4)</strong> <strong><u>shown.bs.modal</u></strong><u> event for the “Trip” modal window</u></h2>
This event is actually a <a href="https://getbootstrap.com/docs/3.3/javascript/#modals">Bootstrap event</a> that triggers once a modal window is fully shown (after the CSS transitions have completed).&nbsp; To wire up this event, we can use the following jQuery code:

&nbsp;

$(‘#trip-modal’).on(‘shown.bs.modal’, function () {});

&nbsp;

Once the modal has been “shown”, we must include the following code in order to correctly render a map using our <strong>Leaflet</strong> library:

&nbsp;

map = new L.Map(‘leaflet’, {

layers: [

new L.TileLayer(‘https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png’)

]

});

&nbsp;

let start = L.marker([<strong><em>start station location – coordinate 1</em></strong>, <strong><em>start station location – coordinate 0</em></strong>]) .bindTooltip(<strong><em>start station name</em></strong>,

{

permanent: true,

direction: ‘right’

}).addTo(map);

&nbsp;

let end = L.marker([<strong><em>end station location – coordinate 1</em></strong>, <strong><em>end station location – coordinate 0</em></strong>]) .bindTooltip(<strong><em>end station name</em></strong>,

{

permanent: true,

direction: ‘right’

}).addTo(map);

&nbsp;

var group = new L.featureGroup([start, end]);

&nbsp;

map.fitBounds(group.getBounds(), { padding: [60, 60] });

&nbsp;

You will notice that there are placeholders for <strong><em>start station location – coordinate</em></strong><em> <strong>1</strong></em> and<strong> <em>0 </em></strong>as well as <strong><em>start station name </em></strong>&nbsp;/ <strong><em>end station name</em></strong>.&nbsp; These should be replaced with the values from the associated properties within the <strong>currentTrip</strong> object..

Additionally, you will notice that the <strong>new</strong> L.Map(‘leaflet’, { … }); code creates an object that we assign to our <strong>map</strong> variable (originally defined as <strong>null</strong> at the top of our file).&nbsp; This is so that we are able to correctly <em>remove</em> the map once the modal window has closed.

&nbsp;

<h2><strong>5)</strong> <strong><u>hidden.bs.modal</u></strong><u> event for the “Trip” modal window</u></h2>
This event is wired up in the exact same way as the “shown.bs.modal” event, defined above.&nbsp; However, this time instead of creating a new map, we must remove the existing map using the code:

&nbsp;

map.remove();

&nbsp;

&nbsp;

6) Pushing code to a private GitHub repository You need to push to a remote repository:

<ul>
<li>Create a new private repository in GitHub and name it web322-assignment4-app</li>
<li>Share this repository by going to your web322-assignment4-app repository in GitHub –</li>
</ul>
&gt; Settings -&gt; Collaborators -&gt; Add People -&gt; Enter “<strong>at-seneca</strong>” and Invite Collaborator

&nbsp;

&nbsp;

Assignment Submission:

<ul>
<li>Add the following declaration at the top of your main.js file</li>
</ul>
&nbsp;

/****************************************************************************** ***

<ul>
<li>WEB422 – Assignment 2</li>
<li>I declare that this assignment is my own work in accordance with Seneca Academic Policy. *&nbsp; No part of this assignment has been copied manually or electronically from any other source * (including web sites) or distributed to other students. *</li>
<li>Name: ______________________ Student ID: __________________ Date:</li>
</ul>
____________________

*

******************************************************************************

**/

<ul>
<li>Compress (.zip) the files in your Visual Studio working directory (this is the folder that you opened in Visual Studio to create your client-side code).</li>
</ul>
Important Note:

<ul>
<li><strong>NO LATE SUBMISSIONS</strong> for assignments. Late assignment submissions will not be accepted and will receive a <strong>grade of zero (0)</strong>.</li>
<li>After the end (11:59PM) of the due date, the assignment submission link on My. Seneca will no longer be available.</li>
<li>Submitted assignments must run locally, i.e.: start up errors causing the assignment/app to fail on Startup will result in a <strong>grade of zero (0)</strong> for the assignment.</li>
</ul>
