
# Résumé des Routes - GPT-generated

## Routes Principales
- `/` - Page d'accueil (HomeRouter.vue)
- `/dashboard` - Tableau de bord (HomeView.vue)
- `/landing` - Page d'atterrissage (BrochureLanding.vue)
- `/upgrade` - Page de mise à niveau (Upgrade.vue)
- `/styleguide` - Guide de style (Styleguide.vue)
- `/beta` - Inscription bêta (BetaRegister.vue)

## Routes Clients
- `/client` - Liste des clients (Clients.vue)
- `/client/dummy` - Page client fictive (Client_dummy.vue)
- `/client/:id` - Profil client (Client.vue) avec sous-routes:
  - `/client/:id/done/:convoId` - Résumé d'activité (ClientActivitySummary.vue)
  - `/client/:id/convo/:convoId` - Résumé d'activité (ClientActivitySummary.vue)
  - `/client/:id/extra/:extraId` - Panel supplémentaire (ClientExtraPanel.vue)
  - `/client/:id/fiche` - Fiche client (ClientFiche.vue)
  - `/client/:id/note` - Panel de notes (Soon.vue)
  - `/client/:id/talk` - Conversation (Convo.vue)
- `/client/:id/fiche2` - Fiche client alternative (ClientFiche.vue)
- `/client/:id/convo/dummy` - Résumé d'activité fictif (ClientActivitySummaryDummy.vue)
- `/client/:id/convo2/:convoId` - Résumé d'activité conversation (ClientActivitySummary.vue)
- `/invite-client` - Invitation client (InviteClient.vue)

## Routes Activités
- `/start-activity/:id` - Démarrage d'activité (ActivityStart.vue)
- `/realtime-activity/:id` - Activité en temps réel (RealtimeActivity.vue)
- `/form-activity/:id` - Activité de formulaire (FormActivity.vue)
- `/wiso/:id` - Conversation (Convo.vue)
- `/extra/:extraId` - Extra autonome (StadaloneExtra.vue) [possible faute d'orthographe]

## Routes Blog
- `/blog` - Liste des articles (Blogs.vue)
- `/blog/:pathMatch(.*)*` - Article de blog (BlogArticle.vue)

## Routes Vidéo/Réunion
- `/host` - Liste des réunions d'hôte (HostMeetingList.vue)
- `/host/:roomId` - Salle d'hôte vidéo (VideoHost.vue)
- `/meet/:roomId` - Rejoindre une vidéo (VideoJoin.vue)

## Routes Authentification
- `/auth` - Authentification (Auth.vue)
- `/login` - Connexion (Auth.vue)
- `/signup` - Inscription (Auth.vue)
- `/debuter/:id` - Inscription patient (PatientSignup.vue)
- `/debuter/merci` - Confirmation d'inscription patient (PatientSignupDone.vue)

## Routes Légales
- `/privacy` - Politique de confidentialité (Privacy.vue)
- `/terms` - Conditions d'utilisation (Terms.vue)

## Route Debugging
- `/supa` - Débogage Supabase (SupaDebug.vue)

## Routes Commentées (Inactives)
- `/home` - Vue d'accueil (HomeView.vue)
- Plusieurs routes `/talk` pour différentes configurations de conversation