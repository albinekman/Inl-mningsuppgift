Övning protekoll

Tcp/ ip är en kortare variant av OSI. 
Tcp/ip består av 4 lager
application vilket hanterar representation, kodning och dialog
host to host är ungifär samma sak som OSIs transport. Det hanterar pålitlighet och kontroll av error
internet visar vägen för paketer fån sändaren till destenationen. 
network access är konceptet för data link och fysiska lagren för båda Lan och Wan.

OSI består av 7 lager, application, presentation, session, transport, network, datalink och physical.

Båda protokollen fungerar likadant med transport och nätverks lagren och att båda är baserade på packet-switched teknologi. Det som skiljer är själva uppbygnaden av deras lager.

TCP består av först en heather som består av 20 byte och sen en paylode. Innan den börjar skicka så fastställer den en kontakt mellan sendaren och mottagaren. Datan bryts ner i olika segment som skickas till mottagaren där dety byggs ihopp igen i rätt orning och vid eventuellt förlust skickas det om. Segmenten kan max ligga på 1500 bytes vilket är maximala storleken för Maximum Transfer Unit. Segmenten får olika Sequence Number och Acknowledgment. Sequence Number anvends för att kolla om det har förlorats några segment.Acknowledgment är för att kolla vilket som är det nästa väntande segmentet.

Udp är snabbare och har färre lager än Tcp. Tanken med UDP är att det ska gå fort och effektivt, det bryr som inte om att rätta till errors. Till skillnad mot Tcp/Ip som är skapat av USAs försvar av anledningen att kommunikationen ska vara stabil under alla förutsättningar. UDP förlitar sig istället på applikationens lager och består bara av Source port, Destination port, Length, Checksum, Data.
