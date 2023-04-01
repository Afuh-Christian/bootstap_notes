# Work similarly to buttons .... ......................

alert alert-dark

 - alert alert-primary  =  sky blue alert 
 - alert alert-danger =   light red alert 
 - alert alert-secondary = 
 - alert alert-success = 
 - alert alert-warning = 
 - alert alert-info = 
 - alert alert-light = 
 - alert alert-dark = 


# A real functioning alert . ...........................
    div 
    alert alert-success alert-dismissible 
    role = "alert" 

    button 
    btn-close 
    aria-label = "close" 
    data-bs-dismiss = "alert"

 <div class="alert alert-success alert-dismissible" 
    role="alert">Alert
      <button class="btn-close" aria-label="close"
      data-bs-dismiss="alert"></button>
    </div>

# add more info in the alert .. e.g a link ... 

  alert-link 


<div class="alert alert-success alert-dismissible" 
    role="alert">Alert
    <a href=""class="alert-link">Go here to find out more ..</a>
      <button class="btn-close" aria-label="close"
      data-bs-dismiss="alert"></button>
    </div>




# for the alert to fade out .... 

 "fade"  

 "show"

 you must add the show for it to work ... 

#<div class="alert alert-success alert-dismissible fade show" 
    role="alert">
    <h1>Alert</h1>
    <a href=""class="alert-link">Go here to find out more ..</a>
      <button class="btn-close" aria-label="close"
      data-bs-dismiss="alert"></button>
    </div>