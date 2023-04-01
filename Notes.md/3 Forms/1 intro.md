https://getbootstrap.com/docs/5.2/forms

# 22:00

   # forms

   form-label = for label tags
   form-control = for input tags

   #<form action="">
      <label for="email" class="form-label">Email</label>
      <input type="email" id="email" class="form-control">
      <button>submit</button>
     </form>

   # to controll size of input tag 

   form-control-sm   = small input tag (height)
   form-control-lg  = large input tag (height)

   #<form action="">
      <label for="email" class="form-label">Email</label>
      <input type="email" id="email" class="form-control-lg" >
      <label for="email" class="form-label">Email</label>
      <input type="email" id="email" class="form-control-sm" >
      <button>submit</button>
     </form>

    form-control-plaintext  = makes the form like a plain text (advisible : it should have a value and should be readonly)
   
   #<form action="">
      <label for="email" class="form-label">Email</label>
      <input type="email" id="email" value="Afuh Christain"     readonly class="form-control-plaintext" >
      <button>submit</button>
     </form>

# input, select and other forms  takes in attributs like 
    - disabeled 
    - readonly
     etc



 # COLOR PIcker .... 
 - if the form type is color picker .... 

 type = "color" 
 form-control-color 

  #<input type="color" class="form-control-color">




# Range input ... 

type = "range" 
form-range 

 #<input type="range" class="form-range" >



# Select input .................

form-select 
form-select-sm = small
form-select-lg = large

 #<select class="form-select-sm">
        <option>One</option>
        <option>Two</option>
        <option>Three</option>
      </select> 



# Checkbox ...  ........

 -   form-check-input = for the input tag 
 -   form-check-label = for the label tag 

 - Always use the form-check on the classes of the input and label when using check boxes ....

<form action="">
      <input type="checkbox" class="form-check-input">
      <label for="email" class="form-check-label">Email</label>
     </form>


 - wrap it all in the div with form-check class to have proper styling .... 

 <form action="">
      <div class="form-check">
      <input type="checkbox" class="form-check-input">
      <label for="email" class="form-check-label">Email</label>
    </div> 
    </form>


- we can turn this into a toggle switch by using .... 
    - form-switch = this should be in the div wrapping      the input and label of the  checkbox

 <form action="">
      <div class="form-check form-switch">
      <input type="checkbox" class="form-check-input">
      <label for="email" class="form-check-label">Email</label>
    </div> 
    </form>   



- If  we have multiple checkboxes we can make them inline .. 
    - form-check-inline  = inside class of each div round each checkbox

 <form action="">
      <div class="form-check form-switch form-check-inline">
      <input type="checkbox" class="form-check-input">
      <label for="email" class="form-check-label">Email</label>
    </div> 
      <div class="form-check form-switch form-check-inline">
      <input type="checkbox" class="form-check-input">
      <label for="email" class="form-check-label">Email</label>
    </div> 
      <div class="form-check form-switch form-check-inline">
      <input type="checkbox" class="form-check-input">
      <label for="email" class="form-check-label">Email</label>
    </div> 
    </form>




# Input Group .... .....................................


