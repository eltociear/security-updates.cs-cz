---
TOCTitle: 'MS09-OCT'
Title: 'Souhrnný bulletin zabezpečení společnosti Microsoft, říjen 2009'
ms:assetid: 'ms09-oct'
ms:contentKeyID: 61223992
ms:mtpsurl: 'https://technet.microsoft.com/cs-CZ/library/ms09-oct(v=Security.10)'
---

 

Souhrnný bulletin zabezpečení společnosti Microsoft, říjen 2009
===============================================================

Publikováno: 13. října 2009 | Aktualizováno: 22. června 2010

**Verze:** 4.2

Tento souhrnný bulletin uvádí bulletiny zabezpečení vydané v říjnu 2009.

Spolu s vydáním bulletinů pro říjen 2009 nahrazuje tento souhrnný bulletin předběžné oznámení o bulletinech vydané 8. října 2009. Další informace o službě předběžného oznámení o bulletinech naleznete v části [Předběžné oznámení o bulletinech zabezpečení společnosti Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Informace o tom, jak dostávat automatická oznámení o vydání nových bulletinů zabezpečení společnosti Microsoft, naleznete na webu [Zasílání technických oznámení o zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

Pro zodpovězení zákaznických dotazů týkajících se těchto bulletinů uspořádá společnost Microsoft webové vysílání 14. října 2009 v 11:00 časového pásma Tichomoří (USA a Kanada). [Registrovat se pro webové vysílání týkající se říjnových bulletinů zabezpečení](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407488&culture=en-us). Po tomto datu je webové vysílání dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://technet.microsoft.com/security/bulletin/summary).

Společnost Microsoft se snaží zákazníkům usnadnit upřednostnění měsíčně vydávaných aktualizací zabezpečení před jakýmikoli důležitými aktualizacemi nesouvisejícími se zabezpečením, které jsou vydány ve stejný den jako měsíčně vydávané aktualizace zabezpečení. Další informace získáte v části **Další informace**.

### Informace o bulletinech

Shrnutí
-------


Následující tabulka shrnuje podle závažnosti bulletiny zabezpečení pro tento měsíc.

Podrobnosti o softwaru obsahujícím tuto chybu naleznete v následující části **Software obsahující tuto chybu a umístění aktualizací ke stažení**.

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >ID bulletinu</th>
<th style="border:1px solid black;" >Název bulletinu a shrnutí</th>
<th style="border:1px solid black;" >Maximální stupeň závažnosti a dopad chyby zabezpečení</th>
<th style="border:1px solid black;" >Požadavek na restartování</th>
<th style="border:1px solid black;" >Software obsahující tuto chybu</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163970">MS09-050</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v protokolu SMBv2 umožňují vzdálené spuštění kódu (975517)</strong><br />
<br />
Tato aktualizace zabezpečení řeší jednu veřejně známou a dvě soukromou osobou oznámené chyby zabezpečení protokolu Server Message Block Version 2 (SMBv2). Nejzávažnější z těchto chyb zabezpečení by mohla umožnit vzdálené spuštění kódu v případě, že by útočník odeslal speciálně vytvořený paket SMB do počítače se službou Server. Doporučené postupy pro používání brány firewall a standardní konfigurace této brány zajišťují ochranu sítí před útoky pocházejícími z oblasti mimo rozlehlou síť. Je vhodné, aby systémy připojené k Internetu měly přístupný minimální počet portů.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125438">MS09-051</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení formátu Windows Media Runtime umožňují vzdálené spuštění kódu (975682)</strong><br />
<br />
Tato aktualizace zabezpečení řeší dvě chyby zabezpečení formátu Windows Media Runtime oznámené soukromými osobami. Tyto chyby zabezpečení umožňují vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený mediální soubor nebo obdrží speciálně vytvořený obsah vysílání datového proudu médií z webové stránky nebo jakékoli aplikace poskytující webový obsah. Útočník, který by úspěšně zneužil tyto chyby zabezpečení, by mohl získat stejná uživatelská práva, jaká má místní uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163913">MS09-052</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení programu Windows Media Player umožňuje vzdálené spuštění kódu (974112)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení v programu Windows Media Player, kterou oznámila soukromá osoba. Tato chyba zabezpečení umožňuje vzdálené spuštění kódu v případě přehrávání speciálně vytvořeného souboru ASF v programu Windows Media Player 6.4. Útočník, který by úspěšně zneužil tuto chybu zabezpečení, by mohl získat stejná uživatelská práva, jako má místní uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163979">MS09-054</a></td>
<td style="border:1px solid black;"><strong>Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (974455)</strong><br />
<br />
Tato aktualizace zabezpečení řeší tři chyby zabezpečení oznámené soukromými osobami a jednu veřejně známou chybu zabezpečení v aplikaci Internet Explorer. Tyto chyby zabezpečení mohou umožňovat vzdálené spuštění kódu, pokud uživatel pomocí aplikace Internet Explorer zobrazí speciálně vytvořenou webovou stránku. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. Instalaci této aktualizace zabezpečení doporučujeme také uživatelům prohlížeče Firefox, kteří používají modul plug-in grafického subsystému Windows Presentation Foundation (WPF) a nemají jej zakázaný. Další informace o tomto problému najdete v části Nejčastější dotazy týkající se chyby zabezpečení při zpracování součástí HTML - CVE-2009-2529.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-055">MS09-055</a></td>
<td style="border:1px solid black;"><strong>Kumulativní aktualizace zabezpečení dezaktivačních bitů ActiveX (973525)</strong><br />
<br />
Tato aktualizace zabezpečení řeší aktuálně zneužívanou chybu zabezpečení oznámenou soukromou osobou v ovládacích prvcích ActiveX. Chyba zabezpečení v ovládacích prvcích ActiveX, které byly sestaveny pomocí verze knihovny Microsoft Active Template Library (ATL) obsahující chybu zabezpečení, umožňuje vzdálené spuštění kódu v případě, že uživatel v aplikaci Internet Explorer otevře speciálně vytvořenou webovou stránku, která vytváří instance ovládacího prvku ActiveX. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160633">MS09-060</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v ovládacích prvcích knihovny Microsoft Active Template Library (ATL) pro systém Microsoft Office umožňují vzdálené spuštění kódu (973965)</strong><br />
<br />
Tato aktualizace zabezpečení řeší několik soukromými osobami oznámených chyb zabezpečení ovládacích prvků ActiveX v systému Microsoft Office, které byly sestaveny pomocí verze knihovny Microsoft Active Template Library (ATL) obsahující chybu zabezpečení. Tyto chyby zabezpečení by mohly umožnit vzdálené spuštění kódu, pokud by uživatel načetl speciálně vytvořenou komponentu nebo ovládací prvek. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160527">MS09-061</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení ve společném jazykovém modulu runtime Microsoft .NET umožňují vzdálené spuštění kódu (974378)</strong><br />
<br />
Tato aktualizace zabezpečení řeší tři soukromými osobami oznámené chyby zabezpečení ve službách Microsoft .NET Framework a Microsoft Silverlight. Tyto chyby zabezpečení by mohly umožnit vzdálené spuštění kódu v klientském systému, pokud by uživatel zobrazil speciálně vytvořenou webovou stránku pomocí webového prohlížeče, v němž lze otevírat aplikace XAML Browser Applications (XBAP) nebo Silverlight Applications nebo kdyby útočník přesvědčil uživatele, aby spustil speciálně vytvořenou aplikaci Microsoft .NET. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce. Chyby zabezpečení dále mohou umožnit vzdálené spuštění kódu na serverovém systému se službou IIS v případě, že tento server umožňuje zpracování stránek ASP.NET a útočníkovi se úspěšně podaří na daném serveru načíst speciálně vytvořenou stránku ASP.NET a spustit ji, jako například v případě hostování webu. Aplikace Microsoft .NET, Silverlight, stránky XBAP a ASP.NET, které neobsahují škodlivý kód, nejsou vystaveny riziku napadení v důsledku této chyby zabezpečení.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)</strong><br />
<br />
Tato aktualizace zabezpečení řeší několik chyb zabezpečení v rozhraní GDI+ systému Microsoft Windows oznámených soukromými osobami. Tato chyba zabezpečení může umožnit vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený soubor s obrázkem nebo přejde na web, který obsahuje speciálně vytvořený obsah. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer,<br />
Microsoft .NET Framework,<br />
Microsoft Office,<br />
Microsoft SQL Server,<br />
Vývojářské nástroje společnosti Microsoft,<br />
Microsoft Forefront</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=164004">MS09-053</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení ve službě FTP pro Internetovou informační službu umožňují vzdálené spuštění kódu (975254)</strong><br />
<br />
Tato aktualizace zabezpečení řeší dvě veřejně známé chyby zabezpečení ve službě FTP Service pro Internetovou informační službu (IIS) 5.1, Internetovou informační službu (IIS) 6.0 a Internetovou informační službu (IIS) 7.0. Ve službě IIS 7.0 tuto chybu zabezpečení obsahuje pouze služba FTP 6.0. Tyto chyby zabezpečení by mohly umožnit vzdálené spuštění kódu (RCE) v systémech se službou FTP ve službě IIS 5.0 nebo odmítnutí služby (DoS) v systémech se službou FTP ve službě IIS 5.0, IIS 5.1, IIS 6.0 nebo IIS 7.0.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163830">MS09-056</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v rozhraní Windows CryptoAPI umožňují vkládání falešného obsahu (974571)</strong><br />
<br />
Tato aktualizace zabezpečení řeší dvě veřejně známé chyby zabezpečení v systému Microsoft Windows. Tyto chyby zabezpečení by mohly umožnit umístění falešného obsahu, pokud by útočník získal přístup k certifikátu používanému koncovým uživatelem pro ověření.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Falšování obsahu</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163832">MS09-057</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení Služby indexování umožňuje vzdálené spuštění kódu (969059)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení v systému Microsoft Windows, kterou oznámila soukromá osoba. Tato chyba zabezpečení by mohla způsobit vzdálené spuštění kódu, pokud by útočník nastavil webovou stránku obsahující chybu zabezpečení, která spustí Službu indexování prostřednictvím volání součásti ActiveX. Toto volání by mohlo obsahovat škodlivou adresu URL a zneužít chybu zabezpečení tak, že útočníkovi udělí přístup do klientského systému s oprávněními uživatele, který webovou stránku prochází. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=162442">MS09-058</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (971486)</strong><br />
<br />
Tato aktualizace zabezpečení řeší několik chyb zabezpečení jádra systému Windows oznámených soukromými osobami. Nejzávažnější z těchto chyb zabezpečení by mohla způsobit zvýšení úrovně oprávnění, pokud by se útočník přihlásil k systému a spustil speciálně vytvořenou aplikaci. Tuto chybu může zneužít pouze útočník s platnými pověřeními pro přihlášení, která by mu umožňovala se místně přihlásit. Uvedené chyby zabezpečení nemohou zneužít vzdálení ani anonymní uživatelé.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163843">MS09-059</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení ve službě LSASS (Local Security Authority Subsystem Service) může způsobit odmítnutí služby (975467)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení v systému Microsoft Windows, kterou oznámila soukromá osoba. Tato chyba zabezpečení by mohla způsobit odmítnutí služby, pokud by útočník odeslal nebezpečný paket během procesu ověřování NTLM.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Odmítnutí služby</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
<p></p>
  
Index zneužitelnosti  
--------------------
  

Následující tabulka uvádí hodnocení zneužitelnosti každé chyby zabezpečení uvedené v tomto měsíci. Chyby zabezpečení jsou řazeny podle čísla jednotlivých bulletinů (ID bulletinu) a chyb (ID CVE).
  
**Jak pracovat s touto tabulkou**
  
V této tabulce zjistíte, jaká je pravděpodobnost vydání funkčního zneužitelného kódu během 30 dní od vydání tohoto bulletinu zabezpečení pro všechny aktualizace zabezpečení, které bude třeba nainstalovat. Všechna níže uvedená hodnocení zvažte na základě vaší specifické konfigurace a podle závěrů hodnocení nastavte priority pro zavádění jednotlivých aktualizací. Další informace o významu těchto hodnocení a způsobu jejich stanovení najdete v indexu zneužitelnosti [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| ID bulletinu                                                        | Název bulletinu                                                                                                                                                      | ID CVE                                                                           | Hodnocení indexu zneužitelnosti                                                                                                | Hlavní poznámky                                                                                                                                                                                                                                                                                                                                                                                         |  
|---------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-050](http://go.microsoft.com/fwlink/?linkid=163970)           | Chyby zabezpečení v protokolu SMBv2 umožňují vzdálené spuštění kódu (975517)                                                                                         | [CVE-2009-2526](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2526) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení, která způsobuje omezené odmítnutí služby.                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-050](http://go.microsoft.com/fwlink/?linkid=163970)           | Chyby zabezpečení v protokolu SMBv2 umožňují vzdálené spuštění kódu (975517)                                                                                         | [CVE-2009-2532](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2532) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-050](http://go.microsoft.com/fwlink/?linkid=163970)           | Chyby zabezpečení v protokolu SMBv2 umožňují vzdálené spuštění kódu (975517)                                                                                         | [CVE-2009-3103](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3103) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | Zneužití kódu je veřejně publikováno.                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-051](http://go.microsoft.com/fwlink/?linkid=125438)           | Chyby zabezpečení formátu Windows Media Runtime umožňují vzdálené spuštění kódu (975682)                                                                             | [CVE-2009-0555](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0555) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-051](http://go.microsoft.com/fwlink/?linkid=125438)           | Chyby zabezpečení formátu Windows Media Runtime umožňují vzdálené spuštění kódu (975682)                                                                             | [CVE-2009-2525](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2525) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-052](http://go.microsoft.com/fwlink/?linkid=163913)           | Chyba zabezpečení programu Windows Media Player umožňuje vzdálené spuštění kódu (974112)                                                                             | [CVE-2009-2527](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2527) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-053](http://go.microsoft.com/fwlink/?linkid=164004)           | Chyby zabezpečení ve službě FTP pro Internetovou informační službu umožňují vzdálené spuštění kódu (975254)                                                          | [CVE-2009-2521](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2521) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení, která způsobuje odmítnutí služby (DoS). Zneužití kódu je veřejně publikováno.                                                                                                                                                                                                                                                                                             |  
| [MS09-053](http://go.microsoft.com/fwlink/?linkid=164004)           | Chyby zabezpečení ve službě FTP pro Internetovou informační službu umožňují vzdálené spuštění kódu (975254)                                                          | [CVE-2009-3023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3023) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | Zneužití kódu je veřejně publikováno.                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979)           | Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (974455)                                                                                          | [CVE-2009-1547](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1547) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979)           | Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (974455)                                                                                          | [CVE-2009-2529](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2529) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979)           | Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (974455)                                                                                          | [CVE-2009-2530](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2530) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | V systémech Microsoft Windows 2000 zvyšuje nedostatečná ochrana haldy hodnocení indexu zneužitelnosti na hodnotu [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný.                                                                                                                                                                       |  
| [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979)           | Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (974455)                                                                                          | [CVE-2009-2531](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2531) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              |                                                                                                                                                                                                                                                                                                                                                                                                         |  
| [MS09-055](http://technet.microsoft.com/security/bulletin/ms09-055) | Kumulativní aktualizace zabezpečení dezaktivačních bitů ActiveX (973525)                                                                                             | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | Žádné                                                                                                                          | (Této chybě zabezpečení byl přidělen index zneužitelnosti již v [červencovém souhrnném bulletinu](http://technet.microsoft.com/security/bulletin/ms09-jul). Důvodem je, že tato chyba zabezpečení se poprvé objevila v bulletinu [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131).) Viz také stejné číslo CVE v bulletinu [MS09-060](http://go.microsoft.com/fwlink/?linkid=160633).           |  
| [MS09-056](http://go.microsoft.com/fwlink/?linkid=163830)           | Chyby zabezpečení v rozhraní Windows CryptoAPI umožňují vkládání falešného obsahu (974571)                                                                           | [CVE-2009-2510](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2510) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení umožňující vkládání falešného obsahu.                                                                                                                                                                                                                                                                                                                                      |  
| [MS09-056](http://go.microsoft.com/fwlink/?linkid=163830)           | Chyby zabezpečení v rozhraní Windows CryptoAPI umožňují vkládání falešného obsahu (974571)                                                                           | [CVE-2009-2511](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2511) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení umožňující vkládání falešného obsahu.                                                                                                                                                                                                                                                                                                                                      |  
| [MS09-057](http://go.microsoft.com/fwlink/?linkid=163832)           | Chyba zabezpečení Služby indexování umožňuje vzdálené spuštění kódu (969059)                                                                                         | [CVE-2009-2507](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2507) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-058](http://go.microsoft.com/fwlink/?linkid=162442)           | Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (971486)                                                                                          | [CVE-2009-2515](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2515) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-058](http://go.microsoft.com/fwlink/?linkid=162442)           | Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (971486)                                                                                          | [CVE-2009-2516](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2516) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Tato chyba zabezpečení je příčinou odmítnutí služby v případě cíleného použití sdílené síťové položky a zvýšení úrovně oprávnění v případě místního použití k zaměření na místní systém.                                                                                                                                                                                                                |  
| [MS09-058](http://go.microsoft.com/fwlink/?linkid=162442)           | Chyby zabezpečení jádra systému Windows umožňují zvýšení oprávnění (971486)                                                                                          | [CVE-2009-2517](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2517) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení, která způsobuje odmítnutí služby (DoS).                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-059](http://go.microsoft.com/fwlink/?linkid=163843)           | Chyba zabezpečení ve službě LSASS (Local Security Authority Subsystem Service) může způsobit odmítnutí služby (975467)                                               | [CVE-2009-2524](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2524) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení, která způsobuje omezené odmítnutí služby.                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-060](http://go.microsoft.com/fwlink/?linkid=160633)           | Chyby zabezpečení v ovládacích prvcích ActiveX knihovny Microsoft Active Template Library (ATL) pro systém Microsoft Office umožňují vzdálené spuštění kódu (973965) | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | Žádné                                                                                                                          | (Této chybě zabezpečení byl přidělen index zneužitelnosti již v [červencovém souhrnném bulletinu](http://technet.microsoft.com/security/bulletin/ms09-jul). Tato chyba zabezpečení se poprvé objevila v bulletinu [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131).)                                                                                                                           |  
| [MS09-060](http://go.microsoft.com/fwlink/?linkid=160633)           | Chyby zabezpečení v ovládacích prvcích ActiveX knihovny Microsoft Active Template Library (ATL) pro systém Microsoft Office umožňují vzdálené spuštění kódu (973965) | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | Žádné                                                                                                                          | (Této chybě zabezpečení byl přidělen index zneužitelnosti již v [červencovém souhrnném bulletinu](http://technet.microsoft.com/security/bulletin/ms09-jul). Důvodem je, že tato chyba zabezpečení se poprvé objevila v bulletinu [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131).) Viz také stejné číslo CVE v bulletinu [MS09-055](http://technet.microsoft.com/security/bulletin/ms09-055). |  
| [MS09-060](http://go.microsoft.com/fwlink/?linkid=160633)           | Chyby zabezpečení v ovládacích prvcích ActiveX knihovny Microsoft Active Template Library (ATL) pro systém Microsoft Office umožňují vzdálené spuštění kódu (973965) | [CVE-2009-2495](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Jedná se o chybu zabezpečení typu zpřístupnění informací.                                                                                                                                                                                                                                                                                                                                               |  
| [MS09-061](http://go.microsoft.com/fwlink/?linkid=160527)           | Chyby zabezpečení ve společném jazykovém modulu runtime Microsoft .NET umožňují vzdálené spuštění kódu (974378)                                                      | [CVE-2009-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0090) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-061](http://go.microsoft.com/fwlink/?linkid=160527)           | Chyby zabezpečení ve společném jazykovém modulu runtime Microsoft .NET umožňují vzdálené spuštění kódu (974378)                                                      | [CVE-2009-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0091) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-061](http://go.microsoft.com/fwlink/?linkid=160527)           | Chyby zabezpečení ve společném jazykovém modulu runtime Microsoft .NET umožňují vzdálené spuštění kódu (974378)                                                      | [CVE-2009-2497](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2497) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | Existuje potenciál útoků ovlivňujících Internet.                                                                                                                                                                                                                                                                                                                                                        |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-2500](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2500) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-2501](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2501) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-2502](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2502) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-2503](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2503) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-2504](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2504) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-2518](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2518) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-2528](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2528) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-062](http://go.microsoft.com/fwlink/?linkid=161342)           | Chyby zabezpečení v rozhraní GDI+ umožňují vzdálené spuštění kódu (957488)                                                                                           | [CVE-2009-3126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3126) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | (Žádné)                                                                                                                                                                                                                                                                                                                                                                                                 |
  
Software obsahující tuto chybu a umístění aktualizací ke stažení  
----------------------------------------------------------------
  

Následující tabulky řadí bulletiny podle kategorie hlavního softwaru a závažnosti.
  
**Jak pracovat s těmito tabulkami?**
  
V těchto tabulkách zjistíte, které aktualizace zabezpečení bude třeba nainstalovat. Přečtěte si seznam všech programů a komponent a zjistěte, zda se některé aktualizace zabezpečení týkají vaší instalace. Pokud se program nebo komponenta v seznamu nachází, je v něm zároveň uveden odkaz na dostupnou aktualizaci softwaru a také stupeň závažnosti aktualizace softwaru.
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://go.microsoft.com/fwlink/?linkid=163843)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádné
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
[**Žádný**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Hlasový kodek DirectShow WMA](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=8f850a82-61f9-447b-a0aa-a2c192cc5d2e)  
(KB954155)  
(Kritický)  
[Správce zvukové komprese](http://www.microsoft.com/downloads/details.aspx?familyid=6dfd5405-cabe-4bd7-9330-b6bde1d99194)  
(KB975025)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=13035ef7-7e47-487c-8b7c-7795d33ce7de)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=26515c7b-d7a6-4405-96b5-a518dcb39d38)  
(Kritický)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8154ba37-0fbc-4d31-9d6e-0b21586ad65a)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=edfea805-9544-4dc0-a52c-d7594205657b)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f3fef608-dafb-4b37-a65a-9cc4ae8e2c4c)  
(KB958869)  
(Kritický)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ecf78619-80fa-417d-852b-1b5b2cf574e2)  
(KB971108)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3e534aa8-29c2-4379-9f57-931a6ff47418)  
(KB971110)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e6f5e730-85cc-4c08-a50d-c456b1e9f5bc)  
(KB971111)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=7fecd367-aaff-458b-91bc-8925c8e57528)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=52b9198d-b65f-467a-a5ab-141e23d64a86)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=b34d94b5-b828-4e16-a636-04344c60d945)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=bdfa6583-28a2-4d6b-91d2-157a8518b664)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://go.microsoft.com/fwlink/?linkid=163843)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádné
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 a Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Hlasový kodek DirectShow WMA](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=4516c219-e357-485e-a52b-23dcb8ee49d8)  
(KB954155)  
(Kritický)  
(pouze Windows XP Service Pack 2)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=746d3440-5a6a-421e-9286-7b534a1dfe54)  
(KB954155)  
(Kritický)  
(pouze Windows XP Service Pack 3)  
[Správce zvukové komprese](http://www.microsoft.com/downloads/details.aspx?familyid=6ecc7129-8caa-4daf-a8e2-8f3536225fb3)  
(KB975025)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=b2efe1ac-d8d7-41bb-b87d-fc5e22afef0f)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9aacf890-afb4-46a7-a13f-dd9fe3c0ca4a)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dc166dc6-577f-4d8d-94df-dd963233dd85)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=8799159d-df69-49f6-9db5-49147690ce0c)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=171d43d3-669c-4923-b266-e47591833c05)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1bc56c26-1c7c-47e3-94f4-37af7e00392c)  
(KB953295)  
(Kritický)  
(Pouze Tablet PC Edition 2005 a Media Center Edition 2005)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e2acde20-a6d3-4135-b6eb-1214f743d474)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2ae0bdd4-f8b2-420a-b1ac-d2cdaa87c828)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9c5ab624-e37b-418a-a919-d8f652b15679)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=768fd74e-0a2f-4353-ac22-65d0d6321739)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cece4c55-0756-4357-9d2d-6709e8426068)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e997ea40-668e-40df-bd50-0ca53437b375)<sup>[1]</sup>
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Hlasový kodek DirectShow WMA](http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=4729de51-8fd8-46c6-b4ad-9c9f25202684)  
(KB954155)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2) v sadě Windows Media Format SDK 9.5 x64 Edition  
(KB954155)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=a866a490-6d3a-4ecd-acf4-770312ba2fd6) v sadě Windows Media Format SDK 11  
(KB954155)  
(Kritický)  
[Správce zvukové komprese](http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=a9e7dfd8-7ba1-4f14-8e60-92ef00d91467)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=89a2cf2a-a7a2-4d4b-aa6f-24dde288d500)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=bd54e595-25f2-4839-a838-2a0f809bde2b)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=77b18fc2-e769-47c6-8e72-916716a49e58)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c08623bf-94bc-4c50-8c10-f50fb8448a0b)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad92503a-8c91-4d73-98b0-942d7961637d)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=819dd2d1-cad5-4784-9baf-185d8a76df5d)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad29696d-4611-4a12-9dfa-74fa6866b759)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=270ec100-5ba1-4f8c-aa36-105d30ad57bf)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5459b7d4-1fab-4a04-ab9d-b8323505c1e2)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17008892-7950-44c4-850d-002c8d73495f)<sup>[1]</sup>
(Vysoký)
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://go.microsoft.com/fwlink/?linkid=163843)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádné
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
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Hlasový kodek DirectShow WMA](http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=00b3cb86-c9eb-4fbe-987e-2b0d94271d87)  
(KB954155)  
(Kritický)  
[Správce zvukové komprese](http://www.microsoft.com/downloads/details.aspx?familyid=ab1803ff-2371-487f-a7b6-95747c46ba4e)  
(KB975025)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=5f82d01c-573e-425e-b9f2-86a54f377b19)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=8101625d-ee93-46e5-aec2-3bdbf2d86472)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4647bcf1-69fb-4ad6-9e03-7bc22d8a914b)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9eae7eca-1a6f-4397-a6e2-7dda6b9d5276)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f3249c99-82e4-45dc-a254-28e647e822c8)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d1b4a58b-f0b1-4400-a6e6-0255b0513bd1) (KB953298)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=414466a4-39a0-476d-9a43-ae7674cbd6a0)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48256ea3-b433-4e84-9019-22300069cfc1)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=78072164-84d1-44da-8ede-2a9d212d47a9)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1e3f3842-f8fd-4969-a2cf-706db38d7580)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9dff4662-7771-4bdc-87ec-7899d79b3a55)<sup>[1]</sup>
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Hlasový kodek DirectShow WMA](http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=13ba4839-7fa9-4bbb-95f6-3fafb6c49f20)  
(KB954155)  
(Kritický)  
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2) v sadě Windows Media Format SDK 9.5 x64 Edition  
(KB954155)  
(Kritický)  
[Správce zvukové komprese](http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=65e9036e-2e1b-40ff-a84b-c507107bcce8)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2f966053-01eb-4a23-a9d5-71deac2498ea)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e7d77bd9-8317-42f3-9ad1-a0b8bfa65b53)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=708a549d-11fd-43bf-a6e1-309e3205d59d)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1ad3f7b3-58d5-4507-ae20-a265e47cee9c)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eb95e8d9-6ef5-4526-99d2-507e50de049b)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=61bded07-201e-4815-ac1e-468bf907e063)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8aa1f97d-ad53-4450-bb93-4a147dd10a87)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=95286b8d-4b53-4e6c-af59-e9e18fad3559)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8df7a2d9-2f97-4f18-84e8-415a1632cf09)<sup>[1]</sup>
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 pro systémy s procesorem Itanium
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
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=79a1a94d-3b47-47e9-9476-2f591c3f6a59)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=07e66c09-2cd7-47ba-bf87-d3da602184b4)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=575e75d9-e348-4fbb-9eaa-43240e4d715e)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=a678ceb9-a37a-4c29-8bd1-f209922990e5)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b99d4d9b-e0cc-4a8c-ad99-6a53958b37c8)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2ede1eb9-7f5f-411d-bbc3-5db46d80e0bb)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=fb5678b9-5ef1-42db-902e-c9ea02880e0a)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=faef714b-5f46-47f2-bea7-881df05a1bc0)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=83c77015-7f96-4c0d-bd56-60aef90ea2f8)<sup>[1]</sup>
(Vysoký)
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://go.microsoft.com/fwlink/?linkid=163843)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Žádné
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
Windows Vista
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=29842c0c-8930-4b5f-83c6-1a718974b63f)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=f17ee0ea-f1e2-49f4-9f90-60296246ddfe)  
(KB954155)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f6995616-2a84-4c26-9599-26f1314873ed)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e8f6014f-950b-4e11-a105-51d298069f1a)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7313c03b-8844-4086-a0cc-43dfdb3ca48c)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=19aa01f3-026d-4264-85f8-216d0597969b)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bb96eb1c-66a2-4276-9773-eea22179bcd4)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b5a9a95-9439-40c8-acef-000b919daa04)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista a Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=04ae306b-0d0d-4767-ab54-cc11aec477ed)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
(Kritický)
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
(Mírný)
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=62ed5d0a-5ca6-4942-80c9-7808b14cb6b5)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=26905f12-92c7-4d45-99e7-227f03d2cb82)  
(KB954155)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=b3de5236-afdd-436e-8648-5382d564cc99)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=85978f28-5fc0-481b-9b03-2021c785889b)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7216bcb1-ff16-402b-ad1b-1500d46d0157)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 1 a Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8f5f0c1d-1dd6-47fa-aef2-d3c96c8fc06e)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bce096c8-833b-45c8-99cd-1280f0744f2f)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4a60f789-1a4a-49a8-8d13-fda989ed40be)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition a Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=58c995ca-f308-4e07-8e60-2e542384d95d)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
(Kritický)
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(Kritický)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
(Mírný)
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://go.microsoft.com/fwlink/?linkid=163843)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Nízký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Žádné
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
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ff6bfcf3-76c9-4c45-b57d-22f94458dd6e)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=2eaa9857-a147-4f31-9bf4-b9e2cf4c15c3)\*\*  
(KB954155)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=72dd580e-eb53-41da-a5c0-a392ad388bfc)\*\*  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1baf7e96-ba3e-47e7-8ea3-eb092e653a39)\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=51eb56fa-8204-45f3-86d7-6d03a2c8d78d)\*\*  
(Nízký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systém](http://www.microsoft.com/downloads/details.aspx?familyid=fd1694af-8873-43aa-9243-91f7cde452b7)y\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d9c5039f-d0cf-4d84-850f-f2f7701dcb79)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f9b487af-fe73-42a8-b240-d59c4321f95b)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f2f617c2-f149-4e9b-bfdd-08ed0f3f99db)\*  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro 32bitové systémy Service Pack 2
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)\*\*  
(KB974470)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
(Mírný)
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aff6f9c7-4a72-48f2-b750-204d796c7daa)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Dekodér Windows Media Audio Voice](http://www.microsoft.com/downloads/details.aspx?familyid=70aabba3-53d6-4b52-be83-6d3f3869ecbd)\*\*  
(KB954155)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0111d741-bda4-4a50-a12b-d3337ff4441d)\*\*  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7a4b755b-7fa0-43aa-8862-c1d0c7d94c2c)\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=131b047a-ae93-4a99-83e5-71d5a79e96ea)\*\*  
(Nízký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Důležitý)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
(Důležitý)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=41bc4cdb-273a-4a6e-80d9-c8ce20e32da9)\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=db969ddc-708e-42b7-9956-6c27bf346bbb)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0d8a2a3e-d7d4-47fb-8364-16fce28e4d38)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=deb84cb8-2ba3-47e3-9185-2bbc5b0a7e18)\*  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64 Service Pack 2
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)\*\*  
(KB974470)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
(Mírný)
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7b70108b-7f59-4898-ab4e-76be990de878)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e81f30b7-ef05-4488-b62a-d330e17129cf)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d16c5bf-ee5c-4220-9755-5cb92eac2aae)  
(Nízký)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda)  
(KB974291)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2 a Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)  
(KB974469)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=a4f42085-1cb9-4b8d-a931-85be71fdf06d)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a221451a-cb4e-4a43-a225-4b1e86e87525)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8962f0b6-f346-4e88-9d83-4d15b699dd9d)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(Vysoký)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aac0e3e-9b49-4a4a-ab17-707ff03b4d9b)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
(Vysoký)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)  
(KB974470)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(Mírný)
</td>
<td style="border:1px solid black;">
Stejné jako výše uvedené
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://go.microsoft.com/fwlink/?linkid=163843)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
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
Windows 7 pro 32bitové systémy
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
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=89d1fb78-68cd-48dd-afc2-15a79ebe9fde)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=b64bcc14-38a7-45b9-8f85-acc573777506)  
(Vysoký)
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
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=ad6f06d5-27db-445d-a8b2-c42adc90afc0)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows 7 pro 32bitové systémy](http://www.microsoft.com/downloads/details.aspx?familyid=35b85783-90df-4f67-a3cb-02351432133e)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 pro systémy s procesorem x64
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
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=10d9f7ac-65f4-437c-91cc-171632c69b0e)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=809e29f3-ec68-4a2b-b04e-11759dd16001)  
(Vysoký)
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
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=70cd0270-77e9-492a-82d9-798364640c10)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows 7 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=97010f2c-6c10-4fda-84fd-6c8749968db5)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="13" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-050**](http://go.microsoft.com/fwlink/?linkid=163970)
</td>
<td style="border:1px solid black;">
[**MS09-051**](http://go.microsoft.com/fwlink/?linkid=125438)
</td>
<td style="border:1px solid black;">
[**MS09-052**](http://go.microsoft.com/fwlink/?linkid=163913)
</td>
<td style="border:1px solid black;">
[**MS09-054**](http://go.microsoft.com/fwlink/?linkid=163979)
</td>
<td style="border:1px solid black;">
[**MS09-055**](http://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
<td style="border:1px solid black;">
[**MS09-053**](http://go.microsoft.com/fwlink/?linkid=164004)
</td>
<td style="border:1px solid black;">
[**MS09-056**](http://go.microsoft.com/fwlink/?linkid=163830)
</td>
<td style="border:1px solid black;">
[**MS09-057**](http://go.microsoft.com/fwlink/?linkid=163832)
</td>
<td style="border:1px solid black;">
[**MS09-058**](http://go.microsoft.com/fwlink/?linkid=162442)
</td>
<td style="border:1px solid black;">
[**MS09-059**](http://go.microsoft.com/fwlink/?linkid=163843)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Nízký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
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
Windows Server 2008 R2 pro systémy s procesorem x64
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
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f50307d6-7869-4996-9ff7-23f87d08994b)\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=bcd2b944-6852-48f2-820b-cce7d195e391)\*\*  
(Nízký)
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
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=ce78c019-ec08-4ec6-abec-334f5ec5cb76)\*  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=597ac3a7-e02d-49a5-9b8e-d097e867acea)\*  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 pro systémy s procesorem Itanium
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
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9b6a28ae-b3f2-42b0-8209-e3950ec37abb)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=85e76e55-3766-4ffe-9a18-8655de935b7c)  
(Nízký)
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
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=6442a77a-3c0d-4beb-b2d2-2885376c2135)  
(Vysoký)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=abc94857-37d8-4bb8-ad9e-46e687fca40e)  
(Vysoký)
</td>
</tr>
</table>
<p></p>
 
**Poznámky k systémům Windows Server 2008 a Windows Server 2008 R2**

**\*Instalace Server Core obsahující chybu zabezpečení.** Tato aktualizace se stejným hodnocením závažnosti se vztahuje k podporovaným edicím systému Windows Server 2008 nebo Windows Server 2008 R2, jak je uvedeno, s instalací pomocí volby pro instalaci Server Core nebo bez ní. Další informace o této možnosti instalace naleznete v článcích na webu služby MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) a [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008 a Windows Server 2008 R2; další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Instalace Server Core není touto chybou ovlivněna.** Chyby zabezpečení, které tato aktualizace řeší, nemají vliv na podporované edice systému Windows Server 2008 nebo Windows Server 2008 R2, jak je uvedeno, v případě instalace s využitím možnosti instalace Server Core. Další informace o této možnosti instalace naleznete v článcích na webu služby MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) a [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008 a Windows Server 2008 R2; další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Poznámka k bulletinu MS09-061**

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

**Poznámky k bulletinu MS09-062**

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

**Poznámka k bulletinu MS09-059**

<sup>[1]</sup>Tento operační systém obsahuje danou chybu zabezpečení pouze v případě, že je nainstalována oprava uvedená v článku KB968389 Rozšířená ochrana pro ověřování (viz [Informační zpravodaj zabezpečení společnosti Microsoft 973811](http://technet.microsoft.com/security/advisory/973811)). Další informace naleznete v části Nejčastější dotazy související s touto aktualizací zabezpečení v bulletinu [MS09-059](http://go.microsoft.com/fwlink/?linkid=163843).

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
<th colspan="3" style="border:1px solid black;">
Sady Microsoft Office, systémy a komponenty
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-060**](http://go.microsoft.com/fwlink/?linkid=160633)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=04878c2c-eb97-426f-be08-89036a6799db)  
(KB973702)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d)<sup>[2]</sup>
(KB974811)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=79e2b2e8-d5e8-4014-b489-720af2b5083d)  
(KB973705)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7)<sup>[3]</sup>
(KB972580)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Systém Microsoft Office 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2007 Service Pack 1 a Microsoft Office Outlook 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d39234a3-c62c-44ba-a626-3179a183ca09)  
(KB972363)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Systém Microsoft Office 2007 Service Pack 1 a systém Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Vysoký)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Další software sady Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-060**](http://go.microsoft.com/fwlink/?linkid=160633)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=920ee70b-c5c1-47b5-8f33-938ffe14eea4)  
(KB975365)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio Viewer
</td>
<td style="border:1px solid black;">
Microsoft Visio 2002 Viewer<sup>[1]</sup>
(Kritický)  
Microsoft Office Visio 2003 Viewer<sup>[1]</sup>
(Kritický)  
[Microsoft Office Visio Viewer 2007 Service Pack 1 a Microsoft Office Visio Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d20004c5-dd01-459e-8120-5f127e20c085)  
(KB973709)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio Viewer 2007 Service Pack 1 a Microsoft Office Visio Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d)<sup>[2]</sup>
(KB974811)  
(Vysoký)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer, Microsoft Office Excel Viewer a Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer 2003 Service Pack 3 a Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7)<sup>[3]</sup>
(KB972580)  
(Vysoký)  
[Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Vysoký)  
[PowerPoint Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Vysoký)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 1 a sada Microsoft Office Compatibility Pack pro formáty souborů aplikací Word, Excel a PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec)\[4\]  
(KB972581)  
(Důležitý)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=6f96de9a-62d8-428f-9567-51d55c129be6)  
(KB973636)  
(Vysoký)
</td>
</tr>
</table>
<p></p>
 
