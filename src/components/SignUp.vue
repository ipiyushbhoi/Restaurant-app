<template>
<img class="logo" src="../assets/restro-logo.jpg" />
<h1>Sign Up</h1>
<div class="register">
    <input type="text" placeholder="Enter Name" />
    <input type="text" placeholder="Enter Email" />
    <input type="text" placeholder="Enter Password" />
    <button>Sign Up</button>
</div>
</template>
<script>

export default {
    name: 'SignUp'
}
</script>
<style>
.logo{
    width: 100px;
}
.register input {
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-left: auto;
    margin-right: auto;
    border: 1px solid black;
}
.register button {
    width: 325px;
    height: 40px;
    color: white;
    background-color: darkorange;
    border: darkorange;
    cursor: pointer;
}

</style>