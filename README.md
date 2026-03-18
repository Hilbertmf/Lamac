Códigos feitos no Lamac

activate env:
source .venv/bin/activate

Set identity:
git config user.name "Your Name"
git config user.email "your@email.com"

credential cache:
git config --global credential.helper 'cache --timeout=56700'

You'll be asked your Personal Access Token (PAT) when committing
To create one:
Github > Settings > Developer settings > Personal acess token > classic


Rodar todo dia antes de codar:
source .venv/bin/activate
git config user.name "hilbertmf"
git config user.email "hilbertmf@gmail.com"
git config --global credential.helper 'cache --timeout=56700'
git push

Clean up:
git credential-cache exit