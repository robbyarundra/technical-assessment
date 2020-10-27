<template>
<div>
    <nav class="container">
        <div class="logo">
            <img src="images/Isobar-logo.png" width="200" height="80">
        </div>
        <ul class="nav-links">
            <li>
                <router-link class="nav-link" :to="'/'" exact>Home</router-link>
            </li>
            <li>
            <h5>|</h5>
            </li>
            <li>
                <router-link class="nav-link" :to="'/contactus'" exact>Contact Us</router-link>
            </li>
            <li>
            <h5>|</h5>
            </li>
            <li>
                <router-link class="nav-link" :to="'/login'" exact>Login</router-link>
            </li>
        </ul>
    </nav>
</div>
</template>

<script>
export default {
  name: 'Header',
}

</script>