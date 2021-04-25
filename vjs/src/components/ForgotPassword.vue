<template>
  <div class="vue-tempalte">
    <div class="testt">
      <form>
        <h3>{{ tittle }}</h3>

        <div class="form-group">
          <label>{{ mail }}</label>
          <input type="email" class="form-control form-control-lg" />
        </div>

        <button type="submit" class="btn btn-dark btn-lg btn-block">
          {{ reset }}
        </button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tittle: "Forgot password",

      reset: "Reset password",
      mail: "Email adress"
    };
  }
};
</script>
