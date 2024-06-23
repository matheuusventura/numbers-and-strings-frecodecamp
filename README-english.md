# 🌎🖥 Creating a Luhn validation algorithm (Luhn formula) in Python

Learning to work with numbers and strings in Python by creating a validation algorithm known as the 'Luhn algorithm' during the Scientific Computing with Python course from freecodecamp.org.
<br>
<br>
🗣️ [portuguese](https://web.whatsapp.com/) - [english](https://web.whatsapp.com/) - [spanish](https://web.whatsapp.com/)
<h3>What is the Luhn Algorithm?</h3>
The Luhn Algorithm (or Luhn Formula) is a simple method used to verify the validity of identification numbers such as credit card numbers, cell phone IMEI numbers, social security numbers (in some countries), among others.
<br>
<h3>How does it work?</h3>
<ol>
  <li>The algorithm starts by reversing the order of the digits of the original number.<br></li>
  <li>Then the digits in odd positions (considering the new order) are added directly, while the digits in even positions are multiplied by 2. If the multiplication results in a number greater than or equal to 10, the digits of the result are added individually (for example, 12 becomes 1 + 2 = 3).<br></li>
  <li>The algorithm checks if the total sum of the digits (after the above operations) is a multiple of 10.</li>
</ol>
<br>
If the number is not a multiple of 10, the algorithm returns 'INVALID!', otherwise we get 'VALID!' as the result.
<hr>
<h4>👋😆 This was my second stage of the freecodecamp course. I will be publishing and explaining all projects and my progression as I go along.</h4>