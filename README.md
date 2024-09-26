# Oblig1 IIKG3001?

## Bruksanvisning:
- skriv inn i terminal, pass på at du står i root folder av prosjektet
- komandoer:
-    terraform init
-    terraform plan -out=main.tfplan
-    terraform apply "main.tfplan"
- For å ta ned alle ressursene:
-    terraform destroy

## Hvordan endre på programmet:
- alle variabler kan endres ved bruk av terraform.tfvars
- alle variabler er definert i variables.tf i root folder av prosjektet.
