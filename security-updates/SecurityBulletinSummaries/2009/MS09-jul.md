---
TOCTitle: 'MS09-JUL'
Title: 'Souhrnný bulletin zabezpečení společnosti Microsoft, červenec 2009'
ms:assetid: 'ms09-jul'
ms:contentKeyID: 61223987
ms:mtpsurl: 'https://technet.microsoft.com/cs-CZ/library/ms09-jul(v=Security.10)'
---

 

Souhrnný bulletin zabezpečení společnosti Microsoft, červenec 2009
==================================================================

Publikováno: 14. července 2009 | Aktualizováno: 9. března 2010

**Verze:** 8.0

Tento souhrnný bulletin uvádí bulletiny zabezpečení vydané v červenci 2009.

Spolu s vydáním bulletinů pro červenec 2009 nahrazuje tento souhrnný bulletin předběžné oznámení o bulletinu vydané 9. července 2009 a mimořádné předběžné oznámení o bulletinu původně vydané 24. července 2009. Další informace o službě předběžného oznámení o bulletinech naleznete v části [Předběžné oznámení o bulletinech zabezpečení společnosti Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Informace o tom, jak dostávat automatická oznámení o vydání nových bulletinů zabezpečení společnosti Microsoft, naleznete na webu [Zasílání technických oznámení o zabezpečení společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21163).

Pro zodpovězení zákaznických dotazů týkajících se pravidelně plánovaných bulletinů uspořádala společnost Microsoft 15. července 2009 v 11:00 časového pásma Tichomoří (USA a Kanada) webové vysílání. Toto webové vysílání je dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://technet.microsoft.com/security/bulletin/summary).

Jako součást mimořádných bulletinů zabezpečení přidaných k verzi 2.0 tohoto souhrnného bulletinu MS09-034 a MS09-035 uspořádá 28. července ve 13:00 časového pásma Tichomoří (USA a Kanada) a v 16:00 časového pásma Tichomoří (USA a Kanada) společnost Microsoft dva webové přenosy pro zodpovězení zákaznických dotazů týkajících se těchto bulletinů. Přihlaste se k webovému přenosu konanému [28. července ve 13:00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us) a [28. července v 16:00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us). Později budou tyto webové přenosy dostupné na požádání. Další informace získáte v [souhrnných bulletinech zabezpečení společnosti Microsoft a webovém vysílání](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení integrovaného modulu písma OpenType umožňují vzdálené spuštění kódu (961371)</strong><br />
<br />
Tato aktualizace zabezpečení řeší dvě soukromými osobami oznámené chyby zabezpečení v součásti systému Microsoft Windows, a to integrovaném modulu písma Embedded OpenType (EOT). Tyto chyby zabezpečení by mohly umožnit vzdálené spuštění kódu. Útočník, který by úspěšně zneužil některou z těchto chyb zabezpečení, by mohl převzít úplnou vzdálenou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v rozhraní Microsoft DirectShow umožňují vzdálené spuštění kódu (971633)</strong><br />
<br />
Tato aktualizace zabezpečení řeší jednu veřejně známou a dvě soukromými osobami oznámené chyby zabezpečení v rozhraní Microsoft DirectShow. Tyto chyby zabezpečení umožňují vzdálené spuštění kódu, pokud uživatel otevře speciálně vytvořený mediální soubor QuickTime. Útočník, který by úspěšně zneužil některou z těchto chyb zabezpečení, by mohl získat stejná uživatelská práva, jaká má místní uživatel. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td style="border:1px solid black;"><strong>Kumulativní aktualizace zabezpečení dezaktivačních bitů ActiveX (973346)</strong><br />
<br />
Tato aktualizace zabezpečení řeší soukromou osobou oznámenou chybu zabezpečení, k jejímuž zneužití v současné době dochází. Chyba zabezpečení ovládacího prvku videa Microsoft ActiveX by mohla umožnit vzdálené spuštění kódu v případě, že uživatel pomocí aplikace Internet Explorer zobrazí speciálně vytvořenou webovou stránku umožňující vytváření instancí ovládacího prvku ActiveX. Tento ovládací prvek ActiveX nebyl nikdy určen pro vytváření instancí v aplikaci Internet Explorer. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (972260)</strong><br />
<br />
Tato aktualizace zabezpečení je mimořádně vydána spolu s bulletinem zabezpečení společnosti Microsoft MS09-035, který popisuje chyby zabezpečení v těch součástech a ovládacích prvcích, které byly vyvinuty pomocí chybných verzí knihovny Microsoft Active Template Library (ATL). V rámci zvýšení ochrany tato aktualizace zabezpečení aplikace Internet Explorer pomáhá snížit známé způsoby útoku v rámci aplikace Internet Explorer těch součástí a ovládacích prvků, které byly vyvinuty pomocí chybných verzí knihovny ATL, jak je popsáno v informačním zpravodaji zabezpečení společnosti Microsoft (973882) a bulletinu zabezpečení společnosti Microsoft MS09-035.<br />
<br />
Tato aktualizace zabezpečení dále řeší tři soukromě oznámené chyby zabezpečení aplikace Internet Explorer. Tyto chyby zabezpečení mohou umožňovat vzdálené spuštění kódu, pokud uživatel pomocí aplikace Internet Explorer zobrazí speciálně vytvořenou webovou stránku. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritický</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení nástroje Virtual PC a Virtual Server umožňuje zvýšení úrovně oprávnění (969856)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení nástroje Microsoft Virtual PC a Microsoft Virtual Server, kterou oznámila soukromá osoba. Útočník, který by tuto chybu zabezpečení úspěšně zneužil, by mohl spustit libovolný kód a získat úplnou kontrolu nad postiženým hostovaným operačním systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Virtual PC, Virtual Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení nástroje Microsoft ISA Server 2006 umožňuje zvýšení úrovně oprávnění (970953)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení nástroje Microsoft Internet Security and Acceleration (ISA) Server 2006 oznámenou soukromou osobou. Chyba zabezpečení by mohla vést ke zvýšení úrovně oprávnění, pokud by útočník dokázal napodobit uživatelský účet správce nástroje ISA Server, který je nakonfigurován pro ověření Radius One Time Password (OTP) a delegování ověření Kerberos Constrained Delegation (delegování s vynuceným použitím protokolu Kerberos).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Zvýšení úrovně oprávnění</td>
<td style="border:1px solid black;">Vyžaduje restartování</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td style="border:1px solid black;"><strong>Chyba zabezpečení v aplikaci Microsoft Office Publisher umožňuje vzdálené spuštění kódu (969516)</strong><br />
<br />
Tato aktualizace zabezpečení řeší chybu zabezpečení aplikace Microsoft Office Publisher oznámenou soukromou osobou, která by mohla umožnit vzdálené spuštění kódu v případě, že uživatel otevře speciálně vytvořený soubor aplikace Publisher. Útočník, který by tuto chybu zabezpečení zneužil, by mohl získat úplnou kontrolu nad postiženým systémem. Útočník by tak mohl instalovat programy, zobrazovat, měnit či odstraňovat data nebo vytvářet nové účty s úplnými uživatelskými právy. Uživatelé, jejichž účty jsou konfigurovány tak, aby měli v systému méně uživatelských práv, by byli vystaveni menšímu riziku než uživatelé s uživatelskými právy správce.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Důležité</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Chyby zabezpečení v knihovně Visual Studio Active Template Library umožňují vzdálené spuštění kódu (969706)</strong><br />
<br />
Tato aktualizace zabezpečení řeší několik soukromě oznámených chyb zabezpečení ve veřejných verzích knihovny Microsoft Active Template Library (ATL), které jsou součástí aplikace Visual Studio. Tato aktualizace zabezpečení je navržena zejména pro vývojáře součástí a ovládacích prvků. Vývojáři vytvářející a distribuující součásti a ovládací prvky využívající knihovnu ATL by si měli nainstalovat aktualizaci poskytnutou v tomto bulletinu. Tito vývojáři by měli postupovat dle uvedených pokynů, aby vytvořili a distribuovali svým zákazníkům součásti a ovládací prvky, které nepodléhají chybám zabezpečení popsaným v tomto bulletinu zabezpečení.<br />
<br />
Tento bulletin zabezpečení popisuje chyby zabezpečení, které by mohly umožnit vzdálené spuštění kódu, pokud uživatel načte součást nebo ovládací prvek vytvořený pomocí knihovny ATL chybné verze.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Mírný</a><br />
Vzdálené spuštění kódu</td>
<td style="border:1px solid black;">Může vyžadovat restartování</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
</tbody>
</table>
<p></p>

  
Index zneužitelnosti  
--------------------
  
 
Následující tabulka uvádí hodnocení zneužitelnosti každé chyby zabezpečení uvedené v tomto měsíci. Chyby zabezpečení jsou řazeny podle čísla jednotlivých bulletinů (ID bulletinu) a chyb (ID CVE).
  
**Jak pracovat s touto tabulkou**
  
V této tabulce zjistíte, jaká je pravděpodobnost vydání funkčního zneužitelného kódu během 30 dní od vydání tohoto bulletinu zabezpečení pro všechny aktualizace zabezpečení, které bude třeba nainstalovat. Všechna níže uvedená hodnocení zvažte na základě vaší specifické konfigurace a podle závěrů hodnocení nastavte priority pro zavádění jednotlivých aktualizací. Další informace o významu těchto hodnocení a způsobu jejich stanovení najdete v indexu zneužitelnosti [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| ID bulletinu                                              | Název bulletinu                                                                                             | ID CVE                                                                           | Hodnocení indexu zneužitelnosti                                                                                                | Hlavní poznámky                                                                       |  
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Chyby zabezpečení v rozhraní Microsoft DirectShow umožňují vzdálené spuštění kódu (971633)                  | [CVE-2009-1537](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | **V současné době dochází ke zneužití této chyby zabezpečení v prostředí Internetu.** |  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Chyby zabezpečení v rozhraní Microsoft DirectShow umožňují vzdálené spuštění kódu (971633)                  | [CVE-2009-1538](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                               |  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Chyby zabezpečení v rozhraní Microsoft DirectShow umožňují vzdálené spuštění kódu (971633)                  | [CVE-2009-1539](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                               |  
| [MS09-029](http://go.microsoft.com/fwlink/?linkid=139788) | Chyby zabezpečení integrovaného modulu písma OpenType umožňují vzdálené spuštění kódu (961371)              | [CVE-2009-0231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                               |  
| [MS09-029](http://go.microsoft.com/fwlink/?linkid=139788) | Chyby zabezpečení integrovaného modulu písma OpenType umožňují vzdálené spuštění kódu (961371)              | [CVE-2009-0232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                               |  
| [MS09-030](http://go.microsoft.com/fwlink/?linkid=147424) | Chyba zabezpečení v aplikaci Microsoft Office Publisher umožňuje vzdálené spuštění kódu (969516)            | [CVE-2009-0566](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                               |  
| [MS09-031](http://go.microsoft.com/fwlink/?linkid=154993) | Chyba zabezpečení nástroje Microsoft ISA Server 2006 umožňuje zvýšení úrovně oprávnění (970953)             | [CVE-2009-1135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | (Žádné)                                                                               |  
| [MS09-032](http://go.microsoft.com/fwlink/?linkid=157386) | Kumulativní aktualizace zabezpečení dezaktivačních bitů ActiveX (973346)                                    | [CVE-2008-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | **V současné době dochází ke zneužití této chyby zabezpečení v prostředí Internetu.** |  
| [MS09-033](http://go.microsoft.com/fwlink/?linkid=153891) | Chyba zabezpečení nástroje Virtual PC a Virtual Server umožňuje zvýšení úrovně oprávnění (969856)           | [CVE-2009-1542](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | Nekonsistentní výsledky zneužití umožňují spuštění funkčního kódu.                    |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (972260)                                 | [CVE-2009-1917](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | Spuštění funkčního kódu je snadné a spolehlivé.                                       |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (972260)                                 | [CVE-2009-1918](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | Nekonsistentní výsledky zneužití umožňují spuštění funkčního kódu.                    |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (972260)                                 | [CVE-2009-1919](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nekonsistentní kód zneužití je pravděpodobný              | Nekonsistentní výsledky zneužití umožňují spuštění funkčního kódu.                    |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Chyby zabezpečení v knihovně Visual Studio Active Template Library umožňují vzdálené spuštění kódu (969706) | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | Spuštění funkčního kódu je snadné a spolehlivé.                                       |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Chyby zabezpečení v knihovně Visual Studio Active Template Library umožňují vzdálené spuštění kódu (969706) | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konsistentní kód zneužití je pravděpodobný                | Spuštění funkčního kódu je snadné a spolehlivé.                                       |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Chyby zabezpečení v knihovně Visual Studio Active Template Library umožňují vzdálené spuštění kódu (969706) | [CVE-2009-2495](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Vytvoření funkčního zneužitelného kódu není pravděpodobné | Chyba umožňující pouze přístup k informacím bez hrozby spuštění kódu.                 |
  
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
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2)  
(Kritický)
</td>
<td style="border:1px solid black;">
[DirectX 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3)  
(Kritický)  
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d)\*\*\*  
(Kritický)  
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda)\*\*\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72)  
(Stupeň závažnosti není určen\*\*)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd)  
(Kritický)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282)  
(Kritický)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b)  
(Kritický)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80)\*\*\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 a Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00)  
(Kritický)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1)  
(Kritický)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4)\*\*\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48)  
(Kritický)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350)  
(Kritický)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab)  
(Kritický)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c)  
(Kritický)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc)\*\*\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9)  
(Mírný)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af)  
(Mírný)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606)  
(Mírný)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935)  
(Kritický)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e)\*\*\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2)  
(Mírný)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d)  
(Mírný)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd)  
(Mírný)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 pro systémy s procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130)  
(Kritický)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042)\*\*\*\*  
(Kritický)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 pro systémy s procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5)  
(Mírný)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc)  
(Mírný)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071)  
(Mírný)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Kritický**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 a Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45)  
(Stupeň závažnosti není určen\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43)  
(Kritický)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 a Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7)  
(Stupeň závažnosti není určen\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6)  
(Kritický)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb)  
(Kritický)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
<td style="border:1px solid black;">
Žádné
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro 32bitové systémy a Windows Server 2008 pro 32bitové systémy Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995)\*  
(Stupeň závažnosti není určen\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead)\*  
(Mírný)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae)\*  
(Mírný)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4)\*  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem x64 a Windows Server 2008 pro systémy s procesorem x64 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0)\*  
(Stupeň závažnosti není určen\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516)\*  
(Mírný)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93)\*  
(Mírný)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d)  
(Kritický)
</td>
<td style="border:1px solid black;">
Netýká se
</td>
<td style="border:1px solid black;">
[Windows Server 2008 pro systémy s procesorem Itanium a Windows Server 2008 pro systémy s procesorem Itanium Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a)  
(Stupeň závažnosti není určen\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d)  
(Mírný)
</td>
</tr>
</table>
<p></p>

 
**Poznámka k systému Windows Server 2008**

