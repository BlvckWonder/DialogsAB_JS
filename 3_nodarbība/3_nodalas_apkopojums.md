Formas ir instruments, ar kura palīdzību HTML dokumentā var organizēt informācijas nosūtīšanu uz noteiktu vietu. Formas tiek plaši pielietotas dažādās aptaujās, internetā veikalos, elektronisko vēstuļu nosūtīšanā un citās sfērās.
Formas darbības princips ir šāds: lapas apmeklētājs uz sava datora aizpilda pārlūkprogrammas parādīto formu. Nospiežot atbilstošu pogu, kas ir atrodama formā, pārlūkprogramma saņem vajadzīgos datus un aizsūta adresātam. Forma var darboties pilnvērtīgi, ja datorā ir speciālas programmas (script) un pieeja reālam serverim.
Formas apraksts tiek ievietots starp tagiem /form/ un //form/

Katrs tags **/input/** satur dažādus vadības elementus:
 
- parametrs **Name** - raksturo dotā lauka vārdu (lauka identifikators);
- parametrs **Size** - norāda ievades lauka platumu;
- parametrs **Maxlength** - norāda maksimāli iespējamo ievadāmās rindas garumu;
- parametrs **Type** - parametram iespējamas šādas vērtības:

**text** - iestāta lauku teksta ievadei. Piem., /input type="text" size="20" name="User" value="text"/. Šajā piemērā lauka platums 20 simboli;
 
**password** - iestāta paroles ievades lauku. Ievadāmo simbolu vietā parādās simbols *, piem., /input type="password" size="20" name="PW" maxlength="10"/. Šajā piemērā maksimālais lauka platums 20 simboli, bet paroles pieļaujamais garums 10 simboli;
 
**radio** - iestāta pārslēdzējpogu. Var saturēt papildu parametru checked, kas norāda, ka poga ir izvēlēta;
 
**checkbox** - karodziņa (ķeksītis) poga, ar kuru var izdarīt izvēli, iestatīšanu. Papildu parametrs checked parāda, ka poga ir izvēlēta;
 
**hidden** - norāda slēpto datu elementu, kas nav redzams lietotājam pie formas aizpildīšanas. Tāds elements ir bieži vajadzīgs datu apstrādātājam, lai zinātu, ar kādu versiju tiek strādāts: /input type="hidden" name="version" value="1.2"/;
 
**submit** - iestāta pogu, kas apstiprina un pārsūta formas datus: /input type="submit" value="nosūtīt"/;
 
**button** - iestāta parastu pogu. Pogas uzrakstu var norādīt atribūtā value: /input type="button" value="rēķināt"/;
 
**reset** - iestāta pogu, kuru nospiežot forma atgriežas sākuma stāvoklī: /input type="reset" value="dzēst"/

https://www.uzdevumi.lv/p/informatika/11-klase/html-formu-un-ietvaru-lietosana-9608/re-3523647f-4a23-4783-b7a8-9fce96a54838.
 
