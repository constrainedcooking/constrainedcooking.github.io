# Table of Contents

* [About Constrained Cooking](#about-constrained-cooking)
  * [Goals](#goals)
* [Development History](#development-history)
  * [Milestone 1: Mockup Development](#milestone-1-mockup-development)
  * [Milestone 2: Add Functionality](#milestone-2-add-functionality)
* [About the Team](#about-the-team)

# About Constrained Cooking

Constrained Cooking is a Meteor application that creates a way for students to share creative recipes tailored to limited kitchen resources, limited ingredients, and limited time.

At the landing page, a user can view the recipe homepage, or create an account to view more content.

<img src="images/landingpagenew.PNG"/>

After a user creates an account,
# Goals

We have several goals that will be included in our final system:
* Users will be able to upload and share recipes
* Recipes can be filtered according to dietary restrictions
* Recipes will have an estimated cost per serving, number of servings, and estimated time to cook
* Vendors will be able to login and establish a profile
  * Include stock, cost, location, and hours
* Admin users will be able to login
  * Edit content, remove content, and verify vendor users

# Development History

Development of Constrained Cooking followed practices of [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314s18/modules/project-management/).  Milestones are used to track the progress on groups of issues; they consist of tasks that take 2-3 days.  To manage progress within a Milestone, GitHub projects are created with three columns corresponding to: Backlog, In Progress, and Done.

## [Milestone 1: Mockup Development](https://github.com/constrainedcooking/constrainedcooking/projects/1)

This milestone started on April 2, 2018 and ended on April 12, 2018.

The goal of Milestone 1 was to create mockup pages of what we expect the final system to look like and implement the basics in Meteor.  Below are layouts our team sketched of several page ideas.

<img src="images/recipepagemockup.PNG"/>

Recipe Home Page

<img src="images/createrecipemockup.PNG"/>

Add Recipe Page

<img src="images/vendoritemsmockup.PNG"/>

Vendor Stock Page

<img src="images/profilepagemockup.PNG"/>

Profile Page

Later we implemented some of these pages in Meteor.  We did not implement databases yet, so the recipe cards and user pages are currently hardcoded.

The first page we completed was the [landing page](http://constrainedcooking.meteorapp.com/#/).  We used Photoshop to create the Constrained Cooking title, and found vector icons to add to our website descriptions.  We plan on adding more to the landing page later such as linking icons to certain pages and maybe having a running feed of new recipes.

<img src="images/landingpage.PNG"/>

Next, we implemented the recipe [home page](http://constrainedcooking.meteorapp.com/#/list).  This shows the recipes as cards with large pictures, descriptions, and tags at the bottom.  The recipes displayed are currently hard coded.  We also plan on turning the tag section into active buttons so a user can click them and filter by tags.

<img src="images/recipehome.PNG"/>

The system also has a vendor role.  The page below shows how they can fill a form to [add an ingredient](http://constrainedcooking.meteorapp.com/#/addvendoritem) that they sell along with viewing a [list](http://constrainedcooking.meteorapp.com/#/listvendor) of items they have.

<img src="images/additem.PNG"/>

Lastly, we also implemented a view [profile page](http://constrainedcooking.meteorapp.com/#/profileview).  This shows general information of the person's account.  It's currently in a card format, but we plan on changing it into a larger diaply which has a person's general information, along with dietary habits, and favorited recipes.

## [Milestone 2: Add Functionality](https://github.com/constrainedcooking/constrainedcooking/projects/2)

This milestone started on April 12, 2018 and ended on ...


# About the Team

Our team is comprised of Aidan Akamine, Collin Takasaki, Cristina McLaughlin, and Brandon Kang.

Aidan plans to assist in database management and page implementation.

Collin plans to contribute his coding and culinary skills.

Cristina plans to help with design and layout.  Tweaking colors, finding pictures, and fixing padding and margins are some of her favorite things to do.

Brandon ...
