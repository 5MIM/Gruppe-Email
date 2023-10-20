# Email Dokumentation



## Ablauf einer Email Kommunikation

Situation: Client 1 will eine Email an einen 2. Client senden

- Das verwendete Protokoll heißt
  


1.  sendet per SMTPS die Email an einen 2 Client dabei gelten beide Clients als MUA  ( Mail User Agent )
2. Der Client 1 sendet die Mail an den Mail server von seiner Domaine. Dieser Mailserver erfragt dann beim DNS System nach der Addresse der Ziel Domaine von client 2.
3. Der Mailserver von Client 1 sendet nun die Email an den Mailserver der in der Domaine von client 2 ist 
4. Der Mailserver sendet die Email an den Client 2


# Test

### Platzhalter
<details>
  <summary>Wie heißt das Protokoll?</summary>

  <select id="dropdown">
    <option value="option1">MTA</option>
    <option value="option2">MUA</option>
    <option value="option3">SMTP</option>
  </select>

  <button onclick="displayOption()">Select</button>

  <p id="result"></p>


</details>



### platzhalter



### platzhalter



### Platzhalter


### Platzhalter
