# Instruktioner

Gå igenom alla steg för att slutföra projektet. Kom ihåg att varje steg är en viktig del i att bygga upp ditt första kvittosystem!

## Steg för steg

### Skapa katalogen

1. Lägg till den första varan, vår älskade **kärlekssoffa**, stjärnan i vår butik. Skapa `lovely_loveseat_description` med följande text:
   ```python
   # Beskrivning av Kärlekssoffa
   Härlig Kärlekssoffa i polyesterblandning. Ett träunderrede bär upp denna 81 cm höga, 102 cm breda och 76 cm djupa soffa. Finns i röd eller vit.
   ```

2. Sätt ett pris på kärlekssoffan. Skapa variabeln `lovely_loveseat_price` och tilldela `254.00`.

3. Utöka sortimentet med en **stilfull bänksoffa**. Skapa variabeln `stylish_settee_description`:
   ```python
   # Beskrivning av Bänksoffa
   Stilfull Bänksoffa i svart konstläder. Slank och modern design på björkben. Mått: 75 cm hög, 139 cm bred och 71 cm djup.
   ```

4. Sätt ett pris på bänksoffan. Skapa variabeln `stylish_settee_price` och ange `180.50`.

5. Glöm inte att lägga till en **lyxig lampa** för en fulländad inredningsupplevelse. Skapa variabeln `luxurious_lamp_description` med följande information:
   ```python
   # Beskrivning av Lyxig Lampa
   Lyxig Lampa i glas och järn. Stående 91 cm hög, med en brun bas och en cremefärgad skärm, sprider den ett behagligt ljus.
   ```

6. Prissätt denna eleganta lampa. Använd `luxurious_lamp_price` och sätt den till `52.15`.

7. Som en del av affärsprocessen, glöm inte att räkna med försäljningsskatt. Skapa `sales_tax` och sätt den till `0.088` (8,8%).


### Vår första kund

8. Vår första kund gör ett köp! Skapa variabeln `customer_one_total` för att hålla reda på deras utgifter. Sätt den till `0`.

9. **Registrera kundens inköp**. Skapa `customer_one_itemization` som en tom sträng `""`.

10. Lägg till kostnaden för den härliga Kärlekssoffan i `customer_one_total`.

11. Inkludera beskrivningen av Kärlekssoffan i `customer_one_itemization`.

12. Addera priset för den lyxiga Lampan till kundens totalbelopp.

13. Uppdatera kundens varulista med detaljerna om den lyxiga Lampan.

14. Beräkna försäljningsskatten när kunden är redo att betala. Använd `customer_one_tax` för att beräkna skatten baserat på `customer_one_total` och `sales_tax`.

15. Lägg till skatten i kundens slutgiltiga kostnad. Nu närmar vi oss slutet!

16. **Dags att skapa ett kvitto!** Börja med att skriva ut en rubrik för kundens varor. Använd frasen `"Varor för Kund Ett:"`.

17. Skriv ut `customer_one_itemization` på kvittot.

18. Fortsätt med att lägga till en rubrik för den totala kostnaden: Skriv ut `"Totalt för Kund Ett:"`.

19. Presentera den slutliga summan. Nu har vår första kund fått ett detaljerat kvitto på sina inköp. Vilken fantastisk start!

20. **Fantastiskt arbete!** Vi har nu satt ihop vår första katalog och hjälpt vår första kund. Vi har använt vår kunskap om strängar och nummer för att skapa och uppdatera variabler och framgångsrikt kunnat presentera en detaljerad lista och total kostnad för kunden. Väl utfört!
