# Incorporating Fontawesome & Bootstrap in Anguar application


Font Awesome is the Internet's icon library and toolkit that can be easily used by developers.

Here is the list of icon categories :

> Sold - <font color="grey"> These icons are completly filled.</font>

> Regular - <font color="grey"> These icons are normal icons and less filled as compared to solid icons.</font>

>Light - <font color="grey">These icons are light weight which are not filled.</font>

>Thin - <font color="grey">These icons have very thin outline.</font>


Here are the steps to install font awesome in angular application.

<font size="5" color="grey">**Step 1**</font> 


install npm package using command as below :

        npm i @fortawesome/fontawesome-free

<font size="5" color="grey">**Step 2**</font>  
import .css file in angular.json file :

```javascript
     "styles": [
              "src/styles.css",
              "node_modules/@fortawesome/fontawesome-free/css/all.css"
            ]
```
Once the package is installed, you will see font-awesome folder in node_module folder as below :

![Modules Folder](https://user-images.githubusercontent.com/100709775/157256091-e973168e-38a6-4457-b43d-29abb4d3e4cb.png)


As there are alot of files in @fontawesome/fontawesome-free/css folder

## all.css
This files contains styles of all categories of icons.

## all.min.css
This files contains styles of all categories of icons but its compressed verison of all.css file which does not have any space in it.

## solid.css
This files contains styles for solid icons only.

## regular.css
This files contains styles for regular icons only.

<font size="5" color="grey">**Step 3**</font>  
As we are making a banking application and in a bank application we will have links to navigate to different components (e.g. create account, manage account) of our application.

To show the links we will be using font-awesome icons.


```javascript
 <ul class="fa-ul">
  <li><i class="fas fa-clock"></i> Create Account</li>
  <li><i class="fas fa-free-code-camp"></i> Manage Account</li>
  <li><i class="fas fa-thumbs-up"></i> Create User</li>
  <li><i class="fa fa-unlock"></i> Invoice</li>
</ul>
```

Run the project and check the fontawesome as below :

![Web_fontawesome](https://user-images.githubusercontent.com/100709775/157281229-647dd4d9-8641-4961-8fe4-9e5e2a42fa14.PNG)


if you want to use font-awesome using HTML markup click here  
https://www.angularjswiki.com/angular/how-to-use-font-awesome-icons-in-angular-applications/




# Bootstrap
Bootstrap is the most popular CSS Framework for developing responsive and mobile-first websites.

Here are the steps to install bootstrap in angular application.

<font size="5" color="grey">**Step 1**</font> 

install npm package using command as below :
```
npm install bootstrap
```

<font size="5" color="grey">**Step 2**</font> 

import .css file in angular.json file :

```javascript
     "styles": [
              "src/styles.css",
              "./node_modules/bootstrap/dist/css/bootstrap.css"
            ]
```
<font size="5" color="grey">**Step 3**</font> 

Add buttons to confirm bootstrap is working.

```javascript
<div class="container">
<button type="button" class="ml-5 btn btn-primary">Primary</button> <br><br>
<button type="button" class="ml-5 btn btn-secondary">Secondary</button> <br><br>
<button type="button" class="ml-5 btn btn-success">Success</button>
</div>

```

Run the project and check the bootstrap & margin-left is working as below :

![Web_Bootstrap](https://user-images.githubusercontent.com/100709775/157279992-a246ed18-7279-45b1-a842-d4ed71195244.png)
