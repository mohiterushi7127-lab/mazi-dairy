माझी डेअरी — Firebase Cloud Version

या आवृत्तीत:
- Email/Password Firebase Login
- Firebase Cloud Firestore
- एकाच account मधून phone/computer वर same data
- जनावरे, दूध, खर्च cloud मध्ये
- जुन्या localStorage prototype data चे first-login migration
- गायचे फोटो compress करून animal record मध्ये save
- Marathi colorful dashboard

सेटअप:
1. Firebase Authentication मध्ये Email/Password ON करा.
2. Firestore Database तयार करा.
3. FIREBASE_RULES.txt मधील rules Firestore → Rules मध्ये Publish करा.
4. Website ला hosting वर चालवा (उदा. Firebase Hosting किंवा दुसरे HTTPS hosting).
5. नवीन account तयार करा किंवा login करा.

टीप:
- Firebase config web app मध्ये ठेवणे सामान्य आहे; private service-account keys कधीही frontend मध्ये ठेवू नका.
- हा version Firestore subcollections वापरतो: users/{uid}/animals, milk, expenses.
