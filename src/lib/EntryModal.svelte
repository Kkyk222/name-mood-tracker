
<div class="modal fade" id="newEntry" tabindex="-1">
    <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
   	 <div class="modal-content">
   		 <div class="modal-header">
   			 <h5 class="modal-title">New Entry</h5>
   			 <button type="button" class="btn-close" data-bs-dismiss="modal" />
   		 </div>

   		 <div class="modal-body">
   			 
<!-- Date Input -->
<div class="row">
    <div class="col">
   	 <form class="form-floating">
   		 <input type="number" class="form-control" id="dayInput" />
   		 <label for="dayInput">Day</label>
   	 </form>
    </div>
    <div class="col">
   	 <form class="form-floating">
   		 <input type="number" class="form-control" id="monthInput" />
   		 <label for="monthInput">Month</label>
   	 </form>
    </div>
    <div class="col">
   	 <form class="form-floating">
   		 <input type="number" class="form-control" id="yearInput" />
   		 <label for="yearInput">Year</label>
   	 </form>
    </div>
</div>


<!-- Mood Scale -->
<div class="row mt-3 text-center">
    <h5>How was your day?</h5>
    <h1 class="display-1">{emoji}</h1>
</div>
<div class="row px-5">
    <div class="btn-group mt-2 mb-3" role="group">
        <!-- Worst Mood -->
        <!-- Bad Mood -->
        <!-- Okay Mood -->
        <!-- Good Mood -->
        <!-- Best Mood -->
   </div>
</div>


   		 </div>

   		 <div class="modal-footer">
   			 <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cancel</button>
   			 <button type="button" class="btn btn-primary">Add</button>
   		 </div>
   	 </div>
    </div>
</div>

