LegalLinks
==========

Simple tool to convert [IITC](https://github.com/jonatkins/ingress-intel-total-conversion) Draw Tools exports to stock Ingress Intel links, available at [http://dirkonet.github.io/LegalLinks](http://dirkonet.github.io/LegalLinks).

The new Ingress Intel map lets you draw links and fields and see blocking links so if you want to export your planned fields from IITC to the normal Intel map or want to show your work to others not using IITC, just convert your Draw Tools export to an Intel link.

This tool takes the Draw Tools export format

```
[{"type":"polygon","latLngs":[{"lat":51.00,"lng":13.50},{"lat":51.20,"lng":13.50},{"lat":51.20,"lng":13.70}],"color":"#a24ac3"}]
```

and converts it to a nice and clean [stock Intel link](https://www.ingress.com/intel?ll=51.13333333333333,13.566666666666668&z=10&pls=51,13.5,51.2,13.5_51.2,13.5,51.2,13.7_51,13.5,51.2,13.7) 

```
https://www.ingress.com/intel?ll=51.13333333333333,13.566666666666668&z=10&pls=51,13.5,51.2,13.5_51.2,13.5,51.2,13.7_51,13.5,51.2,13.7
```

which you can then share with your friends – preferrably made more sharing friendly with the URL shortener of your choice.

Known Limitation: As GET requests have a maximum length, only about 40 links can be displayed at once. More links will cause a server error.
