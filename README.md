# Incorporating Fontawesome & Bootstrap in Anguar application


Font Awesome is the Internet's icon library and toolkit that can be easily used by developers.

Here is the list of icon categories :

> Sold - <font color="grey"> These icons are completly filled.</font>

> Regular - <font color="grey"> These icons are normal icons and less filled as compared to solid icons.</font>

>Light - <font color="grey">These icons are light weight which are not filled.</font>

>Thin - <font color="grey">These icons have very thin outline.</font>


Here are the steps to install font awesome in angular application.

If you want to Scaffold a new angular application [Click Here](https://github.com/PatternsTechGit/PT_AngularCLI)

<font size="5" color="grey">**Step 1**</font> 


Install npm package using command as below :
```
        npm i @fortawesome/fontawesome-free
```
 Once the package is installed, you will see font-awesome folder in node_module folder as below :

![Modules Folder](https://user-images.githubusercontent.com/100709775/157256091-e973168e-38a6-4457-b43d-29abb4d3e4cb.png)

<font size="5" color="grey">**Step 2**</font>  
Import .css file in angular.json file :

```javascript
     "styles": [
              "src/styles.css",
              "node_modules/@fortawesome/fontawesome-free/css/all.min.css"
            ]
```
Styles array is basically used for including external stylesheets.


As there are alot of files in @fontawesome/fontawesome-free/css folder

we have .css files agains each icon catagory of fontawesome and there are .min.css versions are as well. Here we are using only 'all.min.css'

<font size="5" color="grey">**Step 3**</font>  
As we are making a banking application and in a bank application we will have links to navigate to different components (e.g. create account, manage account) of our application.

To show the links we will be using font-awesome icons in app.component.html


```javascript
 <ul class="fa-ul">
  <li><i class="fas fa-clock"></i> Create Account</li>
  <li><i class="fas fa-free-code-camp"></i> Manage Account</li>
  <li><i class="fas fa-thumbs-up"></i> Create User</li>
  <li><i class="fa fa-unlock"></i> Invoice</li>
</ul>
```

Run the project and check the fontawesome working as below :

![1](https://user-images.githubusercontent.com/100709775/157669867-fb2a7088-c045-4dd1-b9f7-e1aa66bd08ab.png)


if you want to use font-awesome using HTML markup click here  
https://www.angularjswiki.com/angular/how-to-use-font-awesome-icons-in-angular-applications/




# Bootstrap
Bootstrap is the most popular CSS Framework for developing responsive and mobile-first websites. For more details [Click Here](https://getbootstrap.com/)

Here are the steps to install bootstrap in angular application.

<font size="5" color="grey">**Step 1**</font> 

install npm package using command as below :
```
npm install bootstrap
```
This will intall latest library of bootstrap.

<font size="5" color="grey">**Step 2**</font> 

import .css file in angular.json file :

```javascript
     "styles": [
              "src/styles.css",
              "./node_modules/bootstrap/dist/css/bootstrap.css"
            ]
```
<font size="5" color="grey">**Step 3**</font> 

Add buttons in app.component.html to confirm bootstrap is working.
Here btn-primary,btn-secondary,btn-success are the bootstrap styles for buttons, where as 'ml-5' is bootstrap style for spacing. for more bootstrap button styles [Click Here](https://www.w3schools.com/bootstrap5/bootstrap_buttons.php) and for spacing style [Click Here](https://getbootstrap.com/docs/4.0/utilities/spacing/)

```javascript
<div class="container">
<button type="button" class="ml-5 btn btn-primary">Primary</button> <br><br>
<button type="button" class="ml-5 btn btn-secondary">Secondary</button> <br><br>
<button type="button" class="ml-5 btn btn-success">Success</button>
</div>

```

Run the project and check the bootstrap & margin-left is working as below :

![Web_Bootstrap](https://user-images.githubusercontent.com/100709775/157658547-9966535f-5091-4cd1-81af-6d3b384a0029.png)

