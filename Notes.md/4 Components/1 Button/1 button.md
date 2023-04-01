
# Button ... 

<button class="btn btn-primary">Test</button>

Like the table .... we have many themes for the btn .... 

 - btn btn-primary  =  sky blue btn 
 - btn btn-danger =   light red btn 
 - btn btn-secondary = 
 - btn btn-success = 
 - btn btn-warning = 
 - btn btn-info = 
 - btn btn-light = 
 - btn btn-dark = 


# ...Can be used on an anchor tag .... 

 <a class="btn btn-primary">Test</a>

 this means you can style a link to look like a btn .. 


 # ... Make a button look like a link .... 

 - btn btn-link

<button class="btn btn-link">Test</button>

# ... Size alter ..
- btn btn-sm
- btn btn-lg

<button class="btn btn-primary btn-sm">Test</button>
<button class="btn btn-primary btn-lg">Test</button>


# ... make an outline btn ... when we click it shows the them we asigned to it ..... 

<button class="btn btn-outline-primary">Test</button>

- btn btn-outline-primary 

Also has all the the thems .... 

 - btn btn-outline-primary  =  sky blue btn 
 - btn btn-outline-danger =   light red btn 
 - btn btn-outline-secondary = 
 - btn btn-outline-success = 
 - btn btn-outline-warning = 
 - btn btn-outline-info = 
 - btn btn-outline-light = 
 - btn btn-outline-dark =


 #      NB ... buttons in boostrap handle the    .. disabled state ....

<button class="btn btn-primary" disabled>Test</button>

 #       NB ... since the anchor tag does not have  the disabled attribute ....  we add the disabled class .... 

<a class="btn btn-primary disabled">Test</a>




# ... To make a button toggle between different states ...active and inactive ... 

 - we will use btn btn-outline-primary so it will be visible

 - data-bs-toggle = "button"

<button class="btn btn-outline-primary" data-bs-toggle="button">Test</button>

this is very important to use ...try it and see how you can apply this in applications .... 


# if you want the button to be ative initially ... 
- active       => add this class in the button 
- aria-pressed = "true"  

<button class="btn btn-outline-primary active" aria-pressed="true" data-bs-toggle="button">Test</button>
