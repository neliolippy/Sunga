# Compilar o Sunga APK

1. Crie um repositório no GitHub.
2. Envie **todos os ficheiros e pastas dentro desta pasta Sunga** para o repositório.
3. No GitHub, abra **Actions**.
4. Execute **Build Sunga APK** com **Run workflow**.
5. Quando terminar, abra a execução concluída e descarregue o artefacto **Sunga-debug-apk**.
6. Dentro do ZIP estará `app-debug.apk`, pronto para instalar no Android.

O workflow usa Java 17, Gradle 8.7 e Android Gradle Plugin 8.6.1.
