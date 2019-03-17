<template>
  <div class="w-full bg-white rounded shadow-lg p-8 m-4 md:max-w-sm md:mx-auto">
        <form class="mb-4 md:flex md:flex-wrap md:justify-between" action="/" >
          <div class="field-group mb-4 md:w-full">
            <label class="field-label" for="email">Email</label>
            <input class="field" type="email" name="email" id="email">
          </div>
          <div class="field-group mb-6 md:w-full">
            <label class="field-label" for="password">Password</label>
            <input class="field" type="password" name="password" id="password">
          </div>
          <button class="btn btn-teal md:w-full" type="submit">Login</button>
        </form>
        <a class="link link-grey w-full text-center" href="/login">Forgot Password?</a>
    </div>
</template>

<script>
import './assets/css/tailwind-styles.css'

export default {
  name: 'app'
}
</script>
