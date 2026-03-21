
      



  
  <h1>Exiprenuarship
  </h1>
  <h2>
    Addicted to innovation
  </h2>
    
  <head>
  
    <body>
      <script>
      let message='Exiprenuership'
      document.write ('Exiprenuership It's a Mobile app that create consiousness to all the student\'s about school event\'s in Different University and Tvet college.')
      
      </script>
      
      
      
      <html>
<head>
  <title>Exiprenuership</title>
</head>

<body>

  <h1>Seminar</h1>

  <button onclick="ShowSeminar()">Click Me</button>

  <p id="Seminar"></p>

  <script>
    function ShowSeminar() {

      let message = "Exipreniership is hosting a seminar on the 15 March 2026 " +
      "at Science Stadium Wit\'s University.Build your consciousness, \"reader\'s are leader\'s\". " +
      "We have different guest speaker\'s Vusi Thembekwayo,Emmanual Bonoko,DJ Sbu,Mbuso Khoza and More. they will be sharing empowering talk\'s to young BBBEE " +
      "on how to get fund\'s, which document\'s are needed to apply, and what do you need to start. " +
      "They will be joined by the following FNO and ISP: MTN, Vodacom, Telkom, Openserve, Zoom Fibre and TT Connect.-Time:12:00am-17h00pm.All the student\'s are welcome!"

      document.getElementById("Seminar").innerHTML =message;}
    
  </script>
</body>
</HTML>
    

<html>
<head>
  <title>Exam Planner</title>
</head>

<body>

  <h2>Exam Planner</h2>

  <!-- Input fields -->
  Subject: <input type="text" id="subject"><br><br>
  Date: <input type="date" id="date"><br><br>
  Time: <input type="time" id="time"><br><br>

  <!-- Table -->
  <table border="1" id="examTable">
    <tr>
      <th>Subject</th>
      <th>Date</th>
      <th>Time</th>
    </tr>
  </table>

  <br>
  <button onclick="addExam()">Add Exam</button>

  <script>
    function addExam() {
      let table = document.getElementById("examTable");
      let row = table.insertRow();

      let subjectCell = row.insertCell(0);
      let dateCell = row.insertCell(1);
      let timeCell = row.insertCell(2);

      // Get user input
      let subject = document.getElementById("subject").value;
      let date = document.getElementById("date").value;
      let time = document.getElementById("time").value;

      // Add to table
      subjectCell.innerHTML = subject;
      dateCell.innerHTML = date;
      timeCell.innerHTML = time;
    }
  </script>

</body>
</html>


  
     
    
      
<head>
  <title>Exiprenuership </title>
</head>

<body>

  <h1>Fests</h1>

  <button onclick="showFests()">Click me</button>

  <p id="fests"></p>
  
  <script>
    function showFests() {

      let message = "On the 19 April 2026, Exiprenuership is hosting an event " +
      "at Wits Rugby Stadium. " +
      "Artists: DJ Tira, Scotts Maphuma, Sjava, Black Coffee, Black Diamond, Mlindo the Vocalist, " +
      "Shimza, Euphonic, Zakes Bantwini, DJ Naked, Solomzi, Kabza De Small,and Our best MC Mark khoza. " +
      "" +
      "You can also nominate yourself by sending a smaller nyana video and tell us why do you think you are the best DJ in the campus. " +
      "You can share your video via our Facebook channel: Exiprenuership-M67 " +
      "Or you can Post your video and tag us via Linkedin: Exiprenuership_Ubizolwami. " +
      "Ticket\'s are available at Computicket. " +
      "Damage: R150. Time: 13h00 till late. Drinks are sold at the venue."
      document.getElementById("fests").innerHTML = message;
    }
  </script>

</body>
</html>
 
      <script>
      function ('fest\s')
  let age = 18;

  if (age >= 18) {
    console.log("You are an adult");
  } else {
    console.log("You are a minor");
  }
</script>
