# aboutME
test. dont even know is it gonna work out!

[justbore.html](https://github.com/user-attachments/files/23234581/justbore.html)
<!DOCTYPE html>
<html>
  <head>
    <title>About Me!</title>
    <script>
      function showFunFact() {
        alert("Fun fact: I once stayed up all night finishing a novel and still went to class the next morning!");
      }

      // greeting animation
      let msg = "Welcome!";
      let i = 0;
      function typeGreeting() {
        if (i < msg.length) {
          document.getElementById("greeting").innerHTML += msg.charAt(i);
          i++;
          setTimeout(typeGreeting, 100);
        }
      }
      window.onload = typeGreeting;
    </script>
  </head>

  <body style="background-color: #f0f8ff; font-family: Arial, sans-serif; text-align: center;">
    <h1 id="greeting" style="color: #2e4a7d; height: 30px;"></h1>

    <h1 style="color: #2e4a7d;">Hi! I'm Nawapas Jornpagdee</h1>
    <p>My nickname is <b>new</b>.</p>

    <img src="IMG_0329.jpg" alt="Photo of Nawapas Jornpagdee" width="300" style="border-radius: 10px; border: 2px solid #ccc;">

    <h2 style="color: #2e4a7d;">About Me</h2>
    <p>I am an engineering student at <b>Chulalongkorn University</b>.</p>
    <p>Right now I am focusing on learning more coding skills and also studying about sustainable city development.</p>

    <h2 style="color: #2e4a7d;">My Hobbies</h2>
    <ul style="list-style-type: square; display: inline-block; text-align: left;">
      <li>Read novels</li>
      <li>Play mobile games</li>
    </ul>

    <h2 style="color: #2e4a7d;">Current Focus</h2>
    <ul style="list-style-type: circle; display: inline-block; text-align: left;">
      <li>Improve my coding skills</li>
      <li>Learn Japanese so I can understand anime</li>
    </ul>

    <button onclick="showFunFact()" style="background-color: #2e4a7d; color: white; border: none; padding: 10px 20px; border-radius: 10px; cursor: pointer; margin-top: 20px;">
      Click for a fun fact!
    </button>

    <h2 style="color: #2e4a7d;">Thank You!</h2>
    <p style="font-style: italic;">"Just created this while I'm bored" web page :)</p>

    <hr style="width: 60%; margin-top: 30px;">
    <p style="font-size: 12px; color: gray;">© 2025 Nawapas Jornpagdee</p>
  </body>
</html>
![IMG_0329](https://github.com/user-attachments/assets/c189c3fb-98a6-4d07-a98c-420d64e69a61)
