---
title: "IP dei Server"
date: 2020-12-12T10:34:42+01:00
draft: false
anchor: "ipserver"
weight: 20
---
I nostri ninjascript ad ogni refresh della pagina controllano l'IP dei nostri server di gioco.\
State calmi e nessuno si farà del male.

| *Ip Address* | *Last checked* |
-----------|------------
<span id=ipText></span> | <span id=date></span>

<script>

fetch("https://dns.google/resolve?name=968a09db22e0.sn.mynetname.net")
      .then(function (response) {
        return response.json();
        })
      
      .then(function (myJson) {
        console.log(myJson.Answer);
        document.querySelector("#ipText").innerHTML = myJson.Answer[0].data;
        document.querySelector("#date").innerHTML = Date(Date.now());
      })
      .catch(function (error) {
        console.log("Error: " + error);
      
      });

</script>
