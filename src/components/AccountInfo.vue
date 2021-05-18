<template>
 <p>Account Information</p>
 <form method="POST">
  <div class="row">
    <div class="col-md-3">Login Name <sup>*</sup> </div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
   
    </div>
    </div>

    <div class="mt-3"></div>
 
   <div class="row">
    <div class="col-md-3">Password<sup>*</sup> </div>
    <div class="col-md-9">
      <input type="Password" class="form-control" required />
    </div>
    </div>

    <div class="mt-3"></div>

      <div class="row">
    <div class="col-md-3">Confirm Password<sup>*</sup> </div>
    <div class="col-md-9">
      <input type="Password" class="form-control" required />
    </div>
    </div>

    <div class="mt-3"></div>

      <div class="row">
    <div class="col-md-3">Email Address<sup>*</sup> </div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
   
    </div>
    </div>

    <div class="mt-3"></div>

       <div class="row">
    <div class="col-md-3">Confirm Email<sup>*</sup> </div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
   
    </div>
    </div>
 
 <div class="mt-3"></div>

   <div class="d-grid gap-2 d-md-flex justify-content-md-end">
      <input class="btn btn-secondary me-md-2" type="reset" />
      <input class="btn btn-success" type="submit" />
    </div>
  </form>
</template>

<script>
export default {
  name: "AccountInfo"
};
</script>

<style>
</style>