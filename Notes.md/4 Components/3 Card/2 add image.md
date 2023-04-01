# In most card on the web .... we usually have images in them ... 


So we will set a 
card-image-top  in an img tag above the card body ....


 <div class="card" style="width:400px;">
        <img src="pc.jpg" class="card-img-top">
        <div class="card-body">
          <h2 class="card-title">Afuh Chris</h2>
          <span class="card-subtitle">Ub Student </span>
          <div class="card-text">
          The course provides an introduction to 
          scientific computing. Several numerical
              </div>
            </div>
     </div>

# so now the structure is .. 

card 
    card-image-top 
    card-body
        card-title 
        card-subtitle
        card-text



# if we want our image to be at the bottom 

- card-image-bottom 
- img tag should be below the body ...

<div class="card" style="width:400px;">
        <div class="card-body">
          <h2 class="card-title">Afuh Chris</h2>
          <span class="card-subtitle">Ub Student </span>
          <div class="card-text">
          The course provides an introduction to 
          scientific computing. Several numerical
              </div>
            </div>
        <img src="pc.jpg" class="card-img-bottom">
     </div>
   




# If we want image overlay ... (let the text be on top of the image ....)

img tag   =  card-img 
body tag  = card-body card-img-overlay

<div class="card" style="width:400px;">
     # <img src="pc.jpg" class="card-img">
     #   <div class="card-body card-img-overlay">
          <h2 class="card-title">Afuh Chris</h2>
          <span class="card-subtitle">Ub Student </span>
          <div class="card-text">
          The course provides an introduction to 
          scientific computing. Several numerical
              </div>
            </div>
     </div>