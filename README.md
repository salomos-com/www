
![obraz](https://github.com/salomos-com/www/assets/5669657/32a99889-f886-42e2-a84d-b95c40defcb1)

# [salomos.com](http://www.salomos.com)


Salomos - smart operations in company. 
Salomos is a voice assistant for the company's operational activities. Works in a flow: SPEECH->NLP->SQL->API providers

![_3f834d89-3ae8-4007-978c-4c518f6d7b11](https://github.com/salomos-com/www/assets/5669657/6ed30938-35fe-40db-9b26-deeeb2f69d3a)




![_a5608541-54df-42de-80bd-a0e72a297429](https://github.com/salomos-com/www/assets/5669657/fdfe07f0-9081-4bca-a8fb-0dc65f11ee72)



# SQL mapping

sql statement mapping to API rest service

+ [Create REST APIs based on SQL statements - IBM Developer](https://developer.ibm.com/tutorials/creating-rest-apis-based-on-sql-statements/)



## keywords

intelligent vision system
intelligent system
supersystem
supervision
hypersystem
smart operations



## Oferta

oglądałem gpt4o i w zasadzie to coś podobnego chcę w opensource udostepniac, ale na poziomie SQL i protokołów streamowania audio i video
no i dodatkowo asystenta do firmy do prowadzenia operacji i zlecenia mu nowych powtarzalnych zadan
tylko mam  malo czasu i zasobow

W sensie, że sam budujesz takiego asystenta?

korzystam z gotowych roziwązań opensource, buduję tylko infrastrukturę, aktualnie na poziomie docker compose, zastanawiam się jak zarobić na tym.

a jaką wartość dla użytkownika końcowego widzisz? 

## Dlaczego ja miałbym to od Ciebie kupić?

zadajesz słuszne pytanie, nie tyle o funkcje, co o integracj z danymi organizacji i z kanałami komunikacyjnymi
Integracja infrastruktury na poziomie protokołów komunikacyjnych jak IMAP/SMTP, danych SQL, dokumentów, WEBDAV/FTP, itd
moim pierwotnym założeniem było oferowanie sterowanego  głosowo systemu kamer w oparciu o już istniejący system CCTV
ale w trakcie tworzenia zauważyłem, ze są tam 3 różne systemy: obróbka wideo, komunikacja audio i mózg do przeszukiwania zdarzeń, detekcji obiektów

w sytuacji interfejsu audio może to mieć postać strony www, apki, itd to co jednak istotne, to sposób przehcowywania danych i dostępu do nich, tak by większa ilość osób mogła korzystać,  skorzystałem z API telegrama, aby stworzyć grupę, do której można dodawać znajomych i w ten sposób też zarządzać użytkownikami a wiadomości są analizowane i generowane przez serwer podłączony do tej grupy

korzyści z asystenta, który odpowiada głosowo w oparciu o  rzeczywiste dane firmy w trybie online jest samo w s obie pomocne, ale to co jest ważne, to powiadamianie o incydentach oraz planowanie powtarzalnych zadan, czyli automatyzacja, bez potrzeby tworzenia tych smiesznych grafów w zewnetrznych cloudach SaaS

tylko jak to sprzedać nie wiem, bo to jest abstrakcja dla wielu, wiec nawet jak to zaoferuje za darmo i lokalnie to nadal większośc nie będzie zainteresowana
zastanawiam się jak dotrzeć do tych, którzy by docenili i chcieli zapłacić każdą cenę za wdrożenie tego lokalnie w ich firmie
