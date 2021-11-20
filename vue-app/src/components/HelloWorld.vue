<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <section>
            <div class="box">
                <div>
                    <h3 id="login-h3">Please Log In</h3>
                    <div id="email">
                        <input type="text" placeholder="Email">
                    </div>
                    <br>
                    <div id="password">
                        <input type="text" placeholder="Password">
                    </div>
                    <br>
                    <div id="login-button-div">
                        <router-link to="/posts">Log In</router-link>
                    </div>
                    <br> 
                </div>
            </div>
        </section>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped src="../assets/css/HelloWorld.css">
/* @import '../assets/css/HelloWorld.css'; */
</style>
