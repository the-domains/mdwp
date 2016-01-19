---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2016-01-19T23:37:52.357Z'
dateModified: '2016-01-19T23:37:22.199Z'
title: Hugo - die blitzschnelle Static Site Engine
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2016-01-19-hugo-die-blitzschnelle-static-site-engine.md
published: true
url: hugo-die-blitzschnelle-static-site-engine/index.html
_type: Article

---
# Hugo - die blitzschnelle Static Site Engine
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/ece06b57-7541-4091-ba51-0ec6dd56c414.jpg)

Seit einigen Jahren schießen sog. Static Website Generators/Static 
Site Engines wie Pilze aus dem Boden. Und sie werden immer besser.

Hugo
steht seit Mitte 2013 zur Verfügung und besitzt einige 
Alleinstellungsmerkmale, die diese Engine von allen anderen hervorhebt.

* Beste Performance
* Keinerlei Abhängigkeiten von anderer Software
* Arbeitet sofort "Out of the box" Clean URLs, Taxonomien u.v.m. stehen ohne weiteres Zutun sofort zur Verfügung.
* Nach
der "Installation" kann sofort eine erste Website erstellt werden. 
Zusätzliche Konfigurationsschritte sind nur für besondere Anpassungen 
erforderlich.

## Warum Hugo?

Hugo ist eine von vielen Static 
Website Engines, die in den letzten Jahren das Licht der Welt entdeckt 
haben. Im Großen und Ganzen arbeiten all diese Engines nach einem 
ähnlichen Prinzip. Wird ein Build-Prozess angestossen, werden aus 
Templates und Inhalten, meistens mit Markdown geschrieben, komplette 
HTML-Dateien generiert. Diese werden, vorzugsweise durch einen 
automatisierten Prozess, auf den Server Ihres Hosting-Providers 
hochgeladen.

Oder in anderen hoch-optimierten Workflows wird der Build-Prozess direkt auf dem Server angestoßen. Das ist z.B. bei [Netlify][0] der Fall.

Und
in diesen Fällen kommt das größte Pfund von Hugo ins Spiel: die 
atemberaubende Geschwindigkeit bei der Generierung der HTML-Dateien. 
Hugo ist so schnell, das Änderungen oder neue Seiten genau so schnell 
Online erreichbar sind, wie bei einem dynamischen CMS.

Geschwindigkeit
ist sicherlich nicht das einzige Kriterium für die Auswahl einer Static
Site Engine. Die zugrundeliegende Programmiersprache, die 
Template-Engine(s), zusätzliche Plugins, Verbreitung und eine aktive 
Community sind sicherlich ebenfalls sehr wichtig und mögen für manchen 
Web-Entwickler auch ausschlaggebend sein.

Für mich ist neben der 
Performance, die Tatsache wichtig, dass man mit Hugo in keiner 
'Dependencie Hell' schmort. Das bedeutet, dass keine zusätzliche 
Software auf dem Entwicklungsrechner laufen muss. Insbesondere muss 
keine spezielle Programmiersprache, wie Ruby oder Python, installiert 
werden.

Viele Ruby basierte Engines hatten große Probleme auf 
Macs nach einem Update auf El Capitaine. Außerdem müssen diese Systeme 
häufig aktualisiert werden und es kann Probleme mit unterschiedlichen 
Versionen einer Software auf unterschiedlichen Rechnern geben, was 
insbesondere in Entwicklerteams zu einigem Mehraufwand führen kann.

Zwar
haben die unterschiedlichsten Package-Manager viele Probleme beseitigt 
oder reduziert, aber auch die müssen zuerst installiert werden.

Das
ist bei Hugo alles nicht nötig. Hugo ist einfach ein ausführbares 
Progamm, das alles enthält was zum Betrieb nötig ist. Es kann ohne 
weitere Maßnahmen auf Mac OS, Linux und Windows installiert und 
gestartet werden.

### Themes

Mit einem der 
vielen kostenlosen Hugo Themes, die natürlich alle responsive sind, 
können Sie sehr schnell eine neue Website launchen.

