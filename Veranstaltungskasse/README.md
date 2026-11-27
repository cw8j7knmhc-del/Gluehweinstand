# Veranstaltungskasse V0.1

Eigenständige Entwicklungskopie der Glühweinkasse V6.31 (Quellcommit a97254bc63e52503bbb992fd4d010e97a5bda397). Der Root-Stand bleibt unverändert. Gemeinsame ES5-Kernlogik in core.js, vier UI-Einstiege. Getrennte Daten-, Token-, Backup-, Cache- und Vorlagen-Namensräume. Keine Übernahme bisheriger lokaler Verkaufsdaten. Die Geräte teilen weiterhin das Browser-Origin und damit dessen Speicherlimit; ein eigenes Repository/Origin ist später möglich.

Kachelminimum 112 x 114 CSS-Pixel, +/- 44 x 44 CSS-Pixel. Kompakter iPad-Modus nur bei ausreichend Platz; sonst scrollbares Layout. V0.1 bleibt ein Entwicklungsstand auf der bisherigen lokalen Datenstruktur. Veranstaltungsprofile, zentrale Produktdatenbank, IndexedDB, Mehrfachpfand und Benutzerverwaltung folgen in späteren Stufen. Keine echten Veranstaltungen mit dieser Vorabversion ohne Prüfung abwickeln.
