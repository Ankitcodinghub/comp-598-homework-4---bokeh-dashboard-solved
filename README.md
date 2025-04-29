# comp-598-homework-4---bokeh-dashboard-solved
**TO GET THIS SOLUTION VISIT:** [COMP 598 Homework 4 – Bokeh Dashboard Solved](https://www.ankitcodinghub.com/product/comp-598-homework-4-bokeh-dashboard-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110765&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP 598 Homework 4 – Bokeh Dashboard Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
30 pts

In this homework, you are a data scientist working with the New York City data division. Your task is to develop a dashboard allowing city leaders to explore the discrepancy in service across zipcodes. You’ll be using a derivate of the following dataset:

– https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9

NOTE: The original dataset is very large and therefore we have provided a subset of it.

For the purpose of this assignment:

1. Download nyc_311.csv.tgz from MyCourses.

For the remainder of this assignment, you should only work with the trimmed down dataset.

Task 1: Get Jupyter running on your EC2 (5 pts)

Setup Jupyter on your EC2 with password login support. For the EC2 instance, you can reuse the instance you created for previous assignments, or spin up an entirely new machine (recommended).

Create a Jupyter notebook in which you have loaded the data file you trimmed (mentioned above) and printed out the number of distinct zipcodes in the dataset. You will submit the logs that Jupyter created when it booted up and handled you logging in via a browser. Note that an automated grading script will be used to evaluate your logs, so they must contain the log text produced when Jupyter successfully boots up AND when you log into the server.

– To capture the log data, redirect the stdout and stderr from your Jupyter notebook command into the file jupyter.log

Task 2: Bokeh dashboard (25 pts)

The goal of your dashboard is to allow a city official to evaluate the difference in response time to complaints filed through the 311 service by zipcode. Response time is measured as the amount of time from incident creation to incident closed. Using the dataset from the previous exercise, build a bokeh dashboard which provides in a single column, the following:

– A drop down for selecting zipcode 1

– A drop down for selecting zipcode 2

– A line plot of monthly average incident create-to-closed time (in hours) o Don’t include incidents that are not yet closed o The plot contains three curves:

▪ A legend naming the three curves

▪ Appropriate x and y axis labels

When either of the zipcode dropdowns are changed, the plot should update as appropriate.

– Your dashboard should be running on port 8080. The dashboard name (in the route) should be “nyc_dash”.

– The bokeh dashboard should authenticate any user who logs in with URL params username = “nyc” and password = “iheartnyc” (quotes not included). Failed authentications just need to fail to allow the user in (i.e., they don’t need to route the user to a login page that actually exists).

– On any change to either zipcode, your dashboard must update within 5 seconds.

– The IP address of your instance must the specified in a file named ip_address.txt

– ip_address.txt should only contain a single line with ip address to your server for example

54.175.131.58

– You are welcome to submit a valid domain name, but it will break the unit tests. It will also break our grading scripts – do this at your own risk.

How to solve this assignment – Hints

1. Please read all the instructions, especially the ones in the GitHub README.

2. Familiarize yourself with Bokeh by reading its documentation

3. Ensure your dashboard is accessible

5. Watch out for the EC2 instance type – a micro instance (free tier) might not be enough.

FAQ

3. Do rows with missing zip codes be included in the overall average? – These should be removed. At the beginning when you trim the data, you should only choose the rows with zipcode.

5. Should we calculate by day or by hour? – In hours.

Submission Instructions

NOTE: It is essential that you follow the submission guidelines as stated in the README file. Failure to follow exact guidelines would result in losing points.