**Poznámky k bulletinu MS09-060**

<sup>[1]</sup>Společnost Microsoft doporučuje uživatelům aplikace Microsoft Visio Viewer 2002 a Microsoft Visio Viewer 2003, aby provedli upgrade na aplikaci Microsoft Office Visio Viewer 2007 Service Pack 2.

**Poznámky k bulletinu MS09-062**

<sup>[2]</sup>Tyto aktualizace jsou totožné.

<sup>[3]</sup>Tyto aktualizace jsou totožné.

\[4\]Tyto aktualizace jsou totožné.

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

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
<th colspan="2" style="border:1px solid black;">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
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
Aktualizace GDR  
Netýká se  
Aktualizace QFE:  
[SQL Server 2000 Reporting Services Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=33554f96-5af7-4683-a537-9db293b67b8d)  
(KB970899)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>
(KB970895)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>
(KB970896)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>
(KB970895)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>
(KB970896)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 pro systémy s procesorem Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23)<sup>[1]</sup>
(KB970895)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235)<sup>[1]</sup>
(KB970896)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 3
</td>
<td style="border:1px solid black;">
Aktualizace GDR  
[SQL Server 2005 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>
(KB970892)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>
(KB970894)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 3
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 x64 Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>
(KB970892)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 x64 Edition Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>
(KB970894)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 pro systémy s procesorem Itanium Service Pack 3
</td>
<td style="border:1px solid black;">
Aktualizace GDR:  
[SQL Server 2005 pro systémy s procesorem Itanium Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce)<sup>[2]</sup>
(KB970892)  
(Kritický)  
Aktualizace QFE:  
[SQL Server 2005 pro systémy s procesorem Itanium Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f)<sup>[2]</sup>
(KB970894)  
(Kritický)
</td>
</tr>
</table>
<p></p>
 
**Poznámka k bulletinu MS09-062**

<sup>[1]</sup>Uživatelé serveru SQL Server 2005 Service Pack 2 závislí na službě Reporting Services SharePoint by si také měli nainstalovat doplněk [Microsoft SQL Server 2005 Reporting Services pro Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=%20f4d4d0ae-e5d4-4ed1-8d78-7137578161ce&displaylang=en), který je k dispozici na webu služby Stažení softwaru.

<sup>[2]</sup>Uživatelé serveru SQL Server 2005 Service Pack 3 závislí na službě Reporting Services SharePoint by si také měli nainstalovat doplněk [Microsoft SQL Server 2005 Reporting Services pro Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=%20648766ac-2a35-4238-a3f4-c26d7077f2a9&displaylang=en), který je k dispozici na webu služby Stažení softwaru.

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

#### Vývojářské nástroje a software společnosti Microsoft

 
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
<th colspan="3" style="border:1px solid black;">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Žádné
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> při instalaci v počítačích Mac  
(KB970363)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> při instalaci ve všech vydáních klientských počítačů se systémem Microsoft Windows  
(KB970363)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](http://www.microsoft.com/silverlight/get-started/install/default.aspx)<sup>[1]</sup> při instalaci ve všech vydáních serverů se systémem Microsoft Windows\*\*  
(KB970363)  
(Mírný)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
Žádné
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9e3b52d3-b211-4d62-891c-ae8f2e4ffc6c)  
(KB971022)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e186aeed-e9d7-4a02-84b3-bbed116ca060)  
(KB971023)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=4fa10c93-ce20-43df-a725-ef4c77353747)  
(KB972221)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=b904dee8-8a26-43f8-8ca9-86ad12cfdb52)  
(KB972222)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 Service Pack 1 při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB971104)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e5d0d515-4b36-4025-bc6f-1c5cdf09e1af)  
při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB971104)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2 při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB971105)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2a930f56-59ac-49a6-830f-bfae7c540ec7)  
při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB971105)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-061**](http://go.microsoft.com/fwlink/?linkid=160527)
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=0dfaf300-2b53-4678-a779-0d805ddfe538)  
(KB971117)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=42ed040f-cf94-4754-b0b3-c8016fbcbe22)  
(KB971118)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 Redistributable Package Service Pack 1
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 Redistributable Package Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6aaa74bd-a46e-4478-b4e1-2063d18d2d42)  
(KB971119)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable: GDI+
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable: GDI+](http://www.microsoft.com/downloads/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(KB975337)  
(Stupeň závažnosti není určen<sup>[2]</sup>)
</td>
</tr>
</table>
<p></p>
 
**Poznámky k bulletinu MS09-061**

<sup>[1]</sup>Tato aktualizace slouží k upgradu aplikace Microsoft Silverlight 2 na Microsoft Silverlight 3, což řeší chybu zabezpečení popsanou v bulletinu.

**\*\*Instalace Server Core není touto chybou ovlivněna.** Chyby zabezpečení, které tato aktualizace řeší, nemají vliv na podporované edice systému Windows Server 2008 nebo Windows Server 2008 R2, jak je uvedeno, v případě instalace s využitím možnosti instalace Server Core. Další informace o této možnosti instalace naleznete v článcích na webu služby MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) a [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008 a Windows Server 2008 R2; další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

**Poznámky k bulletinu MS09-062**

<sup>[2]</sup>U této aktualizace není určen stupeň závažnosti, protože společnost Microsoft neoznačila žádné vektory útoků vztahující se k chybám zabezpečení projednávaným v tomto bulletinu specifickým pro tento software. Tato aktualizace zabezpečení se však nabízí vývojářům, kteří tento software používají, aby mohli vydat vlastní aktualizovanou verzi aplikací.

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

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
<th colspan="2" style="border:1px solid black;">
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-062**](http://go.microsoft.com/fwlink/?linkid=161342)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Client Security 1.0](http://www.microsoft.com/downloads/details.aspx?familyid=c0ce624c-8df3-4223-8a7a-5cba4ac334a8)  
při instalaci v systému Microsoft Windows 2000 Service Pack 4  
(KB975962)  
(Vysoký)
</td>
</tr>
</table>
<p></p>
 
**Poznámka k bulletinu MS09-062**

Více aktualizovaných souborů v rámci stejného identifikátoru bulletinu naleznete také v dalších kategoriích softwaru v rámci této části **Software obsahující tuto chybu a umístění aktualizací ke stažení**. Tento bulletin se vztahuje na více kategorií softwaru.

Nástroje a doporučené postupy zjišťování a nasazení
---------------------------------------------------


**Centrum zabezpečení**

Umožňuje správu aktualizací softwaru a zabezpečení, které je třeba nainstalovat na servery, stolní počítače a přenosné počítače v organizaci. Další informace naleznete na webu [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Další informace o zabezpečení produktů společnosti Microsoft nabízí web [Centrum zabezpečení TechNet](http://go.microsoft.com/fwlink/?linkid=21171). Tyto informace lze také získat kliknutím na nabídku „Nejnovější aktualizace zabezpečení“ na webu [Zabezpečení doma](http://go.microsoft.com/fwlink/?linkid=85102).

Aktualizace zabezpečení jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizace zabezpečení jsou také k dispozici na webu [služby Stažení softwaru](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.

Aktualizace zabezpečení lze stáhnout z katalogu služby [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). Služba Microsoft Update Catalog poskytuje katalog s možností vyhledávání obsahu dostupného prostřednictvím služeb Windows Update a Microsoft Update, včetně aktualizací zabezpečení, ovladačů a aktualizací Service Pack. Vyhledáváním pomocí čísla bulletinu zabezpečení (například MS07-036) můžete přidat všechny dostupné aktualizace do košíku (včetně různých jazykových verzí aktualizace) a stáhnout je do vybrané složky. Další informace o službě Microsoft Update Catalog najdete v části [Nejčastější dotazy týkající se služby Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Poznámka:** K 1. srpnu 2009 ukončí společnost Microsoft podporu webu Office Update a nástroje Office Update Inventory Tool. Nejnovější aktualizace produktů Microsoft Office bude přinášet web [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Další informace naleznete v části [O webu Microsoft Office Update: Nejčastější dotazy](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Doporučené postupy zjišťování a instalace**

Společnost Microsoft poskytuje doporučené postupy zjišťování a nasazení aktualizací zabezpečení. Tyto dokumenty obsahují doporučení a informace, které mohou odborníkům v oblasti IT pomoci porozumět, jak se používají různé nástroje pro detekci a nasazení aktualizací zabezpečení. Další informace získáte v [článku 961747 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Nástroj Microsoft Baseline Security Analyzer**

Pomocí nástroje Microsoft Baseline Security Analyzer (MBSA) mohou správci prohledávat místní i vzdálené systémy a zjistit tak, jestli v nich nechybí některé aktualizace zabezpečení nebo jestli v nastavení zabezpečení systému nedošlo k některým běžným chybám. Další informace o nástroji MBSA získáte na webu [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Služba Windows Server Update Services**

Pomocí služby Windows Server Update Services (WSUS) mohou správci systémů rychle a spolehlivě instalovat nejnovější důležité aktualizace zabezpečení pro systémy Windows 2000 a novější, sadu Office XP a novější, Exchange Server 2003 a SQL Server 2000 do systémů Windows 2000 a novějších.

Další informace o způsobu instalace této aktualizace zabezpečení pomocí služby Windows Server Update Services získáte na webu služby [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) představuje v rozlehlých sítích řešení pro správu aktualizací s rozsáhlými možnostmi konfigurace. Umožňuje správcům identifikovat počítače se systémem Windows, které vyžadují aktualizace zabezpečení, a provést řízenou instalaci těchto aktualizací v celé rozlehlé síti s minimálním dopadem na koncové uživatele. K dispozici je nyní nová verze nástroje SMS, System Center Configuration Manager 2007 (viz také webové stránky produktu [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Další informace o tom, jak mohou správci pomocí serveru SMS 2003 nasazovat aktualizace zabezpečení, získáte na webu [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Uživatelé služby SMS 2.0 mohou k nasazení aktualizací zabezpečení použít také nástroj SUIT (Security Update Inventory Tool). Další informace o serveru SMS získáte na webu [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Poznámka:** Služba SMS pomocí modulu Microsoft Baseline Security Analyzer poskytuje rozsáhlou podporu při zjišťování a nasazení aktualizací bulletinu zabezpečení. Tyto nástroje nemusí některé softwarové aktualizace zjistit. V takovém případě mohou správci použít funkce serveru SMS a nasměrovat aktualizace do určitých systémů. Další informace o tomto postupu najdete na webu [Nasazení aktualizací softwaru pomocí funkce Distribuce softwaru serveru SMS](http://go.microsoft.com/fwlink/?linkid=33341). Některé aktualizace zabezpečení vyžadují po restartování počítače oprávnění správce. Správci mohou k instalaci těchto aktualizací použít nástroj Elevated Rights Deployment Tool (k dispozici v sadě [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) a [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Nástroj Update Compatibility Evaluator a sada Application Compatibility Toolkit**

Aktualizace často zapisují do stejných souborů a nastavení registru požadovaných pro spouštění aplikací. To může způsobit nekompatibilitu a zvýšit dobu, po kterou trvá nasazení aktualizací zabezpečení. Testování a ověřování aktualizací systému Windows lze usnadnit pomocí součástí nástroje [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), které jsou dodávány se sadou [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Sada Application Compatibility Toolkit (ACT) obsahuje nezbytné nástroje a dokumentaci pro posouzení a zmírnění problémů s kompatibilitou aplikací před nasazením systému Microsoft Windows Vista, služby Windows Update, aktualizací zabezpečení společnosti Microsoft nebo nové verze aplikace Windows Internet Explorer ve vašem prostředí.

### Další informace

#### Nástroj pro odstranění škodlivého softwaru systému Microsoft Windows

Společnost Microsoft vydává aktualizovanou verzi Nástroje pro odstranění škodlivého softwaru systému Microsoft Windows na webu Windows Update, Microsoft Update, ve službě Windows Server Update Services a na webu služby Stažení softwaru.

#### Důležité aktualizace nesouvisející se zabezpečením na webu Microsoft Update (MU), Windows Update (WU) a ve službě Windows Server Update Services (WSUS)

Informace o aktualizacích nesouvisejících se zabezpečením na webu Windows Update a Microsoft Update naleznete na webové stránce:

-   [Článek 894199 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Popis služeb Software Update Services a Windows Server Update Services se mění v obsahu. Zahrnuje celý obsah systému Windows.
-   [Aktualizace vydané v uplynulých měsících pro službu Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Obsahuje přehled všech nových, revidovaných a opětovně vydaných aktualizací pro jiné produkty společnosti Microsoft, než je systém Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

Pro zlepšení ochrany dat svých zákazníků poskytuje společnost Microsoft informace o chybách v zabezpečení všem hlavním dodavatelům softwaru pro zabezpečení, a to vždy ještě před vydáním nové měsíční zprávy o aktualizaci zabezpečení. Dodavatelé softwaru pro zabezpečení tak mohou tyto informace o chybách v zabezpečení využít a poskytnout svým zákazníkům ochranu včasnou aktualizací svých programů a zařízení pro zabezpečení, jako jsou antivirové programy, síťové systémy pro detekci napadení či hostitelské systémy pro prevenci napadení. Informace o dostupnosti aktuálních prostředků aktivní ochrany od jednotlivých dodavatelů softwaru pro zabezpečení naleznete na stránkách aktivní ochrany jednotlivých partnerů programu MAPP. Seznam těchto partnerů naleznete na stránce [Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

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

-   [Matthieu Suichemu](http://www.msuiche.net/) z [nizozemského institutu soudních věd](http://www.nederlandsforensischinstituut.nl/) za oznámení chyby popsané v bulletinu MS09-050.
-   Ivanu Fratricovi z organizace [Zero Day Initiative](http://www.zerodayinitiative.com/) a Junovi Xie ze společnosti [McAfee Avert Labs](http://www.avertlabs.com/) za oznámení chyby popsané v bulletinu MS09-051.
-   Vinayi Anantharamanovi ze společnosti [Adobe Systems, Inc.](http://www.adobe.com/) za oznámení chyby popsané v bulletinu MS09-051.
-   Yamatu Liovi ze společnosti [Palo Alto Networks](http://www.paloaltonetworks.com/) za oznámení chyby popsané v bulletinu MS09-052.
-   Uživateli s pseudonymem Skylined ze společnosti [Google Inc.](http://www.google.com/) za oznámení chyby popsané v bulletinu MS09-054.
-   Marku Dowdovi ze společnosti [IBM ISS X-Force](http://www.iss.net/) za oznámení chyby popsané v bulletinu MS09-054.
-   Společnosti [TippingPoint](http://www.tippingpoint.com/) a organizaci [Zero Day Initiative](http://www.zerodayinitiative.com/) za oznámení chyby popsané v bulletinu MS09-054.
-   Samu Thomasovi ze společnosti eshu.co.uk, spolupracujícímu se společností [TippingPoint](http://www.tippingpoint.com/) a organizací [Zero Day Initiative](http://www.zerodayinitiative.com/), za oznámení chyby popsané v bulletinu MS09-054.
-   Ianu Wrightovi a Jean-Lucu Giraudovi ze společnosti [Citrix](http://www.citrix.com/) za spolupráci na řešení chyby zabezpečení popsané v bulletinu MS09-056.
-   Danovi Kaminskymu ze společnosti [IOActive](http://www.ioactive.com/) za oznámení dvou chyb popsaných v bulletinu MS09-056.
-   Yamatu Liovi ze společnosti [Palo Alto Networks](http://www.paloaltonetworks.com/) za oznámení chyby popsané v bulletinu MS09-057.
-   Tavisovi Ormandymu a Neelu Mehtovi ze společnosti [Google Inc.](http://www.google.com/) za oznámení dvou chyb popsaných v bulletinu MS09-058.
-   Týmu [NSFocus Security Team](http://www.nsfocus.com/) za oznámení chyby popsané v bulletinu MS09-058.
-   Davidovi Deweymu ze společnosti [IBM ISS X-Force](http://www.iss.net/) za oznámení chyby popsané v bulletinu MS09-060.
-   Ryanu Smithovi ze společnosti [VeriSign iDefense Labs](http://labs.idefense.com/) za oznámení dvou chyb popsaných v bulletinu MS09-060.
-   [Pavlu Minaevovi](http://int19h.org/) za oznámení chyby popsané v bulletinu MS09-061.
-   Jeroenu Frijtersovi ze společnosti [Sumatra](http://www.sumatra.nl/) za oznámení chyby popsané v bulletinu MS09-061.
-   Yamatu Liovi ze společnosti [Palo Alto Networks](http://www.paloaltonetworks.com/) za oznámení chyby popsané v bulletinu MS09-062.
-   Thomasi Garnierovi ze společnosti [SkyRecon](http://www.skyrecon.com/) za oznámení chyby popsané v bulletinu MS09-062.
-   Uživateli s pseudonymem Wushi ze společnosti [VeriSign iDefense Labs](http://labs.idefense.com/) za oznámení chyby popsané v bulletinu MS09-062.
-   Ivanu Fratricovi z organizace [Zero Day Initiative](http://www.zerodayinitiative.com/) za oznámení chyby popsané v bulletinu MS09-062.
-   Tavisu Ormandymu ze společnosti [Google Inc.](http://www.google.com/) za oznámení dvou chyb popsaných v bulletinu MS09-062.
-   Carlu Di Datovi (alias shinnai) za oznámení chyby popsané v bulletinu MS09-062.
-   Marsu Pilamimu ze společnosti [VeriSign iDefense Labs](http://labs.idefense.com/) za oznámení chyby popsané v bulletinu MS09-062.
-   Carstenu H. Eiramovi ze společnosti [Secunia](http://secunia.com/) za oznámení chyby popsané v bulletinu MS09-062.

#### Technická podpora

-   Uvedený software byl testován za účelem zjištění, kterých verzí se chyba týká. U dalších verzí skončila časově omezená podpora. Pokud chcete zjistit dobu, po kterou je pro určitou verzi softwaru poskytována podpora, navštivte web [Zásady poskytování technické podpory pro produkty společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Zákazníci mohou získat technickou podporu na webu [služby technické podpory společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21131). Hovory související s aktualizacemi zabezpečení jsou bezplatné. Další informace o dostupných možnostech technické podpory naleznete na webu [Pomoc a podpora společnosti Microsoft](http://support.microsoft.com/).
-   Mezinárodní zákazníci získají podporu u místních zastoupení společnosti Microsoft. Technická podpora související s aktualizacemi zabezpečení je bezplatná. Další informace o možnostech kontaktování společnosti Microsoft v případě potřeby technické podpory získáte na [webu mezinárodní technické podpory](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zřeknutí se záruky

Informace ve znalostní bázi Microsoft Knowledge Base jsou poskytovány tak, jak jsou, bez jakékoli záruky. Společnost Microsoft neposkytuje žádné záruky, výslovně uvedené či mlčky předpokládané, včetně záruk obchodovatelnosti a vhodnosti pro určitý účel. Společnost Microsoft ani její dodavatelé nenesou v žádném případě zodpovědnost za žádné škody, včetně přímých, nepřímých, náhodných či následných škod, ztráty zisku či zvláštních škod, a to ani v případě, že byli na možnost takových škod upozorněni. V některých zemích a právních řádech není dovoleno vyloučit nebo omezit odpovědnost, proto se výše uvedené omezení na vás nemusí vztahovat.

#### Revize

-   V1.0 (13. října 2009): Souhrnný bulletin byl publikován.
-   V1.1 (14. října 2009): V bulletinu MS09-055 byl opraven odkaz ke stažení pro edici Windows XP x64 Service Pack 2.
-   V1.2 (18. října 2009): Byla revidována část Shrnutí pro bulletin MS09-054, do níž byly přidány informace pro uživatele aplikace Firefox.
-   V2.0 (28. října 2009): Do seznamu softwaru obsahujícího chybu zabezpečení, uvedeného v bulletinu MS09-062, byly přidány aplikace Microsoft Office Visio Viewer 2007, Microsoft Office Visio Viewer 2007 Service Pack 1 a Microsoft Office Visio Viewer 2007 Service Pack 2. Dále byly do bulletinu MS09-062 přidány poznámky pro uživatele serveru SQL Server 2005 závislé na službě Reporting Services SharePoint.
-   V3.0 (2. listopadu 2009): Bulletin byl revidován oznámením dostupnosti opravy hotfix pro bulletin MS09-054, která řeší problémy s kompatibilitou aplikací. Zákazníci, kteří již tuto aktualizaci nainstalovali, mohou provést instalaci opravy hotfix uvedené v článku 976749 znalostní báze Microsoft Knowledge Base.
-   V3.1 (4. listopadu 2009): Z bulletinů zabezpečení MS09-060 a MS09-062 byly odebrány chybné odkazy označující původní vydání aplikace Microsoft Office Visio Viewer 2007 jako software obsahující chybu.
-   V4.0 (10. listopadu 2009): Bulletin byl revidován oznámením nového vydání aktualizace programu Správce zvukové komprese v systému Microsoft Windows 2000 Service Pack 4 v bulletinu zabezpečení MS09-051, sloužícího k opravě chyby detekce. Jedná se pouze o změnu detekce, v binárních souborech nedošlo ke změně. Zákazníci, kteří systém úspěšně aktualizovali, nemusí tuto aktualizaci znovu instalovat.
-   V4.1 (12. ledna 2010): Ze seznamu softwaru obsahujícího chybu zabezpečení pro bulletin MS09-062 byly odebrány aplikace Microsoft Expression Web, Microsoft Expression Web 2, Microsoft Office Groove 2007 a Microsoft Office Groove 2007 Service Pack 1.
-   V4.2 (22. června 2010): Ze seznamu komponent obsahujících chybu zabezpečení pro systémy Windows 7 a Windows Server 2008 R2, uvedeného v bulletinu MS09-061, bylo odebráno rozhraní .NET Framework 1.1 Service Pack 1.

*Built at 2014-04-18T01:50:00Z-07:00*
