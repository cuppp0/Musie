# 1. Vá até a pasta onde está o arquivo HTML (mude o caminho conforme necessário)
cd /caminho/para/sua/pasta

# 2. Inicialize um repositório Git
git init

# 3. Adicione o repositório remoto (copie a URL do GitHub, por exemplo: https://github.com/seuusuario/bonus-site.git)
git remote add origin https://github.com/seuusuario/bonus-site.git

# 4. Adicione o arquivo
git add bonus_mini_site.html

# 5. Faça o commit
git commit -m "Site com bônus de cadastro"

# 6. Envie para o GitHub
git push -u origin master
