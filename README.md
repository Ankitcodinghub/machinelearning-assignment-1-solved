# machinelearning-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Assignment 1 Solved](https://www.ankitcodinghub.com/product/machinelearning-assignment-1-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95809&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Assignment (Role: Machine Learning Engineer)

As you may know, it is very important to us to have the best possible data to define the businesses we, at Reputation, are analyzing. We pull data from various sources, by various means and at various times. It doesn’t always fit together well.

This is an exercise to get a sense for how you might approach building a scalable and maintainable data quality enhancing and monitoring system which can fit together “messy” data.

Attached is a set of “messy” sample dataset about US Auto dealerships. This data includes:

<ul>
<li>Location ID – A distinct ID for each dealer location</li>
<li>Dealership Name</li>
<li>A Tenant ID – An ID representing parent organization of dealer</li>
<li>Address – Location detail attributes (address_line, city, state, zip, latitude,
longitude)
</li>
<li>Phone Number</li>
<li>Website</li>
<li>Google url – google listing of the location</li>
<li>FB url – FB listing of the location</li>
<li>Cars url – Cars listing of the location
This data is gathered from various sources and is of varying levels of quality. Not all values are filled in for every row and not all of the data in here aligns perfectly. There are a lot of duplicate entries, overlapping entries, mismatched entries, entries with wrong/outdated values and missing entries. None of these values can be trusted fully.

Task is to approach developing a scalable and maintainable system/pipeline which can help monitoring and enhancing this data. On a high level, system should output the following
</li>
</ul>
• Best estimate of a “canonical” list of distinct dealerships in this dataset • Along with (as best as system can figure out) the name, address,

phone number, and website of those dealerships

• As well as the google, facebook, and cars.com websites for those

dealerships if system can determine them

• System should be able to map every one of the entries in the original dataset to that canonical list, along with a confidence score of how confidently system is concluding that this is the same dealership

<ul>
<li>System should be able to handle new dealership data coming in future and scale</li>
<li>System should generate following reports</li>
<li>Total number of canonical locations</li>
<li>Total number of data issues found</li>
<li>Lists of potential correction (add/update) of any fields for each record in
the original dataset.

One way to format this would be to create a csv with columns for
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>Location ID</li>
<li>Attribute Name (e.g. name, phone number, google url)</li>
<li>Current value</li>
<li>New value</li>
</ul>
• Data quality by tenant

One way to format this would be to create a csv with columns for

<ul>
<li>Location ID</li>
<li>Tenant ID</li>
<li>Data Quality %
The expectation here is
</li>
</ul>
<ul>
<li>Not that you build full working system</li>
<li>But clearly demonstrate how you would approach this and showcase the first pass at this</li>
</ul>
<ul>
<li>Clearly lay out the development plan and how you would proceed further</li>
<li>Possibly prepare a notebook to demonstrate your idea/algorithm to the core problem (messy data)</li>
</ul>
• Explain any 2 methods that you would prefer to push the project to production for client usage

• A document for the overall development plan (modules/stages, APIs, interfaces, deployment strategy)

• Brownie points if you could build a RESTful webservice with the algorithm using any framework (Flask/Django) that you are convenient with. (High Level Deliverable)

Hints:

None of the attribute values can be trusted. We may need a probabilistic approach.

</div>
</div>
</div>
</div>
