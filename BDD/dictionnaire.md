# Dictionnaire des données

## Projet

### Entité chantier

| Libellé de la propriété | Nom du champ | Type |
| ----------------------- | ------------ | ---- |
| Identifiant             | CHA_ID       | N    |
| Référence               | CHA_REF      | AN   |
| Nom                     | CHA_NOM      | S    |
| Date                    | CHA_DATE     | DATE |

### Entité produit

| Libellé de la propriété | Nom du champ | Type |
| ----------------------- | ------------ | ---- |
| Identifiant             | PRO_ID       | N    |

### Entité gamme

| Libellé de la propriété | Nom du champ | Type |
| ----------------------- | ------------ | ---- |
| Identifiant             | GAM_ID       | N    |
| Nom                     | GAM_NOM      | S    |

### Entité modèle de gamme

| Libellé de la propriété | Nom du champ | Type |
| ----------------------- | ------------ | ---- |
| Identifiant             | MOD_GAM_ID   | N    |
| Nom                     | MOD_GAM_NOM  | S    |

### Entité module

| Libellé de la propriété | Nom du champ | Type |
| ----------------------- | ------------ | ---- |
| Identifiant             | MOD_ID       | N    |
| Nom                     | MOD_NOM      | S    |

### Entité section

| Libellé de la propriété | Nom du champ | Type |
| ----------------------- | ------------ | ---- |
| Identifiant             | SEC_ID       | N    |
| Numéro                  | SEC_NUM      | N    |
| Longueur                | SEC_LONGUEUR | N    |
| Angle                   | SEC_ANGLE    | S    |
| Degrée angle            | SEC_DEGREE   | N    |

## Client

### Entité Client

| Libellé de la propriété | Nom du champ | Type |
| ----------------------- | ------------ | ---- |
| Identifiant             | CLI_ID       | N    |
| Nom                     | CLI_NOM      | S    |
| Prénom                  | CLI_PRENOM   | S    |
| Mail                    | CLI_MAIL     | S    |
| Téléphone               | CLI_TEL      | S    |

### Entité Code postal

| Libellé de la propriété | Nom du champ    | Type |
| ----------------------- | --------------- | ---- |
| Code commune            | CPT_COMMUNE     | N    |
| Code postal             | CPT_CODEPOST    | N    |
| Code département        | CPT_DEPARTEMENT | N    |
| Code Insee              | CPT_INSEE       | N    |

### Entité Adresse

| Libellé de la propriété | Nom du champ    | Type |
| ----------------------- | --------------- | ---- |
| Identifiant             | ADR_ID          | N    |
| Numéro de la voie       | ADR_NUM_VOIE    | N    |
| Libellé de la rue       | ADR_LIBELLE_RUE | S    |
| Ville                   | adr_ville       | S    |
