# Apple Developer Setup für Codemagic

## 🔧 Signing Fehler beheben

### Fehler: "Signing for App requires a development team"

Das bedeutet, Codemagic hat keinen Zugriff auf deinen Apple Developer Account.

## 🎯 Lösung:

### 1. Apple Developer Account hinzufügen:
1. **Codemagic → Settings → Native Credentials**
2. **"Add new" → "Apple Developer"**
3. **Apple ID und Passwort eingeben**
4. **2FA Code eingeben** (falls aktiviert)

### 2. Certificates & Provisioning:
1. **"Add new" → "iOS Certificate"**
2. **Development oder Distribution Certificate hochladen**
3. **"Add new" → "Provisioning Profile"**
4. **Ad-Hoc Profile hochladen**

### 3. Automatische Alternative:
Falls du keine Zertifikate hast:
- **Codemagic kann automatisch erstellen**
- **"Automatic signing"** auswählen
- **Apple Developer Account wird verbunden**

## 📱 Benötigte Daten:
- **Apple ID** (Developer Account)
- **Passwort** 
- **2FA Code** (wenn aktiviert)
- **Team ID** (optional)

## ⚡ Quick Fix:
1. **Developer Account verbinden**
2. **Build neu starten**
3. **crypto.ipa downloaden**

## 🆘 Ohne Developer Account:
- **Web App Installation** (kostenlos)
- **AltStore** (kostenlos)
- **Freunde mit Developer Account fragen**

Das ist das letzte Hindernis - danach kriegst du deine .ipa! 🚀
