# Basic .... 

 - navbar navbar-expand

 Nb ...  navbar-expand makes the ul elements to be placed horizontally ......

  <nav class="navbar navbar-expand">
    <div class="container">
      Nav text ....
    </div>
  </nav>


  # Sections in the navbar ..... 

- navbar navbar-expand 
    container 
        -navbar-brand        ..... for website name or logo
        -navbar- nav         ..... list of all links ...
            -nav-item
                -nav-link   

<nav class="navbar navbar-expand">
      <div class="container">
        <div class="navbar-brand">Zii</div>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">Help</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">About</a>
          </li>
        </ul>
      </div>
    </nav>


# If we want to make a link active e.g like to denote that we are on the home page .. add "active" class to the Nav Link ..

- Also add the aria attribute for the specific page .....

 nav-link active
 aria-current = "page" 

 <a class="nav-link active"
    aria-current = "page"
    >Home</a>

# if you wish to disable a link ... and disabled class ... 

 nav-link disabled

<a class="nav-link disabled">Help</a>


# If you wish to add plain text into the nav bar .... 

 navbar-text 


<div class="navbar-text">Test</div>



# full code .

  <nav class="navbar navbar-expand">
      <div class="container">
        <div class="navbar-brand">Zii</div>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active"
            aria-current = "page"
            >Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled">Help</a>
          </li>
          <li class="nav-item">
            <a class="nav-link">About</a>
          </li>
        </ul>
        <div class="navbar-text">Test</div>
      </div>
    </nav>

# ..............


