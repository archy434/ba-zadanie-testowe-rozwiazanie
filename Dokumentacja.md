AI-Native Technical Project Manager / Business Analyst

Event Storming AS-IS
https://www.figma.com/board/cID48StaJjOFLuFovQwPML/Event-Storming-AS-IS?node-id=0-1&t=JULcIhPFqtgOEH30-1

Event Storming TO-BE
https://www.figma.com/board/Np5qBbx9v8FVkiqbxjlVFQ/Event-Storming-TO-BE?node-id=0-1&p=f&t=08DRqIwlYwSZKt0x-0

1. Specyfikacja rozwiazania:
Zgodnie z diagramem Event Storming TO-BE, AI-CODE processing to centrum przetwarzania wiadomości e-mail,
system human-in-the-loop ze specjalist jako osoba decyzyjna.
2. Integracje:
- ChatGPT Business, Google AutoML, Microsoft Graph API, SAP ERP,
- Jira Api, podpiecie akcji pod przycisk,
- Api do wewnętrznej bazy klientów,
- Zure Blob Storage.
- Native coding.
3. PHP/JAVA 
4. Decyzje kluczowe:
- akceptacja reklamacji i zamówień w rejestrach,
- akceptacja wiadomości e-mail wysyłanej do klienta,

Notatki:
Możliwe zautomatyzowanie z racji subiektywności oceny, np. stworzenie rejestru:
AI 
pobranie danych z wiadomości:
Rejestr zawiera:
dane:
-> zdjęcia
-> numer zamówienia -> konkretny zapis zamówienia np. ZZAAA23324234
-> próba kategoryzacji wady przez AI, możliwość analizy treści np. pod względem występowania treści mogacej posluzyc do kategoryzacji,
-> automatyczne utworzenie ticketu z nowym zgłoszeniem zawierajacym skategoryzowane zg łoszenie, dostęp do tablicy JIRA po api,
->  Stworzenie wiadomości dla osoby obsługujacej zgłoszenie, do wysłania po akceptacji
-> Stworzenie dodatkowego rejestru kategoryzujacego na podstawie nr zamówienia i SKU występujacego w zamowieniu reklamację, 


1. Przeprocesowanie wiadomości e-mail z reklamacja przez AI/Kod.
Po wystapieniu eventu czyli znalezieniu się nowej wiadomości w skrzynce e-mail,
podłaczamy AI przeprocesowuje wiadomość pod katem wady, numeru zamówienia, 
numeru partii, numeru linii produkcyjnej, 


Uwaga:
Czy na pewno na tym etapie czy może wcześniejpowinno być sprawdzone zamówienie w SAP wcześniej?

AI kategoryzacja i wgranie zdjęć do chmury

KOLEJNOSC 1.
Konieczne utworzenie Rejestru z zamowieniami (SAP ERP ) ktory stworzy zamowienie z numerem sku produktu, linia produkcyjna na ktorej dany produkt był produkowany, 

Możliwa wysyłka maili korzystajac z API Microsoft Exchange,
Ustawienie by każdy email był odczytywany przez AI.
