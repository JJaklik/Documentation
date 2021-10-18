# Welcome to CI



# Conversational Intelligence

Rozwiązanie Voicelab.ai Conversational Intelligence to nowoczesny system umożliwiający automatyczną transkrypcję, analizę, kategoryzację i kontrolę nagranych rozmów. Dzięki najnowszym technologiom z dziedziny rozpoznawania mowy i uczenia maszynowego zapewnia on wysoką skuteczność transkrypcji oraz weryfikacji zgodności rozmowy ze zdefiniowanym scenariuszem, jak również pozwala na odkrywanie trendów i nowych tematów pojawiających się w interakcjach.

## Główne funkcjonalności:
System działa zarówno w trybie online jak i offline. 
W zależności od potrzeb klienta oferujemy możliwość integracji potrzebnej do działania systemu. Jako offline rozumie się ładowanie rozmów historycznych - po znalezieniu się danej rozmowy w kolejce nagrań do przetworzenia rozmowa jest zaimportowana do systemu. Jako online rozumie się przetwarzanie na żądanie wybranych przez użytkownika rozmów w postaci ustalonych wcześniej kanałów które są przesyłane w realtime.
System umożliwia integrację z narzędziami BI poprzez REST API.
Zarządzanie biznesowe funkcjonalnościami dostępne jest poprzez interfejs WEB.
System, na podstawie rozmów wideo, analizuje głos Agenta oraz Klienta i na tej podstawie dokonuje dalszej oceny tak jak w przypadku zwykłego połączenia Voice. 
Wymaganie jest spełniane, jeżeli pliki pochodzące ze źródła video będą dostarczone w formacie audio do analizy. To znaczy, że system działa i dokonuje dalszych analiz jak w przypadku zwykłych połączeń.
System daje możliwość pozyskiwania informacji o stanie parametrów systemu, których rozumienie i lista jest uzgodniona (logi, zdarzenia systemu itp.).
System udostępnia alertowanie – to znaczy zdefiniowane wcześniej kryteria powiadamiania użytkowników (np. supervisorów) o zwiększeniu trendu w danej kategorii lub zdarzeń w karcie oceny.











## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
