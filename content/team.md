---
title: "Team"
slug: "team"
draft: false
---
<p><strong>Martinengo Live</strong> realizza progetti coerenti con la propria <a href="/mission/">mission</a>, rivolti alla cittadinanza e grazie al contributo della stessa comunit&agrave;.
Pi&ugrave; specificatamente si rivolge a <strong>4</strong> diverse tipologie di attori che credendo nel valore dei progetti possono decidere di parteciparne alla realizzazione:
<ul>
  <li>
  Il singolo cittadino
  </li>
  <li>
  Le associazioni
  </li>
  <li>
  Il Comune di Martinengo
  </li>
  <li>
  Gli sponsor
  </li>
</ul>  
  
</p>

<style>
  .grid-2x2 {
    display: grid;
    grid-template-columns: 1fr 1fr; /* 2 colonne */
    grid-template-rows: auto auto; /* 2 righe */
    gap: 1rem;
    grid-template-areas:
      "box1 box2"
      "box3 box4";
  }
  .box1 { grid-area: boxgio; }
  .box2 { grid-area: boxven; }
  .box3 { grid-area: boxsab; }
  .box4 { grid-area: boxdom; }

  @media (max-width: 768px) {
    .grid-2x2 {
      grid-template-columns: 1fr;
      grid-template-rows: auto auto auto auto;
      grid-template-areas:
        "box1"
        "box3"
        "box2"
        "box4";
    }
  }

  .grid-2x2 .box {
    padding: 1rem;
    background: transparent;
    border: 3px solid var(--border);   
    border-radius: 6px;
  }
</style>
<div class="grid-2x2" style="text-align: center;">
  <div id="gio" class="box boxgio">
   Il singolo cittadino.<br><br>
   <img src="/images/team-cittadino.webp" alt="il cittadino" style="display:block; margin:0 auto;"> <br>
    Sono proprio i singoli cittadini, che come volontari, contribuiscono in prima persona con il proprio impegno e le proprie capacit&agrave; alla realizzazione dei progetti.
  </div>
  <div id="ven" class="box boxven">
   Le associazioni.<br><br>
   <img src="/images/team-associazioni.webp" alt="le associazioni" style="display:block; margin:0 auto;"> <br>
   Martinengo Live ricerca continuamente collaborazioni con le associazioni del territorio al fine di realizzare progetti, anche con finalit&agrave; diverse, che coinvolgano la musica.
   
  </div>
    <div id="sab" class="box boxsab">
   Il Comune di Martinengo.<br><br>
   <img src="/images/team-comune.webp" alt="il Comune di Martinengo" style="display:block; margin:0 auto;"> <br>
    Il Comune di Martinengo riveste un ruolo fondamentale nel dare il proprio Patrocinio e supporto economico e operativo ai progetti di Martinengo Live.
  </div>
  <div id="dom" class="box boxdm">
   Gli sponsor.<br><br>
   <img src="/images/team-sponsor.webp" alt="gli sponsor" style="display:block; margin:0 auto;"> <br>
   Siamo aperti alla collaborazione con le imprese, in special modo con quelle che abbiano a cuore la musica, il centro storico, in altre parole la missione di Martinengo Live.
  </div>
</div>

