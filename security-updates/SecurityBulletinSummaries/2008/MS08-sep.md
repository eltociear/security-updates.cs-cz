---
TOCTitle: 'MS08-SEP'
Title: 'Souhrnný bulletin zabezpečení společnosti Microsoft, září 2008'
ms:assetid: 'ms08-sep'
ms:contentKeyID: 61223981
ms:mtpsurl: 'https://technet.microsoft.com/cs-CZ/library/ms08-sep(v=Security.10)'
---

 

Souhrnný bulletin zabezpečení společnosti Microsoft, září 2008
==============================================================

Publikováno: 9. září 2008 | Aktualizováno: 9. prosince 2008

**Verze:** 3.0

Tento souhrnný bulletin uvádí bulletiny zabezpečení vydané v září 2008.

Spolu s vydáním bulletinů pro září 2008 nahrazuje tento souhrnný bulletin předběžné oznámení o bulletinech vydané 4. září 2008. Další informace o službě předběžného oznámení o bulletinech naleznete v části [Předběžné oznámení o bulletinech zabezpečení společnosti Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Informace o tom, jak dostávat automatická oznámení o vydání nových bulletinů zabezpečení společnosti Microsoft, naleznete na webu [Zasílání technických oznámení o zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

Pro zodpovězení zákaznických dotazů týkajících se těchto bulletinů uspořádá společnost Microsoft webové vysílání 10. září 2008 v 11:00 časového pásma Tichomoří (USA a Kanada). [Registrovat se pro webové vysílání týkající se zářijových bulletinů zabezpečení](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374633&eventcategory=4&culture=en-us&countrycode=us). Po tomto datu je webové vysílání dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://technet.microsoft.com/security/bulletin/summary).

Společnost Microsoft se snaží zákazníkům usnadnit upřednostnění měsíčně vydávaných aktualizací zabezpečení před jakýmikoli důležitými aktualizacemi nesouvisejícími se zabezpečením, které jsou vydány ve stejný den jako měsíčně vydávané aktualizace zabezpečení. Další informace získáte v části **Další informace**.

### Informace o bulletinech

#### Shrnutí

Bulletiny zabezpečení podle závažnosti:

Kritický (4)
------------

 

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-054                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení programu Windows Media Player umožňuje vzdálené spuštění kódu (954154)**](http://go.microsoft.com/fwlink/?linkid=121739)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Shrnutí**                        | Tato aktualizace řeší chybu zabezpečení programu Windows Media Player oznámenou soukromou osobou, která umožňuje vzdálené spuštění kódu v případě vysílání speciálně vytvořeného zvukového souboru ze serveru Windows Media. Pokud by byl uživatel přihlášen s uživatelskými právy správce, mohl by útočník, který by tuto chybu zabezpečení zneužil, získat úplnou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Aktualizace nevyžaduje restartování.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-052                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (954593)**](http://go.microsoft.com/fwlink/?linkid=125468)                                                                                                                                                                                                                                                                                                                                                                     |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší několik chyb zabezpečení v rozhraní GDI+ systému Microsoft Windows oznámených soukromými osobami. Tato chyba zabezpečení může umožnit vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený soubor s obrázkem nebo přejde na web, který obsahuje speciálně vytvořený obsah. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Tato aktualizace vyžaduje restartování.                                                                                                                                                                                                                                                                                                                                    |
| **Software obsahující tuto chybu** | **Microsoft Windows, Internet Explorer, .NET Framework, Office, SQL Server, Visual Studio.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                      |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-053                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení v programu Windows Media Encoder 9 umožňuje vzdálené spuštění kódu (954156)**](http://go.microsoft.com/fwlink/?linkid=123091)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení programu Windows Media Encoder 9 Series, která byla oznámena soukromými osobami. Chyba zabezpečení umožňuje vzdálené spuštění kódu, pokud uživatel zobrazí speciálně vytvořenou webovou stránku. Pokud by byl uživatel přihlášen s uživatelskými právy správce, mohl by útočník, který by tuto chybu zabezpečení zneužil, získat úplnou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Aktualizace může vyžadovat restartování počítače.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Software obsahující tuto chybu** | **Microsoft Windows.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

| Identifikátor bulletinu            | Bulletin zabezpečení společnosti Microsoft MS08-055                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Název bulletinu**                | [**Chyba zabezpečení v sadě Microsoft Office umožňuje vzdálené spuštění kódu (955047)**](http://go.microsoft.com/fwlink/?linkid=125229)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Shrnutí**                        | Tato aktualizace zabezpečení řeší chybu zabezpečení v sadě Microsoft Office, kterou oznámila soukromá osoba. Uvedená chyba zabezpečení umožňuje vzdálené spuštění kódu, pokud uživatel klikne na speciálně vytvořenou adresu URL aplikace OneNote. Útočník, který by tuto chybu zabezpečení zneužil, by mohl získat úplnou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. |
| **Stupeň maximální závažnosti**    | [Kritický](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Dopad této chyby zabezpečení**   | Vzdálené spuštění kódu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Rozpoznávání**                   | Pomocí nástroje MBSA (Microsoft Baseline Security Analyzer) lze určit, zda počítačový systém potřebuje tuto aktualizaci. Aktualizace převážně nevyžaduje restartování.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Software obsahující tuto chybu** | **Microsoft Office.** Další informace získáte v části Software obsahující tuto chybu a umístění aktualizací ke stažení.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

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
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a860d2d9-653d-4ddb-bbff-323d3ccdb866)  
(KB938464)  
(Kritický)  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c7cbcd19-acc1-4a89-adfa-99b2f431510d)  
(KB947739)  
(Stupeň závažnosti není určen)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6013f866-3ea1-4672-b1bf-e516204c3a7a)  
(KB947742)  
(Stupeň závažnosti není určen)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=7f1cd013-2c4b-4582-9114-cb840a96124a)  
(KB947746)  
(Stupeň závažnosti není určen)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=215b73a3-46ab-44a8-a0fb-6d37bd1c39b8)  
(KB947748)  
(Stupeň závažnosti není určen)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=0cabfbc0-db5d-4a6a-a4cd-e6df89ac2b25)  
(Kritický)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 a Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=d5891180-5dd1-49ec-bcc6-3030a544202c)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e0bd6fbe-f46e-4961-9a79-49ec77d39439)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=57bcb3c2-49d3-4f18-8d03-36abd03d7403)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=caf8a45e-a9f8-4e91-98fd-87eddbeae64c)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition a Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c5d26771-1f49-4bbf-902c-bf92e527cadb)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=18efea9e-b103-46de-90d9-5e295854cec3)  
(Kritický)  
[Windows Media Encoder 9 Series x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ebc1737c-6e78-4244-a1b2-a56d031f16e9)  
(Kritický)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 a Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ac03f138-eca4-46e1-9782-e811820e547f)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=54ce1080-94cf-4e4f-8e09-a7dbab2757c5)  
(Mírný)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition a Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=93f1451b-5b62-47e5-8f0c-b720b957999a)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=c83011cd-90b8-494c-9cad-fa055e101992)  
(Mírný)  
[Windows Media Encoder 9 Series x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=d8f1b782-136b-443f-b5f2-63aa4d1fd94a)  
(Mírný)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 pro systémy s procesorem Itanium a Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=14e99f8a-cdd4-40d7-8cfc-73ae6bd6dfad)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista a Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=2f4118fd-1ffb-46da-b922-cd4ca4f9d84e)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=16f3ad21-ed77-4c32-93df-3b650b2b32a5)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=334352e7-d41f-494f-866d-f1f1745ffd17)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=aa47d016-f5c9-4586-8876-f1f4f255f54d)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=99beebc4-553a-46f8-8245-e3d932306c93)  
(Kritický)  
[Windows Media Encoder 9 Series x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=54d1279a-7f26-4727-a39d-5505bcd4fc53)  
(Kritický)
</td>
</tr>
<tr>
<th style="border:1px solid black;" colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-054**](http://go.microsoft.com/fwlink/?linkid=121739)
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-053**](http://go.microsoft.com/fwlink/?linkid=123091)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro 32bitové systémy
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=72fc6028-6af4-44ec-8d2a-28c53807d6bc)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=23bd3be5-cc66-46f8-9420-49d65d8afe1d)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(Mírný)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](http://www.microsoft.com/downloads/details.aspx?familyid=3906512b-26db-473e-b522-3883ff34a21c)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=7f1e0f05-6c9d-4ad1-9b19-50ee4fa7bd7e)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=5434ca66-5a6b-4517-92fb-72dea0a172ec)\*  
(Mírný)  
[Windows Media Encoder 9 Series x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=e30f9427-26d0-4e86-b9b8-bc637c3b5734)\*  
(Mírný)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5159bdba-3825-4816-a2be-ab035332b9e2)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
</table>
<p></p>
 
