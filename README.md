# MatiasRiboltaNCI.github.io
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h2>Student Form</h2><br>
    <form>
        <fieldset>
          <legend>Student Information:</legend><br /><br />
          <label for="fname">Name: </label>
          <input type="text" id="fname" name="fname" value="Matias Ivan Ribolta"/><br /><br />
          <label for="fname">University e-mail: </label>
          <input
            type="text"
            id="fname"
            name="fname"
            size="50"
            value="x22126066@student.ncirl.ie"
          /><br /><br />
          <label for="fname">Age:</label>
          <input
            type="text"
            id="fname"
            name="fname"
            size="50"
            value="27"
          /><br /><br />
          <label for="country_code">EirCode:</label>
          <input
            type="text"
            id="country_code"
            name="country_code"
            pattern="[A-Za-z]{3}"
            title="EirCode"
            size="10"
            value="D01 WK31"
          /><br /><br />
          <label for="linkedin">LinkedIn:</label>
          <input type="url" id="linkedin" name="linkedin" placeholder="https://www.linkedin.com/" maxlength="60" size="40"><br /><br />
          <label for="linkedin">GitHub:</label>
          <input type="url" id="github" name="github" value="https://matiasriboltanci.github.io" maxlength="60" size="40">
        </fieldset>
      </table>
      <br /><br />
      <li>Current position and Strenghts:</li><br>
      <input type="radio" id="Manager" name="fav_position" value="Manager" />
      <label for="Manager">Technician</label><br />
      <input
        type="radio"
        id="Supervisor"
        name="fav_position"
        value="Supervisor"
      />
      <label for="css">Student</label><br />
      <input
        type="radio"
        id="Assistant"
        name="fav_position"
        value="Assistant"
      />
      <label for="javascript">Computer Hardware</label><br /><br />
      <li id="action">Select the attributes that <strong>MOSTLY</strong> define you:</li><br>
      <input
        type="checkbox"
        id="attribute1"
        name="attribute1"
        value="Hardworker"
      />
      <label for="attribute1"> Hardworker</label><br />
      <input
        type="checkbox"
        id="attribute2"
        name="attribute2"
        value="Confident"
      />
      <label for="attribute2"> Confident</label><br />
      <input
        type="checkbox"
        id="attribute3"
        name="attribute3"
        value="Trusthworthy"
      />
      <label for="attribute3"> Trusthworthy</label><br />
      <input type="checkbox" id="attribute3" name="attribute3" value="Polite" />
      <label for="attribute4"> Polite</label><br /><br />
    </form>
  <p>"My name is Matias Ribolta, and I am thrilled to share my journey and motivation for studying IT. From a young age, I have been captivated by the ever-evolving world of technology and its profound impact on our daily lives. This fascination has fueled my desire to dive deep into the realm of Information Technology and uncover its boundless possibilities."</p>
  </body>
</html>
