# zoo

VAKSTU versioon mängust ZOO koos leveliredaktoriga.

Ajakirja Modelist-Konstruktor 1990. aasta mai- ja juunikuu numbrist masinkoodis sisse toksinud ja kooliarvuti JUKU E5104 peale portinud:

* Vahur Sinijärv (programmeerimine ja graafika)
* Kalle Tomingas (muud tööd, sh suur osa levelitest)

Pikemalt mängust ja selle sünniloost JUKU mängude ketta 2025 saatesõnas:

* https://gafgaf.infoaed.ee/posts/mängude-ketas-2025/

Originaali autorid on Е.Филиппов ja С.Переверзев, leveliredaktori autor В.Зверков.

Mängu ehitamiseks:

```
M80 =LODERUN
L80 LODERUN,LODERUN/N/E
```

Levelirdaktori puhul:

```
M80 =LODEGEN
L80 LODEGEN,LODEGEN/N/E
```

Levis olnud 58 leveliga ZOO puhul algavad levelid teisest mäluaadressist ja kui tahta, mängu käivitamise ja sellest väljumise järel mällu jäänud leveleid brausida, siis tuleks muuta algusaadress [neljandal real](https://github.com/boamaod/zoo/blob/main/lodegen.mac#L4):

```
tabstrt	equ	2200h+0a00h
```

Have a good time with ZOO!

![VSW ehk Vakstu Software](https://github.com/user-attachments/assets/7522e84d-e4a6-4473-b2de-dd6ac8f852b0)
