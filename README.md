<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Online Connection</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, #f8d7e1, #f1e3e0);
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
      text-align: center;
    }

    .container {
      width: 100%;
      max-width: 800px;
      background-color: rgba(255, 255, 255, 0.9);
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      padding: 30px;
    }

    h1 {
      font-size: 2.8em;
      color: #d85d5d;
      margin-bottom: 30px;
    }

    .section {
      display: none;
      font-size: 1.1em;
      line-height: 1.6;
      text-align: left;
    }

    .paragraph {
      margin: 10px 0;
      display: flex;
      align-items: flex-start;
    }

    .avatar {
      flex-shrink: 0;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      margin-right: 10px;
    }

    .text {
      flex-grow: 1;
    }

    strong {
      color: #d85d5d;
    }

    button {
      background-color: #ff6f61;
      color: #fff;
      border: none;
      padding: 12px 25px;
      font-size: 1.1em;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 20px;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #e64a3f;
    }

    .choice-button {
      background-color: #4CAF50;
      padding: 12px 25px;
      font-size: 1.1em;
      border-radius: 5px;
      cursor: pointer;
      margin: 10px 10px 0 0;
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 2em;
      }

      button {
        padding: 10px 20px;
        font-size: 1em;
      }

      .paragraph {
        flex-direction: column;
        align-items: center;
      }

      .text {
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>The Online Connection</h1>
    <div class="story">
      <!-- Sections -->
      <div id="section1" class="section">
        <div class="paragraph">
          <img class="avatar" src="images (1).jpeg" alt="Abhay Avatar">
          <div class="text" data-text="Abhay and Neha had never met in person. They were two strangers who, by a twist of fate, found each other on a social media platform. Their first conversation had been casual, just a simple &quot;Hi&quot; in a group chat that quickly turned into daily exchanges. Over the course of two months, their bond grew."></div>
        </div>
        <button onclick="nextSection(2)">Next</button>
      </div>

      <div id="section2" class="section">
        <div class="paragraph">
          <img class="avatar" src="images (1).jpeg" alt="Abhay Avatar">
          <div class="text" data-text="They had never spoken on the phone. No video calls. Just messages. The conversations were warm and effortless, as if they’d known each other for years. Yet, as the days went by, Abhay felt something deeper growing inside him—a connection that was more than just friendship."></div>
        </div>
        <button onclick="nextSection(3)">Next</button>
      </div>

      <div id="section3" class="section">
        <div class="paragraph">
          <img class="avatar" src="images (1).jpeg" alt="Abhay Avatar">
          <div class="text" data-text="Neha had become someone he couldn’t imagine a day without talking to. Her words felt like a part of his routine, like the air he breathed. But even after all this time, Abhay had never expressed his feelings. It was all so new, so uncertain, and so delicate."></div>
        </div>
        <button onclick="nextSection(4)">Next</button>
      </div>

      <div id="section4" class="section">
        <div class="paragraph">
          <img class="avatar" src="images (1).jpeg" alt="Abhay Avatar">
          <div class="text" data-text="He sat at his desk, looking at the screen. He had rehearsed his message countless times in his mind. There was a nervous excitement mixed with the uncertainty of her response. But he knew one thing for sure—this was the moment to ask her out."></div>
        </div>
        <button onclick="nextSection(5)">Next</button>
      </div>

      <div id="section5" class="section">
        <div class="paragraph">
          <img class="avatar" src="images (1).jpeg" alt="Abhay Avatar">
          <div class="text" data-text="He took a deep breath, fingers hovering over the keyboard. Then, he began to type.

Abhay: &quot;Hey Neha, I’ve been meaning to ask you something for a while now. I know we’ve been talking for a while and, though we’ve never met in person, I feel like I know you more than I’ve known anyone else. You’re someone who has brought so much warmth into my life, and our conversations have meant so much to me.&quot;"></div>
        </div>
        <button onclick="nextSection(6)">Next</button>
      </div>

      <div id="section6" class="section">
        <div class="paragraph">
          <img class="avatar" src="images (1).jpeg" alt="Abhay Avatar">
          <div class="text" data-text="Abhay stared at the message for a moment, his heart pounding in his chest. He read it over and over, ensuring it sounded right, hoping it conveyed everything he felt."></div>
        </div>
        <button onclick="nextSection(7)">Next</button>
      </div>

      <div id="section7" class="section">
        <div class="paragraph">
          <img class="avatar" src="images (1).jpeg" alt="Abhay Avatar">
          <div class="text" data-text="He hit send."></div>
        </div>
        <button onclick="nextSection(8)">Next</button>
      </div>

      <div id="section8" class="section">
        <div class="paragraph">
          <img class="avatar" src="images.jpeg" alt="Neha Avatar">
          <div class="text" data-text="Neha was sitting in her room, her phone buzzing beside her. She picked it up, and as she unlocked the screen, she saw the message from Abhay. She smiled softly. Over the last two months, she had felt something special growing between them too. It was like she knew him in a way she hadn’t known anyone else, even though they'd never actually met."></div>
        </div>
        <button onclick="nextSection(9)">Next</button>
      </div>

      <div id="section9" class="section">
        <div class="paragraph">
          <img class="avatar" src="images.jpeg" alt="Neha Avatar">
          <div class="text" data-text="She bit her lip, thinking for a moment. She had enjoyed their conversations, their jokes, and their shared moments. The thought of spending time with him, in the real world, made her heart flutter. But what if things were different in person? What if the magic didn’t translate?"></div>
        </div>
        <button onclick="nextSection(10)">Next</button>
      </div>

      <div id="section10" class="section">
        <div class="paragraph">
          <img class="avatar" src="images.jpeg" alt="Neha Avatar">
          <div class="text" data-text="Her fingers hovered over the keyboard. Then, with a deep breath, she started typing.

Neha: &quot;Abhay, I can’t tell you how much your message means to me. Honestly, I’ve been thinking about this too. It’s been so wonderful getting to know you, and I feel like we’ve built something really special. I’ve been hesitant about meeting up because it’s all felt so perfect the way it is. But after reading your message, I think I’d like to give it a shot. I’m nervous, but also excited. So, yes, let’s meet. A coffee sounds lovely, or maybe a walk? Let’s make it happen.&quot;"></div>
        </div>
        <div id="choices">
          <button class="choice-button" onclick="meetChoice('cafe')">Choose Café</button>
          <button class="choice-button" onclick="meetChoice('park')">Choose Park</button>
        </div>
      </div>

      <div id="cafeSection" class="section">
        <div class="paragraph">
          <img class="avatar" src="images.jpeg" alt="Abhay Avatar">
          <div class="text" data-text="They decided to meet at a cozy café down the street. They both arrived, feeling the excitement and nerves of their first in-person encounter."></div>
        </div>
        <button onclick="goToFinal()">Next</button>
      </div>

      <div id="parkSection" class="section">
        <div class="paragraph">
          <img class="avatar" src="images.jpeg" alt="Abhay Avatar">
          <div class="text" data-text="They chose a peaceful park for their first meeting. The fresh air and greenery made everything feel calm and natural."></div>
        </div>
        <button onclick="goToFinal()">Next</button>
      </div>

      <div id="section11" class="section">
        <div class="paragraph">
          <img class="avatar" src="images.jpeg" alt="Neha Avatar">
          <div class="text" data-text="Their story was just beginning… and they both couldn’t wait to see where it would lead."></div>
        </div>
      </div>
    </div>
  </div>

  <script>
    let currentSection = 1;
    let typingSpeed = 30;

    function typeText(textElement, fullText, index = 0, callback) {
      if (index < fullText.length) {
        textElement.innerHTML += fullText.charAt(index);
        setTimeout(() => typeText(textElement, fullText, index + 1, callback), typingSpeed);
      } else {
        if (callback) callback();
      }
    }

    function displaySection(id) {
      const section = document.getElementById(id);
      section.style.display = "block";

      const textElements = section.querySelectorAll(".text");
      let i = 0;

      function processNextText() {
        if (i >= textElements.length) return;
        const el = textElements[i];
        const content = el.getAttribute("data-text");
        typeText(el, content, 0, () => {
          i++;
          processNextText();
        });
      }

      processNextText();
    }

    function nextSection(nextId) {
      document.getElementById(`section${currentSection}`).style.display = "none";
      currentSection = nextId;
      displaySection(`section${nextId}`);
    }

    function meetChoice(choice) {
      document.getElementById("section10").style.display = "none";
      document.getElementById("choices").style.display = "none";

      if (choice === "cafe") {
        displaySection("cafeSection");
      } else {
        displaySection("parkSection");
      }

      currentSection = 11;
    }

    function goToFinal() {
      document.getElementById("cafeSection").style.display = "none";
      document.getElementById("parkSection").style.display = "none";
      displaySection("section11");
    }

    window.onload = () => {
      displaySection("section1");
    };
  </script>
</body>
</html>
