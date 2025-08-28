# ✅ ExpenseIt – Visualiseur de Notes de Frais

Une application **WPF** simple et élégante pour consulter les notes de frais des employés par département.  
Développée en **C#**.

---

## ✨ Fonctionnalités principales

- 📋 Liste des employés (IT, Logistique)  
- 👤 Sélection d'un employé dans l'interface  
- 💸 Affichage détaillé des dépenses par personne  
- 🎨 Interface moderne avec styles personnalisés  
- 🔄 Navigation fluide entre les pages  
- 📊 Données structurées avec types de dépenses variés  
- 👥 Données d'exemple incluses  

---

## 🛠️ Technologies utilisées

| Technologie   | Usage principal |
|---------------|-----------------|
| **C#**        | Langage de programmation |
| **WPF**       | Framework d’interface utilisateur |
| **XAML**      | Interface et styles |
| **XML Data Binding** | Source de données intégrée |
| **.NET Framework**   | Plateforme de développement |

---

## 🚀 Installation et utilisation

### 📋 Prérequis
- Visual Studio 2019+  
- .NET Framework 4.7.2+  
- Windows 7+  

### ⚙️ Étapes d'installation
```bash
# 1. Cloner le repository
git clone https://github.com/remi-gntl/ExpenseIt.git

# 2. Ouvrir dans Visual Studio
cd ExpenseIt
# Ouvrir ExpenseIt.sln dans Visual Studio

# 3. Compiler et exécuter
# Appuyer sur F5 ou "Démarrer le débogage"
```


---

## 🎨 Fonctionnalités techniques

- ✅ Navigation WPF avec `NavigationService`  
- ✅ Data Binding XML pour les sources de données  
- ✅ Templates XAML pour l'affichage personnalisé  
- ✅ Validation utilisateur avec messages d'erreur  
- ✅ Styles cohérents définis dans `App.xaml`  
- ✅ Architecture **MVVM** respectée  

---

## 📈 Évolutions possibles

- Connexion base de données (SQL Server, SQLite)  
- Export PDF des rapports de dépenses  
- Ajout/modification d'employés en temps réel  
- Filtres par période ou montant  
- Graphiques de synthèse des coûts  
- Import/Export CSV des données  

---

## 🖥️ Comment utiliser
1. Page d'accueil : voir la liste des employés  
2. Sélectionner un employé dans la liste  
3. Cliquer **Voir** pour afficher ses dépenses détaillées  
4. Navigation : retour automatique à la liste  

---

## 📁 Structure du projet

```plaintext
ExpenseIt/
├── App.xaml                    # Styles globaux et configuration
├── App.xaml.cs                 # Point d'entrée de l'application
├── MainWindow.xaml             # Fenêtre principale
├── ExpenseItHome.xaml          # Page liste des employés
├── ExpenseItHome.xaml.cs       # Logique de sélection
├── ExpenseReportPage.xaml      # Page détail des dépenses
├── ExpenseReportPage.xaml.cs   # Logique d'affichage des rapports
└── watermark.png               # Image de fond
```

---

## 👨‍💻 Auteur

Développé par **Rémi Gentil**  
🎓 Étudiant en **BUT Informatique – 3ᵉ année**  
📍 IUT de Bayonne – Université de Pau et des Pays de l’Adour  
💼 Alternant Assistant Développeur d’applications – The Gill Corporation France


## 📩 Contact

📧 [rgentil@thegillcorp.fr](mailto:rgentil@thegillcorp.fr)  
🔗 [LinkedIn](https://www.linkedin.com/in/remi-gentil) • [GitHub](https://github.com/remi-gntl)

---

> Ce projet a été réalisé dans le cadre de l'apprentissage du framework WPF et des technologies .NET.
