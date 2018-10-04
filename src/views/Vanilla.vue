<template>
  <form>
    <fieldset>
      <section class="row">
        <div class="col-4">
          <label for="exampleInputEmail1">Email address</label>
          <input type="date" id="exampleInputEmail1" placeholder="Email">
        </div>

        <div class="col-4">
          <label for="exampleInputPassword1">Password</label>
          <input type="password" id="exampleInputPassword1" placeholder="Password">
        </div>

        <div class="col-4">
          <label for="exampleInputFile">File input</label>
          <input type="file" id="exampleInputFile">
        </div>
      </section>

      <section class="row">
        <div class="col-12">
          <input type="checkbox" id="CheckMe">
          <label for="CheckMe">Check me out</label>
        </div>
      </section>
      
      <section class="row">
        <div class="col-12">
          <button type="submit">Submit</button>
        </div>
      </section>
    </fieldset>
  </form>
</template>
