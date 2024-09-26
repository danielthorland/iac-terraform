# Oblig1 IIKG3001?

## Hvordan kjøre Terraform scripts:
- skriv inn i terminal, pass på at du står i root folder av prosjektet
- "terraform -plan -ount=main.tfplan" er bare nødvendig å kjøre når en har endret på koden og skal lage en ny plan.
- komandoer:
    - terraform init
    - terraform plan -out=main.tfplan
    - terraform apply "main.tfplan"
- For å ta ned alle ressursene:
    - terraform destroy

## Hvordan endre på programmet:
- alle variabler kan endres i terraform.tfvars filen.
    - Om denne filen ikke eksisterer kan man lage en selv, og skrive inn hvilke variabler man vil endre på hentet fra variables.tf.
    - alle variabler er definert i variables.tf i root folder av prosjektet.
