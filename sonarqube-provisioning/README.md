# Sonarqube Provision

## Informations
- **Desired Version:** https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-9.6.1.59531.zip

## Deploy With OC Commands

	oc new-project oqss-cicd
	oc import-image dferreira/sonarqube:7.9.1 --from=quay.io/dferreira/sonarqube:7.9.1 --confirm
		
