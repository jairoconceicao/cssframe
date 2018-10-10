<template>
  <form>
    <fieldset>
      <legend>Formulário</legend>
      <section>
        <div>
          <label for="exampleInputEmail1">Email address</label>
          <input type="text" id="exampleInputEmail1">
        </div>

        <div>
          <label for="exampleInputPassword1">Password</label>
          <input type="password" id="exampleInputPassword1">
        </div>

        <div>
          <label for="exampleInputFile">File input</label>
          <input type="text" id="exampleInputFile">
        </div>
        <div>
          <label for="CheckMe">Choose me</label>
          <select>
            <option>Choose...</option>
            <option>Option #1</option>
            <option>Option #2</option>
            <option>Option #3</option>
            <option>Option #4</option>
            <option>Option #5</option>
          </select>
        </div>
        <div>
          <input type="checkbox" id="CheckMe">
          <label for="CheckMe">Check me out</label>
        </div>
        <div>
          <input type="radio" id="RadiokMe" name="RadioMe">
          <input type="radio" id="RadiokMe" name="RadioMe">
          <label for="RadioMe">Pick me out</label>
        </div>
        <div>
          <label>Text Area</label>
          <textarea></textarea>
        </div>
        <div>
          <button type="button">OK</button>
          <button type="button">Cancel</button>
        </div>
      </section>
    </fieldset>
  </form>
</template>
