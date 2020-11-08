<template>
  <div>
    <section id='signup'>
      <form class='account-form'>
        <h2>Sign Up</h2>
        <div class='flex-input thirds'>
          <input type='text' placeholder='First Name' id='first-name' />
          <input type='text' placeholder='Last Name' id='last-name' />
          <input type='text' placeholder='Username' id='username' />
        </div>
        <div class='flex-input halves'>
          <input type='email' placeholder='Email' id='email' />
          <input type='text' placeholder='Phone Number' id='phone' />
        </div>
        <div class='flex-input halves'>
          <input type='password' placeholder='Password' id='password' />
          <input type='password' placeholder='Confirm Password' id='confirm-password' />
        </div>
        <input type='submit' value='Sign Up' class='submit' />
      </form>
    </section>
  </div>
</template>
