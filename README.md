# Home Assistant - OpenEpaper - ElectricPriceTag
OpenEpaper Electric price tag with 12h graf

![open_epaper_link 0000021f1f683b15](https://github.com/cokeman0/OpenEpaperElectricPriceTag/assets/6389802/a6c5b93d-533a-45b9-908e-e070f260df1d)

It shows a 12 hour graf, of the electric price, generated by HA and using "Energi Data Service"

Just uploaded a Nordpool edition, just remember to replace "sensor.nordpool_kwh_dk1_dkk_3_10_025", with you nordpool sensor, and you must do so, i yaml mode to replace them all

Top Row: Current price, date/time, Max, min price (Within the 12 hour window)

And when data it not available, it will show this:

![open_epaper_link 0000021f1f683b15](https://github.com/cokeman0/OpenEpaperElectricPriceTag/assets/6389802/397063e7-0a1c-41da-96ca-0bec35f1fea9)

Create a now automation, switch to yaml mode, and paste content

Font used: OpenSans-Regular.ttf and OpenSans-Semibold.ttf, they are placed in /media/fonts
