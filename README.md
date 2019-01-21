# Matemaatiline kartograafia 2019
Antud juhendid toetavad geograafia eriala magistriõppe kursust Matemaatiline kartograafia LOOM.02.007 ja keskenduvad Pythoni matemaatilise kartograafia ja visualiseerimise teegi [Cartopy](https://scitools.org.uk/cartopy/docs/latest/) võimalustele.

Esimene juhend annab ülevaate kaardiakna loomisest, erinevate projektsioonide kasutamisest ja lihtsamate kaardielementide (kaardivõrk, tekst) konstrueerimisest. Teine juhend keskendub täiendavate kaardielementide lisamisele, mille hulka kuuluvad nii eraldiseisvad lisakihid (SHP, rasterfailid) kui erinevad matemaatilised ja kartograafilised konstruktsioonid (ortodroom jms).

## Ettevalmistus
Juhendite kasutamine eeldab Anaconda olemasolu, mis peaks olema arvutiklassi arvutites tagatud. Kes soovib seda seadistada oma arvutis, võib selleks kasutada Alex Kmochi vastavat [juhendit](https://github.com/allixender/meetup-notes/tree/master/02-python-jupyter).

Esmalt laadi alla ja paki kuhugi kausta lahti käesolev repositoorium koos kõigi failidega (Clone or download -> Download ZIP).

Seejärel leia ja ava nn Anaconda Prompt. Loo uus Anaconda keskkond, mille Pythoni versioon on 3.6.

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/create_env.PNG" height="150">

Järgmine rida aktiveerib äsjaloodud keskkonna.

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/activate_env.PNG" height="150">

Nüüd tuleks installida vajalikud Pythoni teegid. Mõlema puhul tulevad kaasa ka mitmed muud teegid, sh Cartopy puhul Matplotlib, millele see tugineb.

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/conda_install.PNG" height="150">

Järgnevalt määra aktiivseks kaustaks see, kuhu sai eelnevalt lahti pakitud antud GitHubi repositoorium.

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/cd_folder.PNG" height="150">

Lõpuks aktiveeri Jupyteri Notebook.

<img src="https://raw.githubusercontent.com/hvirro/mcarto/master/img/jupyter.PNG" height="150">