**\*Instalace Server Core operačního systému Windows Server 2008 neobsahující tuto chybu.** Chyby zabezpečení, které řeší tyto aktualizace, nepostihují podporované edice systému Windows Server 2008, jestliže byl systém Windows Server 2008 instalován s využitím možnosti instalace server core, i když se soubory postižené těmito chybami zabezpečení mohou v systému vyskytovat. I přesto bude uživatelům se soubory postiženými těmito chybami tato aktualizace stále nabízena, neboť soubory aktualizace jsou novější (s vyššími čísly verze) než soubory, které jsou aktuálně ve vašem systému. Více informací o této možnosti instalace naleznete v části [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008. Další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://go.microsoft.com/fwlink/?linkid=125229)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)  
(Důležitý)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 a Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(Důležitý)  
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(Důležitý)  
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e670ad22-d3c1-41f7-ba30-6a67139feaa3)  
(KB953404)  
(Důležitý)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Systém Microsoft Office 2007 a systém Microsoft Office 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(Důležitý)  
[Systém Microsoft Office 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)  
(Důležitý)
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System](http://www.microsoft.com/downloads/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(Důležitý)  
[Systém Microsoft Office 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fb457536-26c5-428b-97e4-1fc13718266e)  
(KB951944)  
(Důležitý)
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
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
</td>
<td style="border:1px solid black;">
[**MS08-055**](http://go.microsoft.com/fwlink/?linkid=125229)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project 2002 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ef3de64c-fc17-4500-9da4-a3bba97fda6d)  
(KB953405)\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2002 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a6d9d3ef-f087-4f61-9ec1-522b7d4b9c48)  
(KB954479)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer, Microsoft Word Viewer 2003, Microsoft Word Viewer 2003 Service Pack 3, Microsoft Office Excel Viewer 2003, Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer, Microsoft Word Viewer 2003, Microsoft Word Viewer 2003 Service Pack 3, Microsoft Office Excel Viewer 2003, Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e9f8e309-d721-4bab-b485-5eede8d49eb8)  
(KB954478)\*\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office PowerPoint Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint Viewer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=cd503f08-1831-45ff-bdf4-dd918ca40505)  
(KB956500)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer, Microsoft Office PowerPoint Viewer 2007, Microsoft Office PowerPoint Viewer 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer, Microsoft Office PowerPoint Viewer 2007, Microsoft Office PowerPoint Viewer 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 a sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 a sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web a Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft Expression Web a Microsoft Expression Web 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove 2007 a Microsoft Office Groove 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove 2007 a Microsoft Office Groove 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4b656fe8-6253-490c-a81a-e4e8f0bb58d2)  
(KB954326)\*\*\*  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](http://www.microsoft.com/downloads/details.aspx?familyid=eb0d224e-a517-40d9-9fc6-2345fa12a841)  
(KB956483)  
(Důležitý)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Digital Image Suite 2006
</td>
<td style="border:1px solid black;">
[Microsoft Digital Image Suite 2006](http://www.microsoft.com/downloads/details.aspx?familyid=04afd760-8173-4069-9e82-d3bf053d9eae)  
(KB955992)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office OneNote 2007
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office OneNote 2007](http://www.microsoft.com/downloads/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(Kritický)  
[Microsoft Office OneNote 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8ac3576c-7873-4ac6-8bbc-033f6a7bb395)  
(KB950130)  
(Kritický)
</td>
</tr>
</table>
<p></p>
 
\*Aktualizace softwaru obsahujícího tuto chybu je totožná s aktualizací systému Microsoft Office XP Service Pack 3.

\*\*Aktualizace softwaru obsahujícího tuto chybu je totožná s aktualizací systému Microsoft Office 2003 Service Pack 2 a Microsoft Office 2003 Service Pack 3.

\*\*\*Aktualizace softwaru obsahujícího tuto chybu je totožná s aktualizací systému Microsoft Office System 2007 a Microsoft Office System 2007 Service Pack 1.

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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
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
SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
Netýká se  
Aktualizace QFE:  
[SQL Server 2000 Reporting Services Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5f9e7f78-7439-414b-a9dc-a779b89427db)  
(KB954609)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 pro systémy s procesorem Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4603c722-2468-4adb-b945-2ed0458b8f47)  
(KB954606)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5148b887-f323-4adb-9721-61e1c0cfd213)  
(KB954607)  
(Kritický)
</td>
</tr>
</table>
<p></p>
 

