# Mon-Livre

Plateforme web de lecture et de téléchargement de livres numériques par abonnement mensuel, similaire à Netflix, mais dédiée exclusivement aux livres.

## ⚙️ Pré-requis

### 1. Installer le SDK .NET 8
Téléchargez et installez .NET 8 depuis le lien suivant :  
👉 [Télécharger .NET 8 (SDK 8.0.412)](https://dotnet.microsoft.com/fr-fr/download/dotnet/thank-you/sdk-8.0.412-windows-x64-installer)

### 2. Installer SQL Server et SSMS (SQL Server Management Studio)
- **SQL Server** : [Télécharger SQL Server](https://www.microsoft.com/fr-fr/sql-server/sql-server-downloads)  
- **SSMS** : [Télécharger SSMS](https://learn.microsoft.com/fr-fr/ssms/install/install)

---

## 🚀 Lancer le projet

### 3. Ouvrir le projet
- Ouvrir le dossier du projet dans **Visual Studio Code** ou **Microsoft Visual Studio 2022**
- Le back-end est basé sur **ASP.NET Core Web API**

### 4. Installer les packages NuGet (back-end)

#### ✅ Avec Visual Studio Code (terminal) :
Placez-vous dans le dossier du projet Web API, puis exécutez :

```
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
dotnet add package Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools

```

✅ Avec Visual Studio 2022 :
    Allez dans Outils > Gestionnaire de packages NuGet > Gérer les packages NuGet pour la solution
    Installez les packages ci-dessus

5. Lancer le back-end

```
dotnet run

```

6. Installer Node.js (front-end)

Téléchargez Node.js :
👉 https://nodejs.org/
7. Installer les dépendances Angular

Dans le dossier front-end, exécutez :

```
npm install

```

8. Lancer l'application Angular

```

ng dev

```
