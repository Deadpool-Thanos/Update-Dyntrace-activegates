# Update-Dyntrace-activegates
This ansible playbook helps in updating dyntace activegates by using API calls.

Create a vault file [ault_api_key.yml] with var "api_key" to securely store thr apikey. 

command to run playbook: ansible-playbook activegates_playbook.yml --ask-vault-pass -e "@vault_api_key.yml"
