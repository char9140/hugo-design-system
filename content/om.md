---
title: "Om"
date: 2018-02-01T08:46:28+01:00
draft: true
description: Lær mere om designsystemet eller kontakt os
---

<div class="container">
        <div id="formfeedback" class="hidden">Tak for beskeden! Vi vender tilbage til dig hurtigst muligt</div>
          <form action="" method="post" id="kontaktmig">
              <label for="Navn">Navn</label>
              <input type="text" id="navn" name="navn" placeholder="Dit navn">
              <label for="email">E-mail</label>
              <input type="email" id="email" name="email" placeholder="Din e-mail">
              <label for="henvendelse">Jeg henvender mig vedr.:</label>
              <select id="henvendelse" name="henvendelse">
                <option value="support">Support</option>
                <option value="tilbud">Tilbud</option>
                <option value="prepurchase">Spørgsmål før køb</option>
              </select>
              <label for="besked">Besked</label>
              <textarea id="besked" name="besked" placeholder="Din besked.."></textarea>
              <input type="submit" name="submit" value="Submit">
              <div id="formfailure" class="hidden"></div>
          </form>
      </div>
