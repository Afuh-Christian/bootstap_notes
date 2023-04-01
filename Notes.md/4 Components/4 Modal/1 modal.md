# ....... A modal is like a custom pop up window .... 


# MODAL 
 modal                          .... id = "modal"
    modal-dialog
        modal-content 

# Button to toggle modal .. 
 btn btn-primary 
 data-bs-toggle = "modal" 
 data-bs-target = "#modal"          .... this is a selector ...


   <button class="btn btn-primary" 
      data-bs-toggle="modal"
      data-bs-target="#modal">OpenModal</button>
      <div class="modal" id="modal">
        <div class="modal-dialog">
          <div class="modal-content">
            Test
          </div>
        </div>
      </div>



# .... Styling the modal .. 

  - "modal fade"         .... to make it have  a nice appear and disappear  animation 

<div class="modal fade" id="modal">
        <div class="modal-dialog">
          <div class="modal-content">
            Test
          </div>
        </div>
      </div>


 # separate modal into different sections ..... header, body,footer ..


 modal                          
    modal-dialog
        modal-content 
            modal-header
            modal-body
            modal-footer

 <div class="modal-content">
              <h3 class="modal-header">Header</h3>
              <div class="modal-body">Body </div>
              <h4 class="modal-footer">Footer</h4>
          </div>


# we can create a close btn in  the header of the modal .... 

    btn-close 
    data-bs-dismiss = "modal"                 ... to close it .
    data-bs-target = "#modal"          .... this is a selector ...

<div class="modal-header">Header
                <button class="btn-close" data-bs-dismiss="modal"
                data-bs-target = "#modal">
                </button>
</div>



# full code ... .
  <button class="btn btn-primary" 
      data-bs-toggle="modal"
      data-bs-target="#modal">OpenModal</button>
      <div class="modal fade" id="modal">
        <div class="modal-dialog">
          <div class="modal-content">
              <div class="modal-header">Header
                <button class="btn-close" data-bs-dismiss="modal" data-bs-target = "#modal"></button>
              </div>
              <div class="modal-body">Body </div>
              <h4 class="modal-footer">Footer</h4>
          </div>
        </div>
      </div>
# ...........



# NB ...any button for closing the modal needs to have ....
data-bs-dismiss="modal"



# To make the modal centered ... 

 - modal-dialog modal-dialog-centered



# To make modal scrollable ... (if we have  lot's of content ... ) 

 - modal-dialog modal-dialog-scrollable


<button class="btn btn-primary" 
      data-bs-toggle="modal"
      data-bs-target="#modal">OpenModal</button>
      <div class="modal fade" id="modal">
        <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
          <div class="modal-content">
              <div class="modal-header">Header
                <button class="btn-close" data-bs-dismiss="modal" data-bs-target = "#modal"></button>
              </div>
              <div class="modal-body">Body </div>
              <h4 class="modal-footer">Footer</h4>
          </div>
        </div>
      </div>


# We can change size of the modal ...  

 - modal modal-sm
 - modal modal-lg

# we can set modal to fullscreen based on break points ...

 - modal-dialog modal-fullscreen 
 - modal-dialog modal-fullscreen-lg-down 
 - modal-dialog modal-fullscreen-sm-down
 etc .... 

# NB .. down must be added to this break points for this to work .. 


this will be placed with the modal-dailog class






