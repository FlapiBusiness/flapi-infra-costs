# Flapi - Infrastructure pricing

## Services OVH - Internal

| Service                                   | Frais mensuels |
|-------------------------------------------|----------------|
| **VPS (6)**                               | 28,60€         |
| **Server dédié (1)**                      | 59,99€         |

**Remarque** : Server dédié à supprimer de chez OVH plus tard, en attendant d'avoir les moyens pour louer plutôt des instances EC2 AWS, à la place !

<br />

---

## Services AWS - Internal

| Service                         | Frais fixes mensuels | Frais par Go                    | Coût pour 1 000 Go | Total (Frais fixes + 1000Go) |
|---------------------------------|----------------------|---------------------------------|--------------------|------------------------------|
| **Network Load Balancer**       | 19,44 USD x 1 actuellement | 0,006 USD/Go                    | 6,00 USD           | 25,44 USD                    |
| **Global Accelerator**          | 18 USD x 1 actuellement    | 0,015 USD/Go                    | 15 USD             | 33,00 USD                    |
| **EC2 Trafic Sortant**          | -                          | 100 Go gratuits, puis 0,09 USD/Go | 81 USD           | 81,00 USD                    |
| **AWS Route 53 (HostedZone)**   | 0.50 USD x 1 (par Hosted Zone)       | - | - | - |
| **AWS Route 53 (DNS-Queries)**  | 0.40 USD per 1,000,000 queries       | - | - | - |
| **AWS Route 53 (Health Checks)**| 0.75 USD per Health Check for Health Checks of non-AWS endpoints (0.75 x 2 actuellement) | - | - | - |
| **Nom de domaine**          | 14 USD (14$ par domaine x 1 par an actuellement) | - | - | - |

**Remarque** : 
- Les coûts des services AWS peuvent varier en fonction de la région et de l'utilisation réelle des ressources. Il est recommandé d'utiliser le calculateur de tarification AWS pour obtenir une estimation plus précise en fonction des besoins spécifiques.
- Il y a budget qui à était créer dans AWS pour surveiller si on ne dépasse pas le budget, voici comment ça marche : Vous serez informé 1) lorsque vos dépenses réelles atteignent 85 % 2) lorsque vos dépenses réelles atteignent 100 % 3) si vos dépenses prévues devraient atteindre 100 %.

<br />

---

## Services Others - Internal

| Service                                  | Frais annuel    | Frais mais à vie |
|------------------------------------------|-----------------|------------------|
| **DockerHub Pro**                        | 60€             | -                |
| **Gitkraken**                            | 60€             | -                |
| **ChatGPT**                              | 260€            | -                |
| **Github Entreprise**                    | 240€            | -                |
| **O2Switch**                             | 105€            | -                |
| **Apple licence**                        | 100€            | -                |
| **Android licence**                      | -               | 25€              |
| **Certificat de signature de code Windows - Azure Key Vault** | 590€   | -                |
| **NPM Pro**                              | 120€            | -                |

<br />

---

## Clients
| Client             | Applications          | Domaine               |
|--------------------|-----------------------|-----------------------|
| Client A	         | App Restaurent	       | restaurent.flapi.org	 |
