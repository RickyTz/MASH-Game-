<!DOCTYPE html>
<html>

  <!-- HEAD SECTION STARTS -->
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=0.5, maximum-scale=0.5, minimal-ui">
    <title>MASH</title>
    <link href="" rel="stylesheet">
    <link href="" rel="stylesheet">
  </head>
  <!-- HEAD SECTION ENDS -->

  <!-- BODY SECTION STARTS -->
  <body>
    <h1>MASH</h1>
    <p class="description">Fill in the blanks and your future will be foretold.</p>
    <form action="" method="post" id="mash">
      <div id="answers" class="hide">
        <p>Your home is in <span id="answer_1"></span> with a <span id="answer_3"></span> as you are a <span id="answer_2"></span> who owns a <span id="home"></span>.
      </div>
      <div class="bucket">
        <div class="choice-bucket">
          <h4 class="highlight">Where will you live?</h4>
          <input name="answer_1[Texas]">
          <input name="answer_1[New York]">
          <input name="answer_1[California]">
          <input name="answer_1[Florida]">
        </div>
        <div class="choice-bucket">
          <h4 class="highlight">Your future profession?</h4>
          <input name="answer_2[Mechanic]">
          <input name="answer_2[Offic Job]">
          <input name="answer_2[Buisness Owner]">
          <input name="answer_2[Musician]">
        </div>
        <div class="choice-bucket">
          <h4 class="highlight">What's your future car?</h4>
          <input name="answer_3[Nissan GTR]">
          <input name="answer_3[Toyota Camry]">
          <input name="answer_3[Honda NSX]">
          <input name="answer_3[Ferrari F40]">
        </div>
      </div>
      <button type="submit" class="button-submit">Tell my fortune</button>
    </form>  
    <script src=""></script>
  </body>
  <!-- BODY SECTION ENDS -->

</html>
