# Frontend-opdracht-1-1.1<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Formulier</title>
</head>
<body>
    <h1>Aanmelden</h1>
        <p>Bent u geïnteresseerd in samenwerken met CMD Amsterdam? Dat kan!
           Tijdens de opleiding werken studenten aan projecten voor echte opdrachtgevers. Ook
           lopen de studenten stage, in het tweede en afstudeerjaar.
        </p>
   
        <p>
            <i>
              CMD Amsterdam zoekt altijd naar positieve verbindingen met de creatieve stad
              Amsterdam.
            </i>
        </p>
       
       
       <p>Voor het aanmelden van stageplekken of projecten kunt u onderstaand formulier invullen.
          Wij nemen zo nodig contact met u op nadat het formulier is verstuurd.
          Voor vragen of opmerkingen kunt u <a href="http://www.hva.nl/over-de-hva/contact/contact.html">contact</a> met ons op.
       </p>
       
       
       
      <form> 
       <fieldset>
          <legend>Contactgegevens</legend><br>
           <label>naam
               <input type="text" name="achternaam" placeholder="vul hier uw naam in"></label><br>
               <label>bedrijf 
               <input type="text" name="bedrijf" placeholder="vul hier uw bedrijf in"></label><br>
       </fieldset>
       
       <fieldset>
           <label>adres <input type="text" name="adres" placeholder="vul hier uw adres in"></label><br>
           <label>postcode <input type="text" pattern="[1-9][0-9]{3}\s?[a-zA-Z]{2}" placeholder="vul hier uw postcode in"></label><br>
           <label>plaats <input type="text" name="plaats" placeholder="vul hier uw woonplaats in"></label><br>
       </fieldset>
       
       <fieldset>
       <label>telefoon <input type="tel" required placeholder="vul hier uw telefoonnummer in"></label> <br>
       <label>email <input type="email" placeholder="vul hier uw email-adres in"></label><br>
       </fieldset>    
    <br>
    Ik wil mij aanmelden:<br>
<input type="radio" name="group1" value="Stage"> Voor een stage<br>
<input type="radio" name="group1" value="Bedrijf" checked> Voor een bedrijf<br><br><br>
</form>

<!--<table>
    <thead>
        <tr>
            <th></th>
            <th scope="col">Project</th>
            <th scope="col">Stage</th>
        </tr>
    </thead>
    
    <tbody>
        <tr>
            <th></th>
                <td>1.titel</td>
                <td>geschikt voor</td>
        </tr>
        <tr>
            <th></th>
                <td>2. Opdrachtomschrijving</td>
                <td>1. tweedejaars studenten</td>
        </tr>
        <tr>
            <th></th>
                <td>3. Doelgroepomschrijving</td>
                <td>2. afstudeer studenten</td>
        </tr>
        <tr>
            <th></th>
                <td>4. Doelstelling/ intentie van het project</td>
                <td>3. onbekend</td>
        </tr>
        <tr>
            <th></th>
                <td>5. Looptijd</td>
                <td></td>
        </tr>
        <tr>
            <th></th>
                <td>6. Deadline</td>
                <td></td>
        </tr>
        
    </tbody>
    
    
</table>-->

           <form>
               <fieldset style="width:500px;">
                   <legend>Project</legend>
                       <label>titel <br>
                           <input type="text" name="Titel" placeholder="titel van project"></label><br>
                        <label>opdrachtomschrijving
                            <textarea rows="4" cols="50"></textarea></label><br>
                        <label>doelgroepsomschrijving
                            <textarea rows="4" cols="50"></textarea></label><br>
                        <label>doelstelling/intentie van project
                              <textarea rows="4" cols="50"></textarea></label><br><br>
                        <label>looptijd
                            <input type="text" name="looptijd" placeholder="vul hier de looptijd in"></label><br>
                        <label>deadline
                            <input type="date" name="deadline"></label><br>
                   
               </fieldset>
               <fieldset style="width:500px;">
                   <legend>geschikt voor</legend>
                 
                           <label>eerstejaars studenten <input type="checkbox" name="eerstejaars"></label><br>
                      
                            <label>tweedejaars studenten<input type="checkbox" name="tweedejaars"></label><br>
                        
                                <label>derdejaars studenten<input type="checkbox" name="derdejaars"><br></label>
                        
                            <label>afstudeerstudenten<input type="checkbox" name="afstudeer"></label><br>
                        
                            <label>onbekend<input type="checkbox" name="onbekend"></label><br>
                            </fieldset>                      
                   <fieldset style="width:500px;">
                       <label>opmerking  <textarea rows="4" cols="50"></textarea></label><br>
                                     
                   </fieldset>    
           </form>
           <br>
           <fieldset style="width:500px;">
               <form>
                   <p>stage</p><br>
                          geschikt voor
                           <fieldset>
                      
                                   <label>eerstejaars studenten<input type="checkbox" name="eerstejaars"></label><br>
                                   <label>tweedejaars studenten<input type="checkbox" name="tweedejaars"></label><br>
                                   <label>onbekend<input type="checkbox" name="onbekend"></label><br>
                       
                           </fieldset>
                   
                           <fieldset>
                               <p>1.Hoe lang is de stage?</p>
                                    <label>10 weken<input type="radio" name="weken"></label><br>
                                    <label>20 weken<input type="radio" name="weken"></label>
                               
                           </fieldset>
                           
                            <fieldset>
                                
                                <label>beschrijving stagewerkzaamheden<textarea rows="4" cols="50"></textarea></label>
                                        
                            </fieldset>
                   
                                <fieldset>
                                    <p>beschrijving bedrijf</p>
                                    <label>bedrijfsnaam<input type="text" name="bedrijf" placeholder="naam van bedrijf"></label><br>
                                    <label>adres<input type="text" name="adres" placeholder="vul hier het adres in"></label><br>
                                    <label>postcode<input type="text" name="postcode" pattern="[1-9][0-9]{3}\s?[a-zA-Z]{2}" placeholder="vul hier de postcode in"></label><br>
                                    <label>plaats<input type="text" name="plaats" placeholder="vul hier de plaats in"></label><br>
                                    <label>sector<input type="text" name="sector" placeholder="vul hier de sector in"></label><br>
                                    <label>core business<input type="text" name="core business" placeholder="vul hier de core business in"></label><br>
                                    
                                </fieldset>
                   </form>
                </fieldset>
                              <fieldset style="width:500px;">
                       <label>opmerking  <textarea rows="4" cols="50"></textarea></label><br>
                                     
                   </fieldset> 
                 
                
                
</body>
</html>
