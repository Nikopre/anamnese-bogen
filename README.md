# Anamnesebogen (statische Seite)

Generiert aus `fm-agent/docs/vorlagen/Anamnesebogen.html` mit `node cockpit/scripts/bogen-export.mjs`
(Ordner `cockpit/dist-anamnese/`). Nicht von Hand bearbeiten: im fm-agent-Repo ändern, exportieren,
hierher kopieren, committen, pushen. Vercel deployt automatisch.

Die Seite hält keine Daten. Sie liest die Fallnummer zum Token von der Datenschnittstelle (Supabase,
Edge Function `anamnese-briefkasten`) und schickt die Antworten dorthin, im Browser verschlüsselt.
