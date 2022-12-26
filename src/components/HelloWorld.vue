<template>
  <main>
    <section class="p-5 h-100">
      <div class="container mt-5 ">
        <div class="d-sm-flex justify-content-between">
          <div class="heading my-auto">
            <h1 class="text-sm-center text-md-start ">Welcome to<span class="text-warning">Profile Viewer</span></h1>
            <p class="lead text-md-start">All your data in one place</p>
            <!-- LogIn Form -->
            <div class="mt-5">
              <div class="pe-5">
                <h1 class="mb-5 text-success">LogIn To Access the Site,</h1>
                <div>
                  <div class="input-group mb-3">
                    <span class="input-group-text">Email</span>
                    <input class="form-control" type="email" id="email" required />
                  </div>
                  <div class="input-group mb-3">
                    <span class="input-group-text">Password</span>
                    <input class="form-control" type="password" id="password" required />
                  </div>
                  <button class="btn btn-lg bg-success rounded border text-white mt-3" type="submit" id="log-in">
                    Log in
                  </button>
                </div>
                <div class="w-25 mx-auto">
                  <hr>
                </div>
                <div class="mt-2 wh">
                  <p><small class="mx-auto">or</small></p>
                  <button class="btn btn-lg mx-auto rounded border bg-success text-white" center>Log In with Google</button>
                </div>
              </div>
            </div>
          </div>
          <img class="w-50 img-fluid d-none d-sm-block rounded-1 " src="../assets/undraw_join_re_w1lh.svg" alt="">
        </div>
      </div>
    </section>
  </main>

</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
    }

  },

  methods: {

  },
}
</script>
<style scoped>
.gcolor{
  margin: 0 auto;
}
.wh{
  width:fit-content;
  margin: 0 auto;
}
</style>