# As we saw before the .. navbar-expand is what makes the ul items to have a horizontally placed 

so we will use break point to include the "navbar-expand" ... when the screen is large and include slide menu when the screen  is small .....  


"navbar-expand-md"   =  at meduim and above ..... 

 
<nav class="navbar navbar-expand-md navbar-dark bg-dark">
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
        <!-- <div class="navbar-text">Test</div> -->
      </div>
    </nav>


# Now for the small screen , we need to create  a toggle for the slider menu .... we will use the collapase class as we did in the previous section ...... 


# 1 enclose the <ul></ul> inside a <div> with class "collapse navbar-collapse" 


  <div class="collapse navbar-collapse" id="nav">
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
      </div>


# Now the button to toggle ... 

        class="navbar-toggler" 
        data-bs-toogle="collapse"
        data-bs-target="#nav"
        aria-controls="nav"

 <button class="navbar-toggler" 
        data-bs-toggle="collapse"
        data-bs-target="#nav"
        aria-controls="nav"
        ></button>
        <div class="collapse navbar-collapse" id="nav">
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
      </div>


# Navbar icon ... 

 class = "navbar-toggler-icon"

<span class="navbar-toggler-icon"></span>






# ..full code ....

<nav class="navbar navbar-expand-md navbar-dark bg-dark">
      <div class="container">
        <a href="#" class="navbar-brand">Brand</a>
        <button class="navbar-toggler" 
        data-bs-toggle="collapse"
        data-bs-target="#nav"
        aria-controls="nav"
        aria-label="Expand Navigation"
        >
      <span class="navbar-toggler-icon"></span>
      </button>
        <div class="collapse navbar-collapse" id="nav">
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
      </div>
        <!-- <div class="navbar-text">Test</div> -->
      </div>
    </nav>


# ...