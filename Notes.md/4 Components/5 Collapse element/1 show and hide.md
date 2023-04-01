# Basic show and hide element ... 

      data-bs-toggle="collapse" 
      data-bs-target="#row"      ..selector .....


<div class="container">
      <button class="btn btn-primary" 
      data-bs-toggle="collapse" 
      data-bs-target="#row"
      >Open/Close</button>

<div class="row" id="row">
        <div class="col">
          <div class="box">sdfa</div>
        </div>
      </div>
     </div>



# Add a fow other html properties ... 

      aria-expanded="true"
      aria-controls="#row"

To tell the sreen reader that the button is controlling the row ...


# Add the collapse class to the row ....

row collapse           ....  default to be already collapsed

row collapse show      ... makes the defualt to be expanded ..

  <div class="container">
      <button class="btn btn-primary" 
      data-bs-toggle="collapse" 
      data-bs-target="#row"
      aria-expanded="true"
      aria-controls="#row"
      >Open/Close</button>

<div class="row collapse show" id="row">
        <div class="col">
          <div class="box">sdfa</div>
        </div>
      </div>
     </div>




# If you wish to collapse many rows .... then you'll place .row as the selector ... 
 - this will aria-controls not to work anymore because two elements can't have thesame id .. 


  <div class="container">
<button class="btn btn-primary" 
      data-bs-toggle="collapse" 
      data-bs-target=".row"
      aria-expanded="true"
      aria-controls="#row"
      >Open/Close</button>

<div class="row collapse show" id="row">
        <div class="col">
          <div class="box">sdfa</div>
        </div>
      </div>
<div class="row collapse show" id="row">
        <div class="col">
          <div class="box">sdfa</div>
        </div>
      </div>
<div class="row collapse show" id="row">
        <div class="col">
          <div class="box">sdfa</div>
        </div>
      </div>
     </div>