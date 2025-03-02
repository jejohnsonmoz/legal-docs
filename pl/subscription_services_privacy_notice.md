﻿# Usługi subskrypcji Mozilla | Zasady prywatności

Wersja 1.0, obowiązuje od 11 października 2022 r.
{: datetime="2022-10-11" }

## W firmie Mozilla projektujemy produkty z myślą o prywatności użytkowników.

__Mozilla VPN__ chroni połączenia internetowe urządzenia użytkownika. Mozilla współpracuje z firmą Mullvad, aby prywatnie i bezpiecznie szyfrować ruch internetowy użytkownika.

__Firefox Relay__ pozwala zachować bezpieczeństwo i prywatność podstawowego adresu e-mail i numeru telefonu użytkownika w usługach online poprzez utworzenie unikatowego, losowego (maska) numeru telefonu i adresów e-mail.

Niniejsze zasady prywatności wyjaśnia, jakie dane usługi Firefox Relay i Mozilla VPN gromadzą i udostępniają oraz dlaczego. Stosujemy się również do [Polityki prywatności](https://www.mozilla.org/privacy/) firmy Mozilla w zakresie sposobów, w jakie otrzymujemy, obsługujemy i udostępniamy informacje.

## Co warto wiedzieć

__Dane konta Firefox.__ Usługi te wymagają konta Firefox, które przesyła do firmy Mozilla adres e-mail, ustawienia regionalne i adres IP użytkownika. Dowiedz się więcej na temat [praktyk dotyczących danych konta Firefox](https://www.mozilla.org/privacy/firefox/#firefox-accounts-join-firefox).

__Informacje o płatności.__ Kiedy użytkownik rozpocznie subskrypcję Usług, dokona płatności za pośrednictwem jednego z naszych zewnętrznych dostawców usług płatniczych: Stripe, Apple, PayPal lub Google Pay. Mozilla otrzymuje dane dotyczące konta użytkownika (w tym jego adres rozliczeniowy i cztery ostatnie cyfry metody płatności) oraz status subskrypcji konta. Mozilla nie przechowuje pełnych danych dotyczących płatności.

__Dane dotyczące interakcji.__ Mozilla otrzymuje dane dotyczące interakcji użytkownika z Usługami. Na przykład, kiedy użytkownik loguje się i wylogowuje oraz preferencje, które użytkownik ustawia. Dowiedz się więcej o [danych dotyczących interakcji z usługą VPN](https://dictionary.telemetry.mozilla.org/apps/mozilla_vpn) oraz [danych dotyczących interakcji z usługą Relay](https://github.com/mozilla/fx-private-relay/blob/main/METRICS.md).

__Dane techniczne.__ Mozilla otrzymuje podstawowe informacje o zainstalowanej wersji dodatkowego oprogramowania VPN lub Relay oraz o urządzeniu, na którym są zainstalowane, w tym o systemie operacyjnym i konfiguracji sprzętowej. Adres IP użytkownika jest tymczasowo gromadzony jako część dzienników naszego serwera przez 90 dni. Podczas korzystania z usługi Mozilla VPN ani Mozilla, ani nasz partner Mullvad nie przechowują żadnych dzienników aktywności użytkownika w sieci.
Używamy tych danych w celu poprawy wydajności i stabilności dla naszych użytkowników oraz w celu pomiaru wydajności Usług.

### Mozilla VPN {: #vpn }

__Dane lokalizacji.__ Mozilla VPN otrzymuje adres IP użytkownika, gdy użytkownik rejestruje się i korzysta z usługi. Używamy adresu IP w celu oszacowania lokalizacji użytkownika, aby ustalić, z którym serwerem VPN użytkownik się łączy, a także dlatego, że dostępność, ceny i oferty usługi Mozilla VPN mogą zależeć od kraju użytkownika.

__Dane kampanii i odwołań__. Pomaga to usłudze Mozilla VPN mierzyć skuteczność kampanii marketingowych. Po zainstalowaniu aplikacji Mozilla może otrzymać adres IP użytkownika, a także dane kampanii i dane odwołań, takie jak kampanie reklamowe, w przypadku których użytkownik podjął aktywność, system operacyjny, typ urządzenia, identyfikatory urządzenia i wersję systemu operacyjnego. Mozilla udostępnia te dane firmie Adjust, ale nie udostępnia ani nie przechowuje adresu IP użytkownika. Przeczytaj [dokumentację Adjust](https://github.com/mozilla-mobile/mozilla-vpn-client/blob/main/src/shared/adjust/adjust.md).

__Dane dotyczące sieci.__ Mullvad otrzymuje ruch internetowy użytkownika w celu świadczenia usługi. Po aktywowaniu usługa Mozilla VPN będzie szyfrować ruch internetowy użytkownika i wysyłać go do firmy Mullvad. Firma Mullvad zobowiązała się nie rejestrować żadnych otrzymywanych danych. Dowiedz się więcej w [Polityce prywatności firmy Mullvad](https://mullvad.net/help/no-logging-data-policy/).

### Firefox Relay {: #relay }

__Wiadomości e-mail.__ Aby wysyłać i przekazywać wiadomości e-mail z zamaskowanych adresów e-mail na podstawowy adres e-mail, Firefox Relay przetwarza wiadomości e-mail. Nie czytamy ani nie przechowujemy treści wiadomości użytkownika. W przypadku, gdy wiadomość e-mail nie może zostać dostarczona do użytkownika, zachowamy ją na naszych serwerach i usuniemy po jej dostarczeniu (w żadnym wypadku nie będziemy jej przechowywać dłużej niż trzy dni). Jeśli użytkownik korzysta z funkcji blokowania promocyjnych wiadomości e-mail, Usługa sprawdzi nagłówki wiadomości e-mail w celu ustalenia, czy wiadomość e-mail powinna zostać zablokowana.

__Maski i miejsce ich użycia.__ Mozilla przechowuje kopię informacji o koncie użytkownika w celu świadczenia usługi, w szczególności w celu powiązania podstawowego adresu e-mail użytkownika z zamaskowanymi adresami e-mail. Jeśli użytkownik utworzy niestandardową maskę, Mozilla będzie ją przechowywać w celu przekazywania do niej wiadomości e-mail. Mozilla przechowuje witrynę, w której utworzono maskę, witryny, w których później użyto maski, oraz wszelkie etykiety powiązane z maską, aby zapewnić, że maski użytkownika będą łatwe do znalezienia, gdy będzie konieczne ich użycie. Dowiedz się, jak [włączać i wyłączać te funkcje](https://relay.firefox.com/faq).

__Połączenia telefoniczne i wiadomości tekstowe.__ Aby wysyłać i przekazywać połączenia telefoniczne i wiadomości tekstowe, usługa Firefox Relay przetwarza numer telefonu i wiadomości tekstowe użytkownika. Przechowujemy rejestr numerów telefonów, z którymi użytkownik kontaktował się za pośrednictwem usługi Relay, aby wyświetlać rejestry połączeń i wiadomości tekstowych, wysyłać odpowiedzi tekstowe i blokować numery telefonów. Nie monitorujemy ani nie przechowujemy treści połączeń telefonicznych, które użytkownik wykonuje za pośrednictwem usługi Firefox Relay.

Przeczytaj dokumentację telemetrii w usłudze [Firefox Relay](https://github.com/mozilla/fx-private-relay/blob/main/METRICS.md). Użytkownik może zrezygnować z gromadzenia danych telemetrycznych, włączając funkcję [Do Not Track (DNT)](https://support.mozilla.org/kb/how-do-i-turn-do-not-track-feature) w swojej przeglądarce.

__Informacje, które udostępniamy.__ Firefox Relay udostępnia informacje stronom trzecim w celu świadczenia usług dla użytkownika. Mozilla zawarła umowę z tą firmą, zobowiązując ją do ochrony danych użytkownika. Oto firmy, których usług używamy do obsługi Firefox Relay:

* __[Amazon Web Services.](https://aws.amazon.com/privacy/)__ Amazon Web Services (AWS) to platforma przetwarzania w chmurze. Firefox Relay używa usług AWS do odbierania wiadomości e-mail wysyłanych na zamaskowane adresy e-mail użytkownika i przekazywania ich na podstawowy adres e-mail powiązany z kontem Firefox użytkownika. Tylko Mozilla zna powiązanie między podstawowym adresem e-mail użytkownika a zamaskowanymi adresami e-mail.

* __[Twilio.](https://www.twilio.com)__ Twilio otrzymuje numer telefonu użytkownika, maskę telefonu oraz numery telefonów, z którymi użytkownik wymienia połączenia telefoniczne i wiadomości tekstowe. Twilio otrzymuje również treść wiadomości tekstowych wysyłanych i odbieranych przez użytkownika za pośrednictwem usługi Firefox Relay, a Mozilla ustawiła usługę Twilio tak, aby usuwała swoje zapisy wiadomości tekstowych wysyłanych i odbieranych przez użytkownika za pośrednictwem usługi Firefox Relay po 7 dniach.

## Inne informacje, które należy znać

Wiele informacji, które przechowujemy na temat użytkowników konta Firefox, jest łatwo dostępnych po zalogowaniu się na konto. Możesz [dowiedzieć się więcej na temat zarządzania swoimi danymi](https://support.mozilla.org/products/privacy-and-security/user-control). Aby złożyć wniosek, należy skontaktować się z nami za pośrednictwem [Portalu wniosków o dostęp do danych osobowych](https://privacyportal.onetrust.com/webform/1350748f-7139-405c-8188-22740b3b5587/4ba08202-2ede-4934-a89e-f0b0870f95f0).

W razie jakichkolwiek innych pytań dotyczących naszych praktyk w zakresie ochrony prywatności, prosimy o kontakt pod adresem compliance@mozilla.com.

Odpowiadamy na wszystkie wnioski otrzymywane od osób pragnących skorzystać z przysługujących im praw w zakresie ochrony danych, niezależnie od ich miejsca zamieszkania. Uwzględnimy wniosek użytkownika, chyba że uniemożliwi nam to wymóg prawny lub ma zastosowanie wyjątek prawny.

Aby uzyskać ogólną pomocą, prosimy odwiedzić nasze [fora](https://support.mozilla.org/).
