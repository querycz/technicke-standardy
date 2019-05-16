# Technické standardy WordPress

- HTML5, CSS3/SASS, JavaScript/jQuery/ES6, PHP/MySQL.
- Gulp.js pro automatizaci vývoje.
- Node.js a NPM pro automatizaci vývoje a správu front-end komponent.
- Responsivní layout – podpora širokých rozlišení, standardních rozlišení, rozlišení mobilních zařízení – tabletů a mobilních telefonů metodou „mobile first“.
- Grafické prvky optimalizované pro zařízení s vysokým rozlišením displeje („Retina“).
- Podpora internetových prohlížečů:
	- Internet Explorer 11 (jádro Trident, Windows) metodou „graceful degradation“,
	- Edge (jádro Edge),
	- Firefox (jádro Gecko, Windows/macOS),
	- Chrome/Opera 15+ (jádro Blink, Windows/macOS),
	- Safari (jádro WebKit, macOS).
- Uživatelská přístupnost a použitelnost:
	- Ctění standardů uživatelské přístupnosti (www.pravidla-pristupnosti.cz) 
- Redakční systém/CMS WordPress – aktuální stabilní revize + ověřené příslušné pluginy.
- SSL/HTTPS – dle možností serveru (doporučeno minimálně použití self-signed certifikátu, typicky Let’s Encrypt.
- HTTP/2 – dle možností serveru.
- Důraz na rychlý běh stránek:
	- Minifikace a kombinace JavaScript skriptů a CSS/SASS souborů pro snížení datové náročnosti a počtu požadavků na server,
    - critical CSS,
    - minifikace generovaných HTML,
	- extra komprese grafických formátů (především PNG, JPG, SVG),
	- cachování (WordPress plugin „WP Super Cache“),
	- serverová g-zip komprese a cachování (CSS, JS, HTML/PHP) dle možností serveru,
	- využití CDN pro načítání standardních skriptů/knihoven (typicky jQuery),
	- omezení počtu pluginů, které zatěžují běh stránky.
- SEO
	- On-page faktory – validita stránek, sémantický a čistý kód.
	- Off-page faktory
		- Indexace
			- Podpora indexace podstrčením nových stránek vyhledávači Google prostřednictvím sitemap.xml a Google Search Console.
			- Podpora indexace podstrčením nových stránek vyhledávačům Google, Seznam, Bing.
- Analytika návštěvnosti – založení Google Analytics profilu, případně vložení vlastního kódu Objednatele.
