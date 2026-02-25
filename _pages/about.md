---
permalink: /
title: "Hi, I'm Bryce Tuggle"
author_profile: true
classes:  wide
redirect_from: 
  - /about/
  - /about.html
---

I'm a social scientist based in Seattle, WA, currently working at the [City of Bellevue](https://bellevuewa.gov/) as the city's Chief Demographer where I use data and research to help government work better for people.

My work sits at the intersection of public policy, human behavior, and applied social science — translating research and disparate data into practical insights that can actually influence how decisions get made. I'm drawn to questions about how communities function, how institutions respond to change, and how evidence can (and sometimes can't) cut through the noise of public life.

## Background

My undergraduate degree is in history with a focus on Latin American (primarily Mexico). In my master's program at the University of Georgia I studied comparative politics and international relations with a continued focus on Latin America. My thesis was on the ways in which the tumultuous social and political history of Mexico contributed to the persistence of the PRI single-party state for the majority of the 20th Century despite its deep corruption. 

I subsequently earned my Ph.D. in political science from Vanderbilt University in the Summer of 2021. My studies focused primarily on empirical research methodology, political psychology, and comparative politics. My dissertation was on the impact of criminal disenfranchisement in democratic political systems. Specifically I examined how it impacted mass public opinion, the self-perceptions of disenfranchised invdividuals themselves, and measures of democratic good governance.

In between my undergraduate and master's programs I worked at the world famous combination pizza restaurant, climbing store, and campground [Miguel's](https://miguelspizza.com/) while living out of my tent and climbing everyday in the beautiful Red River Gorge. I also worked in several breweries ([Stone](https://www.stonebrewing.com/), [Foothills](https://www.foothillsbrewing.com/), and [Terrapin](https://www.terrapinbeer.com/) to be exact) doing everything from operating a bottle filler to running a barrel-aged beer program (feel free to ask me about my gold medal from the Great American Beer Festival).

Before my current role, I worked as the policy analyst for the nonpartisian, non-profit state research center [The Sycamore Institute](https://sycamoretn.org/) based in Nashville, TN.

## Beyond the Work

When I'm not doing social science things, I'm usually out running the trails around Seattle, experimenting in the kitchen, or finding an excuse to be somewhere outdoors. I believe strongly in the value of whimsy — that a little playfulness makes everything, including rigorous research, better.

## Get in Touch

I'm always happy to connect with researchers, practitioners, or curious people working on questions related to data science, survey research, or the impact of institutions on poltical outcomes. Feel free to reach out at [bryce.tuggle@gmail.com](mailto:bryce.tuggle@gmail.com) or find me on [LinkedIn](https://www.linkedin.com/in/bryce-w-tuggle).

<!-- Easter egg: type "whimsy" anywhere on the page to unlock a surprise -->
<script>
(function() {
  const secret = "whimsy";
  let typed = "";

  document.addEventListener("keydown", function(e) {
    if (["INPUT", "TEXTAREA"].includes(document.activeElement.tagName)) return;

    typed += e.key.toLowerCase();
    if (typed.length > secret.length) {
      typed = typed.slice(typed.length - secret.length);
    }

    if (typed === secret) {
      typed = "";
      launchDKJr();
    }
  });

  function launchDKJr() {
    const overlay = document.createElement("div");
    overlay.id = "dkjr-overlay";
    overlay.style.cssText = [
      "position:fixed", "top:0", "left:0",
      "width:100vw", "height:100vh",
      "background:rgba(0,0,0,0.92)",
      "z-index:99999",
      "display:flex",
      "flex-direction:column",
      "align-items:center",
      "justify-content:center",
      "font-family:monospace"
    ].join(";");

    const title = document.createElement("div");
    title.innerHTML = "&#x1F98D; <strong style='color:#f5c518;font-size:1.4rem;'>You found the whimsy.</strong>";
    title.style.cssText = "color:white;margin-bottom:1rem;font-size:1.1rem;";

    const sub = document.createElement("div");
    sub.textContent = "Save Donkey Kong. You know what to do.";
    sub.style.cssText = "color:#aaa;margin-bottom:1.5rem;font-size:0.9rem;";

    const frame = document.createElement("iframe");
    frame.src = "https://www.free80sarcade.com/nes_Donkeykongjr.php";
    frame.style.cssText = [
      "width:min(780px,95vw)",
      "height:min(600px,70vh)",
      "border:3px solid #f5c518",
      "border-radius:6px"
    ].join(";");
    frame.setAttribute("allowfullscreen", "true");

    const close = document.createElement("button");
    close.textContent = "x  Close & return to the serious stuff";
    close.style.cssText = [
      "margin-top:1.2rem",
      "background:transparent",
      "border:1px solid #555",
      "color:#aaa",
      "padding:0.5rem 1.2rem",
      "border-radius:4px",
      "cursor:pointer",
      "font-family:monospace",
      "font-size:0.85rem"
    ].join(";");
    close.onmouseover = function() { close.style.borderColor="#f5c518"; close.style.color="#f5c518"; };
    close.onmouseout  = function() { close.style.borderColor="#555";    close.style.color="#aaa"; };
    close.onclick = function() { document.body.removeChild(overlay); };

    document.addEventListener("keydown", function escClose(e) {
      if (e.key === "Escape" && document.getElementById("dkjr-overlay")) {
        document.body.removeChild(overlay);
        document.removeEventListener("keydown", escClose);
      }
    });

    overlay.appendChild(title);
    overlay.appendChild(sub);
    overlay.appendChild(frame);
    overlay.appendChild(close);
    document.body.appendChild(overlay);
  }
})();
</script>

