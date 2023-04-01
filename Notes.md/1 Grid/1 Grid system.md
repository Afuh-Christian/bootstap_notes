 # Grid system .... 
 Has 3 main section ... 

# 1 ...........- container  = wraps the grid system 
    has styles at every media query breakpiont ... 
   
-  container-fluid =  contianer width is set to 100% at all times
   
- container-md = width is set to 100% when the container is half the actual window width
    
-  container-sm = (width == 100%) when screen width is above about 1/4
    
-   container-lg =  (width == 100%) when screen width is above about 3/4
    
-   container-xl = (width == 100%) when screen width is above about 7/8
    
-   container-xxl = (width == 100%) when screen width is above about 15/16





















# 2........... - rows     = Individual rows in you're grid 

 -uses flexbox to lay everything out ...
 -boostrap grid is based on a 12 col system ..
    -Every single row in bootstrap has 12 hard coded columns (about 1/12 of you're sreen is 1 column by defualt ..)

   # i- setting a amount of cols .... 

   -  row row-cols-2 
   - row row-cols-2 row-cols-lg-4 = adding a break point when the screen size gets above lg ....
    #<div class="row row-cols-2 row-cols-lg-4">
        <!-- <div class="col-lg-4  col-8"><div class="box"></div></div>
        <div class="col-10"><div class="box"></div></div>
        <div class="col-4"><div class="box"></div></div>
        <div class="col-8"><div class="box"></div></div> -->
        <!-- <div class="col-sm-4 col"><div class="box"></div></div>  -->
        <div class="col"><div class="box"></div></div>
        <div class="col"><div class="box"></div></div>
        <div class="col"><div class="box"></div></div>
        <div class="col"><div class="box"></div></div>
        <div class="col"><div class="box"></div></div>
        <div class="col"><div class="box"></div></div>
        <div class="col"><div class="box"></div></div>
        <!-- <div class="col-3 offset-3"><div class="box"></div></div> -->
       
     </div>
    # ii - vertical gap between the wraped items in the row ...
    gy-0
    gy-1
    gy-lg-2 = adding break point when screen size is > lg 
   
    # iii - Horizontal gap between the wraped items in the row ...
    gx-0
    gx-1
    gx-lg-2 = adding break point when screen size is > lg 
   
    # iv - Vertical & Horizontal gap between the wraped items in the row ...
    g-0
    g-1
    g-lg-2 = adding break point when screen size is > lg 

















# 3 ..............- columns = columns in the grid ... 
- We can make a specific column to take up a number of spaces ...     
  - col-6    = spans half of the columns of that row ... 6/12  

        # - Styling the collumns ..
  - col-auto = to fit content width size 

  # let's set a style for the col if below lg  

  - col-lg-4  col-8  = spans 4/12 of columns if window width > about 600  , else it will span 8/12

  # NB ... the col-8 for the else needs to be hardcoded else it will defualt to col-12 if the lg condition is false ...

  # NB ... the larger break points always override the smaller break points .... 

  # NB ... if the sum of the total (10 + 4 + 8) > 12 ...it will rep and go to next line because each row is assigned 12 cols only .. 
   <div class="col-10"><div class="box"></div></div>
    <div class="col-4"><div class="box"></div></div>
    <div class="col-8"><div class="box"></div></div>




 # ..OFFSET .... 
   we use this to push an element of it's natural position ... 

    offset-3  = moves 3/12 columns away ...
    offset-13  = moves 13/12 columns away .. moves to a new line .... ...

   #<div class="col-3"><div class="box"></div></div>
    <div class="col-3 offset-3"><div class="box"></div></div>
       



 Boostrap already has media queries set up for the container ...as the screen alters .. the padding and other set properties change too ... 

 each container has a style attarched to it .. e.g container-fluid ...


 


 #  NB ...  Rows can be nested within a column .... 

   
#<div class="container">
     <div class="row row-cols-2 row-cols-lg-4 gy-4">
        <div class="col"><div class="box"></div></div>
        <div class="col">
        <div class="row">
            <div class="col"><div class="box"></div></div>
            <div class="col"><div class="box"></div></div>
        </div>
        </div></div>
        <!-- <div class="col-3 offset-3"><div class="box"></div></div> -->
     </div>
    </div>