#### Vývojářské nástroje a software společnosti Microsoft

 
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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
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
Microsoft Visual Studio .NET 2002 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7848a652-4025-44bb-9c98-37a078b56d01)  
(KB947736)  
(Stupeň závažnosti není určen)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9bc1e8f8-6c30-4aa0-90f5-fbb0ad5fd90e)  
(KB947737)  
(Stupeň závažnosti není určen)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7bf790b-3249-4ee8-9440-fa911ebbc08a)  
(KB947738)  
(Stupeň závažnosti není určen)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=a8c80b29-6d00-4949-a005-5d706122919a)  
(KB952241)  
(Stupeň závažnosti není určen)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=82833f27-081d-4b72-83ef-2836360a904d)  
(KB954765)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=6ae0aa19-3e6c-474c-9d57-05b2347456b1)  
(KB954766)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1f4371b9-b8be-4455-94d2-2304ee340543) při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB955368)  
(Stupeň závažnosti není určen)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=49b21e30-722d-446e-9020-aceb3870db69) při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB955369)  
(Stupeň závažnosti není určen)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=36957f47-9d8b-477d-bd60-5959e5a2eafa) při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB955370)  
(Stupeň závažnosti není určen)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable: GDI+
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable: GDI+](http://www.microsoft.com/downloads/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(Stupeň závažnosti není určen)
</td>
</tr>
</table>
<p></p>
 

#### Microsoft - software pro zabezpečení

 
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
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS08-052**](http://go.microsoft.com/fwlink/?linkid=125468)
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
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Client Security 1.0](http://www.microsoft.com/downloads/details.aspx?familyid=1eb1a79f-44ca-499e-90bb-ac51894e9d1e) při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB957177)  
(Důležitý)
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

**Doporučené postupy zjišťování a instalace**

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

-   Gregu MacManusovi ze společnosti [VeriSign iDefense Labs](http://labs.idefense.com/) za oznámení chyby popsané v bulletinu MS08-052.
-   Bingu Liuovi z výzkumného týmu [FortiGuard Global Security Research Team společnosti Fortinet](http://www.fortiguardcenter.com/) za oznámení chyby popsané v bulletinu MS08-052.
-   Peteru Winter-Smithovi ze společnosti [NGSSoftware](http://www.ngssoftware.com/) a Ivanu Fratricovi, spolupracovníku organizace [Zero Day Initiative](http://www.zerodayinitiative.com/), za oznámení chyby popsané v bulletinu MS08-052.
-   [Výzkumnému týmu chyb zabezpečení, Assurent Secure Technologies](http://www.assurent.com/), za oznámení chyby popsané v bulletinu MS08-052.
-   Anonymnímu výzkumníkovi spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) za oznámení chyby popsané v bulletinu MS08-052.
-   Nguyenu Minh Ducovi a Leu Manh Tungovi z centra [Bach Khoa Internetwork Security Center (BKIS) Hanojské polytechnické univerzity (Vietnam)](http://security.bkis.vn/) za oznámení chyby popsané v bulletinu MS08-053.
-   Brettu Mooreovi ze společnosti [Insomnia Security](http://www.insomniasec.com/) za oznámení chyby popsané v bulletinu MS08-055.

#### Technická podpora

-   Uvedený software byl testován za účelem zjištění, kterých verzí se chyba týká. U dalších verzí skončila časově omezená podpora. Pokud chcete zjistit dobu, po kterou je pro určitou verzi softwaru poskytována podpora, navštivte web [Zásady poskytování technické podpory pro produkty společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Zákazníci mohou získat technickou podporu na webu [služby technické podpory společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21131). Hovory související s aktualizacemi zabezpečení jsou bezplatné.
-   Mezinárodní zákazníci získají podporu u místních zastoupení společnosti Microsoft. Technická podpora související s aktualizacemi zabezpečení je bezplatná. Další informace o možnostech kontaktování společnosti Microsoft v případě potřeby technické podpory získáte na [webu mezinárodní technické podpory](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zřeknutí se záruky

Informace ve znalostní bázi Microsoft Knowledge Base jsou poskytovány tak, jak jsou, bez jakékoli záruky. Společnost Microsoft neposkytuje žádné záruky, výslovně uvedené či mlčky předpokládané, včetně záruk obchodovatelnosti a vhodnosti pro určitý účel. Společnost Microsoft ani její dodavatelé nenesou v žádném případě zodpovědnost za žádné škody, včetně přímých, nepřímých, náhodných či následných škod, ztráty zisku či zvláštních škod, a to ani v případě, že byli na možnost takových škod upozorněni. V některých zemích a právních řádech není dovoleno vyloučit nebo omezit odpovědnost, proto se výše uvedené omezení na vás nemusí vztahovat.

#### Revize

-   V1.0 (9. září 2008): Souhrnný bulletin byl publikován.
-   V2.0 (9. září 2008): Souhrnný bulletin byl aktualizován, aby do seznamu softwaru obsahujícího chybu zabezpečení uvedenou v bulletinu MS08-052 přidal software Microsoft Office Project 2002 Service Pack 2, všechny prohlížeče Office Viewer pro systém Microsoft Office 2003 a všechny prohlížeče Office Viewer pro systém Microsoft Office 2007.
-   V2.1 (17. září 2008): Souhrnný bulletin byl aktualizován, aby v tabulce softwaru obsahujícího chybu změnil název Microsoft Office Project 2002 Service Pack 2 na Microsoft Office Project 2002 Service Pack 1. Jedná se pouze o změnu názvu. Nebyly provedeny žádné změny binárních souborů nebo detekce.
-   V2.2 (29. října 2008): Souhrnný bulletin byl aktualizován, aby odebral prohlížeče Microsoft Visio 2003 Viewer, Microsoft Visio 2007 Viewer a Microsoft Visio 2007 Viewer Service Pack 1 ze seznamu softwaru obsahujícího chybu zabezpečení v bulletinu MS08-052.
-   V3.0 (9. prosince 2008): Souhrnný bulletin byl aktualizován, aby do seznamu softwaru obsahujícího chybu zabezpečení, uvedeného v bulletinu MS08-052, přidal sadu Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 a sadu Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 1, aplikace Microsoft Expression Web, Microsoft Expression Web 2, Microsoft Office Groove 2007 a Microsoft Office Groove 2007 Service Pack 1.

*Built at 2014-04-18T01:50:00Z-07:00*
