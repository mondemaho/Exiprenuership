# Exiprenuership

## What Is Exiprenuership?

Exiprenuership is a mobile app that creates consciousness to all students about school events in different universities and TVET colleges.

.content {
  color: black;
}

.header {
  color: blue;
}

  
  <h1>Exiprenuership
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

      let message = "Exiprenuership is hosting a seminar on the 15 March 2026 " +
      "at Science Stadium Wit\'s University.Build your consciousness, \"reader\'s are leader\'s\". " +
      "We have different guest speaker\'s Vusi Thembekwayo,Emmanual Bonoko,DJ Sbu,Mbuso Khoza and More. they will be sharing empowering talk\'s to young BBBEE " +
      "on how to get fund\'s, which document\'s are needed to apply, and what do you need to start. " +
      "They will be joined by the following FNO and ISP: MTN, Vodacom, Telkom, Openserve, Zoom Fibre and TT Connect.-Time:12:00am-17h00pm.All the student\'s are welcome!"

      document.getElementById("Seminar").innerHTML =message;}
    
  </script>
</body>
</HTML>
    

HTML
<h2>Exam Planner</h2>

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

window.onload = function () {
  let savedData = localStorage.getItem("examData");

  if (savedData) {
    document.getElementById("examTable").innerHTML = savedData;
  }
};

function addExam() {

  let subject = prompt("Enter Subject:");
  let date = prompt("Enter Date:");
  let time = prompt("Enter Time:");

  let table = document.getElementById("examTable");

  let row = table.insertRow();

  row.insertCell(0).innerHTML = subject;
  row.insertCell(1).innerHTML = date;
  row.insertCell(2).innerHTML = time;

  localStorage.setItem("examData", table.innerHTML);
}

</script> 
  
     
    
      
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



 
      
