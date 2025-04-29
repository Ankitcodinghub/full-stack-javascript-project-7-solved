# full-stack-javascript-project-7-solved
**TO GET THIS SOLUTION VISIT:** [FULL_STACK_JAVASCRIPT Project 7 Solved](https://www.ankitcodinghub.com/product/full_stack_javascript-instructions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116371&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FULL_STACK_JAVASCRIPT Project 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Create your project

• Use the create-react-app to set up and create your initial directory.

Build your app components

• Use the index.html file and mockups as a general guide while you create the components of this project.

• Use the src/App.js file as your main container component.

• Stateless functional components work well for components that focus on the UI and receive data via props. Some examples of the stateless components you could use for your app are:

o A Photo component that displays the li and img elements.

o A Nav component for the apps navigation links. o A NotFound component for displaying a user friendly message when the search returns no results

• Stateful class components will be better suited for your search form and photo container where data can be managed with state.

Get a Flickr API key

• Create yahoo account/use tumblr account to sign in.

• Apply for a non-commercial API key:

https://identity.flickr.com/login?redir=%2Fservices%2Fapps%2Fcreate%2Fapply%2F

• You’ll need to set up a config.js file in your project that imports your API key into your application so that you and other users can request data from the Flickr API. This should be imported into src/App.js.

• The config.js file should look something like this:

• Import your API key into your application, preferably into src/app.js, and save it to a variable like you would any other module, and use the variable where applicable. That way, your app’s users will only need to enter in an API key once.

Important Note: This config.js file must be listed in the .gitignore file so it won’t be committed to your github repository. This will prevent your keys and tokens from getting posted publicly to GitHub. It is very important that you do NOT upload any of your personal API keys / secrets / passwords to Github or other publicly accessible place. When you submit this project for grading, your project reviewer will create their own config.js file and use their own API key to run the project.

Routes

• Install React Router and set up your &lt;Route&gt; and &lt;Link&gt; or &lt;NavLink&gt; elements.

• Include a “Search” link that includes a search field to let users search for photos.

• Clicking a nav link should navigate the user to the correct route, displaying the appropriate info.

• The current route should be reflected in the URL.

• Your app should display at least 3 default topic links that return a list of photos matching some criteria. For example: Sunsets, waterfalls, and rainbows.

• It’s okay to request and load the photos for the three default topics when the app first loads. Those default topic pages don’t have to re-request and reload new data every time one of those pages are loaded.

Requesting the data

• Fetch the data from the Flickr API using the Fetch API or a tool like Axios.

• Make sure data fetching and state is managed by a higher-level “container” component, like src/App.js.

• It is recommended that you use the following link for help with this part of the project: https://www.flickr.com/services/api/explore/flickr.photos.search o Enter a tag to search for, such as “sunsets”. o You should also limit the number of results to 24 using the per_page argument. o Choose JSON as the output, then “Do not sign call.” o Click “Call Method…” At the bottom of the page, and you’ll see an example of the API call you’ll need to make. You can click on the URL to see what the response will look like.

Search

• Be sure to include a search field feature and a search route to search for new categories of images.

Displaying the data

• Make sure each image gets a unique “key” prop.

• There should be no console warnings regarding unique “key” props.

• The title of each page displaying images should be dynamically provided via “props”.

• The current route should be reflected in the URL.

• There should be no more than 24 images displayed.

CSS styles

• The mockups are just a general guide for how the elements should be arranged and positioned on the page. But other than general arrangement, spacing, and positioning; you are free to experiment with things like color, background color, font, shadows, transitions, animations, etc.

Add good code comments!

Cross-Browser consistency:

• Google Chrome has become the default development browser for most developers. With such a selection of browsers for users to choose from, it’s a good idea to get in the habit of testing your projects in all modern browsers.

Review the “How you’ll be graded” section!

Quality Assurance and Project Submission Checklist

• Perform QA testing on your project, checking for bugs, user experience, and edge cases.

• Check off all the items on the Student Project Submission Checklist.

NOTE: Seeking assistance

• If you’re feeling stuck or having trouble with this project o Reach out to the team on Slack.

Extra Credit

• Add a loading indicator that displays each time the app fetches new data. Since the data for the three main topic pages can be requested when the page first loads, it’s okay if the loading indicator is only present on the search route.

• If no matches are found by the search, display a friendly user message to tell the user there are no matches.

• Include a 404-like error route that displays a friendly 404 error page when a URL does not match an existing route.