* Agency - [Demo][1]  
$ git clone https://github.com/digitalcraftsman/hugo-agency-theme
* Air - [Demo][2]  
$ git clone https://github.com/syui/hugo-theme-air
* Casper - [Demo][3]  
$ git clone https://github.com/vjeantet/hugo-theme-casper
* Creative - [Demo][4]  
$ git clone https://github.com/digitalcraftsman/hugo-creative-theme
* Crisp   
$ git clone https://github.com/kathyqian/crisp-ghost-theme
* Freelancer - [Demo][5]  
$ git clone https://github.com/digitalcraftsman/hugo-freelancer-theme
* Greyshade - [Demo][6]  
$ git clone https://github.com/cxfksword/greyshade
* Hikari - [Demo][7]  
$ git clone https://github.com/digitalcraftsman/hugo-hikari-theme
* Hugo Base Theme - [Demo][8]  
$ git clone https://github.com/crakjie/hugo-base-theme
* Hugo Bootswatch - [Demo][9]  
$ git clone https://github.com/nilproductions/hugo-bootswatch
* Hugo Incorporated - [Demo][10]  
$ git clone https://github.com/nilproductions/hugo-incorporated
* Hugo mdl - [Demo][11]  
$ git clone https://github.com/jchatkinson/HugoMDL
* Hugo Minimalist - [Demo][12]  
$ git clone https://github.com/digitalcraftsman/hugo-minimalist-theme
* Hugo Multi-Bootswatch - [Demo][13]  
$ git clone https://github.com/mpas/hugo-multi-bootswatch
* Hugo Uno - [Demo][14]  
$ git clone https://github.com/SenjinDarashiva/hugo-uno
* Hugoscroll - [Demo][15]  
$ git clone https://github.com/SenjinDarashiva/hugoscroll
* Hurock - [Demo][16]  
$ git clone https://github.com/TiTi/hurock
* Hyde - [Demo][17]  
$ git clone https://github.com/spf13/hyde
* Landing Page Hugo - [Demo][18]  
$ git clone https://github.com/crakjie/landing-page-hugo
* Liquorice - [Demo][19]  
$ git clone https://github.com/eliasson/liquorice/
* Material Design - [Demo][20]  
$ git clone https://github.com/pdevty/material-design
* Material Lite - [Demo][21]  
$ git clone https://github.com/SamuelDebruyn/hugo-material-lite
* Persona   
$ git clone https://github.com/aries1980/hugo-theme-persona
* Pixyll - [Demo][22]  
$ git clone https://github.com/azmelanar/hugo-theme-pixyll
* Polymer - [Demo][23]  
$ git clone https://github.com/pdevty/polymer
* Projecthub - [Demo][24]  
$ git clone https://github.com/vjeantet/hugo-theme-projecthub
* Purehugo - [Demo][25]  
$ git clone http://dplesca.github.io/purehugo
* Redlounge - [Demo][26]  
$ git clone https://github.com/tmaiaroto/hugo-redlounge
* Robust - [Demo][27]  
$ git clone https://github.com/dim0627/hugo\_theme\_robust
* Shiori - [Demo][28]  
$ git clone https://github.com/chibicode/hugo-theme-shiori
* Simple-A - [Demo][29]  
$ git clone https://github.com/AlexFinn/simple-a
* Slim - [Demo][30]  
$ git clone https://github.com/zhe/hugo-theme-slim
* Start-Bootstrap Clean Blog - [Demo][31]  
$ git clone https://github.com/humboldtux/sbcb-demo
* Strata - [Demo][32]  
$ git clone https://github.com/digitalcraftsman/hugo-strata-theme
* Twenty Fourteen - [Demo][33]  
$ git clone https://github.com/jaden/twentyfourteen
* Vienna - [Demo][34]  
$ git clone https://github.com/keichi/vienna.git

[0]: https://netlify.com/
[1]: https://ironsummitmedia.github.io/startbootstrap-agency/
[2]: https://syui.github.io/hugo-theme-air/
[3]: https://vjeantet.fr/
[4]: https://ironsummitmedia.github.io/startbootstrap-creative/
[5]: https://ironsummitmedia.github.io/startbootstrap-freelancer/
[6]: https://themes.gohugo.io/theme/greyshade/
[7]: https://themes.gohugo.io/theme/hikari
[8]: https://themes.gohugo.io/theme/hugo-base-theme
[9]: https://themes.gohugo.io/theme/hugo-bootswatch
[10]: https://blog.nilproductions.com/
[11]: https://themes.gohugo.io/theme/hugo-mdl/
[12]: https://themes.gohugo.io/theme/hugo-minimalist/
[13]: https://themes.gohugo.io/theme/hugo-multi-bootswatch/
[14]: https://themes.gohugo.io/theme/hugo-uno
[15]: https://themes.gohugo.io/theme/hugoscroll/
[16]: https://themes.gohugo.io/theme/hurock/
[17]: https://themes.gohugo.io/theme/hyde/
[18]: https://themes.gohugo.io/theme/landing-page-hugo/
[19]: https://themes.gohugo.io/theme/liquorice/
[20]: https://themes.gohugo.io/theme/material-design/
[21]: https://materialexample.sa.muel.be/
[22]: https://themes.gohugo.io/theme/pixyll/
[23]: https://themes.gohugo.io/theme/polymer/
[24]: https://themes.gohugo.io/theme/projecthub/
[25]: https://themes.gohugo.io/theme/purehugo/
[26]: https://themes.gohugo.io/theme/redlounge/
[27]: https://themes.gohugo.io/theme/robust/
[28]: https://themes.gohugo.io/theme/shiori/
[29]: https://themes.gohugo.io/theme/simple-a/
[30]: https://themes.gohugo.io/theme/slim/
[31]: https://themes.gohugo.io/theme/startbootstrap-clean-blog
[32]: https://themes.gohugo.io/theme/strata
[33]: https://themes.gohugo.io/theme/twentyfourteen
[34]: https://themes.gohugo.io/theme/vienna