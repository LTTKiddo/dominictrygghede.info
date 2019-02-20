---
lang: "sv"
keywords: "Dominic,Trygghede,Information"
author: "Dominic Trygghede"
description: "Information om mig. (Dominic Trygghede)"
title: "Dominic Trygghede"
---
# Det är jag, Dominic Trygghede.
Jag heter Dominic Trygghede och är en pojke på <span id="age">2003</span> somrar som gillar hundar och att tugga på elkablar.
Min födelsedag är den 16 juni, jobbar just nu på att skaffa mig min första kompis.<br/>
Jag är för tusan elite! #1337 #420blzit

Målet med denna hemsida är så att alla som söker efter "Dominic Trygghede" på internet ska veta vilken cool människa jag är. Allting här är skrivet av mig. 

## vad jag är bra på
* äta
* dricka
* ~~skaffa kompisar~~
* fortnite

## skolmaten
<div id="rss">
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-rss/3.3.0/jquery.rss.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.8.4/moment.min.js"></script>
<script>
    $('#rss').rss("https://skolmaten.se/bergskolan/rss/days/?limit=7", {
        limit: 7,
        ssl: true,
        entryTemplate: '<li><b>{title}</b>: {shortBodyPlain}</li>',
    })
    function _calculateAge(birthday) {
        var ageDifMs = Date.now() - birthday.getTime();
        console.log("Dominic Trygghede fyller år den " + birthday.getDate() + "/" + (birthday.getMonth() + 1) + ". Det är vetenskapligt bevisat.")
		var ageDate = new Date(ageDifMs);
		return Math.abs(ageDate.getUTCFullYear() - 1970);
    }
    document.getElementById('age').innerHTML = _calculateAge(new Date(2003, 5, 16));
</script>
