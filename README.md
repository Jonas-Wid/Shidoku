# Shidoku
Dieses Projekt befasst sich mit dem Minimierungsproblem der gegebenen Tipps für ein Shidoku-Rätsel. Es soll dabei gezeigt werden, dass kein 3-Tipp Shidoku-Rätsel existiert.
Dieses Programm ist eine numerische Verdeutlichung der Bachelorarbeit "Lösen des Minimierungsproblems: Es existiert kein 16-Tipp Sudoku" von mir. Dort wurde der historische Beweis für das Minimierungsproblem in dem klassischen 9x9 Sudoku betrachtet.
Wir wollen nun, die dort gelernte, Theorie benutzen und diese auf das 4x4 Shidoku übertragen.

Ein Shidoku-Rätsel besteht aus einem 4x4 Gitter, welches mit den Zahlen 1-4 auszufüllen ist. Zu Beginn ist eine bestimmte Anzahl an Zellen in dem Gitter ausgefüllt.
Die Spielregeln sind:
  1. In jeder Reihe müssen die Zahlen 1-4 genau ein Mal vorkommen.
  2. in jeder Spalte müssen die Zahlen 1-4 genau ein Mal vorkommen.
  3. in jedem fett umrandeten 2x2 müssen die Zahlen 1-4 genau ein Mal vorkommen.

Dabei wird eine numerische Suche nach potentiellen 3-Tipp Sudokus gestartet. Es werden dabei die Reduktionsmethoden
 1. Einschränkung auf Äquivalenzklassen
 2. Tippeinschränkung durch unvermeidbare Mengen

benutzt. Dies führt dann zu dem Ergebnis, dass kein 3-Tipp Shidoku existiert.
