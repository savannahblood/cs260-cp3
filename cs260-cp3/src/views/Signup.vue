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
    <section id='contact'>
      <form>
        <h2>Questions?</h2>
        <h3>We'll get right back to you.</h3>
        <div class='flex-input halves'>
          <input type='text' placeholder='Name' id='name' />
          <input type='email' placeholder='Email' id='email'/>
        </div>
        <textarea placeholder='Message' id='message'></textarea>
        <input type='submit' value='Send' class='submit' />
      </form>
    </section>
  </div>
</template>
