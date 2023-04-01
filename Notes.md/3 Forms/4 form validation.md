# ...



# with bootstrap ..... 

invalid form 
-  is-invalid = add this to the class of the input tag 
    (gives a read border(outline))
<input type="email" id="email" class="form-control is-invalid">

valid form ... 
-  is-valid = add this to the class of the input tag 
   (gives a blue border and a tick)
<input type="email" id="email" class="form-control is-valid">













# with js ....... Best method .......... 

form 
novalidate 

input 
required .. 

js code ...

#<form action="" novalidate>
      <div class="form-floating">
         <input type="email" placeholder="Place Email here" id="email" class="form-control" required>
         <label for="email"  class="form-label">Float label</label>
      </div>
          <button>sumbmit</button>
    </form>

<script>
  const form =  document.querySelector("form")
  form.addEventListener('submit', e => {
    if(!form.checkValidity()){
      e.preventDefault()
    }
    form.classList.add('was-validated')
  })

</script> 






# You can add  
   - invalid-feedback  
   - valid-feedback  

   NB ... they should be under the label and input ... 

<form action="" novalidate>
      <div class="form-floating">
         <input type="email" placeholder="Place Email here" id="email" class="form-control" required>
         <label for="email"  class="form-label">Float label</label>
        <div class="invalid-feedback">Invalid Email</div>
        <div class="valid-feedback">Valid Email</div>
        </div>
      <button>sumbmit</button>
    </form>
<script>
  const form =  document.querySelector("form")
  form.addEventListener('submit', e => {
    if(!form.checkValidity()){
      e.preventDefault()
    }
    form.classList.add('was-validated')
  })

</script> 
