## Lure Box - Using Honeytokens for Detecting Cyberattacks
We’re living in times of rapid changes in which new opportunities and threats occur due to the increasing digitalization. According to estimates, companies in Germany have a yearly loss of 50 billion dollars due to digital industrial espionage. Therefore, an early detection of an attack is essential to take action by counter-measures and further investigations. For centuries lures and traps have been used to detect attackers or to expose spies. With the help of Honeytokens this principle can also be used in the cyberspace. 

A Honeytoken is any kind of information which is placed as a lure in the physical or digital world. Any access to the Honeytoken is monitored and will raise a silent alarm.

This paper will present the Lure Box which was developed as part of this thesis. The Lure Box is a virtual machine based upon open source software. The box contains all necessary components to receive, process, store and view log data. In addition to the Lure Box, possible applications for Honeytokens in a company network are described. A special focus was given to the usage within databases. As part of a big scenario, Honeytokens were placed in four different database systems which were configured to log every access to the tokens. The generated log data are transferred to the Lure Box. 

A program running on the box can be used to trigger an alarm when logs are received, which indicate an access to a Honeytoken. The Lure Box and the usage of Honeytokens shows that IT security of a company can be increased with the help of simple but effective tools.

![LureBox Implementation](/images/implementation.png)


## Authors
* Christoph Malin (student at FH St. Pölten) - is151514@fhstp.ac.at
* Dr. Simon Tjoa (supervisor at FH St. Pölten)

## Ausgangslage
Bei einer Cyberattacke auf das Karrierenetzwerk LinkedIn im Jahr 2012 wurden mehr als 100 Millionen Konten gestohlen, wobei anfangs noch die Rede von 6,5 Millionen betroffenen BenutzerInnen war. Erst vier Jahre später, im Jahr 2016, fand man heraus, dass Daten in viel größerem Umfang entwendet worden waren. Auch bei der US-Geheimdienstbehörde NSA verging einige Zeit, bis festgestellt wurde, dass der Insider Edward Snowden zwischen 50.000 und 200.000 geheime Dokumente entwendet hatte. Diese beiden Vorfälle zeigen, dass große IT-Unternehmen wie LinkedIn, aber auch vermeintlich allmächtige Geheimdienstbehörden wie die National Security Agency keine vollständige Kontrolle darüber haben, wer wann unerlaubt auf gewisse Daten zugreift. Eine Studie der Firma Garner geht davon aus, dass Unternehmen im Jahr 2016 weltweit 86,1 Milliarden US-Dollar für Informationssicherheit ausgegeben haben. Während also viel Geld in teure Software und Beratung gesteckt wird, werden die sehr günstigen und effizienten Honeytokens nur selten verwendet. Diese sind digitale oder analoge Köder, deren Wert darin liegt, von jemandem unautorisiert verwendet zu werden. Jeglicher Zugriff darauf bzw. jede Verwendung eines dieser Köder wird überwacht und stellt eine verdächtige bzw. verbotene Aktivität dar. So könnte ein Honeytoken beispielsweise ein LinkedIn-Account sein oder ein vermeintlich geheimes Dokument der NSA. Greift jemand darauf zu, kann Alarm geschlagen werden.

## Ziel 
Das Ziel dieser Arbeit ist es, mehr über Honeytokens und deren mögliche Einsatzzwecke in verschiedenen Systemen herauszufinden. In einem umfassenden Szenario soll die Platzierung und Verwendung von Honeytokens in unterschiedlichen Datenbanksystemen evaluiert werden. Mit einem eigens erstellten System, der Lure Box, sollen Zugriffe auf Honeytokens überwacht werden können und im Anlassfall ein Alarm generiert werden. 

## Ergebnis
Das Szenario konnte erfolgreich mit vier verschiedenen Datenbanksystemen umgesetzt werden. Greifen AngreiferInnen auf die Honeytokens in den Datenbanken zu, so generieren diese Logdaten, die von der Lure Box verarbeitet werden; bereits zwei Minuten später wird eine E-Mail-Alarmierung versendet. Zusammen mit der Lure Box konnte auch eine umfassende Dokumentation erstellt werden, wie die einzelnen Komponenten installiert und konfiguriert werden müssen. Diese erlaubt interessierten Personen Honeytokens in verhältnismäßig kurzer Zeit in verschiedenen Systemen zu platzieren und mit Hilfe der Lure Box zu überwachen. 
