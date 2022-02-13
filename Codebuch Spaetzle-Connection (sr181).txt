# 226309 PV Grundlagen sozialer Netzwerkanalyse

# Datensatz Spaetzle-Connection-Regierung-Scholz
Codebuch Stand 2022-02, aktualisiert 2022-02
erstellt von Sara Rozic (sr181)

## Inhalt
- Nodes.csv (Nodelist)
- Edges.csv (Edgelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung der Datenerhebung
https://www.bundestag.de/
Gegencheck: https://www.abgeordnetenwatch.de/

# NODE-Attribute

**id** 
(identisch mit edgelist, aber hier nur einmalige Nennung)

**name_short** 
(Nachname)

**name** 
(voller Name)

**type**
0 = Person
1 = Organisation/Ort/Verband etc.

**sex** 
(Geschlecht)
1 = weiblich 
2 = männlich

**birth** 
(Geburtsjahr)

**position** 
(jetzige Position, z.B. Staatssekretär:in, Minister)
1 = Parlamentarischer Staatssekretär
2 = Staatsminister
3 = Bundesminister

**education** 
(höchster Bildungsabschluss)
1 = Promotion
2 = Diplom
3 = juristisches Staatsexamen
4 = Lizenziat
5 = Magister

**subject** 
(Fachrichtung bei Studium/Promotion)
1 = Politikwissenschaften
2 = Rechtswissenschaften
3 = Wirschaftswissenschaften
4 = Volkswirtschaftslehre
5 = Sozialpädagogik

**party** 
(Parteizugehörigkeit)
1 = SPD
2 = FDP
3 = Grüne

**religion** 
(Religion)
1 = römisch-katholisch 
2 = evangelisch
3 = muslimisch

**kids** 
(Anzahl der Kinder)

**twitter** 
(Anzahl follower)
1 = <5000 Follower
2 = 5000 bis 10.000
3 = 10.000 bis 15.000
4 = 15.000 bis 100.000
5 = >100.000

**instagram** 
(Anzahl follower)
1 = <5000 Follower
2 = 5000 bis 10.000
3 = 10.000 bis 15.000
4 = 15.000 bis 100.000
5 = >100.000

**facebook** 
(Anzahl follower)
1 = <5000 Follower
2 = 5000 bis 10.000
3 = 10.000 bis 15.000
4 = 15.000 bis 100.000
5 = >100.000

**youtube** 
(Anzahl Abonnenten)
1 = <100
2 = >100


# EDGE-Attribute

**from**
(id)

**to**
(id)

**relationship**
1 = Ministerium (auch angegliedert als Staatsekretär:in)
2 = politische Funktionen
3 = Ehrenamt
4 = Unternehmen und Aufsichtsräte
5 = Stipendien
6 = Berufstätigkeiten
7 = Studienort in In- und Ausland

**year** 
(Bezieht sich auf das Jahr, in dem die Variable relationship erhoben wurde)

##
