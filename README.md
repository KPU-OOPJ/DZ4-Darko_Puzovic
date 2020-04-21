**Kreirati aplikaciju koji će imati korisnički interfejs kao što je dato na slici i sledeću funkcionalnost:**

a)	Pritiskom na dugme Konvertuj obavlja se akcija konvertovanja vrednosti metričke jedinice koja je upisana u odgovarajuće polje (npr. 45 kg, 30lb, 20 milja itd.) u jedinicu na osnovu izbora stavke konverzije iz padajuće liste. Padajuća lista bi trebalo da ima sledeće stavke: “km -> milje”, “milje -> km”, “m -> stope”, “stope -> m”, “kg -> lb”, “lb -> kg”.

b)	Akcije se obavljaju pomoću javne klase MetrickiKonvertor koja ima: 
-	Javnu metodu konvertujKmUMi koja prima kao ulazni parametar razdaljinu izraženu u kilometrima (realan broj), pretvara je u razdaljinu izraženu u miljama i vraća kao rezultat (1 milja = 1.67 km). 
-	Javnu metodu konvertujMiUKm koja prima kao ulazni parametar razdaljinu izraženu u miljama (realan broj), pretvara je u razdaljinu izraženu u kilometirma i vraća kao rezultat (1 milja = 1.67 km).
-	Javnu metodu konvertujMUSt koja prima kao ulazni parametar razdaljinu izraženu u metrima (realan broj), pretvara je u razdaljinu izraženu u stopama i vraća kao rezultat (1 stopa = 0.32 m).
-	Javnu metodu konvertujStUM koja prima kao ulazni parametar razdaljinu izraženu u stopama (realan broj), pretvara je u razdaljinu izraženu u metrima i vraća kao rezultat (1 stopa = 0.32 m).
-	Javnu metodu konvertujKgULb koja prima kao ulazni parametar težinu izraženu u kilogramima (realan broj), pretvara je u težinu izraženu u librama (lb) i vraća kao rezultat (1 lb = 0.45 kg).
-	Javnu metodu konvertujLbUKg koja prima kao ulazni parametar težinu izraženu u librama (realan broj), pretvara je u težinu izraženu u kilogramima i vraća kao rezultat (1 lb = 0.45 kg).

![7](https://scontent.fbeg6-1.fna.fbcdn.net/v/t1.15752-9/94102003_2736511509792720_5055968915973210112_n.png?_nc_cat=106&_nc_sid=b96e70&_nc_eui2=AeHGb6MLbIy-cr3J80IKTSsa09AmONd789TT0CY413vz1CPVPfMXpAaEE4SgvnzGCzc&_nc_ohc=DXkpFGI1AnUAX_E-Mra&_nc_ht=scontent.fbeg6-1.fna&oh=04b66fb0b8f372c613232de7b85f5ec0&oe=5EC3FBB5)
