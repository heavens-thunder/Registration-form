<template>
  <p>Contact Information</p>
  <form method="POST">
  <div class="row">
    <div class="col-md-3">First Name <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
    </div>
  </div>

  <div class="mt-3"></div>

  <div class="row">
    <div class="col-md-3">Last Name <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
    </div>
  </div>

  <div class="mt-3"></div>

  <div class="row">
    <div class="col-md-3">Address 1 <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
    </div>
  </div>

  <div class="mt-3"></div>

  <div class="row">
    <div class="col-md-3">Address 2 <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
    </div>
  </div>

  <div class="mt-3"></div>

  <div class="row">
    <div class="col-md-3">City <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
    </div>
  </div>

  <div class="mt-3"></div>

  <div class="row">
    <div class="col-md-3">State or Province <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
    </div>
  </div>

  <div class="mt-3"></div>

  <div class="row">
    <div class="col-md-3">Zip <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required  />
    </div>
  </div>

  <div class="mt-3"></div>

  <div class="row">
    <div class="col-md-3">Country <sup>*</sup></div>
    <div class="col-md-9">
      <input type="text" class="form-control" required />
    </div>
  </div>
  
<div class="mt-3"></div>

  <div class="col-md-3">Gender <sup>*</sup></div>
 <div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="radio"
            id="female"
            value="female"
            name="gender"
          />
          <label class="form-check-label" for="female">Female</label>
        </div>
<div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="radio"
            id="male"
            value="male"
            name="gender"
          />
          <label class="form-check-label" for="male">Male</label>
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
  name: "Contactnfo",
};
</script>

<style>
</style>