# PullTest
Um die IDE für den Master-Pull einzustellen

Falls das "Clone" mit der IDE nicht funktioniert, wegen der ITS Problematik der zwischengeschobenen SSL-Zertifikate, dann hilft folgendes Kommando

    git config --global http.sslverify false

Bei einen Update-Fehler:

    git config --global --add safe.directory <LOKALER_REPPFAD>

Viel Spaß!

    Nach Annahme der Einladung geht`s
