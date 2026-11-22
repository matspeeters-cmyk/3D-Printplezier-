# 3D Printplezier

Een statische webshop-demo gebaseerd op de aangeleverde schermopname, met de naam **3D Printplezier**.

## Online zetten met GitHub Pages
1. Maak op GitHub een nieuwe repository, bijvoorbeeld `3d-printplezier`.
2. Upload `index.html`, `README.md` en de map `images`.
3. Open **Settings → Pages**.
4. Kies **Deploy from a branch**, selecteer `main` en map `/ (root)`, en klik op **Save**.
5. Na het publiceren staat je website op `https://JOUW-GITHUB-NAAM.github.io/3d-printplezier/`.

## Eerst aanpassen
- Vervang de `href="#"` links voor WhatsApp-kanaal en YouTube door je eigen kanaallinks.
- Pas het e-mailadres `info@3dprintplezier.nl` aan als je een ander adres gebruikt.
- Pas de voorbeeldproducten en prijzen aan in de `products`-lijst onderaan `index.html`.
- Vul voor WhatsApp-bestellen je eigen telefoonnummer in. In `sendOrder()` vervang je `https://wa.me/?text=` door `https://wa.me/31JOUWNUMMER?text=` (zonder plus of spaties).

## Belangrijk
Dit is een front-end demo: er is nog geen echte betaalprovider, voorraadbeheer of database gekoppeld. Bestellen opent WhatsApp; de klant verstuurt het bericht zelf. Productnamen en prijzen zijn voorbeeldinhoud uit de schermopname en moeten door jou gecontroleerd worden.
