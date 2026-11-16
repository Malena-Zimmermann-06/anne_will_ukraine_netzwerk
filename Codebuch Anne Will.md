Codebuch Anne Will:

Inhalt

\- Edges.csv (Edgelist)

\- Nodes.csv (Nodelist)

\- Codebuch.md (Codierung der Datensätze)

\## Ursprung und Datenerhebung

Das Netzwerk ist ein gerichtetes two-mode (bi-modales/bipartite) Netzwerk bestehend aus der Gästeliste der Talkshow von Anne-Will aus dem Jahr 2022 mit dem Thema Ukraine.

**EDGE-Attribute**

**from:** Ausgangsknoten der Beziehung (Person)

**to:** Zielknoten der Beziehung

- Sendungsfolge
- Partei

**relationship:** Art der Beziehung

- 1 = Teilnahme an Sendung
- 2 = Parteizugehörigkeit

**NODE-Attribute**

**id**: Eindeutige Kennung des Knotens (z. B. lk für Lars Klingbeil, 500 für Folge 500 oder SPD für die Partei)

**name**: Vollständiger Name des Knotens

**party**: Parteizugehörigkeit der Person. Bei fehlender Parteizugehörigkeit bleibt das Feld leer.

**sector**: Gesellschaftlicher bzw. beruflicher Bereich des Knotens (z. B. Politik, Journalismus oder Wissenschaft)

**country**: Land, dem die Person zugeordnet ist (z. B. Deutschland oder Ukraine)