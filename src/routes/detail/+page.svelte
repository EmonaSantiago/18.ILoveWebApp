<section id="Detail">
    <div class="container">
      <div class="text">
        <h1>Focus op Toegankelijkheid</h1>
        <h3>Fenna de Wilde</h3>
        <p class="datum">19/01/24</p>
        <p>
          In de digitale wereld krijgen esthetiek en vloeiende animaties vaak alle aandacht. Tock is er een cruciaal aspect dat vaak over hte hoofd wordt gezien maar wel onze volle aandacht verdient - Toegankelijkheid.
        </p>
        <p class="locatie">
          The Bell (BELL) Sarphatistraat 370 1018 GW Amsterdam
        </p>
        <a href="/" class="button1">Ga terug</a>
        <a href="/aanmelden" class="button2">Aanmelden</a>
      </div>
      <div class="image">
        <img src="/images/WeLoveWeb.png" alt="Afbeelding" />
      </div>
    </div>
  </section>
  
  <style>
    h1 {
      font-size: 50px;
    }
    .datum {
      margin-top: 1em;
      margin-bottom: 5px;
      font-size: 28px;
    }
  
    .locatie {
      font-size: 12px;
      margin-top: 2em;
      margin-bottom: 3em;
    }
    #Detail {
      margin: 2em;
      color: white;
      height: 70vh;
    }
  
    .button1,
    .button2 {
      margin-top: 2em;
      text-decoration: none;
      border: solid 2px var(--green);
      border-radius: 10px;
      color: var(--green);
      padding: 10px;
    }
  
    .button1 {
      border: solid 2px var(--purple);
      color: var(--blue);
      background-color: var(--purple);
    }
  
    .container {
      display: flex;
      flex-direction: row;
    }
  
    .text {
      flex: 1;
      padding-right: 6em;
      margin-bottom: 2em;
    }
  
    .image {
      flex: 1;
      text-align: right;
    }
  
    img {
      width: 100%;
      border-radius: 12px;
    }
  
    @media (max-width: 600px) {
      h1 {
        font-size: 25px;
      }
      .container {
        flex-direction: column;
      }
  
      .image {
        text-align: center;
      }
    }
  
    @media (max-width: 600px) {
      #Detail {
        height: 80vh;
      }
      .text {
        padding: 0em;
        margin-bottom: 2em;
      }
  
      .datum {
        margin-top: 1em;
        margin-bottom: 5px;
      }
  
      .locatie {
        font-size: 12px;
        margin-top: 2em;
      }
    }
  </style>
  