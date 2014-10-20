PUSieciowych
============

Zajęcia 2:

RPC - Private Procedure Call
PVM - Parallel Virtual Machine
RMI - Remote Method Call

OMG: wyprodukowała CORBA która pozwalała na komunikację obiektów z różnych technologii.


__SOAP__ (ang.) Simple Object Access Protocol – protokół wywoływania zdalnego dostępu do obiektów, wykorzystujący XML do kodowania wywołań i najczęściej protokołów HTTP lub RPC do ich przenoszenia, możliwe jest jednak wykorzystanie innych protokołów do transportu danych.

__Usługa internetowa__ (ang. web service) – realizowana programistycznie usługa świadczona poprzez sieć telekomunikacyjną, a w tym sieć komputerową, w szczególności przez Internet.

__Usługa internetowa__ jest w istocie składnikiem oprogramowania, niezależnym od platformy sprzętowej oraz implementacji, dostarczającym określonej funkcjonalności. Zgodnie z zaleceniami W3C, dane przekazywane są zazwyczaj za pomocą protokołu HTTP i z wykorzystaniem XML[1].

**XML** (ang. Extensible Markup Language, w wolnym tłumaczeniu Rozszerzalny Język Znaczników) – uniwersalny język znaczników przeznaczony do reprezentowania różnych danych w strukturalizowany sposób.

**XML** jest niezależny od platformy, co umożliwia łatwą wymianę dokumentów pomiędzy heterogenicznymi (różnymi) systemami i znacząco przyczyniło się do popularności tego języka w dobie Internetu. XML jest standardem rekomendowanym oraz specyfikowanym przez organizację W3C.

__XML__ - EXTENSIBLE MARKUP LANGUAGE


__Representational State Transfer__ – wzorzec architektury oprogramowania wywiedziony z doświadczeń przy pisaniu specyfikacji protokołu HTTP. REST jest wzorcem architektury oprogramowania wprowadzającym dobre praktyki tworzenia architektury aplikacji rozproszonych.

*REST* wprowadza terminy takie jak jednorodny interfejs, bezstanowa komunikacja, zasób, reprezentacja, HATEOAS.

Zaproponowany przez Roya T. Fieldinga w 2000 roku[1].

Jest wykorzystywany przez wiele frameworków aplikacji internetowych np. Jersey, Ruby on Rails, Apache Sling, Sinatra, Django, RESTlet, RESTeasy i wiele innych.

Charakterystycznym elementem REST jest "restowy" (RESTful) interfejs usług webowych, w którym parametry wywołania danej usługi są umieszczane w ścieżce adresu URL, a nie w części przeznaczonej na parametry, jak w klasycznych wywołaniach GET lub POST:


__Web Services Description Language (WSDL)__ – opracowany przez Microsoft i IBM, oparty na XML język do definiowania usług internetowych.

Język opisuje protokoły i formaty używane przez usługi internetowe. Opisy WSDL mogą być umieszczane w rejestrze UDDI – kombinacja WSDL i UDDI ma się przyczynić do promocji rozwiązań usług internetowych.

WSDL wykorzystuje język XML do opisu punktów dostępu do usług internetowych. Język WSDL definiuje zestaw kilku struktur XML pozwalających na pełny opis usług (struktury danych wymienianych z usługą, sposób połączenia z usługą, najczęściej HTTP).

__W pełni abstrakcyjna klasa__

 interface MojInterface
 {
    int Dodawanie(int a, int b);
    int Odejmowanie(int a, int b);
 }
 
 class Samochod : MojInterface
 class Autobus: MojInterface
 MojInterface abc = new Samochod();
 abc.Dodawanie();
 
 # W DOT.NET
 jeśli dziedzicze po klasie silnik to tak naprawdze dziedziczę również po klasie Object;
 
 ```class Silnk
 {
 }
 class Samochod : Silnik <-- dziedziczy również po silnik.
 
**propercja w przykładzie z wiekiem**
class przyklad
{
DateTime dataUrodzenia;
public int Wiek
  {
    get
      {
      return DateTime.New.Year - dataUrodzenia.Year;
      }
  }
  
  
  Osoba os = new Osoba(){dataUrodzenia ="1987-01-01"};
  WriteLine('os.Wiek');<---wynik```

##zajecia 3

__WCF - Windows Communication Foundation__ (nazwa kodowa Indigo) to następna generacja usług sieciowych. Daje ona wiele nowych możliwości użytkownikom, którzy wymagają, aby ich usługi sieciowe były wszechstronne. WCF jest warstwą komunikacyjną API WinFX i docelowo będzie dostępna dla Microsoft Windows XP, 2003 i Visty.

 HOSTING: możliwości
 1) samochostowanie.
 2) Windows service
 3) IIS
 4) azure
