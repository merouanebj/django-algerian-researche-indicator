# Les Etablisement

CERIST
chef etablisement email="badache@mail.cerist.dz",password= "badache123"
Researcher.objects.create_user(email="badache@mail.cerist.dz",password= "badache123",last_name="BADACHE",first_name="Nadjib", grade="DR",google_scholar_account= "https://scholar.google.com/citations?hl=en&user=P77h8G8AAAAJ")

Les Division

## DSISM chef Division rachid aliradi

password = aliradi123 email = "raliradi@mail.cerist.dz"
"last_name": "",
    "first_name": "",
    "grade": "A.R",
    "division": "DSISM",
    "google_scholar_account": 
Equipe Systèmes d'information et image en Santé S2IS - (chef d'équipe) Abdelkrim MEZIANE
Equipe Systèmes d'information et image en Santé S2IS - (chef d'équipe) Abdelkrim MEZIANE
    "email": ,
Researcher.objects.create_user(email="raliradi@mail.cerist.dz",password="rachid123", last_name ="ALIRADI" ,first_name="Rachid", google_scholar_account="https://scholar.google.com/citations?hl=en&user=vLBwNvwAAAAJ")
Researcher.objects.create_user(email="meziane@gmail.com",password="abdelkrim123", last_name ="MEZIANE" ,first_name="Abdelkrim", google_scholar_account="https://scholar.google.com/citations?hl=en&user=x4OzPQcAAAAJ")
Researcher.objects.create_user(email="aouaa@gmail.com",password="noureddine123", last_name ="AOUAA" ,first_name="Noureddine", google_scholar_account="https://scholar.google.com/citations?hl=en&user=LgCh4kAAAAAJ")
Researcher.objects.create_user(email="hadjadj@gmail.com",password="zineb123", last_name ="HADJADJ" ,first_name="Zineb", google_scholar_account="https://scholar.google.com/citations?hl=en&user=o5rk7VAAAAAJ")
Researcher.objects.create_user(email="setitra@gmail.com",password="insaf123", last_name ="SETITRA" ,first_name="Insaf", google_scholar_account="https://scholar.google.com/citations?hl=en&user=FlJ2v-sAAAAJ")

Researcher.objects.create_user(email="nboulkrinat@mail.cerist.dz",password="nourelhouda123", last_name ="boulkrinat" ,first_name="Nour el houda", google_scholar_account="https://scholar.google.com/citations?hl=ar&user=pwfr0DgAAAAJ")

### Interaction et routage dans les systèmes d’information

Chef Mellah hakima email="hmellah@mail.cerist.dz"
password="hakima123"
Researcher.objects.create_user(email="hmellah@mail.cerist.dz",password="hakima123", last_name ="mellah" ,first_name="hakima", google_scholar_account="https://scholar.google.com/citations?user=WEiBJsMAAAAJ&hl=fr&oi=ao")

## Division Recherche et Développement en Sciences de l'Information et Humanités Numériques DRDHN

Chef Division hassina aliane email='haliane@mail.cerist.dz',
Researcher.objects.create_user(email='haliane@mail.cerist.dz',password="hassina123",last_name='ALIANE', first_name='Hassina', grade='M.R.B', google_scholar_account="https://scholar.google.com/citations?hl=en&user=VOkaVCMAAAAJ")

### Traitement Automatique des Langues et Contenus Numériques
Chef Aliane hassina
Les members
Researcher.objects.create_user(email="mchaa@cerist.dz",password="chaa123",last_name = "Chaa", first_name = "Messaoud", google_scholar_account = "https://scholar.google.com/citations?hl=en&user=M64Rs8UAAAAJ", equipe_researchers_id = 1)
Researcher.objects.create_user(email="lchalabi@cerist.dz",password="chalabi123",last_name = "Chalabi", first_name = "Lydia",google_scholar_account = "https://scholar.google.com/citations?hl=en&user=cQzs_JQAAAAJ", equipe_researchers_id = 1)
Researcher.objects.create_user(email="nleila@mail.cerist.dz",password="nouri123",last_name = "Nouri", first_name = "Leila",google_scholar_account = "https://scholar.google.com/citations?hl=en&user=FqKD0NcAAAAJ", equipe_researchers_id = 1)








# Etablisement CDER Dz 
 Directeur : 
  email="a.hadjarab@cder.dz" password = "amar123"
  first_name = "amar" last_name = "hadj-arab" speciality = "Energies Renouvelables"
  grade = "directeur"
  google_scholar_account = "https://scholar.google.com/citations?hl=en&user=UCrtS_oAAAAJ"

## Divisions 
1. Division Energie Solaire Thermique et Thermodynamique Solaire
* chef :
`email ="s.ouali@cder.dz" password = "salima123" ,first_name = "Salima" ,last_name = "Ouali", speciality="Géothermie",google_scholar_account = "https://scholar.google.com/citations?hl=en&user=RRyeMSoAAAAJ"`
2. Division Energie Eolienn
* chef  Ouahiba Guerri
`email="o.guerri@cder.dz", password="ouhiba123", first_name = "Ouahiba" , last_name ="Guerri", google_scholar_account="https://scholar.google.com/citations?hl=en&user=JUOmDDsAAAAJ", speciality = " Wind Energy" `


query all etablisements researcher who arent leads
Researcher.objects.filter(equipe_researchers__division__etablisment__id=1)