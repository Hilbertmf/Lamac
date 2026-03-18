Códigos feitos no Lamac

Set identity:
git config user.name "Your Name"
git config user.email "your@email.com"

credential cache:
git config --global credential.helper 'cache --timeout=56700'

You'll be asked your Personal Access Token (PAT) when committing
To create one:
Github > Settings > Developer settings > Personal acess token > classic

Clean up:
git credential-cache exit