**\*Instalace Server Core operačního systému Windows Server 2008 neobsahující tuto chybu.** Chyby zabezpečení, které tato aktualizace řeší, nemají vliv na podporované edice systému Windows Server 2008, jestliže byl systém Windows Server 2008 instalován s využitím možnosti instalace Server Core. Více informací o této možnosti instalace naleznete v části [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Možnost instalace Server Core se nevztahuje na určité edice systému Windows Server 2008. Další informace naleznete v části [Porovnání možností instalace Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Poznámka k bulletinu MS09-032**

\*\*U této aktualizace není určen stupeň závažnosti, neboť chyba zabezpečení uvedená v tomto bulletinu se netýká tohoto softwaru. Nicméně v rámci zvýšení ochrany proti eventuálním dalším útokům doporučuje společnost Microsoft uživatelům tohoto softwaru tuto aktualizaci zabezpečení použít.

**Poznámky k bulletinu MS09-028**

\*\*\*Aktualizace rozhraní DirectX 8.1 se týká rovněž verze DirectX 8.1b.

\*\*\*\*Aktualizace rozhraní DirectX 9.0 se týká rovněž verzí DirectX 9.0a, DirectX 9.0b a DirectX 9.0c.

#### Sady Microsoft Office a jejich software

 
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
Sady Microsoft Office, systémy a komponenty
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-030**](http://go.microsoft.com/fwlink/?linkid=147424)
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
Systém Microsoft Office 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8)  
(KB969693)  
(Důležitý)
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
<th colspan="2" style="border:1px solid black;">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-035**](http://go.microsoft.com/fwlink/?linkid=158131)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Mírný**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e)  
(KB971089)  
(Mírný)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197)  
(KB971090)  
(Mírný)  
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42)\*  
(KB973673)  
(Mírný)  
[Microsoft Visual Studio 2005 Service Pack 1 64bitová verze provozující nástroje softwaru Visual C++](http://www.microsoft.com/downloads/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2)  
(KB973830)  
(Mírný)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Embedded CE 6.0
</td>
<td style="border:1px solid black;">
[Windows Embedded CE 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8)\*\*  
(KB974616)  
(Mírný)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c)  
(KB971091)  
(Mírný)  
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd)\*  
(KB973674)  
(Mírný)  
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb)  
(KB971092)  
(Mírný)  
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f)\*  
(KB973675)  
(Mírný)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2005 Service Pack 1 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2)  
(KB973544)  
(Mírný)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2008 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93)  
(KB973551)  
(Mírný)  
[Microsoft Visual C++ 2008 Service Pack 1 Redistributable Package](http://www.microsoft.com/downloads/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c)  
(KB973552)  
(Mírný)
</td>
</tr>
</table>
<p></p>

 
**Poznámky k bulletinu MS09-035**

\*Pro mobilní aplikace s využitím knihovny ATL pro inteligentní zařízení

\*\*Nainstaluje měsíční aktualizaci systému Windows Embedded CE 6.0 (prosinec 2009). Tento balíček aktualizace je dostupný pouze prostřednictvím webu služby Stažení softwaru.

#### Microsoft Server and Security Software

 
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
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-031**](http://go.microsoft.com/fwlink/?linkid=154993)
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
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19)  
(KB970811)  
(Důležitý)  
[Microsoft Internet Security and Acceleration Server 2006 Supportability Update](http://www.microsoft.com/downloads/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476)  
(KB970811)  
(Důležitý)  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5)  
(KB971143)  
(Důležitý)
</td>
</tr>
</table>
<p></p>

 

