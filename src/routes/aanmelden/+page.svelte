<script>
    import Content from "../../lib/components/Content.svelte";
  </script>
  
 <section id="Aanmelden">
<div class="row">
  <div class="column">
    <div class="text">
    <h1>Meld je aan!</h1>
    <h2>Voor de WE 💜 WEB</h2>
    <p>Iedereen is welkom!</p>
  </div>
  </div>
  <div class="column">
    <div class="form">
      <form action="https://formspree.io/f/moqzowdg" method="POST">
        <label for="fname">Naam</label>
        <input
          type="text"
          id="fname"
          name="firstname"
          placeholder="Your name.."
        />
  
        <label for="lname">E-mail</label>
        <input
          type="text"
          id="lname"
          name="lastname"
          placeholder="Your E-mail.."
        />
  
        <label for="country">Aanmelden voor deze sessie</label>
        <select id="country" name="country">
          <option value="sessie">Focus Toegankelijkheid</option>
          <option value="sessie">Javascript</option>
          <option value="sessie">Html/Css</option>
          <option value="sessie">Project Board opzetten</option>
        </select>
  
        <label for="vragen">Vragen?</label>
        <input
          type="text"
          id="vragen"
          name="Vragen"
          placeholder="Stel je vragen hier!"
        />
  
        <input type="submit" value="Submit" />
      </form>
    </div>
  </div>
</div>
</section>

  <Content />
  
  <style>
    h1 {
      color: white;
      padding-bottom: 2px;
      font-size: 85px;
    }
  
    h2 {
      color: var(--purple);
      padding-bottom: 4px;
      font-size: 45px;
    }
  
    p {
      color: white;
      font-size: 20px;
    }
    #Aanmelden {
      height: 50vh;
      margin: 5em;
    }

    .text {
	padding: 0;
	margin-left: 35%;
	transform: translateX(-200%);
	opacity: 0;
	animation: slide-in-anim 0.5s ease-out forwards;
    }

    @keyframes slide-in-anim {
	20% {
		opacity: 0;
	}
	60% {
		transform: translateX(-45%);
	}
	75% {
		transform: translateX(-52%);
	}
	100% {
		opacity: 1;
		transform: translateX(-50%);
	}
}


  
    .form {
      color: white;
      margin-top: 2em;
    }
    input[type="text"],
    select {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid var(--blue);
      border-radius: 4px;
      box-sizing: border-box;
    }
  
    input[type="submit"] {
      width: 100%;
      background-color: var(--green);
      color: var(--blue);
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-weight: bold;
    }
  
    input[type="submit"]:hover {
      background-color: var(--blue);
      color: white;
    }

    * {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 50%;
  height: 200px; 
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }

  #Aanmelden {
    height: 60vh;
    margin: 1em;
  }

  h1 {
    font-size: 40px;
  }

  h2 {
    font-size: 20px;
  }

  .text {
    margin-top: 2em;
  }
}

  </style>
  