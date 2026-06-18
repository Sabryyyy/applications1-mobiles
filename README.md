# applications1-mobiles
Projet d'application mobile développé sur  Android
Voici un résumé clair que vous pouvez donner aux élèves comme description récapitulative du projet.

**Description récapitulative — TP Application Android ChatBot**

Ce TP consiste à concevoir une application Android de chatbot local (sans IA externe), en Java, mobilisant les concepts d'Activity, Fragments, RecyclerView, SharedPreferences et les design patterns Singleton et MVC/MVVM.

**Principe de l'application**
L'utilisateur saisit son prénom sur un écran d'accueil, puis accède à un écran de chat où il échange avec un bot qui répond selon des règles pré-programmées (mots-clés comme "bonjour", "heure", "date", "merci", etc.). L'historique des conversations est sauvegardé localement et reste disponible entre les sessions.

**Écrans à réaliser**
- Accueil (MainActivity) : saisie du prénom et navigation vers le chat
- Chat (ChatActivity + ChatFragment) : zone de conversation avec le bot
- Historique (HistoriqueFragment) : affichage de toutes les sessions passées
- Paramètres (SettingsFragment) : gestion du nom et réinitialisation

**Étapes progressives du TP**
1. Mise en place du projet et de l'écran d'accueil (Activity, Intent, SharedPreferences)
2. Création du modèle de données Message (POJO)
3. Implémentation du moteur du bot BotEngine en Singleton
4. Affichage de la conversation avec RecyclerView (deux types de bulles : utilisateur et bot)
5. Sauvegarde de l'historique avec SharedPreferences et Gson
6. Fragment Historique et navigation complète entre les écrans (BottomNavigationView)
7. (Bonus) Migration vers l'architecture MVVM avec ViewModel et LiveData

**Compétences évaluées**
Architecture multi-écrans, gestion du cycle de vie, persistance de données, patterns de conception, et bonnes pratiques RecyclerView (ViewHolder, getItemViewType, notifyItemInserted).
