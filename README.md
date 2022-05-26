# Churn_Telecom

*(Business Case Training Quest Wild Code School (in French))*

## Problématique

Le client est "Pinky" une entreprise de télécommunication, qui vend des forfaits téléphonique et internet. Ses clients sont donc abonnés, et paient mensuellement. Mais chaque mois, des clients résilient leur abonnement, c'est ce qu'on appelle le taux d'attrition (churn rate en anglais). C'est un indicateur très employé dans tous les secteurs avec des abonnements (télécom, énergie, banque, assurance, etc...).

Pinky dispose d'une plateforme d'appel, avec des conseillers. Les conseillers peuvent appeler les clients pour leur faire des propositions commerciales. Pinky a remarqué qu'il est presqu'impossible de faire revenir un client qui a résilié. Il préfère donc faire des propositions commerciales aux clients "à risque", avant qu'ils ne résilient.

C'est pourquoi Pinky fait appel à toi ! Pinky te fournit une extraction d'un échantillon représentatif de sa base client, dont des clients qui ont résilié ce mois-ci. Ton but va être de décrire les caractéristiques des clients ayant résilié et ce qui les distingue des autres clients. Puis tu devras proposer un scoring pour chaque client, afin de prioriser les appels vers les clients les plus à risque.

## Challenge

Calcul le taux d'attrition (nombre de résiliations / nombre total de clients), puis effectue l'analyse demandée, avec des visualisations explicatives, et propose un scoring par client.

Tu trouveras l'échantillon de la base client ici.

Nous te laissons libre d'y répondre à ta manière. La créativité, l'intuition, la faculté de s'imaginer à la place du client, sont des compétences très importantes dans nos métiers.

## Signification des colonnes

customerID: Customer ID
genderCustomer: gender (female, male)
SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
Partner : Whether the customer has a partner or not (Yes, No)
Dependents: Whether the customer has dependents or not (Yes, No)
tenure: Number of months the customer has stayed with the company
PhoneService: Whether the customer has a phone service or not (Yes, No)
MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
InternetService: Customer’s internet service provider (DSL, Fiber optic, No)
OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service)
OnlineBackup: Whether the customer has online backup or not (Yes, No, No internet service)
DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
TechSupport: Whether the customer has tech support or not (Yes, No, No internet service)
StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service)
Contract: The contract term of the customer (Month-to-month, One year, Two year)
PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
MonthlyCharges: The amount charged to the customer monthly
TotalCharges: The total amount charged to the customer
Churn: Whether the customer churned or not (Yes or No)
