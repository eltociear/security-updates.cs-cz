---
TOCTitle: 'MS08-OCT'
Title: 'Souhrnný bulletin zabezpečení společnosti Microsoft, říjen 2008'
ms:assetid: 'ms08-oct'
ms:contentKeyID: 61223980
ms:mtpsurl: 'https://technet.microsoft.com/cs-CZ/library/ms08-oct(v=Security.10)'
---

 

Souhrnný bulletin zabezpečení společnosti Microsoft, říjen 2008
===============================================================

Publikováno: 14. října 2008 | Aktualizováno: 23. října 2008

**Verze:** 3.0

Tento souhrnný bulletin uvádí bulletiny zabezpečení vydané v říjnu 2008.

Spolu s vydáním bulletinů pro říjen 2008 nahrazuje tento souhrnný bulletin předběžné oznámení o bulletinech vydané 9. října 2008. Další informace o službě předběžného oznámení o bulletinech naleznete v části [Předběžné oznámení o bulletinech zabezpečení společnosti Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Informace o tom, jak dostávat automatická oznámení o vydání nových bulletinů zabezpečení společnosti Microsoft, naleznete na webu [Zasílání technických oznámení o zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

Pro zodpovězení zákaznických dotazů týkajících se těchto bulletinů uspořádá společnost Microsoft webové vysílání dne 15. října 2008 v 11:00 časového pásma Tichomoří (USA a Kanada). [Registrovat se pro webové vysílání týkající se říjnových bulletinů zabezpečení](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374639). Po tomto datu je webové vysílání dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://technet.microsoft.com/security/bulletin/summary).

Společnost Microsoft se snaží zákazníkům usnadnit upřednostnění měsíčně vydávaných aktualizací zabezpečení před jakýmikoli důležitými aktualizacemi nesouvisejícími se zabezpečením, které jsou vydány ve stejný den jako měsíčně vydávané aktualizace zabezpečení. Další informace získáte v části **Další informace**.

### Informace o bulletinech

#### Shrnutí

Bulletiny zabezpečení podle závažnosti:

Kritický (5)
------------

 

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-067                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení služby Server umožňuje vzdálené spuštění kódu (958644)**](http://go.microsoft.com/fwlink/?linkid=130719)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu služby Server oznámenou soukromou osobou. Daná chyba zabezpečení by mohla umožnit vzdálené spuštění kódu v případě, že by uživateli ohroženého systému byl doručen speciálně vytvořený požadavek RPC. V systémech Microsoft Windows 2000, Windows XP a Windows Server 2003 by útočník mohl uvedenou chybu zabezpečení zneužít ke spuštění libovolného kódu bez ověření. Tato chyba zabezpečení pravděpodobně také umožňuje zneužití prostřednictvím červa. Doporučené postupy pro používání brány firewall a její standardní výchozí konfigurace zajišťují ochranu síťových prostředků před útoky pocházejícími z oblasti mimo rozlehlou síť. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-060                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení služby Active Directory umožňuje vzdálené spuštění kódu (957280)**](http://go.microsoft.com/fwlink/?linkid=128125)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení oznámenou soukromou osobou v implementacích služby Active Directory v systému Microsoft Windows 2000 Server. Tato chyba zabezpečení by mohla povolit vzdálené spuštění kódu, pokud útočník získá přístup do postižené sítě. K této chybě zabezpečení dochází pouze u serverů se systémem Microsoft Windows 2000, které jsou nakonfigurovány jako řadiče domény. Pokud nebyl server se systémem Microsoft Windows 2000 povýšen na řadič domény, nebude naslouchat dotazům protokolu LDAP (Lightweight Directory Access Protocol) nebo LDAPS (LDAP přes SSL) a nebude této chybě zabezpečení vystaven. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-058                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (956390)**](http://go.microsoft.com/fwlink/?linkid=128060)                                                                                                                                                                                                                                                                                                                                                              |
| **Shrnutí**                        | Tato kritická aktualizace zabezpečení řeší pět chyb zabezpečení oznámených soukromými osobami a jednu veřejně známou chybu. Tyto chyby zabezpečení mohou umožňovat přístup k informacím nebo vzdálené spuštění kódu, pokud uživatel zobrazí pomocí aplikace Internet Explorer speciálně vytvořenou webovou stránku. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                                                                                                                                              |
| **Software obsahující tuto chybu** | **Microsoft Windows, Internet Explorer.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                   |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-059                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení ve službě Host Integration Server RPC Service umožňuje vzdálené spuštění kódu (956695)**](http://go.microsoft.com/fwlink/?linkid=125712)                                                                                                                                                                                                                                                                                                                                                                                        |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení na serveru Microsoft Host Integration Server oznámenou soukromou osobou. Tato chyba zabezpečení může umožnit vzdálené spuštění kódu, pokud útočník odešle do postiženého systému speciálně vytvořený požadavek vzdáleného volání procedur (RPC). Zákazníci, kteří dodržují osvědčené postupy a nakonfigurují účet služby SNA RPC tak, aby měli méně uživatelských oprávnění k systému, budou chybou méně ohroženi než ti, kdo nakonfigurují účet služby SNA RPC tak, aby měli oprávnění správce. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Aktualizace může vyžadovat restartování počítače.                                                                                                                                                                                                                                                                                                                                                                           |
| **Software obsahující tuto chybu** | **Microsoft Host Integration Server.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                             |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-057                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyby zabezpečení v aplikaci Microsoft Excel umožňují vzdálené spuštění kódu (956416)**](http://go.microsoft.com/fwlink/?linkid=124653)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší tři chyby zabezpečení aplikace Microsoft Office Excel oznámené soukromými osobami, které by mohly umožnit vzdálené spuštění kódu v případě, že uživatel otevře speciálně vytvořený soubor aplikace Excel. Útočník, který by tyto chyby zabezpečení zneužil, by mohl získat úplnou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Aktualizace nevyžaduje restartování.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Software obsahující tuto chybu** | **Microsoft Office.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

Důležité (6)
------------

 

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-066                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení v pomocném ovladači funkcí společnosti Microsoft by mohla umožnit zvýšení úrovně oprávnění (956803)**](http://go.microsoft.com/fwlink/?linkid=125709)                                                                                                                                                                                                              |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení v pomocném ovladači funkcí společnosti Microsoft oznámenou soukromou osobou. Místní útočník, který by tuto chybu zabezpečení zneužil, by mohl získat úplnou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. |
| **Stupeň maximální závažnosti**    | [Vysoký](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                  |
| **Dopad této chyby zabezpečení**   | Zvýšení úrovně oprávnění                                                                                                                                                                                                                                                                                                                                                                |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                                        |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-061                                                                                                                                                                                                                                                                         |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (954211)**](http://go.microsoft.com/fwlink/?linkid=121738)                                                                                                                                                                                            |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší jednu veřejně známou a dvě soukromou osobou oznámené chyby zabezpečení jádra systému Windows. Místní útočník, který by tyto chyby zabezpečení zneužil, by mohl získat úplnou kontrolu nad postiženým systémem. Uvedené chyby zabezpečení nemohou zneužít vzdálení ani anonymní uživatelé. |
| **Stupeň maximální závažnosti**    | [Vysoký](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                      |
| **Dopad této chyby zabezpečení**   | Zvýšení úrovně oprávnění                                                                                                                                                                                                                                                                                                    |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                            |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                    |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-062                                                                                                                                                                                                                                                                                                                 |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení ve službě Tisk přes Internet systému Windows umožňuje vzdálené spuštění kódu (953155)**](http://go.microsoft.com/fwlink/?linkid=120829)                                                                                                                                                                                                        |
| **Shrnutí**                        | Tato aktualizace řeší soukromě oznámenou chybu zabezpečení služby Tisk přes Internet systému Windows, která může způsobit vzdálené spuštění kódu. Útočník, který by tuto chybu zabezpečení zneužil, by mohl získat úplnou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty. |
| **Stupeň maximální závažnosti**    | [Vysoký](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                              |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                              |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                    |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                            |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-063                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení v technologii SMB umožňuje vzdálené spuštění kódu (957095)**](http://go.microsoft.com/fwlink/?linkid=127994)                                                                                                                                                                                                                                                                                            |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení oznámenou soukromou osobou v protokolu SMB (Server Message Block). Tato chyba zabezpečení by mohla povolit vzdálené spuštění kódu na serveru se sdílenými soubory nebo složkami. Útočník, který by úspěšně zneužil tyto chyby zabezpečení, by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. |
| **Stupeň maximální závažnosti**    | [Vysoký](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                       |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                                                                             |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                     |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-064                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení při manipulaci s popisovačem virtuálních adres umožňuje zvýšení úrovně oprávnění (956841)**](http://go.microsoft.com/fwlink/?linkid=128103)                                                                                                                                                                                                                                                                                                                                |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení oznámenou soukromou osobou v popisovači virtuálních adres. Tato chyba zabezpečení umožňuje zvýšit úroveň oprávnění, pokud uživatel spustí speciálně vytvořenou aplikaci. Oprávněný útočník, který by tuto chybu zabezpečení úspěšně zneužil, by mohl získat zvýšenou úroveň oprávnění v postiženém systému. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými právy správce. |
| **Stupeň maximální závažnosti**    | [Vysoký](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Dopad této chyby zabezpečení**   | Zvýšení úrovně oprávnění                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                                                                                                                                                |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                        |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-065                                                                                                                                                                                                                                              |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení služby Řízení front zpráv umožňuje vzdálené spuštění kódu (951071)**](http://go.microsoft.com/fwlink/?linkid=128102)                                                                                                                                                        |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení ve službě Řízení front zpráv (MSMQ) v systémech Microsoft Windows 2000, kterou oznámila soukromá osoba. Tato chyba zabezpečení by mohla umožnit vzdálené spuštění kódu v systémech Microsoft Windows 2000, které mají povolenou službu MSMQ. |
| **Stupeň maximální závažnosti**    | [Vysoký](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                           |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                           |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                 |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                         |

Mírný (1)
---------

 

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-056                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení v systému Microsoft Office může umožnit přístup k informacím (957699)**](http://go.microsoft.com/fwlink/?linkid=128145)                                                                                                                                                                                                                                                                                                                                                            |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení v sadě Microsoft Office, kterou oznámila soukromá osoba. Uvedená chyba zabezpečení umožňuje zpřístupnění informací, pokud uživatel klikne na speciálně vytvořenou adresu URL aplikace CDO. Útočník, který tuto chybu zabezpečení úspěšně zneužije, může ovlivnit skript na straně klienta v prohlížeči uživatele, který by mohl padělat obsah, zpřístupnit informace nebo provést takovou akci, kterou by uživatel mohl provést na postiženém webu. |
| **Stupeň maximální závažnosti**    | [Mírný](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Dopad této chyby zabezpečení**   | Přístup k informacím                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Aktualizace nevyžaduje restartování.                                                                                                                                                                                                                                                                                                                                           |
| **Software obsahující tuto chybu** | **Microsoft Office.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                 |

Index zneužitelnosti
--------------------

 
**Jak pracovat s touto tabulkou**

V této tabulce zjistíte, jaká je pravděpodobnost vydání funkčního zneužitelného kódu pro všechny aktualizace zabezpečení, které bude třeba nainstalovat. Všechna níže uvedená hodnocení zvažte na základě vaší specifické konfigurace a podle závěrů hodnocení nastavte priority pro zavádění jednotlivých aktualizací. Další informace o významu těchto hodnocení a způsobu jejich stanovení najdete v materiálu [Microsoft Exploit Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

| ID bulletinu                                              | Název bulletinu                                                                                                                                                        | ID CVE        | Hodnocení indexu zneužitelnosti                                                                                            | Hlavní poznámky                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [MS08-056](http://go.microsoft.com/fwlink/?linkid=128145) | [Chyba zabezpečení v systému Microsoft Office může umožnit přístup k informacím (957699)](http://go.microsoft.com/fwlink/?linkid=128145)                               | CVE-2008-4020 | [2 - Nekonsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)             | Funkční zneužitelný kód může být vytvořen. Stupeň závažnosti je však omezen, protože chyba zabezpečení umožňuje vložit falešný obsah do dialogového okna jen ve specifických případech webových aplikací. V důsledku toho chybu využije pravděpodobně jen malý počet útočníků.                                                                                                                                                                                                                                       |
| [MS08-057](http://go.microsoft.com/fwlink/?linkid=124653) | [Chyby zabezpečení v aplikaci Microsoft Excel umožňují vzdálené spuštění kódu (956416)](http://go.microsoft.com/fwlink/?linkid=124653)                                 | CVE-2008-4019 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-057](http://go.microsoft.com/fwlink/?linkid=124653) | [Chyby zabezpečení v aplikaci Microsoft Excel umožňují vzdálené spuštění kódu (956416)](http://go.microsoft.com/fwlink/?linkid=124653)                                 | CVE-2008-3471 | [2 - Nekonsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-057](http://go.microsoft.com/fwlink/?linkid=124653) | [Chyby zabezpečení v aplikaci Microsoft Excel umožňují vzdálené spuštění kódu (956416)](http://go.microsoft.com/fwlink/?linkid=124653)                                 | CVE-2008-3477 | [2 - Nekonsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-058](http://go.microsoft.com/fwlink/?linkid=128060) | [Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (956390)](http://go.microsoft.com/fwlink/?linkid=128060)                                           | CVE-2008-2947 | (Zveřejněno spolu s bulletinem)                                                                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-058](http://go.microsoft.com/fwlink/?linkid=128060) | [Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (956390)](http://go.microsoft.com/fwlink/?linkid=128060)                                           | CVE-2008-3472 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-058](http://go.microsoft.com/fwlink/?linkid=128060) | [Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (956390)](http://go.microsoft.com/fwlink/?linkid=128060)                                           | CVE-2008-3473 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-058](http://go.microsoft.com/fwlink/?linkid=128060) | [Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (956390)](http://go.microsoft.com/fwlink/?linkid=128060)                                           | CVE-2008-3475 | [2 - Nekonsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-058](http://go.microsoft.com/fwlink/?linkid=128060) | [Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (956390)](http://go.microsoft.com/fwlink/?linkid=128060)                                           | CVE-2008-3474 | [3 - Vytvoření funkčního zneužitelného kódu není pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-058](http://go.microsoft.com/fwlink/?linkid=128060) | [Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (956390)](http://go.microsoft.com/fwlink/?linkid=128060)                                           | CVE-2008-3476 | [3 - Vytvoření funkčního zneužitelného kódu není pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-059](http://go.microsoft.com/fwlink/?linkid=125712) | [Chyba zabezpečení ve službě RPC serveru Host Integration Server umožňuje vzdálené spuštění kódu (956695)](http://go.microsoft.com/fwlink/?linkid=125712)              | CVE-2008-3466 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               | Přestože si aplikaci Host Integration Server nainstalují pravděpodobně jen někteří zákazníci v rozlehlých sítích, je vytvoření funkčního zneužitelného kódu pravděpodobné.                                                                                                                                                                                                                                                                                                                                           |
| [MS08-060](http://go.microsoft.com/fwlink/?linkid=128125) | [Chyba zabezpečení služby Active Directory umožňuje vzdálené spuštění kódu (957280)](http://go.microsoft.com/fwlink/?linkid=128125)                                    | CVE-2008-4023 | [2 - Nekonsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)             | Je pravděpodobné, že kód obsahující chybu bude spuštěn, aby útočník dosáhnul odepření služby. Vytvoření funkčního zneužitelného kódu, který by využil vzdálené spuštění kódu, je však velmi obtížné, protože útočník není schopen určit potřebnou adresu pro zápis.                                                                                                                                                                                                                                                  |
| [MS08-061](http://go.microsoft.com/fwlink/?linkid=121738) | [Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (954211)](http://go.microsoft.com/fwlink/?linkid=121738)                                           | CVE-2008-2250 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-061](http://go.microsoft.com/fwlink/?linkid=121738) | [Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (954211)](http://go.microsoft.com/fwlink/?linkid=121738)                                           | CVE-2008-2252 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               | Funkční zneužití bude pravděpodobně vytvořeno pro víceprocesorové systémy.                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [MS08-061](http://go.microsoft.com/fwlink/?linkid=121738) | [Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (954211)](http://go.microsoft.com/fwlink/?linkid=121738)                                           | CVE-2008-2251 | [3 - Vytvoření funkčního zneužitelného kódu není pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx) | Je pravděpodobné, že kód obsahující chybu může být spuštěn, ale úspěšně fungující zneužitelný kód lze vytvořit jen velmi obtížně.                                                                                                                                                                                                                                                                                                                                                                                    |
| [MS08-062](http://go.microsoft.com/fwlink/?linkid=120829) | [Chyba zabezpečení ve službě Tisk přes Internet systému Windows umožňuje vzdálené spuštění kódu (953155)](http://go.microsoft.com/fwlink/?linkid=120829)               | CVE-2008-1446 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               | Konsistentní zneužití kódu bylo objeveno jen v úzce omezených a přesně cílených útocích. Služba IPP (Internet Printing Protocol) je sice implicitně zapnuta, ale přístup k ní prostřednictvím serveru IIS implicitně vyžaduje ověření totožnosti uživatele na všech platformách.                                                                                                                                                                                                                                     |
| [MS08-063](http://go.microsoft.com/fwlink/?linkid=127994) | [Chyba zabezpečení v technologii SMB umožňuje vzdálené spuštění kódu (957095)](http://go.microsoft.com/fwlink/?linkid=127994)                                          | CVE-2008-4038 | [2 - Nekonsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-064](http://go.microsoft.com/fwlink/?linkid=128103) | [Chyba zabezpečení při manipulaci s popisovačem virtuálních adres umožňuje zvýšení úrovně oprávnění (956841)](http://go.microsoft.com/fwlink/?linkid=128103)           | CVE-2008-4036 | [2 - Nekonsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-065](http://go.microsoft.com/fwlink/?linkid=128102) | [Chyba zabezpečení služby Řízení front zpráv umožňuje vzdálené spuštění kódu (951071)](http://go.microsoft.com/fwlink/?linkid=128102)                                  | CVE-2008-3479 | [3 - Vytvoření funkčního zneužitelného kódu není pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx) | Přístup k informacím je sice možný, ale získání užitečných údajů z paměti není možné vždy. Lze vyvolat poškození dat v paměti, vzdálené spuštění kódu je však velmi obtížné.                                                                                                                                                                                                                                                                                                                                         |
| [MS08-066](http://go.microsoft.com/fwlink/?linkid=125709) | [Chyba zabezpečení v pomocném ovladači funkcí společnosti Microsoft by mohla umožnit zvýšení úrovně oprávnění (956803)](http://go.microsoft.com/fwlink/?linkid=125709) | CVE-2008-3464 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [MS08-067](http://go.microsoft.com/fwlink/?linkid=130719) | [Chyba zabezpečení služby Server umožňuje vzdálené spuštění kódu (958644)](http://go.microsoft.com/fwlink/?linkid=130719)                                              | CVE-2008-4250 | [1 - Konsistentní zneužití kódu je pravděpodobné](http://technet.microsoft.com/en-us/security/cc998259.aspx)               | Konsistentní zneužití kódu bylo zjištěno jen v omezeném počtu cílených útoků zaměřených na systém Windows XP. Přestože je tato služba ve výchozím nastavení povolena ve všech ohrožených platformách, je zneužití nejpravděpodobnější v systémech Microsoft Windows 2000, Windows XP a Windows Server 2003. V systémech Windows Vista, Windows Server 2008 a Windows 7 Beta je vyžadováno ověření. I v případě ověření je zneužití ztíženo díky vylepšením v podobě technologie ASLR a zabránění spuštění dat (DEP). |

Software obsahující tuto chybu a umístění aktualizací ke stažení
----------------------------------------------------------------

 
**Jak pracovat s touto tabulkou**

V této tabulce zjistíte, které aktualizace zabezpečení bude třeba nainstalovat. Přečtěte si seznam všech programů a komponent a zjistěte, zda jsou u nich vyžadovány aktualizace zabezpečení. Pokud se program nebo komponenta v seznamu nachází, je v něm zároveň uveden odkaz na dostupnou aktualizaci softwaru a také stupeň závažnosti aktualizace softwaru.

**Poznámka:** Jedna chyba zabezpečení může vyžadovat instalaci více aktualizací. Přečtěte si celý sloupec u každého identifikátoru bulletinu. Zjistíte v něm, které aktualizace nainstalovat v závislosti na programech nebo součástech nainstalovaných ve vašem systému.

#### Operační systém Windows a jeho komponenty

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://go.microsoft.com/fwlink/?linkid=130719)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://go.microsoft.com/fwlink/?linkid=128125)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://go.microsoft.com/fwlink/?linkid=128060)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://go.microsoft.com/fwlink/?linkid=125709)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://go.microsoft.com/fwlink/?linkid=121738)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://go.microsoft.com/fwlink/?linkid=120829)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://go.microsoft.com/fwlink/?linkid=127994)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://go.microsoft.com/fwlink/?linkid=128103)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://go.microsoft.com/fwlink/?linkid=128102)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=e22eb3ae-1295-4fe2-9775-6f43c5c2aed3)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Služba Active Directory v systému Microsoft Windows 2000 Server Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=8ed7bb9a-4b26-49d7-8c14-60226d2bc20d)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=257c0478-56dd-42eb-a90e-607d01613db7)  
(Kritický)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=02390258-08e9-4b75-960d-be081b749558)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=3a6165a6-d7e7-4526-9291-290caf0639b4)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=8163d1f6-feb5-4f39-8134-3ed42326b822)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=9ed29c3a-0682-4586-bbc2-a73deaa18e4c)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=899e2728-2433-4ccb-a195-05b5d65e5469)  
(Důležitý)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://go.microsoft.com/fwlink/?linkid=130719)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://go.microsoft.com/fwlink/?linkid=128125)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://go.microsoft.com/fwlink/?linkid=128060)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://go.microsoft.com/fwlink/?linkid=125709)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://go.microsoft.com/fwlink/?linkid=121738)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://go.microsoft.com/fwlink/?linkid=120829)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://go.microsoft.com/fwlink/?linkid=127994)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://go.microsoft.com/fwlink/?linkid=128103)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://go.microsoft.com/fwlink/?linkid=128102)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 a Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d5f9b6e-9265-44b9-a376-2067b73d6a03)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a7f0f47b-b1ee-4516-9fbf-bf8e579963d0)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4e73de2b-05e6-4901-9bac-46d8f469e635)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b16d9dac-c430-4dd8-a1e5-9a614801f1d9)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7718bf14-c26c-43f3-be67-4c79ab5b2607)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e7ef571f-c9e8-4e14-95a3-3eeaec55b784)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2f7e5981-6eef-4f08-86c0-c6a7607ea5d0)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=25997b73-a640-49c1-b19e-768a18bbe22c)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c16a372-7bf8-4571-b982-dac6b2992b25)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=234c05fb-988b-4e02-aab6-bb23e447df3d)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ccf7a3e3-ec30-4b95-9a86-00032301513c)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b607efc-c6fb-4079-8478-e4f3262386d3)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b06d3a02-b6e4-4d40-913a-3759a31f20f3)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3ae4b913-bff0-4974-b198-828ca10d2a87)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4e1675eb-6b06-48e9-9765-23a2c7737bdc)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=50fae854-0bde-46f8-9444-b9e0d9bfecad)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://go.microsoft.com/fwlink/?linkid=130719)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://go.microsoft.com/fwlink/?linkid=128125)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://go.microsoft.com/fwlink/?linkid=128060)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://go.microsoft.com/fwlink/?linkid=125709)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://go.microsoft.com/fwlink/?linkid=121738)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://go.microsoft.com/fwlink/?linkid=120829)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://go.microsoft.com/fwlink/?linkid=127994)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://go.microsoft.com/fwlink/?linkid=128103)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://go.microsoft.com/fwlink/?linkid=128102)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f26d395d-2459-4e40-8c92-3de1c52c390d)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=ae8d22d5-20aa-471d-a423-f54c9d75febe)  
(Mírný)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=feaf2adf-7892-4dbf-a147-db4d5dbe52f3)  
(Nízký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ee88ff2d-1b12-4f4c-a081-9f27a6fba074)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e696762-d652-4a8f-ab8f-622f9746c320)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=437a9b68-6a0c-48c8-9348-0d6fda48aa21)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dbbebb3f-f1c7-402c-bd16-6f88da0d042c)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e8ef3d5f-dd8e-4945-92cd-9d3e30b16667)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c04d2afb-f9d0-4e42-9e1f-4b944a2de400)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=07fc88c4-2571-4a4d-b573-ae576798ab4c)  
(Mírný)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=319dba34-07ca-47f9-a1e9-20df2df7966b)  
(Nízký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab4d94d3-458c-4946-ab7f-03a279629d25)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=57ca28ea-e5e1-4191-a3d6-84aa90a3d668)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d3df6508-a568-449d-ac97-fbf3f97b98ef)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=989ac6f1-515c-467d-a200-2aabe66d9319)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c2e754f9-086a-494c-bc19-5feed7df8b65)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ab590756-f11f-43c9-9dcc-a85a43077acf)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b68937af-f04a-4d1e-9d7f-ec92af5194de)  
(Mírný)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=47381d91-4a14-4a09-96b3-3345155df52d)  
(Nízký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=63234f85-6e5d-4ef6-b7cf-d1d2c78a5517)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1e6c3f81-85bb-48e6-a5af-635a7e540c93)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=748f54f1-40b9-407c-9819-909061b53743)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=91589cfb-15ba-4dd2-9e3b-107899fbcba6)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5a3832ec-3f8f-42c1-a603-b1330d527547)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://go.microsoft.com/fwlink/?linkid=130719)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://go.microsoft.com/fwlink/?linkid=128125)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://go.microsoft.com/fwlink/?linkid=128060)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://go.microsoft.com/fwlink/?linkid=125709)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://go.microsoft.com/fwlink/?linkid=121738)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://go.microsoft.com/fwlink/?linkid=120829)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://go.microsoft.com/fwlink/?linkid=127994)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://go.microsoft.com/fwlink/?linkid=128103)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://go.microsoft.com/fwlink/?linkid=128102)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista a Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=18fdff67-c723-42bd-ac5c-cac7d8713b21)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4756e04b-6e1c-4d78-a3c0-17f6b4b97975)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3483b400-cedc-441f-ba8e-594e3df89190)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9b5995df-a3b8-4e81-b118-9bb057e19884)  
(Stupeň závažnosti není určen)
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72dd6015-25d1-45f4-a769-88ac43074b44)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b4212db5-093e-497d-b999-2e3780f9f7c2)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a976999d-264f-4e6a-9bd6-3ad9d214a4bd)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=bd19c72b-4f83-47ab-93be-d2c286e732c4)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=905ab030-14a5-4a3d-aa11-e8f957f6a1ea)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4a0fcf4b-eb8e-456a-b934-400ae18248ee)  
(Stupeň závažnosti není určen)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f793af16-5464-4db1-a42b-1c5f17c538ed)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c20808cb-c30a-4b53-91e5-810eb6b4b2e3)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://go.microsoft.com/fwlink/?linkid=130719)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://go.microsoft.com/fwlink/?linkid=128125)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://go.microsoft.com/fwlink/?linkid=128060)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://go.microsoft.com/fwlink/?linkid=125709)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://go.microsoft.com/fwlink/?linkid=121738)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://go.microsoft.com/fwlink/?linkid=120829)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://go.microsoft.com/fwlink/?linkid=127994)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://go.microsoft.com/fwlink/?linkid=128103)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://go.microsoft.com/fwlink/?linkid=128102)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro 32bitové systémy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=25c17b07-1efe-43d7-9b01-3dfdf1ce0bd7)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ec73f416-2204-42d6-8932-c96578ac819f)\*\*  
(Nízký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=8b97114a-71aa-47a2-b9e7-f4e158c18c80)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=cf6744e6-b54c-40f6-a78d-7ba9453133c0)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=ec9eeb82-0497-4c55-94bb-9a47cb3521b4)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=7b12018e-0cc1-4136-a68c-be4e1633c8df)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=baacd1c2-9764-4fea-bd4d-c49791974fef)\*\*  
(Nízký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=6e641db2-90c8-458f-9795-3e46b70a5203)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=223236e8-7b19-4b47-8a90-bfc35eb9318a)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=0bc178b8-f8ae-4f41-8f88-fb6a75be1bca)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2bcf89ef-6446-406c-9c53-222e0f0baf7a)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=250a45dd-7eae-4440-bd10-02a703940976)  
(Nízký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b6546e1c-bf7b-4354-8574-6c16fa707de0)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=31783e88-76e2-4bc6-b4ae-308443c6d223)  
(Stupeň závažnosti není určen)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=077b697c-04a0-45bd-b08c-331d5c30cb47)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=0af72663-4945-4916-8c55-090ba4d82793)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="10">
Windows 7 Beta
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-067**](http://go.microsoft.com/fwlink/?linkid=130719)
</td>
<td style="border:1px solid black;">
[**MS08-060**](http://go.microsoft.com/fwlink/?linkid=128125)
</td>
<td style="border:1px solid black;">
[**MS08-058**](http://go.microsoft.com/fwlink/?linkid=128060)
</td>
<td style="border:1px solid black;">
[**MS08-066**](http://go.microsoft.com/fwlink/?linkid=125709)
</td>
<td style="border:1px solid black;">
[**MS08-061**](http://go.microsoft.com/fwlink/?linkid=121738)
</td>
<td style="border:1px solid black;">
[**MS08-062**](http://go.microsoft.com/fwlink/?linkid=120829)
</td>
<td style="border:1px solid black;">
[**MS08-063**](http://go.microsoft.com/fwlink/?linkid=127994)
</td>
<td style="border:1px solid black;">
[**MS08-064**](http://go.microsoft.com/fwlink/?linkid=128103)
</td>
<td style="border:1px solid black;">
[**MS08-065**](http://go.microsoft.com/fwlink/?linkid=128102)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 Beta pro 32bitové systémy
</td>
<td style="border:1px solid black;">
[Windows 7 Beta pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=e877d9c1-3e7c-4551-a899-c3fcc5175bb6)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 Beta pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows 7 Beta x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=0fa96b25-90e3-46ab-bcd5-051f4b2b881b)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 Beta pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows 7 Beta pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=66646156-f3e6-48d7-be22-de1772dd1884)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
</table>
<p></p>
 
**\*Instalace Server Core operačního systému Windows Server 2008 obsahující tuto chybu.** Tato aktualizace se týká všech podporovaných vydání systému Windows Server 2008 se stejným stupněm závažnosti, ať už byl systém Windows Server 2008 instalován pomocí možnosti instalace Server Core či nikoli. Více informací o této možnosti instalace naleznete v části [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008. Další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalace Server Core operačního systému Windows Server 2008 neobsahující tuto chybu.** Chyby zabezpečení, které tyto aktualizace řeší, nemají vliv na podporované edice systému Windows Server 2008, jestliže byl systém Windows Server 2008 instalován s využitím možnosti instalace Server Core. Více informací o této možnosti instalace naleznete v části [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008. Další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Sady Microsoft Office a jejich software

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Sady Microsoft Office, systémy a komponenty
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://go.microsoft.com/fwlink/?linkid=124653)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://go.microsoft.com/fwlink/?linkid=128145)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1b2740e0-ecdd-48ca-84e0-eb187c31eb16)  
(KB955461)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=27cedef1-c47c-472c-a343-cd9b4ebc2bba)  
(KB955464)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1aee2d5-bfa0-40e3-91b6-98bf65524e8c)  
(KB956464)  
(Mírný)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 a Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Excel 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
(Důležitý)  
[Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368)  
(KB955466)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Systém Microsoft Office 2007 a systém Microsoft Office 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Excel 2007](http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
(Důležitý)  
[Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f)  
(KB955470)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://go.microsoft.com/fwlink/?linkid=124653)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://go.microsoft.com/fwlink/?linkid=128145)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ba4fa21a-7e01-4ef8-9b9f-9d51d00ef094)  
(KB958312)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=e70c5ae0-2858-46de-81f8-dcd1786656b7)  
(KB958267)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Otevření nástroje XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Otevření nástroje XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=2a8d9a3b-b8a4-43b6-82a6-a2e7d16ae11d)  
(KB958304)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="3">
Jiný software sady Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-057**](http://go.microsoft.com/fwlink/?linkid=124653)
</td>
<td style="border:1px solid black;">
[**MS08-056**](http://go.microsoft.com/fwlink/?linkid=128145)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
(Důležitý)  
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b)  
(KB955468)  
(Důležitý)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=83c88444-75b8-44d1-b280-3671394ade45)  
(KB955935)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007
</td>
<td style="border:1px solid black;">
[Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
(Důležitý)  
[Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9)  
(KB955936)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
(Důležitý)  
[Microsoft Office SharePoint Server 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535)\*  
(KB955937)  
(Důležitý)  
[Microsoft Office SharePoint Server 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
(Důležitý)  
[Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f)\*  
(KB955937)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
</table>
<p></p>
 
\*Tato aktualizace se týká serverů, které mají naistalovánu službu Excel Services, jak je tomu například u aplikací Microsoft Office SharePoint Server 2007 Enterprise a Microsoft Office SharePoint Server 2007 For Internet Sites ve výchozí konfiguraci. Aplikace Microsoft Office SharePoint Server 2007 Standard neobsahuje službu Excel Services.

#### Microsoft Server Software

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th style="border:1px solid black;" colspan="2">
Microsoft Host Integration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-059**](http://go.microsoft.com/fwlink/?linkid=125712)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Stupeň maximální závažnosti bulletinu**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2000 Service Pack 2 (server)](http://www.microsoft.com/downloads/details.aspx?familyid=11cca58b-59a4-4e93-9eb1-19b07c290a10)  
(Kritický)  
[Klient Microsoft Host Integration Server 2000 Administrator](http://www.microsoft.com/downloads/details.aspx?familyid=41b49291-1231-4e23-aef7-818207453d56)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 (server)](http://www.microsoft.com/downloads/details.aspx?familyid=9ca255ed-9334-4848-af94-49ef3078cdc0)  
(Kritický)  
[Microsoft Host Integration Server 2004 Service Pack 1 (server)](http://www.microsoft.com/downloads/details.aspx?familyid=eca756a1-ca56-4481-b23c-53c159a4e08c)  
(Kritický)  
[Microsoft Host Integration Server 2004 (klient)](http://www.microsoft.com/downloads/details.aspx?familyid=92cb54e7-f4ff-40a4-99cb-6257c4d8d4cd)  
(Kritický)  
[Microsoft Host Integration Server 2004 Service Pack 1 (klient)](http://www.microsoft.com/downloads/details.aspx?familyid=d776515c-09aa-4a04-876d-606bfc26a006)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2006 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=1ae79da3-ec17-4d4b-8011-d777a237ac93)  
(Kritický)  
[Microsoft Host Integration Server 2006 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=05da4540-4976-458a-a612-7385d78695a2)  
(Kritický)
</td>
</tr>
</table>
<p></p>
 

Nástroje a doporučené postupy zjišťování a nasazení
---------------------------------------------------

 
**Centrum zabezpečení**

Umožňuje správu aktualizací softwaru a zabezpečení, které je třeba nainstalovat na servery, stolní počítače a přenosné počítače v organizaci. Další informace naleznete na webu [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Další informace o zabezpečení produktů společnosti Microsoft nabízí web [Centrum zabezpečení TechNet](http://go.microsoft.com/fwlink/?linkid=21171). Tyto informace lze také získat kliknutím na nabídku „Nejnovější aktualizace zabezpečení“ na webu [Zabezpečení doma](http://go.microsoft.com/fwlink/?linkid=85102).

Aktualizace zabezpečení jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) a [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Aktualizace zabezpečení jsou také k dispozici na webu [služby Stažení softwaru](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.

Aktualizace zabezpečení lze stáhnout z katalogu služby [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). Služba Microsoft Update Catalog poskytuje katalog s možností vyhledávání obsahu dostupného prostřednictvím služeb Windows Update a Microsoft Update, včetně aktualizací zabezpečení, ovladačů a aktualizací Service Pack. Vyhledáváním pomocí čísla bulletinu zabezpečení (například MS07-036) můžete přidat všechny dostupné aktualizace do košíku (včetně různých jazykových verzí aktualizace) a stáhnout je do vybrané složky. Další informace o službě Microsoft Update Catalog najdete v části [Nejčastější dotazy týkající se služby Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Doporučené postupy zjišťování a nasazení**

Společnost Microsoft poskytla doporučené postupy zjišťování a instalace aktualizací zabezpečení vydaných tento měsíc. Tyto doporučené postupy by měly pomoci také odborníkům v oblasti IT při používání různých nástrojů při instalaci aktualizace zabezpečení, např. Windows Update, Microsoft Update, Office Update, nástroj MBSA (Microsoft Baseline Security Analyzer), nástroj pro rozpoznávání sady Office, Microsoft Systems Management Server (SMS) a nástroj Extended Security Update Inventory Tool (ESUIT). Další informace získáte v [článku 910723 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/910723).

**Nástroj Microsoft Baseline Security Analyzer**

Pomocí nástroje Microsoft Baseline Security Analyzer (MBSA) mohou správci prohledávat místní i vzdálené systémy a zjistit tak, jestli v nich nechybí některé aktualizace zabezpečení nebo jestli v nastavení zabezpečení systému nedošlo k některým běžným chybám. Další informace o nástroji MBSA získáte na webu [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Služba Windows Server Update Services**

Pomocí služby Windows Server Update Services (WSUS) mohou správci systémů rychle a spolehlivě instalovat nejnovější důležité aktualizace zabezpečení pro systémy Windows 2000 a novější, sadu Office XP a novější, Exchange Server 2003 a SQL Server 2000 do systémů Windows 2000 a novějších.

Další informace o způsobu instalace této aktualizace zabezpečení pomocí služby Windows Server Update Services získáte na webu služby [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) představuje v rozlehlých sítích řešení pro správu aktualizací s rozsáhlými možnostmi konfigurace. Umožňuje správcům identifikovat počítače se systémem Windows, které vyžadují aktualizace zabezpečení, a provést řízenou instalaci těchto aktualizací v celé rozlehlé síti s minimálním dopadem na koncové uživatele. K dispozici je nyní nová verze nástroje SMS, System Center Configuration Manager 2007 (viz také webové stránky produktu [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Další informace o tom, jak mohou správci pomocí serveru SMS 2003 nasazovat aktualizace zabezpečení, získáte na webu [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Uživatelé serveru SMS 2.0 mohou při nasazení aktualizací zabezpečení použít také sadu [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340). Další informace o serveru SMS získáte na webu [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Poznámka:** Server SMS využívá nástroj MBSA (Microsoft Baseline Security Analyzer) a nástroj pro rozpoznávání sady Microsoft Office, a poskytuje tak širokou podporu pro zjišťování a instalaci aktualizací uvedených v bulletinech zabezpečení. Tyto nástroje nemusí některé softwarové aktualizace zjistit. V takovém případě mohou správci použít funkce serveru SMS a nasměrovat aktualizace do určitých systémů. Další informace o tomto postupu najdete na webu [Nasazení aktualizací softwaru pomocí funkce Distribuce softwaru serveru SMS](http://go.microsoft.com/fwlink/?linkid=33341). Některé aktualizace zabezpečení vyžadují po restartování počítače oprávnění správce. Správci mohou k instalaci těchto aktualizací použít nástroj Elevated Rights Deployment Tool (k dispozici v sadě [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) a [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Nástroj Update Compatibility Evaluator a sada Application Compatibility Toolkit**

Aktualizace často zapisují do stejných souborů a nastavení registru požadovaných pro spouštění aplikací. To může způsobit nekompatibilitu a zvýšit dobu, po kterou trvá nasazení aktualizací zabezpečení. Testování a ověřování aktualizací systému Windows lze usnadnit pomocí součástí nástroje [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), které jsou dodávány se sadou [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sada Application Compatibility Toolkit (ACT) obsahuje nezbytné nástroje a dokumentaci pro posouzení a zmírnění problémů s kompatibilitou aplikací před nasazením systému Microsoft Windows Vista, služby Windows Update, aktualizací zabezpečení společnosti Microsoft nebo nové verze aplikace Windows Internet Explorer ve vašem prostředí.

### Další informace

#### Nástroj pro odstranění škodlivého softwaru systému Microsoft Windows

Společnost Microsoft vydává aktualizovanou verzi Nástroje pro odstranění škodlivého softwaru systému Microsoft Windows na webu Windows Update, Microsoft Update, ve službě Windows Server Update Services a na webu služby Stažení softwaru.

#### Důležité aktualizace nesouvisející se zabezpečením na webu Microsoft Update (MU), Windows Update (WU) a ve službě Windows Server Update Services (WSUS)

Informace o aktualizacích nesouvisejících se zabezpečením na webu Windows Update a Microsoft Update naleznete na webové stránce:

-   [Článek 894199 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Popis služeb Software Update Services a Windows Server Update Services se mění v obsahu pro rok 2008. Zahrnuje celý obsah systému Windows.
-   [Nové, revidované a vydané aktualizace pro jiné produkty společnosti Microsoft, než je systém Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Strategie zabezpečení a komunita

**Strategie instalace aktualizací**

Web [Doporučené postupy zabezpečení pro správu aktualizací (Security Guidance for Update Management)](http://go.microsoft.com/fwlink/?linkid=21168) obsahuje další informace o instalaci aktualizací zabezpečení podle doporučení společnosti Microsoft.

**Získání dalších aktualizací zabezpečení**

Aktualizace odstraňující další problémy se zabezpečením získáte v následujících umístěních:

-   Aktualizace zabezpečení jsou k dispozici na webu služby [Stažení softwaru (Microsoft Download Center)](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.
-   Aktualizace pro klientské platformy jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizace zabezpečení nabízené tento měsíc na webu Windows Update jsou k dispozici na webu služby Stažení softwaru v souborech obrazu ISO disku CD s vydanými aktualizacemi zabezpečení a kritickými aktualizacemi. Další informace získáte v [článku 913086 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Komunita odborníků v oblasti zabezpečení**

Můžete se zde naučit, jak zlepšit zabezpečení a jak optimalizovat infrastrukturu IT. Také můžete s dalšími členy komunity IT Pro diskutovat o bezpečnostních tématech na webu [Komunita odborníků v oblasti zabezpečení (IT Pro Security Community)](http://go.microsoft.com/fwlink/?linkid=21164).

#### Poděkování

Společnost Microsoft tímto [děkuje](http://go.microsoft.com/fwlink/?linkid=21127) za spolupráci při ochraně zákazníků:

-   [Společnosti NetAgent Co., Ltd.](http://www.netagent.co.jp/) za oznámení chyby popsané v bulletinu MS08-056.
-   Joshuovi J. Drakeovi ze společnosti [iDefense](http://labs.idefense.com/) za oznámení chyby popsané v bulletinu MS08-057.
-   Wushimu, spolupracujícímu se společností [TippingPoint](http://www.tippingpoint.com/) a organizací [Zero Day Initiative](http://www.zerodayinitiative.com/), za oznámení chyby popsané v bulletinu MS08-057.
-   Lionelu d'Hauenensovi ze společnosti [Labo Skopia](http://www.laboskopia.com/) spolupracující s iniciativou [iDefense VCP](http://labs.idefense.com/) za oznámení chyby popsané v bulletinu MS08-057.
-   Davidu Bloomovi za oznámení chyby popsané v bulletinu MS08-058.
-   Gregorymu Rubinovi za oznámení chyby popsané v bulletinu MS08-058.
-   [Ivanu Fratricovi](http://ifsec.blogspot.com/), spolupracujícímu se společností [TippingPoint](http://www.tippingpoint.com/) a organizací [Zero Day Initiative](http://www.zerodayinitiative.com/), za oznámení chyby popsané v bulletinu MS08-058.
-   Thierrymu Zollerovi ze společnosti [n.runs](http://www.nruns.com/) za oznámení chyby popsané v bulletinu MS08-058.
-   Lee Dagonovi ze společnosti [Composica](http://www.composica.com/) za oznámení chyby popsané v bulletinu MS08-058.
-   Stephenu Fewerovi ze společnosti [Harmony Security](http://www.harmonysecurity.com/), splupracujícímu se společností [iDefense VCP](http://labs.idefense.com/), za oznámení chyby popsané v bulletinu MS08-059.
-   Paulu Miseikovi ze společnosti [nCircle](http://www.ncircle.com/) za oznámení chyby popsané v bulletinu MS08-060.
-   Paulu Catonovi ze společnosti [iShadow](http://www.ishadow.com/) za oznámení chyby popsané v bulletinu MS08-061.
-   Thomasi Garnierovi ze společnosti [SkyRecon](http://www.skyrecon.com/) za oznámení chyby popsané v bulletinu MS08-061.
-   Společnosti [CERT/CC](http://www.cert.org/) za oznámení chyby popsané v bulletinu MS08-062.
-   Joshua Morinovi ze společnosti [Codenomicon](http://www.codenomicon.com/) za oznámení chyby popsané v bulletinu MS08-063.
-   Codymu Pierceovi a Aaronu Portnoyovi ze společnosti [TippingPoint DVLabs](http://dvlabs.tippingpoint.com) za oznámení chyby popsané v bulletinu MS08-065.
-   Fabienu Le Mentecovi ze společnosti [SkyRecon](http://www.skyrecon.com/) za oznámení chyby popsané v bulletinu MS08-066.

#### Technická podpora

-   Uvedený software byl testován za účelem zjištění, kterých verzí se chyba týká. U dalších verzí skončila časově omezená podpora. Pokud chcete zjistit dobu, po kterou je pro určitou verzi softwaru poskytována podpora, navštivte web [Zásady poskytování technické podpory pro produkty společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Zákazníci mohou získat technickou podporu na webu [služby technické podpory společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21131). Hovory související s aktualizacemi zabezpečení jsou bezplatné.
-   Mezinárodní zákazníci získají podporu u místních zastoupení společnosti Microsoft. Technická podpora související s aktualizacemi zabezpečení je bezplatná. Další informace o možnostech kontaktování společnosti Microsoft v případě potřeby technické podpory získáte na [webu mezinárodní technické podpory](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zřeknutí se záruky

Informace ve znalostní bázi Microsoft Knowledge Base jsou poskytovány tak, jak jsou, bez jakékoli záruky. Společnost Microsoft neposkytuje žádné záruky, výslovně uvedené či mlčky předpokládané, včetně záruk obchodovatelnosti a vhodnosti pro určitý účel. Společnost Microsoft ani její dodavatelé nenesou v žádném případě zodpovědnost za žádné škody, včetně přímých, nepřímých, náhodných či následných škod, ztráty zisku či zvláštních škod, a to ani v případě, že byli na možnost takových škod upozorněni. V některých zemích a právních řádech není dovoleno vyloučit nebo omezit odpovědnost, proto se výše uvedené omezení na vás nemusí vztahovat.

#### Revize

-   V1.0 (14. října 2008): Souhrnný bulletin byl publikován.
-   V2.0 (15. října 2008): Byl odebrán stupeň závažnosti pro systém Windows Server 2008 pro systémy s procesorem Itanium (MS08-062).
-   V2.1 (16. října 2008): Shrnutí pro bulletin zabezpečení společnosti Microsoft MS08-062 bylo aktualizováno.
-   V3.0 (23. října 2008): Doplňující bulletin zabezpečení společnosti Microsoft MS08-067: Chyba zabezpečení služby Server umožňuje vzdálené spuštění kódu (958644)

*Built at 2014-04-18T01:50:00Z-07:00*
