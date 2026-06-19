# Rdv-chrono
Prépa RDV via n8n &IA : analyse Calendar, Gmail et LinkedIn (Apify), puis envoie le brief GPT sur WhatsApp.


Ce projet automatise la préparation de vos rendez-vous commerciaux grâce à l'IA et n8n.

Déclenchement horaire : Le workflow vérifie vos prochains rendez-vous dans Google Calendar.

Recherche enrichie : Pour chaque participant, il récupère automatiquement le dernier échange d'emails (Gmail) et extrait son profil ainsi que son activité récente (LinkedIn via Apify).

Synthèse par IA : Un modèle LLM (OpenAI GPT-4o) analyse et résume ces données pour identifier les points clés, les tâches en attente et les sujets de conversation pertinents.

Notification instantanée : L'assistant génère un briefing clair et structuré, puis l'envoie directement sur votre WhatsApp.
