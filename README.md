Web Scraping en Python para acceder al histórico de los valores de las empresas del DAX 40 alemán que proporciona la página de la bolsa de Frankfurt.

El proceso recorre las URL en las que se encuentran los datos de Adidas, Airbus, Allianz, Basf, Bayer, Beiersdorf, BMW, Brenntag, Commerzbank, Continental, Covestro, Daimler Truck, Deutsche Bank, Deutsche Borse, Deutsche Post, Deutsche Telekom, EON, Fresenius SE, Hannover Ruck, Heidelberg Materials, Henkel AG & Co. KGaA Vz, Infineon Technologies, Mercedez Benz Group, Merck KGaA, MTU Aero Engines, Muenchener Rueckversicherungs, Porsche AVG, Porsche Automobil Holding SE Vz, Qiagen, Rheinmetall, RWE AG St, SAP SE, Sartorius, Siemens AG, Siemens Energy AG, Siemens Healthineers, Symrise, Volkswagen, Vonovia y Zalando SE.

Extrae los datos del precio de las acciones desde el 1 de enero de 2020 hasta la actualidad, pero se puede configurar para ampliar el periodo fácilmente. Advertir que hay empresas cuya cotización es posterior, por lo que esos datos no aparecenrán.

El proceso crea un dataframe con el histórico de dichas empresas y además una tabla con la moda de cada una de ellas.

Recordar que por la propia naturaleza del proceso, cualquier cambio de la web implicaría error en la extracción.

Ejercicio realizado con fines didácticos para poner en práctica las funciones relacionadas con Web Scraping.
