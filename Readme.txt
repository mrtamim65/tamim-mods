


Instructions:

1. Add required dex file in apk. (Rename it before adding acording to existing dex files in the apk)

2. Add the following code in the onCreate method of your MainActivity:

invoke-static {p0}, LApkManager/Notification/NotificationHelper;->showNotification(Landroid/content/Context;)V