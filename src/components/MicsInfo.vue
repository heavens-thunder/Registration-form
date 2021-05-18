<template>
  <p>Mics. Information</p>

  <form method="POST">
    <div class="row">
      <div class="col-md-3">Annual Household Income <sup>*</sup></div>
      <div class="col-md-9">
        <select
          class="form-select"
          aria-label="Default select example"
          required
        >
          <option selected value="">select...</option>
          <option value="1">10000</option>
          <option value="2">20000</option>
          <option value="3">30000</option>
          <option value="3">40000</option>
          <option value="3">50000</option>
          <option value="3">60000</option>
          <option value="3">70000</option>
        </select>
      </div>
    </div>

    <div class="mt-3"></div>

    <div class="row">
      <div class="col-md-3">Interests<sup>*</sup></div>
      <div class="col-md-9">
        <!-- Interests options start-->
        <!-- 1. Shopping/Fashion -->
        <div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="checkbox"
            id="shopping"
            value="shopping"
            name="interests"
           />
          <label class="form-check-label" for="shopping"
            >Shopping / Fashion</label
          >
        </div>
        <!-- !end -->
        <!-- 2. Sports -->
        <div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="checkbox"
            id="sports"
            value="sports"
            name="interests"
          />
          <label class="form-check-label" for="sports">Sports</label>
        </div>
        <!-- !end -->
        <!-- 3. Travel -->
        <div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="checkbox"
            id="travel"
            value="travel"
            name="interests"
           />
          <label class="form-check-label" for="travel">Travel</label>
        </div>
        <!-- !ends -->
        <!-- Interests options end -->
      </div>
    </div>

    <div class="mt-3"></div>
    <div class="row">
      <div class="col-md-3">Eye Color<sup>*</sup></div>
      <div class="col-md-9">
        <!-- Eye colors options start-->
        <div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="checkbox"
            id="brown"
            value="brown"
            name="eyecolor"
            />
          <label class="form-check-label" for="brown">Brown</label>
        </div>
        <div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="checkbox"
            id="blue"
            value="blue"
             name="eyecolor"
           />
          <label class="form-check-label" for="blue">Blue</label>
        </div>
        <div class="form-check form-check-inline">
          <input
            class="form-check-input"
            type="checkbox"
            id="black"
            value="black"
             name="eyecolor"
          />
          <label class="form-check-label" for="black">Black</label>
        </div>
        <!-- Eye colors options end -->
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
  name: "MicsInfo",
};
</script>

<style>
</style>