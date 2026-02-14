# 🍼 Συνταγές Βρεφικής Τροφής – Philips Avent 4-in-1

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://michelis2023.github.io/syntages-morou/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📖 Περιγραφή

**Συνταγές Βρεφικής Τροφής** είναι μια διαδραστική, responsive ιστοσελίδα με πλήρη συλλογή συνταγών για βρέφη και νήπια, σχεδιασμένη για τη συσκευή **Philips Avent Premium 4-in-1 Steamer Blender (SCF883/01)**.

Η εφαρμογή παρέχει:
- ✅ Συνταγές οργανωμένες ανά ηλικιακή ομάδα (6+, 7–9, 10–12 μηνών)
- ✅ Ενδεικτικούς χρόνους ατμού και προτεινόμενες υφές
- ✅ Πληροφορίες για θρεπτική αξία, αποθήκευση και ασφάλεια
- ✅ Dark mode με αυτόματη αποθήκευση προτιμήσεων
- ✅ Πλήρως responsive σχεδιασμό για κινητά και tablets
- ✅ Εύκολη πλοήγηση με sticky navigation bar

---

## 🚀 Live Demo

👉 [Δείτε τη σελίδα εδώ](https://michelis2023.github.io/syntages-morou/)

---

## ✨ Χαρακτηριστικά

### 🎨 Σχεδιασμός & UX
- **Modern & Clean Interface**: Σύγχρονη διεπαφή με καρτέλες συνταγών και εύκολη ανάγνωση
- **Dark Mode**: Αυτόματη εναλλαγή φωτεινού/σκοτεινού θέματος με διατήρηση προτίμησης στο `localStorage`
- **Responsive Design**: Βελτιστοποιημένο για desktop, tablet και mobile συσκευές
- **Accessibility**: Σημασιολογικό HTML5 και ARIA attributes για προσβασιμότητα

### 📱 Λειτουργικότητα
- **Sticky Navigation**: Μενού πλοήγησης που παραμένει ορατό κατά το scrolling
- **Mobile Menu**: Hamburger menu για κινητές συσκευές με smooth animations
- **Smooth Scrolling**: Ομαλή μετάβαση μεταξύ των sections
- **Grid Layout**: Responsive grid για τις συνταγές που προσαρμόζεται στο μέγεθος οθόνης

### 📋 Περιεχόμενο
- **25+ Συνταγές**: Πολτοί, κυρίως γεύματα, επιδόρπια και σνακ
- **Πίνακες Αναφοράς**: Χρόνοι ατμού και προτεινόμενες υφές ανά ηλικία
- **Συμβουλές Ασφάλειας**: Οδηγίες αποθήκευσης, υγιεινής και διαχείρισης αλλεργιών
- **Θρεπτικές Πληροφορίες**: Επισημάνσεις για βιταμίνες, μέταλλα και θρεπτικά συστατικά

---

## 🛠️ Τεχνολογίες

- **HTML5**: Σημασιολογική δομή με meta tags για SEO
- **CSS3**: 
  - CSS Custom Properties (CSS Variables) για theming
  - Flexbox & CSS Grid για layouts
  - Media queries για responsive design
  - Smooth transitions & animations
- **Vanilla JavaScript**: 
  - Theme toggle με localStorage persistence
  - Mobile navigation με smooth interactions
  - Χωρίς dependencies (no frameworks/libraries)

---

## 📂 Δομή Project

```
syntages-morou/
├── index.html          # Κύριο αρχείο HTML με όλες τις συνταγές
└── README.md           # Αυτό το αρχείο
```

---

## 🚀 Εγκατάσταση & Χρήση

### Τοπική Εκτέλεση

1. **Clone το repository**:
   ```bash
   git clone https://github.com/Michelis2023/syntages-morou.git
   cd syntages-morou
   ```

2. **Άνοιγμα στον browser**:
   - Απλά ανοίξτε το αρχείο `index.html` σε οποιονδήποτε σύγχρονο browser
   - Ή χρησιμοποιήστε ένα local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Node.js (με npx)
     npx http-server
     ```
   - Επισκεφτείτε: `http://localhost:8000`

### Deployment σε GitHub Pages

Το project είναι ήδη deployed στο GitHub Pages. Για να το κάνετε εσείς:

1. Πηγαίνετε στο **Settings** του repository
2. Επιλέξτε **Pages** από το αριστερό μενού
3. Στο **Source**, επιλέξτε τον κλάδο `main` και το φάκελο `/ (root)`
4. Πατήστε **Save**
5. Η σελίδα θα είναι διαθέσιμη σε λίγα λεπτά στο:
   ```
   https://michelis2023.github.io/syntages-morou/
   ```

---

## 📖 Οδηγός Χρήσης

### Πλοήγηση
- Χρησιμοποιήστε το **navigation bar** για γρήρη μετάβαση σε κάθε ηλικιακή κατηγορία
- Στα κινητά, πατήστε το **hamburger icon** (☰) για να δείτε το πλήρες μενού
- Κάντε κλικ στο **toggle button** (☀️/🌙) για εναλλαγή φωτεινού/σκοτεινού θέματος

### Συνταγές
Κάθε συνταγή περιλαμβάνει:
- **Τίτλος** και **ηλικιακή ομάδα**
- **Αριθμός μερίδων** και **χρόνος ατμού**
- **Υλικά** με ακριβείς ποσότητες
- **Βήματα εκτέλεσης** με σαφείς οδηγίες
- **Θρεπτικές πληροφορίες** για κάθε συνταγή

### Πίνακες Αναφοράς
- **Χρόνοι ατμού**: Ενδεικτικοί χρόνοι για κάθε τύπο τροφίμου
- **Υφή ανά ηλικία**: Προτεινόμενη υφή πολτού από 6 έως 12+ μηνών

---

## 🎯 Χρήση με το Philips Avent 4-in-1

### Βασικές Οδηγίες
1. **Προετοιμασία**: Κόψτε τα υλικά σε κύβους ~1 cm
2. **Ατμομαγείρεμα**: Γεμίστε τη δεξαμενή νερού και ρυθμίστε τον χρόνο
3. **Μπλένταρισμα**: Αναποδογυρίστε την κανάτα και μπλεντάρετε σε παλμούς
4. **Σερβίρισμα**: Ελέγξτε τη θερμοκρασία πριν σερβίρετε

### Συντήρηση
- Πλένετε την κανάτα και τη λεπίδα μετά από κάθε χρήση
- Καθαρίζετε την δεξαμενή νερού τακτικά
- Αποψαλτώνετε όπου χρειάζεται

---

## 📊 Browser Support

Η εφαρμογή υποστηρίζει όλους τους σύγχρονους browsers:

| Browser | Version |
|---------|--------|
| Chrome  | ≥ 90   |
| Firefox | ≥ 88   |
| Safari  | ≥ 14   |
| Edge    | ≥ 90   |

---

## 🤝 Συνεισφορά

Οι συνεισφορές είναι ευπρόσδεκτες! Αν έχετε ιδέες για βελτιώσεις:

1. **Fork** το repository
2. Δημιουργήστε ένα **feature branch**:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit** τις αλλαγές σας:
   ```bash
   git commit -m 'feat: Προσθήκη νέας συνταγής'
   ```
4. **Push** στο branch:
   ```bash
   git push origin feature/amazing-feature
   ```
5. Ανοίξτε ένα **Pull Request**

### Ιδέες για Συνεισφορά
- 🍽️ Προσθήκη νέων συνταγών
- 🌐 Μετάφραση σε άλλες γλώσσες
- 🎨 Βελτιώσεις στο design
- 🐛 Bug fixes
- 📖 Βελτίωση documentation

---

## 📝 Άδεια Χρήσης

Αυτό το project διατίθεται υπό την **MIT License**. Δείτε το αρχείο [LICENSE](LICENSE) για περισσότερες πληροφορίες.

---

## 🔗 Χρήσιμοι Σύνδεσμοι

- [Philips Avent SCF883/01 Official Page](https://www.philips.gr/c-p/SCF883_01/premium-4-in-1-steamer-blender)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [MDN Web Docs](https://developer.mozilla.org/)

---

## 👤 Συγγραφέας

**Michalis**
- GitHub: [@Michelis2023](https://github.com/Michelis2023)
- Repository: [syntages-morou](https://github.com/Michelis2023/syntages-morou)

---

## 📞 Επικοινωνία & Υποστήριξη

Για ερωτήσεις, προτάσεις ή αναφορά προβλημάτων:
- Ανοίξτε ένα [Issue](https://github.com/Michelis2023/syntages-morou/issues)
- Επικοινωνήστε μέσω GitHub

---

## ⚠️ Αποποίηση Ευθύνης

> **Σημαντική Σημείωση**: Οι συνταγές και οι οδηγίες σε αυτή τη σελίδα είναι ενδεικτικές και βασίζονται σε γενικές κατευθύνσεις της Philips Avent. Πριν εισάγετε νέες τροφές στη διατροφή του βρέφους σας, **συμβουλευτείτε πάντα τον παιδίατρό σας**. Κάθε παιδί είναι μοναδικό και μπορεί να έχει διαφορετικές διατροφικές ανάγκες ή αλλεργίες.

---

## 🙏 Ευχαριστίες

- Philips Avent για τις επίσημες οδηγίες και συνταγές
- Η κοινότητα γονέων για τα σχόλια και τις προτάσεις
- Όλοι όσοι συνεισφέρουν στη βελτίωση του project

---

<div align="center">

**Φτιαγμένο με ❤️ για τα μωρά μας**

⭐ Αν σας φάνηκε χρήσιμο, αφήστε ένα star!

[⬆ Επιστροφή στην κορυφή](#-συνταγές-βρεφικής-τροφής--philips-avent-4-in-1)

</div>