#### Virtualizační software Microsoft

 
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
Microsoft Virtual PC
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://go.microsoft.com/fwlink/?linkid=153891)
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
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2004 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad)  
(KB969856)  
(Důležitý)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2007
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(Důležitý)  
[Microsoft Virtual PC 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(Důležitý)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2007 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(Důležitý)  
[Microsoft Virtual PC 2007 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(Důležitý)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Microsoft Virtual Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identifikátor bulletinu**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://go.microsoft.com/fwlink/?linkid=153891)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Celkový stupeň závažnosti**
</td>
<td style="border:1px solid black;">
[**Vysoký**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005](http://www.microsoft.com/downloads/details.aspx?familyid=092a389a-2296-4c3b-a160-2523154ec764)  
(KB969856)  
(Důležitý)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(Důležitý)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(Důležitý)
</td>
</tr>
</table>
<p></p>

 

Nástroje a doporučené postupy zjišťování a nasazení
---------------------------------------------------

 
**Centrum zabezpečení**

Umožňuje správu aktualizací softwaru a zabezpečení, které je třeba nainstalovat na servery, stolní počítače a přenosné počítače v organizaci. Další informace naleznete na webu [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Další informace o zabezpečení produktů společnosti Microsoft nabízí web [Centrum zabezpečení TechNet](http://go.microsoft.com/fwlink/?linkid=21171). Tyto informace lze také získat kliknutím na nabídku „Nejnovější aktualizace zabezpečení“ na webu [Zabezpečení doma](http://go.microsoft.com/fwlink/?linkid=85102).

Aktualizace zabezpečení jsou k dispozici na webu [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizace zabezpečení jsou také k dispozici na webu [služby Stažení softwaru](http://go.microsoft.com/fwlink/?linkid=21129). Nejsnadněji je naleznete hledáním podle klíčových slov aktualizace zabezpečení.

Aktualizace zabezpečení lze stáhnout z katalogu služby [Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=96155). Služba Microsoft Update Catalog poskytuje katalog s možností vyhledávání obsahu dostupného prostřednictvím služeb Windows Update a Microsoft Update, včetně aktualizací zabezpečení, ovladačů a aktualizací Service Pack. Vyhledáváním pomocí čísla bulletinu zabezpečení (například MS07-036) můžete přidat všechny dostupné aktualizace do košíku (včetně různých jazykových verzí aktualizace) a stáhnout je do vybrané složky. Další informace o službě Microsoft Update Catalog najdete v části [Nejčastější dotazy týkající se služby Microsoft Update Catalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Poznámka:** Počínaje 1. srpnem 2009 ukončí společnost Microsoft podporu webu Office Update a nástroje Office Update Inventory Tool. Nejnovější aktualizace produktů Microsoft Office bude přinášet web [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Další informace naleznete v části [O webu Microsoft Office Update: Nejčastější dotazy](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

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

-   [Článek 894199 znalostní báze Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Popis služeb Software Update Services a Windows Server Update Services se mění v obsahu. Zahrnuje celý obsah systému Windows.
-   [Nové, revidované a vydané aktualizace pro jiné produkty společnosti Microsoft, než je systém Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

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

-   Thomasi Garnierovi ze společnosti [SkyRecon](http://www.skyrecon.com/) a Zhengu Wenbinovi, Liu Qiovi a Songu Shenleiovi z [centra zabezpečení společnosti Qihoo 360](http://www.360.cn/) za oznámení chyby popsané v bulletinu MS09-028.
-   Yamatu Liovi ze společnosti [Palo Alto Networks](http://www.paloaltonetworks.com/) za oznámení chyby popsané v bulletinu MS09-028.
-   Aaronu Portnoyovi ze společnosti [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) a anonymnímu výzkumníkovi spolupracujícímu s organizací [Zero Day Initiative](http://www.zerodayinitiative.com/) společnosti TippingPoint, Thomasi Garnierovi ze společnosti [SkyRecon](http://www.skyrecon.com/) a Yamatu Liovi ze společnosti [Palo Alto Networks](http://www.paloaltonetworks.com/) za oznámení chyby popsané v bulletinu MS09-028.
-   Společnosti [VeriSign iDefense Labs](http://labs.idefense.com/) za oznámení chyby popsané v bulletinu MS09-029.
-   Tavisu Ormandymu ze společnosti [Google Inc.](http://www.google.com) za oznámení chyby popsané v bulletinu MS09-029.
-   Thomasi Garnierovi za oznámení chyby popsané v bulletinu MS09-029.
-   Lionelu d'Hauenensovi ze společnosti [Labo Skopia](http://www.laboskopia.com/), spolupracujícímu se společností [VeriSign iDefense Labs](http://www.idefense.com/), za oznámení chyby popsané v bulletinu MS09-030.
-   Ryanu Smithovi a Alexu Wheelerovi ze společnosti [IBM ISS X-Force](http://www.iss.net/) za brzké oznámení chyby popsané v bulletinu MS09-032.
-   Julienu Tinnesovi a Tavisu Ormandymu ze společnosti [Google Inc.](http://www.google.com/) za oznámení chyby popsané v bulletinu MS09-033.
-   Peteru Vreugdenhilovi ze společnosti [VeriSign iDefense Labs](http://labs.idefense.com/) za oznámení chyby popsané v bulletinu MS09-034.
-   Wushimu a Lingovi ze skupiny [team509](http://www.team509.com/), spolupracujícím se společností [TippingPoint](http://www.tippingpoint.com/) a organizací [Zero Day Initiative](http://www.zerodayinitiative.com/), za oznámení chyby popsané v bulletinu MS09-034.
-   Peteru Vreugdenhilovi, spolupracujícímu se společností [TippingPoint](http://www.tippingpoint.com/) a organizací [Zero Day Initiative](http://www.zerodayinitiative.com/), za oznámení chyby popsané v bulletinu MS09-034.
-   Davidu Deweymu ze společnosti [IBM ISS X-Force](http://www.iss.net/), za oznámení chyby popsané v bulletinu MS09-035.
-   Ryanu Smithovi ze společnosti [VeriSign iDefense Labs](http://labs.idefense.com/) za oznámení dvou chyb popsaných v bulletinu MS09-035.

#### Technická podpora

-   Uvedený software byl testován za účelem zjištění, kterých verzí se chyba týká. U dalších verzí skončila časově omezená podpora. Pokud chcete zjistit dobu, po kterou je pro určitou verzi softwaru poskytována podpora, navštivte web [Zásady poskytování technické podpory pro produkty společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Zákazníci mohou získat technickou podporu na webu [služby technické podpory společnosti Microsoft](http://go.microsoft.com/fwlink/?linkid=21131). Hovory související s aktualizacemi zabezpečení jsou bezplatné. Další informace o dostupných možnostech technické podpory naleznete na webu [Pomoc a podpora společnosti Microsoft](http://support.microsoft.com/).
-   Mezinárodní zákazníci získají podporu u místních zastoupení společnosti Microsoft. Technická podpora související s aktualizacemi zabezpečení je bezplatná. Další informace o možnostech kontaktování společnosti Microsoft v případě potřeby technické podpory získáte na [webu mezinárodní technické podpory](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zřeknutí se záruky

Informace ve znalostní bázi Microsoft Knowledge Base jsou poskytovány tak, jak jsou, bez jakékoli záruky. Společnost Microsoft neposkytuje žádné záruky, výslovně uvedené či mlčky předpokládané, včetně záruk obchodovatelnosti a vhodnosti pro určitý účel. Společnost Microsoft ani její dodavatelé nenesou v žádném případě zodpovědnost za žádné škody, včetně přímých, nepřímých, náhodných či následných škod, ztráty zisku či zvláštních škod, a to ani v případě, že byli na možnost takových škod upozorněni. V některých zemích a právních řádech není dovoleno vyloučit nebo omezit odpovědnost, proto se výše uvedené omezení na vás nemusí vztahovat.

#### Revize

-   V1.0 (14. července 2009): Souhrnný bulletin byl publikován.
-   V1.1 (15. července 2009): Aktualizováno shrnutí pro bulletin MS09-032, opraven požadavek na restartování pro bulletin MS09-029 a provedeny různé úpravy.
-   V2.0 (28. července 2009): Byly přidány bulletiny zabezpečení společnosti Microsoft MS09-034: Kumulativní aktualizace zabezpečení pro aplikaci Internet Explorer (972260) a MS09-035: Chyby zabezpečení v knihovně Visual Studio Active Template Library umožňují vzdálené spuštění kódu (969706). Také byly přidány odkazy na webové přenosy těchto mimořádných bulletinů zabezpečení.
-   V3.0 (4. srpna 2009): Byla provedena revize, jejímž cílem je oznámení opětovného vydání aktualizace pro aplikaci Microsoft Internet Explorer 6 Service Pack 1 v systému Microsoft Windows 2000 Service Pack 4. Všichni zákazníci, kteří již mají nainstalovanou původní aktualizaci aplikace Internet Explorer 6 Service Pack 1 v aktualizaci Microsoft Windows 2000 Service Pack 4, již jsou chráněni. Zákazníci, kteří používají korejskou jazykovou verzi aplikace Internet Explorer 6 Service Pack 1, si však mohou znovu nainstalovat aktualizaci aplikace Internet Explorer 6 Service Pack 1 v operačních systémech Windows 2000, aby měli stejnou ochranu a mohli vyřešit problém s tiskem. Viz Bulletin zabezpečení společnosti Microsoft MS09-034.
-   V4.0 (11. srpna 2009): Tento revidovaný souhrnný bulletin oznamuje nové vydání bulletinu MS09-035. Toto nové vydání nabízí nové aktualizace aplikací Microsoft Visual Studio 2005 Service Pack 1 (KB973673), Microsoft Visual Studio 2008 (KB973674) a Microsoft Visual Studio 2008 Service Pack 1 (KB973675). Jsou určeny vývojářům, kteří používají aplikaci Visual Studio k vytváření součástí a ovládacích prvků pro mobilní aplikace s využitím knihovny ATL pro inteligentní zařízení.
-   V4.1 (13. srpna 2009): U bulletinu MS09-035 došlo k opravě požadavku na restartování.
-   V5.0 (19. srpna 2009): Přidána poznámka k bulletinu MS09-028 popisující software obsahující tuto chybu pro rozhraní DirectX 8.1.
-   V6.0 (25. srpna 2009): Tento revidovaný souhrnný bulletin oznamuje nové vydání aktualizace systému Windows XP Service Pack 2, Windows XP Service Pack 3 a Windows XP Professional x64 Edition Service Pack 2 v japonštině. Všichni zákazníci, kteří již mají nainstalovanou původní aktualizaci, jsou chráněni. Avšak zákazníci, kteří mají nainstalován systém Windows XP Service Pack 2, Windows XP Service Pack 3 nebo Windows XP Professional x64 Edition Service Pack 2 v japonštině by měli aktualizaci znovu nainstalovat, aby měli stejnou ochranu a mohli vyřešit problém s tiskem. Viz Bulletin zabezpečení společnosti Microsoft MS09-029.
-   V7.0 (12. ledna 2010): Bulletin byl revidován přidáním systému Windows Embedded CE 6.0 do seznamu softwaru obsahujícího chybu zabezpečení, uvedeného v bulletinu MS09-035. Aktualizace pro systém Windows Embedded CE 6.0 (KB974616) je kumulativní aktualizace dostupná pouze prostřednictvím webu služby Stažení softwaru. Zákazníci používající platformu Windows Embedded CE 6.0 by měli zvážit instalaci kumulativní aktualizace.
-   V8.0 (9. března 2010): Bulletin revidován přidáním nástroje Microsoft Virtual Server 2005 do seznamu softwaru obsahujícího chybu zabezpečení, uvedeného v bulletinu MS09-035.

*Built at 2014-04-18T01:50:00Z-07:00*
