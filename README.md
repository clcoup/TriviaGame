# TriviaGame<!DOCTYPE html>
<html lang="en_us">
   <head><meta charset="utf-8">
      <title>TriviaGame</title>
         
         <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

          <script
           src="https://code.jquery.com/jquery-3.2.1.js"
           integrity="sha256-DZAnKJ/6XZ9si04Hgrsxu/8s717jcIzLy3oi35EouyE="
           crossorigin="anonymous"></script>
      </head>
<body>
     <div class="container">
       <div class="rows">
         <div class="text-center">
            <div class="jumbotron" style="background-color: #F17">
                 <h1>My CrAZy cRAzY TrIvIa GamE</h1> 


 <div class="startGame"><span id="startbutton"></span>
  
  <button>Start</button>
     </div>
        <form id = "quiz" name  = "quiz" onsubmit="event.preventDefault()">

          <p class="question1">1.Why do dogs stick their Head out of the car window?</p>
           <ul class="answers">
              <input type="radio" name="q1" value="a" id="q1a"><label for="q1a">This is a sign that you stink?</label><br/>
              <input type="radio" name="q1" value="b" id="q1b"><label for="q1b"> They love to sniff the air?</label><br/>
              <input type="radio" name="q1" value="c" id="q1c"><label for="q1c">To make sure you're driving Safely?</label><br/>
              <input type="radio" name="q1" value="d" id="q1d"><label for="q1d">This help them get an orgasm?</label><br/>
          </ul>
         

          <p class="question2">2.what is the most stolen food in the world?</p> 
           <ul class="answers">
              <input type="radio" name="q2" value="a" id="q2a"><label for="q2a">bread?</label><br/>
              <input type="radio" name="q2" value="b" id="q2b"><label for="q2b"> vegetables?</label><br/>
              <input type="radio" name="q2" value="c" id="q2c"><label for="q2c">cheese?</label><br/>
              <input type="radio" name="q2" value="d" id="q2d"><label for="q2d">chicken?</label><br/>
            </ul>

          <p class="question3">3.Men who are insecure when it comes to performing sex do what?</p>
          <ul class="answers">
              <input type="radio" name="q3" value="a" id="q3a"><label for="q3a">Call their mothers?</label><br/>
              <input type="radio" name="q3" value="b" id="q3b"><label for="q3b">Wear socks?</label><br/>
              <input type="radio" name="q3" value="c" id="q3c"><label for="q3c">Take handfuls of Viagra?</label><br/>
              <input type="radio" name="q3" value="d" id="q3d"><label for="q3d">Watch television, and tell their partners they have a headache?</label><br/>
          </ul>

          <p class="question4">4.What is illegal to put in clam chowder in the state of Massachusetts?</p>
            <ul class="answers">
              <input type="radio" name="q4" value="a" id="q4a"><label for="q4a">Potatoes?</label><br/>
              <input type="radio" name="q4" value="b" id="q4b"><label for="q4b">Tomatoes?</label><br/>
              <input type="radio" name="q4" value="c" id="q4c"><label for="q4c">Clams?</label><br/>
              <input type="radio" name="q4" value="d" id="q4d"><label for="q4d">Asparagus?</label><br/>
           </ul>

        <p class="question5">5.Twenty-four per cent of British men have lost  their what?</p>
          <ul class="answers">
              <input type="radio" name="q5" value="a" id="q5a"><label for="q5a">Sex drive</label><br/>
              <input type="radio" name="q5" value="b" id="q5b"><label for="q5b">Teeth?</label><br/>
              <input type="radio" name="q5" value="c" id="q5c"><label for="q5c">Memory?</label><br/>
              <input type="radio" name="q5" value="d" id="q5d"><label for="q5d">Wives?</label><br/>
           </ul>

           <p class="question6">6.Name the largest freshwater lake in the world?</p>
          <ul class="answers">
              <input type="radio" name="q6" value="a" id="q6a"><label for="q6a">Lake Superior?</label><br/>
              <input type="radio" name="q6" value="b" id="q6b"><label for="q6b">Lake Baikal?</label><br/>
              <input type="radio" name="q6" value="c" id="q6c"><label for="q6c">Lake Victoria?</label><br/>
              <input type="radio" name="q6" value="d" id="q6d"><label for="q6d">Lake Michigan?</label><br/>
           </ul>
           <input type="submit" name="" onclick="check()">
         </form>
        
             <style type="text/css">
            
              body{
                background-color: #C2ED17;
              }
                 

  
              </style>
              <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
           <!-- Script -->
         <script>
         //correct answer for each question 
        var correctAnswers = [
              'q1b','q2d','q3b','q4b','q5d','q6a'
            ];
          
        function check() { 
           

          if ($('#q1b').prop('checked', true)) {
            console.log('q1b is checked');
          } else {
            ('q1b is not checked');
          }
          document.getElementById('q1b').innerHTML = " question1 " +  qb1;

          if ($('#q2d').prop('checked', true)) {
            console.log('q2d is checked');
          } else {
            ('q2d is not checked', false);
          }
          
            


          //for (var i = 0; i < 6; i++) {
           // document.getElementById('')
          //}





           // var question1 = document.q1.a.value;
           // var question2 = document.q1.b.value;
           // var question3 = document.q1.c.value;
           // var question4 = document.q1.d.value;
           // var correct = 0;
         
           //  if (question1 == "This is a sign that you stink") {
           //   correct++;
           //   }

          }

   
           </script>
    
        </body>
    </html>
