---
title: Inscription
date: 2023-03-21T21:12:56+01:00
draft: false
layout: single
type: _default
---
La GreLAN 2025 du vendredi 14 mars 20h au dimanche 16  mars 2025 vers 13h, dans la grande salle d’Oxywork au 18 Rue de Brotterode, 38950 Saint-Martin-le-Vinoux, en face de la maison de la Pizza Sana. Voir plan ici.

Prix de 20€ par participant.

Fin des inscriptions sur internet une semaine avant la GreLAN 2025 (soit le lundi 10 mars).

Places limitées à 20, merci de vous inscrire et en cas d'annulation de me prévenir rapidement, pour cela (voir L'association).

Inscriptions validées manuellement à la réception du payement.

## Formulaire d'inscription:

<form id="subscribe" name="subscribe" method="POST" data-netlify="true" data-netlify-recaptcha="true">
  <div class="form">
    <p>
      <label>Nom:</label>
      <input type="text" name="nom" size="20" maxlength="30" placeholder="Votre Nom"/>
    </p>
    <p>
      <label>Prénom:</label>
      <input type="text" name="prenom" size="20" maxlength="30" placeholder="Votre Prénom"/>
    </p>
    <p>
      <label>Age:</label>
      <input type="number" name="age" min="10" max="100" placeholder="18">
    </p>
    <p>
      <label>Pseudo:</label>
      <input type="text" name="pseudo" size="20" maxlength="30" placeholder="Votre Pseudo"/>
    </p>
    <p>
      <label>Team:</label>
      <input type="text" name="team" size="20" maxlength="30" placeholder="Votre Team"/>
    </p>
    <p>
      <label>Ville:</label>
      <input type="text" name="ville" size="20" maxlength="30" placeholder="Votre Ville"/>
    </p>
    <p>
      <label>Adresse e-mail:</label>
      <input type="text" name="mail" size="20" maxlength="50" placeholder="Votre Adresse e-mail"/>
    </p>
    <p>
      <label>Numéro de téléphone:</label>
      <input type="text" name="phone" size="20" maxlength="50" placeholder="Votre Numéro de téléphone"/>
    </p>
    <p>
      <label>Type de PC<sup id="fnref:1"><a href="#fn:1" class="footnote-ref" role="doc-noteref">1</a></sup>:</label>
      <input type="radio" name="type" id="typeChoice1" value="Desktop" checked/> PC fixe
      <input type="radio" name="type" id="typeChoice2" value="Laptop"/> PC portable
    </p>
    <p>
     <label for="secouristeCheckBox">Je possède l'attestation PSC1<sup id="fnref:2"><a href="#fn:2"   class="footnote-ref" role="doc-noteref">2</a></sup>:</label>
     <input type="hidden" name="secouriste" id="secouristeHidden" value="Non"/>
     <input type="checkbox" name="secouriste" id="secouristeCheckBox" value="Oui"/>
    </p>
    <p>
      <label class="lbl-textarea">Commentaires:</label>
      <textarea name="commentaires" maxlength="300" rows="5" cols="50"></textarea>
    </p>
  </div>
  <p>
    <label for="acceptCheckbox"><input type="checkbox" name="accepter" id="acceptCheckbox"   value="Oui"  onchange="document.getElementById('submitSubscribe').disabled = !this.checked;">J'ai lu et j'accepte sans réserve les conditions du règlement intérieur de la GreLAN.</label>
  </p>
  <p>
    <div data-netlify-recaptcha="true"></div>
  </p>
  <p>
    <button type="submit" disabled id="submitSubscribe">Envoyer</button>
    <button type="reset">Recommencer</button>
  </p>
</form>
<script>
document.getElementById('subscribe').addEventListener('submit', function(){
    if(document.getElementById("secouristeCheckBox").checked) {
        document.getElementById('secouristeHidden').disabled = true;
    }
});
</script>

<br/>

[Autorisation parentale](/autorisation.pdf) (seulement pour les mineurs) et [règlement intérieur](/reglement.pdf) à rapporter signé(s) pour la LAN.

<br/>

<section class="footnotes" role="doc-endnotes">
<hr>
<ol>
<li id="fn:1" role="doc-endnote">
<p>Pour nous aider à connaitre nos besoins électriques lors de la GreLAN <a href="#fnref:1" class="footnote-backref" role="doc-backlink">↩︎</a></p>
</li>
<li id="fn:2" role="doc-endnote">
<p>PSC1 (Prévention et Secours Civiques de niveau 1), anciennement nommé AFPS (Attestation de Formation aux Premiers Secours). <a href="#fnref:2" class="footnote-backref" role="doc-backlink">↩︎</a></p>
</li>
</ol>
</section>