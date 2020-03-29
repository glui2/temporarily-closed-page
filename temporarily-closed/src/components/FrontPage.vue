<template>
  <div class="hello">
    <h1></h1>
    <h3>Clifton Hill Eyecare Temporary Store Closure</h3>
    <h3 class="colored">While our doors will be closed, we will still be available to help you.</h3>
    <p>
      As the current situation with COVID-19 continues to quickly unfold, we have made the decision to close our doors temporarily tomorrow, Monday 30th March.
      <br />This decision was made with our staff and you, our local community, in mind.
    </p>
    <p>
      <strong>Although our doors will be closed, XXX and XXX will still be available to help you.</strong>
    </p>
    <div>
      <table>
        <th class="tableHeading">ALL THE WAYS WE ARE HERE TO HELP YOU</th>
        <tr>
          <img
            class="diagram"
            alt="Diagram showing ways we can help"
            src="../assets/ways_to_help_you_image_cropped.png"
          />
        </tr>
      </table>
    </div>
    <hr />
    <ul>
      <li>
        <p class="colored"></p>
      </li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "FrontPage"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
p {
  width: 70%;
  margin: auto;
}
.hello {
  display: flex;
  flex-direction: column;
  width: 60%;
  margin: auto;
}
.colored {
  color: #f48128;
  margin: auto;
}
.diagram {
  width: 100%;
}
.tableHeading {
  width: 60%;
  font-size: 24px;
  font-weight: lighter;
  background-color: #f48128;
  padding: 3%;
}
</style>
