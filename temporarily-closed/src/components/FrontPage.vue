<template>
  <div class="hello">
    <div class="titleMessage">
      <h1></h1>
      <h3>{{clinicName}} Temporary Store Closure</h3>
      <h3 class="colored">While our doors will be closed, we will still be available to help you.</h3>
    </div>
    <div class="introParagraph">
      <p>
        As the current situation with COVID-19 continues to quickly unfold, we have made the decision to close our doors temporarily tomorrow, Monday 30th March.
        <br />This decision was made with our staff and you, our local community, in mind.
      </p>
      <p>
        <strong>Although our doors will be closed, we will still be available to help you.</strong>
      </p>
    </div>
    <div>
      <table class="tableDiagram">
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
    <ul class="qna">
      <li>
        <p class="colored">When will {{clinicName}} temporarily close its doors?</p>
        <p>Monday 30th March at 5pm.</p>
      </li>
      <li>
        <p class="colored">Will the team at {{clinicName}} still be available to help?</p>
        <p>Yes, we will be providing ongoing assistance online throughout this temporary store closure.</p>
      </li>
      <li>
        <p class="colored">How will I get in touch with {{clinicName}} once it has closed?</p>
        <p>Please send an email to {{backupEmail}} with your full name and number. A member of our staff will be in touch to assist you with your eye care, eye wear, or eye health query.</p>
      </li>
      <li>
        <p class="colored">In what way with {{clinicName}} assist me while the practice is closed?</p>
        <p></p>
      </li>
      <li>
        <p class="colored">When will {{clinicName}} reopen the practice?</p>
        <p></p>
      </li>
    </ul>
    <hr />
    <div class="closingParagraph">
      <p>Thank you for your understanding.</p>
      <p>
        We look forward to providing you with ongoing eyecare, now and into the future, sending well wishes to you and your families, stay safe and healthy!
        <br />
        <br />
      </p>
      <p>From the team at Clifton Hill Eyecare Plus.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "FrontPage",
  data() {
    return {
      clinicName: "Eyecare Plus Clifton Hill"
    };
  }
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
  margin: 2% auto;
}
p {
  width: 70%;
  margin: auto;
}
.hello {
  display: flex;
  flex-direction: column;
  width: 70%;
  margin: auto;
}
.titleMessage {
  margin: auto;
}
.introParagraph {
  margin: 3% auto;
}
.colored {
  color: #f48128;
  font-weight: bold;
  margin: auto;
}
.tableDiagram {
  margin: 3% auto;
  width: 80%;
}
.diagram {
  width: 90%;
}
.tableHeading {
  width: 60%;
  margin: auto 0;
  color: white;
  font-size: 24px;
  font-weight: lighter;
  background-color: #f48128;
  padding: 3%;
}
.qna {
  text-align: left;
  margin: auto;
}
.closingParagraph {
  text-align: left;
  margin: 3% 0;
}
</style>
