<html>
  </head>
    <style>    .row {
        display: flex;
        flex-wrap: wrap;
        padding: 0 4px;
      }

      /* create four equal columns that sits next to each other */
      .column {
        flex: 25%;
        max-width: 25%;
        padding: 0 4px;
      }
      .column img {
        margin-top: 8px;
        vertical-align: middle;
        width: 100%;
      }
      /* Responsive layout - makes a two column-layout instead of four columns */
      @media screen and (max-width: 800px) {
        .column {
          flex: 50%;
          max-width: 50%;
        }
      }

      /* responsive layout - makes the two columns stack on top of each other instead of next to each other */
      @media screen and (max-width: 600px) {
        .column {
          flex 100%;
          max-width: 100%;
        }
      }
#img-caption {
  font-size:30px;
}

#tribute-link {
  color: blue;
  font-weight: bold;
}

.center{
  margin:auto;
  width: 50%
  padding: 10px;
  text-align: center;
}
    </style>
<body>
<div id="main">

<div class="center">  <h1 id="title">Pam & Pantera </h1>

  <div id="img-div">
    <div class="row">
      <div class="column"></div>
      <div class="column">
      <img src="images/panty.jpg" alt="Pantera yelling about food" id="image">
      <img src="images/pam2.jpg" alt="Judgemental Pam" id="image">
      <img src="images/panty 2.jpg" alt="Inquisitive Panty" id="image">
      <img src="images/pam3.jpg" alt="Pam sassing" id="image">
      </div>
    <div class="column">
      <img src="images/panty 5.jpg" alt="Pantera chilling" id="image">
      <img src="images/pamdrawing.jpg" alt="Drawing of Pam" id="image">
      <img src="images/panty 6.jpg" alt="Pantera side profile" id="image">
      <img src="images/Pam.jpg" alt="Bugged Pam" id="image">
    </div>

    </div>
</div>
<div class="center">   <p id="img-caption"><em>The Greatest to ever do it.</em></p>
  </div>
  <div id="tribute-info"><p></p>

  <p>There was once was a cat with a hungry belly</p>
  <p>The name of the cat was whiskers jelly</p>
  <p>His throat was dry and his bowl was bare</p>
  <p>Meow me furry cats, meow</p>
  <p>Soon may the kittyman come</p>
  <p>With birds and mice and some tasty nums</p>
  <p>One day when the critters come</p>
  <p>We'll eat ’til our bellies are full</p>
  <p>Well jelly got his boys and they gathered 'round</p>
  <p>They scattered seeds from a sack they found</p>
  <p>In hopes the seeds they spread on the ground</p>
  <p>Will bring small critters aboot</p>
  <p>Soon may the kittyman come</p>
  <p>With birds and mice and some tasty nums</p>
  <p>One day when the critters come</p>
  <p>We'll eat ’til our bellies are full</p>
<p>Well the gang was bored and morale had</p> dipped
  <p>'Til one of the seeds grew green catnip</p>
  <p>They sniffed and they snacked and they all got ripped</p>
  <p>They all had a meow that night</p>
  <p>Soon may the kittyman come</p>
  <p>With birds and mice and some tasty nums</p>
  <p>One day when the critters come</p>
  <p>We'll eat 'til our bellies are full</p>
  <p>Well their heads were hung when the morn was nigh</p>
  <p>The nip was strong and they all got high</p>
  <p>Their bellies were shrunk and their bowls still dry</p>
  <p>Oh bring us some mice today</p>
  <p>Soon may the kittyman come</p>
  <p>With birds and mice and some tasty nums</p>
  <p>One day when the critters come</p>
  <p>We'll eat 'til our bellies are full</p>
  </div>

  <a href="https://instagram.com/panterathepygmypanther" target="_blank" id="tribute-link" >
    Follow on Insta for more Feline Shenangins!
  </a>
 </div>
</div>
</body>
</html>
