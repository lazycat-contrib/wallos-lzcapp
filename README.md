# Wallos LazyCat community package

Source https://github.com/ellite/Wallos,5.10.3,GPL-3.0. Official candidate in.zhaoj.wallos. Package community.lazycat.app.wallos,minOS1.5.0,amd64 mirror mode, community store only. Intended classification Tools / Subscription management127.

Single official bellamy/wallos container, native HTTP80. Persist /var/www/html/db and /var/www/html/images/uploads/logos separately under /lzcapp/var. Native startup manages www-data IDs, ownership, PHP-FPM, nginx and cron; do not force a non-root container UID that breaks those steps. Original image healthcheck retained, no added smoke or file interception.

First account creation is MANUAL in upstream registration UI. Use deployment username/secret, enter your email and confirm the credential according to native rules. Parameters do not create or reset accounts; /login.php fills #username and the native credential field without auto-submit. Complete setup before sharing access; only authorize trusted members. Keep deployment values synchronized after credential changes. Platform auth stays on, no anonymous paths.

Subscription/expense history is personal data; back up both database and logos before uninstalling. Mail/reminders/rates need native configuration and external connectivity; no third-party keys are supplied. Build and independent package checks all run on GitHub, no local source/image/LPK download. Startup, registration, fill, subscription CRUD, reminders, cron and persistence remain runtime-unverified.
