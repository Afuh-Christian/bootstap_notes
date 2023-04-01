https://getbootstrap.com/docs/5.2/content/tables/


# table .. 

# ....There are 8 different themes you can use .... 
 - table table-primary  =  sky blue table 
 - table table-danger =   light red table 
 - table table-secondary = 
 - table table-success = 
 - table table-warning = 
 - table table-info = 
 - table table-light = 
 - table table-dark = 

#<table class="table table-secondary">
    <thead>
      <tr>
        <td>First</td>
        <td>Last</td>
        <td>Age</td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Kyle</td>
        <td>Cook</td>
        <td>27</td>
      </tr>
      <tr>
        <td>Chris</td>
        <td>run</td>
        <td>22</td>
      </tr>
      <tr>
        <td>Napal</td>
        <td>tenis</td>
        <td>45</td>
      </tr>
     
    </tbody>
   </table>
  </div>

  # .............



# we can apply this to the to the tr & td .... as we can see from the doc ..... 

https://getbootstrap.com/docs/5.2/content/tables/


# stuff you can apply only to the table ... 

 - table table-striped    =   colours one row , skips and another skips again and so on .. 

 - table table-striped-columns  = same as above but with columns...

 - table table-hover = highlights a row when you hover over it

 - table table-bordered = adds extra borders to the table ..
 
 - table table-borderless = removes all borders on the table ..


 # rows .... 

 - table-active = thesame color as when you hover on it but is permanent ..


 # To make the table responsive ... 
 this will help your table shrink or expand & or add scrolling(horizontal) when the window size reduces or increases....

 - put the table within a div tag of class= "table-responsive" 

 #<div class="table-responsive">
    <table class="table"></table>
 </div>


 - we can also append the break  points to the table-responsive to set at what screen size we want the table to be responsive at .. 



 # stuff to apply only on the head and body of table ... 

  - table-group-divider  =  this puts a line above the component(tag (thead or tbody)) is was placed in ... eg 


     <table class="table">
    <thead class="table-group-divider">
      <tr>
        <td>First</td>
        <td>Last</td>
        <td>Age</td>
      </tr>
    </thead>
    <tbody class="table-group-divider">
      <tr>
        <td>Kyle</td>
        <td>Cook</td>
        <td>27</td>
      </tr>
      <tr>
        <td>Chris</td>
        <td>run</td>
        <td>22</td>
      </tr>
      <tr>
        <td>Chris</td>
        <td>run</td>
        <td>22</td>
      </tr>
      <tr>
        <td>Chris</td>
        <td>run</td>
        <td>22</td>
      </tr>
      <tr>
        <td>Napal</td>
        <td>tenis</td>
        <td>45</td>
      </tr>
     
    </tbody>
   </table>
  </div>