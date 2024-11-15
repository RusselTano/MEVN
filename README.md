npm init vue@latest
cd projet
npm i

aller dans vite.config.ts et ajouter
  build: {
    outDir: '../client-build'
  }
la c'est pour creer mon dossier a l'exterieur

je creer un dossier server
cd/server
npm init -y

installer express
npm i express