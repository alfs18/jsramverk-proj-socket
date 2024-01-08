# jsramverk-socket
Socket server for jsramverk course.

## Project setup
```
npm install
```

```
node app.js
```

## Redovisningstext
Realtidsaspekten implementerades med hjälp av socket.io. När man går till sidan för köp eller sälja  aktier så kopplas man upp mot socketen, vilket gör att grafen som syns i statistiken för en viss aktie kan uppdateras direkt när det nuvarande priset har ändrats, dvs. efter det att något köpts eller sålts.

För att visa en grafisk illustration valde jag att använda mig av chart.js i kombination med primevue, då jag tyckte att det blev en tydlig illustration över aktiepriserna. Dessutom hittade jag bra exempel på hur den kunde användas i ett realtidssammanhang. Tycker att tekniken fungerar bra, men hade en del problem med att få den så som jag önskade.
